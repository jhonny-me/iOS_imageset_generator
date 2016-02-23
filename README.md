# iOS_imageset_generater

这是Mac环境下针对iOS开发时UI提供3倍图，对应生成1倍与2倍图的脚本。

并且基于脚本使用automator创建了一个工作流。

---

## 使用方法

原始图片

![](http://i11.tietuku.com/dbe69a2a322fbea6.png)

### 脚本

将下载好的名为image的脚本文件copy到你常用的目录并配置环境变量

在终端键入```image <dirName>/<pngName>```

其中的dirName是装有图片的文件夹名称，pngName为单个图片名称

![脚本处理文件夹](https://raw.githubusercontent.com/jhonny-me/iOS_imageset_generator/master/pictures/dir_bash.gif)
![脚本处理单个文件](https://raw.githubusercontent.com/jhonny-me/iOS_imageset_generator/master/pictures/png_bash.gif)

### 右键菜单

双击下载的好的两个workflow文件并安装服务。

右键->服务->生成倍图

![右键文件夹](https://raw.githubusercontent.com/jhonny-me/iOS_imageset_generator/master/pictures/dir_click.gif)
![右键单个文件](https://raw.githubusercontent.com/jhonny-me/iOS_imageset_generator/master/pictures/png_click.gif)