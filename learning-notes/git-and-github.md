# Git and GitHub notes

Use this file to record commands in your own words and examples from practice.

## Core workflow

```bash
git clone <repository-url>
cd <repository>
git switch -c fix/short-description
# make changes
git status
git diff
git add <files>
git commit -m "fix: describe the change"
git push -u origin fix/short-description
```

For a fork-based contribution, add the original project as `upstream`:

```bash
git remote add upstream <original-repository-url>
git fetch upstream
git switch main
git merge --ff-only upstream/main
```

## Topics to practise

- [ ] `status`, `diff`, `log`, `show`
- [ ] branches and upstream remotes
- [ ] merge conflicts
- [ ] `rebase` and when not to rewrite shared history
- [ ] `cherry-pick`
- [ ] amending a local commit
- [ ] keeping a fork up to date
- [ ] writing a useful commit message

## My explanations

Add short explanations here after practising each topic. Avoid copying definitions without understanding them.
