
---
title: Python库安装
---
{% note success %}
文字 或者 `markdown` 均可
{% endnote %}
> 1、有时候安装会遇到很多问题，有时候是网络问题，有时候是代码输入问题（ 问题二： Microsoft Visual C++ 14.0 is required.（一般我们的win电脑都会缺这玩意） ）
>
> 2、新方法：下载下来``` whl```文件或者```zip、gz、rar```压缩包文件，放入到本地，然后启动安装即可

## Python库下载网站

1、 https://pypi.org/ 

![](https://gitee.com/lemon0828/tuchuang/raw/master/img/20200515232120.png)

在上面的网站搜索框写入即可

2、 https://www.lfd.uci.edu/~gohlke/pythonlibs/ （这个网站里面使用Ctrl+F搜索）来自知乎 https://zhuanlan.zhihu.com/p/37995301 

![](https://gitee.com/lemon0828/tuchuang/raw/master/img/20200515232733.png)

## 安装历程（以pyaudia为例）

1、以pip install pyaudio安装的话会出现下面问题

![](https://gitee.com/lemon0828/tuchuang/raw/master/img/20200515232713.png)

2、我们下载whl文件如下

![]( https://gitee.com/lemon0828/tuchuang/raw/master/img/20200515232909.png )

#### 38是指python版本，win32指的是系统型号

![](https://gitee.com/lemon0828/tuchuang/raw/master/img/20200515233146.png)

3、下载下来之后，安装代码如下

```shell
pip install PyAudio-0.2.11-cp38-cp38-win32.whl
```

至此安装完毕！







