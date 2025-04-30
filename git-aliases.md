
# 🔧 Git Aliases (Zsh-style)

This is a handy set of Git aliases to speed up your workflow in a Zsh shell. Each section is collapsible for readability.

---

<details>
<summary>🧱 Core</summary>

```zsh
alias g="git"
```

</details>

---

<details>
<summary>⚙️ Common Operations</summary>

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
alias gcb="git checkout -b"                # create and switch to new branch
alias gcurr="git rev-parse --abbrev-ref HEAD"  # show current branch
```

</details>

---

<details>
<summary>🧽 Diff & Clean</summary>

```zsh
alias gd="git diff"
alias gds="git diff --staged"
alias gclean="git clean -fd"
```

</details>

---

<details>
<summary>⬇️ Pull / Push</summary>

```zsh
alias gup="git pull --rebase"
alias gps="git push"
alias gl="git pull"
```

</details>

---

<details>
<summary>📜 Logs & History</summary>

```zsh
alias glog="git log --oneline"
alias glo="git log --oneline --graph --decorate --all"
```

</details>

---

<details>
<summary>📦 Stash</summary>

```zsh
alias gsta="git stash"
alias gstp="git stash pop"
```

</details>

---

<details>
<summary>🌍 Remote</summary>

```zsh
alias grv="git remote -v"
alias grs="git remote show"
```

</details>

---

<details>
<summary>🧪 Cherry-pick, Tags, Blame</summary>

```zsh
alias gcp="git cherry-pick"
alias gtag="git tag"
alias gtags="git tag -l"
alias gblame="git blame"
```

</details>

---

<details>
<summary>🧹 Branch Cleanup</summary>

```zsh
alias gdelb="git branch -d"
alias gdelbf="git branch -D"
```

</details>
