---
title: '3D-MoLM: Towards 3D Molecule-Text Interpretation in Language Models'

#所有作者的列表，假设作者San Zhang是我们组的则是sanzhang，如果不是则填San Zhang
authors:
  - sihangli
  - Liu Zhiyuan
  - yanchenluo
  - xiangwang
  - xiangnanhe
  - Kenji Kawaguchi
  - Tat-Seng Chua
  - Qi Tian
# 论文接受/发表日期
date: '2024-01-16T00:00:00Z'
publishDate: '2024-01-16T00:00:00Z'

# 如果有共一则接触下面两行的注释
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

# doi号
doi: ''


# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# 发表在哪个会议/期刊上
publication: In *ICLR 2024* 
publication_short: In *ICLR'24*

# 论文摘要
abstract: "Language Models (LMs) have greatly influenced diverse domains. However, their inherent limitation in comprehending 3D molecular structures has considerably constrained their potential in the biomolecular domain. To bridge this gap, we focus on 3D molecule-text interpretation, and propose 3D-MoLM: 3D-Molecular Language Modeling. Specifically, 3D-MoLM enables an LM to interpret and analyze 3D molecules by equipping the LM with a 3D molecular encoder. This integration is achieved by a 3D molecule-text projector, bridging the 3D molecular encoder's representation space and the LM's input space. Moreover, to enhance 3D-MoLM's ability of cross-modal molecular understanding and instruction following, we meticulously curated a 3D molecule-centric instruction tuning dataset -- 3D-MoIT. Through 3D molecule-text alignment and 3D molecule-centric instruction tuning, 3D-MoLM establishes an integration of 3D molecular encoder and LM. It significantly surpasses existing baselines on downstream tasks, including molecule-text retrieval, molecule captioning, and more challenging open-text molecular QA tasks, especially focusing on 3D-dependent properties."

featured: true

links:
  # - name: Website
  #   url: https://lsh0520.github.io/3D-MoLM/
# pdf链接
url_pdf: https://arxiv.org/abs/2401.13923.pdf
# 代码链接
url_code: 'https://github.com/lsh0520/3D-MoLM'

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
@inproceedings{li2024molm,
    title={3D-MoLM: Towards 3D Molecule-Text Interpretation in Language Models},
    author={Li, Sihang and Liu, Zhiyuan and Luo, Yanchen and Wang, Xiang and He, Xiangnan and Kawaguchi, Kenji  and Chua, Tat-Seng and Tian, Qi},
    booktitle={ICLR},
    year={2024},
    url={https://openreview.net/forum?id=xI4yNlkaqh}
}
```
