# global-alias
global-alias command with mac  
[![npm version](http://img.shields.io/badge/npm%20package-1.0.0-brightgreen.svg)](http://shields.io/)

## Install
`$ [sudo] npm install -g subl`

## Setting
以sublime Text为例:  

1. 打开mac下隐藏目录的bashrc文件: "bashrc"这个文件主要保存个人的一些个性化设置, 如命令别名\路径等. 也即在同一个服务器上, 只对某个用户的个性化设置相关.  
`$ vi .bashrc`  

2. 添加一个alias写入到bashrc文件中: alias 别名 \''目录'\'  
`$ alias subl=\''/Applications/Sublime Text.app/Contents/SharedSupport/bin/subl'\'`  

3. 保存bashrc后退出:  
`$ source ~/.bashrc`  

## Usage
打开当前目录  
`$ subl .`  

打开当前文件  
`$ subl xxx`
