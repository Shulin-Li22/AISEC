---
layout: default
---

# 主页内容

Welcome to AISEC!

This is Shulin Li's Blog.

This blog is aimed at documenting my personal thoughts/understanding when I read research papers related to Artificial Intelligence (AI) and Artifical Intelligence Security. 

I named this blog "AISEC", which is the abbreviation of "AI" and  "Security"


I am currently a undergraduate student in Beijing University of Posts and Telecommunications (BUPT) and Queen Mary University of London (QMUL), which is the joint programme between BUPT and QMUL.
I will graduated from both university in June 30th, 2026. Then, I will continue my study at Huazhong University of Science and Technology, major in LLM Security.


## 笔记列表

<ul>
  {% for post in site.posts reversed %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      - {{ post.date | date: "%Y-%m-%d" }}
    </li>
  {% endfor %}
</ul>
