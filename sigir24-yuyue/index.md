---
title: 'Let Me Do It For You: Towards LLM Empowered Recommendation via Tool Learning'

#所有作者的列表，假设作者San Zhang是我们组的则是sanzhang，如果不是则填San Zhang
authors:
  - yuyuezhao
  - jiancanwu
  - xiangwang
  - Wei Tang
  - Dingxian Wang
  - Maarten de Rijke
# 论文接受/发表日期
date: '2024-03-25T00:00:00Z'
publishDate: '2024-03-25T00:00:00Z'

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
publication_short: In *SIGIR 2024*

# 论文摘要
abstract: "Conventional recommender systems (RSs) face challenges in precisely capturing users' fine-grained preferences. Large language models (LLMs) have shown capabilities in commonsense reasoning and leveraging external tools that may help address these challenges. However, existing LLM-based RSs suffer from hallucinations, misalignment between the semantic space of items and the behavior space of users, or overly simplistic control strategies (e.g., whether to rank or directly present existing results). To bridge these gap, we introduce ToolRec, a framework for LLM-empowered recommendations via tool learning that uses LLMs as surrogate users, thereby guiding the recommendation process and invoking external tools to generate a recommendation list that aligns closely with users' nuanced preferences. // We formulate the recommendation process as a process aimed at exploring user interests in attribute granularity. The process factors in the nuances of the context and user preferences. The LLM then invokes external tools based on a user's attribute instructions and probes different segments of the item pool. We consider two types of attribute-oriented tools: ranking tools and retrieval tools. Through the integration of LLMs, ToolRec enables conventional recommender systems to become external tools with a natural language interface. Extensive experiments verify the effectiveness of ToolRec, particularly in scenarios that are rich in semantic content."

featured: true

links:
  # - name: Custom Link
  #   url: http://example.org
# pdf链接
url_pdf: xxx
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
@inproceedings{toolrec,
title={Let Me Do It For You: Towards LLM Empowered Recommendation via Tool Learning},
author={Yuyue Zhao and Jiancan Wu and Xiang Wang and Wei Tang and Dingxian Wang and Maarten de Rijke},
booktitle={SIGIR},
year={2024},
}
```

