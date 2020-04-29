---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Senior Build Engineer
          company: Luminar Technologies
          company_url: https://www.luminartech.com/
          company_logo: org-luminar
          location: Munich
          date_start: "2022-12-01"
          date_end: ""
          description: |
            * Tech Lead of the Build and Release Engineering Team
            * Developing and maintaining a monorepo build system, developer tooling, and release automation to support a fast and reliable product development process
            * Coaching software engineering teams to improve their developer productivity and code quality
        - title: Associate Lecturer
          company: Technical University of Munich - Chair of Media Technology
          company_url: https://www.ce.cit.tum.de/lmt
          company_logo: org-tum
          location: Munich
          date_start: "2022-07-01"
          date_end: ""
          description: |
            * Teaching software engineering principles to bachelor students in the field of electrical and computer engineering
            * Raise awareness of time and scale as important factors in professional software development
            * Focus on concepts of unit testing, refactoring, and automation tools for novices with basic programming experience
        - title: Senior Software Engineer
          company: CareX.AI
          company_url: https://carex.ai
          company_logo: org-carex
          location: Munich
          date_start: "2022-07-01"
          date_end: "2022-11-30"
          description: |
            * Leading software architecture and quality, developer tooling, and DevOps
            * Managing the Scrum team developing camera-based vital signs measurement
            * Conducting research about camera-based vital signs measurement
        - title: Research and Teaching Associate
          company: Technical University of Munich - Chair of Media Technology
          company_url: https://www.ce.cit.tum.de/lmt
          company_logo: org-tum
          location: Munich
          date_start: "2019-01-01"
          date_end: "2022-06-30"
          description: |
            * Doctoral candidate working on adaptive live video streaming for teleoperated driving
            * Research focused on video processing, compression, and transmission of multi-camera systems for autonomous and teleoperated driving
            * Teaching and supervision of more than 100 students in the field of electrical and computer engineering
        - title: IT-Consultant/Software Engineer
          company: Objective Software / Luxsoft
          company_url: https://www.luxoft.com/
          company_logo: org-luxoft
          location: Munich
          date_start: "2016-09-01"
          date_end: "2018-12-31"
          description: |
            * Software Engineer in the automotive industry contributing to six projects around autonomous driving in collaboration with BMW
            * Improving build automation for series production projects by implementing and integrating code generators into the build process
            * Feature development and vehicle integration of software components including localization, path planning, and remote communication
    design:
      columns: '2'
  - block: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: Honors, Awards & News
      subtitle:
      # Date format: https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - organization: International Association for Development of the Information Society
          organization_url: https://www.cgv-conf.org/
          title: Outstanding Paper Award at the CGVCVIP 2022
          url: ""
          certificate_url: ''
          date_start: '2022-07-25'
          date_end: ''
          description: |
            * Publication: [AR in VR: Augmented Reality Cues in 360-Degree Stereoscopic Telepresence for Remote Collaboration and Maintenance](/publication/ar_in_vr/)
            * News: [Chair of Media Technology](https://www.ce.cit.tum.de/en/lmt/news/article/outstanding-paper-award-at-the-cgvcvip-2022/)
        - organization: ITG-Fachausschuss MT 2 „Bildkommunikation und Bildverarbeitung“
          organization_url: https://www.vde.com/de/itg/arbeitsgebiete/fb3-medientechnik
          title: Joint Research Incubator Award 2022
          url: ""
          certificate_url: ''
          date_start: '2022-07-21'
          date_end: ''
          description: |
            * Publication: [Evaluation of Video Coding for Machines without Ground Truth](/publication/coding_for_machines/)
            * News: [Chair of Media Technology](https://www.ce.cit.tum.de/en/lmt/news/article/joint-research-incubator-award-2022-at-the-svcp2022/)
        - organization: IEEE Intelligent Transportation Systems Society
          organization_url: https://ieee-itss.org/
          title: Excellent Video Award at Transdisciplinary Mobility Innovation Education Video Competition
          url: https://takacoma.gitlab.io/tmi-educational-video-competition/
          certificate_url: ''
          date_start: '2021-08-11'
          date_end: ''
          description: |
            * Conference: [32nd IEEE Intelligent Vehicles Symposium](https://2021.ieee-iv.org/)
            * News: [Chair of Media Technology](https://www.ce.cit.tum.de/en/lmt/news/article/excellent-video-award-at-tmi-education-video-competition/)
        - organization: Technical University of Munich
          organization_url: https://www.tum.de
          title: 'New Course: Software Engineering Lab'
          url: https://www.ce.cit.tum.de/en/lmt/teaching/software-engineering-laboratory/
          certificate_url: ''
          date_start: '2021-04-01'
          date_end: ''
          description: |
            * Details: [Software Engineering Lab](/teaching/software-lab/)
            * [Chair of Media Technology](https://www.ce.cit.tum.de/lmt)
            * Publication: [Teaching Software Engineering As Programming Over Time](/publication/software_lab)
        - organization: Technical University of Munich
          organization_url: https://www.tum.de
          title: 'Press Release: New early warning system for self-driving cars'
          url: https://www.tum.de/nc/en/about-tum/news/press-releases/details/36509/
          certificate_url: ''
          date_start: '2021-03-30'
          date_end: ''
          description: |
            * Publication: [Introspective Failure Prediction for Autonomous Driving Using Late Fusion of State and Camera Information](/publication/introspection_bb_fusion/)
            * News: [Chair of Media Technology](https://www.ce.cit.tum.de/lmt/aktuelles/article/tum-press-release-new-early-warning-system-for-self-driving-cars/)
            * Post: [Techcrunch](https://techcrunch.com/2021/04/20/deep-science-introspective-detail-oriented-and-disaster-chasing-ais/)
        - organization: IEEE Computer Society
          organization_url: https://www.computer.org/
          title: Best Student Paper Award at 22nd IEEE International Symposium on Multimedia
          url: https://www.ieee-ism.org/
          certificate_url: ''
          date_start: '2020-12-04'
          date_end: ''
          description: |
            * Publication: [Better Look Twice - Improving Visual Scene Perception Using a Two-Stage Approach](/publication/blt/)
            * News: [Chair of Media Technology](https://www.ce.cit.tum.de/en/lmt/news/article/best-student-paper-award-auf-der-ism-2020/)
    design:
      columns: '2'
  - block: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: Courses & Visits
      subtitle: Selected courses and visits
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - organization: EngFlow & Booking.com
          organization_url: https://www.engflow.com/
          title: 1st Bazel Community Day of 2024
          url: ""
          certificate_url: ""
          date_start: "2024-03-25"
          date_end: "2024-03-25"
          description: ""
        - organization: Gradle Inc.
          organization_url: https://gradle.com/
          title: 2023 Developer Productivity Engineering Summit
          url: https://dpe.org/sessions/
          certificate_url: ""
          date_start: "2023-09-20"
          date_end: "2023-09-21"
          description: "The only event dedicated to the practice of Developer Productivity Engineering (DPE) and Developer Experience (DX)"
        - organization: University of Constance
          organization_url: https://www.uni-konstanz.de/
          title: 5th Summer School on Video Compression and Processing
          url: https://www.mmsp.uni-konstanz.de/overview/
          certificate_url: ""
          date_start: "2019-06-17"
          date_end: "2019-06-19"
          description: ""
        - organization: Leibniz Supercomputing Centre
          organization_url: https://www.lrz.de
          title: Advanced C++ with Focus on Software Engineering
          url: https://www.lrz.de/services/compute/courses/archive/2019/2019-06-12_hcpa1s19/
          certificate_url: ""
          date_start: "2019-06-12"
          date_end: "2019-06-14"
          description: ""
    design:
      columns: '2'
  - block: portfolio
    id: projects
    content:
      title: Projects
      filters:
        folders:
          - project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      buttons:
        - name: All
          tag: '*'
        - name: Software Engineering
          tag: Software Engineering
        - name: Research
          tag: Research
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: true
  - block: collection
    id: talks
    content:
      title: Recent & Upcoming Talks
      filters:
        folders:
          - event
    design:
      columns: '2'
      view: compact
  - block: collection
    id: featured
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: card
  - block: collection
    content:
      title: Recent Publications
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      columns: '2'
      view: compact
  - block: tag_cloud
    content:
      title: Popular Topics
    design:
      columns: '2'
---
