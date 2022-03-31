# gittest
Explore git and git commands

## Initializing Git Repo

### Creating a new repository using command line

```bash
echo "# test" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:prathikshetty9b/test.git
git push -u origin main
```

### Push an existing repository from the command line

```bash
git remote add origin git@github.com:prathikshetty9b/test.git
git branch -M main
git push -u origin main
```

## Git Commands

| Commands | Description |
| --- | --- |
| git branch | All your local repositories |
| git branch -r | All your remote branches |
| git branch -a | Both local and remote repositories |
| git branch branch-name | New local branch |
| git checkout branch-name | Switch branches |
| git merge branch-name | Merge two branches |
| git rebase branch-name | Rewrites without merge commit |
| git revert | Revert back |
| git clone url | Copy repo  |
| git branch -d branch-name | Delete Branch |
| git log | Log of historical changes. |

## Notes

- Branching is for parallel development.
- Creates an isolated environment
- It is good practice to hold production level code in main branch.
- Fork repo to your central repository then clone it to your local machine.
- There is no `git fork` command.

## Reference

[Git Rebase vs. Git Merge Explained](https://reflectoring.io/git-rebase-merge/)

[Github's Fork & Pull Workflow for Git Beginners](https://reflectoring.io/github-fork-and-pull/)