# Pull Requests and Code Review Reflection

1. Squash and Merge combines a small feature's implementation and review-fix commits into one clean commit on main, making history easier to follow. The pull request still preserves the discussion and review context.

2. Add single comment publishes feedback immediately, while Start a review holds inline comments until they are submitted together. Batching gives the author organized feedback and avoids repeated notifications.

3. Branch protection rules can prevent direct changes to main and require a pull request and approval before merging. This creates an opportunity to review changes and catch errors before they enter the main codebase.

4. Fetching and merging origin/main into a feature branch lets the author resolve competing edits and test the combined result without rewriting shared history. Force-pushing can discard other commits rather than reconciling the changes.
