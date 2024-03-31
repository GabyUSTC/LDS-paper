---
title: 'Large Language-Recommendation Assistant'

#所有作者的列表，假设作者San Zhang是我们组的则是sanzhang，如果不是则填San Zhang
authors:
  - jiayiliao
  - sihangli
  - zhengyiyang
  - jiancanwu
  - Yancheng Yuan
  - xiangwang
  - xiangnanhe
# 论文接受/发表日期
date: '2024-03-25T00:00:00Z'
publishDate: '2024-03-25T00:00:00Z'
# publishDate: '2024-03-25T00:00:00Z'

# 如果有共一则接触下面两行的注释
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

# doi号
# doi: ''


# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# 发表在哪个会议/期刊上
publication: In *SIGIR 2024*
publication_short: In *SIGIR'24*

# 论文摘要
abstract: "Sequential recommendation aims to predict users’ next interaction with items based on their past engagement sequence. Recently, the advent of Large Language Models (LLMs) has sparked interest in leveraging them for sequential recommendation, viewing it as language modeling. Previous studies represent items within LLMs’ input prompts as either ID indices or textual metadata. However, these approaches often fail to either encapsulate comprehensive world knowledge or exhibit sufficient behavioral understanding. To combine the complementary strengths of conventional recommenders in capturing behavioral patterns of users and LLMs in encoding world knowledge about items, we introduce Large Language-Recommendation Assistant (LLaRA). Specifically, it uses a novel hybrid prompting method that integrates ID-based item embeddings learned by traditional recommendation models with textual item features. Treating the “sequential behaviors of users” as a distinct modality beyond texts, we employ a projector to align the traditional recommender’s ID embeddings with the LLM’s input space. Moreover, rather than directly exposing the hybrid prompt to LLMs, a curriculum learning strategy is adopted to gradually ramp up training complexity. Initially, we warm up the LLM using text-only prompts, which better suit its inherent language modeling ability. Subsequently, we progressively transition to the hybrid prompts, training the model to seamlessly incorporate the behavioral knowledge from the traditional sequential recommender into the LLM. Empirical results validate the effectiveness of our proposed framework. Codes are available at https://github.com/ljy0ustc/LLaRA."

featured: true

links:
  # - name: Custom Link
  #   url: http://example.org
# pdf链接
# url_pdf: https://arxiv.org/pdf/2307.04571.pdf
# 代码链接
# url_code: 'https://github.com/chongminggao/DORL-codes'

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
@inproceedings{llara,
title={Large Language-Recommendation Assistant},
author={Jiayi Liao and Sihang Li and Zhengyi Yang and Jiancan Wu and Yancheng Yuan and Xiang Wang and Xiangnan He},
booktitle={SIGIR},
year={2024},
}
```

