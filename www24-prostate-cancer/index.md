---
title: 'Improving Prostate Cancer Risk Prediction through Partial AUC Optimization'

#所有作者的列表，假设作者San Zhang是我们组的则是sanzhang，如果不是则填San Zhang
authors:
  - xinyuanzhu
  - xiaohanren
  - wentaoshi
  - Changming Wang
  - Xuehan Liu
  - Yuqing Liu
  - Tao Tao
  - fulifeng

# 论文接受/发表日期
date: '2024-03-05T00:00:00Z'
publishDate: '2024-03-05T00:00:00Z'

# 如果有共一则接触下面两行的注释
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

# doi号
doi: '10.1145/3589335.3651458'


# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# 发表在哪个会议/期刊上
publication: Companion Proceedings of the ACM Web Conference 2024
publication_short: WWW ’24

# 论文摘要
abstract: "Prostate cancer risk prediction (PCRP) is crucial in guiding clinical decision-making and ensuring accurate diagnoses. The area under the receiver operating characteristic curve (AUC) is typically used for the evaluation of PCRP models. However, AUC considers regions with high false positive rates (FPRs), which are not applicable in clinical practice. To address this concern, we propose to use partial AUC (pAUC) as a more clinically meaningful metric which evaluates PCRP models with restricted FPR. Moreover, we propose a new PCRP framework named pAUCP, which optimizes pAUC to train PCRP models and adopts model ensemble to further enhance its usability. We construct clinical datasets obtained from two medical centers over an extended period to evaluate the proposed pAUCP framework. Extensive experiments demonstrate the rationality and superiority of the pAUCP framework, especially the cross-time and cross-center transferability of the obtained PCRP model."

featured: true

links:
  # - name: Custom Link
  #   url: http://example.org
# pdf链接
url_pdf: ''
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
@inproceedings{zhu2024improving,
  title = {Improving Prostate Cancer Risk Prediction through Partial AUC Optimization},
  author = {Zhu, Xinyuan and Ren, Xiaohan and Shi, Wentao and Wang, Changming and Liu, Xuehan and Liu, Yuqing and Tao, Tao and Feng, Fuli},
  booktitle = {Companion Proceedings of the ACM Web Conference 2024},
  series = {WWW ’24 Companion},
  location = {Singapore, Singapore.},
  url = {https://doi.org/10.1145/3589335.3651458},
  doi = {0.1145/3589335.3651458},
  numpages = {4},
  year = {2024}
}
```

