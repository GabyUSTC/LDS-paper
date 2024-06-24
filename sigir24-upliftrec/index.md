---
title: 'Treatment Effect Estimation for User Interest Exploration on Recommender Systems'

#所有作者的列表，假设作者San Zhang是我们组的则是sanzhang，如果不是则填San Zhang
authors:
  - jiajuchen
  - Wenjie Wang
  - chongminggao
  - Peng Wu
  - Jianxiong Wei
  - Qingsong Hua
# 论文接受/发表日期
date: '2024-04-06T00:00:00Z'
publishDate: '2024-04-06T00:00:00Z'

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
publication: In *SIGIR 2024* 
publication_short: In *SIGIR'24* 

# 论文摘要
abstract: "Recommender systems learn personalized user preferences from user feedback like clicks. However, user feedback is usually biased towards partially observed interests, leaving many users’ hidden interests unexplored. Existing approaches typically mitigate the bias, increase recommendation diversity, or use bandit algorithms to balance exploration-exploitation trade-offs. Nevertheless, they fail to consider the potential rewards of recommending different categories of items and lack the global scheduling of allocating top-𝑁 recommendations to categories, leading to suboptimal exploration. In this work, we propose an Uplift model-based Recommender (UpliftRec) framework, which regards top-𝑁 recommendation as a treatment optimization problem. UpliftRec estimates the treatment effects, i.e., the click-through rate (CTR) under different category exposure ratios, by using observational user feedback. UpliftRec calculates group-level treatment effects to discover users’ hidden interests with high CTR rewards and leverages inverse propensity weighting to alleviate confounder bias. Thereafter, UpliftRec adopts a dynamic programming method to calculate the optimal treatment for overall CTR maximization. We implement UpliftRec on different backend models and conduct extensive experiments on three datasets. The empirical results validate the effectiveness of UpliftRec in discovering users’ hidden interests while achieving superior recommendation accuracy."

featured: true

links:
  # - name: Custom Link
  #   url: http://example.org
# pdf链接
url_pdf: 'https://arxiv.org/abs/2405.08582' 
# 代码链接
url_code: 'https://github.com/Jiaju-Chen/UpliftRec'

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
@inproceedings{chen2024treatment,
  title = {Treatment Effect Estimation for User Interest Exploration on Recommender Systems},
  author = {Chen, Jiaju and Wang, Wenjie and Gao, Chongming and Wu, Peng and Wei, Jianxiong and Hua, Qingsong},
  booktitle = {Proceedings of the 47th International ACM SIGIR Conference on Research and Development in Information Retrieval},
  series = {SIGIR '24},
  location = {Washington D.C., USA.},
  doi={10.1145/3626772.3657736},
  numpages = {11},
  year = {2024}
}
```

<!-- url = {https://dl.acm.org/doi/10.1145/3626772.3657736},
doi = {}, -->

