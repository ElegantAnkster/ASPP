# ASPP
A pytorch implementation of ASPP modul.

空洞空间卷积池化金字塔(atrous spatial pyramid pooling (ASPP))对所给定的输入以不同采样率的空洞卷积并行采样，相当于以多个比例捕捉图像的上下文。

每一个空洞卷积都会获得更大的感受野，对于大尺寸的目标检测比较友好。

ASPP可以获取不同尺度特征的空间信息，可以理解为多尺度的上下文信息。

在知乎上有个人回答的感觉挺好，上下文信息大概可以理解为：每一个像素不是孤立的，好多个像素组合在一起才能看得出要表达的画面，所以像素和像素之间是具有一定的关系，大量的像素以及他们之间的关系可以理解为上下文信息，也可以理解为感受野。
