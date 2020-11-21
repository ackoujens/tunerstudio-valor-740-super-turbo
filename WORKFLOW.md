# Workflow

This document describes GitHub workflows. Mainly for personal use.
How to create issues/pull requests/releases for a uniform project flow.


## Issues

This is the main flow to follow when working on this project.
If a specific subject needs an improvement or fix, first create a dedicated issue for it.

Provide enough documentation what the specific problem is or what feature needs to be improved.
Use a provided template and fill in with description, issue, symptoms and taken diagnostic steps.


## Branch

An issue should be worked on in a seperate branch. 
When you completely fail to fix/diagnose/improve an issue. 
You're able to completely destroy this branch and start over from where you left off.


## Commits

Only commit clear and consise changes.
Never make minor insignificant changes and commit purely for saving your work.
(This is not the purpose of git version control!)

Commit only to the dedicated branch for a specific issue, never straight to master.
Exceptions are:
- .gitignore updates
- very minor README.md updates (try to save these and bundle for another fitting commit occasion)
- new files unrelated to any issue (repo license file, new .gitignore, new README.md, this workflow document)

### Extra
- do not use punctuation in commit messages, allowed in commit descriptions


## Pull requests

When an issue has been worked on, it is able to be presented as a solution.
A pull request needs to be made to bring your branched off work forward.
At this point tests can be performed or the pull request can be merged with the master branch.
This will at the same time close the highlighted issue and mark it as solved.

PR review is not available as this is mostly a one-man project.
This can be changed in the future.


## Releases

Releases are made when major portions of issues/features have been covered.
Ex: starting/idle milestone has been completely covered and closed

Never push releases when nothing major has been changed.


## Other

Actions present oppertunities for automatisation but is not in use at the moment.
Could be coupled to push releases to a website / update new issues.

Wiki is also out of the picture for the moment.
Some information might just end up at volvovalor.com instead of on GitHub.