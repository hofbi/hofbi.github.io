---
title: Why We Should Care About Test Execution Output in Safety-Critical Industries
event: BazelCon 2024
event_url: https://events.linuxfoundation.org/bazelcon/

location: Computer History Museum
address:
  street: 1401 N. Shoreline Blvd.
  city: Mountain View
  region: CA
  postcode: '94043'
  country: United States of America

summary: "Talk at BazelCon 2024 about why it would be important for safety-critical industries to have test execution output in the build graph."
abstract: "In highly regulated industries such as automotive, aviation, and medical, test artifacts are often essential for further reporting. Automotive SPICE (ASPICE) or AUTOSAR from the automotive field requires detailed, reproducible reporting on executed tests. Companies such as BMW or NVIDIA use Bazel to build their software. However, Bazel does not cache test execution output, but only that a test was executed. To address this, some companies have resorted to forking Bazel and implementing this feature on their own which causes maintenance overhead and impedes collaborative Bazel improvements. Our proposed solution is to treat the test binary as a tool and run it as part of the Bazel build phase. This way, we can depend on the test output for further processing such as skipping integration tests if unit tests fail, collecting output artifacts such as human-readable test reports and machine-readable coverage reports, as well as making coverage collection depend on test outputs. Thanks to Bazel’s caching, the test is not executed again in the test phase which makes this solution an acceptable tradeoff."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2024-10-15T17:00:00Z"
date_end: "2024-10-15T17:10:00Z"
all_day: false

publishDate: "2024-07-30T15:00:00Z"

authors:
- admin
tags:
- Bazel

# Is this a featured talk? (true/false)
featured: true

image:
  caption: 'Image credit: [**BazelCon 2024**](https://events.linuxfoundation.org/bazelcon/)'
  focal_point: Right

links:
- name: Schedule
  url: https://bazelcon2024.sched.com/event/1h6Sq
- icon: github
  icon_pack: fab
  name: Follow
  url: https://github.com/hofbi
url_code: ""
url_pdf: ""
url_slides: https://static.sched.com/hosted_files/bazelcon2024/c8/BazelCon24_Hofbauer.pdf
url_video: "https://youtu.be/Qg1CkDd1pVA?feature=shared"
---
