name: 💡 Request a feature
description: Request a new feature to implement in pynab
title: "[Request]"
body:
  - type: markdown
    attributes:
      value: >
        **Thank you for wanting to request a feature in pynqb!**
  - type: textarea
    attributes:
      label: Is your feature request related to a problem? Please describe.
      description: A clear and concise description of what the problem is. Eg, "I'm always frustrated when [...]".
  - type: textarea
    attributes:
      label: Describe the solution you'd like
      description: >-
        A clear and concise description of what you want to happen. Explain why it needs to be included in pynab's core
        and can't become a new service.
    validations:
      required: true
  - type: textarea
    attributes:
      label: Describe alternatives you've considered
      description: A clear and concise description of any alternative solutions or features you've considered.
  - type: textarea
    attributes:
      label: Additional context
      description: Add any other context or screenshots about the feature request here.
