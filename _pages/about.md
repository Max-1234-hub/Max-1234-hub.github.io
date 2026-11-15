---
permalink: /
title: "Welcome to the Mao Lab"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

{% include base_path %}

We are a research group led by [Dr. Axiu Mao]({{ base_path }}/cv/) in the [Intelligent Information Processing Laboratory (IIPLab)](http://iipl.net.cn/index/index.aspx), [School of Communication Engineering](https://comm.hdu.edu.cn/main.htm), [Hangzhou Dianzi University (HDU)](https://www.hdu.edu.cn/main.htm). Our research is on **deep learning and multimodal intelligent perception**, with a focus on smart animal monitoring and precision livestock farming.

We build models that see, hear and sense animals through cameras, microphones and wearable sensors, and that keep working under real-world constraints: occluded and crowded scenes, limited labels, low-power devices and privacy-sensitive data.

<div class="lab-figure">
  <img src="{{ base_path }}/images/team/group-photo.jpg" alt="Group photo of the Mao Lab">
</div>

Research
======

<div class="lab-figure">
  <a href="{{ base_path }}/research/"><img src="{{ base_path }}/images/research/overview.svg" alt="Overview of the lab's research: multimodal sensing, five research directions, and applications"></a>
</div>

<ul class="home-topics">
{%- for topic in site.data.research.topics %}
<li><a href="{{ base_path }}/research/#{{ topic.id }}">{{ topic.title }}</a></li>
{%- endfor %}
</ul>

See the [Research]({{ base_path }}/research/) page for an illustrated summary of each direction and the related papers, and the [Publications]({{ base_path }}/publications/) page for the full list.

About the PI
======

Axiu Mao is a pre-tenured associate professor at HDU and a postdoctoral fellow at Zhejiang University, working with Prof. [Kaiying Wang](https://person.zju.edu.cn/0001039). She received her Ph.D. from the [City University of Hong Kong](https://www.cityu.edu.hk/) in 2023, where she worked in the [LIU Laboratory for SMART Animal Management](https://www.samcityu.com/) under the supervision of Prof. [Kai Liu](https://www.cityu.edu.hk/ph/staff/dr-kai-liu). She serves as an Associate Editor of *Frontiers in Ethology* and as a reviewer for more than ten international journals.

News
======

<ul class="dated-list dated-list--scroll">
{%- for item in site.data.news %}
<li><span class="dated-list__date">{{ item.date }}</span><span>{{ item.text }}</span></li>
{%- endfor %}
</ul>

Join us
======

We are looking for motivated M.Sc. and undergraduate students, and we welcome collaborations with academia and industry. Please see the [Team]({{ base_path }}/team/#join-us) page or write to [{{ site.author.email }}](mailto:{{ site.author.email }}).

**Office:** Room 302, Xinren Building, Hangzhou Dianzi University, Hangzhou, China.
