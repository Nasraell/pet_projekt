---
name: Custom issue template
about: 'Here Be Dragons '
title: "[Dragon]"
labels: ''
assignees: ''
body:
- type: dropdown
  id: download
  attributes:
    label: How did you download the software?
    options:
      - Homebrew
      - MacPorts
      - apt-get
      - Built from source
  validations:
    required: true
---


