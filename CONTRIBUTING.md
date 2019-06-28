# 贡献指南

> 请您勇敢地去翻译和改进翻译。虽然我们追求卓越，但我们并不要求您做到十全十美，因此请不要担心因为翻译上犯错——在大部分情况下，我们的服务器已经记录所有的翻译，因此您不必担心会因为您的失误遭到无法挽回的破坏。（改编自维基百科）

参考链接

* TensorFlow官网: [https://tensorflow.google.cn](https://tensorflow.google.cn)
* [TensorFlow R1.2 中文文档](http://cwiki.apachecn.org/display/TensorFlow)

负责人

+ [片刻](https://github.com/jiangzhonglian): 529815144

## 章节列表

* 快速入门
    * [开始使用TensorFlow 2.0](tutorials/quickstart/getting_started.md)
    * [Effective TensorFlow 2]()
    * [Migrate from TF 1 to TF 2]()
    * [Convert with the upgrade script]()
    * [Get started for beginners]()
    * [Get started for experts]()
* 初学者教程
    * ML basics
        * [Overview]()
        * [Classify images]()
        * [Classify text]()
        * [Classify structured data]()
        * [Regression]()
        * [Overfitting and underfitting]()
        * [Save and restore models]()
    * Images
        * [Convolutional neural networks]()
        * [Transfer learning with TFHub]()
        * [Transfer learning with pretrained CNNs]()
    * 文本和序列
        * [Word Embeddings 简介](tutorials/text/word_embeddings.md)
        * [Classify preprocessed text]()
        * [Classify text with a RNN]()
    * Estimators
        * [Premade estimators]()
        * [Linear models]()
* ADVANCED TUTORIALS
    * Customization
        * [Overview]()
        * [Tensors and operations]()
        * [Custom layers]()
        * [Automatic differentiation]()
        * [Custom training: basics]()
        * [Custom training: walkthrough]()
        * [TF function and AutoGraph]()
    * Text and sequences
        * [Generate text with an RNN]()
        * [Translation with attention]()
        * [Image captioning]()
        * [Transformer model for language understanding]()
    * lmage generation
        * [Style transfer]()
        * [DCGAN]()
        * [Pix2Pix]()
        * [CycleGAN]()
        * [Variational autoencoder]()
        * [Adversarial FGSM]()
    * Load and preprocess data
        * [CSV]()
        * [Numpy]()
        * [Pandas]()
        * [lmages]()
        * [Text]()
        * [TFRecords]()
        * [Unicode]()
        * [TF.Text]()
    * Distributed training
        * [Distributed training]()
        * [Distributed training with custom]()
        * [training loops]()
        * [Multi worker training with]()
        * [Estimator]()
        * [Multi worker training with Keras]()
* GUIDE
    * [Eager essentials]()
    * [Variables]()
    * [AutoGraph]()
    * Keras
        * [Keras overview]()
        * [Keras functional API]()
        * [Train and evaluate]()
        * [Write layers and models from scratch]()
        * [Save and serialize models]()
        * [Write custom callbacks]()
    * Accelerators
        * [Distribution strategy]()
        * [Using GPU]()
    * Data input pipelines
        * [tf.data Overview]()
        * [Performance]()
    * Serialization
        * [Checkpoints]()
        * [Saved models]()
    * Misc
        * [Version compatibility]()


## 流程

### 一、认领

首先查看[整体进度 - 等待中]()，确认没有人认领了你想认领的章节。
 
然后回复 ISSUE，注明“章节 + QQ 号”（一定要留 QQ）。

### 二、翻译

可以合理利用翻译引擎（例如[谷歌](https://translate.google.cn/)），但一定要把它变得可读！

可以参照之前版本的中文文档，如果有用的话。

如果遇到格式问题，请随手把它改正。

### 三、提交

**提交的时候不要改动文件名称，即使它跟章节标题不一样也不要改，因为文件名和原文的链接是对应的！！！**

+   `fork` Github 项目
+   将译文放在`docs/2.0`文件夹下
+   `push`
+   `pull request`

请见 [Github 入门指南](https://github.com/apachecn/kaggle/blob/master/docs/GitHub)。
