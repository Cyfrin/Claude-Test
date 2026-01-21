# Claude Code Guidelines

## Issue Management & Workflow

1.  **Analyze**: Read the issue to understand requirements.
2.  **Plan & Notify**: Run `gh issue comment create --body "..."` to post your initial checklist. 
    *   **CRITICAL:** Capture the URL/ID of this comment from the output. You will need it later.
3.  **Branch**: Create a new branch.
4.  **Implement**: Write the code and tests.
5.  **PR**: Run `gh pr create --fill` to submit the PR.
6.  **Update Status**: Do NOT create a new comment. 
    *   Use the command `gh issue comment edit <comment-url> --body "..."`
    *   Update your **original comment** to check off the boxes.
    *   Add the link to the PR at the bottom of that same comment.
