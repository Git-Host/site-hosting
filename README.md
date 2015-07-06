mediator
========

A medium inspired Jekyll blog theme. The basic idea came from the Ghost theme
[Readium 2.0](http://www.svenread.com/readium-ghost-theme/). I use mediator on my own blog [The Base](http://blog.base68.com).

Screenshots
--------
![screenshot](/assets/images/screenshot1.jpg)
![screenshot](/assets/images/screenshot2.jpg)
![screenshot](/assets/images/screenshot3.jpg)

Features
-------
* Fully Responsive layout
* Use header images in articles, if you want to (add tag "image" and url to the image in the front matter section of a post)
* Minimal design
* Featured article support
* FontAwesome implemented for easy use of icons fonts
* Free & Open Source Font usage

Getting Started
---
- [Fork this repository](https://github.com/dirkfabisch/mediator)
- Clone it: `git clone https://github.com/YOUR-USER/mediator`
- Install the [GitHub Pages gem](https://github.com/github/pages-gem) (includes Jekyll): `bundle install`
- Install the [Bourbon gem](https://github.com/thoughtbot/bourbon) `gem install bourbon`
- Run the jekyll server: `jekyll serve`

You should have a server up and running locally at <http://localhost:4000>.

Configuration
-----

The main settings happen in side of the _config.yml file:

### Site

Main settings for the site

* **title**: name of your site
* **description**: description of your site
* **logo**: small logo for the site (300x * 300x)
* **cover**: large background image on the index page

* **name**: name site owner
* **email**: mail address of the site owner
* **author**: author name
* **author_image**: small image of author (300x * 300px)


### Social

The template allows to add all major social plattforms to your site.
Fill the the form for each plattform. If you leave the share_* entries empty, the sharing buttons below a post are not shown.  If you leave the **url** and **desc** empty the icons are not shown on the index page, but the share icons on the article pages remains untouched (Thanks to [Phil](https://github.com/philsturgeon))

* **icon**:	name of social plattform (must match a name of [font-awsome](http://fortawesome.github.io/Font-Awesome/) icon set )
* **url**:	url of your account
* **desc**: slogan of the plattform
* **share_url**: share url
* **share_title**: first part of url for the title
* **share_link**: second part of the share url for the link to the post

The Liquid template engine will magical combine the different parts to a share url.

```
http://twitter.com/share?text=post_title&amp;url=post_url
````

See [_config.yml](https://github.com/dirkfabisch/mediator/blob/master/_config.yml) for more examples.

Licensing
---------

[MIT](https://github.com/dirkfabisch/madiator/blob/master/LICENSE) with no added caveats, so feel free to use this on your site without linking back to me or using a disclaimer or anything silly like that.

Contact
-------
I'd love to hear from you at [@dirkfabisch](https://twitter.com/dirkfabisch). Feel free to open issues if you run into trouble or have suggestions. Pull Requests always welcome.
特征

充分响应布局
使用在文章标题图片，如果你想（添加标签“形象”和URL到图像中的一个职位前事部）
简约的设计
精选文章支持
FontAwesome实现易于使用的图标字体
免费和开源字体使用
入门

叉这个仓库
克隆它：混帐克隆https://github.com/YOUR-USER/mediator
安装GitHub的网页的宝石（包括化身）：安装包
安装波旁宝石创业板安装波旁
运行服务器杰基尔：哲基尔服务
你应该有一台服务器并在http在本地运行：//本地主机：4000。

组态

主要设置发生在_config.yml文件的一面：

现场

该网站主要设置

标题：您的网站的名字
说明：您的网站的介绍
标志：小标识的网站（300X * 300倍）
盖：索引页大背景图片

名称：名站点所有者

电子邮件：网站所有者的邮件地址
作者：作者姓名
author_image：作者小图像（300X * 300像素）
社会

该模板允许所有重大社会plattforms添加到您的网站。填写表格为每个plattform。如果你离开share_ *项为空，下面一个帖子分享按钮不会显示。如果将URL和递减空的图标不索引页上显示，但文章页面上的共享图标保持不变（感谢菲尔）

图标：社会plattform的名称（必须字体要命的图标集的名称相匹配）
网址：网址您的帐户
说明：口号plattform的
share_url：共享网址
share_title：网址为题第一部分
share_link：共享URL的链接后第二部分
液体模板引擎将神奇结合不同地方的共享URL。

http://twitter.com/share?text=post_title&amp;url=post_url
见_config.yml更多的例子。

许可

麻省理工学院没有添加警告，可以随意在网站上使用这个链接不还给我或用免责声明或做傻事这样。

联系

我很想听到你在@dirkfabisch。随意，如果你遇到麻烦或有任何建议打开的问题。引入请求总是受欢迎的。
