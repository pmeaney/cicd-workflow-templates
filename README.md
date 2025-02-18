## CICD Workflow templates

Just some example templates to test out some basic features, prior to incorporating those features into projects.

Things to note:

- Workflow files must be in the .github/workflows directory directly. They can't be in subdirectories, or you get this error: `invalid value workflow reference: workflows must be defined at the top level of the .github/workflows/ directory`
  - So, unfortunately, anytime we want to run a template example we need to move its file(s) to the workflows directory

### Example 1: workflow_call

#### Thing to keep in mind:

- A calls B. Therefore, in the particular step where A calls B, the echo statements in B actually appear in the log for A (not B).
