# Process lens: factory-scratch

- **The places:** the owner starts sessions in Claude Code and answers them there; builds and
  reviews run in the session; pull requests are merged on GitHub. There are no releases or deploys.
- **Shared resources:** none.
- **The owner's gates:** the `ready` and `validated` labels, the word that starts a build, and
  the merge. Each approves only the issue or pull request it is given on.
- **The flow's docs:** `.claude/factory/project.md`. No past gaps recorded.
- **What counts as process work:** changes under `.claude/factory/`.
