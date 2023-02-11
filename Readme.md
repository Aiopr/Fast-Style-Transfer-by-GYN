# Effective Style Transfer

注：初次使用时，加载模型可能需要花费1-3min的加载时间，如超过3min，请更换网络进行尝试。

风格迁移经常被用于我们的日常生活中，比如我们常用的美图工具中的各类滤镜背后就是风格迁移技术。其实包括真人到二次元人物、二次元人物到真人之间的转换，还有妆容的迁移等都可以看作是风格迁移在一些特定领域的应用。

这个网页实现了任意图片（通过**select content/style**选择自己的图片）的风格迁移，其具有2种功能：

#### Stylize an image

将风格图片（style image）的风格迁移到内容图片（content image） 的内容中去。

#### Combine two images

将风格图片A（style image A）和风格图片B（style image B）的风格结合，再迁移到内容图片（content image）中去。

#### 交互功能

- 主要体现为用户可以提供自己的图片与网站进行交互，实现任意图片的风格迁移。
- 网站中设计了很多按钮，同时，对于每个按钮设置了一个说明的“？”键，当鼠标移动至“？”时，会显示按钮的详细功能。
- 提供了fast mode和high quality mode两种模式供用户选择。
- 开源制作，通过点击右上角的按钮，可以移动到Github源代码界面。

