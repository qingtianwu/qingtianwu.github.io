---
layout: archive
permalink: /projects/
title: "Projects"
author_profile: true

---
## Real-Time Multitask Learning System for Joint  Detection of Face, Facial Landmark  and Head Pose
The rapid advancement of deep learning techniques has revolutionized the processing methods of various computer vision tasks, such as facial analysis, includ-
ing face detection, facial landmark detection (FLD), and head pose estimation (HPE) methods. This project shows the integration of these tasks, particularly when addressing the complexities posed by large-angle face poses. The primary contribution is the proposal of a real-time multitask detection system capable of simultaneously performing joint detection of faces, facial landmarks, and head poses. This system builds upon the widely adopted YOLOv8 detection framework. Here's a video to share:

![GIF](https://github.com/qingtianwu/qingtianwu.github.io/blob/master/_data/headpose.gif)

<iframe src="//player.bilibili.com/player.html?aid=790133335&bvid=BV1xy4y1w7nY&cid=1312248844&p=1" width="560" height="300"  scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true"> </iframe>

## Jointly Detecting Face and Facial Landmark from Cheap Operations and Driver Drowsiness Detection
Driver drowsiness detection (DDD) is a critical area of research with significant implications for public safety, especially in transportation [1] and healthcare sectors. Realtime DDD can provide timely warnings to drivers, thereby reducing the risk of accidents. Various approaches have been developed for driver drowsiness detection, including physiological measures, behavioral measures, and visual solutions. Detecting driver drowsiness in real-time is crucial for reducing the risk of road accidents and fatalities. However, current facial landmark-based methods can be hindered by various conditions, including driving at night, eye closures, and extreme head poses. To address these challenges, we propose a facial landmark-based approach using a YOLO-based network called YOLOLandmark, which can simultaneously detect faces and their dense (68) landmarks while analyzing the state of drowsiness using extracted eye and mouth information. Here's a video to share:

<iframe src="026n3.jpg" width="560" height="300"  scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true"> </iframe>

![GIF](026n3.jpg)

<img src="026n3.jpg" width="100" height="100" alt="AltText" />


## Intelligent human-machine interaction system

This system combines voice recognition as an entry point to perform various operations, including opening applications, controlling devices, and providing information. The development of this system requires in-depth expertise in voice recognition, natural language processing, internet connectivity, and human-machine interaction technologies. Additionally, it's important to ensure the system's scalability for easy integration of more functionalities and applications in the future. The system should also be adaptable to accommodate different user needs and allow for personalized settings and configurations. Here's a video to share:

<iframe src="//player.bilibili.com/player.html?aid=790163611&bvid=BV1iy4y1w7hr&cid=1312218152&p=1" width="560px" height="400" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true"> </iframe>


 
## YOLOLandmark: end-to-end face and FLD

端到端的人脸关键点检测

<iframe height=498 width=510 src="../_data/WIN_20230324_22_12_35_Pro.mp4"></iframe>

## YOLODDD: end-to-end face and DDD

端到端的司机疲劳检测

<iframe height=498 width=510 src="../_data/WIN_20230324_22_12_35_Pro.mp4"></iframe>




```HTML
<video width="320" height="240" controls>
    <source src="../_data/WIN_20230324_22_12_35_Pro.mp4" type="video/mp4">
</video>
```

或者

```HTML
<video src="../_data/WIN_20230324_22_12_35_Pro.mp4" controls="controls" width="500" height="300"></video>
```

当然，除了`.mp4`它还支持其他的格式，但是对于不同的浏览器支持的格式不一样，见下表：

<table id="tfhover" class="tftable" border="1">
<tr><th>格式</th><th>IE</th><th>Firefox</th><th>Opera</th><th>Chrome</th><th>Safari</th></tr>
<tr><td>Ogg</td><td>No</td><td>3.5+</td><td>10.5+</td><td>5.0+</td><td>No</td></tr>
<tr><td>MPEG4</td><td>9.0+</td><td>No</td><td>No</td><td>5.0+</td><td>3.0+</td></tr>
<tr><td>WebM</td><td>No</td><td>4.0+</td><td>10.6+</td><td>6.0+</td><td>No</td></tr>
</table>


video 元素允许多个 source 元素。source 元素可以链接不同的视频文件。浏览器将使用第一个可识别的格式，这样我们只要多准备几个不同格式的视频就可以了。

用法：

```HTML
1. <video width="500" height="250" controls="controls">

2. <source src="movie.ogg" type="video/ogg">

3. <source src="../_data/WIN_20230324_22_12_35_Pro.mp4" type="video/mp4">

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
<source src="../_data/WIN_20230324_22_12_35_Pro.mp4" type="video/mp4">
</video>
```

<video width="720" height="303" controls>
<source src="../_data/WIN_20230324_22_12_35_Pro.mp4" type="video/mp4">
</video>

第二种：

```HTML
<video src="../_data/WIN_20230324_22_12_35_Pro.mp4" controls="controls" width:100% height:auto></video>
```

<video src="../_data/WIN_20230324_22_12_35_Pro.mp4" controls="controls" width="720" height="405"></video> -->
