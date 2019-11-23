# Dev-Setup For Mac (I‘M a Front End Developer)

> Today is Sat 23 Nov 2019

## Model & Price

- 2.3GHz 8-core 9th-generation Intel Core i9 processor
- Turbo Boost up to 4.8GHz
- AMD Radeon Pro 5500M with 4GB of GDDR6 memory
- 32GB 2666MHz DDR4 memory
- 1TB SSD storage¹
- 16-inch Retina display with True Tone
- Touch Bar and Touch ID
- Four Thunderbolt 3 ports


RMB 25,135

## Must Have

0. system update
1. xcode-select --install
2. brew.sh
3. iterm2
4. zsh
5. visual-studio-code (extensions)

  > cat extensions.txt | xargs -L1 code --install-extension
  > setting-sync
  
extensions:
```conf
  vscode-leetcode
  scode-import-cost
  vscode-eslint
  remote-ssh
  prettier-vscode
  path-intellisense
  npm-intellisense
  Material-theme
  githistory
  gitblame or gitlens
  debugger-for-chrome
  code-settings-sync
  bracket-pair-colorizer
  better-comments
  carbon-now-sh
  vsliveshare
  
```
  
  
keybinding:
```json
    // 将键绑定放在此文件中以覆盖默认值auto[]
    [
        {
            "key": "alt+cmd+enter",
            "command": "git.sync"
        }
    ]
```
6. google-chrome (extensions)
  
6.1. passive（Highly Suggested）
```conf
  ad-block
  refined-github
```
  
6.2. active
```conf
    outline
    onetab
    switchy omega
    sina-pic
    git-pod
    uc-qrcode
```
7. git
8. nvm  & yarn
9. postman
10.spectacle
11. dotfiles
 - alias 
```conf
  alias cls='clear'
  alias nis='cnpm i --save'
  alias myip='curl http://ipecho.net/plain'
  alias s="sudo"
  ...
```
 - ZSH_THEME (agnoster for example)
```conf
  ZSH_THEME="agnoster"
  # to hide the username@hostname
  USER=``
```
12. preference

- Trackpad > Tap to click
- Keyboard > Key Repeat > Fast
- Keyboard > Delay Until Repeat > Short
- Dock > Automatically hide and show the Dock
- Security & Privacy > FileVault > Turn It On
- Security and Privacy > Firewall > Turn It On 
- File Sharing > Turn It Off
- iCloud > Find My Mac > Turn It On
13. file orgnazation
14. Finder
  - Sidebar
  - Show Path
  - Set Default Directory
15. ssh-keygen -t rsa -b 4096 -C "email@email.com"
16. alfred with powerpack
17. dash

## Optional

1. docker
2. tree
3. slack
4. LaTex
5. charles
6. IOS Simulator & genymotion
5. git config
```conf
[user]
	name = lucifer
	email = lucifer@tsign.cn

```
6. preference

- Trackpad > Scroll & Zoom > uncheck scroll direction: Natural
- Users & Groups > Edit Avatar
