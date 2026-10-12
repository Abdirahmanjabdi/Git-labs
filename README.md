# Git labs

Practice repo for the everyday Git workflows: feature branches, merge conflicts, pull requests,
hotfixes, and undoing mistakes.

The files are deliberately trivial. The point is the history, not the content. Clone it and run
`git log --oneline --graph`, or browse the [commit history](https://github.com/Abdirahmanjabdi/Git-labs/commits/main),
to see each exercise.

## What's in the history

| Exercise | Where to look |
|---|---|
| Merge conflict between a feature branch and `main`, resolved by hand | Merge commit [e25c6b1](https://github.com/Abdirahmanjabdi/Git-labs/commit/e25c6b1), joining the two conflicting changes [2f0e7bc](https://github.com/Abdirahmanjabdi/Git-labs/commit/2f0e7bc) and [b9e5c33](https://github.com/Abdirahmanjabdi/Git-labs/commit/b9e5c33). `app.txt` shows the resolved result. |
| Feature branch merged through a pull request | [06918d2](https://github.com/Abdirahmanjabdi/Git-labs/commit/06918d2), PR #1 from `feature/add-about-page` |
| Hotfix | [a3aa78f](https://github.com/Abdirahmanjabdi/Git-labs/commit/a3aa78f) |
| Undoing changes safely | The commits from [6f42298](https://github.com/Abdirahmanjabdi/Git-labs/commit/6f42298) onward, including deliberately bad commits ([aa267fe](https://github.com/Abdirahmanjabdi/Git-labs/commit/aa267fe), [1df6b98](https://github.com/Abdirahmanjabdi/Git-labs/commit/1df6b98)) and a clean-up ([cc080af](https://github.com/Abdirahmanjabdi/Git-labs/commit/cc080af)) |
