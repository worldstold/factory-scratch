# factory-scratch: the factory's project file

A throwaway repository for trying the factory's skills. Nothing here is real work.

## Start here
`README.md`, then this file. There's no CLAUDE.md and no "where things stand" doc. The purpose:
a safe place to test the factory, so the simplest choice wins.

## Owner
`worldstold` on GitHub; commits are made as `Jason Olsan <jason.olsan@gmail.com>`. The owner's
word starts a grill or a build, and the owner merges every pull request. A session never merges,
closes or reopens anything, or deletes a branch.

## Issues
- **Labels:** `type:feature`, `type:fix`. No others.
- **Branches:** `<type>/<issue>-<words>`; the base is `main`.
- **Order:** none kept. Sessions take the issue the owner names.

## Build and test
Nothing to build and no tests. A change is checked by reading its diff.

## On screen
Nothing on screen.

## Reviewers
- `factory:security-reviewer`: not run;
- `factory:ux-reviewer`: not run (nothing on screen);
- `factory:tech-writer`: any text a person reads, on the cheaper model;
- `factory:process-reviewer`: only when a change touches `.claude/factory/`, on the cheaper model;
- no reviewers of the project's own.

Deferred findings go in issues.

## Agents
None.

## Release
- **Versions:** none. A pull request carries no version, CHANGELOG entry or release notes.
- **Before the owner tries it:** nothing; the owner reads the pull request.
- **After the merge:** nothing follows.

## Validate
The owner reads the pull request's diff on GitHub. Every VALIDATE item is something that can be
seen there.

**Untested, then followed up:** not used; nothing here waits on a later event.

## Private
- **Files:** `.env`, `*.key`

## Never
Nothing beyond what the plugin forbids. Put no real secrets, names or addresses in this
repository: its content is made up.
