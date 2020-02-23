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


CNY 25,135

## Must Have

0. system update
1. kycloud & shadowsocks
2. xcode-select --install
3. brew.sh
4. iterm2
5. zsh
6. visual-studio-code (extensions)

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
  JavaScript (ES6) code snippets
  
```
  
  
keybinding:
```json
    [
        {
            "key": "alt+cmd+enter",
            "command": "git.sync"
        }
    ]
```

7. google-chrome (extensions)
  
- passive（Highly Suggested）
```conf
  ad-block
  refined-github
```
  
- active
```conf
    one click extensions manager
    outline
    onetab
    switchy omega
    sina-pic
    git-pod
    octotree
    uc-qrcode
    simple-read
    instapaper(optional)
    toby(or onetab)
    达达滑词翻译
```
8. git
9. nvm  & yarn

nvm 需要設置環境變量：
```conf
# NVM
export NVM_DIR=~/.nvm
source $(brew --prefix nvm)/nvm.sh
```
10. postman
11. spectacle
12. dotfiles
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
  ...
 - .prettierrc .npmrc .yarnrc  etc
```

for more: please check [dev-config](https://github.com/azl397985856/dev-config/blob/master/README.md)
13. preference

- Trackpad > Tap to click
- Keyboard > Key Repeat > Fast
- Keyboard > Delay Until Repeat > Short
- Dock > Automatically hide and show the Dock
- Security & Privacy > FileVault > Turn It On
- Security and Privacy > Firewall > Turn It On 
- File Sharing > Turn It Off
- iCloud > Find My Mac > Turn It On
14. file orgnazation
15. Finder
  - Sidebar
  - Show Path
  - Set Default Directory
16. ssh-keygen -t rsa -b 4096 -C "email@email.com"
17. alfred with powerpack
18. dash
19. switchy-host
20. foxmail
21. [Thor](https://apps.apple.com/cn/app/thor/id1120999687?mt=12)
22. [iina](https://iina.io/)
23. [ezip](https://ezip.awehunt.com/)

## Optional

1. docker
2. tree
3. slack
4. LaTex
5. charles
6. IOS Simulator & genymotion
7. iPic
8. DingTalk
9. Wechat
10. QQ
11. [cheat-sheet](https://www.cheatsheetapp.com/CheatSheet/)
12. youdao-note
13. karabiner-elements
14. hexo.sh 
> curl -s https://xaoxuu.com/install | sh -s hexo.sh 
15. git config
```conf
[user]
	name = lucifer
	email = lucifer@tsign.cn

```
16. preference

- Trackpad > Scroll & Zoom > uncheck scroll direction: Natural
- Users & Groups > Edit Avatar

17. dozer (bci dozer)
> bci for brew cask install

18. [snipaste](https://zh.snipaste.com/)

## Others

### 关于安装了agnoster主题有乱码的解决方法
```bash
git clone https://github.com/powerline/fonts.git --depth=1
cd fonts 
./install.sh
```
最后在iterm中选择字体即可，具体操作：iTerm → Preferences → Profiles → Text → Change Font→ Meslo
