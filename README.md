# What Am I Reading Lately

## 录制完成的论文    


## 所有论文

包括已经录制完成和之后将要介绍的论文。选取的原则是10年内深度学习里有影响力文章（必读文章），或者近期比较有意思的文章。当然这十年里重要的工作太多了，不可能一一过一遍。在选取的时候我会偏向一些之前 [直播课](https://c.d2l.ai/zh-v2/) 中没讲到过的。 欢迎大家在 [讨论区](https://github.com/mli/paper-reading/discussions) 里提供建（点）议（歌）。

总论文数 67，录制完成数 32

（这里引用采用的是 semanticscholar，是因为它提供 [API](https://api.semanticscholar.org/api-docs/graph#operation/get_graph_get_paper) 可以自动获取，不用手动更新。）

### CV


| Read? | Year | Title                                                         | what do i think                 | citation |
| ------ | ---- | ------------------------------------------------------------ | -------------------- | ------------------------------------------------------------ |
| ✅      | 2012 | [AlexNet](https://papers.nips.cc/paper/2012/file/c399862d3b9d6b76c8436e924a68c45b-Paper.pdf) | 深度学习热潮的奠基作                   | [![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fabd1c342495432171beb7ca8fd9551ef13cbd0ff%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/ImageNet-classification-with-deep-convolutional-Krizhevsky-Sutskever/abd1c342495432171beb7ca8fd9551ef13cbd0ff) |
| | 2014 | [VGG](https://arxiv.org/pdf/1409.1556.pdf) | 使用 3x3 卷积构造更深的网络                   | [![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Feb42cf88027de515750f230b23b1a057dc782108%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Very-Deep-Convolutional-Networks-for-Large-Scale-Simonyan-Zisserman/eb42cf88027de515750f230b23b1a057dc782108) |
| | 2014 | [GoogleNet](https://arxiv.org/pdf/1409.4842.pdf) | 使用并行架构构造更深的网络                   | [![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fe15cf50aa89fee8535703b9f9512fca5bfc43327%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Going-deeper-with-convolutions-Szegedy-Liu/e15cf50aa89fee8535703b9f9512fca5bfc43327) |
|  ✅  | 2015 |  [ResNet](https://arxiv.org/pdf/1512.03385.pdf) | 构建深层网络都要有的残差连接。               |[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F2c03df8b48bf3fa39054345bafabfeff15bfd11d%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Deep-Residual-Learning-for-Image-Recognition-He-Zhang/2c03df8b48bf3fa39054345bafabfeff15bfd11d)  |
|  | 2017 | [MobileNet](https://arxiv.org/pdf/1704.04861.pdf) | 适合终端设备的小CNN                   |[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F3647d6d0f151dc05626449ee09cc7bce55be497e%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/MobileNets%3A-Efficient-Convolutional-Neural-Networks-Howard-Zhu/3647d6d0f151dc05626449ee09cc7bce55be497e)  |
| | 2019 | [EfficientNet](https://arxiv.org/pdf/1905.11946.pdf) | 通过架构搜索得到的CNN                   |[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F4f2eda8077dc7a69bb2b4e0a1a086cf054adb3f9%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/EfficientNet%3A-Rethinking-Model-Scaling-for-Neural-Tan-Le/4f2eda8077dc7a69bb2b4e0a1a086cf054adb3f9)  |
| | 2021 |  [Non-deep networks](https://arxiv.org/pdf/2110.07641.pdf) | 让不深的网络也能在ImageNet刷到SOTA                   | [![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F0d7f6086772079bc3e243b7b375a9ca1a517ba8b%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Non-deep-Networks-Goyal-Bochkovskiy/0d7f6086772079bc3e243b7b375a9ca1a517ba8b) |

### Multimodal

| Read? | Year | Title                                                         | what do i think                 | citation |
| ------ | ---- | ------------------------------------------------------------ | -------------------- | ------------------------------------------------------------ |
| ✅ | 2020 | [ViT](https://arxiv.org/pdf/2010.11929.pdf) | Transformer杀入CV界                   |[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F7b15fa1b8d413fbe14ef7a97f651f47f5aff3903%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/An-Image-is-Worth-16x16-Words%3A-Transformers-for-at-Dosovitskiy-Beyer/7b15fa1b8d413fbe14ef7a97f651f47f5aff3903)  |
| ✅ | 2021 |  [CLIP](https://openai.com/blog/clip/) | 图片和文本之间的对比学习                   |[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F6f870f7f02a8c59c3e23f407f3ef00dd1dcf8fc4%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Learning-Transferable-Visual-Models-From-Natural-Radford-Kim/6f870f7f02a8c59c3e23f407f3ef00dd1dcf8fc4)  |

### Generation

| Read? | Year | Title                                                         | what do i think                 | citation |
| ------ | ---- | ------------------------------------------------------------ | -------------------- | ------------------------------------------------------------ |
|  ✅ | 2014 | [GAN](https://papers.nips.cc/paper/2014/file/5ca3e9b122f61f8f06494c97b1afccf3-Paper.pdf) | 生成模型的开创工作                   |[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F54e325aee6b2d476bbbb88615ac15e251c6e8214%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Generative-Adversarial-Nets-Goodfellow-Pouget-Abadie/54e325aee6b2d476bbbb88615ac15e251c6e8214)  |

### NLP
| Read? | Year | Title                                                         | what do i think                 | citation |
| ------ | ---- | ------------------------------------------------------------ | -------------------- | ------------------------------------------------------------ |
| ✅ | 2017 | [Transformer](https://arxiv.org/abs/1706.03762) | 继MLP、CNN、RNN后的第四大类架构                   |[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F204e3073870fae3d05bcbc2f6a8e263d9b72e776%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Attention-is-All-you-Need-Vaswani-Shazeer/204e3073870fae3d05bcbc2f6a8e263d9b72e776)  |


### General New stuffs


| 已录制 | 年份 | 名字                                                         | 简介                 | 引用 |
| ------ | ---- | ------------------------------------------------------------ | -------------------- | ------------------------------------------------------------ |
| ✅ | 2021 | [AlphaFold 2](https://www.nature.com/articles/s41586-021-03819-2.pdf) | atomic level 3D protein prediction      |[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fdc32a984b651256a8ec282be52310e6bd33d9815%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Highly-accurate-protein-structure-prediction-with-Jumper-Evans/dc32a984b651256a8ec282be52310e6bd33d9815)  |

