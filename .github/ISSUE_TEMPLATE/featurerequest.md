name: Feature Request
description: Suggest a new feature for this project
title: "[Feature]: "
labels: ["enhancement"]
body:
  - type: input
    id: name
    attributes:
      label: What is your name?
      placeholder: ex. Sertha Taweewattana
    validations:
      required: true

  - type: dropdown
    id: request-type
    attributes:
      label: Type of request?
      options:
        - New Feature
        - Improvement
        - Documentation
    validations:
      required: true

  - type: dropdown
    id: os
    attributes:
      label: What is the OS which you want to suggest?
      options:
        - Windows
        - macOS
        - Linux
        - All Platforms

  - type: textarea
    id: details
    attributes:
      label: What are the details of your suggestion?
      description: Explain what you want and why it would be useful
      placeholder: Feature details!
    validations:
      required: true
