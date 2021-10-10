# papers
一些AI方面paper整理

## transformer家族

### 国外论文

* [attention is all you need](https://arxiv.org/pdf/1706.03762v5.pdf)(2017)

> 谷歌最早的提出该架构的论文，使用多头自注意力机制代替了传统RNN以及Auto Encoder的方式

* [Informer: Beyond Efficient Transformer for Long Sequence Time-Series Forecasting](https://arxiv.org/pdf/2012.07436v3.pdf)(2020)

> 北航Zhou等人在2020年提出了一个应用在时序预测领域的模型,主要是在内存和时间复杂度上进行了优化,使用了周期性位置编码来强化序列特征提取,降低了注意力矩阵的计算复杂度,修改了子层堆叠的网络结构,解决了decoder中动态解码速度过慢的问题，适用于长序列预测

* [∞-former: Infinite Memory Transformer](https://arxiv.org/pdf/2109.00301.pdf)(2021)

> deepmind提出的对transformer-XL的改进,加入了一个LTM(序列记忆存储器)来优化transformer在长序列上预测的性能

* [Sparse and Continuous Attention Mechanisms](https://arxiv.org/pdf/2006.07214v3.pdf)(2020)


* [Autoformer: Decomposition Transformers with Auto-Correlation for Long-Term Series Forecasting](https://arxiv.org/pdf/2106.13008v2.pdf)(2021)

> 清华出品，超越了Informer的效果，提出了深度分解机制,并且用自相关代替了原来的self-attention,相比于Informer的效果更好

* [Dynamic Routing Between Capsules](https://arxiv.org/pdf/1710.09829.pdf)(2017)

> 动态路由,胶囊神经网络

* [OadTR: Online Action Detection with Transformers](https://arxiv.org/pdf/2106.11149.pdf)(2021)

> 达摩院将transformer用在视频流异常检测上的一种方法

* [Fastformer: Additive Attention Can Be All You Need](https://arxiv.org/pdf/2108.09084.pdf)(2021)

> 清华出品,在速度上相比于传统transformer有了极大的提升


### 国内论文
* [基于Transformer重建的时序数据异常检测与关系提取](https://kns.cnki.net/kcms/detail/detail.aspx?dbcode=CJFD&dbname=CJFDLAST2021&filename=JSJC202102010&uniplatform=NZKPT&v=g9BjGJf5ZLWE9o40R5TjbhtmjfoFxP542ZWNV%25mmd2FWpFkTv1AbENIJQjtHOFJ4nDUKo)(2020)

> 国内论文,比较简单列举了transformer在异常检测的应用
