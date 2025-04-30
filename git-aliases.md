# Core git alias
alias g="git"

# Common operations
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

# Diff and clean
alias gd="git diff"
alias gds="git diff --staged"
alias gclean="git clean -fd"

# Pull / push
alias gup="git pull --rebase"
alias gps="git push"

# Logs and history
alias glog="git log --oneline"
alias gl="git log --oneline --graph --decorate --all"

# Stash
alias gsta="git stash"
alias gstp="git stash pop"

# Remote
alias grv="git remote -v"
alias grs="git remote show"

# Cherry pick, tags, blame
alias gcp="git cherry-pick"
alias gtag="git tag"
alias gtags="git tag -l"
alias gblame="git blame"

# Branch cleanup
alias gdelb="git branch -d"
alias gdelbf="git branch -D"
