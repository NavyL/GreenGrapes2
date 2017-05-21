# GreenGrapes2
一款有科技感颗粒、自定义头像的、功能丰富的、好看的标签云的typecho绿色主题
修改自[https://github.com/hongweipeng/GreenGrapes](https://github.com/hongweipeng/GreenGrapes "https://github.com/hongweipeng/GreenGrapes")

![](http://i.imgur.com/dD8mg7T.png)

## 使用方法 ##
1. 下载Typecho主题，得到一个文件夹
2. 重命名整个文件夹为`GreenGrapes2`并上传至`usr/themes/`目录下
3. 登陆自己的博客后台，在“控制台”的下拉菜单中选择“外观”选项进入已安装主题列表
4. 在相应的主题点击“启用”即可使用

**注意：请在/usr/uploads新建一个权限足够的名为`avatarCache`的目录用来存放头像缓存。
所谓权限足够就是PHP有足够的权限写入文件，一般也就是www:www/755或者干脆777**

## 增加的功能与特色 ##
* 增加了分享功能（插件来自于[river](https://github.com/revir/need-more-share2)）
* 页面和文章访问量统计（不需要插件）
* 改变协议为CC-BY-NC-SA4.0
* 去除页面最下方的备案信息、改成动态的颜文字
* 增加`meta theme color`使Chrome变色
* 增加侧边后台管理
* 启用侧边分类
* 启用页脚加载耗时
* 启用页脚运行时间
* 增加编辑按钮
* 增加字数统计
* 增加最后更新时间
* 增加文章数量统计
* 增加评论框特效（可以在主题中设置是否启用）
* 增加网站运行时间
* 评论头像QQ邮箱和Gravatar同时启用

优先QQ头像，然后是Gravatar，再之后是默认。已经启用了gravatar和QQ头像的缓存策略，所以基本上不会对网站速度有太大影响
* 主题增加设置缓存时间、设置建站日期
* 随机缩略图（分辨率为300*169）

如果文中包含图片的话，将会显示第一张图片作为背景；否则随机选择。请注意：只有在Typecho中添加的图片才会显示，如果是插入的外部图片，将被视为没有图片。
* 增加了404页面的动画选择
* 增加页面加载动画
* 新文章使用new标签
* 评论区可以设置显示UA、不显示UA、显示带图UA、为博主显示UA和图片。默认为为博主显示UA和图片
* 可选隐藏侧边博主回复
* 增加面包屑导航功能
* 两种新的markdown语法支持：拼音、高亮。

不知为何在某些环境版本上的Typecho，默认markdown引擎对于`~~删除线~~`的渲染会失败，所以主题暂时不开启渲染删除线而使用自带的引擎渲染。
* 站点统计功能，可以从百度统计等出粘贴代码，当然，不要粘贴进去自己想说的话，那样页面顶端会出现一些奇怪的东西。
* 三个杂项功能：平滑滚动效果、链接以新标签页形式打开、引用 Pangu.js 实现中英文间自动添加空格


## To do ##
- [ ] 点赞
- [ ] 集成各种插件
- [ ] 夜间模式
反正我也暂时不会完成，所以就先丢在这里吧嘿嘿嘿。

## Q&A ##
1. Q：文章底部版权信息的范例
A：如下，这里支持全部HTML语法，尽管如此，但是在这里加JS可能不太好，JS请加到上面的站点统计上。
```
文章版权归 <a href='{{homepage}}'>{{name}}</a> 所有，
本站默认采用 <a class="alert-link" target="_blank" href="https://creativecommons.org/licenses/by-nc-sa/4.0/">CC-BY-NC-SA 4.0</a>授权，
转载必须包含本声明，并以超链接形式注明原作者和本文原始地址：
<a href='{{link}}'>《{{title}}》</a>
```
2. Q：有的时候设置不生效是咋回事？
A：由于Typecho的一些限制，需要先切换到其他主题，然后再切换回本主题。注意，这样操作将会导致你**丢失全部自定义配置**。
3. Q：如何恢复初始配置？
A：如上，切换到其他主题、再切换回来即可。
4. Q：主题自动更新检查是个啥？
A：就是会和GitHub上的版本号进行比对，如果是新版本会有提示；目前由于一些技术问题，暂不支持自动更新。
5. Q：SNS太丑了
A：所以我不建议开启嘛……暂时还没优化样式。

## 更新历史 ##
我可没工夫写这玩意，直接看Git就得了。

## 演示 ##
[奔跑的蜗牛壳](https://www.mingyueli.com)
该站同时启用了snow、kiana等插件。

## 更多说明 ##

[戳我](https://www.bennythink.com/greengrapes2.html)来获得更多说明
