---
title: 'Masked Graph Modeling with Multi-View Contrast'

#所有作者的列表，假设作者San Zhang是我们组的则是sanzhang，如果不是则填San Zhang
authors:
  - yanchenluo
  - sihangli
  - yongduosui
  - junkangwu
  - jiancanwu
  - xiangwang
# 论文接受/发表日期
date: '2023-12-01T00:00:00Z'
publishDate: '2024-05-14T00:00:00Z'

# 如果有共一则接触下面两行的注释
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

# doi号
doi: ''


# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# 发表在哪个会议/期刊上
publication: In *ICDE 2024*
publication_short: In *ICDE'24*

# 论文摘要
abstract: "Masked modeling has recently achieved remarkable success in specific fields of vision and language, sparking a surge of interest in graph-related research.
However, Masked Graph Modeling (MGM), which captures fine-grained local information by masking low-level elements such as nodes, edges, and features, limits itself to a sub-optimal position, particularly on tasks requiring high-quality graph-level representations.
Such a local perspective disregards the graph's global information and structure.
To address these limitations, we propose a novel graph pre-training framework called \underline{G}raph \underline{C}ontrastive \underline{M}asked \underline{A}utoencoder (GCMAE).
GCMAE leverages the strengths of both MGM and Graph Contrastive Learning (GCL) to provide a more comprehensive perspective of both local and global.
Our framework uses instance discrimination to learn global representations of graphs and reconstructs the graph using masked low-level elements.
We augment the framework with a novel multi-view augmentation module to further enhance the pre-trained model's robustness and generalization ability.
We evaluate GCMAE on real-world biochemistry and social network datasets, conducting extensive experiments on both node and graph classification tasks and transfer learning on downstream graph classification tasks.
Our experimental results demonstrate that GCMAE's comprehensive perspective of both local and global benefits model pre-training.
Moreover, GCMAE outperforms existing MGM and GCL baselines, proving its effectiveness on downstream tasks."

featured: true

# links:
  # - name: Custom Link
  #   url: http://example.org
# pdf链接
# url_pdf: 
# 代码链接
url_code: 'https://github.com/lyc0930/GCMAE'

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

# projects:
#   - internal-project

---

Citation:
```
@inproceedings{GCMAE,
  title = {Masked Graph Modeling with Multi-View Contrast},
  author = {Yanchen Luo and Sihang Li and Yongduo Sui and Junkang Wu and Jiancan Wu and Xiang Wang},
  booktitle = {ICDE},
  year = {2024}
}
```

