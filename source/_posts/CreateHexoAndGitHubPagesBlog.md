---
title: Mac搭建Hexo + GitHub Pages博客
date: 2018-01-15 23:54:24
tags:
---

### GitHub配置

1. `GitHub`创建仓库

    创建一个`Repository name`为`GitHub的用户名.github.io`的仓库

2. 查看`GitHub Pages`功能是否开启

    创建完以后点击菜单`Settings`，找到`GitHub Pages-Source`选项，如果已经显示出`Your site is published at https://'GitHub的用户名'.github.io/`，则跳过以下步骤，如果选项内容为空，则选择`master branch`，点击`Save`。访问`https://'GitHub的用户名'.github.io/`，如果可以正常访问，那么`Github`的配置就结束了。


### 安装配置Hexo

1. 安装

    使用`NPM`安装`Hexo`，在命令行输入以下命令：

    ```shell
    npm install hexo-cli -g
    ```

    安装完以后，命令行输入：

    ```shell
    hexo version
    ```

    查看`Hexo`的版本

    进入到你要创建博客的目录，执行下列命令初始化`Hexo`

    ```shell
    hexo init blog

    cd blog

    npm install
    ```

    新建完成后，指定文件夹的目录如下：

    ```shell
    .
    ├── _config.yml
    ├── package.json
    ├── scaffolds
    ├── source
    |   ├── _drafts
    |   └── _posts
    └── themes
    ```

2. 配置Deployment

    修改`_config.yml`配置文件：
    a.把第 6 行的`title`改成你想要的名字
    b.把第 9 行的`author`改成你的大名
    c.把最后一行的`type`改成`type: git`，注意`type`冒号后面需要一个空格
    d.在最后一行后面新增一行，左边与`type`平齐，加上一行`repo: 仓库地址`（请将仓库地址改为`GitHub的用户名.github.io`对应的仓库地址，仓库地址以`git@github.com:`开头），注意`repo`冒号后面有一个空格
    配置完后，安装`Git`部署插件，命令行执行以下命令：`npm install hexo-deployer-git --save`

3. 发布文章

    命令行执行`hexo new XXX`，该命令会在以下路径：`创建的博客目录/source/_posts/`生成一个`MarkDown`文件，该文件内容就是文章内容，执行`open XXX.md`进行内容编辑，编辑完以后，命令行执行

    ```shell
    hexo generate

    hexo deploy
    ```

    就会把博客相关内容上传到前面配置的`GitHub`仓库地址。

    再次访问`https://'GitHub的用户名'.github.io/`，查看是否已经有新创建的文章，如果有，证明配置正确。

4. 更换主题

    - [https://github.com/hexojs/hexo/wiki/Themes](https://github.com/hexojs/hexo/wiki/Themes) 该网址提供了目前`Hexo`的主题。
    - 挑一个自己喜欢的主题，点击链接跳转到`GitHub`的首页，我选择的主题是：[https://github.com/iissnan/hexo-theme-next](https://github.com/iissnan/hexo-theme-next)
    - 复制该主题的`GitHub`地址，一般推荐`Use SSH`的地址，这里我的地址是：[git@github.com:iissnan/hexo-theme-next.git](git@github.com:iissnan/hexo-theme-next.git)
    - `cd 创建的博客目录/themes`
    - `git clone git@github.com:iissnan/hexo-theme-next.git`
    - `cd ../`
    - 将`_config.yml`的第 75 行改为`theme: hexo-theme-next`，保存并退出
    - `hexo generate`
    - `hexo deploy`
    - 等待博客相关内容上传到`GitHub`仓库地址后，再次访问`https://'GitHub的用户名'.github.io/`，查看主题是否生效。
