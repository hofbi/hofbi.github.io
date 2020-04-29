---
title: Review of State of the Art Solutions for IDE support and Developer Tooling in Monorepos using Bazel
event: BazelCon 2025
event_url: https://events.linuxfoundation.org/bazelcon/

location: Omni Atlanta Hotel at Centennial Park
address:
  street: 190 Marietta Street NW
  city: Atlanta
  region: GA
  postcode: '30303'
  country: United States of America

summary: "Talk at BazelCon 2025 reviewing existing solutions for IDE support and developer tooling in monorepos using Bazel."
abstract: "Many developers complain about lacking IDE when working with Bazel. They might not care about using `bazel run` to execute tools but want use their tools available on the `PATH`. Providing tools on the `PATH` in addition to the ones used by the build system leads to extra effort for the teams maintaining this. In this talk, we review existing solutions available in the Bazel ecosystem: First and foremost, Fabian’s project `bazel_env.bzl` which allows all developers to share the same tool versions as used in the Bazel build for IDEs and local usage. We demonstrate IDE support for C++ and Python in large monorepos by combining multiple projects such as hedronvision/bazel-compile-commands-extractor to generate a `compile_commands.json`, `hofbi/dev-tools` for the compile commands extractor to better scale with large codebases, and `clangd` to integrate with the IDE. To demonstrate all this, we have open-sourced a demo project at https://github.com/hofbi/bazel-ide. Of particular note is the devcontainer environment, which shows that this workflow requires only git, bazel, and `direnv` to be installed locally while everything else is provided and managed by the build system."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2025-11-10T12:10:00Z"
date_end: "2025-11-10T12:20:00Z"
all_day: false

publishDate: "2025-09-04T15:00:00Z"

authors:
- Florian Berchtold
- admin
tags:
- Bazel
- IDE

# Is this a featured talk? (true/false)
featured: true

image:
  caption: 'Image credit: [**BazelCon 2025**](https://events.linuxfoundation.org/bazelcon/)'
  focal_point: Right

links:
- name: Schedule
  url: https://bazelcon2025.sched.com/event/28lmK
- name: Certificate
- name: Pictures
- type: slides
- type: video
---
