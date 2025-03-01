# 论文中提出了基于Two-fold Group Lasso的轻量级深度神经网络，并对同一调制模式下的信号识别取得了不错的效果
用到2016.10b数据集，可以作为方案（1）使模型轻量化，也可以作为方案（2）能很好的识别同一调制模式下的信号，如QAM16和QAM64。

# Group-Sparse-DNN-for-AMC
A Two-fold Group Lasso based Lightweight Deep Neural Network for Automatic Modulation Classification

Automatic modulation classification (AMC) is a hot topic in modern wireless communication, which is a classification problem essentially. The deep learning methods have been applied to AMC gradually, for its excellent performance in classification, regression and decision-making tasks. However, the deep learning methods always come with complex network structure, vast training parameters and extra long training time, which seriously affected its application and promotion on power-limited and resource-constrained devices. In this paper, we propose a lightweight end-to-end AMC model named lightweight deep neural network (LDNN) via a novel group-level sparsity inducing norm, which can help network pruning itself automatically to obtain a highly compact network. In order to solve the problem of recognition confusing types, such as QAM16 and QAM 64 are always been confused in AMC task,  a improved two-step training lightweight deep neural network (TLDNN) is well designed to improve the recognition accuracy. Experimental results shows the accuracy improvement of the proposed lightweight compact networks via two-fold group lasso regularization and two-step training schemes.

(The dataset used is avaliable on: https://www.deepsig.io/datasets)
