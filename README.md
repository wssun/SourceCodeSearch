# A Survey of Source Code Search: A 3-Dimensional Perspective

A collection of academic papers on code search techniques from a **3-dimensional (query-end, code-end, match-end)** perspective. 


**NOTE: We intend to keep updating with the most recent papers whenever time permits, and we warmly welcome pull requests or issues regarding any missing papers. If you find any information is incorrect, please feel free to contact us. We will promptly confirm and make the necessary corrections. All researchers are encouraged to participate in enhancing this repository and expanding the knowledge within the field of source code search.**


[//]: # ([![Awesome]&#40;https://awesome.re/badge.svg&#41;]&#40;https://awesome.re&#41;)

[![arXiv](https://img.shields.io/badge/arXiv-2311.07107-b31b1b.svg)](https://arxiv.org/abs/2311.07107)
![GitHub stars](https://img.shields.io/github/stars/wssun/SourceCodeSearch?color=yellow&label=Stars)

[//]: # (![visitor badge]&#40;https://visitor-badge.glitch.me/badge?page_id=%20QuanjunZhang.AwesomeLearningAPR&#41; )






## Citation

Please read and cite our paper: [![arXiv](https://img.shields.io/badge/arXiv-2311.07107-b31b1b.svg)](https://arxiv.org/abs/2311.07107)

```
@article{2023-Code-Search-Survey-3D-Perspective,
  title={A Survey of Source Code Search: A 3-Dimensional Perspective},
  author={Weisong Sun, Chunrong Fang, Yifei Ge, Yuling Hu, Yuchen Chen, Quanjun Zhang, Xiuting Ge, Yang Liu, Zhenyu Chen},
  journal={arXiv preprint arXiv:2301.03270},
  year={2023}
}
```

----------

## Overall Framework of the code search technique
![dlapr](figs/framework_of_code_search.png)
----------

## Collected Papers in Query End
| **Number** | **Paper Title** | **Venue** | **Year** | **Code Available**                           |
| --- | --------------- | -- |------|----------------------------------------------|
| 1 | [Self-Supervised Query Reformulation for Code Search](http://arxiv.org/abs/2307.00267) | _arXiv_ | 2023 | [yes](https://github.com/RedSmallPanda/SSQR) |
| 2 | [XCoS: Explainable Code Search Based on Query Scoping and Knowledge Graph](https://dl.acm.org/doi/10.1145/3315508.3329975) | _TOSEM_ | 2023 | no |
| 3 | [Hyperbolic Code Retrieval: A Novel Approach for Efficient Code Search Using Hyperbolic Space Embeddings](http://arxiv.org/abs/2308.15234) | _arXiv_ | 2023 | no |
| 4 | [CSSAM:Code Search via Attention Matching of Code Semantics and Structures](http://arxiv.org/abs/2208.03922) | _arXiv_     | 2022  | no |
| 5 | [Utilizing Edge Attention in Graph-Based Code Search](http://ksiresearchorg.ipage.com/seke/seke22paper/paper078.pdf) | _SEKE_     | 2022    | no |
| 6 | [Incorporating Code Structure and Quality in Deep Code Search](https://www.mdpi.com/2076-3417/12/4/2051) | _Applied Sciences_     | 2022     | no |
| 7 | [Learning Deep Semantic Model for Code Search using CodeSearchNet Corpus](http://arxiv.org/abs/2201.11313) | _arXiv_     | 2022     | [yes](https://github.com/overwindows/SemanticCodeSearch) |
| 8 | [Joint Embedding of Semantic and Statistical Features for Effective Code Search](https://www.mdpi.com/2076-3417/12/19/10002) | _Applied Sciences_     | 2022     | no |
| 9 | [Boosting Code Search with Structural Code Annotation](https://www.mdpi.com/2079-9292/11/19/3053)  | _Electronics_    | 2022     | no  |
| 10 | [Fine-grained Co-Attentive Representation Learning for Semantic Code Search](https://ieeexplore.ieee.org/document/9825816/) | _SANER_     | 2022     | [yes](https://github.com/cqu-isse/FcarCS) |
| 11 | [CSRS: Code Search with Relevance Matching and Semantic Matching](http://arxiv.org/abs/2203.07736) | _arXiv_     | 2022   | no |
| 12 | [OCoR: An Overlapping-Aware Code Retriever](https://dl.acm.org/doi/10.1145/1122445.1122456) | _Computing Surveys_ | 2022 | [yes](https://github.com/anyone546/OCoR.) |
| 13 | [Deep Graph Matching and Searching for Semantic Code Retrieval](https://dl.acm.org/doi/10.1145/3447571) | _TKDD_     | 2021 | [yes](https://github.com/ryderling/DGMS) |
| 14 | [Two-Stage Attention-Based Model for Code Search with Textual and Structural Features](https://ieeexplore.ieee.org/document/9425924/) | _SANER_     | 2021     | [yes](https://github.com/cqu-isse/TabCS) |
| 15 | [An Intelligent Code Search Approach Using Hybrid Encoders](https://www.hindawi.com/journals/wcmc/2021/9990988/) | _WCMC_ | 2021 | no  |
| 16 | [deGraphCS: Embedding Variable-based Flow Graph for Neural Code Search](http://arxiv.org/abs/2103.13020) | _TOSEM_     | 2021     | 
| 17 | [Enriching Query Semantics for Code Search with Reinforcement Learning](http://arxiv.org/abs/2105.09630) | _arXiv_ | 2021 | no |
| 18 | [Multimodal Representation for Neural Code Search](http://arxiv.org/abs/2107.00992) | _ICSME_     | 2021     | [yes](https://github.com/jianguda/mrncs) |
| 19 | [Search for Compatible Source Code](https://www.worldscientific.com/doi/abs/10.1142/S0218194021500169) | _IJSEKE_ | 2021 | no |
| 20 | [Self-Attention Networks for Code Search](https://linkinghub.elsevier.com/retrieve/pii/S0950584921000288) | _IST_     | 2021   | [yes](https://github.com/TomasAndersonFang/SANCS) |
| 21 | [CoNCRA: A Convolutional Neural Network Code Retrieval Approach](http://arxiv.org/abs/2009.01959)   | _arXiv_     | 2020     | no |
| 22 | [PSCS: A Path-based Neural Model for Semantic Code Search](http://arxiv.org/abs/2008.03042) | _arXiv_     | 2020     | no |
| 23 | [Improving Code Search with Co-Attentive Representation Learning](https://dl.acm.org/doi/10.1145/3387904.3389269) | _ICPC_     | 2020     | no |
| 24 | [CSDA: A novel attention-based LSTM approach for code search](https://iopscience.iop.org/article/10.1088/1742-6596/1544/1/012056/meta) | _JPCS_   | 2020     | no |
| 25 | [Adaptive Deep Code Search](https://dl.acm.org/doi/10.1145/3387904.3389278) | _ICPC_     | 2020     | no |
| 26 | [CRaDLe: Deep Code Retrieval Based on Semantic Dependency Learning](http://arxiv.org/abs/2012.01028) | _arXiv_     | 2020     | no |
| 27 | [Unsupervised software repositories mining and its application to code search](https://dl.acm.org/doi/10.1145/3315508.3329975) | _SPE_ | 2020 | no |
| 28 | [Automatic query reformulation for code search using crowdsourced knowledge](http://link.springer.com/10.1007/s10664-018-9671-0) | _ESE_ | 2019 | no  |
| 29 | [Neural query expansion for code search](https://dl.acm.org/doi/10.1145/3315508.3329975) | _PLDI_ | 2019 | no |
| 30 | [Deep learning the semantics of change sequences for query expansion](https://onlinelibrary.wiley.com/doi/10.1002/spe.2736) | _SPE_ | 2019 | no |
| 31 | [Multi-modal Attention Network Learning for Semantic Source Code Retrieval](https://ieeexplore.ieee.org/document/8952337/) | _ASE_ | 2019 | no |
| 32 | [Query expansion based on statistical learning from code changes](http://ieeexplore.ieee.org/document/7372014/) | _SPE_ | 2018 | no |
| 33 | [LANGUA SOURCE CODE RETRIEVAL USING KEYWORD & IDENTIFIER LEXICAL GE-AGNOSTICPATTERN](http://ieeexplore.ieee.org/document/7372014/) | _IJSECS_ | 2018 | no |
| 34 | [Interactive Query Reformulation for Source-Code Search With Word Relations](https://ieeexplore.ieee.org/document/8552658/) | _IEEE Access_ | 2018 | no |
| 35 | [Retrieval on source code: a neural code search](http://arxiv.org/abs/2307.00267) | _PLDI_ | 2018 | no |
| 36 | [Deep code search](https://dl.acm.org/doi/10.1145/3180155.3180167) | _ICSE_     | 2018     | [yes](https://github.com/guxd/deep-code-search) |
| 37 | [Expanding Queries for Code Search Using Semantically Related API Class-names](https://ieeexplore.ieee.org/document/8031055/) | _TSE_ | 2018 | no |
| 38 | [Augmenting and structuring user queries to support efficient free-form code search](http://link.springer.com/10.1007/s10664-017-9544-y) | _ESE_ | 2018 | no |
| 39 | [Learning to rank code examples for code search engines](http://link.springer.com/10.1007/s10664-015-9421-5) | _ESE_ | 2017 | no |
| 40 | [IECS: Intent-Enforced Code Search via Extended Boolean Model](https://www.medra.org/servlet/aliasResolver?alias=iospress&doi=10.3233/JIFS-161994) | _IFS_ | 2017 | no |
| 41 | [APIBook: an effective approach for finding APIs](https://doi.org/10.1145/2993717.2993727) | _Internetware_ | 2016 | no | 
| 42 | [Query Expansion Based on Crowd Knowledge for Code Search](http://ieeexplore.ieee.org/document/7462267/) | _TSC_ | 2016 | no |
| 43 | [Query expansion via WordNet for effective code search](http://ieeexplore.ieee.org/document/7081874/) | _SANER_ | 2015 | no |
| 44 | [CodeHow: Effective Code Search Based on API Understanding and Extended Boolean Model](http://ieeexplore.ieee.org/document/7372014/) | _ASE_ | 2015 | no |

[//]: # (| 4 | [SWIM: synthesizing what i mean: code search and idiomatic snippet synthesis]&#40;https://dl.acm.org/doi/10.1145/2884781.2884808&#41; | _ICSE_ | 2016 | no |)
[//]: # (| 6 | [RACK: Automatic API Recommendation Using Crowdsourced Knowledge]&#40;http://ieeexplore.ieee.org/document/7476656/&#41; | _SANER_ | 2016 | no |)
[//]: # (| 12 | [Effective Reformulation of Query for Code Search using Crowdsourced Knowledge and Extra-Large Data Analytics]&#40;http://arxiv.org/abs/1807.08798&#41; | _ICSME_ | 2018 | no |)
[//]: # (| 47 | [RunEx: Augmenting Regular-Expression Code Search with Runtime Values]&#40;https://from.so/static/dbaae30940b60addb67914a0cf61f215/Run_Exp_VLHCC_2023_386558a2d3.pdf&#41; | _VL/HCC_ | 2023 | no |)
[//]: # (| 12 | [Improving source code search with natural language phrasal representations of method signatures]&#40;http://ieeexplore.ieee.org/document/6100115/&#41; | _ASE_ | 2011 | no |)
[//]: # (| 4 | [CONQUER: A Tool for NL-based Query Reﬁnement & Contextualizing Code Search Results]&#40;https://ieeexplore.ieee.org/abstract/document/6676945/&#41; | _ICSME_ | 2013 | no |)

----------

## Collected Papers in Code End
| **Number** | **Paper Title** | **Venue** | **Year** | **Code Available**                           |
| --- | --------------- | -- |------|----------------------------------------------|
| 1 | [GraphSearchNet: Enhancing GNNs via Capturing Global Dependencies for Semantic Code Search](https://ieeexplore.ieee.org/document/10005619) | _TSE_     | 2023     | [yes](https://github.com/shangqing-liu/GraphSearchNet) |
| 2 | [Hyperbolic Code Retrieval: A Novel Approach for Efficient Code Search Using Hyperbolic Space Embeddings](http://arxiv.org/abs/2308.15234) | _arXiv_ | 2023 | no |
| 3 | [CSRS: Code Search with Relevance Matching and Semantic Matching](http://arxiv.org/abs/2203.07736) | _arXiv_     | 2022   | no |
| 4 | [SPT-Code: Sequence-to-Sequence Pre-Training for Learning Source Code Representations](http://arxiv.org/abs/2201.01549) | _arXiv_ | 2022 | no |
| 5 | [Accelerating Code Search with Deep Hashing and Code Classification](http://arxiv.org/abs/2203.15287) | _arXiv_ | 2022 | no |
| 6 | [Joint Embedding of Semantic and Statistical Features for Effective Code Search](https://www.mdpi.com/2076-3417/12/19/10002) | _Applied Sciences_     | 2022     | no |
| 7 | [Learning Deep Semantic Model for Code Search using CodeSearchNet Corpus](http://arxiv.org/abs/2201.11313) | _arXiv_     | 2022     | [yes](https://github.com/overwindows/SemanticCodeSearch) |
| 8 | [Utilizing Edge Attention in Graph-Based Code Search](http://ksiresearchorg.ipage.com/seke/seke22paper/paper078.pdf) | _SEKE_     | 2022    | no |
| 9 | [CodeMatcher: Searching Code Based on Sequential Semantics of Important Query Words](http://arxiv.org/abs/2005.14373) | _TOSEM_ | 2022 | no |
| 10 | [CSSAM:Code Search via Attention Matching of Code Semantics and Structures](http://arxiv.org/abs/2208.03922) | _arXiv_     | 2022  | no |
| 11 | [Fine-grained Co-Attentive Representation Learning for Semantic Code Search](https://ieeexplore.ieee.org/document/9825816/) | _SANER_     | 2022     | [yes](https://github.com/cqu-isse/FcarCS) |
| 12 | [Incorporating Code Structure and Quality in Deep Code Search](https://www.mdpi.com/2076-3417/12/4/2051) | _Applied Sciences_     | 2022     | no |
| 13 | [Boosting Code Search with Structural Code Annotation](https://www.mdpi.com/2079-9292/11/19/3053)  | _Electronics_    | 2022     | no  |
| 14 | [OCoR: An Overlapping-Aware Code Retriever](https://dl.acm.org/doi/10.1145/1122445.1122456) | _Computing Surveys_ | 2022 | [yes](https://github.com/anyone546/OCoR.) |
| 15 | [An Intelligent Code Search Approach Using Hybrid Encoders](https://www.hindawi.com/journals/wcmc/2021/9990988/) | _WCMC_ | 2021 | no  |
| 16 | [Search for Compatible Source Code](https://www.worldscientific.com/doi/abs/10.1142/S0218194021500169) | _IJSEKE_ | 2021 | no |
| 17 | [GraphCodeBERT: Pre-training Code Representations with Data Flow](http://arxiv.org/abs/2009.08366) | _arXiv_ | 2021 | no |
| 18 | [Self-Attention Networks for Code Search](https://linkinghub.elsevier.com/retrieve/pii/S0950584921000288) | _IST_ | 2021   | [yes](https://github.com/TomasAndersonFang/SANCS) |
| 19 | [Two-Stage Attention-Based Model for Code Search with Textual and Structural Features](https://ieeexplore.ieee.org/document/9425924/) | _SANER_     | 2021     | [yes](https://github.com/cqu-isse/TabCS) |
| 20 | [Enriching Query Semantics for Code Search with Reinforcement Learning](http://arxiv.org/abs/2105.09630) | _arXiv_ | 2021 | no |
| 21 | [Deep Graph Matching and Searching for Semantic Code Retrieval](https://dl.acm.org/doi/10.1145/3447571) | _TKDD_     | 2021     | [yes](https://github.com/ryderling/DGMS) |
| 22 | [deGraphCS: Embedding Variable-based Flow Graph for Neural Code Search](http://arxiv.org/abs/2103.13020) | _TOSEM_     | 2021     | [yse](https://github.com/degraphcs/DeGraphCS) |
| 23 | [FACER: An API Usage-based Code-example Recommender for Opportunistic Reuse](https://link.springer.com/article/10.1007/s10664-021-10000-w) | _ESE_     | 2021     | no |
| 24 | [Is a Single Model Enough? MuCoS: A Multi-Model Ensemble Learning for Semantic Code Search](http://arxiv.org/abs/2107.04773) | _arXiv_     | 2021    | no |
| 25 | [Multimodal Representation for Neural Code Search](http://arxiv.org/abs/2107.00992) | _ICSME_     | 2021     | [yes](https://github.com/jianguda/mrncs) |
| 26 | [Neural joint attention code search over structure embeddings for software Q&A sites](https://linkinghub.elsevier.com/retrieve/pii/S0164121220301886) | _JSS_     | 2020    | [yes](https://github.com/hoogang/NJACS) |
| 27 | [CodeBERT: A Pre-Trained Model for Programming and Natural Languages](http://arxiv.org/abs/2002.08155) | _arXiv_ | 2020 | [yes](https://github.com/microsoft/CodeBERT) |
| 28 | [PSCS: A Path-based Neural Model for Semantic Code Search](http://arxiv.org/abs/2008.03042) | _arXiv_     | 2020     | no |
| 29 | [Recommendation Based on Java Code Analysis and Search](https://ebooks.iospress.nl/doi/10.3233/FAIA200728) | _FSDM_   | 2020     | [yes](https://github.com/fushanqing/CodeTip)             |
| 30 | [CSDA: A novel attention-based LSTM approach for code search](https://iopscience.iop.org/article/10.1088/1742-6596/1544/1/012056/meta) | _JPCS_   | 2020     | no |
| 31 | [A Multi-Perspective Architecture for Semantic Code Search](https://www.aclweb.org/anthology/2020.acl-main.758) | _ACL_     | 2020     | [yes](https://github.com/rajarshihaldar/codetextmatch) |
| 32 | [Enhancing example-based code search with functional semantics](https://linkinghub.elsevier.com/retrieve/pii/S0164121220300492) | _JSS_ | 2020 | no |
| 33 | [Improving Code Search with Co-Attentive Representation Learning](https://dl.acm.org/doi/10.1145/3387904.3389269) | _ICPC_     | 2020     | no |
| 34 | [Adaptive Deep Code Search](https://dl.acm.org/doi/10.1145/3387904.3389278) | _ICPC_     | 2020     | no |
| 35 | [CoNCRA: A Convolutional Neural Network Code Retrieval Approach](http://arxiv.org/abs/2009.01959)   | _arXiv_     | 2020     | no |
| 36 | [COSEA: Convolutional Code Search with Layer-wise Attention](http://arxiv.org/abs/2010.09520)  | _arXiv_ | 2020  | no |
| 37 | [CRaDLe: Deep Code Retrieval Based on Semantic Dependency Learning](http://arxiv.org/abs/2012.01028) | _arXiv_     | 2020     | no |
| 38 | [ROSF: Leveraging Information Retrieval and Supervised Learning for Recommending Code Snippets](https://ieeexplore.ieee.org/document/7516727/) |  _TSC_ | 2019 | no |
| 39 | [Automatic query reformulation for code search using crowdsourced knowledge](http://link.springer.com/10.1007/s10664-018-9671-0) | _ESE_ | 2019 | no  |
| 40 | [Multi-modal Attention Network Learning for Semantic Source Code Retrieval](https://ieeexplore.ieee.org/document/8952337/) | _ASE_     | 2019    | no |
| 41 | [Augmenting and structuring user queries to support efficient free-form code search](http://link.springer.com/10.1007/s10664-017-9544-y) | _ESE_ | 2018 | no |
| 42 | [CoaCor: Code Annotation for Code Retrieval with Reinforcement Learning](http://arxiv.org/abs/1904.00720) | _arXiv_ | 2018 | [yes](https://github.com/LittleYUYU/CoaCor.) |
| 43 | [Expanding Queries for Code Search Using Semantically Related API Class-names](https://ieeexplore.ieee.org/document/8031055/) | _TSE_ | 2018 | no |
| 44 | [Retrieval on source code: a neural code search](http://arxiv.org/abs/2307.00267) | _PLDI_ | 2018 | no |
| 45 | [A neural framework for retrieval and summarization of source code](https://dl.acm.org/doi/10.1145/3238147.3240471) | _ASE_     | 2018     | no              |
| 46 | [Deep code search](https://dl.acm.org/doi/10.1145/3180155.3180167) | _ICSE_     | 2018     | [yse](https://github.com/guxd/deep-code-search) |
| 47 | [Learning to rank code examples for code search engines](http://link.springer.com/10.1007/s10664-015-9421-5) | _ESE_ | 2017 | no |
| 48 | [CodeHow: Effective Code Search Based on API Understanding and Extended Boolean Model](http://ieeexplore.ieee.org/document/7372014/) | _ASE_ | 2015 | no |
| 49 | [Portfolio: finding relevant functions and their usage](https://dl.acm.org/doi/10.1145/1985793.1985809) | _ICSE_     | 2011    | no |
| 50 | [Sourcerer: mining and searching internet-scale software repositories](http://link.springer.com/10.1007/s10618-008-0118-x) | _DMKD_     | 2009    | no |

----------
## Collected Papers in Match End
| **Number** | **Paper Title** | **Venue** | **Year** | **Code Available**                           |
| --- | --------------- | -- |------|----------------------------------------------|
| 1 | [Self-Supervised Query Reformulation for Code Search](http://arxiv.org/abs/2307.00267) | _arXiv_ | 2023 | [yes](https://github.com/RedSmallPanda/SSQR) |
| 2 | [Hyperbolic Code Retrieval: A Novel Approach for Efficient Code Search Using Hyperbolic Space Embeddings](http://arxiv.org/abs/2308.15234) | _arXiv_ | 2023 | no |
| 3 | [Accelerating Code Search with Deep Hashing and Code Classification](http://arxiv.org/abs/2203.15287) | _arXiv_ | 2022 | no |
| 4 | [Cascaded Fast and Slow Models for Efficient Semantic Code Search](http://arxiv.org/abs/2110.07811) | _arXiv_ | 2022 | no |
| 5 | [CSSAM:Code Search via Attention Matching of Code Semantics and Structures](http://arxiv.org/abs/2208.03922) | _arXiv_     | 2022  | no |
| 6 | [Incorporating Code Structure and Quality in Deep Code Search](https://www.mdpi.com/2076-3417/12/4/2051) | _Applied Sciences_     | 2022     | no |
| 7 | [Utilizing Edge Attention in Graph-Based Code Search](http://ksiresearchorg.ipage.com/seke/seke22paper/paper078.pdf) | _SEKE_     | 2022    | no |
| 8 | [CodeMatcher: Searching Code Based on Sequential Semantics of Important Query Words](http://arxiv.org/abs/2005.14373) | _TOSEM_ | 2022 | no |
| 9 | [OCoR: An Overlapping-Aware Code Retriever](https://dl.acm.org/doi/10.1145/1122445.1122456) | _Computing Surveys_ | 2022 | [yes](https://github.com/anyone546/OCoR.) |
| 10 | [Learning Deep Semantic Model for Code Search using CodeSearchNet Corpus](http://arxiv.org/abs/2201.11313) | _arXiv_     | 2022     | [yes](https://github.com/overwindows/SemanticCodeSearch) |
| 11 | [Joint Embedding of Semantic and Statistical Features for Effective Code Search](https://www.mdpi.com/2076-3417/12/19/10002) | _Applied Sciences_     | 2022     | no |
| 12 | [Fine-grained Co-Attentive Representation Learning for Semantic Code Search](https://ieeexplore.ieee.org/document/9825816/) | _SANER_     | 2022     | [yes](https://github.com/cqu-isse/FcarCS) |
| 13 | [SPT-Code: Sequence-to-Sequence Pre-Training for Learning Source Code Representations](http://arxiv.org/abs/2201.01549) | _arXiv_ | 2022 | no |
| 14 | [Enriching Query Semantics for Code Search with Reinforcement Learning](http://arxiv.org/abs/2105.09630) | _arXiv_ | 2021 | no |
| 15 | [Two-Stage Attention-Based Model for Code Search with Textual and Structural Features](https://ieeexplore.ieee.org/document/9425924/) | _SANER_     | 2021     | [yes](https://github.com/cqu-isse/TabCS) |
| 16 | [An Intelligent Code Search Approach Using Hybrid Encoders](https://www.hindawi.com/journals/wcmc/2021/9990988/) | _WCMC_ | 2021 | no  |
| 17 | [Deep Graph Matching and Searching for Semantic Code Retrieval](https://dl.acm.org/doi/10.1145/3447571) | _TKDD_     | 2021     | [yes](https://github.com/ryderling/DGMS) |
| 18 | [Multimodal Representation for Neural Code Search](http://arxiv.org/abs/2107.00992) | _ICSME_     | 2021     | [yes](https://github.com/jianguda/mrncs) |
| 19 | [Self-Attention Networks for Code Search](https://linkinghub.elsevier.com/retrieve/pii/S0950584921000288) | _IST_ | 2021   | [yes](https://github.com/TomasAndersonFang/SANCS) |
| 20 | [Search for Compatible Source Code](https://www.worldscientific.com/doi/abs/10.1142/S0218194021500169) | _IJSEKE_ | 2021 | no |
| 21 | [FACER: An API Usage-based Code-example Recommender for Opportunistic Reuse](https://link.springer.com/article/10.1007/s10664-021-10000-w) | _ESE_     | 2021     | no |
| 22 | [GraphCodeBERT: Pre-training Code Representations with Data Flow](http://arxiv.org/abs/2009.08366) | _arXiv_ | 2021 | no |
| 23 | [deGraphCS: Embedding Variable-based Flow Graph for Neural Code Search](http://arxiv.org/abs/2103.13020) | _TOSEM_     | 2021     | 
| 24 | [GraphSearchNet: Enhancing GNNs via Capturing Global Dependencies for Semantic Code Search](http://arxiv.org/abs/2111.02671) | _arXiv_ | 2021 | no |
| 25 | [PSCS: A Path-based Neural Model for Semantic Code Search](http://arxiv.org/abs/2008.03042) | _arXiv_     | 2020     | no |
| 26 | [CodeBERT: A Pre-Trained Model for Programming and Natural Languages](http://arxiv.org/abs/2002.08155) | _arXiv_ | 2020 | [yes](https://github.com/microsoft/CodeBERT) |
| 27 | [Improving Code Search with Co-Attentive Representation Learning](https://dl.acm.org/doi/10.1145/3387904.3389269) | _ICPC_     | 2020     | no |
| 28 | [CSDA: A novel attention-based LSTM approach for code search](https://iopscience.iop.org/article/10.1088/1742-6596/1544/1/012056/meta) | _JPCS_   | 2020     | no |
| 29 | [Adaptive Deep Code Search](https://dl.acm.org/doi/10.1145/3387904.3389278) | _ICPC_     | 2020     | no |
| 30 | [Neural joint attention code search over structure embeddings for software Q&A sites](https://linkinghub.elsevier.com/retrieve/pii/S0164121220301886) | _JSS_     | 2020    | [yes](https://github.com/hoogang/NJACS) |
| 31 | [Unsupervised software repositories mining and its application to code search](https://dl.acm.org/doi/10.1145/3315508.3329975) | _SPE_ | 2020 | no |
| 32 | [A Multi-Perspective Architecture for Semantic Code Search](https://www.aclweb.org/anthology/2020.acl-main.758) | _ACL_     | 2020     | [yes](https://github.com/rajarshihaldar/codetextmatch) |
| 33 | [CRaDLe: Deep Code Retrieval Based on Semantic Dependency Learning](http://arxiv.org/abs/2012.01028) | _arXiv_     | 2020     | no |
| 34 | [Recommendation Based on Java Code Analysis and Search](https://ebooks.iospress.nl/doi/10.3233/FAIA200728) | _FSDM_   | 2020     | [yes](https://github.com/fushanqing/CodeTip)             |
| 35 | [CoNCRA: A Convolutional Neural Network Code Retrieval Approach](http://arxiv.org/abs/2009.01959)   | _arXiv_     | 2020    | no |
| 36 | [TranS^3: A Transformer-based Framework for Unifying Code Summarization and Code Search](http://arxiv.org/abs/2003.03238) | _arXiv_ | 2020 | no |
| 37 | [Enhancing example-based code search with functional semantics](https://linkinghub.elsevier.com/retrieve/pii/S0164121220300492) | _JSS_ | 2020 | no |
| 38 | [ROSF: Leveraging Information Retrieval and Supervised Learning for Recommending Code Snippets](https://ieeexplore.ieee.org/document/7516727/) |  _TSC_ | 2019 | no |
| 39 | [Multi-modal Attention Network Learning for Semantic Source Code Retrieval](https://ieeexplore.ieee.org/document/8952337/) | _ASE_ | 2019 | no |
| 40 | [Neural query expansion for code search](https://dl.acm.org/doi/10.1145/3315508.3329975) | _PLDI_ | 2019 | no |
| 41 | [Expanding Queries for Code Search Using Semantically Related API Class-names](https://ieeexplore.ieee.org/document/8031055/) | _TSE_ | 2018 | no |
| 42 | [Augmenting and structuring user queries to support efficient free-form code search](http://link.springer.com/10.1007/s10664-017-9544-y) | _ESE_ | 2018 | no |
| 43 | [Retrieval on source code: a neural code search](http://arxiv.org/abs/2307.00267) | _PLDI_ | 2018 | no |
| 44 | [LANGUAGE-AGNOSTIC SOURCE CODE RETRIEVAL USING KEYWORD & IDENTIFIER LEXICAL PATTERN](http://ijsecs.ump.edu.my/images/archive/vol4-1/ijsecs.4.1.2018.1.0036.pdf) | _IJSECS_     | 2018     | no              |
| 45 | [A neural framework for retrieval and summarization of source code](https://dl.acm.org/doi/10.1145/3238147.3240471) | _ASE_     | 2018     | no              |
| 46 | [CoaCor: Code Annotation for Code Retrieval with Reinforcement Learning](http://arxiv.org/abs/1904.00720) | _arXiv_ | 2018 | [yes](https://github.com/LittleYUYU/CoaCor.) |
| 47 | [Deep code search](https://dl.acm.org/doi/10.1145/3180155.3180167) | _ICSE_     | 2018     | [yes](https://github.com/guxd/deep-code-search) |
| 48 | [Query expansion based on statistical learning from code changes](http://ieeexplore.ieee.org/document/7372014/) | _SPE_ | 2018 | no |
| 49 | [IECS: Intent-Enforced Code Search via Extended Boolean Model](https://www.medra.org/servlet/aliasResolver?alias=iospress&doi=10.3233/JIFS-161994) | _IFS_ | 2017 | no |
| 50 | [Learning to rank code examples for code search engines](http://link.springer.com/10.1007/s10664-015-9421-5) | _ESE_ | 2017 | no |
| 51 | [Query Expansion Based on Crowd Knowledge for Code Search](http://ieeexplore.ieee.org/document/7462267/) | _TSC_ | 2016 | no |
| 52 | [CodeHow: Effective Code Search Based on API Understanding and Extended Boolean Model](http://ieeexplore.ieee.org/document/7372014/) | _ASE_ | 2015 | no |

[//]: # (| 13 | [Self-Supervised Contrastive Learning for Code Retrieval and Summarization via Semantic-Preserving Transformations]&#40;http://arxiv.org/abs/2009.02731&#41; | _SIGIR_ | 2021 | no |)
[//]: # ([//]| 5 | [Code recommendation for android development: how does it work and what can be improved?]&#40;http://link.springer.com/10.1007/s11432-017-9058-0&#41; | _SCI_ | 2017 | no |)
[//]: # (: # &#40;| 1 | [A Compare-Aggregate Model for Matching Text Sequences]&#40;http://arxiv.org/abs/1611.01747&#41; | _arXiv_ | 2016 | [yes]&#40;https://github.com/shuohangwang/SeqMatchSeq&#41; |&#41;)
