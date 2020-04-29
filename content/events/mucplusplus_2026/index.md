---
title: "MUC++ Talk - Improving Developer Experience: A Practical Approach to IDE Support in Large-Scale C++ Projects using Bazel and VSCode"
event: MUC++
event_url: https://www.meetup.com/mucplusplus/events/314102093

location: Valantic
address:
  street: Birketweg 21
  city: Munich
  region: BY
  postcode: '80639'
  country: Germany

summary: Talk at MUC++ on how to maintain a developer environment with your build system
abstract: "In this talk, we present a methodology that ensures the exact same tools and toolchains managed by Bazel are also used by the local development environment and IDEs. By combining open-source projects such as bazel_env.bzl and bazel-compile-commands with clangd and VSCode, we create a setup that provides accurate and high-quality IDE support, even large and complex C++ codebases."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2026-04-23T19:25:00Z"
date_end: "2026-04-23T19:55:00Z"
all_day: false

publishDate: "2026-04-14T00:00:00Z"

authors:
- me
tags:
- Bazel
- IDE

# Is this a featured talk? (true/false)
featured: true

image:
  caption: ''
  focal_point: Right

links:
- name: code
  url: https://github.com/hofbi/bazel-ide
- type: event
  label: Related Talk
  url: events/bazelcon_2025_bazel_ide
---

Bazel is a powerful build system, especially well-suited for large-scale, multi-language codebases, which is actively used by companies such as Google, BMW, or Nvidia. However, its integration with C++ IDEs remains far from ideal. Unlike CMake, which offers mature IDE support out-of-the-box, Bazel’s limited IDE integration creates friction for developers who rely on features like auto-completion, cross-references, and debugging within tools like Visual Studio Code.

A possible explanation for this is that Bazel is typically used in very large-scale projects, where IDEs themselves often struggle to index the sheer size of the codebase. Additionally, since Bazel supports several programming languages, a general IDE support for all languages is hard to achieve. Projects such as https://github.com/build-server-protocol try to simplify this integration with an abstraction layer, but are not yet available.

Additionally, many IDEs and developers expect common command-line tools to be available in the system PATH, which leads to duplicated effort: one set of tools is managed within the build system, while another must be separately maintained for development use. This fragmentation leads to subtle inconsistencies, onboarding hurdles, and a degraded development experience.

In this talk, we present a practical solution to this problem: a methodology that ensures the exact same tools and toolchains managed by Bazel are also used by the local development environment and IDEs. By combining open-source projects such as bazel_env.bzl and bazel-compile-commands with clangd and VSCode, we create a setup that provides accurate and high-quality IDE support, even large and complex C++ codebases.

To illustrate this approach, we have open-sourced a demo project at https://github.com/hofbi/bazel-ide. Of particular note is the devcontainer environment, which shows that this workflow requires only git, bazel, and direnv to be installed locally while everything else is provided and managed by the build system.
