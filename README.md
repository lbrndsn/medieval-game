# jQuery Project

## How to resolve conflicts?
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

## How to use GitHub?
### Add a file
1. Ga naar de folder waar je de code wilt hebben 
    1. gebruik `cd` om te switchen naar een folder
    2. gebruik `cd ../` om een folder omhoog te gaan
2. terminal: `git init`
3. terminal: `git remote add origin https://github.com/loisberndsen/jquery-klein-project.git` (overeenkomend met de repo op GitHub)
4. voeg een file of meerdere toe
5. om files klaar te zetten voor een commit, doe `git add filename`
6. om te checken wat er allemaal gaande is: `git status`
7. wanneer je veranderingen klaar wilt committen: `git commit` (eventueel met `-m “message hier”`)

#### Commit
Een commit is meestal een klein stuk code wat werkt, of waarvan je het wilt opslaan. Je kan ook meerdere commits doen voordat je een push doet.

`git commit`
of
`git commit -m “heb net wat veranderd aan de javascript”`

#### Push
Een push zorgt ervoor dat de commits die je lokaal hebt gedaan, op GitHub komen.

`git push`