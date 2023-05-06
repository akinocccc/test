name: Bug report
description: Create a report to help us improve.
title: "[Component Name] A title for the problem"
labels: ["bug report"]
body:

- type: input
  id: describe
  label: Describe the bug
  description: A clear and concise description of what the bug is.
  placeholder: Please input
  validations:
  required: true

- type: input
  id: reproduceLink
  label: Reproduce link
  description: Provide CodePen, CodeSandbox or GitHub repo link. Don't offer unrelated link!
  placeholder: Please input

- type: textarea
  id: reproduceSteps
  label: To Reproduce
  description: Steps to reproduce the behavior. If not, the issue will not be fixed and be closed.
  placeholder: Please input

- type: textarea
  label: Expected behavior
  placeholder: Please input

- type: textarea
  id: actual
  label: Actual behavior
  placeholder: Please input

- type: input
  id: frameworkVersion
  label: Framework version
  placeholder: Vue(3.2.0)

- type: input
  id: browsersVersion
  label: Browsers version
  placeholder: Chrome(8.213.231.123)

- type: input
  id: systemVersion
  label: OS version
  placeholder: MacOS(11.2.3)

- type: input
  id: nodeVersion
  label: Node Node version
  placeholder: Please input

- type: textarea
  id: remarks
  label: Additional context
  description: Add any other context about the problem here, like screenshot or video record
  placeholder: Please input
