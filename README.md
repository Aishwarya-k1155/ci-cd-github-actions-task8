# ci-cd-github-actions-task8
# Task 8: Introduction to CI/CD Using GitHub Actions

## Objective
To understand how a CI pipeline works using GitHub Actions and how it is triggered automatically on code changes.

## Steps Performed
1. Created a new GitHub repository with a simple HTML file.
2. Created a CI workflow using GitHub Actions inside `.github/workflows`.
3. Configured the workflow to trigger on every push and pull request.
4. Added steps to check out the code and run a basic validation command.
5. Ran the workflow and observed the execution logs in the Actions tab.
6. Intentionally broke the pipeline by adding a failing step.
7. Fixed the pipeline by removing the failing step and re-running the workflow.

## Pipeline Behavior Observed
- The workflow automatically ran on every commit.
- When the pipeline was broken, the workflow failed and showed error logs.
- After fixing the issue, the workflow ran successfully again.

## Learning Outcome
- Learned how CI pipelines are created using GitHub Actions.
- Understood automatic triggers like push and pull request.
- Learned how to analyze workflow logs.
- Understood how CI failures are detected and resolved.
