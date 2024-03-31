---
title: 'EXGC: Bridging Efficiency and Explainability in Graph Condensation'
authors:
  - junfengfang
  - Xinlin Li
  - yongduosui
  - yuangao
  - Guibin Zhang
  - Kun Wang
  - xiangwang
  - xiangnanhe

date: '2024-02-02T00:00:00Z'
author_notes:
   - 'Equal contribution'
   - 'Equal contribution'

doi: '10.1145/3589334.3645551'
publishDate: '2024-02-02T00:00:00Z'
publication_types: ['1']
publication: In WWW 2024 
publication_short: In WWW 2024 

abstract: "Graph representation learning on vast datasets, like web data, has made significant strides. However, the associated computational and storage overheads raise concerns. In sight of this, Graph condensation (GCond) has been introduced to distill these large real datasets into a more concise yet information-rich synthetic graph. Despite acceleration efforts, existing GCond methods mainly grapple with efficiency, especially on expansive web data graphs.
Hence, in this work, we pinpoint two major inefficiencies of current paradigms: (1) the concurrent updating of a vast parameter set, and (2) pronounced parameter redundancy. To counteract these two limitations correspondingly, we first (1) employ the Mean-Field variational approximation for convergence acceleration, and then (2) propose the objective of Gradient Information Bottleneck (GDIB) to prune redundancy. By incorporating the leading explanation techniques (e.g., GNNExplainer and GSAT) to instantiate the GDIB, our EXGC, the Efficient and eXplainable Graph Condensation method is proposed, which can markedly boost efficiency and inject explainability. Our extensive evaluations across eight datasets underscore EXGC's superiority and relevance. Code is available at https://github.com/MangoKiller/EXGC.
"
featured: true

links:

url_pdf: https://hexiangnan.github.io./papers/www24-EXGC.pdf
url_code: 'https://github.com/MangoKiller/EXGC'
projects:
  - internal-project
slides:
---



Citation:
```
@article{DBLP:journals/corr/abs-2402-05962,
  author       = {Junfeng Fang and
                  Xinglin Li and
                  Yongduo Sui and
                  Yuan Gao and
                  Guibin Zhang and
                  Kun Wang and
                  Xiang Wang and
                  Xiangnan He},
  title        = {{EXGC:} Bridging Efficiency and Explainability in Graph Condensation},
  journal      = {CoRR},
  volume       = {abs/2402.05962},
  year         = {2024}
}
```