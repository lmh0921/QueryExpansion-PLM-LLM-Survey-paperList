# QueryExpansion-PLM-LLM-Survey

This repository collects papers related to **Query Expansion (QE)** for **Information Retrieval (IR)**, with emphasis on **PLM/LLM-era QE**.

- Most are in our survey paper: **Query Expansion in the Age of Pre-trained and Large Language Models: A Comprehensive Survey**

---

## 🌟 Citation

```bibtex
@article{li2025query,
  title={Query Expansion in the Age of Pre-trained and Large Language Models: A Comprehensive Survey},
  author={Li, Minghan and Lv, Xinxuan and Zou, Junjie and Chen, Tongna and Zhang, Chao and An, Suchao and Nie, Ercong and Zhou, Guodong},
  journal={arXiv preprint arXiv:2509.07794},
  year={2025}
}
```

---

## 📋 Table of Content

- [Prompt-only Generative QE](#prompt-only-generative-qe)
- [Grounded PRF / Feedback QE](#grounded-prf--feedback-qe)
- [Interactive / Multi-round QE](#interactive--multi-round-qe)
- [Distillation & Alignment (QE)](#distillation--alignment-qe)
- [KG-Augmented QE](#kg-augmented-qe)
- [Neural / Embedding-side QE](#neural--embedding-side-qe)
- [Domain-specific QE: Code Search](#domain-specific-qe-code-search)
- [Domain-specific QE: Biomedical / Scientific](#domain-specific-qe-biomedical--scientific)
- [Domain-specific QE: E-commerce](#domain-specific-qe-e-commerce)
- [Classic / Other QE (QE-related)](#classic--other-qe-qe-related)


---

## 📄 Paper List (QE-only, cited in the survey)


### Prompt-only Generative QE

- **BioRAGent: A Retrieval-Augmented Generation System for Showcasing Generative Query Expansion and Domain-Specific Search for Scientific Q&A** — Ateia, Samy, 2025 | European Conference on Information Retrieval. [[Paper](https://doi.org/10.1007/978-3-031-88720-8_1)] [[Code](https://github.com/SamyAteia/BioRAGent)]
- **Exp4Fuse: A Rank Fusion Framework for Enhanced Sparse Retrieval using Large Language Model-based Query Expansion** — Liu, Lingyuan, 2025 | Findings of the Association for Computational Linguistics: ACL 2025. [[Paper](https://doi.org/10.18653/v1/2025.findings-acl.9)] [[Code](https://github.com/liuliuyuan6/Exp4Fuse)]
- **Fair Exposure Allocation Using Generative Query Expansion** — Jaenich, Thomas, 2025 | European Conference on Information Retrieval. [[Paper](https://doi.org/10.1007/978-3-031-88717-8_20)]
- **Hypothetical Documents or Knowledge Leakage? Rethinking LLM-based Query Expansion** — Yoon, Yejun, 2025 | Findings of the Association for Computational Linguistics: ACL 2025. [[Paper](https://doi.org/10.18653/v1/2025.findings-acl.980)]
- **Knowledge-Aware Query Expansion with Large Language Models for Textual and Relational Retrieval** — Xia, Yu, 2025 | Proceedings of the 2025 Conference of the Nations of the Americas Chapter of the Association for Computational Linguistics: Human Language Technologies (Volume 1: Long Papers). [[Paper](https://doi.org/10.18653/v1/2025.naacl-long.216)]
- **LLM-based Query Expansion Fails for Unfamiliar and Ambiguous Queries** — Abe, Kenya, 2025 | Proceedings of the 48th International ACM SIGIR Conference on Research and Development in Information Retrieval. [[Paper](https://doi.org/10.1145/3726302.3730222)] [[Code](https://github.com/aken12/LLM-based-QE-fails)]
- **Analyze, generate and refine: Query expansion with LLMs for zero-shot open-domain QA** — Chen, Xinran, 2024 | Findings of the Association for Computational Linguistics ACL 2024. [[Paper](https://doi.org/10.18653/v1/2024.findings-acl.708)] [[Code](https://github.com/process-cxr/AGR)]
- **Corpus-Steered Query Expansion with Large Language Models** — Lei, Yibin, 2024 | Proceedings of the 18th Conference of the European Chapter of the Association for Computational Linguistics (Volume 2: Short Papers). [[Paper](https://doi.org/10.18653/v1/2024.eacl-short.34)] [[Code](https://github.com/Yibin-Lei/CSQE)]
- **Exploring the Best Practices of Query Expansion with Large Language Models** — Zhang, Le, 2024 | Findings of the Association for Computational Linguistics: EMNLP 2024. [[Paper](https://doi.org/10.18653/v1/2024.findings-emnlp.103)] [[Code](https://github.com/lezhang7/Retrieval_MuGI)]
- **Mill: Mutual verification with large language models for zero-shot query expansion** — Jia, Pengyue, 2024 | Proceedings of the 2024 Conference of the North American Chapter of the Association for Computational Linguistics: Human Language Technologies (Volume 1: Long Papers). [[Paper](https://doi.org/10.18653/v1/2024.naacl-long.138)] [[Code](https://github.com/Applied-Machine-Learning-Lab/MILL)]
- **SoftQE: Learned representations of queries expanded by LLMs** — Pimpalkhute, Varad, 2024 | European Conference on Information Retrieval. [[Paper](https://doi.org/10.1007/978-3-031-56066-8_8?urlappend=%3Futm_source%3Dresearchgate.net%26utm_medium%3Darticle)]
- **Generative Query Reformulation for Effective Adhoc Search** — Wang, Xiao, 2023 | Proceedings of the First Workshop on Generative Information Retrieval (Gen-IR@SIGIR 2023). [[Paper](https://arxiv.org/abs/2308.00415)]
- **Query expansion by prompting large language models** — Jagerman, Rolf, 2023 | arXiv preprint arXiv:2305.03653. [[Paper](https://doi.org/10.48550/arXiv.2305.03653)]
- **Query2doc: Query Expansion with Large Language Models** — Wang, Liang, 2023 | Proceedings of the 2023 Conference on Empirical Methods in Natural Language Processing. [[Paper](https://doi.org/10.18653/v1/2023.emnlp-main.585)]

### Grounded PRF / Feedback QE

- **ECLIPSE: Contrastive Dimension Importance Estimation with Pseudo-Irrelevance Feedback for Dense Retrieval** — D'Erasmo, Giulio, 2025 | Proceedings of the 2025 International ACM SIGIR Conference on Innovative Concepts and Theories in Information Retrieval (ICTIR). [[Paper](https://doi.org/10.1145/3731120.3744579)]
- **LLM-VPRF: Large Language Model Based Vector Pseudo Relevance Feedback** — Li, Hang, 2025 | arXiv preprint arXiv:2504.01448. [[Paper](https://doi.org/10.48550/arXiv.2504.01448)]
- **Pseudo Relevance Feedback is Enough to Close the Gap Between Small and Large Dense Retrieval Models** — Li, Hang, 2025 | arXiv preprint arXiv:2503.14887. [[Paper](https://doi.org/10.48550/arXiv.2503.14887)]
- **Selecting query-bag as pseudo relevance feedback for information-seeking conversations** — Zhang, Xiaoqing, 2024 | arXiv preprint arXiv:2404.04272. [[Paper](https://doi.org/10.48550/arXiv.2404.04272)]
- **ColBERT-PRF: Semantic pseudo-relevance feedback for dense passage and document retrieval** — Wang, Xiao, 2023 | ACM Transactions on the Web. [[Paper](https://doi.org/10.1145/3572405)]
- **Generative relevance feedback with large language models** — Mackie, Iain, 2023 | Proceedings of the 46th international ACM SIGIR conference on research and development in information retrieval. [[Paper](https://doi.org/10.1145/3539618.3591992)]
- **Improving query representations for dense retrieval with pseudo relevance feedback** — Yu, HongChien, 2021 | Proceedings of the 30th ACM International Conference on Information & Knowledge Management. [[Paper](https://doi.org/10.1145/3459637.3482124)]
- **Relevance feedback in information retrieval** — Rocchio Jr, Joseph John, 1971 | The SMART retrieval system: experiments in automatic document processing. 

### Interactive / Multi-round QE

- **ThinkQE: Query Expansion via an Evolving Thinking Process** — Lei, Yibin, 2025 | Findings of the Association for Computational Linguistics: EMNLP 2025. [[Paper](https://doi.org/10.18653/v1/2025.findings-emnlp.965)] [[Code](https://github.com/Yibin-Lei/Think_QE)]

### Distillation & Alignment (QE)

- **Aligned Query Expansion: Efficient Query Expansion for Information Retrieval through LLM Alignment** — Yang, Adam, 2025 | arXiv preprint arXiv:2507.11042. [[Paper](https://doi.org/10.48550/arXiv.2507.11042)]
- **RADCoT: Retrieval-augmented distillation to specialization models for generating chain-of-thoughts in query expansion** — Lee, Sung-Min, 2024 | Proceedings of the 2024 Joint International Conference on Computational Linguistics, Language Resources and Evaluation (LREC-COLING 2024). [[Paper](https://aclanthology.org/2024.lrec-main.1182/)] [[Code](https://github.com/ZIZUN/RADCoT)]

### KG-Augmented QE

- **A comparison of methods and techniques for ontological query expansion** — Sartori, Fabio, 2009 | Research Conference on Metadata and Semantic Research. [[Paper](https://doi.org/10.1007/978-3-642-04590-5_19)]
- **A review of ontology based query expansion** — Bhogal, Jagdev, 2007 | Information processing & management. [[Paper](https://doi.org/10.1016/j.ipm.2006.09.003)]
- **Ontology-based spatial query expansion in information retrieval** — Fu, Gaihua, 2005 | OTM Confederated International Conferences" On the Move to Meaningful Internet Systems". [[Paper](https://doi.org/10.1007/11575801_33)]
- **An analysis of ontology-based query expansion strategies** — Navigli, Roberto, 2003 | Proceedings of the 14th European Conference on Machine Learning, Workshop on Adaptive Text Extraction and Mining, Cavtat-Dubrovnik, Croatia. [[Paper](https://www.researchgate.net/publication/243777754_An_Analysis_of_Ontology-based_Query_Expansion_Strategies)]

### Neural / Embedding-side QE

- **Query Expansion with Topic-aware In-context Learning and Vocabulary Projection for Open-domain Dense Retrieval** — Li, Ronghan, 2025 | Pattern Recognition. [[Paper](https://doi.org/10.1016/j.patcog.2025.112812)] [[Code](https://github.com/XD-BDIV-NLP/TDPR)]
- **Personalized query expansion with contextual word embeddings** — Bassani, Elias, 2023 | ACM Transactions on Information Systems. [[Paper](https://doi.org/10.1145/3624988)]
- **CEQE to SQET: A study of contextualized embeddings for query expansion** — Naseri, Shahrzad, 2022 | Information Retrieval Journal. [[Paper](https://doi.org/10.1007/s10791-022-09405-y)] [[Code](https://github.com/sherinaseri/ceqe-release)]
- **Ceqe: Contextualized embeddings for query expansion** — Naseri, Shahrzad, 2021 | European conference on information retrieval. [[Paper](https://doi.org/10.1007/978-3-030-72113-8_31)] [[Code](https://github.com/sherinaseri/ceqe-release)]
- **BERT-QE: Contextualized Query Expansion for Document Re-ranking** — Zheng, Zhi, 2020 | Findings of the Association for Computational Linguistics: EMNLP 2020. [[Paper](https://doi.org/10.18653/v1/2020.findings-emnlp.424)] [[Code](https://github.com/zh-zheng/BERT-QE)]

### Domain-specific QE: Code Search

- **Enhancing Code Search through Query Expansion: A Fusion of LSTM with GloVe and BERT Model (ECSQE)** — Bibi, Nazia, 2025 | Results in Engineering. [[Paper](https://doi.org/10.1016/j.rineng.2025.105979)]
- **Self-supervised query reformulation for code search** — Mao, Yuetian, 2023 | Proceedings of the 31st acm joint european software engineering conference and symposium on the foundations of software engineering. [[Paper](https://doi.org/10.1145/3611643.3616306)] [[Code](https://github.com/RedSmallPanda/SSQR)]
- **Generation-augmented query expansion for code retrieval** — Li, Dong, 2022 | arXiv preprint arXiv:2212.10692. [[Paper](https://doi.org/10.48550/arXiv.2212.10692)]
- **Neural query expansion for code search** — Liu, Jason, 2019 | Proceedings of the 3rd acm sigplan international workshop on machine learning and programming languages. [[Paper](https://doi.org/10.1145/3315508.3329975)]
- **Expanding queries for code search using semantically related api class-names** — Zhang, Feng, 2017 | IEEE Transactions on Software Engineering. [[Paper](https://doi.org/10.1109/TSE.2017.2750682)]
- **A search log mining based query expansion technique to improve effectiveness in code search** — Satter, Abdus, 2016 | 2016 19th International Conference on Computer and Information Technology (ICCIT). [[Paper](https://doi.org/10.1109/ICCITECHN.2016.7860264)]
- **Query expansion based on crowd knowledge for code search** — Nie, Liming, 2016 | IEEE Transactions on Services Computing. [[Paper](https://doi.org/10.1109/TSC.2016.2560165)]
- **Query expansion via wordnet for effective code search** — Lu, Meili, 2015 | 2015 IEEE 22nd International Conference on Software Analysis, Evolution, and Reengineering (SANER). [[Paper](https://doi.org/10.1109/SANER.2015.7081874)]
- **Thesaurus-based automatic query expansion for interface-driven code search** — Lemos, Ot'avio AL, 2014 | Proceedings of the 11th working conference on mining software repositories. [[Paper](https://doi.org/10.1145/2597073.2597087)]

### Domain-specific QE: Biomedical / Scientific

- **Contextual Query Expansion for Conducting Technology-Assisted Biomedical Reviews.** — Khader, Ayesha, 2022 | Canadian AI. [[Paper](https://doi.org/10.21428/594757db.57f9f224)]
- **Enhancing Query Expansion for Rare Diseases in PubMed Using Embedding-Based Semantic Representations** — Kelly, Sam Kerr, 2021 | engRxiv. [[Paper](https://doi.org/10.31224/4535)]
- **The research of query expansion based on medical terms reweighting in medical information retrieval** — Diao, Lijuan, 2018 | EURASIP Journal on Wireless Communications and Networking. [[Paper](https://doi.org/10.1186/s13638-018-1124-3)]
- **Study of query expansion techniques and their application in the biomedical information retrieval** — Rivas, Andreia Rodriguez, 2014 | The Scientific World Journal. [[Paper](https://doi.org/10.1155/2014/132158)]
- **Evaluation of query expansion using MeSH in PubMed** — Lu, Zhiyong, 2009 | Information retrieval. [[Paper](https://doi.org/10.1007/s10791-008-9074-8)]
- **Query expansion using the UMLS Metathesaurus** — Aronson, Alan R, 1997 | Proceedings of the AMIA annual fall symposium. [[Paper](https://pmc.ncbi.nlm.nih.gov/articles/PMC2233565/)]

### Domain-specific QE: E-commerce

- **Large language model based long-tail query rewriting in taobao search** — Peng, Wenjun, 2024 | Companion Proceedings of the ACM Web Conference 2024. [[Paper](https://doi.org/10.1145/3589335.3648298)]
- **Modified query expansion through generative adversarial networks for information extraction in e-commerce** — Cakir, Altan, 2023 | Machine Learning with Applications. [[Paper](https://doi.org/10.1016/j.mlwa.2023.100509)]
- **Advancing Query Rewriting in E-Commerce via Shopping Intent Learning** — Zhang, Mengxiao, 2022 | Proceedings of the SIGIR 2022 Workshop on eCommerce (SIGIR eCom '22). [[Paper](https://www.amazon.science/publications/advancing-query-rewriting-in-e-commerce-via-shopping-intent-learning)]
- **Query Rewriting using Automatic Synonym Extraction for E-commerce Search.** — Mandal, Aritra, 2019 | eCOM@ SIGIR. [[Paper](https://api.semanticscholar.org/CorpusID:198120240)]

### Classic / Other QE (QE-related)

- **Query Expansion by Retrieval-Augmented Generation Based on DeepSeek** — Hu, Junying, 2025 | SSRN Electronic Journal. [[Paper](https://doi.org/10.2139/ssrn.5316412)]
- **Progressive query expansion for retrieval over cost-constrained data sources** — Rashid, Muhammad Shihab, 2024 | arXiv preprint arXiv:2406.07136. [[Paper](https://doi.org/10.48550/arXiv.2406.07136)]
- **A hybrid text generation-based query expansion method for open-domain question answering** — Zhu, Wenhao, 2023 | Future Internet. [[Paper](https://doi.org/10.3390/fi15050180)]
- **Event-Centric Query Expansion in Web Search** — Zhang, Yanan, 2023 | Proceedings of the 61st Annual Meeting of the Association for Computational Linguistics (Volume 5: Industry Track). [[Paper](https://doi.org/10.18653/v1/2023.acl-industry.45)] [[Code](https://open-event-hub.github.io/eqe/)]
- **Expand, Rerank, and Retrieve: Query Reranking for Open-Domain Question Answering** — Chuang, Yung-Sung, 2023 | Findings of the Association for Computational Linguistics: ACL 2023. [[Paper](https://doi.org/10.18653/v1/2023.findings-acl.768)] [[Code](https://github.com/voidism/EAR)]
- **Learning to rank query expansion terms for COVID-19 scholarly search** — Khader, Ayesha, 2023 | Journal of Biomedical Informatics. [[Paper](https://doi.org/10.1016/j.jbi.2023.104386)]
- **When self-supervision met Query Expansion** — Liu, XiangZheng, 2023 | Authorea Preprints. [[Paper](https://doi.org/10.36227/techrxiv.24101100.v1)]
- **Query expansion using contextual clue sampling with language models** — Liu, Linqing, 2022 | arXiv preprint arXiv:2210.07093. [[Paper](https://doi.org/10.48550/arXiv.2210.07093)]
- **A knowledge-based semantic framework for query expansion** — Nasir, Jamal Abdul, 2019 | Information processing & management. [[Paper](https://doi.org/10.1016/j.ipm.2019.04.007)]
- **A survey of statistical approaches for query expansion** — Raza, Muhammad Ahsan, 2019 | Knowledge and information systems. [[Paper](https://doi.org/10.1007/s10115-018-1269-8)]
- **Deep learning the semantics of change sequences for query expansion** — Huang, Qing, 2019 | Software: Practice and Experience. [[Paper](https://doi.org/10.1002/spe.2736)]
- **Query expansion for cross-language question re-ranking** — Rahman, Muhammad Mahbubur, 2019 | arXiv preprint arXiv:1904.07982. [[Paper](https://doi.org/10.48550/arXiv.1904.07982)]
- **Query expansion techniques for information retrieval: a survey** — Azad, Hiteshwar Kumar, 2019 | Information Processing & Management. [[Paper](https://doi.org/10.1016/j.ipm.2019.05.009)]
- **Query expansion based on statistical learning from code changes** — Huang, Qing, 2018 | Software: Practice and Experience. [[Paper](https://doi.org/10.1002/spe.2574)]
- **Querying concepts in product data by means of query expansion** — Homoceanu, Silviu, 2014 | Web intelligence and agent systems. [[Paper](https://doi.org/10.3233/WIA-140282)]
- **A survey of automatic query expansion in information retrieval** — Carpineto, Claudio, 2012 | Acm Computing Surveys (CSUR). [[Paper](https://doi.org/10.1145/2071389.2071390)]
- **A survey on query expansion based on local analysis** — Lei, Jiayin, 2011 | 2011 4th International Conference on Intelligent Networks and Intelligent Systems. [[Paper](https://doi.org/10.1109/ICINIS.2011.6)]
- **A new query expansion method based on query logs mining** — Kunpeng, Zhu, 2009 | International Journal on Asian Language Processing.[[Paper](http://www.colips.org/journals/volume19/19_1_-1-Zhu-KunPeng.pdf)]
- **Query expansion using external evidence** — Yin, Zhijun, 2009 | European conference on information retrieval. [[Paper](https://doi.org/10.1007/978-3-642-00958-7_33)]
- **Query recommendation using query logs in search engines** — Baeza-Yates, Ricardo, 2004 | International conference on extending database technology. [[Paper](https://doi.org/10.1007/978-3-540-30192-9_58)]
- **Query expansion by mining user logs** — Cui, Hang, 2003 | IEEE transactions on knowledge and data engineering. [[Paper](https://doi.org/10.1109/TKDE.2003.1209002)]
- **Probabilistic query expansion using query logs** — Cui, Hang, 2002 | Proceedings of the 11th international conference on World Wide Web. [[Paper](https://doi.org/10.1145/511446.511489)]
- **Query Expansion.** — Efthimiadis, Efthimis N, 1996 | Annual review of information science and technology (ARIST). 
- **Query expansion using lexical-semantic relations** — Voorhees, Ellen M, 1994 | SIGIR’94: Proceedings of the Seventeenth Annual International ACM-SIGIR Conference on Research and Development in Information Retrieval, organised by Dublin City University. [[Paper](https://hdl.handle.net/10356/42508)]
- **Concept based query expansion** — Qiu, Yonggang, 1993 | Proceedings of the 16th annual international ACM SIGIR conference on Research and development in information retrieval. [[Paper](https://doi.org/10.1145/160688.160713)]
- **The limitations of term co-occurrence data for query expansion in document retrieval systems** — Peat, Helen J, 1991 | Journal of the american society for information science. [[Paper](https://doi.org/10.1002/(SICI)1097-4571(199106)42:5%3C378::AID-ASI8%3E3.0.CO;2-8)]


---

## 🤝 Contributing

- Add QE papers / fix links by PR.

---

## 📜 License

MIT License (see `LICENSE`).
