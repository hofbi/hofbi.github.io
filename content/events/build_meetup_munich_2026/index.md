---
title: IDE support and Developer Tooling in Monorepos using Bazel
event: Build Meetup Munich 2026
event_url: https://meetup.build/munich-2026

location: Salesforce
address:
  street: Erika-Mann-Straße 31
  city: Munich
  region: Bavaria
  postcode: '80636'
  country: Germany

summary: "Talk at the Build Meetup Munich 2026 about how to maintain IDE support and developer tooling in monorepos using Bazel"
abstract: "Many developers complain about lacking IDE when working with Bazel. They might not care about using `bazel run` to execute tools but want use their tools available on the `PATH`. Providing tools on the `PATH` in addition to the ones used by the build system leads to extra effort for the teams maintaining this. In this talk, we review existing solutions available in the Bazel ecosystem: First and foremost, Fabian’s project `bazel_env.bzl` which allows all developers to share the same tool versions as used in the Bazel build for IDEs and local usage. We demonstrate IDE support for C++ and Python in large monorepos by combining multiple projects such as hedronvision/bazel-compile-commands-extractor to generate a `compile_commands.json`, `hofbi/dev-tools` for the compile commands extractor to better scale with large codebases, and `clangd` to integrate with the IDE. To demonstrate all this, we have open-sourced a demo project at https://github.com/hofbi/bazel-ide. Of particular note is the devcontainer environment, which shows that this workflow requires only git, bazel, and `direnv` to be installed locally while everything else is provided and managed by the build system."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2026-05-11T17:15:00Z"
date_end: "2026-05-11T17:30:00Z"
all_day: false

publishDate: "2026-05-11T17:15:00Z"

authors:
- me
tags:
- Bazel
- IDE

# Is this a featured talk? (true/false)
featured: true

image:
  caption: 'Image credit: [**Build Meetup Munich**](https://meetup.build/munich-2026)'
  focal_point: Right

links:
- type: code
  url: https://github.com/hofbi/bazel-ide
- type: custom
  label: Event
  url: https://meetup.build/munich-2026
---
