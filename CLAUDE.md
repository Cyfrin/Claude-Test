# Claude Code Guidelines

## Issue Management & Workflow
When you are asked to fix an issue or implement a feature from a GitHub Issue, strictly follow this process:

1.  **Analyze**: Read the issue and understand the requirements.
2.  **Branch**: Create a new branch for the fix (e.g., `fix/issue-number-short-description`).
3.  **Implement**: Write the code and tests to resolve the issue.
4.  **PR**: Create a Pull Request targeting the default branch.
    *   **Title**: Use a clear title (e.g., "Fix: description of fix").
    *   **Body**: Include "Closes #<issue_number>" in the PR description.
5.  **Link**: Post a comment on the original issue with a link to the new PR.
