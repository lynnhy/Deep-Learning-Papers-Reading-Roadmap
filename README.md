# Deep-Learning-Papers-Reading-Roadmap（深度学习论文阅读路线图）

## 深度学习基础及历史
### 1.0 书
- 深度学习圣经：Bengio, Yoshua, Ian J. Goodfellow, and Aaron Courville. “Deep learning.” An MIT Press book. (2015)

### 1.1 报告
- 三巨头报告：LeCun, Yann, Yoshua Bengio, and Geoffrey Hinton. “Deep learning.” Nature 521.7553 (2015)

### 1.2 深度信念网络 (DBN)
- 深度学习前夜的里程碑：Hinton, Geoffrey E., Simon Osindero, and Yee-Whye Teh. “A fast learning algorithm for deep belief nets.” Neural computation 18.7 (2006)
- 展示深度学习前景的里程碑：Hinton, Geoffrey E., and Ruslan R. Salakhutdinov. “Reducing the dimensionality of data with neural networks.” Science 313.5786 (2006)

### 1.3 ImageNet革命（深度学习大爆炸）
- AlexNet的深度学习突破：Krizhevsky, Alex, Ilya Sutskever, and Geoffrey E. Hinton. “Imagenet classification with deep convolutional neural networks.” Advances in neural information processing systems. 2012. 
- VGGNet深度神经网络出现：Simonyan, Karen, and Andrew Zisserman. “Very deep convolutional networks for large-scale image recognition.” arXiv preprint arXiv:1409.1556 (2014). 
- GoogLeNet：Szegedy, Christian, et al. “Going deeper with convolutions.” Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition. 2015. 
- ResNet极深度神经网络，CVPR最佳论文：He, Kaiming, et al. “Deep residual learning for image recognition.” arXiv preprint arXiv:1512.03385 (2015). 

### 1.4 语音识别革命
- 语音识别突破：Hinton, Geoffrey, et al. “Deep neural networks for acoustic modeling in speech recognition: The shared views of four research groups.” IEEE Signal Processing Magazine 29.6 (2012): 82-97. 
- RNN论文：Graves, Alex, Abdel-rahman Mohamed, and Geoffrey Hinton. “Speech recognition with deep recurrent neural networks.” 2013 IEEE international conference on acoustics, speech and signal processing. IEEE, 2013. 
- 端对端RNN语音识别：Graves, Alex, and Navdeep Jaitly. “Towards End-To-End Speech Recognition with Recurrent Neural Networks.” ICML. Vol. 14. 2014. 
- Google语音识别系统论文：Sak, Haşim, et al. “Fast and accurate recurrent neural network acoustic models for speech recognition.” arXiv preprint arXiv:1507.06947 (2015). 
- 百度语音识别系统论文：Amodei, Dario, et al. “Deep speech 2: End-to-end speech recognition in english and mandarin.” arXiv preprint arXiv:1512.02595 (2015). 
- 来自微软的当下最先进的语音识别论文：W. Xiong, J. Droppo, X. Huang, F. Seide, M. Seltzer, A. Stolcke, D. Yu, G. Zweig “Achieving Human Parity in Conversational Speech Recognition.” arXiv preprint arXiv:1610.05256 (2016). 

## 深度学习方法
### 2.1 模型
- Dropout：Hinton, Geoffrey E., et al. “Improving neural networks by preventing co-adaptation of feature detectors.” arXiv preprint arXiv:1207.0580 (2012). 
- 过拟合：Srivastava, Nitish, et al. “Dropout: a simple way to prevent neural networks from overfitting.” Journal of Machine Learning Research 15.1 (2014): 1929-1958. 
- Batch归一化——2015年杰出成果：Ioffe, Sergey, and Christian Szegedy. “Batch normalization: Accelerating deep network training by reducing internal covariate shift.” arXiv preprint arXiv:1502.03167 (2015). 
- Batch归一化的升级：Ba, Jimmy Lei, Jamie Ryan Kiros, and Geoffrey E. Hinton. “Layer normalization.” arXiv preprint arXiv:1607.06450 (2016). 
- 快速训练新模型：Courbariaux, Matthieu, et al. “Binarized Neural Networks: Training Neural Networks with Weights and Activations Constrained to+ 1 or−1.” 
- 训练方法创新：Jaderberg, Max, et al. “Decoupled neural interfaces using synthetic gradients.” arXiv preprint arXiv:1608.05343 (2016). 
- 修改预训练网络以降低训练耗时：Chen, Tianqi, Ian Goodfellow, and Jonathon Shlens. “Net2net: Accelerating learning via knowledge transfer.” arXiv preprint arXiv:1511.05641 (2015). 
- 修改预训练网络以降低训练耗时：Wei, Tao, et al. “Network Morphism.” arXiv preprint arXiv:1603.01670 (2016). 

### 2.2 优化
- 动量优化器：Sutskever, Ilya, et al. “On the importance of initialization and momentum in deep learning.” ICML (3) 28 (2013): 1139-1147. 
- 可能是当前使用最多的随机优化：Kingma, Diederik, and Jimmy Ba. “Adam: A method for stochastic optimization.” arXiv preprint arXiv:1412.6980 (2014). 
- 神经优化器：Andrychowicz, Marcin, et al. “Learning to learn by gradient descent by gradient descent.” arXiv preprint arXiv:1606.04474 (2016). 
- ICLR最佳论文，让神经网络运行更快的新方向：Han, Song, Huizi Mao, and William J. Dally. “Deep compression: Compressing deep neural network with pruning, trained quantization and huffman coding.” CoRR, abs/1510.00149 2 (2015). 
- 优化神经网络的另一个新方向：Iandola, Forrest N., et al. “SqueezeNet: AlexNet-level accuracy with 50x fewer parameters and< 1MB model size.” arXiv preprint arXiv:1602.07360 (2016). 

### 2.3 无监督学习 / 深度生成式模型
- Google Brain找猫的里程碑论文，吴恩达：Le, Quoc V. “Building high-level features using large scale unsupervised learning.” 2013 IEEE international conference on acoustics, speech and signal processing. IEEE, 2013. 
- 变分自编码机 (VAE)：Kingma, Diederik P., and Max Welling. “Auto-encoding variational bayes.” arXiv preprint arXiv:1312.6114 (2013). 
- 生成式对抗网络 (GAN)：Goodfellow, Ian, et al. “Generative adversarial nets.” Advances in Neural Information Processing Systems. 2014. 
- 解卷积生成式对抗网络 (DCGAN)：Radford, Alec, Luke Metz, and Soumith Chintala. “Unsupervised representation learning with deep convolutional generative adversarial networks.” arXiv preprint arXiv:1511.06434 (2015). 
- Attention机制的变分自编码机：Gregor, Karol, et al. “DRAW: A recurrent neural network for image generation.” arXiv preprint arXiv:1502.04623 (2015). 
- PixelRNN：Oord, Aaron van den, Nal Kalchbrenner, and Koray Kavukcuoglu. “Pixel recurrent neural networks.” arXiv preprint arXiv:1601.06759 (2016). 
- PixelCNN：Oord, Aaron van den, et al. “Conditional image generation with PixelCNN decoders.” arXiv preprint arXiv:1606.05328 (2016). 

### 2.4 RNN / 序列到序列模型
- RNN的生成式序列，LSTM：Graves, Alex. “Generating sequences with recurrent neural networks.” arXiv preprint arXiv:1308.0850 (2013). 
- 第一份序列到序列论文：Cho, Kyunghyun, et al. “Learning phrase representations using RNN encoder-decoder for statistical machine translation.” arXiv preprint arXiv:1406.1078 (2014). 
- 神经机器翻译：Bahdanau, Dzmitry, KyungHyun Cho, and Yoshua Bengio. “Neural Machine Translation by Jointly Learning to Align and Translate.” arXiv preprint arXiv:1409.0473 (2014). 
- 序列到序列Chatbot：Vinyals, Oriol, and Quoc Le. “A neural conversational model.” arXiv preprint arXiv:1506.05869 (2015). 

### 2.5 神经网络图灵机
- 未来计算机的基本原型：Graves, Alex, Greg Wayne, and Ivo Danihelka. “Neural turing machines.” arXiv preprint arXiv:1410.5401 (2014). 
- 强化学习神经图灵机：Zaremba, Wojciech, and Ilya Sutskever. “Reinforcement learning neural Turing machines.” arXiv preprint arXiv:1505.00521 362 (2015). 
- 记忆网络：Weston, Jason, Sumit Chopra, and Antoine Bordes. “Memory networks.” arXiv preprint arXiv:1410.3916 (2014). 
- 端对端记忆网络：Sukhbaatar, Sainbayar, Jason Weston, and Rob Fergus. “End-to-end memory networks.” Advances in neural information processing systems. 2015. 
- 指针网络：Vinyals, Oriol, Meire Fortunato, and Navdeep Jaitly. “Pointer networks.” Advances in Neural Information Processing Systems. 2015. 

### 2.6 深度强化学习
- 第一篇以深度强化学习为名的论文：Mnih, Volodymyr, et al. “Playing atari with deep reinforcement learning.” arXiv preprint arXiv:1312.5602 (2013). 
- 里程碑：Mnih, Volodymyr, et al. “DeepMind:Human-level control through deep reinforcement learning.” Nature 518.7540 (2015): 529-533. 
- ICLR最佳论文：Wang, Ziyu, Nando de Freitas, and Marc Lanctot. “Dueling network architectures for deep reinforcement learning.” arXiv preprint arXiv:1511.06581 (2015). 
- 当前最先进的深度强化学习方法：Mnih, Volodymyr, et al. “Asynchronous methods for deep reinforcement learning.” arXiv preprint arXiv:1602.01783 (2016). 
- DDPG：Lillicrap, Timothy P., et al. “Continuous control with deep reinforcement learning.” arXiv preprint arXiv:1509.02971 (2015). 
- NAF：Gu, Shixiang, et al. “Continuous Deep Q-Learning with Model-based Acceleration.” arXiv preprint arXiv:1603.00748 (2016). 
- TRPO：Schulman, John, et al. “Trust region policy optimization.” CoRR, abs/1502.05477 (2015). 
- AlphaGo：Silver, David, et al. “Mastering the game of Go with deep neural networks and tree search.” Nature 529.7587 (2016): 484-489. 

### 2.7 深度迁移学习 / 终生学习 / 强化学习
- Bengio教程：Bengio, Yoshua. “Deep Learning of Representations for Unsupervised and Transfer Learning.” ICML Unsupervised and Transfer Learning 27 (2012): 17-36. 
- 终生学习的简单讨论：Silver, Daniel L., Qiang Yang, and Lianghao Li. “Lifelong Machine Learning Systems: Beyond Learning Algorithms.” AAAI Spring Symposium: Lifelong Machine Learning. 2013. 
- Hinton、Jeff Dean大神研究：Hinton, Geoffrey, Oriol Vinyals, and Jeff Dean. “Distilling the knowledge in a neural network.” arXiv preprint arXiv:1503.02531 (2015). 
- 强化学习策略：Rusu, Andrei A., et al. “Policy distillation.” arXiv preprint arXiv:1511.06295 (2015). 
- 多任务深度迁移强化学习：Parisotto, Emilio, Jimmy Lei Ba, and Ruslan Salakhutdinov. “Actor-mimic: Deep multitask and transfer reinforcement learning.” arXiv preprint arXiv:1511.06342 (2015). 
- 累进式神经网络：Rusu, Andrei A., et al. “Progressive neural networks.” arXiv preprint arXiv:1606.04671 (2016). 

### 2.8 一次性深度学习
- 不涉及深度学习，但值得一读：Lake, Brenden M., Ruslan Salakhutdinov, and Joshua B. Tenenbaum. “Human-level concept learning through probabilistic program induction.” Science 350.6266 (2015): 1332-1338. 
- 一次性图像识别（暂无）：Koch, Gregory, Richard Zemel, and Ruslan Salakhutdinov. “Siamese Neural Networks for One-shot Image Recognition.”(2015). [pdf](http://www.cs.utoronto.ca/%7Egkoch/files/msc-thesis.pdf)
- 一次性学习基础（暂无）：Santoro, Adam, et al. “One-shot Learning with Memory-Augmented Neural Networks.” arXiv preprint arXiv:1605.06065 (2016). [pdf](http://arxiv.org/pdf/1605.06065)
- 一次性学习网络：Vinyals, Oriol, et al. “Matching Networks for One Shot Learning.” arXiv preprint arXiv:1606.04080 (2016). 
- 大型数据（暂无）：Hariharan, Bharath, and Ross Girshick. “Low-shot visual object recognition.” arXiv preprint arXiv:1606.02819 (2016). [pdf](http://arxiv.org/pdf/1606.02819)
