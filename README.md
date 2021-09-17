# 我的工作台

记录一些 系统/app 偏好的设置方式，方便今后使用新电脑/电脑重装时，快速配置。

## Mac

- Preference:

  - 键盘 => 快捷键

    - 输入法: `cmd + space`

    - 聚焦: `ctrl + tab`

  - 触控板

    - 查询与数据监测器: `三指轻点`

    - 打开`「轻点来点按」`

  - 辅助功能

    - 指针控制 => 触控板选项 => 启用拖移 => `三指拖移`

## iTerm2

- 安装: https://iterm2.com/

- Preference:

  - 新建 Tab 时使用上次的 path: Profile => Working Directory => 开启 `Reuse previous session's directory`

  - `vim ~/.vimrc`

  ```shell
  syntax enable
  syntax on

  set showmode
  set showcmd

  set number
  set cursorline
  set ruler

  set background=dark

  set mouse=a
  ```

## ohmyzsh

- 安装: https://github.com/ohmyzsh/ohmyzsh#basic-installation

- Preference:

  - `vim ~/.zshrc`

  ```shell
  alias zshconfig="mate ~/.zshrc"
  alias ohmyzsh="mate ~/.oh-my-zsh"
  alias gs="git status"
  alias gp="git push"
  alias ga="git add -p"
  alias gd="git diff"
  alias gdc="git diff --cached"
  alias gc="git commit"
  alias gb="git branch"
  alias gclc='git commit -v --reset-author -c `git log --pretty=%H -n1`'
  alias gcp="git cherry-pick"
  ```

## VS Code

- 开启 code 命令: `cmd + shift + p` => 输入 `shell command` => 选中 `Shell Command: Install ‘code’ command in PATH`

## Package

- 安装 Homebrew: https://brew.sh/

- 安装 node: `brew install node`

- 安装 yarn: `npm install -g yarn`

- 安装 nvm: `https://github.com/nvm-sh/nvm#install--update-script`

## Github

- 设置 username 和 email

```shell
git config --global user.name "Leecason"
git config --global user.email "leecason0722@gmail.com"
```
