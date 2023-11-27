# Welcome to MkDocs

For full documentation visit [mkdocs.org](https://www.mkdocs.org).

## Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.

## Project layout
    自测命令 mkdocs serve   mkdocs gh-deploy
    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        img/
            ...png
        文档1
        文档2
        
        ...       # Other markdown pages, images and other files.

wiki资源网站
https://lianghaoxun.github.io/pytorch_for_l_learn/
第 1 步：生成 SSH 密钥参考 
https://dev.classmethod.jp/articles/fix-gitgithub-com-permission-denied-publickey-fatal-could-not-read-from-remote-repository/

终端运行此命令，复制到github ssh秘钥即可
```python
ssh-keygen
```

更新github 的方法，在项目文件地址运行
```python
git init
git add .
git commit -m"update"
git remote add origin git@github.com:lianghaoxun/pytorch_for_l_learn.git
git push -u origin main
cd my-wiki
mkdocs gh-deploy
```





