---
title: Mac安装和使用NVM
date: 2018-01-15T23:52:07.000Z
tags: null
---

### 前言

1. 什么是`NVM`

  `NVM`全称`Node Version Manager`，中文意思`Node版本管理工具`。(注：[GitHub地址](https://github.com/creationix/nvm))

2. 为什么要使用`NVM`工具

  a.因为`Node.js`不同版本支持的特性不一致，开发的项目需要涉及到兼容性问题。
  b.开发的项目涉及到某个模块只支持特定的`Node.js`版
  对于以上两种情况，我们都需要在开发的过程中切换`Node.js`不同版本，而`NVM`能够做到快速切换和管理`Node.js`版本，其实对于`NVM`可以理解为`Python`的`virtualenv`或者`Ruby`的`rvm`，每个`Node.js`版本的模块都会被安装在各自版本的沙箱里面。(注：[Node.js发展历史](http://www.infoq.com/cn/articles/node-js-and-io-js/))

### NVM安装

1. 安装

    ```shell
    curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.33.8/install.sh | bash
    ```

    该命令会从远程下载`install.sh`脚本并执行。注意这个版本数字`v0.33.8`会随着项目开发而变化，建议通过官方最新安装命令来检查最新安装版本，执行完上述命令，会创建`~/.nvm`文件夹，该文件夹就是`NVM`的安装路径。

2. 配置环境变量

    本人Mac使用的`Shell`是`ZSH`，所以需要在`~/.zshrc`这个文件中配置，如果你是使用默认的`Shell`，则需要在`~/.bash_profile`或者`~/.profile`文件中配置。请在`~/.zshrc`文件最后一行增加以下内容：

    ```shell
    export NVM_DIR="$HOME/.nvm"
    [ -s "$NVM_DIR/nvm.sh" ] && . "$NVM_DIR/nvm.sh" # This loads nvm
    ```

    该命令的作用是每次开启`Shell`环境，会自动把`NVM`加入到环境变量中。加入完成后在`Shell`环境下执行`source ~/.zshrc`命令重新启动一下配置。在`Shell`环境下执行`nvm`命令：

    ```shell
    ➜  ~  nvm

    Node Version Manager

    Note: <version> refers to any version-like string nvm understands. This includes:
      - full or partial version numbers, starting with an optional "v" (0.10, v0.1.2, v1)
      - default (built-in) aliases: node, stable, unstable, iojs, system
      - custom aliases you define with `nvm alias foo`

    Usage:
      nvm help                                  Show this message
      nvm --version                             Print out the latest released version of nvm
      nvm install [-s] <version>                Download and install a <version>, [-s] from source. Uses .nvmrc if available
        --reinstall-packages-from=<version>     When installing, reinstall packages installed in <node|iojs|node version number>
      nvm uninstall <version>                   Uninstall a version
      nvm use [--silent] <version>              Modify PATH to use <version>. Uses .nvmrc if available
      nvm exec [--silent] <version> [<command>] Run <command> on <version>. Uses .nvmrc if available
      nvm run [--silent] <version> [<args>]     Run `node` on <version> with <args> as arguments. Uses .nvmrc if available
      nvm current                               Display currently activated version
      nvm ls                                    List installed versions
      nvm ls <version>                          List versions matching a given description
      nvm ls-remote                             List remote versions available for install
      nvm version <version>                     Resolve the given description to a single local version
      nvm version-remote <version>              Resolve the given description to a single remote version
      nvm deactivate                            Undo effects of `nvm` on current shell
      nvm alias [<pattern>]                     Show all aliases beginning with <pattern>
      nvm alias <name> <version>                Set an alias named <name> pointing to <version>
      nvm unalias <name>                        Deletes the alias named <name>
      nvm reinstall-packages <version>          Reinstall global `npm` packages contained in <version> to current version
      nvm unload                                Unload `nvm` from shell
      nvm which [<version>]                     Display path to installed node version. Uses .nvmrc if available

    Example:
      nvm install v0.10.32                  Install a specific version number
      nvm use 0.10                          Use the latest available 0.10.x release
      nvm run 0.10.32 app.js                Run app.js using node v0.10.32
      nvm exec 0.10.32 node app.js          Run `node app.js` with the PATH pointing to node v0.10.32
      nvm alias default 0.10.32             Set default node version on a shell

    Note:
      to remove, delete, or uninstall nvm - just remove the `$NVM_DIR` folder (usually `~/.nvm`)
    ```

    如果看到以上内容，证明`NVM`安装成功。

### 通过NVM安装任意版本的Node.js

因为`NVM`的服务器放在国外，再加上其它原因，造成如果使用`NVM`默认服务器来下载`Node.js`会非常慢，所以我们要先修改`NVM`的服务器镜像地址，打开`~/.zshrc`配置文件，在最后一行，增加以下内容：

```shell
NVM_NODEJS_ORG_MIRROR=https://npm.taobao.org/mirrors/node/
```

加入完成后在`Shell`环境下执行`source ~/.zshrc`命令重新启动一下配置。在`Shell`环境下执行`nvm ls-remote`命令，查看一下服务器目前有哪些版本的`Node.js`可以安装：

```shell
➜  ~  nvm ls-remote
            v0.1.14
            v0.1.15
            v0.1.16
            ...
```

执行`nvm install 'Node.js版本号'`命令开始安装`Node.js`，安装完成以后`NVM`会将各个版本的`Node.js`安装在`~/.nvm/versions/node`目录下。

### NVM常用命令

* `nvm install <version>`## 安装指定版本，可模糊安装，如：安装v4.4.0，既可`nvm install v4.4.0`，又可`nvm install 4.4`
* `nvm uninstall <version>` ## 删除已安装的指定版本，语法与`install`类似
* `nvm use <version>` ## 切换使用指定的版本`Node.js`
* `nvm ls ##` 列出所有安装的版本
* `nvm ls-remote` ## 列出所以远程服务器的版本（官方Node.js Version List）
* `nvm current` ## 显示当前的版本
* `nvm alias <name> <version>` ## 给不同的版本号添加别名
* `nvm unalias <name>` ## 删除已定义的别名
* `nvm reinstall-packages <version>` ## 在当前版本`Node.js`环境下，重新全局安装指定版本号的`NPM`包