- [Awesome GNN](#awesome-gnn)
  - [Tutorials and Surveys](#tutorials-and-surveys)
    - [Video and Side Courses](#video-and-side-courses)
    - [Brief Tutorials](#brief-tutorials)
  - [Definitions and Methods](#definitions-and-methods)
  - [Applications](#applications)
    - [Recommendation System](#recommendation-system)
    - [Videos Understanding](#videos-understanding)
  - [Adversarial Attacks on GNNs](#adversarial-attacks-on-gnns)
  - [Interpretability of GNNs](#interpretability-of-gnns)
  - [Privacy of GNNs](#privacy-of-gnns)
  - [Federated GNNs](#federated-gnn)

# Awesome GNN

The most related repositories：

1. https://github.com/thunlp/GNNPapers

2. https://github.com/ChandlerBang/awesome-graph-attack-papers
3. https://github.com/safe-graph/graph-adversarial-learning-literature
4. https://github.com/gitgiter/Graph-Adversarial-Learning

## Books

- 刘忠雨，李彦霖，周洋 著. 深入浅出图神经网络：GNN原理解析, 北京：机械工业出版社，2020.
- William L. Hamilton, Graph Representation Learning. https://www.cs.mcgill.ca/~wlh/grl_book/files/GRL_Book.pdf 中文翻译版网上有售
- Yao Ma, Jiliang Tang, Deep Learning on Graphs https://cse.msu.edu/~mayao4/dlg_book/dlg_book.pdf (有中文版)
- Zhiyuan Liu, Jie Zhou, Introduction to Graph Neural Networks. Synthesis Lectures on Artificial Intelligence and Machine Learning, Morgan & Claypool Publishers, 2020. （有中文版)
- Davide Bacciu, Federico Errica, Alessio Micheli, Marco Podda: A gentle introduction to deep learning for graphs. Neural Networks 129: 203-221 (2020)
- Kipf, T. N. (2020). Deep learning with graph-structured representations. https://pure.uva.nl/ws/files/46900201/Thesis.pdf

## Tutorials and Surveys

### Video and Side Courses

1.  CS224W: Machine Learning with Graphs http://web.stanford.edu/class/cs224w/  （中文简洁版：https://www.bilibili.com/video/BV1jE411p7pj) Notes：https://snap-stanford.github.io/cs224w-notes/
2.  ESE680: Graph Neural Networks https://gnn.seas.upenn.edu/ (B站视频：https://www.bilibili.com/video/BV1L5411j7kb)
3.  宾夕法尼亚大学《图神经网络》短期课程(2020) https://www.bilibili.com/video/BV17y4y1B7JN
4.  宾夕法尼亚大学《图神经网络》课程(2020) by Alejandro RIbeiro https://www.bilibili.com/video/av457264185/

### Brief Tutorials

1. 崔鹏《图神经网络年度进展概述》https://www.bilibili.com/video/BV1za4y1J7CY
2. 台大李宏毅助教讲解GNN图神经网络 https://www.bilibili.com/video/BV1G54y1971S
3. Introduction to GNN - 杜岳華 https://www.bilibili.com/video/BV1At411N7nh
4. 图神经网络 Graph Network https://www.bilibili.com/video/BV1K5411H7EQ
5. GNN从入门到精通：https://www.bilibili.com/video/BV1K5411H7EQ
6. 图神经网络在线研讨会（上） https://www.bilibili.com/video/BV1w7411Q7kK （下）https://www.bilibili.com/video/BV1w7411Q7pQ
7. 异质图神经网络:模型和应用 https://www.bilibili.com/video/BV1HE41157GD
8. 图神经网络学习班 https://www.bilibili.com/video/BV135411t76X
9. 朱时超： 图神经网络模型及应用进展 https://www.bilibili.com/video/av37250492/
10. 图卷积网络介绍及进展  https://www.bilibili.com/video/BV15t411z71q
11. 呼奋宇：深度层次化图卷积神经网络 https://www.bilibili.com/video/BV1dx411d7JT
12. 朱时超： 图表示学习专题 https://www.bilibili.com/video/BV1554y1z7mY
13. 2020 北京智源大会 6.23 图神经网络专题 https://www.bilibili.com/video/BV1nV411k7c5
14. 图神经网络：方法与应用的综述 https://www.bilibili.com/video/BV1B64y1k7L6
15. Graph Neural Networks: Models and Applications https://cse.msu.edu/~mayao4/tutorials/aaai2020/
16. Deep Learning on Graphs, by Xavier bresson https://www.dropbox.com/s/wksvde7wx9y7z20/talk_QuantumBlack_McKinsey_12Nov19.pdf?dl=0
17. Deep Graph Learning: Foundations, Advances and Applications https://ai.tencent.com/ailab/ml/KDD-Deep-Graph-Learning.html
18. Theoretical Foundations of Graph Neural Networks https://petar-v.com/talks/GNN-Wednesday.pdf
19. 图数据库介绍及其在各场景中的应用 https://www.bilibili.com/video/BV1ef4y1Y77o

### Surveys
1. 马帅,刘建伟,左信.图神经网络综述[J/OL].计算机研究与发展,{3},{4}{5}:1-44[2021-07-14].http://kns.cnki.net/kcms/detail/11.1777.tp.20210625.1353.004.html.
2. 徐冰冰,岑科廷,黄俊杰,沈华伟,程学旗.图卷积神经网络综述[J].计算机学报,2020,43(05):755-780.
3. Zonghan Wu, Shirui Pan, Fengwen Chen, Guodong Long, Chengqi Zhang, Philip S. Yu: A Comprehensive Survey on Graph Neural Networks. IEEE Trans. Neural Networks Learn. Syst. 32(1): 4-24 (2021)
4. David Ahmedt-Aristizabal, Mohammad Ali Armin, Simon Denman, Clinton Fookes, Lars Petersson: Graph-Based Deep Learning for Medical Diagnosis and Analysis: Past, Present and Future. CoRR abs/2105.13137 (2021)
5. Stavros Georgousis, Michael P. Kenning, Xianghua Xie: Graph Deep Learning: State of the Art and Challenges. IEEE Access 9: 22106-22140 (2021)
6. Yaochen Xie, Zhao Xu, Zhengyang Wang, Shuiwang Ji: Self-Supervised Learning of Graph Neural Networks: A Unified Review. CoRR abs/2102.10757(2021)
7. Zixing Song, Xiangli Yang, Zenglin Xu, Irwin King: Graph-based Semi-supervised Learning: A Comprehensive Review. CoRR abs/2102.13303 (2021)
8. Shoujin Wang, Liang Hu, Yan Wang, Xiangnan He, Quan Z. Sheng, Mehmet A. Orgun, Longbing Cao, Francesco Ricci, Philip S. Yu: Graph Learning based Recommender Systems: A Review. CoRR abs/2105.06339 (2021)
9. Guixiang Ma, Nesreen K. Ahmed, Theodore L. Willke, Philip S. Yu: Deep graph similarity learning: a survey. Data Min. Knowl. Discov. 35(3): 688-725 (2021) 
10. Ilya Makarov, Dmitrii Kiselev, Nikita Nikitinsky, Lovro Subelj: Survey on graph embeddings and their applications to machine learning problems on graphs. PeerJ Comput. Sci. 7: e357 (2021)
11. Ziwei Zhang, Xin Wang, Wenwu Zhu: Automated Machine Learning on Graphs: A Survey. CoRR abs/2103.00742CCF none (2021)
12. Yixin Liu, Shirui Pan, Ming Jin, Chuan Zhou, Feng Xia, Philip S. Yu: Graph Self-Supervised Learning: A Survey. CoRR abs/2103.00111 2021)
13. Feng Xia, Ke Sun, Shuo Yu, Abdul Aziz, Liangtian Wan, Shirui Pan, Huan Liu: Graph Learning: A Survey. CoRR abs/2105.00696CCF none (2021)
14. Chong, Yun Ding, Qing Yan, Shaoming Pan: Graph-based semi-supervised learning: A review. Neurocomputing 408: 216-230 (2020)
15. Jie Zhou, Ganqu Cui, Shengding Hu, Zhengyan Zhang, Cheng Yang, Zhiyuan Liu, Lifeng Wang, Changcheng Li, Maosong Sun: Graph neural networks: A review of methods and applications. AI Open 1: 57-81 (2020)
16. Seyed Mehran Kazemi, Rishab Goel, Kshitij Jain, Ivan Kobyzev, Akshay Sethi, Peter Forsyth, Pascal Poupart: Representation Learning for Dynamic Graphs: A Survey. J. Mach. Learn. Res. 21 : 70:1-70:73 (2020) 
17. Ziwei Zhang, Peng Cui, Wenwu Zhu: Deep Learning on Graphs: A Survey. CoRR abs/1812.04202 (2018)

## Definitions and Methods

## Implementation

1. Patrick Reiser, André Eberhard, Pascal Friederich: Implementing graph neural networks with TensorFlow-Keras. CoRR abs/2103.04318 (2021)
2. Weihua Hu, Matthias Fey, Marinka Zitnik, Yuxiao Dong, Hongyu Ren, Bowen Liu, Michele Catasta, Jure Leskovec: Open Graph Benchmark: Datasets for Machine Learning on Graphs. NeurIPS 2020

## Applications

### Recommendation System

1.  系统网络在推荐广告场景中的应用 https://www.bilibili.com/video/BV1hh411f7n7

2. 崔泽宇：套装搭配推荐在图神经网络上的应用 https://www.bilibili.com/video/BV1Jx411d73R

### Videos Understanding

1. 图神经网络在视频理解中的探索 https://www.bilibili.com/video/BV1Vb411W7t9

## Adversarial Attacks on GNNs

1. I-Chung Hsieh, Cheng-Te Li: NetFense: Adversarial Defenses against Privacy Attacks on Neural Networks for Graph Data. CoRR abs/2106.11865CCF none (2021)
2. Kaiyang Li, Guangchun Luo, Yang Ye, Wei Li, Shihao Ji, Zhipeng Cai: Adversarial Privacy-Preserving Graph Embedding Against Inference Attack. IEEE Internet Things J. 8(8)CCF none: 6904-6915 (2021)
3. Shengsheng Qian, Dizhan Xue, Huaiwen Zhang, Quan Fang, Changsheng Xu: Dual Adversarial Graph Neural Networks for Multi-label Cross-modal Retrieval. AAAI 2021CCF A: 2440-2448
4. Uday Shankar Shanthamallu, Jayaraman J. Thiagarajan, Andreas Spanias: Uncertainty-Matching Graph Neural Networks to Defend Against Poisoning Attacks. AAAI 2021CCF A: 9524-9532
5. Boyuan Feng, Yuke Wang, Yufei Ding: UAG: Uncertainty-aware Attention Graph Neural Network for Defending Adversarial Attacks. AAAI 2021CCF A: 7404-7412
6. Xin Zhao, Zeru Zhang, Zijie Zhang, Lingfei Wu, Jiayin Jin, Yang Zhou, Ruoming Jin, Dejing Dou, Da Yan: Expressive 1-Lipschitz Neural Networks for Robust Multiple Graph Learning against Adversarial Attacks. ICML 2021: 12719-12735
7. Peiyuan Liao, Han Zhao, Keyulu Xu, Tommi S. Jaakkola, Geoffrey J. Gordon, Stefanie Jegelka, Ruslan Salakhutdinov: Information Obfuscation of Graph Neural Networks. ICML 2021: 6600-6610
8. Jiaxiang Ren, Zijie Zhang, Jiayin Jin, Xin Zhao, Sixing Wu, Yang Zhou, Yelong Shen, Tianshi Che, Ruoming Jin, Dejing Dou: Integrated Defense for Resilient Graph Matching. ICML 2021: 8982-8997
9. 图神经网络的对抗攻击研究https://www.bilibili.com/video/BV1YJ411J7SL
10. Heng Chang, Yu Rong, Tingyang Xu, Wenbing Huang, Honglei Zhang, Peng Cui, Xin Wang, Wenwu Zhu, Junzhou Huang: Adversarial Attack Framework on Graph Embedding Models with Limited Knowledge. CoRR abs/2105.12419 (2021)
11. 陈晋音,黄国瀚,张敦杰,张旭鸿,纪守领.一种面向图神经网络的图重构防御方法[J].计算机研究与发展,2021,58(05):1075-1091.
12. Jacob Dineen, A. S. M. Ahsan-Ul-Haque, Matthew Bielskas: Reinforcement Learning For Data Poisoning on Graph Neural Networks. CoRR abs/2102.06800 (2021)
13. GraphAttacker: A General Multi-Task GraphAttack Framework arXiv:2101.06855
    Jinyin Chen, Dunjie Zhang, Zhaoyan Ming, Kejie Huang 
14. Zijie Zhang, Zeru Zhang, Yang Zhou, Yelong Shen, Ruoming Jin, Dejing Dou: Adversarial Attacks on Deep Graph Matching. NeurIPS 2020
15. Xiang Zhang, Marinka Zitnik: GNNGuard: Defending Graph Neural Networks against Adversarial Attacks. NeurIPS 2020
16. Jiaqi Ma, Shuangrui Ding, Qiaozhu Mei: Towards More Practical Adversarial Attacks on Graph Neural Networks. NeurIPS 2020.
17. Jairo Giraldo, Alvaro A. Cárdenas, Murat Kantarcioglu, Jonathan Katz: Adversarial Classification Under Differential Privacy. NDSS 2020
18. **Adversarial Attacks on Neural Networks for Graph Data.** KDD 2018. [paper](http://delivery.acm.org/10.1145/3230000/3220078/p2847-zugner.pdf?ip=101.5.139.169&id=3220078&acc=ACTIVE SERVICE&key=BF85BBA5741FDC6E.587F3204F5B62A59.4D4702B0C3E38B35.4D4702B0C3E38B35&__acm__=1545706391_e7484be677293ffb5f18b39ce84a0df9)

   *Daniel Zügner, Amir Akbarnejad, Stephan Günnemann.*

11. **Adversarial Attack on Graph Structured Data.** ICML 2018. [paper](https://arxiv.org/abs/1806.02371)

    *Hanjun Dai, Hui Li, Tian Tian, Xin Huang, Lin Wang, Jun Zhu, Le Song.*

12. **Adversarial Examples on Graph Data: Deep Insights into Attack and Defense.** IJCAI 2019. [paper](https://arxiv.org/pdf/1903.01610.pdf)

    *Huijun Wu, Chen Wang, Yuriy Tyshetskiy, Andrew Docherty, Kai Lu, Liming Zhu.*

13. **Topology Attack and Defense for Graph Neural Networks: An Optimization Perspective.** IJCAI 2019. [paper](https://arxiv.org/pdf/1906.04214.pdf)

    *Kaidi Xu, Hongge Chen, Sijia Liu, Pin-Yu Chen, Tsui-Wei Weng, Mingyi Hong, Xue Lin.*

14. **Robust Graph Convolutional Networks Against Adversarial Attacks.** KDD 2019. [paper](http://pengcui.thumedialab.com/papers/RGCN.pdf)

   *Dingyuan Zhu, Ziwei Zhang, Peng Cui, Wenwu Zhu.*

11. **Certifiable Robustness and Robust Training for Graph Convolutional Networks.** KDD 2019. [paper](https://arxiv.org/pdf/1906.12269)

   *Daniel Zügner, Stephan Günnemann.*

11. **Adversarial Attacks on Node Embeddings via Graph Poisoning.** ICML 2019. [paper](https://arxiv.org/pdf/1809.01093)

   *Aleksandar Bojchevski, Stephan Günnemann.*

11. **Adversarial Attacks on Graph Neural Networks via Meta Learning.** ICLR 2019. [paper](https://github.com/thunlp/GNNPapers/blob/master)

   *Daniel Zügner, Stephan Günnemann.*

11. **PeerNets: Exploiting Peer Wisdom Against Adversarial Attacks.** ICLR 2019. [paper](https://openreview.net/pdf?id=Sk4jFoA9K7)

    *Jan Svoboda, Jonathan Masci, Federico Monti, Michael Bronstein, Leonidas Guibas.*

12. **Certifiable Robustness to Graph Perturbations.** NeurIPS 2019. [paper](http://papers.nips.cc/paper/by-source-2019-4514)

    *Aleksandar Bojchevski, Stephan Günnemann.*

13. **A Unified Framework for Data Poisoning Attack to Graph-based Semi-supervised Learning.** NeurIPS 2019. [paper](http://papers.nips.cc/paper/by-source-2019-5182)

    *Xuanqing Liu, Si Si, Jerry Zhu, Yang Li, Cho-Jui Hsieh.*

14. **GNNGuard: Defending Graph Neural Networks against Adversarial Attacks.** NeurIPS 2020. [paper](https://papers.nips.cc/paper/2020/hash/690d83983a63aa1818423fd6edd3bfdb-Abstract.html)

    *Xiang Zhang, Marinka Zitnik.*
## Security of GNNs

1. Jing Xu, Minhui Xue, Stjepan Picek: Explainability-based Backdoor Attacks Against Graph Neural Networks. CoRR abs/2104.03674  (2021)
2. Zaixi Zhang, Jinyuan Jia, Binghui Wang, Neil Zhenqiang Gong: Backdoor Attacks to Graph Neural Networks. CoRR abs/2006.11165 (2020)
3. Zhaohan Xi, Ren Pang, Shouling Ji, Ting Wang: Graph Backdoor. USENIX Security 2021.(2021)([pdf](https://nesa.zju.edu.cn/download/Graph%20Backdoor.pdf))

## Interpretability of GNNs

1. Jindong Gu:Interpretable Graph Capsule Networks for Object Recognition. AAAI 2021CCF A: 1469-1477
2. Wanyu Lin, Hao Lan, Baochun Li: Generative Causal Explanations for Graph Neural Networks. ICML 2021: 6666-6679 
3. Hao Yuan, Haiyang Yu, Jie Wang, Kang Li, Shuiwang Ji: On Explainability of Graph Neural Networks via Subgraph Explorations. ICML 2021: 12241-12252
4. Ryan Henderson, Djork-Arné Clevert, Floriane Montanari: Improving Molecular Graph Neural Network Explainability with Orthonormalization and Induced Sparsity. ICML 2021: 4203-4213
5. Zhu, Xiao Wang, Chuan Shi, Houye Ji, Peng Cui: Interpreting and Unifying Graph Neural Networks with An Optimization Framework. CoRR abs/2101.11859  (2021)
6. Ana Lucic, Maartje ter Hoeve, Gabriele Tolomei, Maarten de Rijke, Fabrizio Silvestri: CF-GNNExplainer: Counterfactual Explanations for Graph Neural Networks. CoRR abs/2102.03322  (2021)
7. Minh N. Vu, My T. Thai: PGM-Explainer: Probabilistic Graphical Model Explanations for Graph Neural Networks. NeurIPS 2020
8. Hao Yuan, Haiyang Yu, Shurui Gui, Shuiwang Ji: Explainability in Graph Neural Networks: A Taxonomic Survey. CoRR abs/2012.15445 (2020)
9. Lukas Pfahler, Jan Richter: Interpretable Nearest Neighbor Queries for Tree-Structured Data in Vector Databases of Graph-Neural Network Embeddings. EDBT/ICDT Workshops 2020
10. Qiang Huang, Makoto Yamada, Yuan Tian, Dinesh Singh, Dawei Yin, Yi Chang: GraphLIME: Local Interpretable Model Explanations for Graph Neural Networks. CoRR abs/2001.06216  (2020)
11. Chris Lin, Gerald J. Sun, Krishna C. Bulusu, Jonathan R. Dry, Marylens Hernandez: Graph Neural Networks Including Sparse Interpretability. CoRR abs/2007.00119(2020)
12. Avinash Kori, Parth Natekar, Ganapathy Krishnamurthi, Balaji Srinivasan: Abstracting Deep Neural Networks into Concept Graphs for Concept Level Interpretability. CoRR abs/2008.06457(2020)
13. Yuhang Yao, Carlee Joe-Wong: Interpretable Clustering on Dynamic Graphs with Recurrent Graph Neural Networks. CoRR abs/2012.08740 (2020)
14. Siheng Chen, Yonina C. Eldar, Lingxiao Zhao: Graph Unrolling Networks: Interpretable Neural Networks for Graph Signal Denoising. CoRR abs/2006.01301 (2020)
15. Zhitao Ying, Dylan Bourgeois, Jiaxuan You, Marinka Zitnik, Jure Leskovec: GNNExplainer: Generating Explanations for Graph Neural Networks. NeurIPS 2019CCF A: 9240-9251
16. Tianle Ma, Aidong Zhang: Incorporating Biological Knowledge with Factor Graph Neural Network for Interpretable Deep Learning. CoRR abs/1906.00537 (2019)
17. Phillip E. Pope, Soheil Kolouri, Mohammad Rostami, Charles E. Martin, Heiko Hoffmann: Explainability Methods for Graph Convolutional Neural Networks. CVPR 2019: 10772-10781

## Privacy of GNNs

1. Zaixi Zhang, Qi Liu, Zhenya Huang, Hao Wang, Chengqiang Lu, Chuanren Liu, Enhong Chen: GraphMI: Extracting Private Graph Data from Graph Neural Networks. CoRR abs/2106.02820CCF none (2021)
2. Binghui Wang, Jiayi Guo, Ang Li, Yiran Chen, Hai Li: Privacy-Preserving Representation Learning on Graphs: A Mutual Information Perspective. CoRR abs/2107.01475 (2021)
3. Jacob Imola, Takao Murakami, Kamalika Chaudhuri, Locally Differentially Private Analysis of Graph Statistics. USENIX Security '21(2021)
4. Mingqi Lv, Dajian Zeng, Ling Chen, Tieming Chen, Tiantian Zhu, and Shouling Ji, Private Cell-ID Trajectory Prediction Using Multi-Graph Embedding and EncoderDecoder Network, IEEE Transactions on Mobile Computing (TMC), 2021.
5. Timour Igamberdiev, Ivan Habernal: Privacy-Preserving Graph Convolutional Networks for Text Classification. CoRR abs/2102.09604(2021)
6. Iyiola E. Olatunji, Wolfgang Nejdl, Megha Khosla: Membership Inference Attack on Graph Neural Networks. CoRR abs/2101.06570  (2021)
7. Xinlei He, Rui Wen, Yixin Wu, Michael Backes, Yun Shen, Yang Zhang: Node-Level Membership Inference Attacks Against Graph Neural Networks. CoRR abs/2102.05429 (2021)
8. Xinlei He, Jinyuan Jia, Michael Backes, Neil Zhenqiang Gong, Yang Zhang: Stealing Links from Graph Neural Networks. USENIX Security '21(2021)
9. Lun Wang, Qi Pang, Dawn Song: Towards practical differentially private causal graph discovery. NeurIPS 2020
10. Sina Sajadmanesh, Daniel Gatica-Perez: Locally Private Graph Neural Networks. CoRR abs/2006.05535 (2020) https://github.com/sisaman/LPGNN
11. Vasisht Duddu, Antoine Boutet, Virat Shejwalkar: Quantifying Privacy Leakage in Graph Embedding. CoRR abs/2010.00906 (2020)
12. Guang Yang, Juan Cao, Zhineng Chen, Junbo Guo, Jintao Li: Graph-based neural networks for explainable image privacy inference. Pattern Recognit. 105 107360 (2020)
13. Jun Zhou, Chaochao Chen, Longfei Zheng, Xiaolin Zheng, Bingzhe Wu, Ziqi Liu, Li Wang: Privacy-Preserving Graph Neural Network for Node Classification. CoRR abs/2005.11903 (2020)
14. Sina Sajadmanesh, Daniel Gatica-Perez: When Differential Privacy Meets Graph Neural Networks. CoRR abs/2006.05535 (2020)
15. Luca Luceri, Davide Andreoletti, Silvia Giordano: Infringement of Tweets Geo-Location Privacy: an approach based on Graph Convolutional Neural Networks. CoRR abs/1903.11206

## Federated GNNs

1. Longfei Zheng, Jun Zhou, Chaochao Chen, Bingzhe Wu, Li Wang, Benyu Zhang: ASFGNN: Automated separated-federated graph neural network. Peer Peer Netw. Appl. 14(3)CCF C: 1692-1704 (2021)
2. Elsa Rizk, Ali H. Sayed: A Graph Federated Architecture with Privacy Preserving Learning. CoRR abs/2104.13215 (2021)
3. Chaoyang He, Keshav Balasubramanian, Emir Ceyani, Yu Rong, Peilin Zhao, Junzhou Huang, Murali Annavaram, Salman Avestimehr: **FedGraphNN: A Federated Learning System and Benchmark for Graph Neural Networks**. CoRR abs/2104.07145 (2021)
4. Chuhan Wu, Fangzhao Wu, Yang Cao, Yongfeng Huang, Xing Xie: FedGNN: Federated Graph Neural Network for Privacy-Preserving Recommendation. CoRR abs/2102.04925 (2021)
5. Chunnan Wang, Bozhou Chen, Geng Li, Hongzhi Wang: FL-AGCNS: Federated Learning Framework for Automatic Graph Convolutional Network Search. CoRR abs/2104.04141 (2021)
6. Binghui Wang, Ang Li, Hai Li, Yiran Chen: GraphFL: A Federated Learning Framework for Semi-Supervised Node Classification on Graphs. CoRR abs/2012.04187(2020)
7. Dongming Han, Wei Chen, Rusheng Pan, Yijing Liu, Jiehui Zhou, Ying Xu, Tianye Zhang, Changjie Fan, Jianrong Tao, Xiaolong Zhang: GraphFederator: Federated Visual Analysis for Multi-party Graphs. CoRR abs/2008.119892020)
8. Guangxu Mei, Ziyu Guo, Shijun Liu, Li Pan: SGNN: A Graph Neural Network Based Federated Learning Approach by Hiding Structure. BigData 2019 2560-2568
9. Anusha Lalitha, Osman Cihan Kilinc, Tara Javidi, Farinaz Koushanfar: Peer-to-peer Federated Learning on Graphs. CoRR abs/1901.11173 (2019)
10. Chaoyang He, Conghui Tan, Hanlin Tang, Shuang Qiu, Ji Liu: Central Server Free Federated Learning over Single-sided Trust Social Networks. CoRR abs/1910.04956  (2019)
11. Toyotaro Suzumura, Yi Zhou, Nathalie Barcardo, Guangnan Ye, Keith Houck, Ryo Kawahara, Ali Anwar, Lucia Larise Stavarache, Daniel Klyashtorny, Heiko Ludwig, Kumar Bhaskaran: Towards Federated Graph Learning for Collaborative Financial Crimes Detection. CoRR abs/1909.12946 (2019)

## Development Tools

- 清华大学：CogDL is a graph representation learning toolkit http://keg.cs.tsinghua.edu.cn/cogdl/index.html
- 清华大学：AutoGL http://mn.cs.tsinghua.edu.cn/autogl/
- 纽约大学上海分校：DEEP GRAPH LIBRARY https://www.dgl.ai   https://www.bilibili.com/video/BV1cq4y1W7aA
- ptgnn: A PyTorch GNN Library
- [DIG: A Turnkey Library for Diving into Graph Deep Learning Research](https://arxiv.org/abs/2103.12608) https://github.com/divelab/DIG
- PyTorch Geometric. https://pytorch-geometric.readthedocs.io/en/latest/
- 阿里巴巴： graph learn https://github.com/alibaba/graph-learn
- 阿里巴巴：euler https://github.com/alibaba/euler
- 微软：pytorch GAT https://github.com/gordicaleksa/pytorch-GAT
- DeepRobust is a PyTorch adversarial library for attack and defense methods on images and graphs.https://github.com/DSE-MSU/DeepRobust
- 南洋理工大学：Benchmarking Graph Neural Networks https://github.com/graphdeeplearning/benchmarking-gnns
- 斯坦福大学：Open Graph Benchmark https://ogb.stanford.edu/

## Topics

- defense on back-door:
  -  [Turning Your Weakness Into a Strength: Watermarking Deep Neural Networks by Backdooring](https://www.aminer.cn/pub/5a9cb65d17c44a376ffb8431/turning-your-weakness-into-a-strength-watermarking-deep-neural-networks-by-backdooring)
  - [Fine-Pruning: Defending Against Backdooring Attacks on Deep Neural Networks](https://www.aminer.cn/pub/5b3d98cc17c44a510f80195f/fine-pruning-defending-against-backdooring-attacks-on-deep-neural-networks)
- data poisoning on graph based applications: 
  - [Poisoning Attacks to Graph-Based Recommender Systems](https://www.aminer.cn/pub/5bdc31b817c44a1f58a0c5f4/poisoning-attacks-to-graph-based-recommender-systems)

