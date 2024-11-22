---
name: Task template
about: Describe this issue template's purpose here.
title: ''
labels: ''
assignees: ''

---

name: Task
description: Create a new task effort
body:
  - type: dropdown
    id: type
    attributes:
      label: Type
      options: [Task]
    validations:
      required: true
      
  - type: input
    id: parent_project
    attributes:
      label: Parent Project
      description: Link to parent project (if applicable)
    validations:
      required: false
      
  - type: input
    id: dri
    attributes:
      label: DRI
      description: Who owns this task?
    validations:
      required: true
