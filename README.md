# Awesome-Analog-IC-Design-Automation

## Table of content

- Survey
- Papers
  - Analog Circuit Modeling
  - Analog Circuit Sizing Optimization & Analog Circuit Synthesis
  - Analog Circuit Performance Space Exploration
  - Analog Circuit Design Space Exploration
  - Analog Circuit Placement
  - Analog Circuit Routing
  - Analog IC Fault Testing and Diagnosis
  - Automation for Analog Circuit Cases
- Opensource Repositiories



## Survey

- Review: Machine Learning Techniques in Analog/RF Integrated Circuit Design, Synthesis, Layout, and Test [[PDF]](https://www.sciencedirect.com/science/article/abs/pii/S0167926020302947?casa_token=Hx7EK98EbcIAAAAA:39QF_rULshCpat5NXpVvCTwAebqRBQTsTCfp1gYmK2mubpu-4ubSebzDx5XGc-7XtkTfxUUrnw)
  - *Engin Afacan, Nuno Lourenço, RicardoMartins, Günhan Dündar, VLSI 20201*

- Applications of Artiﬁcial Intelligence on the Modeling and Optimization for Analog and Mixed-Signal Circuits: A Review [[PDF]](https://ieeexplore.ieee.org/abstract/document/9383813)
  - *Morteza Fayazi,  Zachary Colter, Ehsan Afshari,  and Ronald Dreslinski, IEEE TCAS-I 2021*
- Challenges and opportunities toward fully automated analog layout design [[PDF]](https://iopscience.iop.org/article/10.1088/1674-4926/41/11/111407/meta)
  - *Hao Chen, Mingjie Liu, Xiyuan Tang, Keren Zhu, Nan Sun, and David Z. Pan, JOS 2020*



## Papers

### Analog Circuit Modeling

- Co-learning Bayesian model fusion: Efﬁcient performance modeling of analog and mixed-signal circuits using side information [[PDF]](https://ieeexplore.ieee.org/abstract/document/7372621/)
  - *Fa Wang, Manzil Zaheer, Xin Li, Jean-Olivier Plouchart, and Alberto Valdes-Garcia, ICCAD, 2015*

- Efﬁcient hierarchical performance modeling for integrated circuits via Bayesian co-learning [[PDF]](https://dl.acm.org/doi/abs/10.1145/3061639.3062235)
  - *Mohamad Alawieh, Fa Wang, and Xin Li, DAC 2017*

- S<sup>2</sup>-PM semi-supervised learning for efﬁcient performance modeling of analog and mixed signal circuits [[PDF]](https://dl.acm.org/doi/abs/10.1145/3287624.3287657)
  - *Mohamed Baker Alawieh, Xiyuan Tang, and David Z. Pan, ASPDAC 2019*

- Rethinking sparsity in performance modeling for analog and mixed circuits using spike and slab models [[PDF]](https://dl.acm.org/doi/abs/10.1145/3316781.3317896)
  - *Mohamed Baker Alawieh, Sinead A. Williamson, and David Z. Pan, DAC 2019*

- Modelling a simple current to voltage converter using ANN [[PDF]](https://ieeexplore.ieee.org/abstract/document/7853224/authors#authors)
  - *Veepsa Bhatia, Kriti Gupta, Nidhi Batra, Neeta Pandey, ICPEICES 2016*

- Modelling and design of inverter threshold quantization based current comparator using artiﬁcial neural networks [[PDF]](https://www.researchgate.net/publication/299518789_Modelling_and_Design_of_Inverter_Threshold_Quantization_based_Current_Comparator_using_Artificial_Neural_Networks)
  - *Veepsa Bhatia, Neeta Pandey, Asok Bhattacharyya, International Journal of Electrical and Computer Engineering (IJECE) 2016*

### Analog Circuit Sizing Optimization

- Artiﬁcial Neural Network Assisted Analog IC Sizing Tool [[PDF]](https://ieeexplore.ieee.org/abstract/document/8795293)
  - *Gamze İslamoğlu, Tuğberk Oğulcan Çakici, Engin Afacan, Günhan Dündar, SMACD 2019*

- An efﬁcient Bayesian optimization approach for automated optimization of analog circuits [[PDF]](https://ieeexplore.ieee.org/abstract/document/8116661)
  - *Wenlong Lyu, Pan Xue, Fan Yang, Changhao Yan, Zhiliang Hong, Xuan Zeng, Dian Zhou, IEEE TCAS-I, 2018*

- Batch Bayesian optimization via multi-objective acquisition ensemble for automated analog circuit design [[PDF]](http://proceedings.mlr.press/v80/lyu18a.html?ref=https://githubhelp.com)
  - *Wenlong Lyu, Fan Yang, Changhao Yan, Dian Zhou, Xuan Zeng, PMLR,2018*

- Multi-objective bayesian optimization for analog/rf circuit synthesis [[PDF]](https://dl.acm.org/doi/abs/10.1145/3195970.3196078)
  - *Wenlong Lyu, Fan Yang, Changhao Yan, Dian Zhou, and Xuan Zeng, DAC 2018*

- Bayesian optimization approach for analog circuit synthesis using neural network [[PDF]](https://ieeexplore.ieee.org/abstract/document/8714788)
  - *Shuhan Zhang, Wenlong Lyu, Fan Yang, Changhao Yan, Dian Zhou, Xuan Zeng, DATE 2019*

- Analog circuit generator based on deep neural network enhanced combinatorial optimization [[PDF]](https://dl.acm.org/doi/abs/10.1145/3316781.3322468)
  - *Kourosh Hakhamaneshi, Nick Werblun, Pieter Abbeel, and Vladimir, DAC 2019*

- Smart-MSP: A self-adaptive multiple starting point optimization approach for analog circuit synthesis [[PDF]](https://ieeexplore.ieee.org/abstract/document/7984897/)
  - *Yishi Yang, Hengliang Zhu, Zhaori Bi, Changhao Yan, Dian Zhou, Yangfeng Su, Xuan Zeng,  IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems, 2017*

- Learning to design circuits [[PDF]](https://arxiv.org/abs/1812.02734)
  - *Hanrui Wang, Jiacheng Yang, Hae-Seung Lee, Song Han, arxiv 2020*

- A seizure-detection IC employing machine learning to overcome data-conversion and analog-processing non-idealities [[PDF]](https://ieeexplore.ieee.org/abstract/document/7338456)
  - *Jintao Zhang, Liechao Huang, Zhuo Wang, Naveen Verma, CICC 2015*

- Prediction of element values of OpAmp for required speciﬁcations utilizing deep learning [[PDF]](https://ieeexplore.ieee.org/abstract/document/8253353)
  - *Nobukazu Takai, Masafumi Fukuda, ISESD 2017*

- On the exploration of promising analog ic designs via artiﬁcial neural networks [[PDF]](https://ieeexplore.ieee.org/abstract/document/8434896)
  - *Nuno Lourenço, João Rosa, Ricardo Martins, Helena Aidos; António Canelas, Ricardo Póvoa, Nuno Horta, SMACD, 2018*

- RF-LNA circuit synthesis using an array of artiﬁcial neural networks with constrained inputs [[PDF]](https://ieeexplore.ieee.org/abstract/document/7168698)
  - *Etienne Dumesnil, Frederic Nabki, Mounir Boukadoum, ISCAS, 2015*

- Using Polynomial Regression and Artiﬁcial Neural Networks for Reusable Analog IC Sizing [[PDF]](https://ieeexplore.ieee.org/abstract/document/8795282)
  - *N. Lourenço, E. Afacan, R. Martins, F. Passos, A. Canelas, R. Póvoa, N. Horta, G. Dundar, SMCAD, 2019*

- Deep reinforcement learning for analog circuit sizing [[PDF]](https://ieeexplore.ieee.org/abstract/document/9181149)
  - *Zhenxin Zhao, Lihong Zhang, ISCAS 2020*

- AutoCkt: Deep Reinforcement Learning of Analog Circuit Designs [[PDF]](https://ieeexplore.ieee.org/abstract/document/9116200)
  - *Keertana Settaluri, Ameer Haj-Ali, Qijing Huang, Kourosh Hakhamaneshi, Borivoje Nikolic, DATE 2020*

- Deep Reinforcement Learning for Analog Circuit Sizing with an Electrical Design Space and Sparse Rewards [[PDF]](https://dl.acm.org/doi/abs/10.1145/3551901.3556474)
  - *Yannick Uhlmann, Michael Essich, Lennart Bramlage, Jürgen Scheible, and Cristóbal Curio, MLCAD 2022*

### Analog Circuit Performance Space Exploration

- An efﬁcient learning based approach for performance exploration on analog and RF circuit synthesis
  - *Po-Cheng Pan, Chien-Chia Huang, and Hung-Ming Chen, DAC 2019*
- 

## Opensource Repositories

