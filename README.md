## This repository was created to test and understand how to create templates for PRs

To use templates for PRs, just create a file named PULL_REQUEST_TEMPLATE and place it one of these locations:

 - The root of your project
 - .github folder

Despite the extension being optional, using Markdown (.md) files is recommended.

Once GitHub detects the PULL_REQUEST_TEMPLATE file, it will auto-populate new PRs with the contents.

Remember to use this exact name for the file: PULL_REQUEST_TEMPLATE

### This is the template that i created for my PRs:

---------------------------------------------------------------------------------------

## Description

Add a short, objective description of the changes made

## Related

Tickets Jira

## Type of change

- [ ] Bug
- [ ] Defect
- [ ] New feature
- [ ] Improvement

## Checklist:

- [ ] I have added Unit Test
- [ ] I have added data-testid
- [ ] I have added Integration Test
- [ ] I have added E2E Integration Test
- [ ] I have performed a self-review of my own code
- [ ] I have no SonarLint warnings, bugs or security errors in my code
- [ ] I have added unit and/or integration and/or e2e tests for other unrelated features
- [ ] I changed existing tests to keep the system working
- [ ] My code follows the style guidelines of this project
- [ ] New and existing tests pass locally with my changes
