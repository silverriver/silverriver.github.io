---
layout: archive
title: "Datasets"
permalink: /datasets/
author_profile: true
---

{% include base_path %}

You can find some interesting datasets for dialogue systems on this page.

-----

## 1. LCCC

### About

The LCCC (Large-scale Cleaned Chinese Conversation) corpus (LCCC) is a cleaned open-domain dialogue dataset.
A strict data cleaning pipeline is designed to ensure the quality of LCCC.
It contains 7,273,804 single-turn dialogues and 4,733,955 multi-turn dialogues.
You can find more details from this paper: [A Large-Scale Chinese Short-Text Conversation Dataset](https://arxiv.org/abs/2008.03946).

### Download

You can find the download link of LCCC from this [repo](https://github.com/thu-coai/CDial-GPT) or huggingface [Dataset Zoo](https://huggingface.co/datasets/silver/lccc).

### Reference

Please cite the following paper if you find this dataset useful:

```bibtex
@inproceedings{wang2020large,
  title     = {A Large-Scale Chinese Short-Text Conversation Dataset},
  author    = {Wang, Yida and Ke, Pei and Zheng, Yinhe and Huang, Kaili and Jiang, Yong and Zhu, Xiaoyan and Huang, Minlie},
  booktitle = {NLPCC},
  year      = {2020}
}
```

## 2. PersonalDialog

### About

The PersonalDialog dataset is a large-scale multi-turn Chinese dialogue dataset containing various traits from a large number of speakers. The whole dataset consists of 20.83M sessions and 56.25M utterances from 8.47M speakers. Each utterance is associated with a speaker marked with traits like Age, Gender, Location, Interest Tags, etc. Several anonymization schemes are designed to protect the privacy of each speaker. This large-scale dataset will facilitate not only the study of personalized dialogue generation but also other researches on sociolinguistics or social science.
You can find more details from this paper: [Personalized Dialogue Generation with Diversified Traits](https://arxiv.org/abs/1901.09672)

 <img src="/images/PersonalDialog.jpg" width = "400" alt="A Sample Dialogue from PersonaDilaog" align=center />

A sample Dialogue from PersonaDilaog

### Download

The PersonalDialog dataset contains various persona-related information collected from the web.
You can find the download link of PersonalDialog [here](https://github.com/silverriver/PersonalDilaog).

### Reference

Please cite the following papers if you find this dataset useful:

```bibtex
@article{zheng2019personalized,
  title   = {Personalized dialogue generation with diversified traits},
  author  = {Zheng, Yinhe and Chen, Guanyi and Huang, Minlie and Liu, Song and Zhu, Xuan},
  journal = {arXiv preprint arXiv:1901.09672},
  year    = {2019}
}

@inproceedings{zheng2020pre,
  title     = {A pre-training based personalized dialogue generation model with persona-sparse data},
  author    = {Zheng, Yinhe and Zhang, Rongsheng and Huang, Minlie and Mao, Xiaoxi},
  booktitle = {Proceedings of the AAAI Conference on Artificial Intelligence},
  volume    = {34},
  number    = {05},
  pages     = {9693--9700},
  year      = {2020}
}
```

## 3. MMChat

### About

MMCHAT contains image-grounded dialogues collected from real conversations on social media.
Specifically, MMCHAT contains 120.84K sessions of open-domain dialogues
(filtered out of 32.4M sessions of raw dialogues) and 204.32K corresponding images.

 <img src="/images/mmchat.jpg" width = "400" alt="A Sample Dialogue from MMChat" align=center />

A sample Dialogue from MMChat

### Download

You can find the download link of MMChat from this [repo](https://github.com/silverriver/MMChat).

### Reference

Please cite the following paper if you find this dataset useful:

```bibtex
@inproceedings{zheng2022MMChat,
  author    = {Zheng, Yinhe and Chen, Guanyi and Liu, Xin and Sun, Jian},
  title     = {MMChat: Multi-Modal Chat Dataset on Social Media},
  booktitle = {Proceedings of The 13th Language Resources and Evaluation Conference},
  year      = {2022},
  publisher = {European Language Resources Association},
}
```
