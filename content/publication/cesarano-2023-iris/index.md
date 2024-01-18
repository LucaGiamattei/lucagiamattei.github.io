---
title: 'IRIS: a Record and Replay Framework to Enable Hardware-assisted Virtualization Fuzzing'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Marcello Cinque
  - Domenico Cotroneo
  - Luigi De Simone
  - Giorgio Farina

# Author notes (optional)
author_notes: ""
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2023-03-01T00:00:00Z'
doi: '10.1109/DSN58367.2023.00045'

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']
#["article-journal"]
#["article"]

# Publication name and optional abbreviated publication name.
publication: In *The 53rd Annual IEEE/IFIP International Conference on Dependable Systems and Networks*
publication_short: In *DSN2023*

abstract: Nowadays, industries are looking into virtualization as an effective means to build safe applications, thanks to the isolation it can provide among virtual machines (VMs) running on the same hardware. In this context, a fundamental issue is understanding to what extent the isolation is guaranteed, despite possible (or induced) problems in the virtualization mechanisms. Uncovering such isolation issues is still an open challenge, especially for hardware-assisted virtualization, since the search space should include all the possible VM states (and the linked hypervisor state), which is prohibitive. In this paper, we propose IRIS, a framework to record (learn) sequences of inputs (i.e., VM seeds) from the real guest execution (e.g., OS boot), replay them as-is to reach valid and complex VM states, and finally use them as valid seed to be mutated for enabling fuzzing solutions for hardware-assisted hypervisors. We demonstrate the accuracy and efficiency of IRIS in automatically reproducing valid VM behaviors, with no need to execute guest workloads. We also provide a proof-of-concept fuzzer, based on the proposed architecture, showing its potential on the Xen hypervisor.

# Summary. An optional shortened abstract.
summary: ''

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2303.12817.pdf'
url_code: 'https://github.com/dessertlab/iris'
#url_dataset: 'https://github.com/dessertlab/iris'
url_poster: ''
url_project: ''
url_slides: ''
#url_source: 'https://github.com/dessertlab/iris'
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
#  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

