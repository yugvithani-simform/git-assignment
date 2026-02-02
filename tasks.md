## Git tasks
- T01: Create a new branch from develop.
- T02: Add a commit message hook to the repository.
- T03: Perform multiple commits in the newly created branch.
- T04: Create a Pull Request (PR) targeting the develop branch.
- T05: Ensure the PR is small in size.
Prefer one commit per PR.
Allow multiple commits only when appropriate (e.g., multiple small one-line bug fixes).
- T06: Create another branch from develop while the previous PR is still under review.
- T07: Commit changes in the current branch and push it to the remote repository.
- T08: Handle the scenario where the previous PR gets merged into develop.
- T09: Update the current branch so it is up to date with the latest develop branch.
- T10: Create a PR for the current branch after syncing with develop.
- T11: For every new build release, add a version tag to the corresponding commit to track releases.
- T12: Create two more branches (3rd and 4th) from develop.
- T13: Push README changes to the 3rd branch.
- T14: Cherry-pick the commit from the 3rd branch into the 4th branch.
- T15: Modify the commit message in the 4th branch.
- T16: Add three new commits to the 4th branch.
- T17: Delete the last commit from the 4th branch.