# RNN
循环神经网络详解

循环神经网络（Recurrent Neural Network，RNN）是一种用于处理序列数据的神经网络。相比一般的神经网络来说，他能够处理序列变化的数据。比如某个单词的意思会因为上文提到的内容不同而有不同的含义，RNN就能够很好地解决这类问题。

![图](https://pic3.zhimg.com/v2-4aae3943ad14c7b2e9d73ce47dcbbbae_r.jpg)

循环神经网络层只有一个cell。这个cell 的权重是共享的，上页的图只是代表了一个 cell 在不同时序的状态，训练样本的每个sample只会通过一个 cell，然后不断更新它的权重。
这也是RNN模型也称为递归神经网路模型的原因。

