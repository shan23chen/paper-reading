# How do I go through CS paper:

<p>CS/informatics papers usually hold <strong>six</strong> main components:</p>
><ol>
<li>title</li>
<li>abstract</li>
<li>introduction</li>
<li>method</li>
<li>experiments</li>
<li>conclusion</li>
></ol>

<p>And I will spend time to run through the paper three times:</p>

> First round: Run through the title, abstract, conclusion. Take a look at important figures and tables in the Methods and Experiments section. In this way, you can spend more than ten minutes to understand whether the paper is suitable for your research direction. 

> Second round: After confirming that the paper is worth reading, you can quickly go through the whole paper. You don’t need to know all the details. You need to understand important figures and tables, know what each part is doing, and circle the relevant literature. If you think the article is too difficult, you can read the cited literature. 

> The third round: what problem to ask, what method to use to solve this problem. How the experiment was done. Close the article and recall what each section is about.

# How to edit this ReadMe

（Using semantics-scholar，Because its clean [API](https://api.semanticscholar.org/api-docs/graph#operation/get_graph_get_paper)）

How to use semantics-scholar's API:

(https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F + last chunk of slash in the url + %3Ffields%3DcitationCount) plus sign not included with no space

### Cool blog talk about new techs

[What is Diffusion](https://lilianweng.github.io/posts/2021-07-11-diffusion-models/) //
[Diffusion Demo with code](https://huggingface.co/blog/annotated-diffusion) //
[prompting intro](https://thegradient.pub/prompting/) //
[contrastive learning and multi-modal](https://nips.cc/media/neurips-2021/Slides/21895.pdf)

### What are we reading on next?


| Proposed by? | Year | Title                                                         | Date                 | citation |
| ------ | ---- | ------------------------------------------------------------ | -------------------- | ------------------------------------------------------------ |
| Shan    | 2022 | [Competence-based Multimodal Curriculum Learning for Medical Report Generation](https://aclanthology.org/2021.acl-long.234.pdf) | Sept,06/22 | [![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fa816733a342b68b75957cdda927424ff9cb04d42%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Competence-based-Multimodal-Curriculum-Learning-for-Liu-Ge/a816733a342b68b75957cdda927424ff9cb04d42) |



### CV


| Read? | Year | Title                                                         | what do i think                 | citation |
| ------ | ---- | ------------------------------------------------------------ | -------------------- | ------------------------------------------------------------ |
| ✅      | 2012 | [AlexNet](https://papers.nips.cc/paper/2012/file/c399862d3b9d6b76c8436e924a68c45b-Paper.pdf) | First big W for Deeplearning                   | [![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fabd1c342495432171beb7ca8fd9551ef13cbd0ff%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/ImageNet-classification-with-deep-convolutional-Krizhevsky-Sutskever/abd1c342495432171beb7ca8fd9551ef13cbd0ff) |

### Multimodal

| Read? | Year | Title                                                         | what do i think                 | citation |
| ------ | ---- | ------------------------------------------------------------ | -------------------- | ------------------------------------------------------------ |
| ✅ | 2020 | [ViT](https://arxiv.org/pdf/2010.11929.pdf) | Transformer into CV world                  |[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F7b15fa1b8d413fbe14ef7a97f651f47f5aff3903%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/An-Image-is-Worth-16x16-Words%3A-Transformers-for-at-Dosovitskiy-Beyer/7b15fa1b8d413fbe14ef7a97f651f47f5aff3903)  |
| ✅ | 2021 |  [CLIP](https://openai.com/blog/clip/) | unsupervised contrastive learning with huge amount data building a richer semantics             |[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F6f870f7f02a8c59c3e23f407f3ef00dd1dcf8fc4%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Learning-Transferable-Visual-Models-From-Natural-Radford-Kim/6f870f7f02a8c59c3e23f407f3ef00dd1dcf8fc4)  |

### Generation

| Read? | Year | Title                                                         | what do i think                 | citation |
| ------ | ---- | ------------------------------------------------------------ | -------------------- | ------------------------------------------------------------ |
|  ✅ | 2014 | [GAN](https://papers.nips.cc/paper/2014/file/5ca3e9b122f61f8f06494c97b1afccf3-Paper.pdf) | First GAN                   |[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F54e325aee6b2d476bbbb88615ac15e251c6e8214%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Generative-Adversarial-Nets-Goodfellow-Pouget-Abadie/54e325aee6b2d476bbbb88615ac15e251c6e8214)  |

### NLP
| Read? | Year | Title                                                         | what do i think                 | citation |
| ------ | ---- | ------------------------------------------------------------ | -------------------- | ------------------------------------------------------------ |
| ✅ | 2017 | [Transformer](https://arxiv.org/abs/1706.03762) | Best for NLP after (MLP、CNN、RNN)                  |[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F204e3073870fae3d05bcbc2f6a8e263d9b72e776%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Attention-is-All-you-Need-Vaswani-Shazeer/204e3073870fae3d05bcbc2f6a8e263d9b72e776)  |
| ✅ | 2022 | [Do Prompt-Based Models Really Understand the Meaning of Their Prompts?](https://aclanthology.org/2022.naacl-main.167.pdf) | prompt semantics not as how we think |[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F9ba50f992ccd92f428503ea6246157260a26cd77%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Do-Prompt-Based-Models-Really-Understand-the-of-Webson-Pavlick/9ba50f992ccd92f428503ea6246157260a26cd77) |



### General New stuffs


| Read? | Year | Title                                                         | what do i think                 | citation |
| ------ | ---- | ------------------------------------------------------------ | -------------------- | ------------------------------------------------------------ |
| ✅ | 2021 | [AlphaFold 2](https://www.nature.com/articles/s41586-021-03819-2.pdf) | atomic level 3D protein prediction      |[![citation](https://img.shields.io/badge/dynamic/json?label=citation&query=citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fdc32a984b651256a8ec282be52310e6bd33d9815%3Ffields%3DcitationCount)](https://www.semanticscholar.org/paper/Highly-accurate-protein-structure-prediction-with-Jumper-Evans/dc32a984b651256a8ec282be52310e6bd33d9815)  |

