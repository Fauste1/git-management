Hello!

This project was created to be able to safely play around with git, gitHub etc.

Things I'm trying:
1. managing merge conflict
2. working with multiple branches on github
3. developing multiple features simulatenously
4. anything else I find interesting

What I learned:
1. To push from local branch to a non-existent remote (GitHub) branch, use:
> git push -u [name-of-the-new-branch](1)
This creates new remote branch (e.g. on GitHub), publishes it and sets the HEAD of your local branch to this remote, so that next time you need to push directly from your local branch to this specific remote, you only use "git push" with no options and watch the magic happen.

---
Footnotes
(1) TIP: keep it consistent with the naming of your local branch