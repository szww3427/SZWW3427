TensorFlow在Mac下的安装应用
=========================

### 安装
官方文档中推荐的安装方法如下：
1. 先安装软件包管理工具：homebrew
```Bash
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```
homebrew的卸载也很简单：
```Bash
$ cd `brew --prefix`
$ rm -rf Cellar
$ brew prune
$ rm `git ls-files`
$ rm -r Library/Homebrew Library/Aliases Library/Formula Library/Contributions
$ rm -rf .git
$ rm -rf ~/Library/Caches/Homebrew
```

