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
# About Me

I am an Assistant Professor in the Department of <a href='https://www.kean.edu/academics/programs/computer-science'>Computer Science and Technology</a> at <a href='https://www.kean.edu/'>Kean University</a>. 

Previously, I completed my Ph.D. at the University of Texas at Arlington (UTA), where I conducted research with Prof. <a href='https://huilucs.github.io'>Hui Lu</a>. I received my M.S. from the State University of New York (SUNY) at Binghamton, and obtained my B.E. from Beijing University of Posts and Telecommunications (BUPT).

<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->

<span class='anchor' id='research'></span>
# Research Interests

My research focuses on building efficient and scalable cloud-based networking systems. Recently, I am also exploring the reconfigurable, disaggregated hardware and AI Infrastructure.

<!--# 📝 Publications -->
<span class='anchor' id='publications'></span>
# Publications

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IPDPS</div><img src='images/pubs/ipdps23_cut.png' alt="sym" width="80%"></div></div>
<div class='paper-box-text' markdown="1">

[MFlow: Accelerating Packet Processing in Container Overlay Networks via Packet-level Prallelism](assets/pubs/ipdps23.pdf)

**<font color=black>Jiaxin Lei</font>**, Manish Munikar, Hui Lu, Jia Rao

IEEE International Parallel and Distributed Processing Symposium (IPDPS), 2023

[**[Paper]**](assets/pubs/ipdps23.pdf)
[**[BibTex]**](assets/pubs/ipdps23_bib.txt) <!--<strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>-->
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICDCS</div><img src='images/pubs/icdcs22_cut.png' alt="sym" width="80%"></div></div>
<div class='paper-box-text' markdown="1">

[PRISM: Streamlined Packet Processing for Containers with Flow Prioritization](assets/pubs/icdcs22.pdf)

Manish Munikar, **<font color=black>Jiaxin Lei</font>**, Hui Lu, Jia Rao

IEEE International Conference on Distributed Computing Systems (ICDCS), 2022

[**[Paper]**](assets/pubs/icdcs22.pdf)
[**[BibTex]**](assets/pubs/icdcs22_bib.txt) <!--<strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>-->
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EuroSys</div><img src='images/pubs/eurosys21_cut.png' alt="sym" width="80%"></div></div>
<div class='paper-box-text' markdown="1">

[Parallelizing Packet Processing in Container Overlay Networks](assets/pubs/eurosys21.pdf)

**<font color=black>Jiaxin Lei</font>**, Manish Munikar, Kun Suo, Hui Lu, Jia Rao

ACM European Conference on Computer Systems (EuroSys), 2021

[**[Paper]**](assets/pubs/eurosys21.pdf)
[**[BibTex]**](assets/pubs/eurosys21_bib.txt) <!--<strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>-->
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">SoCC</div><img src='images/pubs/socc20_cut.png' alt="sym" width="80%"></div></div>
<div class='paper-box-text' markdown="1">

[BAOVERLAY: A Block-Accessible Overlay File System for Fast and Efficient Container Storage](assets/pubs/socc20.pdf)

Yu Sun, **<font color=black>Jiaxin Lei</font>**, Seunghee Shin, Hui Lu

ACM Symposium on Cloud Computing (SoCC), 2020

[**[Paper]**](assets/pubs/socc20.pdf)
[**[BibTex]**](assets/pubs/socc20_bib.txt) <!--<strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>-->
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">HotCloud</div><img src='images/pubs/hotcloud19_cut.png' alt="sym" width="80%"></div></div>
<div class='paper-box-text' markdown="1">

[Tackling Parallelization Challenges of Kernel Network Stack for Container Overlay Networks](assets/pubs/hotcloud19.pdf)

**<font color=black>Jiaxin Lei</font>**, Kun Suo, Hui Lu, Jia Rao

USENIX Workshop on Hot Topics in Cloud Computing (HotCloud), 2019

[**[Paper]**](assets/pubs/hotcloud19.pdf)
[**[BibTex]**](assets/pubs/hotcloud19_bib.txt) <!--<strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>-->
</div>
</div>

<!--
- [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020**
-->

<span class='anchor' id='teaching'></span>
# Teaching

- [**2024 Fall**] TECH-2920-Computer Systems
- [**2024 Fall**] CPS-3250-Computer Operating Systems 

<span class='anchor' id='talks'></span>
# Talks

- [**2023.05**] “Accelerating Packet Processing in Container Overlay Networks via Packet-leve Parallelism”, in IPDPS '23, St.Petersburg, FL, USA.
- [**2022.11**] “Accelerating Packet Processing in Container Overlay Networks”, in SUNY Binghamton Computer Science Department Seminar, Binghamton, NY, USA.
- [**2021.04**] “Parallelizing Packet Processing in Container Overlay Networks”, in EuroSys ‘21, Virtual.
- [**2019.07**] “Tackling parallelization challenges of kernel network stack for container overlay networks”, in HotCloud ‘19, Renton, WA, USA.

<!--
# 🔥 News
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
-->

<!--
# 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
-->

<!-- # 📖 Educations -->
<!--
<span class='anchor' id='education'></span>
# Education

- 2023 - 2024, Ph.D. in Computer Science

    University of Texas at Arlington

- 2019 - 2023, Ph.D. Candidate in Computer Science

    State University of New York at Binghamton

- 2017 - 2019, M.S. in Computer Science

    State University of New York at Binghamton

- 2013 - 2017, B.E. in Telecommunications Engineering with Management
    
    Beijing University of Posts and Telecommunications
-->

<!--
# 📖 Educations
- *2019.06 - 2022.04 (now)*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2015.09 - 2019.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.
--> 

<!--
# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)
-->

<!--
# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China.
-->

<br>

<p> &copy; Last updated on 11/29/2024 by <a href="https://www.kean.edu/directory/jiaxin-lei-0" target="_blank" rel="noopener">Jiaxin Lei</a></p>