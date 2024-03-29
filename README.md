<p align="center"><img width="40%" src="https://github.com/Walhalla-Summary/Pytorch_Learning/blob/master/logo/pytorch_logo.png" /></p>

--------------------------------------------------------------------------------

Pytorch知识点总结、强化学习(Reinforcement Learning)、机器学习(Machine Learning)、神经网络(Neural Network)


PyTorch 是一个 Python 包，它提供了两个高级特性：

-   具有强大 GPU 加速功能的张量计算（如 NumPy）
-   建立在基于磁带的 autograd 系统上的深度神经网络


在粒度级别上，PyTorch 是一个由以下组件组成的库： 

|                          Component                           |                         Description                          |
| :----------------------------------------------------------: | :----------------------------------------------------------: |
|   [**torch**](https://pytorch.org/docs/stable/torch.html)    |          像 NumPy 这样的张量库，具有强大的 GPU 支持          |
| [**torch.autograd**](https://pytorch.org/docs/stable/autograd.html) |  一个基于tape的自动微分库，支持torch中所有可微分的张量运算   |
|  [**torch.jit**](https://pytorch.org/docs/stable/jit.html)   | 用于从 PyTorch 代码创建可序列化和可优化模型的编译堆栈 (TorchScript) |
|   [**torch.nn**](https://pytorch.org/docs/stable/nn.html)    |    与 autograd 深度集成的神经网络库，旨在实现最大的灵活性    |
| [**torch.multiprocessing**](https://pytorch.org/docs/stable/multiprocessing.html) | Python 多处理，但具有跨进程的火炬张量的神奇内存共享。对数据加载和 Hogwild 训练很有用 |
| [**torch.utils**](https://pytorch.org/docs/stable/data.html) |           DataLoader和其他实用程序功能，以方便使用           |

通常，PyTorch 用作：

-   替代 NumPy 以使用 GPU 的强大功能。
-   一个深度学习研究平台，可提供最大的灵活性和速度。


# PyTorch

- [前言·术语库](https://github.com/Walhalla-Summary/Pytorch_Learning/blob/master/pytorch/%E7%AC%AC%E9%9B%B6%E7%AB%A0%20%E5%89%8D%E8%A8%80%E6%9C%AF%E8%AF%AD%E5%BA%93.md)

- [第一章 Pytorch入门](https://github.com/Walhalla-Summary/Pytorch_Learning/blob/master/pytorch/%E7%AC%AC%E4%B8%80%E7%AB%A0%20Pytorch%E5%BF%AB%E9%80%9F%E5%85%A5%E9%97%A8.md)

- [第二章 Pytorch简介](https://github.com/Walhalla-Summary/Pytorch_Learning/blob/master/pytorch/%E7%AC%AC%E4%BA%8C%E7%AB%A0%20Pytorch%E7%AE%80%E4%BB%8B.md)

- [第三章 Pytorch张量基础](https://github.com/Walhalla-Summary/Pytorch_Learning/blob/master/pytorch/%E7%AC%AC%E4%B8%89%E7%AB%A0%20Pytorch%E5%BC%A0%E9%87%8F%E5%9F%BA%E7%A1%80.md)

- [第四章 Pytorch自动微分](https://github.com/Walhalla-Summary/Pytorch_Learning/blob/master/pytorch/%E7%AC%AC%E5%9B%9B%E7%AB%A0%20Pytorch%E8%87%AA%E5%8A%A8%E5%BE%AE%E5%88%86.md)


- [第五章 Pytorch模型构建](https://github.com/Walhalla-Summary/Pytorch_Learning/blob/master/pytorch/%E7%AC%AC%E4%BA%94%E7%AB%A0%20Pytorch%E6%A8%A1%E5%9E%8B%E6%9E%84%E5%BB%BA.md)

- [第六章 Pytorch激活函数](https://github.com/Walhalla-Summary/Pytorch_Learning/blob/master/pytorch/%E7%AC%AC%E5%85%AD%E7%AB%A0%20Pytorch%E6%BF%80%E6%B4%BB%E5%87%BD%E6%95%B0.md)

- [第七章 Pytorch损失函数](https://github.com/Walhalla-Summary/Pytorch_Learning/blob/master/pytorch/%E7%AC%AC%E4%B8%83%E7%AB%A0%20Pytorch%E6%8D%9F%E5%A4%B1%E5%87%BD%E6%95%B0.md)

- [第八章 Pytorch优化器](https://github.com/Walhalla-Summary/Pytorch_Learning/blob/master/pytorch/%E7%AC%AC%E5%85%AB%E7%AB%A0%20Pytorch%E4%BC%98%E5%8C%96%E5%99%A8.md)

- [第九章 Pytorch CUDA](https://github.com/Walhalla-Summary/Pytorch_Learning/blob/master/pytorch/%E7%AC%AC%E4%B9%9D%E7%AB%A0%20Pytorch%20CUDA.md)

- [第十章 Pytorch Utils](https://github.com/Walhalla-Summary/Pytorch_Learning/blob/master/pytorch/%E7%AC%AC%E5%8D%81%E7%AB%A0%20Pytorch%20utils.md)

- [第十一章 Pytorch Jit](https://github.com/Walhalla-Summary/Pytorch_Learning/blob/master/pytorch/%E7%AC%AC%E5%8D%81%E4%B8%80%E7%AB%A0%20Pytorch%20jit.md)

- [第十二章 Pytorch Multiprocessing](https://github.com/Walhalla-Summary/Pytorch_Learning/blob/master/pytorch/%E7%AC%AC%E5%8D%81%E4%BA%8C%E7%AB%A0%20Pytorch%20multiprocessing.md)


- [Pytorch怪巧奇技](https://github.com/Walhalla-Summary/Pytorch_Learning/blob/master/pytorch/Pytorch%E6%8A%80%E5%B7%A7.md)

- [Pytorch入门到精通](https://github.com/Walhalla-Summary/Pytorch_Learning/blob/master/pytorch/Pytorch%E5%85%A5%E9%97%A8%E5%88%B0%E7%B2%BE%E9%80%9A.md)


# 强化学习

- [第一章 强化学习基础](https://github.com/Walhalla-Summary/Pytorch_Learning/blob/master/RL/%E7%AC%AC%E4%B8%80%E7%AB%A0%20%E5%BC%BA%E5%8C%96%E5%AD%A6%E4%B9%A0%E5%9F%BA%E7%A1%80.md)

- [第二章 强化学习算法](https://github.com/Walhalla-Summary/Pytorch_Learning/blob/master/RL/%E7%AC%AC%E4%BA%8C%E7%AB%A0%20%E5%BC%BA%E5%8C%96%E5%AD%A6%E4%B9%A0%E7%AE%97%E6%B3%95.md)
