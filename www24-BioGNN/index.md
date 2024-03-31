---
title: 'Graph Anomaly Detection with Bi-level Optimization'

#所有作者的列表，假设作者San Zhang是我们组的则是sanzhang，如果不是则填San Zhang
authors:
  - Yuan Gao
  - Junfeng Fang
  - Yongduo Sui
  - liyangyang
  - Xiang Wang
  - fenghuamin
  - zhangyongdong

# 论文接受/发表日期
date: '2024-01-23T14:45:06Z'
publishDate: '2024-01-23T14:45:06Z'

# 如果有共一则接触下面两行的注释
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

# doi号
doi: '10.1145/3589334.3645673'


# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# 发表在哪个会议/期刊上
publication: In *WWW 2024*
publication_short: In *WWW 2024*

# 论文摘要
abstract: "Graph anomaly detection (GAD) has various applications in finance, healthcare, and security. Graph Neural Networks (GNNs) are now the primary method for GAD, treating it as a task of semisupervised node classification (normal vs. anomalous). However, most traditional GNNs aggregate and average embeddings from all neighbors, without considering their labels, which can hinder detecting actual anomalies. To address this issue, previous methods try to selectively aggregate neighbors. However, the same selection strategy is applied regardless of normal and anomalous classes, which does not fully solve this issue. This study discovers that nodes with different classes yet similar neighbor label distributions (NLD) tend to have opposing loss curves, which we term it as “loss rivalry”. By introducing Contextual Stochastic Block Model (CSBM) and defining NLD distance, we explain this phenomenon theoretically
and propose a Bi-level optimization Graph Neural Network (BioGNN), based on these observations. In a nutshell, the lower
level of BioGNN segregates nodes based on their classes and NLD,
while the upper level trains the anomaly detector using separation outcomes. Our experiments demonstrate that BioGNN outperforms state-of-the-art methods and effectively mitigates “loss rivalry”. Codes are available at https://github.com/blacksingular/Bio-GNN."

featured: true

links:
  # - name: Custom Link
  #   url: http://example.org
# pdf链接
url_pdf: '#'
# 代码链接
url_code: '#'

# 以下视情况填写
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: '#'
# url_video: '#'

# 如果需要放图，请放在同一个目录下，名字叫`featured.jpg/png` 
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ''
#   preview_only: false

projects:
  - internal-project

---

Citation:
```
@inproceedings{gao2024graph,
  title = {Graph Anomaly Detection with Bi-level Optimization},
  author = {Gao, Yuan and Fang, Junfeng and Sui, Yongduo and Li, Yangyang and Wang, Xiang and Feng, Huamin and Zhang, Yongdong},
  booktitle = {Proceedings of the ACM Web Conference 2024 (WWW '24)},
  year = {2024}
}
```

