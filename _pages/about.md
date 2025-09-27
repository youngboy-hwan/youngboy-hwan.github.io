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

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. Suspendisse condimentum, libero vel tempus mattis, risus risus vulputate libero, elementum fermentum mi neque vel nisl. Maecenas facilisis maximus dignissim. Curabitur mattis vulputate dui, tincidunt varius libero luctus eu. Mauris mauris nulla, scelerisque eget massa id, tincidunt congue felis. Sed convallis tempor ipsum rhoncus viverra. Pellentesque nulla orci, accumsan volutpat fringilla vitae, maximus sit amet tortor. Aliquam ultricies odio ut volutpat scelerisque. Donec nisl nisl, porttitor vitae pharetra quis, fringilla sed mi. Fusce pretium dolor ut aliquam consequat. Cras volutpat, tellus accumsan mattis molestie, nisl lacus tempus massa, nec malesuada tortor leo vel quam. Aliquam vel ex consectetur, vehicula leo nec, efficitur eros. Donec convallis non urna quis feugiat.

My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>).


# 🔥 News
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2019</div><img src='images/fs.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[FastSpeech: Fast, Robust and Controllable Text to Speech](https://papers.nips.cc/paper/8580-fastspeech-fast-robust-and-controllable-text-to-speech.pdf) \\
**Yi Ren**, Yangjun Ruan, Xu Tan, Tao Qin, Sheng Zhao, Zhou Zhao, Tie-Yan Liu

[**Project**](https://speechresearch.github.io/fastspeech/) <strong><span class='show_paper_citations' data='4FA6C0AAAAAJ:qjMakFHDy7sC'></span></strong>

- FastSpeech is the first fully parallel end-to-end speech synthesis model.
- **Academic Impact**: This work is included by many famous speech synthesis open-source projects, such as [ESPNet ![](https://img.shields.io/github/stars/espnet/espnet?style=social)](https://github.com/espnet/espnet). Our work are promoted by more than 20 media and forums, such as [机器之心](https://mp.weixin.qq.com/s/UkFadiUBy-Ymn-zhJ95JcQ)、[InfoQ](https://www.infoq.cn/article/tvy7hnin8bjvlm6g0myu).
- **Industry Impact**: FastSpeech has been deployed in [Microsoft Azure TTS service](https://techcommunity.microsoft.com/t5/azure-ai/neural-text-to-speech-extends-support-to-15-more-languages-with/ba-p/1505911) and supports 49 more languages with state-of-the-art AI quality. It was also shown as a text-to-speech system acceleration example in [NVIDIA GTC2020](https://resources.nvidia.com/events/GTC2020s21420).
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2021</div><img src='images/fs2.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[FastSpeech 2: Fast and High-Quality End-to-End Text to Speech](https://arxiv.org/abs/2006.04558) \\
**Yi Ren**, Chenxu Hu, Xu Tan, Tao Qin, Sheng Zhao, Zhou Zhao, Tie-Yan Liu

[**Project**](https://speechresearch.github.io/fastspeech2/) <strong><span class='show_paper_citations' data='4FA6C0AAAAAJ:LkGwnXOMwfcC'></span></strong>
  - This work is included by many famous speech synthesis open-source projects, such as [PaddlePaddle/Parakeet ![](https://img.shields.io/github/stars/PaddlePaddle/PaddleSpeech?style=social)](https://github.com/PaddlePaddle/PaddleSpeech), [ESPNet ![](https://img.shields.io/github/stars/espnet/espnet?style=social)](https://github.com/espnet/espnet) and [fairseq ![](https://img.shields.io/github/stars/pytorch/fairseq?style=social)](https://github.com/pytorch/fairseq).
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2024</div><img src='images/mega.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Mega-TTS 2: Boosting Prompting Mechanisms for Zero-Shot Speech Synthesis](https://openreview.net/forum?id=mvMI3N4AvD) \\ 
Ziyue Jiang, Jinglin Liu, **Yi Ren**, et al.

[**Project**](https://boostprompt.github.io/boostprompt/) 
  - This work has been deployed on many TikTok products.
  - Advandced zero-shot voice cloning model.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2022</div><img src='images/diffsinger.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[DiffSinger: Singing Voice Synthesis via Shallow Diffusion Mechanism](https://arxiv.org/abs/2105.02446) \\
Jinglin Liu, Chengxi Li, **Yi Ren**, Feiyang Chen, Zhou Zhao

- Many [video demos](https://www.bilibili.com/video/BV1be411N7JA) created by the [DiffSinger community](https://github.com/openvpi) are released.
- DiffSinger was introduced in [a very popular video](https://www.bilibili.com/video/BV1uM411t7ZJ) (1600k+ views) on Bilibili!

- [**Project**](https://diffsinger.github.io/) \| [![](https://img.shields.io/github/stars/NATSpeech/NATSpeech?style=social&label=DiffSpeech Stars)](https://github.com/NATSpeech/NATSpeech) \| [![](https://img.shields.io/github/stars/MoonInTheRiver/DiffSinger?style=social&label=DiffSinger Stars)](https://github.com/MoonInTheRiver/DiffSinger) \| [![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-blue?label=Demo)](https://huggingface.co/spaces/NATSpeech/DiffSpeech)
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2021</div><img src='images/portaspeech.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[PortaSpeech: Portable and High-Quality Generative Text-to-Speech](https://arxiv.org/abs/2109.15166) \\
**Yi Ren**, Jinglin Liu, Zhou

[**Project**](https://portaspeech.github.io/) \| [![](https://img.shields.io/github/stars/NATSpeech/NATSpeech?style=social&label=Code+Stars)](https://github.com/NATSpeech/NATSpeech) \| [![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-blue?label=Demo)](https://huggingface.co/spaces/NATSpeech/PortaSpeech)
</div>
</div>

- `AAAI 2024` [Emotion Rendering for Conversational Speech Synthesis with Heterogeneous Graph-Based Context Modeling](https://arxiv.org/abs/2312.11947), Rui Liu, Yifan Hu, **Yi Ren**, et al. [![](https://img.shields.io/github/stars/walker-hyf/ECSS?style=social&label=Code+Stars)](https://github.com/walker-hyf/ECSS)
- <p> <code>ICML 2023</code> DDDDo: Text-To-Audio ... [Make-An-Audio: Text-To-Audio Generation with Prompt-Enhanced Diffusion Models](https://text-to-audio.github.io/paper.pdf), Rongjie Huang, Jiawei Huang, Dongchao Yang, **Yi Ren**, et al. </p>
- ``ACL 2023`` [CLAPSpeech: Learning Prosody from Text Context with Contrastive Language-Audio Pre-Training](), Zhenhui Ye, Rongjie Huang, **Yi Ren**, et al.
- ``ACL 2023`` [FluentSpeech: Stutter-Oriented Automatic Speech Editing with Context-Aware Diffusion Models](), Ziyue Jiang, Qian Yang, Jialong Zuo, Zhenhui Ye, Rongjie Huang, **Yi Ren** and Zhou Zhao
- ``ACL 2023`` [Revisiting and Incorporating GAN and Diffusion Models in High-Fidelity Speech Synthesis](), Rongjie Huang, **Yi Ren**, Ziyue Jiang, et al.
- ``ACL 2023`` [Improving Prosody with Masked Autoencoder and Conditional Diffusion Model For Expressive Text-to-Speech](), Rongjie Huang, Chunlei Zhang, **Yi Ren**, et al.
- `ICLR 2023` [Bag of Tricks for Unsupervised Text-to-Speech](https://openreview.net/forum?id=SbR9mpTuBn), **Yi Ren**, Chen Zhang, Shuicheng Yan
- `INTERSPEECH 2023` [StyleS2ST: zero-shot style transfer for direct speech-to-speech translation](https://arxiv.org/abs/2305.17732), Kun Song, **Yi Ren**, Yi Lei, et al.
- `INTERSPEECH 2023` [GenerTTS: Pronunciation Disentanglement for Timbre and Style Generalization in Cross-Lingual Text-to-Speech](https://arxiv.org/abs/2306.15304), Yahuan Cong, Haoyu Zhang, Haopeng Lin, Shichao Liu, Chunfeng Wang, **Yi Ren**, et al.
- `NeurIPS 2022` [Dict-TTS: Learning to Pronounce with Prior Dictionary Knowledge for Text-to-Speech](), Ziyue Jiang, Zhe Su, Zhou Zhao, Qian Yang, **Yi Ren**, et al. [![](https://img.shields.io/github/stars/Zain-Jiang/Dict-TTS?style=social&label=Code+Stars)](https://github.com/Zain-Jiang/Dict-TTS)
- `NeurIPS 2022` [GenerSpeech: Towards Style Transfer for Generalizable Out-Of-Domain Text-to-Speech](), Rongjie Huang, **Yi Ren**, et al.

# 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 📖 Educations
- *2019.06 - 2022.04 (now)*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2015.09 - 2019.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)

# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China.