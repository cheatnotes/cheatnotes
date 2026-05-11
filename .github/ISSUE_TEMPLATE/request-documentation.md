---
name: Request Documentation
about: Suggest an idea for this project
title: ''
labels: enhancement
assignees: ''
type: Feature

---

## 📚 Request Documentation

**File:** `.github/ISSUE_TEMPLATE/documentation.md`

```yaml
name: 📚 Request Documentation
description: Request documentation for missing or poorly explained topics
title: "[DOCS] "
labels: ["documentation"]
assignees: []

body:
  - type: markdown
    attributes:
      value: |
        Help us document topics that need better coverage!

  - type: textarea
    id: topic
    attributes:
      label: Topic to Document
      description: What topic or concept needs documentation?
      placeholder: |
        Topic: [specific topic name]
        Category: [general area of knowledge]
      validations:
        required: true

  - type: textarea
    id: why-needed
    attributes:
      label: Why Is This Needed?
      description: Why should we document this?
      placeholder: |
        - Many people ask about this
        - It's commonly used for [purpose]
        - Current documentation is incomplete
        - Beginners struggle with [reason]

  - type: textarea
    id: current-state
    attributes:
      label: Current Documentation (if any)
      description: Is this topic already covered? How could it be improved?
      placeholder: |
        Currently documented in: [section]
        Could be improved by: [suggestions]

  - type: textarea
    id: scope
    attributes:
      label: What Should Be Covered?
      description: What aspects of this topic are important?
      placeholder: |
        - Basic concepts
        - Common use cases
        - Best practices
        - Practical examples

  - type: textarea
    id: resources
    attributes:
      label: Helpful Resources
      description: Any links or resources that might help write this?
      placeholder: |
        Official docs: https://...
        Related tutorial: https://...

  - type: checkboxes
    id: verification
    attributes:
      label: Before Submitting
      options:
        - label: This topic isn't already covered
          required: true
        - label: This would help many users
```
