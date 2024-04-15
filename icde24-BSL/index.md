---
title: 'BSL: Understanding and Improving Softmax Loss for Recommendation'

#所有作者的列表，假设作者San Zhang是我们组的则是sanzhang，如果不是则填San Zhang
authors:
  - junkangwu
  - Jiawei Chen
  - jiancanwu
  - wentaoshi
  - jizhizhang
  - xiangwang
# 论文接受/发表日期
date: '2023-12-01T00:00:00Z'
publishDate: '2023-12-09T00:00:00Z'

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
abstract: "Loss functions steer the optimization direction of recommendation models and are critical to model performance, but have received relatively little attention in recent recommendation research. Among various losses, we find Softmax loss (SL) stands out for not only achieving remarkable accuracy but also better robustness and fairness. Nevertheless, the current literature lacks a comprehensive explanation for the efficacy of SL. 
Toward addressing this research gap, we conduct theoretical analyses on SL and uncover three insights: 1) Optimizing SL is equivalent to performing Distributionally Robust Optimization (DRO) on the negative data, thereby learning against perturbations on the negative distribution and yielding robustness to noisy negatives. 2) Comparing with other loss functions, SL implicitly penalizes the prediction variance, resulting in a smaller gap between predicted values and and thus producing fairer results. Building on these insights, we further propose a novel loss function Bilateral SoftMax Loss (BSL) that extends the advantage of SL to both positive and negative sides. BSL augments SL by applying the same Log-Expectation-Exp structure to positive examples as is used for negatives, making the model robust to the noisy positives as well. Remarkably, BSL is simple and easy-to-implement — requiring just one additional line of code compared to SL. Experiments on four realworld datasets and three representative backbones demonstrate the effectiveness of our proposal. The code is available at https://github.com/junkangwu/BSL. "

featured: true

links:
  # - name: Custom Link
  #   url: http://example.org
# pdf链接
url_pdf: "https://arxiv.org/pdf/2312.12882.pdf"
# 代码链接
url_code: 'https://github.com/junkangwu/BSL'

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
@inproceedings{GCMAE,
  title = {BSL: Understanding and Improving Softmax Loss for Recommendation},
  author = {Junkang Wu and Jiawei Chen and Jiancan Wu and Wentao Shi and Jizhi Zhang and Xiang Wang},
  booktitle = {ICDE},
  year = {2024}
}
```

