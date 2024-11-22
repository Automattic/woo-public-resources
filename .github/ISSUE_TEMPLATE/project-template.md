---
name: Project template
about: Use this to create new projects
title: ''
labels: ''
assignees: ''

---

name: Project
description: Create a new project effort
body:
  - type: dropdown
    id: type
    attributes:
      label: Type
      options: [Project]
    validations:
      required: true
      
  - type: input
    id: goal
    attributes:
      label: Goal
      description: What's the project objective?
    validations:
      required: true
      
  - type: input
    id: dri
    attributes:
      label: DRI
      description: Who owns this project?
    validations:
      required: true
