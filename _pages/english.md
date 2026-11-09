---
layout: archive
title: ""
permalink: /english
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}


**[中文](/) \| [English](/english)**

# 👤 Bio

I am currently a postdoctoral researcher in the School of Computer Science at the [University of Science and Technology of China (USTC)](https://ustc.edu.cn/), working with the LINKE laboratory. During my doctoral studies, I was supervised by [Professor Xiangyang Li](https://cs.ustc.edu.cn/2020/0806/c23235a460096/page.htm) (ACM Fellow, IEEE Fellow). My research interests mainly include efficient inference and industrial intelligence, with additional interests in intelligent sensing and intelligent-model security. My [CV](/files/CV_Junyang_Zhang.pdf) is available for download.

# 🎓 Education

- **2022.09 - 2026**&emsp;<a href="https://ustc.edu.cn/" style="color: inherit;">University of Science and Technology of China</a>, School of Computer Science, PhD in Computer Science.
- **2020.09 - 2022.06**&emsp;<a href="https://ustc.edu.cn/" style="color: inherit;">University of Science and Technology of China</a>, School of Computer Science, pursuing a Master's degree in Computer Science.
- **2016.09 - 2020.06**&emsp;<a href="https://www.cqu.edu.cn/" style="color: inherit;">Chongqing University</a>, Hongshen School/Computer Science School, obtained a Bachelor's degree in Computer Science.

# 📰 News
- **[Oct 2026]** 🎓 Graduated with a PhD in Computer Science from the School of Computer Science, USTC.

# 🏅 Awards
- **2026** Chinese Academy of Sciences President's Award
- **2025** National Scholarship for PhD Students
- **2025** China Association for Science and Technology Young Elite Scientists Sponsorship Program (PhD Student Special)

# 📚 Publications

1. **A-VL: Adaptive Attention for Large Vision-Language Models.**  
   **Junyang Zhang**, Mu Yuan, Ruiguang Zhong, Puhan Luo, Huiyou Zhan, Ningkang Zhang, Chengchen Hu, Xiangyang Li.  
   *AAAI 2025*, 39(21): 22461–22469. (First author)

2. **WordWhisper: Exploiting Real-Time, Hardware-Dependent IoT Communication Against Eavesdropping.**  
   **Junyang Zhang**, Jiahui Hou, Ye Tian, Xiang-Yang Li.  
   *IEEE Transactions on Mobile Computing*, 2025, 24(1): 15–29. (First author)

3. **Deploy Efficient Large Language Model Distributed Inference Pipeline for Heterogeneous GPUs.**  
   **Junyang Zhang**, Jiahui Hou, Bowen Zhang, Xiang-Yang Li.  
   *IEEE/ACM IWQoS 2025*: 1–10. (First author)

4. **TensAllo: Adaptive Deployment of LLMs on Resource-Constrained Heterogeneous Edge Devices.**  
   Bowen Zhang, **Junyang Zhang**, Jiahui Hou, Yixin Wang.  
   *IEEE INFOCOM 2025*: 1–10. (Co-first author)

5. **LightMoE: Task-Aware Expert Availability Management for Memory-Efficient MoE-LLM Inference.**  
   P. Luo, Y. Yao, J. Wang, **Junyang Zhang**, X.-Y. Li.  
   *Findings of ACL 2026*: 21124–21134. (Corresponding author)

6. **CALSI: Context-Aware Layer Skipping Inference for On-Device LLM Serving.**  
   Puhan Luo, Mu Yuan, Ningkang Zhang, Ruiguang Zhong, **Junyang Zhang**, Chengchen Hu, Xiang-Yang Li.  
   *IEEE Transactions on Mobile Computing*, 2026, 25(10): 17863–17878. (Corresponding author)

7. **FlexiTensor: Adaptive Multi-Task Deployment of LLMs on Resource-Constrained Heterogeneous Edge Devices.**  
   Bowen Zhang, Jiahui Hou, **Junyang Zhang**.  
   *IEEE Transactions on Parallel and Distributed Systems*, 2026, 37(9): 2078–2094. (Collaborative paper)

8. **面向智能物联网的资源高效模型推理综述**  
   袁牧，张兰，姚云昊，**张钧洋**，罗溥晗，李向阳。  
   *计算机学报*，2024，47(10)：2247–2273。（Collaborative paper）

[Additional preprints are available on arXiv.]


# 📝 Research

### Model Inference Optimization

Model inference optimization (primary research focus): This area addresses performance bottlenecks when deep learning models are deployed in real-world applications. The goal is to enhance the inference efficiency of deep learning models, reduce computational costs, minimize latency, and optimize resource utilization while maintaining or improving accuracy, ultimately achieving cost reduction and efficiency enhancement.
- **Application Project:** Independently responsible for research on multimodal large model computational optimization in the **NIO Industry-University Collaboration Project** "Intelligent Cockpit Inference Optimization Based on Large Models", aiming to reduce computational load, decrease inference latency, and minimize KV Cache memory usage.
- **Application Project:** Independently responsible for research on distributed inference optimization for large models under heterogeneous computing power in the **Huawei Industry-University Collaboration Project** "AI Efficiency Improvement on the Edge", aiming to enhance inference throughput and improve resource utilization under heterogeneous computing environments.
- **Application Project:** Participated in the development of an industry knowledge base and large model Q&A system in the **Baidu Industry-University Collaboration Project** "ESG Domain-Specific Question Answering System", focusing on real system optimization for vertical domain knowledge Q&A.
- **First Author, AAAI 2025:** A-VL: Adaptive Attention for Large Vision-Language Models.
- **First Author, IWQoS 2025:** Deploy Efficient Large Language Model Distributed Inference Pipeline for Heterogeneous GPUs.
- **Co-first Author, INFOCOM 2025:** TensAllo: Adaptive Deployment of LLMs on Resource-Constrained Heterogeneous Edge Devices.
- **Corresponding Author, Findings of ACL 2026:** LightMoE: Task-Aware Expert Availability Management for Memory-Efficient MoE-LLM Inference.
- **Corresponding Author, IEEE TMC 2026:** CALSI: Context-Aware Layer Skipping Inference for On-Device LLM Serving.
- **Collaborative Paper, IEEE TPDS 2026:** FlexiTensor: Adaptive Multi-Task Deployment of LLMs on Resource-Constrained Heterogeneous Edge Devices.
- **Collaborative Paper:** 面向智能物联网的资源高效模型推理综述。

### Intelligent Sensing

Intelligent sensing: The deep integration of artificial intelligence and information sensing technology, leveraging wireless signals for environmental perception, object detection, and behavior recognition. This technology overcomes the limitations of traditional sensors, such as light and visibility angle, and offers advantages in low power consumption, non-contact sensing, and high precision. Intelligent sensing often leads to unexpected breakthroughs using common wireless signals, combining inspiration and creativity to drive innovation.
- **First Author Paper: [CCF A]** WordWhisper: Exploiting Real-Time, Hardware-Dependent IoT Communication Against Eavesdropping.
 
### Model Security

Model inference security: Model inference security can be divided into three stages: pre-inference (input security), during inference (weight security), and post-inference (output security). From a goal-oriented perspective, it can further be categorized into end-to-end data protection (privacy) during the computation process and authentication and traceability (public) after computation. My collaborators and I primarily focus on authentication and traceability of intelligent model computations post-inference, aiming to protect the legitimate interests of all parties involved.
- **Collaborative Paper:** DERMARK: A Dynamic, Efficient, and Robust Multi-bit Watermark for Large Language Models.


# 🌏 Service

- Teaching Assistant: Served as a Teaching Assistant for the graduate-level course "Computer Applied Mathematics" at USTC in 2023.
- Volunteer Activities: Volunteered for the ACM TURC, as well as for various events such as the college’s evening parties, among others.


# 💫 Hobbies

Beyond my research work, I also have a passion for **photography** (Nikon fan), music (singing and guitar), and gaming (PC & Switch)—feel free to reach out if you'd like to chat about any of these! I'm also fond of hosting and have had the pleasure of hosting two university-level events, one at the college level, and two in the lab. It's always a joy to meet new people!
I love experimenting with various quirky coding projects—coding things I enjoy is a true pleasure, and the sense of accomplishment constantly drives me to explore what comes next.
Work hard, but also enjoy life. ✨

<div style="width:100%; margin:0 auto;">
    <div style="display:flex; width:100%; margin-bottom:10px;">
      <!-- 第一张图片 -->
      <div style="flex:0 0 50%; margin-right:2%;">
        <!-- 图片裁剪容器：利用 padding-top 设置固定比例 -->
        <div style="position:relative; width:100%; overflow:hidden; padding-top:55%;">
          <a href="/images/IMG70.jpg" target="_blank">
          <img src="../images/IMG70_small.jpg" alt="photography" style="position:absolute; top:0; left:0; width:100%; height:100%; object-fit:cover;"> </a>
        </div>
      </div>
      <!-- 第二张图片 -->
      <div style="flex:0 0 23%; margin-right:2%;">
        <div style="position:relative; width:100%; overflow:hidden; padding-top:120%;">
          <a href="/images/IMG69.jpg" target="_blank">
          <img src="../images/IMG69_small.jpg" alt="photography" style="position:absolute; top:0; left:0; width:100%; height:100%; object-fit:cover;"></a>
        </div>
      </div>
    <!-- 第三张图片 -->
      <div style="flex:0 0 23%">
        <div style="position:relative; width:100%; overflow:hidden; padding-top:120%;">
          <a href="/images/IMG71.jpg" target="_blank">
          <img src="./images/IMG71_small.jpg" alt="photography" style="position:absolute; top:0; left:0; width:100%; height:100%; object-fit:cover;"></a>
        </div>
      </div>
    </div>


  </div>
