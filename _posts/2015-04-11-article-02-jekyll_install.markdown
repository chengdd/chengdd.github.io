---
layout: post
title:  "jekyll 安装"
date:   2015-04-11 21:12:00
categories: jekyll
---
1.安装ruby

{% highlight javascript %}
sudo apt-get install ruby ruby-dev
{% endhighlight %}

2.更换ruby源

~~~
vim ~/.gemrc
在:sources:行下删除
- https://rubygems.org/
- http://rubygems.org/
增加：
- http://ruby.taobao.org/
~~~

或者:

~~~
 sudo gem sources –remove https://rubygems.org/
 sudo gem sources –remove http://rubygems.org/
 sudo gem sources -a http://ruby.taobao.org/
~~~

3.安装javascript运行环境

~~~
sudo apt-get install nodejs
~~~
4.安装jekyll


~~~
sudo gem install jekyll
~~~

5.运行jekyll server

~~~
jekyll new myblog
cd myblog
jekyll server
访问：http://127.0.0.1:4000/   
正常访问，则安装完毕
~~~

6.kramdown参考网址：

~~~
http://kramdown.gettalong.org/
~~~