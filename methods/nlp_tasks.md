# 自然语言处理相关任务

## 背景与展望
- [NLP综述（思维导图）](https://zhuanlan.zhihu.com/p/56802149)
- [BERT时代与后时代的NLP](https://zhuanlan.zhihu.com/p/66676144)

## 对话机器人chatbot
- [对话机器人](https://www.zhihu.com/column/c_1154767675480821760)

【Rasa】
- [rasa文章导引（用于收藏）](https://zhuanlan.zhihu.com/p/88112269)
- [Finetune BERT Embeddings with spaCy and Rasa](https://github.com/JulianGerhard21/bert_spacy_rasa)

## 命名实体识别NER

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

