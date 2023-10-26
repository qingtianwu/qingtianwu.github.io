---
layout: archive
permalink: /projects/
title: "Projects"
author_profile: true
redirect_from: 
  - /md/
  - /markdown.html
---

## Locations of key files/directories


不论你是用的是什么博客系统，WP也好，Typecho也罢，甚至是静态博客，就像我的博客，绕不开的是两种书写语言，一种称之为富文本，一种叫做Markdown。我的博客就是用Markdown写的。

Markdown有很多好处，也有很多坏处，比如说居中，Markdown本身没有这个功能。再比如说视频，Markdown也不具有插入视频的功能。

值得庆幸的是Markdown支持HTML的标签，在HTML中我们可以用`<video>`标签插入视频，在Markdown中，我们同样可以使用`<video>`标签插入视频，具体格式如下：

```HTML
<video width="320" height="240" controls>
    <source src="movie.mp4" type="video/mp4">
</video>
```

或者

```HTML
<video src="movie.mp4.mp4" controls="controls" width="500" height="300"></video>
```

当然，除了`.mp4`它还支持其他的格式，但是对于不同的浏览器支持的格式不一样，见下表：

<table id="tfhover" class="tftable" border="1">
<tr><th>格式</th><th>IE</th><th>Firefox</th><th>Opera</th><th>Chrome</th><th>Safari</th></tr>
<tr><td>Ogg</td><td>No</td><td>3.5+</td><td>10.5+</td><td>5.0+</td><td>No</td></tr>
<tr><td>MPEG4</td><td>9.0+</td><td>No</td><td>No</td><td>5.0+</td><td>3.0+</td></tr>
<tr><td>WebM</td><td>No</td><td>4.0+</td><td>10.6+</td><td>6.0+</td><td>No</td></tr>
</table>

当然还有编码等限制，这里就不再介绍，感兴趣的小伙伴可以百度上学习一下。

video 元素允许多个 source 元素。source 元素可以链接不同的视频文件。浏览器将使用第一个可识别的格式，这样我们只要多准备几个不同格式的视频就可以了。

用法：

```HTML
1. <video width="500" height="250" controls="controls">

2. <source src="movie.ogg" type="video/ogg">

3. <source src="movie.mp4" type="video/mp4">

4. 您的浏览器不支持此种视频格式。

5. </video>
```

其次，这是对一些参数的说明：

```HTML
autoplay :出现该属性意味着视频在就绪后将自动播放，用法：autoplay="autoplay"

controls :出现该属性意味着向用户显示控件，如播放按钮等，用法：controls="controls"

height:设置高度      width:设置宽度

loop:自动重播，用法：loop="loop"

preload:视频在页面加载时进行加载并预备播放，用法：preload="auto" - 当页面加载后载入整个视频；preload="meta" - 当页面加载后只载入元数据；preload="none" - 当页面加载后不载入视频。注意：若使用了autoplay，则忽略preload

src:要播放视频的url
```

示例：
第一种：

```HTML
<video width="720" height="303" controls> #或者：<video width:60% height:auto controls>
<source src="https://movie.cy798.cn/%E9%BB%91%E8%B1%B9.Black.Panther.2018.BD720P.X264.AAC.English.CHS-ENG.mp4" type="video/mp4">
</video>
```

<video width="720" height="303" controls>
<source src="https://movie.cy798.cn/%E9%BB%91%E8%B1%B9.Black.Panther.2018.BD720P.X264.AAC.English.CHS-ENG.mp4" type="video/mp4">
</video>

第二种：

```HTML
<video src="https://movie.cy798.cn/Blue.Planet.S02.2017.BluRay.1080p.DTS-HD.MA5.1.2Audio.x264-CHD/Blue.Planet.S02E01.One.Ocean.2017.BluRay.1080p.DTS-HD.MA5.1.2Audio.x264-CHD.mkv" controls="controls" width:100% height:auto></video>
```

<video src="https://movie.cy798.cn/Blue.Planet.S02.2017.BluRay.1080p.DTS-HD.MA5.1.2Audio.x264-CHD/Blue.Planet.S02E01.One.Ocean.2017.BluRay.1080p.DTS-HD.MA5.1.2Audio.x264-CHD.mkv" controls="controls" width="720" height="405"></video>