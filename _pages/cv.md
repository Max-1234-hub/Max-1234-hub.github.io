---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

**Axiu Mao (毛阿秀)** · [axiu.mao@hdu.edu.cn](mailto:axiu.mao@hdu.edu.cn) · Room 302, Xinren Building, Hangzhou Dianzi University, China

[Download CV (PDF)]({{ base_path }}/files/CV_AxiuMao.pdf){: .btn .btn--info}

Professional experience
======
* **Associate Professor (pre-tenured)**, Hangzhou Dianzi University, China (Dec. 2023 – present)
  * Department of Information and Communication Engineering, Intelligent Information Processing Laboratory (IIPLab)
* **Postdoctoral Fellow**, Zhejiang University, China (May 2025 – present)
  * Department of Agriculture Engineering; supervisor: Prof. Kaiying Wang
* **Part-time Research Assistant**, City University of Hong Kong (Sep. 2021 – Sep. 2023)
  * Jockey Club College of Veterinary Medicine and Life Sciences
* **Teaching Assistant**, City University of Hong Kong (Sep. 2020 – May 2023)
  * Jockey Club College of Veterinary Medicine and Life Sciences

Education
======
* **Ph.D.**, City University of Hong Kong (Oct. 2019 – Oct. 2023)
  * Department of Infectious Diseases and Public Health; supervisor: Prof. Kai Liu
  * Thesis: *Towards robust animal activity recognition using deep learning and wearable sensors*
* **B.S.** in Quality Management Engineering, China Jiliang University (Sep. 2015 – Jun. 2019)
  * Rank: 1/81

Research interests
======
Deep learning, wearable sensors, computer vision, activity pattern recognition, acoustic detection, intelligent animal monitoring, precision livestock farming.

Funding
======
<ul>
{%- for project in site.data.research.projects %}
<li><strong>{{ project.role }}</strong>, {{ project.funder }}, {{ project.year }}. Topic: {{ project.title }}.</li>
{%- endfor %}
</ul>

Publications
======
{{ site.data.publications | where: "type", "journal" | size }} journal articles and {{ site.data.publications | where: "type", "conference" | size }} conference papers; see the [Publications]({{ base_path }}/publications/) page for authors, links and code.

<ul class="pub-lines">
{%- for pub in site.data.publications %}
<li class="pub-line"><span class="venue-tag">{{ pub.tag }}</span> {{ pub.title }}</li>
{%- endfor %}
</ul>

Selected awards
======
* Outstanding Faculty Award of Annual Assessment, School of Communication Engineering, HDU (2024)
* Second Runner-Up, Huawei Developer Competition 2023 – Asia Pacific (2023)
* Bronze Award, 9th China International College Students' 'Internet+' Innovation and Entrepreneurship Competition (2023)
* Silver Award, 8th China International College Students' 'Internet+' Innovation and Entrepreneurship Competition (2022)
* Research Tuition Scholarship, City University of Hong Kong (2022)
* Outstanding Graduate Student Paper and Presentation Award, ISAEW 2021 (2021)
* Outstanding Graduate of Zhejiang Province (2019)
* Meritorious Winner, Mathematical Contest in Modeling (2018)
* First Prize, National Mathematics Competition (2018)

Professional service
======
* **Associate Editor:** Frontiers in Ethology
* **Program Committee Member:** IEEE BIBM 2026
* **Journal reviewer:** Artificial Intelligence in Agriculture; Computers and Electronics in Agriculture; Expert Systems With Applications; Information Processing in Agriculture; Computers in Biology and Medicine; Patterns; Journal of the ASABE; Scientific Reports; AgriEngineering; Sustainability; Agriculture
* **Conference reviewer:** USPLF 2023
* **Conference presentations:** ACPLF 2024 (Beijing, China); ECPLF 2024 (Bologna, Italy); USPLF 2023 (Tennessee, United States); ECPLF 2022 (Vienna, Austria); ISAEW 2021 (Chongqing, China)
