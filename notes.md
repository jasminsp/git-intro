Git commands:

Exersice 1
1. Clone remote repo from github
git clone <url>

2. Remove existing origin
git remote remove origin

3. Add new origin
git remote add origin <new-url>

4. Add files to commit
git add .

5. Commit changes
git commit -m 'message'

6. Push to remote
git push

7. Check git status
git status

8. Set upstream, the branch that will be followed from main
git push --set-upstream origin master

9. Add a new file
touch <new-file-name>

10. Edit file
vi <file-name>


Exersice 2
11. Create new branch
git checkout -b <branch-name>

12. Swap branch
git checkout <branch-name>

13. Merge branch to master
git merge <branch-name-to-be-merged>

14. Pull updates from remote
git pull

15. Delete branch locally
git branch -d <localBranchName>

16. Delete branch remotely
git push origin --delete <remoteBranchName>
