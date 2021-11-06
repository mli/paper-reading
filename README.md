# 深度学习论文精读


| 日期 | 标题 | 封面 | 时长 | 视频（4K） |
| -- | -- | -- | -- | -- |
| 录制中 | [BERT](https://arxiv.org/abs/1810.04805) |
| 录制中 | [GAN](https://arxiv.org/abs/1406.2661) | 
| 11/3/21 | 零基础多图详解 [图神经网络](https://distill.pub/2021/gnn-intro/)（GNN/GCN） | <img src="imgs/gnn.jpg" width="250px"/> | 66:19 | [B站](https://www.bilibili.com/video/BV1iT4y1d7zP/), [知乎](https://www.zhihu.com/zvideo/1439540657619087360), [YouTube](https://youtu.be/sejA2PtCITw) |
| 10/27/21 | [Transformer](https://arxiv.org/abs/1706.03762) 逐段精读<br> （视频中提到的文献 [^transformer]) |<img src="imgs/transformer.jpg" width="250px"/> | 87:05 |[B站](https://www.bilibili.com/video/BV1pu411o7BE/), [知乎](https://www.zhihu.com/zvideo/1437034536677404672), [YouTube](https://youtu.be/nzqlFIcCSWQ)|
| 10/22/21 | [ResNet](https://arxiv.org/abs/1512.03385) 论文逐段精读 | <img src="imgs/resnet-2.jpg" width="250px"/> | 53:46 | [B站](https://www.bilibili.com/video/BV1P3411y7nn/), [知乎](https://www.zhihu.com/zvideo/1434795406001180672), [YouTube](https://www.youtube.com/watch?v=pWMnzCX4cwQ) |
| 10/21/21 | 撑起计算机视觉半边天的 [ResNet](https://arxiv.org/abs/1512.03385) | <img src="imgs/resnet-1.jpg" width="250px"/> | 11:50 | [B站](https://www.bilibili.com/video/BV1Fb4y1h73E/), [知乎](https://www.zhihu.com/zvideo/1434787226101751808), [YouTube](https://www.youtube.com/watch?v=NnSldWhSqvY) |
| 10/15/21 | [AlexNet](https://papers.nips.cc/paper/2012/file/c399862d3b9d6b76c8436e924a68c45b-Paper.pdf) 论文逐段精读 | <img src="imgs/alexnet-2.jpg" width="250px"/> | 55:21 | [B站](https://www.bilibili.com/video/BV1hq4y157t1/), [知乎](https://www.zhihu.com/zvideo/1432354207483871232), [YouTube](https://www.youtube.com/watch?v=zjnxu8KUYKA) |
| 10/14/21 | 9年后重读深度学习奠基作之一：[AlexNet](https://papers.nips.cc/paper/2012/file/c399862d3b9d6b76c8436e924a68c45b-Paper.pdf) | <img src="imgs/alexnet-1.jpg" width="250px"/> | 19:59 | [B站](https://www.bilibili.com/video/BV1ih411J7Kz/), [知乎](https://www.zhihu.com/zvideo/1432155856322920448), [YouTube](https://www.youtube.com/watch?v=vdYH0fE6thY) |
| 10/06/21 | 如何读论文 | <img src="imgs/read-paper.jpg" width="250px"/> | 06:39 | [B站](https://www.bilibili.com/video/BV1H44y1t75x/), [知乎](https://www.zhihu.com/zvideo/1428973951632969728), [YouTube](https://www.youtube.com/watch?v=txjl_Q4jCyQ&list=PLFXJ6jwg0qW-7UM8iUTj3qKqdhbQULP5I&index=1) |


[^transformer]: 1 [斯坦福100+作者的200+页综述](https://arxiv.org/abs/2108.07258)，2 [对LayerNorm的新研究](https://arxiv.org/pdf/1911.07013.pdf)，3 [对Attention在Transformer里面作用的研究](https://arxiv.org/abs/2103.03404)

## 候选论文

考虑在之后视频中将要介绍的论文。选取的原则是10年内深度学习里有影响力文章（必读文章），或者近期比较有意思的文章。当然这十年里重要的工作太多了，不可能一一过一遍。在选取的时候我会偏向一些之前 [直播课](https://c.d2l.ai/zh-v2/) 中没讲到过的。 欢迎大家在 [讨论区](https://github.com/mli/paper-reading/discussions) 里提供（点）建议（歌）。

录一篇文章的时间大概是 8（之前低估成了5）个小时（录制、剪辑、上传），这里不算上读文章的时间。我一般是每天深夜找半个小时或者一个小时做一点。如果没有其他更紧要的事情的话，10天左右可以出一篇。如果大家热情 [加⭐ ](https://github.com/mli/paper-reading/stargazers) 话，可以多赶一赶🤣

下面列表将会持续更新（数字不代表讲的顺序）。

1. [Adam](https://arxiv.org/abs/1412.6980)。深度学习里最常用的优化算法之一。
3. [EfficientNet](https://arxiv.org/abs/1905.11946)。通过架构搜索得到的CNN，现在常被使用。
5. [GPT3](https://arxiv.org/abs/2005.14165)。朝着zero-shot learning迈了一大步。当然也得讲一讲GPT/GPT-2
7. [CLIP](https://openai.com/blog/clip/)。图片分类从此不用标数据。
8. [Non-deep networks](https://arxiv.org/pdf/2110.07641.pdf)。21年10月的新工作，让不深的网络也能在ImageNet刷到SOTA。
9. [为什么超大的模型泛化性不错](https://cacm.acm.org/magazines/2021/3/250713-understanding-deep-learning-still-requires-rethinking-generalization/fulltext)
11. [AlphaGo](https://deepmind.com/research/case-studies/alphago-the-story-so-far)。让强化学习出圈的一系列工作。
1. Swin Transformer
1. Out-of-distribution
1. AlphaFold
1. Contrastive learning
1. Video recognition
1. Anchor-free object detection
1. Knowledge graph
1. [MoCo](https://arxiv.org/abs/1911.05722), 对比学习让自监督训练的backbone比有监督训练的更香
1. [ViT](https://arxiv.org/abs/2010.11929), 开启CV界的transformer时代。
1. [Two-stream networks](https://arxiv.org/abs/1406.2199)，首次超越手工特征IDT的视频分类架构
