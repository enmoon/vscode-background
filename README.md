# vscode-background

[![Version](http://vsmarketplacebadge.apphb.com/version/shalldie.background.svg)](https://marketplace.visualstudio.com/items?itemName=shalldie.background)
[![Installs](http://vsmarketplacebadge.apphb.com/installs/shalldie.background.svg)](https://marketplace.visualstudio.com/items?itemName=shalldie.background)
[![Ratings](https://vsmarketplacebadge.apphb.com/rating/shalldie.background.svg)](https://vsmarketplacebadge.apphb.com/rating/shalldie.background.svg)

## Add a lovely background-image to your vscode.
 <br />
### Cross all themes, cross most os! 已支持所有主题，大部分操作系统(window,os x,linux?)！ 

### windows 与 os x 已经测试，欢迎品尝.

### Be sure to have administrator authority！！ 如果不能使用，请确保你有管理员权限！！


GitHub: [https://github.com/shalldie/vscode-background](https://github.com/shalldie/vscode-background)

Vscode Market: [https://marketplace.visualstudio.com/items?itemName=shalldie.background](https://marketplace.visualstudio.com/items?itemName=shalldie.background)

### U can config yourself background in settings.json .  在setting.json中，可以对background插件进行配置。
 <br />
![](https://raw.githubusercontent.com/shalldie/vscode-background/master/gif/settings.png)


### It looks like:
 <br />
![](https://raw.githubusercontent.com/shalldie/vscode-background/master/gif/show.gif)

<br />
***
Press F1,and you can get it by enter **ext install background** in your vscode. (～￣▽￣)～
<br />
<br />
你可以在vscode中，按下F1，然后输入 **ext install background** 来下载她 (～￣▽￣)～
*** 

**Enjoy!**

## 想了想，需要加个日志，就从这次开始吧，，I decide to add a log by now.

#### 2016/8/11
    修复vscode1.4下不能使用的问题。

#### 2016/8/21
    买了一台mac...于是把mac支持了。感谢 [@asteryk](https://github.com/shalldie/vscode-background/issues/2)  :D

### 2016/8/27
    重写了所有代码。  可以自动获取vscode安装目录，去除注入js的方式，改为直接修改css。
    windows 跟 mac 已经完全支持。  Linux 相信也没问题，，，但是这个我无法测试，ahaha。

### 2016/8/30
    之前文件名写错了...导致在linux下出错。 Sorry ... 该版本已修复.

### 2016/9/26
    1.将输入框改成配置文件 setting.json
    2.图片路径注入对时候，进行 encodeURI 编码，并用引号扩起来
    3.其它部分代码优化和更改