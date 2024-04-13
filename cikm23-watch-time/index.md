---
title: 'Leveraging Watch-time Feedback for Short-Video Recommendations: A Causal Labeling Framework'

#所有作者的列表，假设作者San Zhang是我们组的则是sanzhang，如果不是则填San Zhang
authors:
  - Yang Zhang
  - yimengbai
  - Jianxin Chang
  - Xiaoxue Zang
  - Song Lu
  - Jing Lu
  - fulifeng
  - Yanan Niu
  - Yang Song


# 论文接受/发表日期
date: '2023-08-05T00:00:00Z'
publishDate: '2023-10-21T00:00:00Z'

# 如果有共一则接触下面两行的注释
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'
  - 'Equal contribution'

# doi号
doi: '10.1145/3583780.3615483'


# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# 发表在哪个会议/期刊上
publication: In *CIKM 2023* <font color='red'>
publication_short: In *CIKM'23*

# 论文摘要
abstract: "With the proliferation of short video applications, the significance of short video recommendations has vastly increased. Unlike other recommendation scenarios, short video recommendation systems heavily rely on feedback from watch time. Existing approaches simply treat watch time as a direct label, failing to effectively harness its extensive semantics and introduce bias, thereby limiting the potential for modeling user interests based on watch time. To overcome this challenge, we propose a framework named Debiased Multiple-semantics-extracting Labeling (DML). DML constructs labels that encompass various semantics by utilizing quantiles derived from the distribution of watch time, prioritizing relative order rather than absolute label values. This approach facilitates easier model learning while aligning with the ranking objective of recommendations. Furthermore, we introduce a method inspired by causal adjustment to refine label definitions, thereby directly mitigating bias at the label level. We substantiate the effectiveness of our DML framework through both online and offline experiments. Extensive results demonstrate that our DML could effectively leverage watch time to discover users' real interests, enhancing their engagement in our application."
featured: true

links:
  # - name: Custom Link
  #   url: http://example.org
# pdf链接
url_pdf: https://arxiv.org/pdf/2306.17426.pdf
# 代码链接
# url_code: 

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
@inproceedings{10.1145/3583780.3615483,
author = {Zhang, Yang and Bai, Yimeng and Chang, Jianxin and Zang, Xiaoxue and Lu, Song and Lu, Jing and Feng, Fuli and Niu, Yanan and Song, Yang},
title = {Leveraging Watch-time Feedback for Short-Video Recommendations: A Causal Labeling Framework},
year = {2023},
isbn = {9798400701245},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
url = {https://doi.org/10.1145/3583780.3615483},
doi = {10.1145/3583780.3615483},
booktitle = {Proceedings of the 32nd ACM International Conference on Information and Knowledge Management},
pages = {4952–4959},
numpages = {8},
keywords = {recommender system, debiasing, causal recommendation},
location = {<conf-loc>, <city>Birmingham</city>, <country>United Kingdom</country>, </conf-loc>},
series = {CIKM '23}
}
```

