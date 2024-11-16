
# Papers

| Date  | Code | Publication                  | Paper                                                                                                         | 主要内容                                                        |
|-------|-----------|------------------------------|--------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------|
| 23.03 | https://github.com/facebookresearch/SemDeDup | arxiv                      | SemDeDup: Data-efficient learning at web-scale through semantic deduplication| 对语义重复的数据进行清洗，先找Embedding再聚类再设置阈值进行门控。   |
|23.12|没找到|NeurIPS'23|D4: Improving LLM Pretraining via Document De-Duplication and Diversification|和SemDeDup一个作者，先用SemDeDup去重，然后重新聚类，再使用SSL Prototypes进行数据选择。他的数据重复选择是设计过的，而非随机的。|
| 23.06 |   没找到   | SIGMOD'23     | Near-Duplicate Sequence Search at Scale for Large Language Model Memorization Evaluation | 提出了对数据集里近似重复（Near-Duplicate）序列搜索算法 （算法为训练语料库中的每个序列创建min-hash草图，并比较查询序列的草图与训练序列的草图以找到近重复），以及新的评估方案（提出了评估LLM生成的文本中有多少具有训练数据中的近重复序列的问题。定义两个序列为近重复，如果它们的Jaccard相似度高于给定阈值）|
|24.05||WWW'24|Near-duplicate Question Detection|论文提出了一种方法，利用文本嵌入从词汇匹配到语义相似性的各种方法，有效地量化文本相似性|
|24.04|https://zenodo.org/records/10494170|ICSE 2024|Automatic Semantic Augmentation of Language Model Prompts (for Code Summarization)|在代码摘要任务中，自动地用语义事实增强LLM的提示可以提高性能|
|24.01||HILDA'24|Cocoon: Semantic Table Profiling Using Large Language Models|将语义信息融入统计剖析中。通过增加三个步骤来增强传统剖析方法：语义上下文、语义剖析和语义审查|
|23.09|https://huggingface.co/MBZUAI-LLM/SlimPajama-DC    以及   https://huggingface.co/datasets/MBZUAI-LLM/SlimPajama-627B-DC |arxiv|SlimPajama-DC: Understanding Data Combinations for LLM Training|在我们对 SlimPajama 的研究过程中，出现了两个关键的观察结果：(1) 全局重复数据删除与局部重复数据删除。我们分析和讨论全局（跨不同数据集源）和本地（在单一数据集源内）重复数据删除如何影响训练模型的性能。 (2) 组合中高度去重的多源数据集的比例。|
|24.03|https://github.com/lynnliu030/vldb25|arxiv|Optimizing LLM Queries in Relational Workloads|sql中优化llm的reasoning，一些底层我看不懂的缓存啥的，以及删除重复的冗余推理请求|
|24.03|https://github.com/nexync/dated_data/|arXiv|Dated Data: Tracing Knowledge Cutoffs in Large Language Models|关于有效Cutoffs和报告的cutoffs不一样的原因（1.新储存中存在大量旧数据；2.复杂的LLM的数据删除方案（语意重复和近似重复）|
|24.06||FORGE'24 （ICSE的workshop，24年开始的）|MeTMaP: Metamorphic Testing for Detecting False Vector Matching Problems in LLM Augmented Generation|提出一种检测生成错误的框架（语义相似的应该匹配，不相似的不匹配）|
|24.06|deepmind的，没给代码|arxiv|To Believe or Not to Believe Your LLM|benchmark  这个是一样的|
|24.03|https://github.com/KID-22/Cocktail|ACL'24|Cocktail: A Comprehensive Information Retrieval Benchmark with LLM-Generated Documents Integration|benchmark  感觉纯做实验，没提出新的东西，该论文提供了一个创新的基准测试Cocktail，用于评估和理解在LLM时代信息检索模型在处理混合语料库时的性能和偏见，对于IR领域的研究具有重要意义|
|23.09||EMNLP'23|Text Encoders Lack Knowledge: Leveraging Generative LLMs for Domain-Specific Semantic Textual Similarity|讨论文本相似性的，考虑继续详细看|


