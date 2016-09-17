---
title: 環境準備
date: 2016-09-18 00:50:01
tags:
---
準備順手的環境是最重要的，久久配置一次就老是會忘記，紀錄一下。

<!-- more -->

終端機用 iTerm，純文字代碼編寫用 Sumlime Text 3，Mac。

需要使用 Xcode 的透過 App Store 安裝，然後安裝終端機工具，輸入 `xcode-select --install`，根據跳出視窗點擊確認、安裝。

1. 安裝 [Homebrew](http://brew.sh/index_zh-tw.html)，輸入一行指令 `/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`
2. 首先安裝 Git，輸入 `brew install git`
3. 安裝 bash-completion
4. 安裝 pandoc

參考這篇 ihower 大神的 [Git 偏好設定](https://ihower.tw/blog/archives/5436)。

### Node 開發環境

為了可能會碰到使用不同 Node 版本的問題，不直接使用 Node 安裝程式，而是透過 [NVM](https://github.com/creationix/nvm) 安裝與管理多個版本。

``` bash
curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.32.0/install.sh | bash
```

之後修改 [.bash_profile](https://gist.github.com/wastemobile/e7aebc2078b2aae5bdfa93d99f93cbd6) 。

Node 安裝後第一件事，記得更新 NPM `npm update -g npm` ，接著再安裝必要的全域套件。

### Meteor

一行指令安裝 `curl https://install.meteor.com/ | sh`

### 開發主機環境

- 下載安裝 [Vagrant](https://www.vagrantup.com)
- 下載安裝 [VirgualBox](https://www.virtualbox.org)
- 安裝 Ansible via homebrew
- 安裝可以直接啟動 Digital Ocean 的外掛 `vagrant plugin install vagrant-digitalocean` 。參考[說明文件](https://github.com/devopsgroup-io/vagrant-digitalocean)。

準備好配對金鑰。


