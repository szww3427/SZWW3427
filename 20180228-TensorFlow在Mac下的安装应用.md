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
2. 使用homebrew安装python
```Bash
brew install python
```
3. 使用easy_install安装pip
使用brew install安装会报错，所以使用easy_install
```Bash
sudo easy_install pip
```
4. 在python中安装TensorFlow
```Bash
sudo pip install https://storage.googleapis.com/tensorflow/mac/tensorflow-0.5.0-py2-none-any.whl
```

### 运行TensorFlow
```Python
$ python

>>> import tensorflow as tf
>>> hello = tf.constant('Hello, TensorFlow!')
>>> sess = tf.Session()
>>> print sess.run(hello)
Hello, TensorFlow!
>>> a = tf.constant(10)
>>> b = tf.constant(32)
>>> print sess.run(a+b)
42
>>>
```

### 安装好用的ide
ide很多推荐pycharm的，我没用过，之前用eclipse和idea用惯了，又因为eclipse免费，所以ide选择了eclipse。安装eclipse之后pydev插件，配置python解释器即可新建python 项目，编写程序


