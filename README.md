# Awesome-Analog-IC-Design-Automation

This is github for Survey for Analog-IC-Design-Automation.

## Table of content

- [Survey](#1)
- [Papers](#2)
  - [Analog Circuit Modeling](#2.1)
  - [Analog Circuit Sizing Optimization & Analog Circuit Synthesis](#2.2)
  - [Analog Circuit Performance Space Exploration](#2.3)
  - [Analog Circuit Analysis](#2.4)
  - [Analog Circuit Placement](#2.5)
  - [Analog Circuit Routing](#2.6)
  - [Synthesis-friendly Analog Circuits Design Automation](#2.7)
- [Open-source repositories](#3)

## <a id="1">Survey</a>

- Review: Machine Learning Techniques in Analog/RF Integrated Circuit Design, Synthesis, Layout, and Test [[PDF]](https://www.sciencedirect.com/science/article/abs/pii/S0167926020302947?casa_token=Hx7EK98EbcIAAAAA:39QF_rULshCpat5NXpVvCTwAebqRBQTsTCfp1gYmK2mubpu-4ubSebzDx5XGc-7XtkTfxUUrnw)
  - *Engin Afacan, Nuno Lourenço, RicardoMartins, Günhan Dündar, VLSI 2021*

- Applications of Artiﬁcial Intelligence on the Modeling and Optimization for Analog and Mixed-Signal Circuits: A Review [[PDF]](https://ieeexplore.ieee.org/abstract/document/9383813)
  - *Morteza Fayazi,  Zachary Colter, Ehsan Afshari,  and Ronald Dreslinski, IEEE TCAS-I 2021*
- Challenges and opportunities toward fully automated analog layout design [[PDF]](https://iopscience.iop.org/article/10.1088/1674-4926/41/11/111407/meta)
  - *Hao Chen, Mingjie Liu, Xiyuan Tang, Keren Zhu, Nan Sun, and David Z. Pan, JOS 2020*

## <a id="2">Papers</a>

### <a id="2.1">Analog Circuit Modeling</a>

- Efficient Performance Trade-off Modeling for Analog Circuit based on Bayesian Neural Network [[PDF]](https://ieeexplore.ieee.org/abstract/document/8942174)
  - *Zhengqi Gao, Jun Tao, Fan Yang, Yangfeng su, Dian zhou ,and Xuan Zeng, iccad 2019*

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

### <a id="2.2">Analog Circuit Sizing Optimization & Analog Circuit Synthesis</a>

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
- Domain Knowledge-Infused Deep Learning for Automated Analog/Radio-Frequency Circuit Parameter Optimization [[PDF]](https://dl.acm.org/doi/10.1145/3489517.3530501)
  - *Weidong Cao, Mouhacine Benosman, Xuan Zhang, Rui Ma, DAC 2022*
- VLSI Placement Parameter Optimization using Deep Reinforcement Learning [[PDF]](https://dl.acm.org/doi/10.1145/3400302.3415690)
  - *Anthony Agnesina, Kyungwook Chang, and Sung Kyu Lim, ICCAD 2020*
- GCN-RL Circuit Designer: Transferable Transistor Sizing with Graph Neural Networks and Reinforcement Learning [[PDF]](https://ieeexplore.ieee.org/abstract/document/9218757)
  - *Hanrui Wang, Kuan Wang, Jiacheng Yang, Linxiao Shen, Nan Sun, Hae-Seung Lee, Song Han, DAC 2020*

### <a id="2.3">Analog Circuit Performance Space Exploration</a>

- An efﬁcient learning based approach for performance exploration on analog and RF circuit synthesis [[PDF]](https://dl.acm.org/doi/abs/10.1145/3316781.3322467)
  - *Po-Cheng Pan, Chien-Chia Huang, and Hung-Ming Chen, DAC 2019*
- An Analog/RF Circuit Synthesis and Design Assistant Tool for Analog IP: DATA-IP [[PDF]](https://ieeexplore.ieee.org/abstract/document/8434906)
  - *Ezgi Kaya, Engin Afacan, Gunhan Dundar, SMACD 2018*

- Harvesting design knowledge from the internet: High-dimensional performance tradeoff modeling for large-scale analog circuits [[PDF]](https://ieeexplore.ieee.org/abstract/document/7131496)
  - *Jun Tao, Changhai Liao, Xuan Zeng, Xin Li, IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems 2016*

- An Artificial Neural Network Assisted Optimization System for Analog Design Space Exploration [[PDF]](https://ieeexplore.ieee.org/abstract/document/8937720)
  - *Yaping Li, Yong Wang, Yusong Li, Ranran Zhou, Zhaojun Lin, IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems 2020*

### <a id="2.4">Analog Circuit Analysis</a>

- S<sup>3</sup>DET: Detecting System Symmetry Constraints for Analog Circuits with Graph Similarity [[PDF]](https://ieeexplore.ieee.org/abstract/document/9045109)
  - *Mingjie Liu, Wuxi Li, Keren Zhu, Biying Xu, Yibo Lin, Linxiao Shen, Xiyuan Tang, Nan Sun, David Z. Pan, ASP-DAC 2020*

- Analog placement constraint extraction and exploration with the application to layout retargeting. [[PDF]](https://dl.acm.org/doi/abs/10.1145/3177540.3178245)
  - *Biying Xu, Bulent Basaran, Ming Su, and David Z. Pan, ISPD 2018*

- Towards decrypting the art of analog layout: Placement quality prediction via transfer learning. [[PDF]](https://ieeexplore.ieee.org/abstract/document/9116330)
  - *Mingjie Liu, Keren Zhu, Jiaqi Gu, Linxiao Shen, Xiyuan Tang, Nan Sun, David Z. Pan, DATE 2020*

- Analog layout synthesis with knowledge mining [[PDF]](https://ieeexplore.ieee.org/abstract/document/7300111)
  - *Po-Hsun Wu, Mark Po-Hung Lin, Tsung-Yi Ho, ECCTD 2015*

- A general approach for identifying hierarchical symmetry constraints for analog circuit layout [[PDF]](https://dl.acm.org/doi/abs/10.1145/3400302.3415685)
  - *Kishor Kunal, Jitesh Poojary, Tonmoy Dhar, Meghna Madhusudan, Ramesh Harjani, and Sachin S. Sapatnekar, ICCAD 2020.*

- GANA: Graph convolutional network based automated netlist annotation for analog circuits [[PDF]](https://ieeexplore.ieee.org/abstract/document/9116329)
  - *Kunal, Kishor and Dhar, Tonmoy and Madhusudan, Meghna and Poojary, Jitesh and Sharma, Arvind and Xu, Wenbin and Burns, Steven M. and Hu, Jiang and Harjani, Ramesh and Sapatnekar, Sachin S., DATE 2020*

- Closing the Design Loop: Bayesian Optimization Assisted Hierarchical Analog Layout Synthesis [[PDF]](https://ieeexplore.ieee.org/abstract/document/9218621/)
  - *Mingjie Liu, Keren Zhu, Xiyuan Tang, Biying Xu, Wei Shi, Nan Sun, David Z. Pan, DAC 2020*

- Design Rule Checking with a CNN Based Feature Extractor [[PDF]](https://dl.acm.org/doi/abs/10.1145/3380446.3430625)
  - *Luis Francisco, Tanmay Lagare, Arpit Jain, Somal Chaudhary, Madhura Kulkarni, Divya Sardana, W. Rhett Davis, and Paul Franzon, MLCAD 2020* 

- MLParest: Machine Learning based Parasitic Estimation for Custom Circuit Design [[PDF]](https://ieeexplore.ieee.org/abstract/document/9218495)
  - *Brett Shook, Prateek Bhansali, Chandramouli Kashyap, Chirayu Amin, Siddhartha Joshi, DAC 2020*
- A customized graph neural network model for guiding analog IC placement [[PDF]](https://dl.acm.org/doi/abs/10.1145/3400302.3415624)
  - Yaguang Li, Yishuang Lin, Meghna Madhusudan, Arvind Sharma, Wenbin Xu, Sachin S. Sapatnekar, Ramesh Harjani, and Jiang Hu, ICCAD 2020


### <a id="2.5">Analog Circuit Placement</a>

- Are Analytical Techniques Worthwhile for Analog IC Placement? [[PDF]](https://ieeexplore.ieee.org/document/9774498/)
  - *Yishuang Lin, Yaguang Li, Donghao Fang, Meghna Madhusudan, Sachin S. Sapatnekar, Ramesh Harjani, Jiang Hu, DATE 2022*

- Align: Open-source analog layout automation from the ground up [[PDF]](https://dl.acm.org/doi/abs/10.1145/3316781.3323471)
  - *Kishor Kunal, Meghna Madhusudan, Arvind K. Sharma, Wenbin Xu, Steven M. Burns, Ramesh Harjani, Jiang Hu, Desmond A. Kirkpatrick, and Sachin S. Sapatnekar, DAC 2019*

- Artiﬁcial Neural Networks as an Alternative for Automatic Analog IC Placement [[PDF]](https://ieeexplore.ieee.org/abstract/document/8795267/)
  - *Daniel Guerra, António Canelas, Ricardo Póvoa, Nuno Horta, Nuno Lourenço, Ricardo Martins, SMACD 2019*

- Semi-Supervised Artiﬁcial Neural Networks towards Analog IC Placement Recommender [[PDF]](https://ieeexplore.ieee.org/abstract/document/9181148)
  - *António Gusmão, Fábio Passos, Ricardo Póvoa, Nuno Horta, Nuno Lourenço, Ricardo Martins, ISCAS 2020*

- Wellgan: Generative-adversarial-network-guided well generation for analog/mixed-signal circuit layout [[PDF]](https://dl.acm.org/doi/abs/10.1145/3316781.3317930)
  - *Biying Xu, Yibo Lin, Xiyuan Tang, Shaolan Li, Linxiao Shen, Nan Sun, and David Z. Pan, DAC 2019*

- Two-step RF IC block synthesis with preoptimized inductors and full layout generation in-the-loop [[PDF]](https://ieeexplore.ieee.org/abstract/document/8356050/)
  - *Ricardo Martins, Nuno Lourenço, Fábio Passos, Ricardo Póvoa, António Canela, Elisenda Roca, Rafael Castro-López, Javier Sieiro, Francisco V. Fernandez, Nuno Horta, IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems 2019*

- Current-ﬂow and current-density-aware multi-objective optimization of analog IC placement [[PDF]](https://doi.org/10.1016/j.vlsi.2016.05.008)
  - *Ricardo Martins, Ricardo Póvoa, Nuno Lourenço, Nuno Horta, Integration 2016*

- Analog placement with current ﬂowand symmetry constraints using PCP-SP [[PDF]](https://dl.acm.org/doi/abs/10.1145/3195970.3195990)
  - *Abhishek Patyal, Po-Cheng Pan, Asha K A, Hung-Ming Chen, Hao-Yu Chi, and Chien-Nan Liu, DAC 2018*

- MAGICAL: Toward Fully Automated Analog IC Layout Leveraging Human and Machine Intelligence [[PDF]](https://ieeexplore.ieee.org/abstract/document/8942060/)
  - *Biying Xu, Keren Zhu, Mingjie Liu, Yibo Lin, Shaolan Li, Xiyuan Tang, Nan Sun, David Z. Pan, ICCAD 2019*

- GUI-Enhanced layout generation of ffe sst txs for fast high-speed serial link design [[PDF]](https://ieeexplore.ieee.org/abstract/document/9218723/)
  - *Seungho Han, Sungyu Jeong, Chanho Kim, Hong-June Park, Byungsub Kim, DAC 2020*

- BAG2: A process-portable framework for generator-based ams circuit design [[PDF]](https://ieeexplore.ieee.org/abstract/document/8357061)
  - *Eric Chang, Jaeduk Han, Woorham Bae, Zhongkai Wang, Nathan Narevsky, Borivoje NikoliC, Elad Alon, CICC 2018*

- Layout-dependent effects-aware analytical analog placement. [[PDF]](https://dl.acm.org/doi/abs/10.1145/2744769.2744865)
  - *Hung-Chih Ou, Kai-Han Tseng, Jhao-Yan Liu, I-Peng Wu, and Yao-Wen Chang, DAC 2015*

- Hierarchical and analytical placement techniques for high-performance analog circuits [[PDF]](Hierarchical and analytical placement techniques for high-performance analog circuits)
  - *Biying Xu, Shaolan Li, Xiaoqing Xu, Nan Sun, and David Z. Pan, ISPD 2017*

- Device layer-aware analytical placement for analog circuits. [[PDF]](https://dl.acm.org/doi/abs/10.1145/3299902.3309751)
  - *Biying Xu, Shaolan Li, Chak-Wa Pui, Derong Liu, Linxiao Shen, Yibo Lin, Nan Sun, ISPD 2019*

- Effective analog/mixed-signal circuit placement considering system signal flow [[PDF]](https://dl.acm.org/doi/abs/10.1145/3400302.3415625)
  - *Keren Zhu, Hao Chen, Mingjie Liu, Xiyuan Tang, Nan Sun, and David Z. Pan, ICCAD 2020*

- Exploring a machine learning approach to performance driven analog IC placement [[PDF]](https://ieeexplore.ieee.org/abstract/document/9154987)
  - *Yaguang Li, Yishuang Lin, Meghna Madhusudan, Arvind Sharma, Wenbin Xu, Sachin Sapatnekar, Ramesh Harjani, Jiang Hu, ISVLSI 2020*

- From Speciﬁcation to Silicon: Towards Analog/Mixed-Signal Design Automation using Surrogate NN Models with Transfer Learning [[PDF]](https://ieeexplore.ieee.org/abstract/document/9643445/)
  - *Juzheng Liu, Shiyu Su, Meghna Madhusudan, Mohsen Hassanpourghadi, Samuel Saunders, Qiaochu Zhang, Rezwan Rasul, Yaguang Li, Jiang Hu, Arvind Kumar Sharma, Sachin S. Sapatnekar, Ramesh Harjani, Ramesh Harjani, Sandeep Gupta, Mike Shuo-Wei Chen, ICCAD 2021*

### <a id="2.6">Analog Circuit Routing</a>

- A pre-search assisted ILP approach to analog integrated circuit routing [[PDF]](https://ieeexplore.ieee.org/abstract/document/7357110)
  - *Chia-Yu Wu, Helmut Graeb, Jiang Hu, ICCD 2015*


- Reliability-driven power/ground routing for analog ICs [[PDF]](https://dl.acm.org/doi/abs/10.1145/2071356.2071362)
  - *Jing-Wei Lin, Tsung-Yi Ho, and Iris Hui-Ru Jiang, ACM Transactions on Design Automation of Electronic Systems 2012*

- Toward silicon-proven detailed routing for analog and mixed-signal circuits [[PDF]](https://dl.acm.org/doi/abs/10.1145/3400302.3415660)
  - *Hao Chen, Keren Zhu, Mingjie Liu, Xiyuan Tang, Nan Sun, and David Z. Pan, ICCAD 2020*

- GeniusRoute: A new analog routing paradigm using generative neural network guidance. [[PDF]](https://ieeexplore.ieee.org/abstract/document/8942164)
  - *Keren Zhu, Mingjie Liu, Yibo Lin, Biying Xu, Shaolan Li, Xiyuan Tang, Nan Sun, David Z. Pan, ICCAD 2019*

- Attention Routing: Track-Assignment Detailed Routing Using Attention-Based Reinforcement Learning [[PDF]](https://asmedigitalcollection.asme.org/IDETC-CIE/proceedings-abstract/IDETC-CIE2020/V11AT11A002/1090194)
  - *Haiguang Liao, Qingyi Dong, Xuliang Dong, Wentai Zhang, Wangyang Zhang, Weiyi Qi, Elias Fallon, Levent Burak Kara, IDETC/DAC 2020*

### <a id="2.7">Synthesis-friendly Analog Circuits Design Automation</a>

- An all-digital scalable and reconfigurable wide-input range stochastic ADC using only standard cells [[PDF]](An all-digital scalable and reconfigurable wide-input range stochastic ADC using only standard cells.)
  - *Ahmed Fahmy, Jun Liu, Taewook Kim, Nima Maghari, IEEE Transactions on Circuits and Systems II 2015*

- A fully automated verilog-to-layout synthesized ADC demonstrating 56 dB-SNDR with 2 MHz-BW [[PDF]](https://ieeexplore.ieee.org/abstract/document/7387508/)
  - *Allen Waters, Un-Ku Moon, A-SSCC 2015*

- A reusable code-based SAR-ADC design with CDAC compiler and synthesizable analog building blocks [[PDF]](https://ieeexplore.ieee.org/abstract/document/8331129/)
  - *Min-Jae Seo, Yi-Ju Roh, Dong-Jin Chang, Wan Kim, Ye-Dam Kim, Seung-Tak Ryu, IEEE Transactions on Circuits and Systems II 2018*

- A fully synthesizable distributed and scalable all-digital LDO in 10 nm CMOS [[PDF]](https://ieeexplore.ieee.org/abstract/document/9063040/)
  - *Suyoung Bang, Wootaek Lim, Charles Augustine, Andres Malavasi, Muhammad Khellah, James Tschanz, Vivek De, ISSCC 2020*

- A 60-fJ/step 11-ENOB VCO-based CTDSM synthesized from digital standard cell library [[PDF]](https://ieeexplore.ieee.org/abstract/document/8780194/)
  - *Shaolan Li, Biying Xu, David Z. Pan, Nan Sun, CICC 2019*

- A scaling compatible, synthesis friendly VCO-based delta-sigma ADC design and synthesis methodology [[PDF]](https://dl.acm.org/doi/abs/10.1145/3061639.3062192)
  - *Biying Xu, Shaolan Li, Nan Sun, and David Z. Pan, ADC 2017*

- Edge-pursuit comparator: An energy-scalable oscillator collapse-based comparator with application in a 74.1 dB SNDR and 20 kS/s 15 b SAR ADC [[PDF]](https://ieeexplore.ieee.org/document/7815388)
  - *Minseob Shim, Seokhyeon Jeong, Paul D. Myers, Suyoung Bang, Junhua Shen, Chulwoo Kim, Dennis Sylvester, David Blaauw, Wanyeong Jung, IEEE Journal of Solid-State Circuits 2017*

- A Hybrid Design Automation Tool for SAR ADCs in IoT [[PDF]](https://ieeexplore.ieee.org/abstract/document/8463579)
  - *Ming Ding; Pieter Harpe; Guibin Chen; Benjamin Busze; Yao-Hong Liu; Christian Bachmann; Kathleen Philips, Arthur van Roermund, IEEE TVLSI 2018*

## <a id="3">Open-source Repositories</a>

[ALIGN-analoglayout/ALIGN-public](https://github.com/ALIGN-analoglayout/ALIGN-public)

[magical-eda/MAGICAL: Machine Generated Analog IC Layout](https://github.com/magical-eda/MAGICAL)

[thu-nics/awesome_ai4eda](https://github.com/thu-nics/awesome_ai4eda)

[ucb-art/BAG_framework](https://github.com/ucb-art/BAG_framework)

---

Collect by Xupengkai Lu (student of Institute of Computing Technology, Chinese Academy of Sciences) 

Any advice and suggestion can be provided by creating by issues or contact me for email luxupengkai21s@ict.ac.cn
