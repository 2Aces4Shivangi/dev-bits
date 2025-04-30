
# 🚀 Git Aliases for Zsh (Oh My Zsh Plugin + Custom)

This file includes both standard Git aliases and additional advanced aliases from the Oh My Zsh `git` plugin. Use this to speed up your Git workflow.

---

## 🧱 Core

```zsh
alias g="git"
```

---

## ⚙️ Common Operations

```zsh
alias gst="git status"
alias gaa="git add --all"
alias ga="git add"
alias gco="git checkout"
alias gcm="git commit -m"
alias gca="git commit -a -m"
alias gamend="git commit --amend"
alias gcan="git commit --amend --no-edit"
alias gc="git clone"
alias gb="git branch"
alias gbr="git branch -r"
alias gcb="git checkout -b"
alias gcurr="git rev-parse --abbrev-ref HEAD"
```

---

## 🔍 Diff & Clean

```zsh
alias gd="git diff"
alias gds="git diff --staged"
alias gclean="git clean -fd"
```

---

## 🔄 Pull / Push

```zsh
alias gl="git pull"  # updated
alias gup="git pull --rebase"
alias gps="git push"
```

---

## 📜 Logs & History

```zsh
alias glog="git log --oneline"
alias glo="git log --oneline --graph --decorate --all"  # updated

```

---

## 📦 Stash

```zsh
alias gsta="git stash"
alias gstp="git stash pop"
```

---

## 🌍 Remote

```zsh
alias grv="git remote -v"
alias grs="git remote show"
```

---

## 🧪 Cherry-pick, Tags, Blame

```zsh
alias gcp="git cherry-pick"
alias gtag="git tag"
alias gtags="git tag -l"
alias gblame="git blame"
```

---

## 🧹 Branch Cleanup

```zsh
alias gdelb="git branch -d"
alias gdelbf="git branch -D"
```

---

## 🏷️ Tag Utilities (Oh My Zsh)

```zsh
alias gtl='gtl(){ git tag --sort=-v:refname -n --list "${1}*" }; noglob gtl'
alias gts="git tag --sign"
alias gtv="git tag | sort -V"
```

---

## 🚧 WIP (Work-In-Progress)

```zsh
alias gunignore="git update-index --no-assume-unchanged"
alias gunwip='git rev-list --max-count=1 --format="%s" HEAD | grep -q "--wip--" && git reset HEAD~1'
alias gwip='git add -A; git rm $(git ls-files --deleted) 2> /dev/null; git commit --no-verify --no-gpg-sign --message "--wip-- [skip ci]"'
alias gwipe='git reset --hard && git clean --force -df'
```

---

## 🌲 Git Worktree

```zsh
alias gwt="git worktree"
alias gwta="git worktree add"
alias gwtls="git worktree list"
alias gwtmv="git worktree move"
alias gwtrm="git worktree remove"
```
