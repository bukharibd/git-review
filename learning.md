# Review

1.  Why we need git and github?
2.  Basic configuration
3.  SSH key
    - SSH key generate
    - SSH public key add to gitHub
4.  Git workflow (add-commit-push)
5.  Merge conflickt
6.  How to resolve merge conflict
7.  collaboration (clone) and (fork => clone)
    - fork => 3rd party repo => own github => git clone
8.  git page
9.  github issues + gitignore + README.md
10. git merge vs git rebase
11. GitHub actions (CI/CD)
12. Advanced

            - gitHub Actions (CI/CD)
            - Git Flow /GitHub Flow, Trunk Basked Developnemt
            - Rewriting history: git reflog, git filter-branch, git cherry-pick
            - Performance and Optimization: Shallow clones, Partial clones
            - Undo changes (Working directory => staging area => local ripository => remote repository)
              - git checkout -- <filename.tex / .> Undo from unstaging
              - git reset HEAD . / <filename.tex / .> Undo from staging area
              - git reset --hard HEAD => Undo from unstaging && Undo from staging area
              - git commit --amend => Change commit messege

            remove git repository: rm -rf .git
