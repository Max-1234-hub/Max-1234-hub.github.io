---
permalink: /
title: "About Me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

I am an associate professor (since December 2023) in the [Intelligent Information Processing Laboratory (IIPLab)](http://iipl.net.cn/index/index.aspx), [School of Communication Engineering](https://comm.hdu.edu.cn/main.htm), [Hangzhou Dianzi University (HDU)](https://www.hdu.edu.cn/main.htm). I am also a postdoctoral fellow at Zhejiang University, working with Prof. [Kaiying Wang](https://person.zju.edu.cn/0001039). I received my Ph.D. from the [City University of Hong Kong](https://www.cityu.edu.hk/) in 2023, where I worked in the [LIU Laboratory for SMART Animal Management](https://www.samcityu.com/) under the supervision of Prof. [Kai Liu](https://www.cityu.edu.hk/ph/staff/dr-kai-liu).

My research focuses on deep learning and multimodal intelligent perception for smart animal monitoring and precision livestock farming. I use wearable sensors, computer vision and acoustic signals for animal activity recognition, identification and tracking, and health and welfare monitoring, with an emphasis on models that stay reliable under real-world constraints such as limited labels, low-power devices, occluded scenes and privacy-sensitive data. See [Research]({{ base_path }}/research/) for details.

I serve as an Associate Editor of *Frontiers in Ethology*. Motivated students and collaborators are welcome to contact me at [{{ site.author.email }}](mailto:{{ site.author.email }}).

News
======

<ul class="dated-list dated-list--scroll">
{%- for item in site.data.news %}
<li><span class="dated-list__date">{{ item.date }}</span><span>{{ item.text }}</span></li>
{%- endfor %}
</ul>

Awards and Honors
======

<ul class="dated-list">
{%- for award in site.data.awards %}
<li><span class="dated-list__date">{{ award.date }}</span><span>{{ award.text }}</span></li>
{%- endfor %}
</ul>
