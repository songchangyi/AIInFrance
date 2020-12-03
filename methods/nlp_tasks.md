# 自然语言处理相关任务

## 背景与展望
- [NLP综述（思维导图）](https://zhuanlan.zhihu.com/p/56802149)
- [BERT时代与后时代的NLP](https://zhuanlan.zhihu.com/p/66676144)

## 对话机器人chatbot
- [智能客服机器人分类图](https://blog.csdn.net/u011646912/article/details/102816281)
- [知乎专栏：对话机器人](https://www.zhihu.com/column/c_1154767675480821760)
- [五八同城智能客服系统“帮帮”技术揭秘](https://mp.weixin.qq.com/s/5ewD2xD8J08W89-Rwixw4Q)

【Rasa】
- [rasa文章导引（用于收藏）](https://zhuanlan.zhihu.com/p/88112269)
- [Rasa教程系列](https://blog.csdn.net/ljp1919/category_9656007.html)

Rasa NLU Pipeline
- [Finetune BERT Embeddings with spaCy and Rasa](https://github.com/JulianGerhard21/bert_spacy_rasa)
- [EmbeddingIntentClassifier官方文档](https://legacy-docs-v1.rasa.com/nlu/components/#embeddingintentclassifier)
- [Understanding Rasa Tensorflow intent classifier](https://medium.com/@tatiana.parshina/understanding-rasa-tensorflow-intent-classifier-e9d4ef019c6)
- [StarSpace: Embed All The Things!](https://blog.csdn.net/Forlogen/article/details/91345913)
- [论文阅读——StarSpace:Embed All The Things!](https://www.jianshu.com/p/35c15221c1c4)

Rasa Core Policies
- [Policy官方文档](https://rasa.com/docs/rasa/policies/)
- [Rasa教程系列-Core-5-Policies](https://blog.csdn.net/ljp1919/article/details/104002385)

Rasa Test CI/CD
- [Test](https://rasa.com/docs/rasa/testing-your-assistant/)
- [CI/CD](https://rasa.com/docs/rasa/setting-up-ci-cd)

## 命名实体识别 NER

【实战链接】

Rasa中的NER
- 结论：可以使用ner_spacy实现人名提取
- [rasa blog - 深入理解rasa NLU: Part2 - 实体识别 (翻译)](https://zhuanlan.zhihu.com/p/84220988)
- [原文链接](https://blog.rasa.com/rasa-nlu-in-depth-part-2-entity-recognition/)

Spacy官方NER demo
- [displaCy Named Entity Visualizer](https://explosion.ai/demos/displacy-ent)

经典建模实现NER
- 结论：CRF，BiLSTM以及BiLSTM+CRF都有不错的表现，超过HMM
- [NLP实战-中文命名实体识别](https://zhuanlan.zhihu.com/p/61227299)

Bert实现NER
- [基于BERT 的中文数据集下的命名实体识别(NER)](https://github.com/xuanzebi/BERT-CH-NER)
- [BERT-BiLSTM-CRF命名实体识别应用](https://www.omegaxyz.com/2020/05/18/bert-bilstm-crf/)
- [Bert-NER](https://github.com/binhking/Bert-NER)

Kashgari - 一个工业级NLP迁移学习框架
- [Kashgari](https://github.com/BrikerMan/Kashgari/)

【领域背景】

5种框架在NER上的表现对比
- 结论：TextSpace > StanfordNLP > spaCy > IBM MAX = Dialogflow
- [Benchmarking Named Entity Recognition: StanfordNLP, IBM, spaCy, Dialogflow, and TextSpace](https://towardsdatascience.com/benchmarking-named-entity-recognition-stanfordnlp-ibm-spacy-dialogflow-and-textspace-af6615eb7930)

## 分词 Tokenization

【中文】

中文NLP分词
- 结论：分为基于词典和基于统计的算法。常见的分词器都是使用两者的结合。
- 存在问题：分词标准不一，歧义（组合型，交集型，真歧义），新词
- [中文分词利器 jieba 和 HanLP](https://www.jianshu.com/p/009671e56027)
- [中文分词原理和工具总结](https://blog.csdn.net/sinat_26811377/article/details/102802044)
- [中文分词器分词效果评估对比](https://github.com/ysc/cws_evaluation)

## 特征抽取
- [放弃幻想，全面拥抱Transformer](https://zhuanlan.zhihu.com/p/54743941)

## 情感分析
- [Word2vec情感分析和分类](https://cloud.tencent.com/developer/article/1061949)

## 文本分类聚类

【LDA主题模型】
- [利用sklearn训练LDA主题模型及调参详解](https://blog.csdn.net/TiffanyRabbit/article/details/76445909)

【大规模文本聚类】
结论：使用增量聚类算法，比如single-pass。对每条文本，计算与已有类的相似度，高于则加入该类，低于则创建新类。
- [大数据量的文本聚类](https://www.zhihu.com/question/59920681/answer/760343357)

【大规模文本分类】
- [深度学习解决大规模文本分类问题](https://cloud.tencent.com/developer/article/1399904)

聚类小结：
- [聚类之层次聚类、基于划分的聚类（k-means）、基于密度的聚类、基于模型的聚类](https://blog.csdn.net/qq_16365849/article/details/50646679)
- [聚类算法评估指标](https://zhuanlan.zhihu.com/p/115752696)
- [聚类算法评估指标](https://www.biaodianfu.com/cluster-score.html)
- [中文文本聚类实验](https://github.com/FesonX/cn-text-classifier)

## 知识图谱
- [知识图谱在贝壳找房的从0到1实践](https://mp.weixin.qq.com/s?__biz=MzU1NTMyOTI4Mw==&mid=2247485923&idx=1&sn=27735f64a2196ba7210503da84c90c33&chksm=fbd4bb8fcca3329939fbec3673773f005839b68cc41471075917b6063fb80ac045b01678164f&scene=21#wechat_redirect)

## 搜索引擎
- [神马搜索技术演进之路](https://mp.weixin.qq.com/s?__biz=MzU1NTMyOTI4Mw==&mid=2247485830&idx=1&sn=621393b30e179660de9b35d57da60752&chksm=fbd4bbeacca332fcfe9733a126f07386ad66c3a0381b5e0c2daa81c70d88d0d19048fad645c1&scene=21#wechat_redirect)

## 模型

【Word2Vec】
- [Word2Vec的参数解释](https://blog.csdn.net/laobai1015/article/details/86540813)
- [Word2Vec的簡易教學與參數調整指南](https://www.kaggle.com/jerrykuo7727/word2vec)

【TextCNN】
- [TextCNN的优化经验](https://www.cnblogs.com/ModifyRong/p/11442661.html)

【Bert】
- [BERT模型原理详解系列](https://zhuanlan.zhihu.com/p/46652512)
- [BERT是如何分词的](https://cloud.tencent.com/developer/article/1524436)
- [CPU上的Bert性能优化](https://blog.roblox.com/2020/05/scaled-bert-serve-1-billion-daily-requests-cpus/)
- [跨语种语言模型](https://zhuanlan.zhihu.com/p/139630839)
