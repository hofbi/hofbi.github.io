---
title: "A Bazel Story: Cargo Splicing and the Three Lockfiles"
event: BazelCon 2025
event_url: https://events.linuxfoundation.org/bazelcon/

location: Omni Atlanta Hotel at Centennial Park
address:
  street: 190 Marietta Street NW
  city: Atlanta
  region: GA
  postcode: '30303'
  country: United States of America

summary: "Talk at BazelCon 2025 summarizing the core problem of cargo splicing, exploring our recent solutions to decouple internal deps, and generating a stable Cargo.bazel.lock file to improve developer experience in large Rust codebases using Bazel via `rules_rust`."
abstract: "In large Rust codebases, `rules_rust`’s `crate_universe` rule uses cargo to resolve dependencies and generate build targets. This involves cargo splicing - merging cargo manifests and computing the full rust dependency graph. However, on large projects, splicing is required to run on almost every workspace related change and it can take several minutes, slowing down workflows significantly. The root cause is cargo storing both internal and external dependencies in the same `Cargo.lock` file. Bazel's lockfile could help to avoid repeated splicing, but introduces a new bottleneck: the checksum of the `Cargo.lock` file is embedded in `MODULE.bazel.lock`. Any change to internal dependencies - even unrelated to third-party crates - alters the `Cargo.lock` hence the checksum in the `MODULE.bazel.lock`. This leads to widespread and unnecessary merge conflicts across large codebases. In this talk, we’ll summarize the core problem, cargo not separating first-party and third-party code in their metadata, and explore our recent solutions in `rules_rust` to decouple internal deps, generate a stable `Cargo.bazel.lock`, and improve developer experience in large Rust codebases using Bazel via `rules_rust`."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2025-11-11T12:00:00Z"
date_end: "2025-11-11T12:10:00Z"
all_day: false

publishDate: "2025-09-04T15:00:00Z"

authors:
- admin
tags:
- Bazel
- Rust

# Is this a featured talk? (true/false)
featured: true

image:
  caption: 'Image credit: [**BazelCon 2025**](https://events.linuxfoundation.org/bazelcon/)'
  focal_point: Right

links:
- name: Schedule
  url: https://bazelcon2025.sched.com/event/28lP0
- name: Certificate
- name: Pictures
- type: slides
- type: video
---
