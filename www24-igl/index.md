---
title: 'Invariant Graph Learning for Causal Effect Estimation'

#所有作者的列表，假设作者San Zhang是我们组的则是sanzhang，如果不是则填San Zhang
authors:
  - yongduosui
  - Caizhi Tang
  - Zhixuan Chu
  - junfengfang
  - yuangao 
  - Qing Cui 
  - Longfei Li 
  - Jun Zhou
  - xiangwang
# 论文接受/发表日期
date: '2024-02-01T00:00:00Z'
publishDate: '2023-04-06T00:00:00Z'

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
publication: In *WWW 2024*
publication_short: In *WWW'24*

# 论文摘要
abstract: "Causal effect estimation from networked observational data encounters notable challenges, primarily hidden confounders arising from network structure, or spillover effects that influence unit's outcomes based on neighboring treatment assignments. Existing graph neural network (GNN)-based methods have endeavored to address these challenges, utilizing the GNN's message-passing mechanism to capture hidden confounders or model spillover effects. 
However, they mainly focus on transductive causal effect learning on a single networked data, limiting their efficacy in inductive settings for real-world applications where networked data often originates from multiple environments influenced by potentially varying time or geographical regions.In light of this, we introduce the principle of invariance to the task of causal effect estimation on networked data, culminating in our Invariant Graph Learning (IGL) framework. Specifically, it first generates multiple networked data to simulate diverse environments from a given observational data. Then it further encourages the model to learn environment-invariant representations for confounders and spillover effects.
Such a design enables the model to extrapolate beyond a single observed environment, thereby improving the performance of causal effect estimation in potential new environments. 
Extensive experiments on two real-world datasets demonstrates the superiority of our approach."

featured: true

links:
  # - name: Custom Link
  #   url: http://example.org
# pdf链接
url_pdf: 
# 代码链接
url_code: ''

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

```

