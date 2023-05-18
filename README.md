# Commit Issue Example

## Reset

This is a simple recreation of an issue that I hit multiple times in a real world scenario. Though the issue is not visible here. I'm using a dummy project so as to not risk any damage to exisiting projects.

The issue stemmed from accidentally pushing a commit (due to going through the push process to quickly) that had files or changes that shouldn't have been included. To recreate, simply add changes to some file, commit, and push. Then, reset the offending branch and try to reflect those changes on GitHub.

The process should be to reset the branch to a previous commit, confirm files are as intended, push forcefully, and changes should be reflected. If that process works, there should be no evidence of my issue in this repo. But the process is infinitely repeatable (as is the mistake...).

Status: SUCCESS

## Restore

Now for the same challenge but using restore instead of reset. The difference in use case would be for a time when an offending file made it to a branch shared by multiple devs as opposed to something like a feature branch. So maybe a PR is made from a feature branch and merged into a branch like `qa` or something similar. Only later to realize a change was made that shouldn't have been included. Using reset, while removing the changes, would also remove branches from git history that could corrupt other users branch history. Restore handles this by removing the offending file or change while keeping the history intact.

Status: PENDING
