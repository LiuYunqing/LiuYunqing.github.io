---
permalink: /
layout: archive
title: "About Me"
excerpt: "About Me"
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




I am currently a PhD candidate at the Department of Computing (COMP), The Hong Kong Polytechnic University (PolyU) <img src='/images/polyu_logo.png' style='width: 1.2em;'>, under the supervision of [Prof. Wenqi Fan](https://wenqifan03.github.io/) and [Chair Prof. Qing Li](https://www4.comp.polyu.edu.hk/~csqli/). Before joining the PolyU, I received my Master's degree in Computer Science from the University of Edinburgh  (M.Sc. in Computer Science) <img src='/images/uoe_log.png' style='width: 1.2em;'>. In 2020, I got my bachelor's degrees from Wuhan University (B.Sc. in Chemistry and B.Eng. in Computer Science and Technology) <img src='/images/whu_logo.png' style='width: 1.2em;'>. I am a self-motivated person and have a strong passion for scientific research. Currently, my research interest lies in AI4Science, Graph Neural Networks, and Natural Language Processing. I am always welcoming collaboration from solid partners.


## Research Interest

+ AI for Science
+ Graph Neural Networks (GNNs)
+ Natural Language Processing (NLP) 
 
## Publications <a href='https://scholar.google.com/citations?user=x8cAD_EAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>



<div class="pubs-container">

<div class="pubs-item">
    <div class="p">
    <a href="https://arxiv.org/abs/2506.06294"> <b>GLProtein: Global-and-Local Structure Aware Protein Representation Learning </b></a>
  <br><small> <b>Yunqing Liu</b>, Wenqi Fan, Xiaoyong Wei, Qing Li</small>
  <br> <a href="https://arxiv.org/abs/2506.06294"><img src="https://img.shields.io/badge/arXiv-2506.06294-b31b1b.svg" alt="badge-arxiv"/></a> 
   
  <div class='paper-box-image' style='-webkit-filter: drop-shadow(10px 10px 10px rgba(0,0,0,.5)); 
                filter: drop-shadow(10px 10px 10px rgba(0,0,0,.5)); margin-top: 5px;'><div><div class="badge">EMNLP 2025</div><img src='/images/GLProtein.png' alt="sym" width="400"></div></div>
  <br>
    </div>
  </div>


<div class="pubs-item">
    <div class="p">
    <a href="https://arxiv.org/abs/2412.14642"> <b>TOMG-Bench: Evaluating LLMs on Text-based Open Molecule Generation </b></a>
  <br><small> Jiatong Li, Junxian Li, <b>Yunqing Liu</b>, Dongzhan Zhou, Qing Li</small>
  <br> <a href="https://arxiv.org/abs/2412.14642"><img src="https://img.shields.io/badge/arXiv-2412.14642-b31b1b.svg" alt="badge-arxiv"/></a> 
   
  <div class='paper-box-image' style='-webkit-filter: drop-shadow(10px 10px 10px rgba(0,0,0,.5)); 
                filter: drop-shadow(10px 10px 10px rgba(0,0,0,.5)); margin-top: 5px;'><div><div class="badge">arXiv</div><img src='/images/TOMG.png' alt="sym" width="400"></div></div>
  <br>
    </div>
  </div>



<div class="pubs-item">
    <div class="p">
    <a href="https://arxiv.org/abs/2411.14721"> <b>MolReFlect: Towards In-Context Fine-grained Alignments between Molecules and Texts </b></a>
  <br><small> Jiatong Li, <b>Yunqing Liu</b>, Wei Liu, Jingdi Le, Di Zhang, Wenqi Fan, Dongzhan Zhou, Yuqiang Li, Qing Li</small>
  <br> <a href="https://arxiv.org/abs/2411.14721"><img src="https://img.shields.io/badge/arXiv-2411.14721-b31b1b.svg" alt="badge-arxiv"/></a> 
   
  <div class='paper-box-image' style='-webkit-filter: drop-shadow(10px 10px 10px rgba(0,0,0,.5)); 
                filter: drop-shadow(10px 10px 10px rgba(0,0,0,.5)); margin-top: 5px;'><div><div class="badge">arXiv</div><img src='/images/MolReFlect.png' alt="sym" width="400"></div></div>
  <br>
    </div>
  </div>


  
<div class="pubs-item">
    <div class="p">
    <a href="https://arxiv.org/abs/2307.02046"> <b>Recommender Systems in the Era of Large Language Models (LLMs) </b></a>
  <br><small> Wenqi Fan, Zihuai Zhao, Jiatong Li, <b>Yunqing Liu</b>, Xiaowei Mei, Yiqi Wang, Jiliang Tang, Qing Li</small>
  <br> <small>IEEE Transactions on Knowledge and Data Engineering (<b><i>TKDE</i></b>)</small> <a href="https://arxiv.org/abs/2307.02046"><img src="https://img.shields.io/badge/arXiv-2307.02046-b31b1b.svg" alt="badge-arxiv"/></a> 
  <br> <a href="/files/LLM4Rec.pdf" class="button"><small>PDF</small></a> <a href="https://advanced-recommender-systems.github.io/llms_rec_tutorial/" class="button"><small>Tutorial</small></a> 
  <div class='paper-box-image' style='-webkit-filter: drop-shadow(10px 10px 10px rgba(0,0,0,.5)); 
                filter: drop-shadow(10px 10px 10px rgba(0,0,0,.5)); margin-top: 5px;'><div><div class="badge">IEEE TKDE</div><img src='/images/LLMs_tasks.png' alt="sym" width="400"></div></div>
  <br>
    </div>
  </div>

<div class="pubs-item">
    <div class="p">
    <a href="https://arxiv.org/abs/2306.06615"> <b>Empowering Molecule Discovery for Molecule-Caption Translation with Large Language Models: A ChatGPT Perspective</b></a>
  <br> <small>Jiatong Li*, <b>Yunqing Liu</b>*, Wenqi Fan, Xiao-Yong Wei, Hui Liu, Jiliang Tang, Qing Li</small>
  <br> <small>IEEE Transactions on Knowledge and Data Engineering (<b><i>TKDE</i></b>)</small> <a href="https://arxiv.org/abs/2306.06615"><img src="https://img.shields.io/badge/arXiv-2306.06615-b31b1b.svg" alt="badge-arxiv"/></a>  
  <br> <small><b>*Co-first author</b></small>
  <br> <a href="/files/MolReGPT.pdf" class="button"><small>PDF</small></a> <a href="https://github.com/phenixace/MolReGPT" class="button"><small>Code</small></a> <a href="https://mp.weixin.qq.com/s/h5D-rOcOZ8_J65UHH_Z2uQ" class="button"><small>中文Chinese</small></a>
  <div class='paper-box-image' style='-webkit-filter: drop-shadow(10px 10px 10px rgba(0,0,0,.5)); 
                filter: drop-shadow(10px 10px 10px rgba(0,0,0,.5)); margin-top: 5px;'><div><div class="badge">IEEE TKDE</div><img src='/images/MolReGPT.png' alt="sym" width="400"></div></div>  
    </div>
  </div>

  <div class="pubs-item">
    <div class="p">
    <a href="https://arxiv.org/abs/2302.02591"> <b>Generative Diffusion Models on Graphs: Methods and Applications</b></a>
  <br> <small>Chengyi Liu, Wenqi Fan, <b>Yunqing Liu</b>, Jiatong Li, Hang Li, Hui Liu, Jiliang Tang, Qing Li</small>
  <br> <small>The 32nd International Joint Conference On Artificial Intelligence (<b><i>IJCAI</i> 2023</b>)</small> <a href="https://arxiv.org/abs/2302.02591"><img src="https://img.shields.io/badge/arXiv-2302.02591-b31b1b.svg" alt="badge-arxiv"/></a> 
  <br> <a href="/files/Diffusion_Survey.pdf" class="button"><small>PDF</small></a> <a href="https://mp.weixin.qq.com/s/rWyLqXZKuxF5hyG8TCbIyg" class="button"><small>中文Chinese</small></a> <a href="https://github.com/ChengyiLIU-cs/Generative-Diffusion-Models-on-Graphs" class="button"><small>Github</small></a> <a href="/files/diffusion_survey_poster.pdf" class="button"><small>Poster</small></a>
  <div class='paper-box-image' style='-webkit-filter: drop-shadow(10px 10px 10px rgba(0,0,0,.5)); 
                filter: drop-shadow(10px 10px 10px rgba(0,0,0,.5)); margin-top: 5px;'><div><div class="badge">IJCAI 2023</div><img src='/images/survey.png' alt="sym" width="400"></div></div>
  <br>      
    </div>
  </div>


  <div class="pubs-item">
    <div class="p">
    <a href="https://arxiv.org/abs/2302.09820"> <b>Improving User Controlled Table-To-Text Generation Robustness</b></a>
  <br> <small>Hanxu Hu, <b>Yunqing Liu</b>, Zhongyi Yu and Laura Perez-Beltrachini</small>
  <br> <small>Findings of the Association for Computational Linguistics (<b><i>EACL</i> 2023</b>)</small> <a href="https://arxiv.org/abs/2302.09820"><img src="https://img.shields.io/badge/arXiv-2302.09820-b31b1b.svg" alt="badge-arxiv"/></a> 
  <br> <a href="/files/T2TRobust.pdf" class="button"><small>PDF</small></a> <a href="https://github.com/hanxuhu/controllT2Trobust" class="button"><small>Code</small></a>
  <div class='paper-box-image' style='-webkit-filter: drop-shadow(10px 10px 10px rgba(0,0,0,.5)); 
                filter: drop-shadow(10px 10px 10px rgba(0,0,0,.5)); margin-top: 5px;'><div><div class="badge">EACL 2023</div><img src='/images/outputs.png' alt="sym" width="400"></div></div>
  <br>    
    </div>
  </div>

  <div class="pubs-item">
    <div class="p">
    <a href="https://pubs.acs.org/doi/10.1021/acs.orglett.1c00609"> <b>Late-Stage Photoredox C–H Amidation of N-Unprotected Indole Derivatives: Access to N-(Indol-2-yl)amides</b></a>
  <br> <small>Yue Weng, Bo Ding, <b>Yunqing Liu</b>, Chunlan Song, Lo-Ying Chan, and Chien-Wei Chiang</small>
  <br> <small><b><i>Organic Letters</i>, 2021</b>, <i>23</i>(7), 2710-2714</small> 
  <br> <a href="/files/acs.orglett.1c00609.pdf" class="button"><small>PDF</small></a>
  <div class='paper-box-image' style='-webkit-filter: drop-shadow(10px 10px 10px rgba(0,0,0,.5)); 
                filter: drop-shadow(10px 10px 10px rgba(0,0,0,.5)); margin-top: 2px;'><div><div class="badge">Org. Lett.</div><img src='/images/2021ACS.png' alt="sym" width="400"></div></div>
  <br>     
    </div>
  </div>

  <div class="pubs-item">
    <div class="p">
    <a href="https://chemistry-europe.onlinelibrary.wiley.com/doi/abs/10.1002/ejoc.201901572"> <b>Selective Photoredox Trifluoromethylation of Tryptophan-Containing Peptides</b></a>
  <br> <small>Bo Ding, Yue Weng, <b>Yunqing Liu</b>, Chunlan Song, Le Yin, Jiafan Yuan, Yanrui Ren, Aiwen Lei, Chien-Wei Chiang</small>
  <br> <small><b><i>European Journal of Organic Chemistry</i>, 2019</b>, <i>46</i>(12), 7596-7605</small> 
  <br> <a href="/files/ejoc.201901572.pdf" class="button"><small>PDF</small></a>
  <div class='paper-box-image' style='-webkit-filter: drop-shadow(10px 10px 10px rgba(0,0,0,.5)); 
                filter: drop-shadow(10px 10px 10px rgba(0,0,0,.5)); margin-top: 2px;'><div><div class="badge">EurJOC</div><img src='/images/ejoc_3.jpg' alt="sym" width="400"></div></div>
  
</div>
</div>
</div>





   
       

## Education

+ <img align="left" decoding="async" src="/images/polyu_logo.png" width="9%"> &nbsp;&nbsp;&nbsp;Ph.D student in Computing | <small>2023.01 - Now</small>
<br>&nbsp;&nbsp;&nbsp;The Hong Kong Polytechnic University
<br>&nbsp;&nbsp;&nbsp;Advisor: [Prof. Wenqi Fan](https://wenqifan03.github.io/) and [Chair Prof. Qing Li](https://www4.comp.polyu.edu.hk/~csqli/)
  
+ <img align="left" decoding="async" src="/images/uoe_log.png" width="9%">  &nbsp;&nbsp;&nbsp;MSc in Computer Science | <small>2021.09 - 2022.11</small>
<br>&nbsp;&nbsp;&nbsp;University of Edinburgh
<br>&nbsp;&nbsp;&nbsp;Advisor: [Prof. Elizabeth Polgreen](https://polgreen.github.io/)

+ <img align="left" decoding="async" src="/images/whu_logo.png" width="9%"> &nbsp;&nbsp;&nbsp;BEng in Computer Science and Technology | <small>2017.09 - 2020.06</small>
<br>&nbsp;&nbsp;&nbsp;Wuhan University
<br>&nbsp;&nbsp;&nbsp;Advisor: [Dr. Huajun Liu](http://csold.whu.edu.cn/teacherinfo.aspx?id=303)

+ <img align="left" decoding="async" src="/images/whu_logo.png" width="9%"> &nbsp;&nbsp;&nbsp;BSc in Chemistry | <small>2016.09 - 2020.06</small>
<br>&nbsp;&nbsp;&nbsp;Wuhan University
<br>&nbsp;&nbsp;&nbsp;Advisor: [Prof. Chien-Wei Chiang](https://scholar.google.com/citations?user=wItc-JoAAAAJ&hl=zh-TW) and [Prof. Aiwen Lei](http://aiwenlei.whu.edu.cn/lawsys/l/Aiwen_Lei/)


## Working Experience

+ Research Assistant | <small>2022.10 - 2023.01</small> | <small>Hong Kong</small> 
 <br>Department of Computing, Hong Kong Polytechnic University
 <br>Advisor: [Prof. Wenqi Fan](https://wenqifan03.github.io/) and [Chair Prof. Qing Li](https://www4.comp.polyu.edu.hk/~csqli/)
+ Research Assistant | <small>2020.12 - 2021.05</small> | <small>Beijing</small>
 <br>State Key Laboratory of Computer Science ([SKLCS](http://lcs.ios.ac.cn/)), Institute of Software, Chinese Academy of Sciences
 <br>Advisor: [Dr. Zhendong Lei](https://www.tcs-lab.com/members/leizhendong/) and [Prof. Shaowei Cai](http://lcs.ios.ac.cn/~caisw/)
 
 
 
 
 

