---
title: 'Text-to-Image Generation for Abstract Concepts'

#所有作者的列表，假设作者San Zhang是我们组的则是sanzhang，如果不是则填San Zhang
authors:
  - jiayiliao
  - Xu Chen
  - Qiang Fu
  - Lun Du
  - xiangnanhe
  - xiangwang
  - Shi Han
  - Dongmei Zhang
# 论文接受/发表日期
date: '2023-12-09T00:00:00Z'
publishDate: '2023-12-09T00:00:00Z'

# 如果有共一则接触下面两行的注释
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

# doi号
doi: 'https://doi.org/10.1609/aaai.v38i4.28122'


# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# 发表在哪个会议/期刊上
publication: In *AAAI 2024*
publication_short: In *AAAI'24*

# 论文摘要
abstract: "Recent years have witnessed the substantial progress of large-scale models across various domains, such as natural language processing and computer vision, facilitating the expression of concrete concepts. Unlike concrete concepts that are usually directly associated with physical objects, expressing abstract concepts through natural language requires considerable effort since they are characterized by intricate semantics and connotations. An alternative approach is to leverage images to convey rich visual information as a supplement. Nevertheless, existing Text-to-Image (T2I) models are primarily trained on concrete physical objects and often struggle to visualize abstract concepts. Inspired by the three-layer artwork theory that identifies critical factors, intent, object and form during artistic creation, we propose a framework of Text-to-Image generation for Abstract Concepts (TIAC). The abstract concept is clarified into a clear intent with a detailed definition to avoid ambiguity. LLMs then transform it into semantic-related physical objects, and the concept-dependent form is retrieved from an LLM-extracted form pattern set. Information from these three aspects will be integrated to generate prompts for T2I models via LLM. Evaluation results from human assessments and our newly designed metric concept score demonstrate the effectiveness of our framework in creating images that can sufficiently express abstract concepts."

featured: true

links:
  # - name: Custom Link
  #   url: http://example.org
# pdf链接
url_pdf: https://arxiv.org/pdf/2309.14623v2.pdf
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
@inproceedings{liao2024tiac,
  author       = {Jiayi Liao and
                  Xu Chen and
                  Qiang Fu and
                  Lun Du and
                  Xiangnan He and
                  Xiang Wang and
                  Shi Han and
                  Dongmei Zhang},
  title        = {Text-to-Image Generation for Abstract Concepts},
  booktitle    = {{AAAI}},
  pages        = {3360--3368},
  publisher    = {{AAAI} Press},
  year         = {2024}
}
```

