# jQuery Project

## How to resolve conflicts?
Help! I got a conflict, what do I do? 
### For WebStorm:
Steps:
1. Navigate to `VCS` -> `Git` -> `Resolve conflicts`
2. Select the file which has a conflict (could be multiple)
3. Click on `merge`
4. Now you'll see three windows: your changes on the left, changes from someone else on the right, and the final result in the middle.
5. Pick and choose which changes you want to keep from each side
6. Check if the final result is what you want it to be
7. Confirm changes
8. (Optional) If you have more files with conflicts, do the same with these
9. All conflicts resolved? Good. Run `git add .` to add all changed files for a commit
10. Commit the changes using `git commit -m "resolved all conflicts"`
11. Push changes `git push`

### Via terminal:
See: https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/resolving-a-merge-conflict-using-the-command-line 

