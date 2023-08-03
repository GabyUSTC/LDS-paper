---
title: 'Adap-τ: Adaptively Modulating Embedding Magnitude for Recommendation'
authors:
  - jiaweichen
  - junkangwu
  - jiancanwu
  - xuezhicao
  - shengzhou
  - xiangnanhe

date: '2023-01-26T00:00:00Z'
doi: ''
publishDate: '2023-01-26T00:00:00Z'
publication_types: ['1']
publication: In WWW 2023 
publication_short: In WWW 2023 

abstract: "Recent years have witnessed the great successes of embedding-based methods in recommender systems. Despite their decent performance, we argue one potential limitation of these methods --- the embedding magnitude has not been explicitly modulated, which may aggravate popularity bias and training instability, hindering the model from making a good recommendation. It motivates us to leverage the embedding normalization in recommendation. By normalizing user/item embeddings to a specific value, we empirically observe impressive performance gains (9\% on average) on four real-world datasets. Although encouraging, we also reveal a serious limitation when applying normalization in recommendation --- the performance is highly sensitive to the choice of the temperature $\tau$ which controls the scale of the normalized embeddings.
To fully foster the merits of the normalization while circumvent its limitation, this work studied on how to adaptively set the proper $\tau$. Towards this end, we first make a comprehensive analyses of $\tau$ to fully understand its role on recommendation. We then accordingly develop an adaptive fine-grained strategy Adap-$\tau$ for the temperature with satisfying four desirable properties including adaptivity, personalized, efficiency and model-agnostic. Extensive experiments have been conducted to validate the effectiveness of the proposal. The code is available at \url{https://github.com/junkangwu/Adap_tau}."
featured: true

links:

url_pdf: https://hexiangnan.github.io./papers/www23-adap.pdf
url_code: 'https://github.com/junkangwu/Adap_tau'
projects:
  - internal-project
slides:
---



Citation:
```
@inproceedings{chen2023adap,
  title={Adap-$\tau$: Adaptively Modulating Embedding Magnitude for Recommendation},
  author={Chen, Jiawei and Wu, Junkang and Wu, Jiancan and Cao, Xuezhi and Zhou, Sheng and He, Xiangnan},
  booktitle={Proceedings of the ACM Web Conference 2023},
  pages={1085--1096},
  year={2023}
}
```