# Commit Issue Example

This is a simple recreation of an issue that I hit multiple times in a real world scenario. Though the issue is not visible here. I'm using a dummy project so as to not risk any damage to exisiting projects.

The issue stemmed from accidentally pushing a commit (due to going through the push process to quickly) that had files or changes that shouldn't have been included. To recreate, simply add changes to some file, commit, and push. Then, reset the offending branch and try to reflect those changes on GitHub.

The process should be to reset the branch to a previous commit, confirm files are as intended, push forcefully, and changes should be reflected. If that process works, there should be no evidence of my issue in this repo. But the process is infinitely repeatable (as is the mistake...).

Status: SUCCESS
