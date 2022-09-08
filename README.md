# Awesome Efficient PLM Papers

Must-read papers on improving efficiency for pre-trained language models.

The paper list is mainly mantained by [Lei Li](https://github.com/TobiasLee).

## Knowledge Distillation

1. **DistilBERT, a distilled version of BERT: smaller, faster, cheaper and lighter** NeurIPS workshop

   *Victor Sanh, Lysandre Debut, Julien Chaumond, Thomas Wolf* [[pdf](https://arxiv.org/pdf/2107.13586)] [[project](https://huggingface.co/transformers/model_doc/distilbert.html)]
2. **Patient Knowledge Distillation for BERT Model Compression** EMNLP 2019

   *Siqi Sun, Yu Cheng, Zhe Gan, Jingjing Liu* [[pdf](https://arxiv.org/abs/1908.09355)] [[project](https://github.com/intersun/PKD-for-BERT-Model-Compression)]
3. **Well-Read Students Learn Better: On the Importance of Pre-training Compact Models** Preprint

   *Iulia Turc, Ming-Wei Chang, Kenton Lee, Kristina Toutanova* [[pdf](https://arxiv.org/abs/1908.08962)] [[project](https://github.com/google-research/bert)]
4. **TinyBERT: Distilling BERT for Natural Language Understanding** Findings of EMNLP 2020

   *Xiaoqi Jiao, Yichun Yin, Lifeng Shang, Xin Jiang, Xiao Chen, Linlin Li, Fang Wang, Qun Liu* [[pdf](https://arxiv.org/abs/1909.10351)] [[project](https://github.com/huawei-noah/Pretrained-Language-Model/tree/master/TinyBERT)]
5. **DynaBERT: Dynamic BERT with Adaptive Width and Depth** NeurIPS 2020

   *Lu Hou, Zhiqi Huang, Lifeng Shang, Xin Jiang, Xiao Chen, Qun Liu* [[pdf](https://arxiv.org/abs/2004.04037)]  [[project](https://github.com/huawei-noah/Pretrained-Language-Model/tree/master/DynaBERT)]
6. **BERT-of-Theseus: Compressing BERT by Progressive Module Replacing** EMNLP 2020

   *Canwen Xu, Wangchunshu Zhou, Tao Ge, Furu Wei, Ming Zhou* [[pdf](https://arxiv.org/abs/2002.02925)] [[project](https://github.com/JetRunner/BERT-of-Theseus)]
7. **MiniLM: Deep Self-Attention Distillation for Task-Agnostic Compression of Pre-Trained Transformers** NeurIPS 2020

   *Wenhui Wang, Furu Wei, Li Dong, Hangbo Bao, Nan Yang, Ming Zhou*  [[pdf](https://arxiv.org/abs/2002.10957)] [[project](https://github.com/microsoft/unilm/tree/master/minilm)]
8. **BERT-EMD: Many-to-Many Layer Mapping for BERT Compression with Earth Mover's Distance** EMNLP 2020

   *Jianquan Li, Xiaokang Liu, Honghong Zhao, Ruifeng Xu, Min Yang, Yaohong Jin* [[pdf](https://arxiv.org/abs/2010.06133)] [[project](https://github.com/lxk00/BERT-EMD)]
9. **MixKD: Towards Efficient Distillation of Large-scale Language Models** ICLR 2021

   *Kevin J Liang, Weituo Hao, Dinghan Shen, Yufan Zhou, Weizhu Chen, Changyou Chen, Lawrence Carin*  [[pdf](https://arxiv.org/abs/2011.00593)]
10. **Meta-KD: A Meta Knowledge Distillation Framework for Language Model Compression across Domains** ACL-IJCNLP 2021

    *Haojie Pan, Chengyu Wang, Minghui Qiu, Yichang Zhang, Yaliang Li, Jun Huang* [[pdf](https://arxiv.org/abs/2012.01266)]
11. **MATE-KD: Masked Adversarial TExt, a Companion to Knowledge Distillation** ACL-IJCNLP 2021

    *Ahmad Rashid, Vasileios Lioutas, Mehdi Rezagholizadeh*  [[pdf](https://arxiv.org/abs/2105.05912)]
12. **Structural Knowledge Distillation: Tractably Distilling Information for Structured Predictor** ACL-IJCNLP 2021

    *Xinyu Wang, Yong Jiang, Zhaohui Yan, Zixia Jia, Nguyen Bach, Tao Wang, Zhongqiang Huang, Fei Huang, Kewei Tu*  [[pdf](https://arxiv.org/abs/2010.05010)] [[project](https://github.com/Alibaba-NLP/StructuralKD)]
13. **Weight Distillation: Transferring the Knowledge in Neural Network Parameters** ACL-IJCNLP 2021

    *Ye Lin, Yanyang Li, Ziyang Wang, Bei Li, Quan Du, Tong Xiao, Jingbo Zhu* [[pdf](https://arxiv.org/abs/2009.09152)]
14. **Marginal Utility Diminishes: Exploring the Minimum Knowledge for BERT Knowledge Distillation** ACL-IJCNLP 2021

    *Yuanxin Liu, Fandong Meng, Zheng Lin, Weiping Wang, Jie Zhou* [[pdf](https://arxiv.org/abs/2106.05691)]
15. **MiniLMv2: Multi-Head Self-Attention Relation Distillation for Compressing Pretrained Transformers** Findings of ACL-IJCNLP 2021

    *Wenhui Wang, Hangbo Bao, Shaohan Huang, Li Dong, Furu Wei* [[pdf](https://arxiv.org/abs/2012.15828)] [[project](https://github.com/microsoft/unilm/tree/master/minilm)]
16. **One Teacher is Enough? Pre-trained Language Model Distillation from Multiple Teachers** Findings of ACL-IJCNLP 2021

    *Chuhan Wu, Fangzhao Wu, Yongfeng Huang* [[pdf](https://arxiv.org/abs/2106.01023)]
17. **Dynamic Knowledge Distllation for Pre-trained Language Models** EMNLP 2021

    *Lei Li, Yankai Lin, Shuhuai Ren, Peng Li, Jie Zhou, Xu Sun* [[pdf]](https://arxiv.org/abs/2109.11295) [[project]](https://github.com/lancopku/DynamicKD)
18. **EfficientBERT: Progressively Searching Multilayer Perceptron via Warm-up Knowledge Distillation** Findings of EMNLP 2021

    *Chenhe Dong, Guangrun Wang, Hang Xu, Jiefeng Peng, Xiaozhe Ren, Xiaodan Liang* [[pdf]](https://arxiv.org/abs/2109.07222) [[project]](https://github.com/cheneydon/efficient-bert)
19. **Beyond Preserved Accuracy: Evaluating Loyalty and Robustness of BERT Compression**  EMNLP 2021

    *Canwen Xu, Wangchunshu Zhou, Tao Ge, Ke Xu, Julian McAuley, Furu Wei* [[pdf]](https://arxiv.org/abs/2109.03228)  [[project]](https://github.com/JetRunner/beyond-preserved-accuracy)
20. **How to Select One Among All? An Extensive Empirical Study Towards the Robustness of Knowledge Distillation in Natural Language Understanding**  Findings of EMNLP 2021

    *Tianda Li, Ahmad Rashid, Aref Jafari, Pranav Sharma, Ali Ghodsi, Mehdi Rezagholizadeh* [[pdf]](https://arxiv.org/abs/2109.05696)
21. **Why Skip If You Can Combine: A Simple Knowledge Distillation Technique for Intermediate Layers** EMNLP 2020

    *Yimeng Wu, Peyman Passban, Mehdi Rezagholizadeh, Qun Liu* [[pdf](https://aclanthology.org/2020.emnlp-main.74.pdf)] [[project](https://github.com/yimeng0701/CKD_pytorch)]
22. **ALP-KD: Attention-Based Layer Projection for Knowledge Distillation** AAAI 2021

    *Peyman Passban, Yimeng Wu, Mehdi Rezagholizadeh, Qun Liu* [[pdf](https://arxiv.org/pdf/2012.14022)]
23. **Universal-KD: Attention-based Output-Grounded Intermediate Layer Knowledge Distillation** EMNLP 2021

    *Yimeng Wu, Mehdi Rezagholizadeh, Abbas Ghaddar, Md Akmal Haidar, Ali Ghodsi* [[pdf](https://aclanthology.org/2021.emnlp-main.603.pdf)]

## Dynamic Early Exiting

1. **DeeBERT: Dynamic Early Exiting for Accelerating BERT Inference**   ACL 2020

   *Ji Xin, Raphael Tang, Jaejun Lee, Yaoliang Yu, Jimmy Lin*  [[pdf](https://arxiv.org/abs/2004.12993)] [[project](https://github.com/castorini/DeeBERT)]
2. **FastBERT: a Self-distilling BERT with Adaptive Inference Time**   ACL 2020

   *Weijie Liu, Peng Zhou, Zhe Zhao, Zhiruo Wang, Haotang Deng, Qi Ju*  [[pdf](https://arxiv.org/abs/2004.02178)] [[project](https://github.com/autoliuweijie/FastBERT)]
3. **The Right Tool for the Job: Matching Model and Instance Complexities**  ACL 2020

   *Roy Schwartz, Gabriel Stanovsky, Swabha Swayamdipta, Jesse Dodge, Noah A. Smith*  [[pdf](https://arxiv.org/abs/2004.07453)] [[project](https://github.com/allenai/sledgehammer)]
4. **A Global Past-Future Early Exit Method for Accelerating Inference
   of Pre-trained Language Models** NAACL 2021

   *Kaiyuan Liao, Yi Zhang, Xuancheng Ren, Qi Su, Xu Sun, Bin He* [[pdf](https://aclanthology.org/2021.naacl-main.162)] [[project](https://github.com/lancopku/Early-Exit)]
5. **CascadeBERT: Accelerating Inference of Pre-trained Language Models via Calibrated Complete Models Cascade**  Preprint

   *Lei Li, Yankai Lin, Deli Chen, Shuhuai Ren, Peng Li, Jie Zhou, Xu Sun* [[pdf](https://arxiv.org/abs/2012.14682)] [[project](https://github.com/lancopku/CascadeBERT)]
6. **Early Exiting BERT for Efficient Document Ranking** SustaiNLP 2020

   *Ji Xin, Rodrigo Nogueira, Yaoliang Yu, and Jimmy Lin* [[pdf](https://aclanthology.org/2020.sustainlp-1.11/)] [[project](https://github.com/castorini/earlyexiting-monobert)]
7. **BERxiT: Early Exiting for BERT with Better Fine-Tuning and Extension to Regression** EACL 2021

   *Ji Xin, Raphael Tang, Yaoliang Yu, and Jimmy Lin* [[pdf](https://aclanthology.org/2021.eacl-main.8/)] [[project](https://github.com/castorini/berxit)]
8. **Accelerating BERT Inference for Sequence Labeling via Early-Exit** ACL 2021

   *Xiaonan Li, Yunfan Shao, Tianxiang Sun, Hang Yan, Xipeng Qiu, Xuanjing Huang* [[pdf](https://arxiv.org/abs/2105.13878)] [[project](https://github.com/LeeSureman/Sequence-Labeling-Early-Exit)]
9. **BERT Loses Patience: Fast and Robust Inference with Early Exit** NeurIPS 2020

   *Wangchunshu Zhou, Canwen Xu, Tao Ge, Julian McAuley, Ke Xu, Furu Wei* [[pdf](https://arxiv.org/abs/2006.04152)] [[project](https://github.com/JetRunner/PABEE)]
10. **Early Exiting with Ensemble Internal Classifiers** Preprint

    *Tianxiang Sun, Yunhua Zhou, Xiangyang Liu, Xinyu Zhang, Hao Jiang, Zhao Cao, Xuanjing Huang, Xipeng Qiu* [[pdf](https://arxiv.org/abs/2105.13792)]
11. **LeeBERT: Learned Early Exit for BERT with Cross-Level Optimization** ACL 2021

    *Wei Zhu* [[pdf](https://aclanthology.org/2021.acl-long.231.pdf)]
12. **Consistent Accelerated Inference via Confident Adaptive Transformers** EMNLP 2021

    *Tal Schuster, Adam Fisch, Tommi Jaakkola, Regina Barzilay* [[pdf]](https://arxiv.org/abs/2104.08803) [[project]](https://github.com/TalSchuster/CATs)
13. **Towards Efficient NLP: A Standard Evaluation and A Strong Baseline** NAACL 2022 

    *Xiangyang Liu, Tianxiang Sun, Junliang He, Lingling Wu, Xinyu Zhang, Hao Jiang, Zhao Cao, Xuanjing Huang, Xipeng Qiu* [[pdf]](https://arxiv.org/abs/2110.07038) [[project]](http://eluebenchmark.fastnlp.top/#/landing)
14. **A Simple Hash-Based Early Exiting Approach For Language Understanding and Generation** Findings of ACL 2022

    *Tianxiang Sun, Xiangyang Liu, Wei Zhu, Zhichao Geng, Lingling Wu, Yilong He, Yuan Ni, Guotong Xie, Xuanjing Huang, Xipeng Qiu* [[pdf]](https://arxiv.org/abs/2203.01670)
    
15. **SkipBERT: Efficient Inference with Shallow Layer Skipping** ACL 2022

    *Jue Wang, Ke Chen, Gang Chen, Lidan Shou, Julian McAuley* [[pdf]](https://aclanthology.org/2022.acl-long.503.pdf) [[project]](https://github.com/LorrinWWW/SkipBERT)

## Quantization

1. **Q-BERT: Hessian Based Ultra Low Precision Quantization of BERT** AAAI 2020

   *Sheng Shen, Zhen Dong, Jiayu Ye, Linjian Ma, Zhewei Yao, Amir Gholami, Michael W. Mahoney, Kurt Keutzer* [[pdf](https://arxiv.org/abs/1909.05840)] [[project](https://github.com/sIncerass/QBERT)]
2. **TernaryBERT: Distillation-aware Ultra-low Bit BERT** EMNLP 2020

   *Wei Zhang, Lu Hou, Yichun Yin, Lifeng Shang, Xiao Chen, Xin Jiang, Qun Liu* [[pdf](https://arxiv.org/abs/2009.12812)] [[project](https://github.com/huawei-noah/Pretrained-Language-Model/tree/master/TernaryBERT)]
3. **Q8BERT: Quantized 8Bit BERT** NeurIPS 2019 Workshop

   *Ofir Zafrir, Guy Boudoukh, Peter Izsak, Moshe Wasserblat* [[pdf](https://arxiv.org/abs/1910.06188)] [[project](https://github.com/IntelLabs/nlp-architect)]
4. **BinaryBERT: Pushing the Limit of BERT Quantization** EMNLP 2020

   *Haoli Bai, Wei Zhang, Lu Hou, Lifeng Shang, Jing Jin, Xin Jiang, Qun Liu, Michael Lyu, Irwin King* [[pdf](https://arxiv.org/abs/2012.15701)] [[project](https://github.com/huawei-noah/Pretrained-Language-Model/tree/master/BinaryBERT)]
5. **Automatic Mixed-Precision Quantization Search of BERT** IJCAI 2021

   *Changsheng Zhao, Ting Hua, Yilin Shen, Qian Lou, Hongxia Jin* [[pdf]](https://www.ijcai.org/proceedings/2021/0472.pdf)
6. **I-BERT: Integer-only BERT Quantization** ICML 2021

   *Sehoon Kim, Amir Gholami, Zhewei Yao, Michael W. Mahoney, Kurt Keutzer* [[pdf](https://arxiv.org/abs/2101.01321)] [[project](https://github.com/kssteven418/I-BERT)]
7. **Training with Quatization Noise for Extreme Model CompressionN**  ICLR 2021

   *Angela Fan, Pierre Stock, Benjamin Graham, Edouard Grave, Remi Gribonval Herve Jegou, Armand Joulin* [[pdf](https://arxiv.org/abs/2004.07320)] [[project](https://github.com/pytorch/fairseq/tree/main/examples/quant_noise)]
   
8. **Compression of Generative Pre-trained Language Models via Quantization** ACL 2022

   *Chaofan Tao, Lu Hou, Wei Zhang, Lifeng Shang, Xin Jiang, Qun Liu, Ping Luo, Ngai Wong* [[pdf](https://arxiv.org/pdf/2203.10705.pdf)] 

9. **BiBERT: Accurate Fully Binarized BERT** ICLR 2022 
  
   *Haotong Qin, Yifu Ding, Mingyuan Zhang, Qinghua YAN, Aishan Liu, Qingqing Dang, Ziwei Liu, Xianglong Liu* [[pdf](https://openreview.net/pdf?id=5xEgrl_5FAJ)] 
  
## Pruning

1. **Analyzing Multi-Head Self-Attention: Specialized Heads Do the Heavy Lifting, the Rest Can Be Pruned** ACL 2019

   *Elena Voita, David Talbot, Fedor Moiseev, Rico Sennrich, Ivan Titov* [[pdf](https://aclanthology.org/P19-1580/)] [[project](https://github.com/lena-voita/the-story-of-heads)]
2. **Are Sixteen Heads Really Better than One?** NeurIPS 2019

   *Paul Michel, Omer Levy, Graham Neubig* [[pdf](https://arxiv.org/abs/1905.10650)] [[project](https://github.com/pmichel31415/are-16-heads-really-better-than-1)]
3. **The Lottery Ticket Hypothesis for Pre-trained BERT Networks** NeurIPS 2020

   *Tianlong Chen, Jonathan Frankle, Shiyu Chang, Sijia Liu, Yang Zhang, Zhangyang Wang, Michael Carbin* [[pdf](https://arxiv.org/abs/2007.12223)] [[project](https://github.com/VITA-Group/BERT-Tickets)]
4. **Movement Pruning: Adaptive Sparsity by Fine-Tuning** NeurIPS 2020

   *Victor Sanh, Thomas Wolf, Alexander M. Rush* [[pdf](https://arxiv.org/abs/2005.07683)] [[project](https://github.com/huggingface/transformers/tree/master/examples/research_projects/movement-pruning)]
5. **Compressing BERT: Studying the Effects of Weight Pruning on Transfer Learning** Rep4NLP 2020

   *Mitchell A. Gordon, Kevin Duh, Nicholas Andrews* [[pdf](https://arxiv.org/abs/2002.08307)] [[project]](https://github.com/mitchellgordon95/bert-prune)
6. **Reducing Transformer Depth on Demand with Structured Dropout** Preprint

   *Angela Fan, Edouard Grave, Armand Joulin* [[pdf](https://arxiv.org/abs/1909.11556)]
7. **When BERT Plays the Lottery, All Tickets Are Winning** EMNLP 2020

   *Sai Prasanna, Anna Rogers, Anna Rumshisky* [[pdf](https://arxiv.org/abs/2005.00561)] [[project](https://github.com/sai-prasanna/bert-experiments)]
8. **Pruning Redundant Mappings in Transformer Models via Spectral-Normalized Identity Prior** Findings of EMNLP 2020

   *Zi Lin, Jeremiah Liu, Zi Yang, Nan Hua, Dan Roth* [[pdf](https://aclanthology.org/2020.findings-emnlp.64/)]
9. **Structured Pruning of a BERT-based Question Answering Model** Preprint

   *J.S. McCarley, Rishav Chakravarti, Avirup Sil* [[pdf](https://arxiv.org/abs/1910.06360)]
10. **Structured Pruning of Large Language Models** EMNLP 2020

    *Ziheng Wang, Jeremy Wohlwend, Tao Lei* [[pdf](https://aclanthology.org/2020.emnlp-main.496/)] [[project](https://github.com/asappresearch/flop)]
11. **Rethinking Network Pruning -- under the Pre-train and Fine-tune Paradigm** NAACL 2021

    *Dongkuan Xu, Ian E.H. Yen, Jinxi Zhao, Zhibin Xiao* [[pdf](https://arxiv.org/abs/2104.08682)]
12. **Super Tickets in Pre-Trained Language Models: From Model Compression to Improving Generalization** ACL 2021

    *Chen Liang, Simiao Zuo, Minshuo Chen, Haoming Jiang, Xiaodong Liu, Pengcheng He, Tuo Zhao, Weizhu Chen* [[pdf](https://arxiv.org/abs/2105.12002)]  [[project](https://github.com/cliang1453/super-structured-lottery-tickets)]
13. **Block Pruning For Faster Transformers** EMNLP 2021

    *François Lagunas, Ella Charlaix, Victor Sanh, Alexander M. Rush* [[pdf](https://arxiv.org/abs/2109.04838)]  [[project](https://github.com/huggingface/nn_pruning)]

## Other Methods

1. **Explicit Sparse Transformer: Concentrated Attention Through Explicit Selection** arxiv 2019

   *Guangxiang Zhao, Junyang Lin, Zhiyuan Zhang, Xuancheng Ren, Qi Su, Xu Sun* [[pdf](https://arxiv.org/abs/1912.11637)] [[project](https://github.com/lancopku/Explicit-Sparse-Transformer)]
2. **Compressing Pre-trained Language Models by Matrix Decomposition** AACL 2020

   *Matan Ben Noach, Yoav Goldberg* [[pdf](https://aclanthology.org/2020.aacl-main.88/)]
3. **LadaBERT: Lightweight Adaptation of BERT through Hybrid Model Compression** COLING 2020

   *Yihuan Mao, Yujing Wang, Chufan Wu, Chen Zhang, Yang Wang, Yaming Yang, Quanlu Zhang, Yunhai Tong, Jing Bai* [[pdf](https://arxiv.org/abs/2004.04124)]
4. **Enabling Lightweight Fine-tuning for Pre-trained Language Model Compression based on Matrix Product Operators** ACL 2021

   *Peiyu Liu, Ze-Feng Gao, Wayne Xin Zhao, Zhi-Yuan Xie, Zhong-Yi Lu and Ji-Rong Wen* [[pdf](https://arxiv.org/abs/2106.02205)] [[project](https://github.com/RUCAIBox/MPOP)]
   
5. **Exploring Extreme Parameter Compression for Pre-trained Language Models** ICLR 2022

   *Benyou Wang, Yuxin Ren, Lifeng Shang, Xin Jiang, Qun Liu* [[pdf](https://openreview.net/pdf?id=RftryyYyjiG)] [[project](https://github.com/twinkle0331/Xcompression)]

## Contribution

If you find any related work not included in the list, do not hesitate to raise a PR to help us complete the list.
