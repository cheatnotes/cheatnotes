---
name: Bug Report Template
about: Create a report to help us improve
title: ''
labels: bug
assignees: aw-junaid
type: Bug

---

## 🐛 Bug Report Template

**File:** `.github/ISSUE_TEMPLATE/bug_report.md`

```yaml
name: 🐛 Report an Error
description: Report incorrect information, broken links, or inaccurate examples
title: "[BUG] "
labels: ["bug", "needs-review"]
assignees: []

body:
  - type: markdown
    attributes:
      value: |
        Thanks for reporting an error! Help us improve the cheat sheet.

  - type: dropdown
    id: type
    attributes:
      label: Type of Error
      description: What type of issue did you find?
      options:
        - "Incorrect information"
        - "Broken or outdated link"
        - "Code example doesn't work"
        - "Unclear explanation"
        - "Missing information"
        - "Formatting issue"
        - "Typo or grammar"
        - "Other"
    validations:
      required: true

  - type: textarea
    id: location
    attributes:
      label: Location in Cheat Sheet
      description: Where in the README is the error? (section name, headings, line number if possible)
      placeholder: |
        Section: "SQL Queries"
        Subsection: "JOIN Operations"
      validations:
        required: true

  - type: textarea
    id: problem
    attributes:
      label: What's the Problem?
      description: Describe the error clearly
      placeholder: |
        The code example shows:
        [incorrect code]
        
        But it should be:
        [correct code]
      validations:
        required: true

  - type: textarea
    id: expected
    attributes:
      label: What Should It Be?
      description: What's the correct information?
      placeholder: |
        The correct information is...

  - type: textarea
    id: source
    attributes:
      label: Reference/Source
      description: Where did you find the correct information? (link to official docs, etc.)
      placeholder: |
        Official documentation: https://...
        Tested and verified: Yes

  - type: textarea
    id: additional
    attributes:
      label: Additional Context
      description: Anything else we should know?
      placeholder: |
        - Tested with version X.X.X
        - Also affects [related section]

  - type: checkboxes
    id: verification
    attributes:
      label: Verification
      options:
        - label: I have searched for duplicate issues
          required: true
        - label: I have verified the error is actually incorrect
          required: true
        - label: I can provide a source for the correction
          required: true
```

---
