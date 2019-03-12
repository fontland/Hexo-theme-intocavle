# Hexo-theme-intocavle
A custom theme for Hexo


## Installation
$ git clone https://github.com/fontland/Hexo-theme-intocavle themes/intocavle

## 说明

这个主题呈现的内容组织方式和界面设计基本重现了多年前我为自己设计的个人网站。

我想要的不只是一个博客，更像是一份电子杂志。主要的内容按category来分类，一篇文章应该只能属于一个category，在首页上会有每个category的入口，每个category也有自己的首页。

为每篇文章添加和去除category模拟了杂志的上线和下线功能，请把自己当前最希望呈现给读者的文章放在各个category下面。每个category下面的文章数量不宜太多，最好不要超过十篇。

在每篇文章的最下方有根据写作时间的前一篇和后一篇文章的链接以及文章的tag标签，读者可以快速访问相关内容。

读者可以通过每个页面左上角的存档链接访问全部历史文章的列表，即便这篇文章没有配置category。

首页封面图片默认为source/images路径下的cover.jpg,可以在theme/_config.yml的coverimg项进行修改。

各个category的封面图片应存放在source/images/categories下，在theme/_config.yml的categoryimg可以添加categoryname：category_coverimg这样的键值对来配置，例如：

categoryimg:

  人: /images/categories/f11f3a292df5e0fe282658245f6034a85edf72dd.jpg

  梦: /images/categories/P1180011.JPG

  思: /images/categories/IMGP3079x.jpg

上线的文章也要有自己的题图，只能使用jpg格式，题图名字与文章名相同，保存在source/images/下。


预览效果：fanjun.name
