name: "🐞 Bug Report"
description: Report a bug or issue with the app
title: "[Bug]: "
labels: ["bug"]
body:
  - type: input
    id: summary
    attributes:
      label: Short Summary
      placeholder: e.g. App crashes when saving expense
    validations:
      required: true

  - type: textarea
    id: steps
    attributes:
      label: Steps to Reproduce
      placeholder: 1. Open app\n2. Go to Add Expense\n3. Tap Save\n4. Crash
    validations:
      required: true

  - type: textarea
    id: expected
    attributes:
      label: Expected Behavior
      placeholder: App should save the expense and return to the dashboard
    validations:
      required: true

  - type: textarea
    id: actual
    attributes:
      label: Actual Behavior
      placeholder: App crashes with error message
    validations:
      required: true

  - type: textarea
    id: context
    attributes:
      label: Additional Context
      placeholder: Device type, iOS version, screenshots, logs...
    validations:
      required: false
