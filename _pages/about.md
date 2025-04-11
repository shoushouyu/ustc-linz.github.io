---
permalink: /
title: "He Sun - Homepage"
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

# About Me (Updated in 2025.2)

<span class='anchor' id='about-me'></span>
Hi, there. I am Zijie Lin (林子杰), a second-year master's student in the [Department of Computer Science and Technology](https://cs.ustc.edu.cn/main.htm) & [Suzhou Institute for Advanced Study](https://sz.ustc.edu.cn/index.html) & [State Key Laboratory of Cognitive Intelligence](http://cogskl.iflytek.com/) at the [University of Science and Technology of China](https://ustc.edu.cn/) (USTC), supervised by Prof. [Mingjun Xiao](http://staff.ustc.edu.cn/~xiaomj/indexEN.html).

My research interests include Natural Language Processing & Multi-agent Systems. I have published several academic papers in top-tier international conferences and journals, including IEEE INFOCOM, IEEE ICDCS, IEEE Transactions on Mobile Computing, IEEE Transactions on Parallel and Distributed Systems, etc.


**I am seeking opportunities for Doctoral Researcher in 2026. If you are interested in my research, please don't hesitate to contact me: lzj741@mail.ustc.edu.cn** 

# 🔥 News
<span class='anchor' id='-news'></span>


# 📝 Publications 
<span class='anchor' id='-publications'></span>

  
## Conferences

{% raw %}
<!-- 更多内容 -->
<div id="more-content" style="display: none;">
    <ul>
        <li><b>He Sun</b>, Junyuan Mao, Jinrui Zhou, Mingjun Xiao. "ReSmart: Distributed Stable Task Matching in Non-stationary Environment", VLDB 25‘ (On Submission)</li>
        <li><b>He Sun</b>, Xihao Sun, Li Li, Yebo Wu, Mingjun Xiao, Chengzhong Xu. "LongInfer: Exploring Fast Inference of Long-Context Large Language Models on a Consumer-grade GPU." (On Submission)</li>
        <li><b>He Sun</b>, Li Li, Mingjun Xiao, Yebo Wu, Chengzhong Xu. "Efficient Split Federated Tuning for Long-Context Large Language Models." (On Submission)</li>
    </ul>
</div>

<!-- More按钮 -->
<p class="more-button" onclick="toggleMore()">More...</p>

<script>
    function toggleMore() {
        var moreContent = document.getElementById("more-content");
        var moreButton = document.querySelector(".more-button");

        if (moreContent.style.display === "none") {
            moreContent.style.display = "block";
            moreButton.textContent = "Less...";
        } else {
            moreContent.style.display = "none";
            moreButton.textContent = "More...";
        }
    }

    // 确保页面加载时隐藏更多内容
    document.addEventListener("DOMContentLoaded", function() {
        document.getElementById("more-content").style.display = "none";
    });
</script>
{% endraw %}

## Journals


# 📝 Experiences 
<span class='anchor' id='-experiences'></span>
<div class='school-box'>
<div><img src='../images/iotsc.png' alt="sym" width="80"></div>
<div class='school-box-text' markdown="1">

State Key Laboratory in the Internet of Things for Smart City, University of Macau, Macau, China.
</div>
</div>

<div class='school-box'>
<div><img src='../images/ustc.png' alt="sym" width="80"></div>
<div class='school-box-text' markdown="1">

</div>
</div>

# 📖 Professional Services
<span class='anchor' id='-services'></span>
## Conferences


## Journals

 
# 🎖 Honors and Awards
<span class='anchor' id='-honors-and-awards'></span>

## Honors
- Suzhou Industrial Park Scholarship at USTC (2023.3)
- "Yang Yuanqing" Scholarship at USTC (2022.12)
- Excellent League member at USTC( 2021.4)
- 5 times first-class scholarship at QDU (2016-2020)
- "Shuguang" scholarship (2019.10)
- Outstanding student leaders prize at QDU (2018.10)
- Outstanding graduate prize at QDU (2020.5)

## Competitions Awards
- Second Prize in China software open source innovation competition (National College Green Computing) Contest-21 (Open source project innovation competition) by CCF, 2021.
- Outstanding Winner(No.1) in National College Green Computing Contest-19 (Project Challenge) by CCF, 2019.
- Outstanding Winner(No.3) in National College Green Computing Contest-18 (Project Challenge) by CCF, 2018.
- Third Prize in Math Competition for College Students, 2019. 
- Third Prize(Top 8) in Imagine Cup 2018 of Microsoft, 2018. 
- First prize in the National High School Mathematics Competition in Shandong Province, 2015.

# 🎓 Educations
<span class='anchor' id='-educations'></span>
<div class='school-box'>
<div><img src='images/ustc.png' alt="sym" width="80"></div>
<div class='school-box-text' markdown="1">
2022.07 - Now, Ph.D. Student.

School of Computer Science and Technology, University of Science and Technology of China (CS, USTC), Hefei, Anhui.
</div>
</div>

<div class='school-box'>
<div><img src='images/ustc.png' alt="sym" width="80"></div>
<div class='school-box-text' markdown="1">
2020.09 - 2022.6, Master Student.

School of Cyberspace Security, University of Science and Technology of China (CS, USTC), Hefei, Anhui.
</div>
</div>

<div class='school-box'>
<div><img src='images/qdu.png' alt="sym" width="80"></div>
<div class='school-box-text' markdown="1">
2016.09 - 2020.06, B.S. School of Computer Science and Technology.<br>
2017.09 - 2020.06, B.A. School of Foreign Languages.

Qingdao University (QDU), Qingdao.
</div>
</div>

# 💬 Talks
<span class='anchor' id='-invited-talks'></span>
- *2023.05*: &nbsp; IEEE INFOCOM 2023, 17-20 May, Stevens Institute of Technology, New York Area. [slides](https://ustc-sunny.github.io/INFOCOM2023_slides.pdf)
- *2024.07*: &nbsp; CIBD 2024, 20 July, State Key Laboratory of Cognitive Intelligence, USTC&iFlytek, Hefei. [Poster](https://ustc-sunny.github.io/CIBD2024_sunhe.pdf)

# 💻 Project
<span class='anchor' id='-Project'></span>
- National Innovation and Entrepreneurship Program for College Students in China, The Research and Development of Parking Sharing System in Smart City, 2018.5-2020.5.: **Project leader**
- Project of National Natural Science Foundation of China, Research on Intelligent and Trusted Cooperation Mechanism of Mobile Group Intelligence Computing based on blockchain, 2022.01-2025.12: **Core member**
- Project of National Natural Science Foundation of China, Research on Key Technologies of Secure and Trusted Mobile Group Intelligence Sensing Data Trading System, 2019.01-2022.12：**Core member**
- Jiangsu Provincial Natural Science Foundation Project, Research on Key Technologies of Data Trading System based on Mobile Group Intelligence Perception, 2019.07-2022.0：**Core member**

<script type="text/javascript" id="clustrmaps" src="//clustrmaps.com/map_v2.js?d=LqdKMIUIOitYiwaA4JQq_FwX-hC5DUE7OOLAKpsMmV8&cl=ffffff&w=a"></script>
