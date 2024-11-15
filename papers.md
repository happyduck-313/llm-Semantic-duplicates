
# Papers

| Date  | Code | Publication                  | Paper                                                                                                         | 主要内容                                                        |
|-------|-----------|------------------------------|--------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------|
| 23.03 | https://github.com/facebookresearch/SemDeDup | arxiv                      | [SemDeDup: Data-efficient learning at web-scale through semantic deduplication](https://link-to-paper.com)                         | 对语义重复的数据进行清洗，先找Embedding再聚类再设置阈值进行门控。                                         |
|23.12|没找到|NeurIPS'23|[D4: Improving LLM Pretraining via Document De-Duplication and Diversification](https://link-to-paper.com)|和SemDeDup一个作者|
| 23.06 |   没找到   | SIGMOD'23     | [Near-Duplicate Sequence Search at Scale for Large Language Model Memorization Evaluation](https://link-to-paper.com) | 提出了对数据集里近似重复（Near-Duplicate）序列搜索算法 ，以及新的评估方案|
|24.05||WWW'24|[Near-duplicate Question Detection](https://link-to-paper.com)||
|24.04||ICSE 2024|[Automatic Semantic Augmentation of Language Model Prompts (for Code Summarization)](https://link-to-paper.com)||
|24.01||HILDA'24(workshop)|[Cocoon: Semantic Table Profiling Using Large Language Models](https://link-to-paper.com)||
|23.09|https://huggingface.co/MBZUAI-LLM/SlimPajama-DC    以及   https://huggingface.co/datasets/MBZUAI-LLM/SlimPajama-627B-DC |arxiv|[SlimPajama-DC: Understanding Data Combinations for LLM Training](https://link-to-paper.com)|在我们对 SlimPajama 的研究过程中，出现了两个关键的观察结果：(1) 全局重复数据删除与局部重复数据删除。我们分析和讨论全局（跨不同数据集源）和本地（在单一数据集源内）重复数据删除如何影响训练模型的性能。 (2) 组合中高度去重的多源数据集的比例。|
|24.03|https://github.com/lynnliu030/vldb25|arxiv|[Optimizing LLM Queries in Relational Workloads](https://link-to-paper.com)|sql中优化llm的reasoning，一些底层我看不懂的缓存啥的，以及删除重复的冗余推理请求|
|24.03|https://github.com/nexync/dated_data/|arXiv|[Dated Data: Tracing Knowledge Cutoffs in Large Language Models](https://link-to-paper.com)|关于有效Cutoffs和报告的cutoffs不一样的原因（1.新储存中存在大量旧数据；2.复杂的LLM的数据删除方案（语意重复和近似重复）|
|24.06||FORGE'24|[MeTMaP: Metamorphic Testing for Detecting False Vector Matching Problems in LLM Augmented Generation](https://link-to-paper.com)|提出一种检测生成错误的框架（语义相似的应该匹配，不相似的不匹配）|
|24.06|deepmind的，没给代码|arxiv|[To Believe or Not to Believe Your LLM](https://link-to-paper.com)|benchmark 3.0 这个是一样的|
|24.03|https://github.com/KID-22/Cocktail|ACL'24|[Cocktail: A Comprehensive Information Retrieval Benchmark with LLM-Generated Documents Integration](https://link-to-paper.com)|benchmark 2.0 感觉纯做实验，没提出新的东西|
|24.02|https://anonymous.4open.science/r/llm_eval-E16D/|arxiv|[Benchmarking LLMs on the Semantic Overlap Summarization Task](https://link-to-paper.com)|benchmark 1.0 |
|23.09||EMNLP'23|[Text Encoders Lack Knowledge: Leveraging Generative LLMs for Domain-Specific Semantic Textual Similarity](https://link-to-paper.com)|讨论文本相似性的，考虑继续详细看|


