# TensorFlow 2.0 介绍

> 译者：[片刻](https://github.com/jiangzhonglian)

TensorFlow 2.0专注于简单性和易用性，具有热切执行，直观的高级API以及在任何平台上灵活构建模型等更新。从 [初学者笔记本](https://tensorflow.google.cn/beta/tutorials/quickstart/beginner)教程和[Effective TensorFlow 2.0](https://tensorflow.google.cn/beta/guide/effective_tf2)指南开始。安装TensorFlow 2.0 Beta预览包：

```python
$ pip install tensorflow==2.0.0-beta1
```

有关支持CUDA®的卡，请参阅[GPU指南](https://tensorflow.google.cn/install/gpu)。该 [TensorFlow 2.0社区测试FAQ](https://github.com/tensorflow/community/blob/master/sigs/testing/faq.md) 包含额外的兼容性和迁移的详细信息。


## 对于初学者

最好的起点是使用用户友好的Sequential API。通过将构建块插入一起来创建模型。
运行此[“Hello World”示例](https://colab.research.google.com/github/tensorflow/docs/blob/master/site/en/r2/tutorials/quickstart/beginner.ipynb)，然后阅读指南和教程以了解更多信息。

## 对于专家

Subclassing API为高级研究提供了一个按运行定义的界面。为您的模型创建一个类，然后强制写入前向传递。轻松编写自定义图层，激活和训练循环。
运行此[“Hello，World”示例](https://colab.research.google.com/github/tensorflow/docs/blob/master/site/en/r2/tutorials/quickstart/advanced.ipynb)，然后阅读指南和教程以了解更多信息。

<iframe width="863" height="485" src="https://www.youtube.com/embed/lEljKc9ZtU8" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<br/>
<table>
  <tr align="center">
    <td><a title="什么是TensorFlow 2.0" href="https://medium.com/tensorflow/whats-coming-in-tensorflow-2-0-d3663832e9b8" target="_blank"><font size="5">什么是TensorFlow 2.0</font></a> <br/> <br/> TensorFlow 2.0将专注于简单性和易用性：简单的模型构建，在任何平台上生产的强大模型部署，以及强大的研究实验。
</td>
    <td><a title="标准化Keras：TensorFlow 2.0中的高级API指南" href="https://medium.com/tensorflow/standardizing-on-keras-guidance-on-high-level-apis-in-tensorflow-2-0-bad2b04c819a" target="_blank"><font size="5">标准化Keras：TensorFlow 2.0中的高级API指南</font></a> <br/> <br/> 使用Keras作为TensorFlow的高级API，新的机器学习开发人员更容易开始使用TensorFlow。
</td>
    <td><a title="有助于TensorFlow：SIG，RFC，测试，文档" href="https://medium.com/tensorflow/contributing-to-tensorflow-sigs-rfcs-testing-and-docs-1c0f8240166c" target="_blank"><font size="5">有助于TensorFlow：SIG，RFC，测试，文档</font></a> <br/> <br/> TensorFlow一直受到社区的影响，我们很高兴能够在我们新的社区团体和流程的基础上建立多年的巨大贡献。
  </tr>
</table>
<br/>

---

除非另有说明，否则本页面的内容根据[知识共享署名4.0许可进行许可](https://creativecommons.org/licenses/by/4.0/)，代码示例根据[Apache 2.0许可进行许可](https://www.apache.org/licenses/LICENSE-2.0)。有关详细信息，请参阅[Google Developers网站政策](https://developers.google.cn/site-policies)。Java是Oracle和/或其附属公司的注册商标

