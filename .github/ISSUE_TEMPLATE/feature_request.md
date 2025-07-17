---
name: "🚀 Feature Request"
about: Suggest a new feature or improvement
title: "[Feature]: "
labels: ["feature"]
body:
  - type: input
    id: summary
    attributes:
      label: Short Summary
      placeholder: e.g. Add recurring income feature
    validations:
      required: true

  - type: textarea
    id: details
    attributes:
      label: Detailed Description
      placeholder: What should the feature do? Who needs it?
    validations:
      required: true

  - type: textarea
    id: alternatives
    attributes:
      label: Alternatives Considered
      placeholder: Did you consider any other approaches?
    validations:
      required: false

  - type: textarea
    id: context
    attributes:
      label: Additional Context
      placeholder: Screenshots, examples, references...
    validations:
      required: false
---
