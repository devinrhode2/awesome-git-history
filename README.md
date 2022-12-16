# awesome-git-history
Tools and resources on how to create awesome git history!

# CLI Tools:
 - Maintain atomic commits: [git-absorb](https://github.com/tummychow/git-absorb)
 - Create more atomic commits by default, use [Graphite](https://graphite.dev/) (also makes reviewing stacked PRs easier)

# Git blame extensions
If you don't like code comments, you can use a good git-blame extension, which will encourage writing good commit messages:
 - VSCode: [git-lens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)
 - JetBrains IntelliJ: https://stackoverflow.com/a/55917374/565877
 - vim: TODO!
 - emacs: TODO!



# git hooks
 - Automatically git-blame-ignore `style` commits: https://github.com/devinrhode2/git-blame-ignore-style-formatting-post-commit-hook
 - Prevent "foxtrot" merges: https://stackoverflow.com/questions/35962754/how-can-i-prevent-foxtrot-merges-in-my-master-branch
    - Hint: Don't run `git pull origin master`.
 - Predict merge conflicts pre-push: (TODO: @devinrhode2 has two flavors for this. One is focused on Azure DevOps, another is focused on BitBucket)
 - Normalize yarn.lock changes: (TODO: @devinrhode2 has an unpublished prototype for this)

# Formatting/prettier:
 - Automatically resolve conflicts after prettier formatting was applied to whole project: https://stackoverflow.com/a/71812873/565877
 - TODO: Script to help manage prettier upgrades
 
 
# Blogs/articles/discussions:
 - Discussions inside this repo: https://github.com/devinrhode2/awesome-git-history/discussions
 - 
