# config
My Mac config



1. 키반복입력 : defaults write -g ApplePressAndHoldEnabled -bool false

2. homebrew : ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

3. zsh, OhMyZsh, iterm2 Theme : https://beomi.github.io/2017/07/07/Beautify-ZSH/

4. vi ~/.gitconfig

    [alias]
        co = checkout
        rb = rebase -i
        st = status
        cm = commit
        pl = pull
        ps = push
        lg = log --graph --abbrev-commit --decorate --format=format:'%C(cyan)%h%C(reset) - %C(green)(%ar)%C(reset) %C(white)%s%C(reset) %C(dim white)- %an%C(reset)%C(yellow)%d%C(reset)' --all
        ad = add
        tg = tag -n
        df = diff
        br = branch

