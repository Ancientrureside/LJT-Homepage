---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

## Education

- **Ph.D. in Computer Science**, Hong Kong University of Science and Technology (2024-Present)
  - HKUST NLP Group, led by Professor Junxian He.
  - PhD supervisor: Professor Junxian He.
- **B.Eng.**, Shanghai Jiao Tong University (2020-2024)
  - Graduated in June 2024.
  - Professor Junxian He previously advised Junteng Liu during undergraduate studies at SJTU.

## Research Experience

- **Research Intern, MINIMAX** (February 2025 - Present)
- **PhD research at HKUST NLP Group** (2024-Present)
  - Supervisor: Professor Junxian He.
  - Research areas: natural language processing and machine learning; LLM Reasoning and Reinforcement Learning; Hallucination in Vision-Language Models (VLM); LLM Truthfulness and Interpretability.
- **Research Intern, Tencent WXG** (June 2024 - September 2024)
  - Advisor: Zifei Shan.
- **Research Intern, Shanghai AI Lab** (June 2023 - December 2023)
  - Advisor: Prof. Yu Cheng.

## Skills

- Natural Language Processing
- Machine Learning
- LLM Reasoning and Reinforcement Learning
- Hallucination in Vision-Language Models (VLM)
- LLM Truthfulness and Interpretability
- Research methods documented in publications: verifiable reasoning data synthesis, VLM chart-understanding/perception analysis, truthfulness hyperplane analysis, inner-representation analysis for hallucination mitigation, Chinese foundation-model evaluation, and arithmetic composition of parameter-efficient modules.

## Honors and Awards

- Zhiyuan Honor Scholarship, awarded by Shanghai Jiao Tong University.

## Publications

{% assign publications_by_order = site.publications | sort: "order" %}
<ul>
{% for post in publications_by_order %}
  {% include archive-single-cv.html %}
{% endfor %}
</ul>

## Contact Information

- Email: [jliugi@connect.ust.hk](mailto:jliugi@connect.ust.hk)
- GitHub: [Vicent0205](https://github.com/Vicent0205)
- Google Scholar: <https://scholar.google.com/citations?hl=en&user=tbK9jl4AAAAJ&view_op=list_works&sortby=pubdate>
- X (Twitter): [@junteng88716710](https://twitter.com/junteng88716710)
