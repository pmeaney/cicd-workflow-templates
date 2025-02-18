## CICD Workflow templates

Just some example templates to test out some basic features, prior to incorporating those features into projects.

### Example 1: workflow_call

#### Thing to keep in mind:

- A calls B. Therefore, in the particular step where A calls B, the echo statements in B actually appear in the log for A (not B).
