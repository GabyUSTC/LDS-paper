---
title: 'Revisiting Attack-caused Structural Distribution Shift in Graph Anomaly Detection'

#所有作者的列表，假设作者San Zhang是我们组的则是sanzhang，如果不是则填San Zhang
authors:
  - Yuan Gao
  - Jinghan Li
  - Xiang Wang
  - Xiangnan He
  - fenghuamin
  - zhangyongdong

# 论文接受/发表日期
date: '2024-03-19T20:59:56Z'
publishDate: '2024-03-19T20:59:56Z'

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
publication_types: ['2']

# 发表在哪个会议/期刊上
publication: In *TKDE*
publication_short: In *TKDE*

# 论文摘要
abstract: "Graph anomaly detection (GAD) under semi-supervised setting poses a significant challenge due to the distinct structural distribution between anomalous and normal nodes. Specifically, anomalous nodes constitute a minority and exhibit high heterophily and low homophily compared to normal nodes, which makes the distribution of neighbors of the two types of nodes close, that is, most of them are composed of normal nodes, which causes the two types of nodes to be difficult to distinguish during the aggregation process. Furthermore, we discover that apart from various time factors and annotation preferences, graph adversarial attacks can lead to and amplify the heterophily difference across training and testing data, which is called structural distribution shift (SDS) in this paper. Current mainstream methods for GAD tend to overlook the SDS problem, resulting in poor generalization performance and limited effectiveness in detecting anomalies.
This work solves the problem from a feature view. We observe that the degree of SDS varies between anomalies and normal nodes.
Hence to address the issue, the key lies in resisting high heterophily for anomalies meanwhile benefiting the learning of normals from homophily. Since different labels correspond to the difference of critical anomaly features which make great contributions to the GAD, we tease out the anomaly features on which we constrain to mitigate the effect of heterophilous neighbors and make them invariant. However, the prior distribution of anomaly features is dynamic and hard to estimate, we thus devise a prototype vector to infer and
update this distribution during training. For normal nodes, we constrain the remaining features to preserve the connectivity of nodes and reinforce the influence of the homophilous neighborhood. We term our proposed framework as Graph Decomposition Network (GDN). To demonstrate the effectiveness of the network, we explain the process of feature decomposition in the spectral domain. Extensive experiments are conducted on four benchmark datasets, including two additional datasets and two used in the preliminary work. To further validate our performance under SDS, we conduct an adversarial attack to incur different heterophily degrees for the training set and the test set. The proposed framework achieves remarkable accuracy and robustness boost in GAD, especially in an SDS environment where anomalies have largely different structural distribution across training and testing environments. Our code is open-sourced in https://github.com/fortunato-all/skl-GDN."

featured: true

links:
  # - name: Custom Link
  #   url: http://example.org
# pdf链接
url_pdf: '#'
# 代码链接
url_code: 'https://github.com/fortunato-all/skl-GDN'

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
@inproceedings{gao2024revisiting,
  title = {Revisiting Attack-caused Structural Distribution Shift in Graph Anomaly Detection},
  author = {Gao, Yuan and Li, Jinghan and Wang, Xiang and He, Xiangnan and Feng, Huamin and Zhang, Yongdong},
  booktitle = {In Transactions on Knowledge and Data Engineering},
  year = {2024}
}
```

