## lcfu1主题

这个jekyll-theme是在[minima](https://github.com/jekyll/minima)的基础上修改的。

### 使用

1、Fork到你的github上

2、Settings-->GitHub Pages-->Change theme，随便选择一个theme然后Select theme。

![image.png](http://upload-images.jianshu.io/upload_images/6025530-5737301d4ddc8b2e.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

3、现在就可以看到如下图提示：

![image.png](http://upload-images.jianshu.io/upload_images/6025530-d32ad6a67df68004.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

4、修改Repository name

![image.png](http://upload-images.jianshu.io/upload_images/6025530-bc73f80282647360.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

5、根据需要修改_config.yml，这里只是简单说明了一下需要注意的点，如下：
- baidu_analytics：这个是百度站长统计，如下图获得你id粘贴到_config.yml。

![image.png](http://upload-images.jianshu.io/upload_images/6025530-47a46e3aa5998989.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

- github_star：这个是显示你博客在github上的star，填上你博客的github地址。
- theme：这个可以删除不要。

### 分类

1、修改这个theme主要是为了对文章进行多个分类。minima主题也可以在header上显示分类，但如果有很多分类，都放header上就显得拥挤了。
2、如_posts中的2018-1-27-first_categories.md就是一个分类。比如想要再弄个"学习笔记"分类，就可以复制修改2018-1-27-first_categories.md，这里的first_categories可以修改为你的分类名（尽量用英文），想要显示中文可以修改.md文件的layout-title，如：

![image.png](http://upload-images.jianshu.io/upload_images/6025530-4c72b47f0712fa81.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

还要修改.md文件的site.categories.first，first是你的categories，以后要在文章中用到，所以要注意填写。如下：

![image.png](http://upload-images.jianshu.io/upload_images/6025530-877298dbf9d35f81.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
