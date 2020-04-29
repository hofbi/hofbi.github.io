---
title: Autogenerate your Build System - A Bazel Migration To Fully Ephemeral BUILD Files
event: Bay Area Build Meetup 2024
event_url: https://docs.google.com/forms/d/e/1FAIpQLSex7cHtqULL5_QzSSJRuVUwEKvTuCR6HEC8Os9MqfTln3qiyA/viewform

location: Meta
address:
  street: Facebook Building 14, 14 Hacker Wy
  city: Menlo Park
  region: CA
  postcode: '94025'
  country: United States of America

summary: "Talk at the Bay Area Build Meetup 2024 about Luminar's Bazel migration strategy using fully ephemeral BUILD files"
abstract: "We present Luminar's Bazel migration from a custom build system based on the C++ package manager Conan to Bazel. Our focus is on leveraging the tool Gazelle for automatic build file generation which enables us to have fully ephemeral BUILD files, which are not being tracked in version control. Additionally, we use Nix as a package manager for seamless management of all C++ toolchains and the inclusion of third-party dependencies that are not trivial to compile with Bazel. We will also share our experience during and after the migration with this unique approach of using ephemeral BUILD files integrated in a regular Bazel workspace . This method enabled us to operate both the legacy and new build systems simultaneously for approximately a year, without imposing additional burdens on developers or exerting undue pressure on the migration team. First, we briefly discuss our existing build system based on Conan and motivate why we migrate to Bazel. Then, we present our step-by-step approach, offering valuable insights and lessons learned from the ongoing migration process, as seen from both a developer's and a Bazel migration team's perspective. Key components of our migration strategy are explored, beginning with the implementation of our own C++ language extension for Gazelle. We explain how Gazelle automates the creation of Bazel BUILD files exclusively based on a standardized file and folder structure. In our case, this structure was already defined by our Conan packages. This allows us not only to migrate our codebase once from Conan to Bazel, but also to continuously maintain our Bazel BUILD files in a consistent way. Our methodology carries numerous advantages. Auto-generating our build targets eliminates the overhead for developers in managing a multitude of targets. It also reduces the need for Bazel experts to teach developers, as many won't interact directly with BUILD files. Adherence to Bazel's best practices becomes easier, aiming for the smallest possible targets to fully exploit Bazel's parallelization. Significant changes to the build system, typically requiring large scale changes across the codebase, can be implemented seamlessly, without disrupting the developers’ workflow. An example of such a large-scale change was a refactoring on how we specify copts, which we implemented by only changing the code at a single place rather than touching every BUILD file. Finally, the fact that BUILD files are not tracked in version control promotes a cleaner and more efficient development process, eliminating unnecessary clutter and reducing the risk of conflicts. Finally, we delve into the integration of the Nix package manager with Bazel, showcasing how it simplifies the inclusion of third-party dependencies that are not trivial to compile natively with Bazel such as QNX. This integration enhances our workflow, providing a seamless approach to managing and distributing external packages. Attendees will gain valuable insights from our migration strategy. We will share benefits and lessons learned of running Gazelle and Nix in conjunction with Bazel in production for more than a year. We hope this can kick off further efforts in creating an open-source C++ language extension for Gazelle."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2024-10-16T10:30:00Z"
date_end: "2024-10-16T10:45:00Z"
all_day: false

publishDate: "2024-10-09T15:00:00Z"

authors:
- admin
tags:
- Bazel
- Gazelle
- Go

# Is this a featured talk? (true/false)
featured: true

image:
  caption: ''
  focal_point: Right

links:
- type: custom
  label: Event
  url: https://docs.google.com/forms/d/e/1FAIpQLSex7cHtqULL5_QzSSJRuVUwEKvTuCR6HEC8Os9MqfTln3qiyA/viewform
---
