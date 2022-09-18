Based on fork model. Owners of upstream repository have full permissions. Others can only fork and submit pull requests.

1. Fork https://github.com/eduard-kavalchuk/sf-hw-git
2. git clone https://github.com/eduard-kavalchuk/sf-hw-git
3. git remote add upstream https://github.com/eduard-kavalchuk/sf-hw-git
4. git checkout -b <branch>
5. git checkout main
6. git fetch upstream
7. git merge upstream/main
8. git checkout <branch>
9. git merge main
Resolve conflicts and make a final commit.
10. git push origin <branch>

11. Go to web:
a. "Compare & pull request"
b. Add description of changes
c. Check "Allow edits by maintainers"
d. "Create pull request"
6. Wait for email with a confirmation or make necessary changes.


git config user.name "Eduard Kovalchuk"
git config user.email eduardkovalchuk@mail.ru
git config alias.history 'log --graph'
