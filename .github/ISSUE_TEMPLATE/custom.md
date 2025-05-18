---
name: Custom issue template
about: Describe this issue template's purpose here.
title: ''
labels: ''
assignees: ''

---

body:
  - type: textarea
    id: what-are-we-doing
    attributes:
      label: What are we doing?
      description: Briefly describe the purpose and goal of this issue.
    validations:
      required: true
  - type: textarea
    id: how-are-we-doing-it
    attributes:
      label: How are we doing it?
      description: Outline the steps, approach, or method to achieve the goal.
    validations:
      required: true
  - type: textarea
    id: how-do-i-test
    attributes:
      label: How do I test?
      description: Describe how to validate, verify, or test this change.
    validations:
      required: true
