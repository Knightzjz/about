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
Hi, there:   
&nbsp;&nbsp;&nbsp;&nbsp;I'm Jizhe Zhou (周吉喆), Associate Professor at the School of Computer Science, Sichuan University. I obtained my Ph.D. (early graduation) from the University of Macau in 2021. My primary research areas are the self-supervised learning theories and the multimedia content security. I am the first or corresponding author for many top conferences and IEEE transactions, including ICCV, NIPS, ACM MM, ACL, IJCAI, AAAI, etc,. Four of them are oral papers, 1 in ICCV, 3 in ACM MM. My publication recieved a total <a href='https://scholar.google.com/citations?user=-cNWmJMAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a> citations.   

&nbsp;&nbsp;&nbsp;&nbsp;周吉喆，四川大学计算机学院副教授，主要擅长内容安全和自监督学习方向，长期招收AI+CV方向solid background and self-motivated的研究生与本科生（限川大），组内各研究方向详见Supervised Students部分，欢迎联系邮件 jzzhou@scu.edu.cn 。   

# 🔥 News
- ``Competition`` *2024.09*: &nbsp;🎉🎉 We won the *First Price* in  **``Tecent AI Arena competition (腾讯开悟比赛多智能体博弈赛道)``**, meaning  *1/2000+* . Both of our teams are advanced to the grand finals, check "[Award List of Tecent AI Arena 2024](https://pre-prod.kaiwu.pvp.qq.com/aiarena/zh/match/open-competition-2024?tab=score)" for details.   
- ``Publication`` *2024.07*: &nbsp;🎉🎉 Two of our works on image generation are accepted as *oral* in *ACM MM2024*! Code and paper will soon be available!
- ``S&A Service`` *2024.06*: Appointed as the *Program Committee Member* for *AAAI24*.  
- ``Publication`` *2024.06*: &nbsp;🎉🎉 Our comprehensive benchmark and modular codebase on IML (addressing the model evaluation), [IMDL-BenCo](https://github.com/scu-zjz/IMDLBenCo)[![](https://img.shields.io/github/stars/scu-zjz/IMDLBenCo?style=social&label=Code+Stars)](https://github.com/scu-zjz/IMDLBenCo), is now fully released and under long-term maintenance and construction!  
- ``Publication`` *2024.06*: &nbsp;🎉🎉 Our latest framework and benchmark model on private object detection, [PrivacyGuard](https://arxiv.org/pdf/2406.12736), is now online; the code and training dataset will soon be available!
- ``S&A Service`` *2024.04*: Appointed as the *Program Committee Member* for *NIPS24*.
- ``S&A Service`` *2024.02*: Appointed as the *Program Committee Member* for *ECCV24*. 
- ``S&A Service`` *2024.01*: Appointed as the *Area Chair* for *MM24*. 
- ``Publication`` *2023.12*: &nbsp;🎉🎉 Our latest benchmark model on IML, [IML-ViT](https://github.com/SunnyHaze/IML-ViT), is now fully outsourced!  

# 📝 Selected Publications 

## Image Generation
- ``TIFS`` [Personal privacy protection via irrelevant faces tracking and pixelation in video live streaming](https://ieeexplore.ieee.org/abstract/document/9218980/), **Jizhe Zhou**, Chi-Man Pun.
- ``ACM MM 2020`` [Privacy-sensitive objects pixelation for live video streaming](https://dl.acm.org/doi/abs/10.1145/3394171.3413972), **Jizhe Zhou**, Chi-Man Pun, Yu Tong.
- ``TNNLS`` [Shunting at Arbitrary Feature Levels via Spatial Disentanglement: Toward Selective Image Translation](https://ieeexplore.ieee.org/abstract/document/10153513/), Jian Wang, Xue Yang, Yuxin Tian, **Jizhe Zhou**, Jiancheng Lv.
      
## Anti-Generation
- ``ICCV 2023 (oral)`` [Pre-training-free Image Manipulation Localization through Non-Mutually Exclusive Contrastive Learning](https://openaccess.thecvf.com/content/ICCV2023/html/Zhou_Pre-Training-Free_Image_Manipulation_Localization_through_Non-Mutually_Exclusive_Contrastive_Learning_ICCV_2023_paper.html), **Jizhe Zhou**, Xiaochen Ma, Xia Du, Ahmed Y Alhammadi, Wentao Feng, [![](https://img.shields.io/github/stars/knightzjz/NCL-IML?style=social&label=Code+Stars)](https://github.com/knightzjz/NCL-IML)  
- ``To Appear`` [IML-ViT: Image Manipulation Localization by Vision Transformer](https://arxiv.org/abs/2307.14863). Xiaochen Ma, Bo Du, Zhuohang Jiang, Ahmed Y. Al Hammadi, **Jizhe Zhou**,  [![](https://img.shields.io/github/stars/SunnyHaze/IML-ViT?style=social&label=Code+Stars)](https://github.com/SunnyHaze/IML-ViT)        
- ``ACM MM 2023 (oral)`` [M2ATS: A Real-world Multimodal Air Traffic Situation Benchmark Dataset and Beyond](https://dl.acm.org/doi/abs/10.1145/3581783.3613759), Dongyue Guo, Yi Lin, Zheng Zhang, **Jizhe Zhou**.  

## Reasoning under DNN
- ``ACL 2022`` [Word Segmentation by Separation Inference for East Asian Languages](https://aclanthology.org/2022.findings-acl.309/), Yu Tong, Jingzhi Guo, **Jizhe Zhou**, Ge Chen, Guokai Zheng.
- ``IJCAI 2022`` [Abstract rule learning for paraphrase generation](https://ijcai-22.org/main-track-accepted-papers/), Xianggen Liu, Wenqiang Lei, Jiancheng Lv, **Jizhe Zhou**.
- ``TASLP`` [Separation inference: A unified framework for word segmentation in east Asian languages](https://ieeexplore.ieee.org/abstract/document/9740431), Yu Tong, Jingzhi Guo, **Jizhe Zhou**.
- ``TASLP`` [Towards Recognition for Radio-echo Speech in Air Traffic Control: Dataset and a Contrastive Learning Approach](https://ieeexplore.ieee.org/abstract/document/10225727/). Yi Lin, Qingyang Wang, Xincheng Yu, Zichen Zhang, Dongyue Guo, **Jizhe Zhou**.  <!---- **IEEE/ACM Transactions on Audio, Speech, and Language Processing.** -->


# 📖 Educations
 >- *2013*, **Bsc.**, Software Engineering, FST, University of Macau, Macau SAR.
 >- *2018*, **Msc.**, Software Engineering, FST, University of Macau, Macau SAR.
 >- *2021*, **Ph.D.**, Computer and Information Science, FST, University of Macau, Macau SAR.
 >- *2016 - 2018*, **Student Research Assistant**, CSE, Chinese University of Hong Kong, Hong Kong SAR.
 >- *2019 - 2020*, **Student Research Assistant**, Kakao Track, Yonsei University, Korean.

# 💬 Invited Talks
> ["A Song of Ice and Fire: Image Tampering Techniques in the Age of Large Generative Models"](https://www.bilibili.com/video/BV1sw411y7YR/?spm_id_from=333.337.search-card.all.click), [PRML 2023](http://www.prml.org/invited.html), Urumqi, China.   
> ["如何为直播中的人脸自动打码"](https://vs.scu.edu.cn/info/1021/1793.htm), Academic Salon (a.k.a Job Talk), Sichuan Unviersity 2021.   
> ["Multi-Object Online-Tracking"](https://github.com/UniversityMLCampJeju/2019), University ML Camp (UMLC2019), Jeju, Korean.   

<!---
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)
 --->
# 📝 Academic Services
>- Area Chair: ACM MM 2023
>- Publicity Chair: CSAI 2023  
>- Technical Program Committee: PRML 2023  
>- Program Committee: AAAI 2021 & 2022, WWW 2021, ICLR 2022, ACM MM 2021 & 2022 & 2023, TCSVT, TIP, TMM, TNNLS, etc.. 

# 📝 Supervised Students (2022-now)
- **Image Manipulation Localization**  
>1. [Xiaochen Ma](https://me.xiaochen.world/), Research Assistant at Sichuan University [Now Ph.D student in MBZUAI, UAE] (Backbone Architecture for IML).   
>2. Bo Du, Graduate Student in CS, Sichuan University (IML by Diffusion)    
>3. Xinyu Yang, Undergraduate Student in CS, Sichuan University (Data Sythensize for IML)   
>4. Lei Su, Master Student in CS, Sichuan University (Anti-AIGC)  
>5. Mingxi Guo, Ph.D. Candidate in CIS, University of Macau (Anti-AIGC)    
- **Reasoning under DNN Architecture**  
>1. [Yu Tong](https://eng.stu.edu.cn/info/1082/3025.htm), Lecture, Department of Computer Science and Technology, College of Engineering, Shantou Univerisity (Separation Inference)  
>2. Ruiyang Ni, Master Student in CS, Sichuan University (Graph Inference)  
>3. Bingkui Tong, Undergraduate Student in CS, Sichuan University (Graph Inference)
>4. Pengsen Liu, Ph.D Student in Lamda Lab, Nanjing University (Game AI)
>5. Zeyu Lei, Undergraduate Student in CS [Now exchange student in University of Macau], Honor College, Sichuan University (Fine-grained Classification)
- **Image Generation and Industrial Detection**
>1. Jian Wang, Ph.D. Candidate in CS, Sichuan University (Image-to-Image Translation)   
>2. Jian Zhang, Master Student in CS, Sichuan University (Defect Detection)    
>3. Zhuohang Jiang, Undergraduate Student in CS [Now Ph.D student in PolyU, HongKong], Sichuan University (Deblur \& Image Privacy )  
>4. Xuekang Zhu, Master Student in CS, Sichuan University (Game Avatar Generation)   

