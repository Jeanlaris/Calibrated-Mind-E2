name: Bug Report
description: File a bug report to help us improve the system
title: "[Bug]: "
labels: ["bug", "needs-triage"]
assignees: []

body:
  - type: markdown
    attributes:
      value: |
        Thanks for taking the time to fill out this bug report!

  - type: input
    id: summary
    attributes:
      label: Bug Summary
      description: A short summary of what the bug is.
      placeholder: e.g., Event bus fails to register lifespan hooks
    validations:
      required: true

  - type: textarea
    id: reproduction
    attributes:
      label: Steps to Reproduce
      description: How can we reproduce this issue?
      placeholder: |
        1. Run command X
        2. Trigger event Y
        3. See error
    validations:
      required: true

  - type: textarea
    id: expected
    attributes:
      label: Expected Behavior
      description: What did you expect to happen?
    validations:
      required: true
