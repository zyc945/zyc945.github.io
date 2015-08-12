###用gem安装jekyll长时间无响应的一种解决办法
要安装jekyll了，可是运行

```
gem install jekyll
```
无响应。想可能是GFW的问题，于是用淘宝的源替换了一下，即可正常使用

```
 gem sources --remove http://rubygems.org/
 gem sources --remove https://rubygems.org/
 gem sources -a https://ruby.taobao.org/
```

出现：

```
*** CURRENT SOURCES ***

https://ruby.taobao.org
```
即可。


> 注：[https://ruby.taobao.org/](https://ruby.taobao.org/) 是rubygems.org 在国内的一个完整镜像，同步频率目前为15分钟一次，可以用此代替官方版本。

