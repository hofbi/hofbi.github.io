file_finder = find . -type f \( $(1) \) -not -path '*/build/*'

SLIDE_FILES = $(call file_finder,-name slide-deck.md)
SLIDE_FILES_LIGHT = $(call file_finder,-name slide-deck-light.md)

SLIDE_DECK_HTML = find build/* -type f -name slide-deck.html
BUILD_FOLDERS = find build/* -type d
BUILD_FILES = find build/* -type f

light_theme_slides:
	$(SLIDE_FILES) | xargs -I '{}' sh -c 'v={}; cp $$v $${v%.md}-light.md'
	$(SLIDE_FILES_LIGHT) | xargs sed -i '/class. invert/d'
	$(SLIDE_FILES_LIGHT) | xargs sed -i '/- invert/d'

.PHONY: slides
slides: light_theme_slides
	mkdir -p build && cp -r slides/images build/
	docker compose run -e MARP_USER=$(shell id -u):$(shell id -g) generate --input-dir ./slides
	docker compose run -e MARP_USER=$(shell id -u):$(shell id -g) generate --input-dir ./slides --pdf

deploy:
	mkdir -p ../public/marp-slides/
	$(BUILD_FOLDERS) | xargs chmod --reference=slides
	$(BUILD_FILES) | xargs chmod --reference=docker-compose.yml
	$(SLIDE_DECK_HTML) | xargs -I '{}' sh -c 'f={}; mv -- $$f $${f%slide-deck.html}index.html' \;
	cp -r build/* ../public/marp-slides/
