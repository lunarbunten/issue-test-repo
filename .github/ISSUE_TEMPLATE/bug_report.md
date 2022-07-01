name: Bug report
description: "Create a bug report"
body:
  - type: input
    id: version
    attributes:
      label: Enderscape Version
      description: >-
        Please provide the version of Enderscape you are using.
      placeholder: 'Example: v0.2.0'
    validations:
      required: true
  - type: input
    id: version
    attributes:
      label: BCLib Version
      description: >-
        (For 1.18 and above) Please provide the version of BCLib you are using.
      placeholder: 'Example: 2.0.0'
    validations:
      required: false
  - type: textarea
    id: expected
    attributes:
      label: What happened?
      description: What did you expect to happen?
    validations:
      required: true
  - type: textarea
    id: repro-steps
    attributes:
      label: Steps to reproduce
      description: >-
        Provide information for how to reproduce this bug.
      placeholder: |
        Example:
        1. Place a Redstone Lamp in front of a Redstone Repeater
        2. Use a Lever to activate the Redstone Repeater
        3. Nothing happens
    validations:
      required: true
  - type: textarea
    id: additional
    attributes:
      label: Additional information
      description: >-
        Provide a list of additional mods you are using
