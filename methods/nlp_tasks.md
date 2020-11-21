# 自然语言处理相关任务

## 背景与展望
- [NLP综述（思维导图）](https://zhuanlan.zhihu.com/p/56802149)
- [BERT时代与后时代的NLP](https://zhuanlan.zhihu.com/p/66676144)

## 对话机器人chatbot
- [智能客服机器人分类图](https://blog.csdn.net/u011646912/article/details/102816281)
- [知乎专栏：对话机器人](https://www.zhihu.com/column/c_1154767675480821760)

【Rasa】
- [rasa文章导引（用于收藏）](https://zhuanlan.zhihu.com/p/88112269)
- [Finetune BERT Embeddings with spaCy and Rasa](https://github.com/JulianGerhard21/bert_spacy_rasa)

## 命名实体识别 NER

【实战链接】

Rasa中的NER：
- 结论：可以使用ner_spacy实现人名提取
- [rasa blog - 深入理解rasa NLU: Part2 - 实体识别 (翻译)](https://zhuanlan.zhihu.com/p/84220988)
- [原文链接](https://blog.rasa.com/rasa-nlu-in-depth-part-2-entity-recognition/)

Spacy官方NER demo：
- [displaCy Named Entity Visualizer](https://explosion.ai/demos/displacy-ent)

经典建模实现NER：
- 结论：CRF，BiLSTM以及BiLSTM+CRF都有不错的表现，超过HMM
- [NLP实战-中文命名实体识别](https://zhuanlan.zhihu.com/p/61227299)

Bert实现NER：
- [基于BERT 的中文数据集下的命名实体识别(NER)](https://github.com/xuanzebi/BERT-CH-NER)
- [BERT-BiLSTM-CRF命名实体识别应用](https://www.omegaxyz.com/2020/05/18/bert-bilstm-crf/)
- [Bert-NER](https://github.com/binhking/Bert-NER)

Kashgari - 一个工业级NLP迁移学习框架：
- [Kashgari](https://github.com/BrikerMan/Kashgari/)

【领域背景】

5种框架在NER上的表现对比：
- 结论：TextSpace > StanfordNLP > spaCy > IBM MAX = Dialogflow
- [Benchmarking Named Entity Recognition: StanfordNLP, IBM, spaCy, Dialogflow, and TextSpace](https://towardsdatascience.com/benchmarking-named-entity-recognition-stanfordnlp-ibm-spacy-dialogflow-and-textspace-af6615eb7930)

## 分词 Tokenization

【中文】

中文NLP分词：
- 结论：分为基于词典和基于统计的算法。常见的分词器都是使用两者的结合。
- 存在问题：分词标准不一，歧义（组合型，交集型，真歧义），新词
- [中文分词利器 jieba 和 HanLP](https://www.jianshu.com/p/009671e56027)
- [中文分词原理和工具总结](https://blog.csdn.net/sinat_26811377/article/details/102802044)
- [中文分词器分词效果评估对比](https://github.com/ysc/cws_evaluation)

## 特征抽取
- [放弃幻想，全面拥抱Transformer](https://zhuanlan.zhihu.com/p/54743941)

## 文本聚类 Clustering

LDA主题模型：
- [利用sklearn训练LDA主题模型及调参详解](https://blog.csdn.net/TiffanyRabbit/article/details/76445909)

聚类小结：
- [聚类之层次聚类、基于划分的聚类（k-means）、基于密度的聚类、基于模型的聚类](https://blog.csdn.net/qq_16365849/article/details/50646679)

## 模型

【Word2Vec】
- [Word2Vec的参数解释](https://blog.csdn.net/laobai1015/article/details/86540813)
- [Word2Vec的簡易教學與參數調整指南](https://www.kaggle.com/jerrykuo7727/word2vec)

【TextCNN】
- [TextCNN的优化经验](https://www.cnblogs.com/ModifyRong/p/11442661.html)
