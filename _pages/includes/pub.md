# 📝 Selected Publications

> (*: Equal Contribution)

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NDSS 2025</div><img src='./images/Raconteur.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Raconteur : A Knowledgeable, Insightful, and Portable LLM-Powered Shell Command Explainer](https://arxiv.org/abs/2409.02074) Jiangyi Deng<sup>*</sup>, **Xinfeng Li<sup>*</sup>**, Yanjiao Chen, Yijie Bai, Haiqin Weng, Yan Liu, Tao Wei, Wenyuan Xu. In Proceedings of Network and Distributed System Security Symposium, **NDSS 2025** (CCF-A, Big4) [[Website, Dataset](https://raconteur-ndss.github.io/)]

Raconteur is the first tool using Large Language Models (LLMs) to explain shell commands clearly. It provides detailed insights into command functions and purposes, aligning with MITRE ATT&CK standards. Equipped with professional cybersecurity knowledge, Raconteur delivers accurate explanations. A documentation retriever helps understand new commands. Tested extensively, Raconteur offers unique insights, helping security analysts better understand command intentions.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM CCS 2024</div><img src='./images/SafeGen.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[SafeGen: Mitigating Sexually Explicit Content Generation in Text-to-Image Models](https://arxiv.org/abs/2404.06666) **Xinfeng Li**, Yuchen Yang, Jiangyi Deng, Chen Yan, Yanjiao Chen, Xiaoyu Ji, Wenyuan Xu. In Proceedings of ACM Conference on Computer and Communications Security, **CCS 2024** (CCF-A, Big4) [[Code](https://github.com/LetterLiGo/SafeGen_CCS2024)][[Pretrained Weights](https://huggingface.co/LetterJohn/SafeGen-Pretrained-Weights)][[Paper](https://letterligo.github.io/paper/SafeGen_v1.pdf)]

As T2I technologies advance, their misuse to generate sexually explicit content has become a major concern. SafeGen effectively mitigates this by removing any explicit visual representations from the model, making it safe regardless of the adversarial text input, outperforming eight other protection approaches. SafeGen adjusts the model's visual self-attention layers to ensure that the high-quality production of benign images is not compromised. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM CCS 2024</div><img src='./images/SafeEar.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[SafeEar: Content Privacy-Preserving Audio Deepfake Detection](https://letterligo.github.io/SafeEar/) **Xinfeng Li**, Kai Li, Yifan Zheng, Chen Yan, Xiaoyu Ji, Wenyuan Xu. To appear in Proceedings of ACM Conference on Computer and Communications Security, **CCS 2024** (CCF-A, Big4) [[Website](https://letterligo.github.io/SafeEar/)][[Dataset](https://zenodo.org/records/11229569)][[Code](https://github.com/LetterLiGo/SafeEar)].

To our knowledge, SafeEar is the first content privacy-preserving audio deepfake detection framework. Since audio deepfakes and user privacy concerns have been increasingly significant societal issues, we demonstrate how to achieve reliable deepfake detection while preventing both machine and human adversaries from eavesdropping on sensitive user speech content. To facilitate future research, we also develop a comprehensive multilingual deepfake datasets (more than 1,500,000 genuine & deepfake audio samples) using advanced TTS/VC techniques.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NDSS 2024</div><img src='./images/Vrifle.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Inaudible Adversarial Perturbation: Manipulating the Recognition of User Speech in Real Time](https://arxiv.org/abs/2308.01040), **Xinfeng Li**, Chen Yan, Xuancun Lu, Xiaoyu Ji, Wenyuan Xu., In Proceedings of Network and Distributed System Security Symposium, **NDSS 2024** (CCF-A, Big4) [[Website1](https://sites.google.com/view/vrifle)], [[Website2](https://zjushine.github.io/VRIFLE/)], [[Code](https://github.com/LetterLiGo/Adversarial_Audio_Attack-VRifle)]

<!-- [**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->
- First completely inaudible adversarial perturbation attacks, increasing the attack range to 10 meters away.
- First attempt on ultrasound transformation modeling.
- Significant improvement of attack distances, universality, and stealthiness compared with prior adversarial example attacks.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">USENIX 2023</div><img src='images/normdetect.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Learning Normality is Enough: A Software-based Mitigation against the Inaudible Voice Attacks](https://www.usenix.org/conference/usenixsecurity23/presentation/li-xinfeng), **Xinfeng Li**, Xiaoyu Ji, Chen Yan, Chaohao Li, Yichen Li, Zhenning Zhang, Wenyuan Xu.,
In Proceedings of 32nd **USENIX Security 2023** (CCF-A, Big4) [[Website](https://sites.google.com/view/normdetect)]
<!-- [**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->
- Unsupervised software-based mitigation that can instantly protect miscallenous legacy devices.
- Universal detection performance demonstrated on a wide range of devices.
</div>
</div>

- [Neural Invisibility Cloak: Concealing Adversary in Images via Compromised AI-driven Image Signal Processing](https://www.usenix.org/conference/usenixsecurity25/presentation/zhu-wenjun), Wenjun Zhu, Xiaoyu Ji, **Xinfeng Li**, Qihang Chen, Kun Wang, Xinyu Li, Ruoyan Xu, and Wenyuan Xu, Zhejiang University. **USENIX Security 2025** (CCF-A, Big4)

- [LightAntenna: Characterizing the Limits of Fluorescent Lamp-Induced Electromagnetic Interference](https://www.ndss-symposium.org/ndss-paper/lightantenna-characterizing-the-limits-of-fluorescent-lamp-induced-electromagnetic-interference/), Fengchen Yang, Wenze Cui, **Xinfeng Li**, Chen Yan, Xiaoyu Ji, Wenyuan Xu. **NDSS 2025** (CCF-A, Big4)

- [Legilimens: Practical and Unified Content Moderation for Large Language Model Services](), Jialin Wu, Jiangyi Deng, Shengyuan Pang, Yanjiao Chen, Jiayang Xu, **Xinfeng Li**, Wenyuan Xu. **ACM CCS 2024** (CCF-A, Big4) [[Code](https://github.com/lin000001/Legilimens)]

- [Scoring Metrics of Assessing Voiceprint Distinctiveness based on Speech Content and Rate](), Ruiwen He, Yushi Cheng, Junning Ze, **Xinfeng Li**, Xiaoyu Ji, Wenyuan Xu. Transcations on Dependable and Secure Computing, **TDSC 2024** (CCF-A)

- [Inaudible Adversarial Perturbation: Manipulating the Recognition of User Speech in Real Time](https://arxiv.org/abs/2308.01040), **Xinfeng Li**, Chen Yan, Xuancun Lu, Xiaoyu Ji, Wenyuan Xu., In Proceedings of Network and Distributed System Security Symposium, **NDSS 2024** (CCF-A, Big4) [[Google Site](https://sites.google.com/view/vrifle)], [[Website](https://zjushine.github.io/VRIFLE/)], [[Code](https://github.com/LetterLiGo/Adversarial_Audio_Attack-VRifle)]

- [Detecting Inaudible Voice Commands via Acoustic Attenuation by Multi-channel Microphones](), Xiaoyu Ji, Guoming Zhang, **Xinfeng Li**, Gang Qu, Xiuzhen Cheng, Wenyuan Xu. Transcations on Dependable and Secure Computing, **TDSC 2023** (CCF-A)

- [The Silent Manipulator: Practical and Inaudible Backdoor Attack against Speech Recognition Systems](https://dl.acm.org/doi/10.1145/3581783.3613843), Zhicong Zheng, **Xinfeng Li**, Chen Yan, Xiaoyu Ji, Wenyuan Xu., ACM multimedia **MM 2023** (CCF-A)

- [Enrollment-stage Backdoor Attacks on Speaker Recognition Systems via Adversarial Ultrasound](https://arxiv.org/abs/2306.16022), **Xinfeng Li**, Junning Ze, Chen Yan, Yushi Cheng, Xiaoyu Ji, Wenyuan Xu., IEEE Internet of Things Journal, **IoT-J** (SCI, JCR-1)

- [Towards Pitch-Insensitive Speaker Verification via Soundfield](https://www.researchgate.net/publication/371918855_Towards_Pitch-Insensitive_Speaker_Verification_via_Soundfield), **Xinfeng Li**, Zhicong Zheng, Chen Yan, Chaohao Li, Xiaoyu Ji, Wenyuan Xu., IEEE Internet of Things Journal, **IoT-J** (SCI, JCR-1)

- [Learning Normality is Enough: A Software-based Mitigation against the Inaudible Voice Attacks](https://www.usenix.org/conference/usenixsecurity23/presentation/li-xinfeng), **Xinfeng Li**, Xiaoyu Ji, Chen Yan, Chaohao Li, Yichen Li, Zhenning Zhang, Wenyuan Xu.,
In Proceedings of 32nd **USENIX Security 2023** (CCF-A, Big4) [[Website](https://sites.google.com/view/normdetect)]

- [UltraBD: Backdoor Attack against Automatic Speaker Verification Systems via Adversarial Ultrasound](https://ieeexplore.ieee.org/document/10078010), **Junning Ze**, **Xinfeng Li**, Yushi Cheng, Xiaoyu Ji, Wenyuan Xu., In Proceedings of 2022 IEEE 28th International Conference on Parallel and Distributed Systems **ICPADS 2022** (CCF-C) [[Extended Version](https://arxiv.org/abs/2306.16022)]

- [”OK, Siri” or ”Hey, Google”: Evaluating Voiceprint Distinctiveness via Content-based PROLE Score](https://www.usenix.org/conference/usenixsecurity22/presentation/he-ruiwen), Ruiwen He, Xiaoyu Ji, **Xinfeng Li**, Yushi Cheng, Wenyuan Xu., In Proceedings of 31st **USENIX Security 2022** (CCF-A, Big4) [[Website, Our Interactive Demo](https://sites.google.com/view/voiceprint-sec)]

- [EarArray: Defending against DolphinAttack via Acoustic Attenuation](https://www.ndss-symposium.org/ndss-paper/eararray-defending-against-dolphinattack-via-acoustic-attenuation/), Guoming Zhang, Xiaoyu Ji, **Xinfeng Li**, Gang Qu, Wenyuan Xu., In Proceedings of Network and Distributed System Security Symposium, **NDSS 2021** (CCF-A, Big4) 

