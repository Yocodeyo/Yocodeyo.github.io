---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I am currently visiting SALT Lab and Stanford NLP Group! I am pursuing my PhD in Computer Science at the National University of Singapore (NUS) WING lab with research interests in human-centered and socially aware Natural Language Processing. I am fortunately supervised by [**Prof Kan Min-Yen**](https://www.comp.nus.edu.sg/~kanmy/) from NUS, [**Dr Nancy F. Chen**](https://www.a-star.edu.sg/i2r/i2r-profiles/nancychen) from ASTAR, and [**Prof Shafiq Joty**](https://raihanjoty.github.io/) from Salesforce. I am also having great collaborations with SALT Lab under the advice of [**Prof Diyi Yang**](https://cs.stanford.edu/~diyiy/) from Stanford University. I graduated with a bachelor in NUS.

My research interests include **(1) Human-Centric and Data-Centric NLP**, **(2) NLP for Social Good** and **（3）Socially Aware NLP System**. I have published papers at the top tier NLP conferences like ACL and EMNLP.

I like playing piano🎹, table tennis🏓 and badminton🏸. I enjoy listening to music and watching talk shows because they deliver inspiration and positive energy through words and rhythms. I also like traveling and exploring the world/good food!😋


# 🔥 News
- *2024.11*: &nbsp;🎉🎉 Our paper (as first author) DnA-Eval: Enhancing Large Language Model Evaluation through Decomposition and Aggregation was accepted by *COLING 2025*.
- *2024.11*: &nbsp;🎉🎉 I received Google PhD Fellowship (NLP direction)!
- *2024.09*: &nbsp;🎉🎉 I started my visit at Stanford!
- *2024.05*: &nbsp;🎉🎉 Our paper (as first author) Social Intelligence Data Infrastructure: Structuring the Present and Navigating the Future was accepted by *ACL 2024 Findings*.
- *2024.01*: &nbsp;🎉🎉 I received Research Achievement Award awarded by School of Computing!
- *2023.12*: &nbsp;🎉🎉 I passed my PhD Qualification Exam!
- *2023.10*: &nbsp;🎉🎉 Our paper (as first author) CoAnnotating: Uncertainty-Guided Work Allocation between Human and Large Language Models for Data Annotation was accepted by *EMNLP 2023 Main Conference*.
- *2023.10*: &nbsp;🎉🎉 Our paper (as collaborator) Retrieving Multimodal Information for Augmented Generation: A Survey was accepted by *EMNLP 2023 Findings*.
- *2022.03*: &nbsp;🎉🎉 Our paper (as first co-author) Inducing Positive Perspectives with Text Reframing was accepted by *ACL 2022 Main Conference*. We also received **Outstanding Paper Award**!


# 📝 Publications 


## 🎙 First (Co-)Author
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2025</div><img src='images/09.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**(4)**  [DnA-Eval: Enhancing Large Language Model Evaluation through Decomposition and Aggregation](https://arxiv.org/abs/2405.15329)

**Minzhi Li**, Zhengyuan Liu, Shumin Deng, Shafiq Joty, Nancy F Chen, Min-Yen Kan

[<strong>*COLING 2025*</strong>](https://arxiv.org/abs/2405.15329) <strong><span class='show_paper_citations' data='1fXM4wUAAAAJ:UeHWp8X0CEIC'></span></strong>

- We propose Decompose and Aggregate, which breaks down the evaluation process into different stages based on pedagogical practices. Our experiments illustrate that it not only provides a more interpretable window for how well LLMs evaluate, but also leads to improvements up to 39.6% for different LLMs on a variety of meta-evaluation benchmarks.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2024</div><img src='images/08.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**(3)**  [Social Intelligence Data Infrastructure: Structuring the Present and Navigating the Future](https://arxiv.org/abs/2403.14659)

**Minzhi Li**, Weiyan Shi, Caleb Ziems, Diyi Yang

[<strong>*ACL 2024*</strong>](https://arxiv.org/abs/2403.14659) <strong><span class='show_paper_citations' data='1fXM4wUAAAAJ:UeHWp8X0CEIC'></span></strong>

- We build a Social AI Data Infrastructure, which consists of a comprehensive social AI taxonomy and a data library of 480 NLP datasets. Our infrastructure allows us to analyze existing dataset efforts, and also evaluate language models' performance in different social intelligence aspects. Our analyses demonstrate its utility in enabling a thorough understanding of current data landscape and providing a holistic perspective on potential directions for future dataset development.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2023</div><img src='images/07.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**(2)**  [CoAnnotating: Uncertainty-Guided Work Allocation between Human and Large Language Models for Data Annotation](https://arxiv.org/abs/2310.15638)

**Minzhi Li**, Taiwei Shi, Caleb Ziems, Min-Yen Kan, Nancy F. Chen, Zhengyuan Liu, Diyi Yang,*

[<strong>*EMNLP 2023*</strong>](https://arxiv.org/abs/2310.15638) <strong><span class='show_paper_citations' data='1fXM4wUAAAAJ:UeHWp8X0CEIC'></span></strong>

- This work propose CoAnnotating, a novel paradigm for Human-LLM co-annotation of unstructured texts at scale. Under this framework, we utilize uncertainty to estimate LLMs' annotation capability. Our empirical study shows CoAnnotating to be an effective means to allocate work from results on different datasets, with up to 21% performance improvement over random baseline.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2022</div><img src='images/06.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**(1)**  [Inducing Positive Perspectives with Text Reframing](https://arxiv.org/abs/2204.02952)

Caleb Ziems, **Minzhi Li** (equal contribution), Anthony Zhang, Diyi Yang

[<strong>*ACL 2022*</strong>](https://arxiv.org/abs/2204.02952) <strong><span class='show_paper_citations' data='1fXM4wUAAAAJ:UeHWp8X0CEIC'></span></strong>
- We introduce a large-scale benchmark, Positive Psychology Frames, with 8,349 sentence pairs and 12,755 structured annotations to explain positive reframing in terms of six theoretically-motivated reframing strategies. Then we evaluate a set of state-of-the-art text style transfer models, and conclude by discussing key challenges and directions for future work.
</div>
</div>




## 🎙 Co-author
- **(1)** Ruochen Zhao, Hailin Chen, Weishi Wang, Fangkai Jiao, Xuan Long Do, Chengwei Qin, Bosheng Ding, Xiaobao Guo, Minzhi Li, Xingxuan Li, Shafiq Joty, 2023. Retrieving Multimodal Information for Augmented Generation: A Survey. EMNLP Findings (2023): 2207397. [link](https://arxiv.org/abs/2303.10868)



# 🎖 Honors and Awards
- *2024.11* Google PhD Fellowship (NLP Direction)
- *2024.01* Research Achievement Award
- *2022.08* ACIS Scholarship Award
- *2022.01* 21/22 S1 Dean's List Award
- *2021.01* 20/21 S1 Dean's List Award
- *2018.08* Science and Technology Merit Scholarship
- *2013.11* MOE SM1 Scholarship


# 📖 Educations
- *2024.09 - 2025.09*, Visiting Ph.D., Department of Computer Science, Stanford University
- *2022.08 - Present*, Ph.D., Department of Computer Science, School of Computing, National University of Singapore, Singapore
- *2018.08 - 2022.05*, B.S., Business Analytics, School of Computing, National University of Singapore, Singapore
- *2014.01 - 2017.11*, Dunman High School, Singapore. 
- *2010.08 - 2013.05*, Nanjing Foreign Language School, Nanjing, China. 

# 💬 Research Interest
- **(1) Human-Centric and Data-Centric NLP**
- **(2)  NLP for Social Good**
- **(3) Socially Aware NLP System**


