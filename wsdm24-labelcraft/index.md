---
title: 'LabelCraft: Empowering Short Video Recommendations with Automated Label Crafting'

#所有作者的列表，假设作者San Zhang是我们组的则是sanzhang，如果不是则填San Zhang
authors:
  - yimengbai
  - Yang Zhang
  - Jing Lu
  - Jianxin Chang
  - Xiaoxue Zang
  - Yanan Niu
  - Yang Song
  - fulifeng

# 论文接受/发表日期
date: '2023-10-20T00:00:00Z'
publishDate: '2024-03-04T00:00:00Z'

# 如果有共一则接触下面两行的注释
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

# doi号
doi: '10.1145/3616855.3635816'


# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# 发表在哪个会议/期刊上
publication: In *WSDM 2024* <font color='red'>
publication_short: In *WSDM'24*

# 论文摘要
abstract: "Short video recommendations often face limitations due to the quality of user feedback, which may not accurately depict user interests. To tackle this challenge, a new task has emerged: generating more dependable labels from original feedback. Existing label generation methods rely on manual rules, demanding substantial human effort and potentially misaligning with the desired objectives of the platform. To transcend these constraints, we introduce LabelCraft, a novel automated label generation method explicitly optimizing pivotal operational metrics for platform success. By formulating label generation as a higher-level optimization problem above recommender model optimization, LabelCraft introduces a trainable labeling model for automatic label mechanism modeling. Through meta-learning techniques, LabelCraft effectively addresses the bi-level optimization hurdle posed by the recommender and labeling models, enabling the automatic acquisition of intricate label generation mechanisms. Extensive experiments on real-world datasets corroborate LabelCraft's excellence across varied operational metrics, encompassing usage time, user engagement, and retention. Codes are available at https://github.com/baiyimeng/LabelCraft."

featured: true

links:
  # - name: Custom Link
  #   url: http://example.org
# pdf链接
url_pdf: https://arxiv.org/pdf/2312.10947.pdf
# 代码链接
url_code: https://github.com/baiyimeng/LabelCraft

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
@inproceedings{10.1145/3616855.3635816,
author = {Bai, Yimeng and Zhang, Yang and Lu, Jing and Chang, Jianxin and Zang, Xiaoxue and Niu, Yanan and Song, Yang and Feng, Fuli},
title = {LabelCraft: Empowering Short Video Recommendations with Automated Label Crafting},
year = {2024},
isbn = {9798400703713},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
url = {https://doi.org/10.1145/3616855.3635816},
doi = {10.1145/3616855.3635816},
pages = {28–37},
numpages = {10},
keywords = {label generation, short video recommendation},
location = {<conf-loc>, <city>Merida</city>, <country>Mexico</country>, </conf-loc>},
series = {WSDM '24}
}
```

