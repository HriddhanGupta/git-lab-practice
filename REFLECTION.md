1. Merging `update-message-a` was clean because `main` had not changed the sum line. Merging `update-message-b` caused a conflict because both branches changed that same line differently.

2. The section under `HEAD` is the version currently on `main`. The section under the branch name is the incoming version from the branch being merged.

3. `git merge --abort`

4. Part B showed a single line because the merge was a fast-forward. Part C showed branches diverging and rejoining at a merge commit because both branches had separate commits.