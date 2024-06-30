# MME: A Comprehensive Evaluation Benchmark for Multimodal Large Language Models

<img src="./images/dataset.png" width="96%" height="96%">

> Multimodal Large Language Model (MLLM) relies on the powerful LLM to perform multimodal tasks, showing amazing emergent abilities in recent studies, such as writing poems based on an image. However, it is difficult for these case studies to fully reflect the performance of MLLM, lacking a comprehensive evaluation. In this paper, we fill in this blank, presenting the first MLLM Evaluation benchmark MME. It measures both perception and cognition abilities on a total of 14 subtasks. In order to avoid data leakage that may arise from direct use of public datasets for evaluation, the annotations of instruction-answer pairs are all manually designed. The concise instruction design allows us to fairly compare MLLMs, instead of struggling in prompt engineering. Besides, with such an instruction, we can also easily carry out quantitative statistics. A total of 50+ advanced MLLMs are comprehensively evaluated on our MME, which not only suggests that existing MLLMs still have a large room for improvement, but also reveals the potential directions for the subsequent model optimization.




## Our MLLM works

🔥🔥🔥 **A Survey on Multimodal Large Language Models**  
**[Project Page [This Page]](https://github.com/BradyFU/Awesome-Multimodal-Large-Language-Models)** | **[Paper](https://arxiv.org/pdf/2306.13549.pdf)**

The first survey for Multimodal Large Language Models (MLLMs). :sparkles: </div>  

Welcome to add WeChat ID (wmd_ustc) to join our MLLM communication group! :star2: </div>


---

🔥🔥🔥 **Video-MME: The First-Ever Comprehensive Evaluation Benchmark of Multi-modal LLMs in Video Analysis**  
<p align="center">
    <img src="./images/videomme.jpg" width="100%" height="100%">
</p>

<font size=7><div align='center' > [[🍎 Project Page](https://video-mme.github.io/)] [[📖 arXiv Paper](https://arxiv.org/pdf/2405.21075)] [[📊 Dataset](https://github.com/BradyFU/Video-MME?tab=readme-ov-file#-dataset)][[🏆 Leaderboard](https://video-mme.github.io/home_page.html#leaderboard)]  </div></font>

[2024.06.03] We are very proud to launch Video-MME, the first-ever comprehensive evaluation benchmark of MLLMs in Video Analysis! 🌟  

It applies to both <b>image MLLMs</b>, i.e., generalizing to multiple images, and <b>video MLLMs</b>. Our leaderboard involes SOTA models like Gemini 1.5 Pro, GPT-4o, GPT-4V, LLaVA-NeXT-Video, InternVL-Chat-V1.5, and Qwen-VL-Max. 🌟  

It includes both <b>short- (< 2min)</b>, <b>medium- (4min\~15min)</b>, and <b>long-term (30min\~60min)</b> videos, ranging from <b>11 seconds to 1 hour</b>. ✨ 

<b>All data are newly collected and annotated by humans, not from any existing video dataset</b>. ✨ 

---

🔥🔥🔥 **MME: A Comprehensive Evaluation Benchmark for Multimodal Large Language Models**  
**[Project Page [Leaderboards]](https://github.com/BradyFU/Awesome-Multimodal-Large-Language-Models/tree/Evaluation)** | **[Paper](https://arxiv.org/pdf/2306.13394.pdf)** | :black_nib: **[Citation](./images/bib_mme.txt)**

The first comprehensive evaluation benchmark for MLLMs. Now the leaderboards include **50+** advanced models, such as Qwen-VL-Max, Gemini Pro, and GPT-4V. :sparkles:

If you want to add your model in our leaderboards, please feel free to email bradyfu24@gmail.com. We will update the leaderboards in time. :sparkles:

<details><summary>Download MME :star2::star2: </summary>

The benchmark dataset is collected by Xiamen University for academic research only. You can email yongdongluo@stu.xmu.edu.cn to obtain the dataset, according to the following requirement. 

**Requirement**: A real-name system is encouraged for better academic communication. Your email suffix needs to match your affiliation, such as xx@stu.xmu.edu.cn and Xiamen University. Otherwise, you need to explain why. Please include the information bellow when sending your application email.

```
Name: (tell us who you are.)
Affiliation: (the name/url of your university or company)
Job Title: (e.g., professor, PhD, and researcher)
Email: (your email address)
How to use: (only for non-commercial use)
```

</details>

---

🔥🔥🔥 **Woodpecker: Hallucination Correction for Multimodal Large Language Models**  
**[Paper](https://arxiv.org/pdf/2310.16045.pdf)** | **[Source Code![Star](https://img.shields.io/github/stars/BradyFU/Woodpecker.svg?style=social&label=Star)](https://github.com/BradyFU/Woodpecker)**

The first work to correct hallucinations in MLLMs. :sparkles:

---

🔥🔥🔥 **A Challenger to GPT-4V? Early Explorations of Gemini in Visual Expertise**  
**[Paper](https://arxiv.org/pdf/2312.12436.pdf)**

The first technical report for <b>Gemini vs GPT-4V</b>. A total of <b>128 pages</b>. Completed within one week of the Gemini API opening. :star2:

---

<br> **📑 If you find our projects helpful to your research, please consider citing:** <br>
```
@article{fu2023mme,
  title={MME: A Comprehensive Evaluation Benchmark for Multimodal Large Language Models},
  author={Fu, Chaoyou and Chen, Peixian and Shen, Yunhang and Qin, Yulei and Zhang, Mengdan and Lin, Xu and Yang, Jinrui and Zheng, Xiawu and Li, Ke and Sun, Xing and others},
  journal={arXiv preprint arXiv:2306.13394},
  year={2023}
}

@article{fu2024video,
  title={Video-MME: The First-Ever Comprehensive Evaluation Benchmark of Multi-modal LLMs in Video Analysis},
  author={Fu, Chaoyou and Dai, Yuhan and Luo, Yondong and Li, Lei and Ren, Shuhuai and Zhang, Renrui and Wang, Zihan and Zhou, Chenyu and Shen, Yunhang and Zhang, Mengdan and others},
  journal={arXiv preprint arXiv:2405.21075},
  year={2024}
}

@article{yin2023survey,
  title={A survey on multimodal large language models},
  author={Yin, Shukang and Fu, Chaoyou and Zhao, Sirui and Li, Ke and Sun, Xing and Xu, Tong and Chen, Enhong},
  journal={arXiv preprint arXiv:2306.13549},
  year={2023}
}

@article{yin2023woodpecker,
  title={Woodpecker: Hallucination correction for multimodal large language models},
  author={Yin, Shukang and Fu, Chaoyou and Zhao, Sirui and Xu, Tong and Wang, Hao and Sui, Dianbo and Shen, Yunhang and Li, Ke and Sun, Xing and Chen, Enhong},
  journal={arXiv preprint arXiv:2310.16045},
  year={2023}
}

@article{fu2023challenger,
  title={A challenger to gpt-4v? early explorations of gemini in visual expertise},
  author={Fu, Chaoyou and Zhang, Renrui and Lin, Haojia and Wang, Zihan and Gao, Timin and Luo, Yongdong and Huang, Yubo and Zhang, Zhengye and Qiu, Longtian and Ye, Gaoxiang and others},
  journal={arXiv preprint arXiv:2312.12436},
  year={2023}
}
```


---

# News 🚀

1. [06-06] Thanks to [**CMRI**](https://cmri.chinamobile.com/), [**JT-VL-Chat-V1.0**](https://github.com/jiutiancv/JT-VL-Chat) is added in MME. 
2. [05-27] Thanks to [**Junbo Cui**](https://scholar.google.com.hk/citations?view_op=list_works&hl=zh-CN&user=rKPAFfYAAAAJ), [**MiniCPM-Llama3-V 2.5**](https://github.com/OpenBMB/MiniCPM-V) joins MME. 
3. [05-18] Thanks to [**Chunyu Xie**](https://scholar.google.com/citations?user=SxpPPuQAAAAJ&hl=zh-CN), [**360VL**](https://github.com/360CVGroup/360VL?tab=readme-ov-file) is incorporated into MME. 
4. [04-27] Thanks to [**Zhe Chen**](https://scholar.google.com.hk/citations?user=j1rq_lYAAAAJ&hl=zh-CN&oi=sra), we welcome a new member [**InternVL-Chat-V1.5**](https://arxiv.org/pdf/2404.16821). 
5. [04-15] Thanks to [**Junbo Cui**](https://scholar.google.com.hk/citations?view_op=list_works&hl=zh-CN&user=rKPAFfYAAAAJ), [**MiniCPM-V-2**](https://github.com/OpenBMB/MiniCPM/#minicpm-v) is added in MME. 
6. [04-10] Thanks to [**Wenqiao Zhang**](https://scholar.google.com.hk/citations?user=XBbuP9YAAAAJ&hl=zh-CN&oi=sra), [**HyperLLaVA**](https://arxiv.org/pdf/2403.13447.pdf) joins our leaderboards. 
7. [03-14] Thanks to [**Muyang He**](https://scholar.google.com.hk/citations?user=Q0Xn7i4AAAAJ&hl=zh-CN&oi=sra), [**Bunny-3B**](https://github.com/BAAI-DCAI/Bunny) takes part in MME. 
8. [02-23] Thanks to [**Jingyu Liu**](https://scholar.google.com/citations?hl=en&tzom=-480&user=RCxy7UQAAAAJ), [**ChatTruth-7B**](https://huggingface.co/mingdali/ChatTruth-7B) is added to MME. 
9. [02-07] Thanks to [**TsinghuaNLP**](https://github.com/OpenBMB), [**MiniCPM**](https://github.com/OpenBMB/MiniCPM/#minicpm-v) and [**OmniLMM**](https://github.com/OpenBMB/MiniCPM/#minicpm-v) are incorporated into our leaderboards. 
10. [02-05] Thanks to [**Haotian Liu**](https://hliu.cc/), [**LLaVA-1.6**](https://llava-vl.github.io/blog/2024-01-30-llava-1-6/) is added to MME. 
11. [02-05] Thanks to [**Bin Lin**](https://scholar.google.com.hk/citations?user=GCOVDKoAAAAJ&hl=zh-CN&oi=sra), [**MoE-LLaVA**](https://github.com/PKU-YuanGroup/MoE-LLaVA) joins MME. 
12. [02-05] Thanks to [**Weihan Wang**](https://scholar.google.com.hk/citations?user=UaxGkIwAAAAJ&hl=zh-CN&oi=ao) and [**Wenyi Hong**](https://scholar.google.com.hk/citations?user=JSEzrlwAAAAJ&hl=zh-CN&oi=ao), [**CogVLM**](https://arxiv.org/pdf/2311.03079.pdf) and [**CogAgent**](https://arxiv.org/pdf/2312.08914.pdf) take part in MME. 
13. [01-25] Thanks to [**Shijie Wang**](https://scholar.google.com.hk/citations?hl=zh-CN&user=DuAqyTwAAAAJ), we welcome a new member [**Qwen-VL-Max**](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start). 
14. [01-22] Thanks to [**Xiaoyi Dong**](https://scholar.google.com/citations?user=FscToE0AAAAJ&hl=en), [**InternLM-XComposer2-VL**](https://github.com/InternLM/InternLM-XComposer) joins our leaderboards. 

<details><summary> <b>2023</b> </summary>

**[2023-12]** 

1. [12-31] Thanks to [**Dian Li**](https://scholar.google.com/citations?hl=zh-CN&user=rF7HU94AAAAJ), [**PureMM**](https://github.com/Q-MM/PureMM) takes part in our leaderboards (update in 2024-01-14 and 2024-01-21). 
2. [12-31] Thanks to Yilin Ma and [**Min Xu**](http://faculty.dlut.edu.cn/minxu/zh_CN/index.htm), [**RBDash**](https://github.com/RBDash-Team/RBDash) is added in MME. 
3. [12-18] Thanks to [**Zihan Wang**](https://github.com/hanhanHANS), our leaderboards usher in [**Gemini Pro**](https://storage.googleapis.com/deepmind-media/gemini/gemini_1_report.pdf).
4. [12-18] Thanks to [**Jinze Bai**](https://github.com/jinze1994), a new model [**Qwen-VL-Plus**](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start) is added in MME.
5. [12-18] Thanks to [**Junbum Cha**](https://scholar.google.com.hk/citations?user=Py2gKnAAAAAJ&hl=zh-CN&oi=ao), [**Honeybee**](https://arxiv.org/pdf/2312.06742.pdf) joins our leaderboards.
6. [12-12] Thanks to [**Yuliang Liu**](https://github.com/Yuliang-Liu), [**Monkey-Chat**](https://github.com/Yuliang-Liu/Monkey) takes part in MME. 
7. [12-12] Thanks to [**Junkun Yuan**](https://scholar.google.com.hk/citations?hl=zh-CN&user=j3iFVPsAAAAJ&view_op=list_works&sortby=pubdate), we welcome a new member [**AGILMM**](https://github.com/AIResearchEnthusiast/AGILMM). 
8. [12-01] Thanks to [**Cheng Wen**](https://scholar.google.com/citations?user=9MLB3s8AAAAJ&hl=zh-CN), [**BELLE-VL**](https://huggingface.co/BELLE-2/BELLE-VL) is added to our leaderboards. 
9. [12-01] Thanks to [**PCI Research**](https://www.pcitech.com/), [**TransCore-M**](https://github.com/PCIResearch/TransCore-M) joins MME. 


**[2023-11]** 

1. [11-24] Thanks to [**Xiaoyi Dong**](https://scholar.google.com/citations?user=FscToE0AAAAJ&hl=en), we add [**ShareGPT4V**](https://github.com/InternLM/InternLM-XComposer/tree/main/projects/ShareGPT4V) to our leaderboards. 
2. [11-24] Thanks to [**Muyang He**](https://scholar.google.com/citations?hl=en&user=Q0Xn7i4AAAAJ), [**DataOptim**](https://github.com/BAAI-DCAI/DataOptim) joins MME. 
3. [11-24] Thanks to [**Zifei Shan**](https://scholar.google.com/citations?user=DGIdpTwAAAAJ&hl=en&oi=ao), [**Kanva**](https://github.com/llp1992/Kanva) is added. 
4. [11-21] Thanks to [**Junke Wang**](https://scholar.google.com.hk/citations?user=qQuxuo0AAAAJ&hl=zh-CN&oi=ao), [**LVIS-INSTRUCT4V**](https://arxiv.org/pdf/2311.07574.pdf) is added to our MME.
5. [11-18] Thanks to [**Zhenbo Luo**](https://dblp.org/pid/152/8206.html), our leaderboards welcome a new member [**CVLM**](https://github.com/buptlihang/CVLM).
6. [11-10] Thanks to [**Qinghao Ye**](https://scholar.google.com.hk/citations?user=ZYOhaGwAAAAJ&hl=zh-CN&oi=ao), we get a new model [**mPLUG-Owl2**](https://github.com/X-PLUG/mPLUG-Owl/tree/main/mPLUG-Owl2) in our leaderboards.
7. [11-10] Thanks to [**Zhibin Wang**](https://scholar.google.com/citations?hl=zh-CN&user=YHzKee8AAAAJ), [**InfMLLM**](https://github.com/mightyzau/InfMLLM) joins our leaderboards (update in 2023-12-12).

**[2023-10]** 

1. [10-29] Thanks to [**Jiaming Han**](https://scholar.google.com/citations?hl=en&user=vgcxKEcAAAAJ&view_op=list_works), [**SPHINX**](https://github.com/Alpha-VLLM/LLaMA2-Accessory/tree/main/SPHINX) is added to our leaderboards. 
2. [10-23] Thanks to [**Zihan Wang**](https://github.com/hanhanHANS), he manually evaluate the performance of [**GPT-4V**](https://cdn.openai.com/papers/GPTV_System_Card.pdf) on our benchmark. Note that GPT-4V refuses to answer questions that involve individuals, resulting in a zero score in the Celebrity subtask. 
3. [10-13] Thanks to [**Yizhou Zhou**](https://scholar.google.com/citations?user=dHBNmSkAAAAJ&hl=en&oi=sra), [**WeMM**](https://github.com/scenarios/WeMM) joins our leaderboards (The results are renewed on 2023-11-10 by updating the model). 
4. [10-13] Thanks to [**Cui Junbo**](https://github.com/thunlp/Muffin), we add [**Muffin**](https://github.com/thunlp/Muffin) to our leaderboards. 
5. [10-13] Thanks to [**Jiaming Han**](https://scholar.google.com/citations?hl=en&user=vgcxKEcAAAAJ&view_op=list_works), the results of [**LLaMA-Adapter V2**](https://github.com/OpenGVLab/LLaMA-Adapter) have been updated. 
6. [10-04] Thanks to [**Haotian Liu**](https://hliu.cc/), the results of [**LLaVA**](https://github.com/haotian-liu/LLaVA) have been updated. 

**[2023-09]** 

1. [09-28] Thanks to [**Huasong Zhong**](https://github.com/mynameischaos), [**Lion**](https://github.com/mynameischaos/Lion) is added.
2. [09-27] Thanks to [**Xiaoyi Dong**](https://scholar.google.com/citations?user=FscToE0AAAAJ&hl=en), [**InternLM-XComposer-VL**](https://github.com/InternLM/InternLM-XComposer) joins our leaderboards.
3. [09-05] Thanks to [**Jinze Bai**](https://github.com/jinze1994), our leaderboards usher in [**Qwen-VL-Chat**](https://github.com/QwenLM/Qwen-VL).
4. [09-01] Thanks to [**Skywork Multi-Modal Group**](https://github.com/will-singularity), [**Skywork-MM**](https://github.com/will-singularity/Skywork-MM/tree/main) takes part in our leaderboards.

**[2023-08]** 

1. [08-28] Thanks to [**UCSD MLPC**](https://github.com/mlpc-ucsd), we welcome [**BLIVA**](https://github.com/mlpc-ucsd/BLIVA) to join our leaderboards. 
2. [08-28] Thanks to [**Jianfeng Wang**](https://scholar.google.com.hk/citations?user=vJWEw_8AAAAJ&hl=zh-CN&oi=sra), [**GIT2**](https://github.com/microsoft/GenerativeImage2Text) is added to our leaderboards. 
3. [08-28] Thanks to [**Yike Yuan**](https://github.com/yyk-wew) and [**Songyang Zhang**](https://github.com/tonysy), the results of [**MiniGPT4**](https://arxiv.org/pdf/2304.10592.pdf) have been revised. 
4. [08-21] Thanks to [**Haozhe Zhao**](https://github.com/HaozheZhao), [**MMICL**](https://github.com/HaozheZhao/MIC) joins our leaderboards (The results are renewed on 2023-09-17 by upgrading the checkpoint.). 
5. [08-13] Thanks to [**Zhejiang University DCD Lab**](https://github.com/DCDmllm), our leaderboards incorporate a new member [**Cheetor**](https://github.com/DCDmllm/Cheetah). 
6. [08-08] Thanks to [**Fuxiao Liu**](https://github.com/FuxiaoLiu), we add [**LRV-Instruction**](https://github.com/FuxiaoLiu/LRV-Instruction) to our leaderboards. 

**[2023-07]** 

1. [07-28] Thanks to [**Yingzi Ma**](https://gray311.github.io/), his work [**Octopus**](https://github.com/gray311/UnifiedMultimodalInstructionTuning) has been updated to our leaderboards.
2. [07-15] Thanks to [**Jiani Zheng**](https://github.com/Garlicisnotmyfavor), our leaderboards welcome a new member [**Lynx**](https://github.com/bytedance/lynx-llm).
3. [07-12] Thanks to [**Ao Zhang**](https://github.com/waxnkw), his work [**VPGTrans**](https://github.com/VPGTrans/VPGTrans) has been added in our leaderboards.
4. [07-09] Thanks to [**Bo Li**](https://github.com/Luodian), we have updated the evaluation of his work [**Otter**](https://github.com/Luodian/Otter). It uses the latest model [**OTTER-Image-MPT7B**](https://huggingface.co/luodian/OTTER-Image-MPT7B) that incoporates OpenFlamingv2 and enhances instruction following ability.

**[2023-06]** 

1. [06-30] Thanks to [**Renrui Zhang**](https://github.com/ZrrSkywalker), we have updated the evaluation of his two works, i.e., [**LLaMA-Adapter V2**](https://github.com/OpenGVLab/LLaMA-Adapter) and [**ImageBind_LLM**](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/imagebind_LLM). The former is re-evaluated after changing the model [**weights**](https://github.com/OpenGVLab/LLaMA-Adapter/releases/download/v.2.0.0/7fa55208379faf2dd862565284101b0e4a2a72114d6490a95e432cf9d9b6c813_BIAS-7B.pth), and the latter is a newly added MLLM.
2. [06-30] Thanks to [**Gen Luo**](https://github.com/luogen1996), we have added the evaluation of his work [**LaVIN**](https://github.com/luogen1996/LaVIN).
3. [06-30] The results of other models have also been updated, retrieving the answer from the beginning of the generated responses instead of the whole responses. [**An automated evaluation script**](https://github.com/BradyFU/Awesome-Multimodal-Large-Language-Models/blob/Evaluation/tools/eval_tool.zip) for the calculation of scores has been released!

</details>

---

# Results of Available Models [[Unavailable Version](https://github.com/BradyFU/Awesome-Multimodal-Large-Language-Models/tree/Evaluation-PrivateModel)]

<img src="./images/evaluation_chart_public_0128.png" width="70%" height="70%">

# Leaderboards of Available Models [[Unavailable Version](https://github.com/BradyFU/Awesome-Multimodal-Large-Language-Models/tree/Evaluation-PrivateModel)]

<img src="./images/xmind.png" width="96%" height="96%">

---

- [Perception](#perception)
  - [Existence](#existence) | [Count](#count) | [Position](#position) | [Color](#color) | [Poster](#poster) | [Celebrity](#celebrity) | [Scene](#scene) | [Landmark](#landmark) | [Artwork](#artwork) | [OCR](#ocr)
  
- [Cognition](#cognition)
  - [Commonsense Reasoning](#commonsense-reasoning) | [Numerical Calculation](#numerical-calculation) | [Text Translation](#text-translation) | [Code Reasoning](#code-reasoning)


---

## Perception

Sum of the scores of all perception subtasks, including existence, count, position, color, poster, celebrity, scene, landmark, artwork, and OCR. The full score of each subtask is 200, and that of all perception is 2000.

| Rank |                            Model                             |                           Version                            |  Score  |
| :--: | :----------------------------------------------------------: | :----------------------------------------------------------: | :-----: |
|  🏅️   | [Qwen-VL-Max](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start) | [-](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start) | 1790.04 |
|  🥈   | [ChatTruth-7B](https://huggingface.co/mingdali/ChatTruth-7B) |   [Qwen-7B](https://huggingface.co/mingdali/ChatTruth-7B)    | 1735.88 |
|  🥉   | [InternLM-XComposer2-VL](https://github.com/InternLM/InternLM-XComposer) | [InternLM2-7B](https://github.com/InternLM/InternLM-XComposer) | 1712.00 |
|  4   |           [PureMM](https://github.com/Q-MM/PureMM)           |         [Vicuna-13B](https://github.com/Q-MM/PureMM)         | 1686.52 |
|  5   | [Qwen-VL-Plus](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start) | [-](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start) | 1681.25 |
|  6   |       [InfMLLM](https://github.com/infly-ai/INF-MLLM)        |      [Vicuna-13B](https://github.com/infly-ai/INF-MLLM)      | 1673.75 |
|  7   |  [InternVL-Chat-V1.1](https://arxiv.org/pdf/2312.14238.pdf)  |     [LLaMA2-13B](https://github.com/OpenGVLab/InternVL/)     | 1672.35 |
|  8   |       [Honeybee](https://arxiv.org/pdf/2312.06742.pdf)       |     [Vicuna-13B](https://github.com/kakaobrain/honeybee)     | 1661.13 |
|  9   | [Bunny-8B](https://huggingface.co/BAAI/Bunny-v1_1-Llama-3-8B-V) |       [LLaMA3-8B](https://github.com/BAAI-DCAI/Bunny)        | 1644.14 |
|  10  |    [JT-VL-Chat](https://github.com/jiutiancv/JT-VL-Chat)     |         [-](https://github.com/jiutiancv/JT-VL-Chat)         | 1642.51 |
|  11  | [360VL](https://github.com/360CVGroup/360VL?tab=readme-ov-file) | [LLaMA3-70B](https://github.com/360CVGroup/360VL?tab=readme-ov-file) | 1640.86 |
|  12  |    [InternVL-Chat-V1.5](https://arxiv.org/pdf/2404.16821)    |    [InternLM2-20B](https://github.com/OpenGVLab/InternVL)    | 1637.84 |
|  13  |   [OmniLMM](https://github.com/OpenBMB/MiniCPM/#minicpm-v)   | [Zephyr-7B-beta](https://github.com/OpenBMB/MiniCPM/#minicpm-v) | 1636.90 |
|  14  | [LLaVA-1.6](https://llava-vl.github.io/blog/2024-01-30-llava-1-6/) |      [Vicuna-34B](https://github.com/haotian-liu/LLaVA)      | 1631.47 |
|  15  |          [WeMM](https://github.com/scenarios/WeMM)           |       [InternLM-7B](https://github.com/scenarios/WeMM)       | 1621.66 |
|  16  | [MiniCPM-Llama3-V 2.5](https://github.com/OpenBMB/MiniCPM-V) |      [LLaMA3-8B](https://github.com/OpenBMB/MiniCPM-V)       | 1619.29 |
|  17  |      [ShareGPT4V](https://arxiv.org/pdf/2311.12793.pdf)      | [Vicuna-13B](https://github.com/InternLM/InternLM-XComposer/tree/main/projects/ShareGPT4V) | 1618.70 |
|  18  |       [RBDash](https://github.com/RBDash-Team/RBDash)        |     [Vicuna-13B](https://github.com/RBDash-Team/RBDash)      | 1610.15 |
|  19  |     [BELLE-VL](https://huggingface.co/BELLE-2/BELLE-VL)      |     [Qwen-14B](https://huggingface.co/BELLE-2/BELLE-VL)      | 1595.34 |
|  20  |  [TransCore-M](https://github.com/PCIResearch/TransCore-M)   | [PCITransGPT-13B](https://github.com/PCIResearch/TransCore-M) | 1588.16 |
|  21  |    [Bunny-4B](https://huggingface.co/BAAI/Bunny-v1_1-4B)     | [Phi-3-Mini-4K-Instruct](https://github.com/BAAI-DCAI/Bunny) | 1581.52 |
|  22  |      [HyperLLaVA](https://arxiv.org/pdf/2403.13447.pdf)      |     [Vicuna-13B](https://github.com/dcdmllm/hyperllava)      | 1575.61 |
|  23  |   [LVIS-INSTRUCT4V](https://arxiv.org/pdf/2311.07574.pdf)    |    [Vicuna-13B](https://github.com/X2FD/LVIS-INSTRUCT4V)     | 1574.89 |
|  24  | [MindSource-VL-Chat](https://github.com/luogen1996/LLaVA-HR) |   [MindSource-7B](https://github.com/luogen1996/LLaVA-HR)    | 1567.99 |
|  25  |  [DataOptim-LLaVA](https://github.com/BAAI-DCAI/DataOptim)   |     [Vicuna-13B](https://github.com/BAAI-DCAI/DataOptim)     | 1563.56 |
|  26  | [SPHINX](https://github.com/Alpha-VLLM/LLaMA2-Accessory/tree/main/SPHINX) | [LLaMA2-13B](https://github.com/Alpha-VLLM/LLaMA2-Accessory/tree/main/SPHINX) | 1560.15 |
|  27  |        [LLaVA](https://arxiv.org/pdf/2304.08485.pdf)         |      [Vicuna-13B](https://github.com/haotian-liu/LLaVA)      | 1531.31 |
|  28  | [InternLM-XComposer-VL](https://github.com/InternLM/InternLM-XComposer) | [InternLM-7B](https://github.com/InternLM/InternLM-XComposer) | 1528.44 |
|  29  |     [Monkey-Chat](https://arxiv.org/pdf/2311.06607.pdf)      |       [Qwen-7B](https://github.com/Yuliang-Liu/Monkey)       | 1522.39 |
|  30  |       [CogAgent](https://arxiv.org/pdf/2312.08914.pdf)       |         [Vicuna-7B](https://github.com/THUDM/CogVLM)         | 1497.79 |
|  31  | [Gemini Pro](https://storage.googleapis.com/deepmind-media/gemini/gemini_1_report.pdf) | [-](https://storage.googleapis.com/deepmind-media/gemini/gemini_1_report.pdf) | 1496.57 |
|  32  |      [Qwen-VL-Chat](https://github.com/QwenLM/Qwen-VL/)      |         [Qwen-7B](https://github.com/QwenLM/Qwen-VL)         | 1487.57 |
|  33  |   [MiniCPM](https://github.com/OpenBMB/MiniCPM/#minicpm-v)   | [MiniCPM-2B](https://github.com/OpenBMB/MiniCPM/#minicpm-v)  | 1452.01 |
|  34  |      [mPLUG-Owl2](https://arxiv.org/pdf/2311.04257.pdf)      | [LLaMA2-7B](https://github.com/X-PLUG/mPLUG-Owl/tree/main/mPLUG-Owl2) | 1450.19 |
|  35  | [MiniCPM-V-2](https://github.com/OpenBMB/MiniCPM/#minicpm-v) | [MiniCPM-2B](https://github.com/OpenBMB/MiniCPM/#minicpm-v)  | 1443.19 |
|  36  |        [CogVLM](https://arxiv.org/pdf/2311.03079.pdf)        |         [Vicuna-7B](https://github.com/THUDM/CogVLM)         | 1439.07 |
|  37  |      [MoE-LLaVA](https://arxiv.org/pdf/2401.15947.pdf)       |   [Phi-2.7B×4](https://github.com/PKU-YuanGroup/MoE-LLaVA)   | 1431.34 |
|  38  | [GPT-4V](https://cdn.openai.com/papers/GPTV_System_Card.pdf) |   [-](https://cdn.openai.com/papers/GPTV_System_Card.pdf)    | 1409.43 |
|  39  |        [MMICL](https://arxiv.org/pdf/2309.07915.pdf)         |        [FlanT5xxl](https://github.com/HaozheZhao/MIC)        | 1381.74 |
|  40  |         [Lynx](https://arxiv.org/pdf/2307.02469.pdf)         |      [Vicuna-7B](https://github.com/bytedance/lynx-llm)      | 1373.24 |
|  41  |        [BLIVA](https://arxiv.org/pdf/2308.09936.pdf)         |       [FlanT5xxl](https://github.com/mlpc-ucsd/BLIVA)        | 1337.73 |
|  42  |         [GIT2](https://arxiv.org/pdf/2205.14100.pdf)         | [VQAv2-finetuned](https://github.com/microsoft/GenerativeImage2Text) | 1332.05 |
|  43  |   [LLaMA-Adapter V2](https://arxiv.org/pdf/2304.15010.pdf)   | [LLaMA-Adapter-v2.1-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/llama_adapter_v2_multimodal7b) | 1328.39 |
|  44  |       [Cheetor](https://arxiv.org/pdf/2308.04152.pdf)        |       [Vicuna-7B](https://github.com/DCDmllm/Cheetah)        | 1299.97 |
|  45  |   [LRV-Instruction](https://arxiv.org/pdf/2306.14565.pdf)    |    [LRV-7B](https://github.com/FuxiaoLiu/LRV-Instruction)    | 1299.79 |
|  46  |        [BLIP-2](https://arxiv.org/pdf/2301.12597.pdf)        | [Flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/blip2) | 1293.84 |
|  47  |        [Otter](https://arxiv.org/pdf/2305.03726.pdf)         |    [OTTER-Image-MPT7B](https://github.com/Luodian/Otter)     | 1292.26 |
|  48  |          [Muffin](https://github.com/thunlp/Muffin)          |        [Vicuna-13B](https://github.com/thunlp/Muffin)        | 1281.02 |
|  49  |     [InstructBLIP](https://arxiv.org/pdf/2305.06500.pdf)     | [FlanT5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/instructblip) | 1212.82 |
|  50  |      [mPLUG-Owl](https://arxiv.org/pdf/2304.14178.pdf)       | [LLaMA-7B](https://huggingface.co/MAGAer13/mplug-owl-llama-7b) | 967.34  |
|  51  |        [LaVIN](https://arxiv.org/pdf/2305.15023.pdf)         |       [LAVIN-13B](https://github.com/luogen1996/LaVIN)       |  963.6  |
|  52  |       [VPGTrans](https://arxiv.org/pdf/2305.01278.pdf)       |      [Vicuna-7B](https://github.com/VPGTrans/VPGTrans)       | 790.45  |
|  53  | [ImageBind_LLM](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main) | [LLaMA-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/imagebind_LLM) | 775.77  |
|  54  |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     | 705.31  |
|  55  |    [Multimodal-GPT](https://arxiv.org/pdf/2305.04790.pdf)    | [Multimodal-GPT-9B](https://github.com/open-mmlab/Multimodal-GPT) | 654.72  |
|  56  |       [PandaGPT](https://arxiv.org/pdf/2305.16355.pdf)       |       [Vicuna-7B](https://github.com/yxuansu/PandaGPT)       | 642.59  |
|  57  |      [MiniGPT-4](https://arxiv.org/pdf/2304.10592.pdf)       |    [Vicuna-13B](https://github.com/Vision-CAIR/MiniGPT-4)    | 581.66  |

### Existence

| Rank |                            Model                             |                           Version                            | Score  |
| :--: | :----------------------------------------------------------: | :----------------------------------------------------------: | :----: |
|  🏅️   | [MiniCPM-Llama3-V 2.5](https://github.com/OpenBMB/MiniCPM-V) |      [LLaMA3-8B](https://github.com/OpenBMB/MiniCPM-V)       | 200.00 |
|  🥈   |        [Otter](https://arxiv.org/pdf/2305.03726.pdf)         |    [OTTER-Image-MPT7B](https://github.com/Luodian/Otter)     | 195.00 |
|  🥈   |         [Lynx](https://arxiv.org/pdf/2307.02469.pdf)         |      [Vicuna-7B](https://github.com/bytedance/lynx-llm)      | 195.00 |
|  🥈   |          [WeMM](https://github.com/scenarios/WeMM)           |       [InternLM-7B](https://github.com/scenarios/WeMM)       | 195.00 |
|  🥈   |          [Muffin](https://github.com/thunlp/Muffin)          |        [Vicuna-13B](https://github.com/thunlp/Muffin)        | 195.00 |
|  🥈   | [SPHINX](https://github.com/Alpha-VLLM/LLaMA2-Accessory/tree/main/SPHINX) | [LLaMA2-13B](https://github.com/Alpha-VLLM/LLaMA2-Accessory/tree/main/SPHINX) | 195.00 |
|  🥈   |       [InfMLLM](https://github.com/infly-ai/INF-MLLM)        |      [Vicuna-13B](https://github.com/infly-ai/INF-MLLM)      | 195.00 |
|  🥈   |   [LVIS-INSTRUCT4V](https://arxiv.org/pdf/2311.07574.pdf)    |    [Vicuna-13B](https://github.com/X2FD/LVIS-INSTRUCT4V)     | 195.00 |
|  🥈   |       [RBDash](https://github.com/RBDash-Team/RBDash)        |     [Vicuna-13B](https://github.com/RBDash-Team/RBDash)      | 195.00 |
|  🥈   | [InternLM-XComposer2-VL](https://github.com/InternLM/InternLM-XComposer) | [InternLM2-7B](https://github.com/InternLM/InternLM-XComposer) | 195.00 |
|  🥈   |        [CogVLM](https://arxiv.org/pdf/2311.03079.pdf)        |         [Vicuna-7B](https://github.com/THUDM/CogVLM)         | 195.00 |
|  🥈   | [ChatTruth-7B](https://huggingface.co/mingdali/ChatTruth-7B) |   [Qwen-7B](https://huggingface.co/mingdali/ChatTruth-7B)    | 195.00 |
|  🥈   | [MindSource-VL-Chat](https://github.com/luogen1996/LLaVA-HR) |   [MindSource-7B](https://github.com/luogen1996/LLaVA-HR)    | 195.00 |
|  🥈   | [MiniCPM-V-2](https://github.com/OpenBMB/MiniCPM/#minicpm-v) | [MiniCPM-2B](https://github.com/OpenBMB/MiniCPM/#minicpm-v)  | 195.00 |
|  🥈   | [Bunny-8B](https://huggingface.co/BAAI/Bunny-v1_1-Llama-3-8B-V) |       [LLaMA3-8B](https://github.com/BAAI-DCAI/Bunny)        | 195.00 |
|  🥉   |         [GIT2](https://arxiv.org/pdf/2205.14100.pdf)         | [VQAv2-finetuned](https://github.com/microsoft/GenerativeImage2Text) | 190.00 |
|  🥉   | [InternLM-XComposer-VL](https://github.com/InternLM/InternLM-XComposer) | [InternLM-7B](https://github.com/InternLM/InternLM-XComposer) | 190.00 |
|  🥉   | [GPT-4V](https://cdn.openai.com/papers/GPTV_System_Card.pdf) |   [-](https://cdn.openai.com/papers/GPTV_System_Card.pdf)    | 190.00 |
|  🥉   |      [ShareGPT4V](https://arxiv.org/pdf/2311.12793.pdf)      | [Vicuna-13B](https://github.com/InternLM/InternLM-XComposer/tree/main/projects/ShareGPT4V) | 190.00 |
|  🥉   |  [DataOptim-LLaVA](https://github.com/BAAI-DCAI/DataOptim)   |     [Vicuna-13B](https://github.com/BAAI-DCAI/DataOptim)     | 190.00 |
|  🥉   |     [BELLE-VL](https://huggingface.co/BELLE-2/BELLE-VL)      |     [Qwen-14B](https://huggingface.co/BELLE-2/BELLE-VL)      | 190.00 |
|  🥉   |  [TransCore-M](https://github.com/PCIResearch/TransCore-M)   | [PCITransGPT-13B](https://github.com/PCIResearch/TransCore-M) | 190.00 |
|  🥉   | [LLaVA-1.6](https://llava-vl.github.io/blog/2024-01-30-llava-1-6/) |      [Vicuna-34B](https://github.com/haotian-liu/LLaVA)      | 190.00 |
|  🥉   |   [MiniCPM](https://github.com/OpenBMB/MiniCPM/#minicpm-v)   | [MiniCPM-2B](https://github.com/OpenBMB/MiniCPM/#minicpm-v)  | 190.00 |
|  🥉   |   [OmniLMM](https://github.com/OpenBMB/MiniCPM/#minicpm-v)   | [Zephyr-7B-beta](https://github.com/OpenBMB/MiniCPM/#minicpm-v) | 190.00 |
|  🥉   |    [Bunny-4B](https://huggingface.co/BAAI/Bunny-v1_1-4B)     | [Phi-3-Mini-4K-Instruct](https://github.com/BAAI-DCAI/Bunny) | 190.00 |
|  🥉   |      [HyperLLaVA](https://arxiv.org/pdf/2403.13447.pdf)      |     [Vicuna-13B](https://github.com/dcdmllm/hyperllava)      | 190.00 |
|  🥉   |    [InternVL-Chat-V1.5](https://arxiv.org/pdf/2404.16821)    |    [InternLM2-20B](https://github.com/OpenGVLab/InternVL)    | 190.00 |
|  🥉   | [360VL](https://github.com/360CVGroup/360VL?tab=readme-ov-file) | [LLaMA3-70B](https://github.com/360CVGroup/360VL?tab=readme-ov-file) | 190.00 |
|  4   |           [PureMM](https://github.com/Q-MM/PureMM)           |         [Vicuna-13B](https://github.com/Q-MM/PureMM)         | 188.33 |
|  5   |   [LLaMA-Adapter V2](https://arxiv.org/pdf/2304.15010.pdf)   | [LLaMA-Adapter-v2.1-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/llama_adapter_v2_multimodal7b) | 185.00 |
|  5   |     [InstructBLIP](https://arxiv.org/pdf/2305.06500.pdf)     | [FlanT5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/instructblip) | 185.00 |
|  5   |        [LLaVA](https://arxiv.org/pdf/2304.08485.pdf)         |      [Vicuna-13B](https://github.com/haotian-liu/LLaVA)      | 185.00 |
|  5   |        [LaVIN](https://arxiv.org/pdf/2305.15023.pdf)         |       [LAVIN-13B](https://github.com/luogen1996/LaVIN)       | 185.00 |
|  5   |      [mPLUG-Owl2](https://arxiv.org/pdf/2311.04257.pdf)      | [LLaMA2-7B](https://github.com/X-PLUG/mPLUG-Owl/tree/main/mPLUG-Owl2) | 185.00 |
|  5   |     [Monkey-Chat](https://arxiv.org/pdf/2311.06607.pdf)      |       [Qwen-7B](https://github.com/Yuliang-Liu/Monkey)       | 185.00 |
|  5   |       [Honeybee](https://arxiv.org/pdf/2312.06742.pdf)       |     [Vicuna-13B](https://github.com/kakaobrain/honeybee)     | 185.00 |
|  5   |  [InternVL-Chat-V1.1](https://arxiv.org/pdf/2312.14238.pdf)  |     [LLaMA2-13B](https://github.com/OpenGVLab/InternVL/)     | 185.00 |
|  5   |       [CogAgent](https://arxiv.org/pdf/2312.08914.pdf)       |         [Vicuna-7B](https://github.com/THUDM/CogVLM)         | 185.00 |
|  5   |    [JT-VL-Chat](https://github.com/jiutiancv/JT-VL-Chat)     |         [-](https://github.com/jiutiancv/JT-VL-Chat)         | 185.00 |
|  6   | [Qwen-VL-Max](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start) | [-](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start) | 183.33 |
|  7   |       [Cheetor](https://arxiv.org/pdf/2308.04152.pdf)        |       [Vicuna-7B](https://github.com/DCDmllm/Cheetah)        | 180.00 |
|  7   |        [BLIVA](https://arxiv.org/pdf/2308.09936.pdf)         |       [FlanT5xxl](https://github.com/mlpc-ucsd/BLIVA)        | 180.00 |
|  7   |      [MoE-LLaVA](https://arxiv.org/pdf/2401.15947.pdf)       |   [Phi-2.7B×4](https://github.com/PKU-YuanGroup/MoE-LLaVA)   | 180.00 |
|  8   | [Qwen-VL-Plus](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start) | [-](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start) | 175.00 |
|  8   | [Gemini Pro](https://storage.googleapis.com/deepmind-media/gemini/gemini_1_report.pdf) | [-](https://storage.googleapis.com/deepmind-media/gemini/gemini_1_report.pdf) | 175.00 |
|  9   |        [MMICL](https://arxiv.org/pdf/2309.07915.pdf)         |        [FlanT5xxl](https://github.com/HaozheZhao/MIC)        | 170.00 |
|  10  |   [LRV-Instruction](https://arxiv.org/pdf/2306.14565.pdf)    |    [LRV-7B](https://github.com/FuxiaoLiu/LRV-Instruction)    | 165.00 |
|  11  |        [BLIP-2](https://arxiv.org/pdf/2301.12597.pdf)        | [Flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/blip2) | 160.00 |
|  12  |      [Qwen-VL-Chat](https://github.com/QwenLM/Qwen-VL/)      |         [Qwen-7B](https://github.com/QwenLM/Qwen-VL)         | 158.33 |
|  13  | [ImageBind_LLM](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main) | [LLaMA-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/imagebind_LLM) | 128.33 |
|  14  |      [mPLUG-Owl](https://arxiv.org/pdf/2304.14178.pdf)       | [LLaMA-7B](https://huggingface.co/MAGAer13/mplug-owl-llama-7b) | 120.00 |
|  15  |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     | 85.00  |
|  16  |       [PandaGPT](https://arxiv.org/pdf/2305.16355.pdf)       |       [Vicuna-7B](https://github.com/yxuansu/PandaGPT)       | 70.00  |
|  16  |       [VPGTrans](https://arxiv.org/pdf/2305.01278.pdf)       |      [Vicuna-7B](https://github.com/VPGTrans/VPGTrans)       | 70.00  |
|  17  |      [MiniGPT-4](https://arxiv.org/pdf/2304.10592.pdf)       |    [Vicuna-13B](https://github.com/Vision-CAIR/MiniGPT-4)    | 68.33  |
|  18  |    [Multimodal-GPT](https://arxiv.org/pdf/2305.04790.pdf)    | [Multimodal-GPT-9B](https://github.com/open-mmlab/Multimodal-GPT) | 61.67  |

### Count

| Rank |                            Model                             |                           Version                            | Score  |
| :--: | :----------------------------------------------------------: | :----------------------------------------------------------: | :----: |
|  🏅️   |       [CogAgent](https://arxiv.org/pdf/2312.08914.pdf)       |         [Vicuna-7B](https://github.com/THUDM/CogVLM)         | 180.00 |
|  🥈   |    [InternVL-Chat-V1.5](https://arxiv.org/pdf/2404.16821)    |    [InternLM2-20B](https://github.com/OpenGVLab/InternVL)    | 175.00 |
|  🥉   |       [RBDash](https://github.com/RBDash-Team/RBDash)        |     [Vicuna-13B](https://github.com/RBDash-Team/RBDash)      | 173.33 |
|  🥉   |  [InternVL-Chat-V1.1](https://arxiv.org/pdf/2312.14238.pdf)  |     [LLaMA2-13B](https://github.com/OpenGVLab/InternVL/)     | 173.33 |
|  🥉   |    [JT-VL-Chat](https://github.com/jiutiancv/JT-VL-Chat)     |         [-](https://github.com/jiutiancv/JT-VL-Chat)         | 173.33 |
|  4   |       [Honeybee](https://arxiv.org/pdf/2312.06742.pdf)       |     [Vicuna-13B](https://github.com/kakaobrain/honeybee)     | 170.00 |
|  4   | [LLaVA-1.6](https://llava-vl.github.io/blog/2024-01-30-llava-1-6/) |      [Vicuna-34B](https://github.com/haotian-liu/LLaVA)      | 170.00 |
|  4   | [MindSource-VL-Chat](https://github.com/luogen1996/LLaVA-HR) |   [MindSource-7B](https://github.com/luogen1996/LLaVA-HR)    | 170.00 |
|  5   | [MiniCPM-Llama3-V 2.5](https://github.com/OpenBMB/MiniCPM-V) |      [LLaMA3-8B](https://github.com/OpenBMB/MiniCPM-V)       | 168.33 |
|  6   | [Qwen-VL-Max](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start) | [-](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start) | 166.67 |
|  7   |    [Bunny-4B](https://huggingface.co/BAAI/Bunny-v1_1-4B)     | [Phi-3-Mini-4K-Instruct](https://github.com/BAAI-DCAI/Bunny) | 165.80 |
|  7   |      [ShareGPT4V](https://arxiv.org/pdf/2311.12793.pdf)      | [Vicuna-13B](https://github.com/InternLM/InternLM-XComposer/tree/main/projects/ShareGPT4V) | 165.00 |
|  7   |  [DataOptim-LLaVA](https://github.com/BAAI-DCAI/DataOptim)   |     [Vicuna-13B](https://github.com/BAAI-DCAI/DataOptim)     | 165.00 |
|  7   |  [TransCore-M](https://github.com/PCIResearch/TransCore-M)   | [PCITransGPT-13B](https://github.com/PCIResearch/TransCore-M) | 165.00 |
|  7   |        [CogVLM](https://arxiv.org/pdf/2311.03079.pdf)        |         [Vicuna-7B](https://github.com/THUDM/CogVLM)         | 165.00 |
|  7   |   [OmniLMM](https://github.com/OpenBMB/MiniCPM/#minicpm-v)   | [Zephyr-7B-beta](https://github.com/OpenBMB/MiniCPM/#minicpm-v) | 165.00 |
|  7   | [Bunny-8B](https://huggingface.co/BAAI/Bunny-v1_1-Llama-3-8B-V) |       [LLaMA3-8B](https://github.com/BAAI-DCAI/Bunny)        | 165.00 |
|  8   |          [Muffin](https://github.com/thunlp/Muffin)          |        [Vicuna-13B](https://github.com/thunlp/Muffin)        | 163.33 |
|  9   | [360VL](https://github.com/360CVGroup/360VL?tab=readme-ov-file) | [LLaMA3-70B](https://github.com/360CVGroup/360VL?tab=readme-ov-file) | 160.80 |
|  10  |        [MMICL](https://arxiv.org/pdf/2309.07915.pdf)         |        [FlanT5xxl](https://github.com/HaozheZhao/MIC)        | 160.00 |
|  10  | [GPT-4V](https://cdn.openai.com/papers/GPTV_System_Card.pdf) |   [-](https://cdn.openai.com/papers/GPTV_System_Card.pdf)    | 160.00 |
|  10  | [SPHINX](https://github.com/Alpha-VLLM/LLaMA2-Accessory/tree/main/SPHINX) | [LLaMA2-13B](https://github.com/Alpha-VLLM/LLaMA2-Accessory/tree/main/SPHINX) | 160.00 |
|  10  |   [LVIS-INSTRUCT4V](https://arxiv.org/pdf/2311.07574.pdf)    |    [Vicuna-13B](https://github.com/X2FD/LVIS-INSTRUCT4V)     | 160.00 |
|  10  | [InternLM-XComposer2-VL](https://github.com/InternLM/InternLM-XComposer) | [InternLM2-7B](https://github.com/InternLM/InternLM-XComposer) | 160.00 |
|  10  | [ChatTruth-7B](https://huggingface.co/mingdali/ChatTruth-7B) |   [Qwen-7B](https://huggingface.co/mingdali/ChatTruth-7B)    | 160.00 |
|  10  |      [HyperLLaVA](https://arxiv.org/pdf/2403.13447.pdf)      |     [Vicuna-13B](https://github.com/dcdmllm/hyperllava)      | 160.00 |
|  11  | [InternLM-XComposer-VL](https://github.com/InternLM/InternLM-XComposer) | [InternLM-7B](https://github.com/InternLM/InternLM-XComposer) | 158.33 |
|  12  |        [LLaVA](https://arxiv.org/pdf/2304.08485.pdf)         |      [Vicuna-13B](https://github.com/haotian-liu/LLaVA)      | 155.00 |
|  12  |      [mPLUG-Owl2](https://arxiv.org/pdf/2311.04257.pdf)      | [LLaMA2-7B](https://github.com/X-PLUG/mPLUG-Owl/tree/main/mPLUG-Owl2) | 155.00 |
|  12  |      [MoE-LLaVA](https://arxiv.org/pdf/2401.15947.pdf)       |   [Phi-2.7B×4](https://github.com/PKU-YuanGroup/MoE-LLaVA)   | 155.00 |
|  13  | [Qwen-VL-Plus](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start) | [-](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start) | 153.33 |
|  14  |         [Lynx](https://arxiv.org/pdf/2307.02469.pdf)         |      [Vicuna-7B](https://github.com/bytedance/lynx-llm)      | 151.67 |
|  15  |      [Qwen-VL-Chat](https://github.com/QwenLM/Qwen-VL/)      |         [Qwen-7B](https://github.com/QwenLM/Qwen-VL)         | 150.00 |
|  15  |     [BELLE-VL](https://huggingface.co/BELLE-2/BELLE-VL)      |     [Qwen-14B](https://huggingface.co/BELLE-2/BELLE-VL)      | 150.00 |
|  15  |     [Monkey-Chat](https://arxiv.org/pdf/2311.06607.pdf)      |       [Qwen-7B](https://github.com/Yuliang-Liu/Monkey)       | 150.00 |
|  15  |           [PureMM](https://github.com/Q-MM/PureMM)           |         [Vicuna-13B](https://github.com/Q-MM/PureMM)         | 150.00 |
|  16  |       [InfMLLM](https://github.com/infly-ai/INF-MLLM)        |      [Vicuna-13B](https://github.com/infly-ai/INF-MLLM)      | 145.00 |
|  17  |     [InstructBLIP](https://arxiv.org/pdf/2305.06500.pdf)     | [FlanT5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/instructblip) | 143.33 |
|  18  |          [WeMM](https://github.com/scenarios/WeMM)           |       [InternLM-7B](https://github.com/scenarios/WeMM)       | 140.00 |
|  19  |        [BLIVA](https://arxiv.org/pdf/2308.09936.pdf)         |       [FlanT5xxl](https://github.com/mlpc-ucsd/BLIVA)        | 138.33 |
|  20  |        [BLIP-2](https://arxiv.org/pdf/2301.12597.pdf)        | [Flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/blip2) | 135.00 |
|  21  | [MiniCPM-V-2](https://github.com/OpenBMB/MiniCPM/#minicpm-v) | [MiniCPM-2B](https://github.com/OpenBMB/MiniCPM/#minicpm-v)  | 133.33 |
|  21  |   [LLaMA-Adapter V2](https://arxiv.org/pdf/2304.15010.pdf)   | [LLaMA-Adapter-v2.1-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/llama_adapter_v2_multimodal7b) | 133.33 |
|  22  | [Gemini Pro](https://storage.googleapis.com/deepmind-media/gemini/gemini_1_report.pdf) | [-](https://storage.googleapis.com/deepmind-media/gemini/gemini_1_report.pdf) | 131.67 |
|  23  |   [MiniCPM](https://github.com/OpenBMB/MiniCPM/#minicpm-v)   | [MiniCPM-2B](https://github.com/OpenBMB/MiniCPM/#minicpm-v)  | 130.00 |
|  24  |         [GIT2](https://arxiv.org/pdf/2205.14100.pdf)         | [VQAv2-finetuned](https://github.com/microsoft/GenerativeImage2Text) | 118.33 |
|  25  |   [LRV-Instruction](https://arxiv.org/pdf/2306.14565.pdf)    |    [LRV-7B](https://github.com/FuxiaoLiu/LRV-Instruction)    | 111.67 |
|  26  |       [Cheetor](https://arxiv.org/pdf/2308.04152.pdf)        |       [Vicuna-7B](https://github.com/DCDmllm/Cheetah)        | 96.67  |
|  27  |        [Otter](https://arxiv.org/pdf/2305.03726.pdf)         |    [OTTER-Image-MPT7B](https://github.com/Luodian/Otter)     | 88.33  |
|  27  |        [LaVIN](https://arxiv.org/pdf/2305.15023.pdf)         |       [LAVIN-13B](https://github.com/luogen1996/LaVIN)       | 88.33  |
|  28  |       [VPGTrans](https://arxiv.org/pdf/2305.01278.pdf)       |      [Vicuna-7B](https://github.com/VPGTrans/VPGTrans)       | 85.00  |
|  29  | [ImageBind_LLM](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main) | [LLaMA-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/imagebind_LLM) | 60.00  |
|  30  |      [MiniGPT-4](https://arxiv.org/pdf/2304.10592.pdf)       |    [Vicuna-13B](https://github.com/Vision-CAIR/MiniGPT-4)    | 55.00  |
|  30  |    [Multimodal-GPT](https://arxiv.org/pdf/2305.04790.pdf)    | [Multimodal-GPT-9B](https://github.com/open-mmlab/Multimodal-GPT) | 55.00  |
|  31  |      [mPLUG-Owl](https://arxiv.org/pdf/2304.14178.pdf)       | [LLaMA-7B](https://huggingface.co/MAGAer13/mplug-owl-llama-7b) | 50.00  |
|  31  |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     | 50.00  |
|  31  |       [PandaGPT](https://arxiv.org/pdf/2305.16355.pdf)       |       [Vicuna-7B](https://github.com/yxuansu/PandaGPT)       | 50.00  |

### Position

| Rank |                            Model                             |                           Version                            | Score  |
| :--: | :----------------------------------------------------------: | :----------------------------------------------------------: | :----: |
|  🏅️   | [Qwen-VL-Max](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start) | [-](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start) | 176.67 |
|  🥈   |       [InfMLLM](https://github.com/infly-ai/INF-MLLM)        |      [Vicuna-13B](https://github.com/infly-ai/INF-MLLM)      | 170.00 |
|  🥉   |    [InternVL-Chat-V1.5](https://arxiv.org/pdf/2404.16821)    |    [InternLM2-20B](https://github.com/OpenGVLab/InternVL)    | 166.67 |
|  4   | [InternLM-XComposer2-VL](https://github.com/InternLM/InternLM-XComposer) | [InternLM2-7B](https://github.com/InternLM/InternLM-XComposer) | 163.33 |
|  4   |  [InternVL-Chat-V1.1](https://arxiv.org/pdf/2312.14238.pdf)  |     [LLaMA2-13B](https://github.com/OpenGVLab/InternVL/)     | 163.33 |
|  5   | [Qwen-VL-Plus](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start) | [-](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start) | 161.67 |
|  6   | [ChatTruth-7B](https://huggingface.co/mingdali/ChatTruth-7B) |   [Qwen-7B](https://huggingface.co/mingdali/ChatTruth-7B)    | 158.33 |
|  7   |       [Honeybee](https://arxiv.org/pdf/2312.06742.pdf)       |     [Vicuna-13B](https://github.com/kakaobrain/honeybee)     | 155.00 |
|  7   | [360VL](https://github.com/360CVGroup/360VL?tab=readme-ov-file) | [LLaMA3-70B](https://github.com/360CVGroup/360VL?tab=readme-ov-file) | 155.00 |
|  8   |      [ShareGPT4V](https://arxiv.org/pdf/2311.12793.pdf)      | [Vicuna-13B](https://github.com/InternLM/InternLM-XComposer/tree/main/projects/ShareGPT4V) | 153.33 |
|  8   | [SPHINX](https://github.com/Alpha-VLLM/LLaMA2-Accessory/tree/main/SPHINX) | [LLaMA2-13B](https://github.com/Alpha-VLLM/LLaMA2-Accessory/tree/main/SPHINX) | 153.33 |
|  9   | [MindSource-VL-Chat](https://github.com/luogen1996/LLaVA-HR) |   [MindSource-7B](https://github.com/luogen1996/LLaVA-HR)    | 146.67 |
|  10  |    [JT-VL-Chat](https://github.com/jiutiancv/JT-VL-Chat)     |         [-](https://github.com/jiutiancv/JT-VL-Chat)         | 145.00 |
|  11  |       [RBDash](https://github.com/RBDash-Team/RBDash)        |     [Vicuna-13B](https://github.com/RBDash-Team/RBDash)      | 138.33 |
|  11  | [LLaVA-1.6](https://llava-vl.github.io/blog/2024-01-30-llava-1-6/) |      [Vicuna-34B](https://github.com/haotian-liu/LLaVA)      | 138.33 |
|  12  |  [TransCore-M](https://github.com/PCIResearch/TransCore-M)   | [PCITransGPT-13B](https://github.com/PCIResearch/TransCore-M) | 136.67 |
|  12  | [MiniCPM-Llama3-V 2.5](https://github.com/OpenBMB/MiniCPM-V) |      [LLaMA3-8B](https://github.com/OpenBMB/MiniCPM-V)       | 136.67 |
|  13  |       [CogAgent](https://arxiv.org/pdf/2312.08914.pdf)       |         [Vicuna-7B](https://github.com/THUDM/CogVLM)         | 135.00 |
|  13  | [Bunny-8B](https://huggingface.co/BAAI/Bunny-v1_1-Llama-3-8B-V) |       [LLaMA3-8B](https://github.com/BAAI-DCAI/Bunny)        | 135.00 |
|  14  |        [LLaVA](https://arxiv.org/pdf/2304.08485.pdf)         |      [Vicuna-13B](https://github.com/haotian-liu/LLaVA)      | 133.33 |
|  15  |   [OmniLMM](https://github.com/OpenBMB/MiniCPM/#minicpm-v)   | [Zephyr-7B-beta](https://github.com/OpenBMB/MiniCPM/#minicpm-v) | 131.67 |
|  15  |    [Bunny-4B](https://huggingface.co/BAAI/Bunny-v1_1-4B)     | [Phi-3-Mini-4K-Instruct](https://github.com/BAAI-DCAI/Bunny) | 131.67 |
|  16  |     [BELLE-VL](https://huggingface.co/BELLE-2/BELLE-VL)      |     [Qwen-14B](https://huggingface.co/BELLE-2/BELLE-VL)      | 130.00 |
|  17  |   [LVIS-INSTRUCT4V](https://arxiv.org/pdf/2311.07574.pdf)    |    [Vicuna-13B](https://github.com/X2FD/LVIS-INSTRUCT4V)     | 128.33 |
|  17  |      [HyperLLaVA](https://arxiv.org/pdf/2403.13447.pdf)      |     [Vicuna-13B](https://github.com/dcdmllm/hyperllava)      | 128.33 |
|  17  |      [Qwen-VL-Chat](https://github.com/QwenLM/Qwen-VL/)      |         [Qwen-7B](https://github.com/QwenLM/Qwen-VL)         | 128.33 |
|  18  | [InternLM-XComposer-VL](https://github.com/InternLM/InternLM-XComposer) | [InternLM-7B](https://github.com/InternLM/InternLM-XComposer) | 126.67 |
|  18  |          [WeMM](https://github.com/scenarios/WeMM)           |       [InternLM-7B](https://github.com/scenarios/WeMM)       | 126.67 |
|  19  |           [PureMM](https://github.com/Q-MM/PureMM)           |         [Vicuna-13B](https://github.com/Q-MM/PureMM)         | 123.33 |
|  20  |  [DataOptim-LLaVA](https://github.com/BAAI-DCAI/DataOptim)   |     [Vicuna-13B](https://github.com/BAAI-DCAI/DataOptim)     | 121.67 |
|  21  |     [Monkey-Chat](https://arxiv.org/pdf/2311.06607.pdf)      |       [Qwen-7B](https://github.com/Yuliang-Liu/Monkey)       | 118.33 |
|  21  |      [MoE-LLaVA](https://arxiv.org/pdf/2401.15947.pdf)       |   [Phi-2.7B×4](https://github.com/PKU-YuanGroup/MoE-LLaVA)   | 118.33 |
|  22  |        [CogVLM](https://arxiv.org/pdf/2311.03079.pdf)        |         [Vicuna-7B](https://github.com/THUDM/CogVLM)         | 103.33 |
|  23  |         [GIT2](https://arxiv.org/pdf/2205.14100.pdf)         | [VQAv2-finetuned](https://github.com/microsoft/GenerativeImage2Text) | 96.67  |
|  24  | [GPT-4V](https://cdn.openai.com/papers/GPTV_System_Card.pdf) |   [-](https://cdn.openai.com/papers/GPTV_System_Card.pdf)    | 95.00  |
|  25  |   [MiniCPM](https://github.com/OpenBMB/MiniCPM/#minicpm-v)   | [MiniCPM-2B](https://github.com/OpenBMB/MiniCPM/#minicpm-v)  | 93.33  |
|  26  |         [Lynx](https://arxiv.org/pdf/2307.02469.pdf)         |      [Vicuna-7B](https://github.com/bytedance/lynx-llm)      | 90.00  |
|  26  | [Gemini Pro](https://storage.googleapis.com/deepmind-media/gemini/gemini_1_report.pdf) | [-](https://storage.googleapis.com/deepmind-media/gemini/gemini_1_report.pdf) | 90.00  |
|  27  |      [mPLUG-Owl2](https://arxiv.org/pdf/2311.04257.pdf)      | [LLaMA2-7B](https://github.com/X-PLUG/mPLUG-Owl/tree/main/mPLUG-Owl2) | 88.33  |
|  28  |        [Otter](https://arxiv.org/pdf/2305.03726.pdf)         |    [OTTER-Image-MPT7B](https://github.com/Luodian/Otter)     | 86.67  |
|  28  |   [LRV-Instruction](https://arxiv.org/pdf/2306.14565.pdf)    |    [LRV-7B](https://github.com/FuxiaoLiu/LRV-Instruction)    | 86.67  |
|  28  | [MiniCPM-V-2](https://github.com/OpenBMB/MiniCPM/#minicpm-v) | [MiniCPM-2B](https://github.com/OpenBMB/MiniCPM/#minicpm-v)  | 86.67  |
|  29  |        [MMICL](https://arxiv.org/pdf/2309.07915.pdf)         |        [FlanT5xxl](https://github.com/HaozheZhao/MIC)        | 81.67  |
|  29  |        [BLIVA](https://arxiv.org/pdf/2308.09936.pdf)         |       [FlanT5xxl](https://github.com/mlpc-ucsd/BLIVA)        | 81.67  |
|  30  |       [Cheetor](https://arxiv.org/pdf/2308.04152.pdf)        |       [Vicuna-7B](https://github.com/DCDmllm/Cheetah)        | 80.00  |
|  31  |        [BLIP-2](https://arxiv.org/pdf/2301.12597.pdf)        | [Flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/blip2) | 73.33  |
|  32  |     [InstructBLIP](https://arxiv.org/pdf/2305.06500.pdf)     | [FlanT5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/instructblip) | 66.67  |
|  32  |          [Muffin](https://github.com/thunlp/Muffin)          |        [Vicuna-13B](https://github.com/thunlp/Muffin)        | 66.67  |
|  33  |        [LaVIN](https://arxiv.org/pdf/2305.15023.pdf)         |       [LAVIN-13B](https://github.com/luogen1996/LaVIN)       | 63.33  |
|  33  |       [VPGTrans](https://arxiv.org/pdf/2305.01278.pdf)       |      [Vicuna-7B](https://github.com/VPGTrans/VPGTrans)       | 63.33  |
|  34  |    [Multimodal-GPT](https://arxiv.org/pdf/2305.04790.pdf)    | [Multimodal-GPT-9B](https://github.com/open-mmlab/Multimodal-GPT) | 58.33  |
|  35  |   [LLaMA-Adapter V2](https://arxiv.org/pdf/2304.15010.pdf)   | [LLaMA-Adapter-v2.1-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/llama_adapter_v2_multimodal7b) | 56.67  |
|  36  |      [mPLUG-Owl](https://arxiv.org/pdf/2304.14178.pdf)       | [LLaMA-7B](https://huggingface.co/MAGAer13/mplug-owl-llama-7b) | 50.00  |
|  36  |       [PandaGPT](https://arxiv.org/pdf/2305.16355.pdf)       |       [Vicuna-7B](https://github.com/yxuansu/PandaGPT)       | 50.00  |
|  37  |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     | 48.33  |
|  38  | [ImageBind_LLM](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main) | [LLaMA-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/imagebind_LLM) | 46.67  |
|  39  |      [MiniGPT-4](https://arxiv.org/pdf/2304.10592.pdf)       |    [Vicuna-13B](https://github.com/Vision-CAIR/MiniGPT-4)    | 43.33  |

### Color

| Rank |                            Model                             |                           Version                            | Score  |
| :--: | :----------------------------------------------------------: | :----------------------------------------------------------: | :----: |
|  🏅️   |       [InfMLLM](https://github.com/infly-ai/INF-MLLM)        |      [Vicuna-13B](https://github.com/infly-ai/INF-MLLM)      | 195.00 |
|  🏅️   | [InternLM-XComposer2-VL](https://github.com/InternLM/InternLM-XComposer) | [InternLM2-7B](https://github.com/InternLM/InternLM-XComposer) | 195.00 |
|  🏅️   | [LLaVA-1.6](https://llava-vl.github.io/blog/2024-01-30-llava-1-6/) |      [Vicuna-34B](https://github.com/haotian-liu/LLaVA)      | 195.00 |
|  🏅️   | [ChatTruth-7B](https://huggingface.co/mingdali/ChatTruth-7B) |   [Qwen-7B](https://huggingface.co/mingdali/ChatTruth-7B)    | 195.00 |
|  🏅️   | [Bunny-8B](https://huggingface.co/BAAI/Bunny-v1_1-Llama-3-8B-V) |       [LLaMA3-8B](https://github.com/BAAI-DCAI/Bunny)        | 195.00 |
|  🥈   |       [RBDash](https://github.com/RBDash-Team/RBDash)        |     [Vicuna-13B](https://github.com/RBDash-Team/RBDash)      | 190.00 |
|  🥈   |  [InternVL-Chat-V1.1](https://arxiv.org/pdf/2312.14238.pdf)  |     [LLaMA2-13B](https://github.com/OpenGVLab/InternVL/)     | 190.00 |
|  🥈   |      [MoE-LLaVA](https://arxiv.org/pdf/2401.15947.pdf)       |   [Phi-2.7B×4](https://github.com/PKU-YuanGroup/MoE-LLaVA)   | 190.00 |
|  🥉   |      [ShareGPT4V](https://arxiv.org/pdf/2311.12793.pdf)      | [Vicuna-13B](https://github.com/InternLM/InternLM-XComposer/tree/main/projects/ShareGPT4V) | 185.00 |
|  🥉   |  [TransCore-M](https://github.com/PCIResearch/TransCore-M)   | [PCITransGPT-13B](https://github.com/PCIResearch/TransCore-M) | 185.00 |
|  🥉   |     [Monkey-Chat](https://arxiv.org/pdf/2311.06607.pdf)      |       [Qwen-7B](https://github.com/Yuliang-Liu/Monkey)       | 185.00 |
|  🥉   | [360VL](https://github.com/360CVGroup/360VL?tab=readme-ov-file) | [LLaMA3-70B](https://github.com/360CVGroup/360VL?tab=readme-ov-file) | 185.00 |
|  4   |        [BLIVA](https://arxiv.org/pdf/2308.09936.pdf)         |       [FlanT5xxl](https://github.com/mlpc-ucsd/BLIVA)        | 180.00 |
|  4   |   [LVIS-INSTRUCT4V](https://arxiv.org/pdf/2311.07574.pdf)    |    [Vicuna-13B](https://github.com/X2FD/LVIS-INSTRUCT4V)     | 180.00 |
|  4   | [Qwen-VL-Plus](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start) | [-](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start) | 180.00 |
|  4   |       [Honeybee](https://arxiv.org/pdf/2312.06742.pdf)       |     [Vicuna-13B](https://github.com/kakaobrain/honeybee)     | 180.00 |
|  4   | [Qwen-VL-Max](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start) | [-](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start) | 180.00 |
|  4   |   [OmniLMM](https://github.com/OpenBMB/MiniCPM/#minicpm-v)   | [Zephyr-7B-beta](https://github.com/OpenBMB/MiniCPM/#minicpm-v) | 180.00 |
|  4   | [MindSource-VL-Chat](https://github.com/luogen1996/LLaVA-HR) |   [MindSource-7B](https://github.com/luogen1996/LLaVA-HR)    | 180.00 |
|  4   |      [HyperLLaVA](https://arxiv.org/pdf/2403.13447.pdf)      |     [Vicuna-13B](https://github.com/dcdmllm/hyperllava)      | 180.00 |
|  5   |    [InternVL-Chat-V1.5](https://arxiv.org/pdf/2404.16821)    |    [InternLM2-20B](https://github.com/OpenGVLab/InternVL)    | 178.33 |
|  6   |     [BELLE-VL](https://huggingface.co/BELLE-2/BELLE-VL)      |     [Qwen-14B](https://huggingface.co/BELLE-2/BELLE-VL)      | 175.00 |
|  6   |    [JT-VL-Chat](https://github.com/jiutiancv/JT-VL-Chat)     |         [-](https://github.com/jiutiancv/JT-VL-Chat)         | 175.00 |
|  7   |        [LLaVA](https://arxiv.org/pdf/2304.08485.pdf)         |      [Vicuna-13B](https://github.com/haotian-liu/LLaVA)      | 170.00 |
|  7   |         [Lynx](https://arxiv.org/pdf/2307.02469.pdf)         |      [Vicuna-7B](https://github.com/bytedance/lynx-llm)      | 170.00 |
|  7   |      [Qwen-VL-Chat](https://github.com/QwenLM/Qwen-VL/)      |         [Qwen-7B](https://github.com/QwenLM/Qwen-VL)         | 170.00 |
|  7   |           [PureMM](https://github.com/Q-MM/PureMM)           |         [Vicuna-13B](https://github.com/Q-MM/PureMM)         | 170.00 |
|  7   |    [Bunny-4B](https://huggingface.co/BAAI/Bunny-v1_1-4B)     | [Phi-3-Mini-4K-Instruct](https://github.com/BAAI-DCAI/Bunny) | 170.00 |
|  8   |          [WeMM](https://github.com/scenarios/WeMM)           |       [InternLM-7B](https://github.com/scenarios/WeMM)       | 168.33 |
|  9   |   [LRV-Instruction](https://arxiv.org/pdf/2306.14565.pdf)    |    [LRV-7B](https://github.com/FuxiaoLiu/LRV-Instruction)    | 165.00 |
|  9   | [InternLM-XComposer-VL](https://github.com/InternLM/InternLM-XComposer) | [InternLM-7B](https://github.com/InternLM/InternLM-XComposer) | 165.00 |
|  9   |          [Muffin](https://github.com/thunlp/Muffin)          |        [Vicuna-13B](https://github.com/thunlp/Muffin)        | 165.00 |
|  9   | [MiniCPM-Llama3-V 2.5](https://github.com/OpenBMB/MiniCPM-V) |      [LLaMA3-8B](https://github.com/OpenBMB/MiniCPM-V)       | 165.00 |
|  10  | [Gemini Pro](https://storage.googleapis.com/deepmind-media/gemini/gemini_1_report.pdf) | [-](https://storage.googleapis.com/deepmind-media/gemini/gemini_1_report.pdf) | 163.33 |
|  11  | [SPHINX](https://github.com/Alpha-VLLM/LLaMA2-Accessory/tree/main/SPHINX) | [LLaMA2-13B](https://github.com/Alpha-VLLM/LLaMA2-Accessory/tree/main/SPHINX) | 160.00 |
|  11  |       [CogAgent](https://arxiv.org/pdf/2312.08914.pdf)       |         [Vicuna-7B](https://github.com/THUDM/CogVLM)         | 160.00 |
|  11  |        [CogVLM](https://arxiv.org/pdf/2311.03079.pdf)        |         [Vicuna-7B](https://github.com/THUDM/CogVLM)         | 160.00 |
|  12  |   [MiniCPM](https://github.com/OpenBMB/MiniCPM/#minicpm-v)   | [MiniCPM-2B](https://github.com/OpenBMB/MiniCPM/#minicpm-v)  | 158.33 |
|  12  |         [GIT2](https://arxiv.org/pdf/2205.14100.pdf)         | [VQAv2-finetuned](https://github.com/microsoft/GenerativeImage2Text) | 158.33 |
|  13  |        [MMICL](https://arxiv.org/pdf/2309.07915.pdf)         |        [FlanT5xxl](https://github.com/HaozheZhao/MIC)        | 156.67 |
|  14  |  [DataOptim-LLaVA](https://github.com/BAAI-DCAI/DataOptim)   |     [Vicuna-13B](https://github.com/BAAI-DCAI/DataOptim)     | 155.00 |
|  15  |     [InstructBLIP](https://arxiv.org/pdf/2305.06500.pdf)     | [FlanT5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/instructblip) | 153.33 |
|  16  | [GPT-4V](https://cdn.openai.com/papers/GPTV_System_Card.pdf) |   [-](https://cdn.openai.com/papers/GPTV_System_Card.pdf)    | 150.00 |
|  16  |      [mPLUG-Owl2](https://arxiv.org/pdf/2311.04257.pdf)      | [LLaMA2-7B](https://github.com/X-PLUG/mPLUG-Owl/tree/main/mPLUG-Owl2) | 150.00 |
|  17  |        [BLIP-2](https://arxiv.org/pdf/2301.12597.pdf)        | [Flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/blip2) | 148.33 |
|  18  | [MiniCPM-V-2](https://github.com/OpenBMB/MiniCPM/#minicpm-v) | [MiniCPM-2B](https://github.com/OpenBMB/MiniCPM/#minicpm-v)  | 145.00 |
|  19  |   [LLaMA-Adapter V2](https://arxiv.org/pdf/2304.15010.pdf)   | [LLaMA-Adapter-v2.1-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/llama_adapter_v2_multimodal7b) | 118.33 |
|  20  |       [Cheetor](https://arxiv.org/pdf/2308.04152.pdf)        |       [Vicuna-7B](https://github.com/DCDmllm/Cheetah)        | 116.67 |
|  21  |        [Otter](https://arxiv.org/pdf/2305.03726.pdf)         |    [OTTER-Image-MPT7B](https://github.com/Luodian/Otter)     | 113.33 |
|  22  |      [MiniGPT-4](https://arxiv.org/pdf/2304.10592.pdf)       |    [Vicuna-13B](https://github.com/Vision-CAIR/MiniGPT-4)    | 75.00  |
|  22  |        [LaVIN](https://arxiv.org/pdf/2305.15023.pdf)         |       [LAVIN-13B](https://github.com/luogen1996/LaVIN)       | 75.00  |
|  23  | [ImageBind_LLM](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main) | [LLaMA-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/imagebind_LLM) | 73.33  |
|  23  |       [VPGTrans](https://arxiv.org/pdf/2305.01278.pdf)       |      [Vicuna-7B](https://github.com/VPGTrans/VPGTrans)       | 73.33  |
|  24  |    [Multimodal-GPT](https://arxiv.org/pdf/2305.04790.pdf)    | [Multimodal-GPT-9B](https://github.com/open-mmlab/Multimodal-GPT) | 68.33  |
|  25  |      [mPLUG-Owl](https://arxiv.org/pdf/2304.14178.pdf)       | [LLaMA-7B](https://huggingface.co/MAGAer13/mplug-owl-llama-7b) | 55.00  |
|  25  |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     | 55.00  |
|  26  |       [PandaGPT](https://arxiv.org/pdf/2305.16355.pdf)       |       [Vicuna-7B](https://github.com/yxuansu/PandaGPT)       | 50.00  |

### Poster

| Rank |                            Model                             |                           Version                            | Score  |
| :--: | :----------------------------------------------------------: | :----------------------------------------------------------: | :----: |
|  🏅️   | [GPT-4V](https://cdn.openai.com/papers/GPTV_System_Card.pdf) |   [-](https://cdn.openai.com/papers/GPTV_System_Card.pdf)    | 192.18 |
|  🥈   |           [PureMM](https://github.com/Q-MM/PureMM)           |         [Vicuna-13B](https://github.com/Q-MM/PureMM)         | 191.50 |
|  🥉   | [Qwen-VL-Max](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start) | [-](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start) | 187.76 |
|  4   |       [InfMLLM](https://github.com/infly-ai/INF-MLLM)        |      [Vicuna-13B](https://github.com/infly-ai/INF-MLLM)      | 183.33 |
|  5   | [Qwen-VL-Plus](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start) | [-](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start) | 181.63 |
|  6   |     [Monkey-Chat](https://arxiv.org/pdf/2311.06607.pdf)      |       [Qwen-7B](https://github.com/Yuliang-Liu/Monkey)       | 178.91 |
|  7   |      [Qwen-VL-Chat](https://github.com/QwenLM/Qwen-VL/)      |         [Qwen-7B](https://github.com/QwenLM/Qwen-VL)         | 178.57 |
|  8   | [360VL](https://github.com/360CVGroup/360VL?tab=readme-ov-file) | [LLaMA3-70B](https://github.com/360CVGroup/360VL?tab=readme-ov-file) | 176.87 |
|  9   | [MiniCPM-Llama3-V 2.5](https://github.com/OpenBMB/MiniCPM-V) |      [LLaMA3-8B](https://github.com/OpenBMB/MiniCPM-V)       | 175.85 |
|  10  | [ChatTruth-7B](https://huggingface.co/mingdali/ChatTruth-7B) |   [Qwen-7B](https://huggingface.co/mingdali/ChatTruth-7B)    | 174.15 |
|  11  |    [InternVL-Chat-V1.5](https://arxiv.org/pdf/2404.16821)    |    [InternLM2-20B](https://github.com/OpenGVLab/InternVL)    | 173.81 |
|  12  |   [OmniLMM](https://github.com/OpenBMB/MiniCPM/#minicpm-v)   | [Zephyr-7B-beta](https://github.com/OpenBMB/MiniCPM/#minicpm-v) | 171.43 |
|  13  | [InternLM-XComposer2-VL](https://github.com/InternLM/InternLM-XComposer) | [InternLM2-7B](https://github.com/InternLM/InternLM-XComposer) | 171.09 |
|  14  |       [Honeybee](https://arxiv.org/pdf/2312.06742.pdf)       |     [Vicuna-13B](https://github.com/kakaobrain/honeybee)     | 170.07 |
|  15  |  [DataOptim-LLaVA](https://github.com/BAAI-DCAI/DataOptim)   |     [Vicuna-13B](https://github.com/BAAI-DCAI/DataOptim)     | 169.73 |
|  16  | [LLaVA-1.6](https://llava-vl.github.io/blog/2024-01-30-llava-1-6/) |      [Vicuna-34B](https://github.com/haotian-liu/LLaVA)      | 169.39 |
|  17  |      [ShareGPT4V](https://arxiv.org/pdf/2311.12793.pdf)      | [Vicuna-13B](https://github.com/InternLM/InternLM-XComposer/tree/main/projects/ShareGPT4V) | 169.05 |
|  18  |    [JT-VL-Chat](https://github.com/jiutiancv/JT-VL-Chat)     |         [-](https://github.com/jiutiancv/JT-VL-Chat)         | 168.71 |
|  19  |       [CogAgent](https://arxiv.org/pdf/2312.08914.pdf)       |         [Vicuna-7B](https://github.com/THUDM/CogVLM)         | 167.35 |
|  20  | [Bunny-8B](https://huggingface.co/BAAI/Bunny-v1_1-Llama-3-8B-V) |       [LLaMA3-8B](https://github.com/BAAI-DCAI/Bunny)        | 167.35 |
|  21  |     [BELLE-VL](https://huggingface.co/BELLE-2/BELLE-VL)      |     [Qwen-14B](https://huggingface.co/BELLE-2/BELLE-VL)      | 166.33 |
|  22  |       [RBDash](https://github.com/RBDash-Team/RBDash)        |     [Vicuna-13B](https://github.com/RBDash-Team/RBDash)      | 165.99 |
|  23  | [MiniCPM-V-2](https://github.com/OpenBMB/MiniCPM/#minicpm-v) | [MiniCPM-2B](https://github.com/OpenBMB/MiniCPM/#minicpm-v)  | 165.31 |
|  24  | [Gemini Pro](https://storage.googleapis.com/deepmind-media/gemini/gemini_1_report.pdf) | [-](https://storage.googleapis.com/deepmind-media/gemini/gemini_1_report.pdf) | 164.97 |
|  25  |      [HyperLLaVA](https://arxiv.org/pdf/2403.13447.pdf)      |     [Vicuna-13B](https://github.com/dcdmllm/hyperllava)      | 164.97 |
|  26  | [SPHINX](https://github.com/Alpha-VLLM/LLaMA2-Accessory/tree/main/SPHINX) | [LLaMA2-13B](https://github.com/Alpha-VLLM/LLaMA2-Accessory/tree/main/SPHINX) | 164.29 |
|  27  |   [LVIS-INSTRUCT4V](https://arxiv.org/pdf/2311.07574.pdf)    |    [Vicuna-13B](https://github.com/X2FD/LVIS-INSTRUCT4V)     | 162.59 |
|  28  | [InternLM-XComposer-VL](https://github.com/InternLM/InternLM-XComposer) | [InternLM-7B](https://github.com/InternLM/InternLM-XComposer) | 161.90 |
|  29  |  [InternVL-Chat-V1.1](https://arxiv.org/pdf/2312.14238.pdf)  |     [LLaMA2-13B](https://github.com/OpenGVLab/InternVL/)     | 161.22 |
|  30  |        [LLaVA](https://arxiv.org/pdf/2304.08485.pdf)         |      [Vicuna-13B](https://github.com/haotian-liu/LLaVA)      | 160.54 |
|  31  |          [WeMM](https://github.com/scenarios/WeMM)           |       [InternLM-7B](https://github.com/scenarios/WeMM)       | 160.54 |
|  32  |  [TransCore-M](https://github.com/PCIResearch/TransCore-M)   | [PCITransGPT-13B](https://github.com/PCIResearch/TransCore-M) | 160.20 |
|  33  |      [mPLUG-Owl2](https://arxiv.org/pdf/2311.04257.pdf)      | [LLaMA2-7B](https://github.com/X-PLUG/mPLUG-Owl/tree/main/mPLUG-Owl2) | 160.20 |
|  34  |   [MiniCPM](https://github.com/OpenBMB/MiniCPM/#minicpm-v)   | [MiniCPM-2B](https://github.com/OpenBMB/MiniCPM/#minicpm-v)  | 158.50 |
|  35  | [MindSource-VL-Chat](https://github.com/luogen1996/LLaVA-HR) |   [MindSource-7B](https://github.com/luogen1996/LLaVA-HR)    | 155.10 |
|  36  |        [BLIVA](https://arxiv.org/pdf/2308.09936.pdf)         |       [FlanT5xxl](https://github.com/mlpc-ucsd/BLIVA)        | 155.10 |
|  37  |    [Bunny-4B](https://huggingface.co/BAAI/Bunny-v1_1-4B)     | [Phi-3-Mini-4K-Instruct](https://github.com/BAAI-DCAI/Bunny) | 150.34 |
|  38  |   [LLaMA-Adapter V2](https://arxiv.org/pdf/2304.15010.pdf)   | [LLaMA-Adapter-v2.1-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/llama_adapter_v2_multimodal7b) | 147.96 |
|  39  |       [Cheetor](https://arxiv.org/pdf/2308.04152.pdf)        |       [Vicuna-7B](https://github.com/DCDmllm/Cheetah)        | 147.28 |
|  40  |        [CogVLM](https://arxiv.org/pdf/2311.03079.pdf)        |         [Vicuna-7B](https://github.com/THUDM/CogVLM)         | 146.94 |
|  41  |        [MMICL](https://arxiv.org/pdf/2309.07915.pdf)         |        [FlanT5xxl](https://github.com/HaozheZhao/MIC)        | 146.26 |
|  42  |        [BLIP-2](https://arxiv.org/pdf/2301.12597.pdf)        | [Flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/blip2) | 141.84 |
|  43  |   [LRV-Instruction](https://arxiv.org/pdf/2306.14565.pdf)    |    [LRV-7B](https://github.com/FuxiaoLiu/LRV-Instruction)    | 139.04 |
|  44  |        [Otter](https://arxiv.org/pdf/2305.03726.pdf)         |    [OTTER-Image-MPT7B](https://github.com/Luodian/Otter)     | 138.78 |
|  45  |          [Muffin](https://github.com/thunlp/Muffin)          |        [Vicuna-13B](https://github.com/thunlp/Muffin)        | 137.76 |
|  46  |      [mPLUG-Owl](https://arxiv.org/pdf/2304.14178.pdf)       | [LLaMA-7B](https://huggingface.co/MAGAer13/mplug-owl-llama-7b) | 136.05 |
|  47  |         [Lynx](https://arxiv.org/pdf/2307.02469.pdf)         |      [Vicuna-7B](https://github.com/bytedance/lynx-llm)      | 124.83 |
|  48  |     [InstructBLIP](https://arxiv.org/pdf/2305.06500.pdf)     | [FlanT5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/instructblip) | 123.81 |
|  49  |         [GIT2](https://arxiv.org/pdf/2205.14100.pdf)         | [VQAv2-finetuned](https://github.com/microsoft/GenerativeImage2Text) | 112.59 |
|  50  |      [MoE-LLaVA](https://arxiv.org/pdf/2401.15947.pdf)       |   [Phi-2.7B×4](https://github.com/PKU-YuanGroup/MoE-LLaVA)   | 99.32  |
|  51  |       [VPGTrans](https://arxiv.org/pdf/2305.01278.pdf)       |      [Vicuna-7B](https://github.com/VPGTrans/VPGTrans)       | 84.01  |
|  52  |        [LaVIN](https://arxiv.org/pdf/2305.15023.pdf)         |       [LAVIN-13B](https://github.com/luogen1996/LaVIN)       | 79.59  |
|  53  |       [PandaGPT](https://arxiv.org/pdf/2305.16355.pdf)       |       [Vicuna-7B](https://github.com/yxuansu/PandaGPT)       | 76.53  |
|  54  |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     | 65.99  |
|  55  | [ImageBind_LLM](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main) | [LLaMA-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/imagebind_LLM) | 64.97  |
|  56  |    [Multimodal-GPT](https://arxiv.org/pdf/2305.04790.pdf)    | [Multimodal-GPT-9B](https://github.com/open-mmlab/Multimodal-GPT) | 57.82  |
|  57  |      [MiniGPT-4](https://arxiv.org/pdf/2304.10592.pdf)       |    [Vicuna-13B](https://github.com/Vision-CAIR/MiniGPT-4)    | 41.84  |

### Celebrity

| Rank |                            Model                             |                           Version                            | Score  |
| :--: | :----------------------------------------------------------: | :----------------------------------------------------------: | :----: |
|  🏅️   | [Qwen-VL-Max](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start) | [-](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start) | 184.12 |
|  🏅️   | [Qwen-VL-Plus](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start) | [-](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start) | 184.12 |
|  🥈   |           [PureMM](https://github.com/Q-MM/PureMM)           |         [Vicuna-13B](https://github.com/Q-MM/PureMM)         | 182.35 |
|  🥉   |          [WeMM](https://github.com/scenarios/WeMM)           |       [InternLM-7B](https://github.com/scenarios/WeMM)       | 179.12 |
|  4   | [SPHINX](https://github.com/Alpha-VLLM/LLaMA2-Accessory/tree/main/SPHINX) | [LLaMA2-13B](https://github.com/Alpha-VLLM/LLaMA2-Accessory/tree/main/SPHINX) | 177.94 |
|  5   | [ChatTruth-7B](https://huggingface.co/mingdali/ChatTruth-7B) |   [Qwen-7B](https://huggingface.co/mingdali/ChatTruth-7B)    | 177.65 |
|  6   |       [Honeybee](https://arxiv.org/pdf/2312.06742.pdf)       |     [Vicuna-13B](https://github.com/kakaobrain/honeybee)     | 177.06 |
|  7   | [Bunny-8B](https://huggingface.co/BAAI/Bunny-v1_1-Llama-3-8B-V) |       [LLaMA3-8B](https://github.com/BAAI-DCAI/Bunny)        | 175.29 |
|  8   |        [Otter](https://arxiv.org/pdf/2305.03726.pdf)         |    [OTTER-Image-MPT7B](https://github.com/Luodian/Otter)     | 172.65 |
|  9   |   [OmniLMM](https://github.com/OpenBMB/MiniCPM/#minicpm-v)   | [Zephyr-7B-beta](https://github.com/OpenBMB/MiniCPM/#minicpm-v) | 172.06 |
|  10  |       [RBDash](https://github.com/RBDash-Team/RBDash)        |     [Vicuna-13B](https://github.com/RBDash-Team/RBDash)      | 170.00 |
|  11  | [360VL](https://github.com/360CVGroup/360VL?tab=readme-ov-file) | [LLaMA3-70B](https://github.com/360CVGroup/360VL?tab=readme-ov-file) | 168.24 |
|  12  |       [InfMLLM](https://github.com/infly-ai/INF-MLLM)        |      [Vicuna-13B](https://github.com/infly-ai/INF-MLLM)      | 164.41 |
|  12  |      [mPLUG-Owl2](https://arxiv.org/pdf/2311.04257.pdf)      | [LLaMA2-7B](https://github.com/X-PLUG/mPLUG-Owl/tree/main/mPLUG-Owl2) | 164.41 |
|  13  |       [Cheetor](https://arxiv.org/pdf/2308.04152.pdf)        |       [Vicuna-7B](https://github.com/DCDmllm/Cheetah)        | 164.12 |
|  14  |      [HyperLLaVA](https://arxiv.org/pdf/2403.13447.pdf)      |     [Vicuna-13B](https://github.com/dcdmllm/hyperllava)      | 162.06 |
|  15  |   [LVIS-INSTRUCT4V](https://arxiv.org/pdf/2311.07574.pdf)    |    [Vicuna-13B](https://github.com/X2FD/LVIS-INSTRUCT4V)     | 161.47 |
|  15  |    [JT-VL-Chat](https://github.com/jiutiancv/JT-VL-Chat)     |         [-](https://github.com/jiutiancv/JT-VL-Chat)         | 161.47 |
|  16  | [LLaVA-1.6](https://llava-vl.github.io/blog/2024-01-30-llava-1-6/) |      [Vicuna-34B](https://github.com/haotian-liu/LLaVA)      | 160.00 |
|  17  |  [DataOptim-LLaVA](https://github.com/BAAI-DCAI/DataOptim)   |     [Vicuna-13B](https://github.com/BAAI-DCAI/DataOptim)     | 159.41 |
|  18  | [MiniCPM-Llama3-V 2.5](https://github.com/OpenBMB/MiniCPM-V) |      [LLaMA3-8B](https://github.com/OpenBMB/MiniCPM-V)       | 157.94 |
|  19  |   [MiniCPM](https://github.com/OpenBMB/MiniCPM/#minicpm-v)   | [MiniCPM-2B](https://github.com/OpenBMB/MiniCPM/#minicpm-v)  | 155.59 |
|  20  |  [InternVL-Chat-V1.1](https://arxiv.org/pdf/2312.14238.pdf)  |     [LLaMA2-13B](https://github.com/OpenGVLab/InternVL/)     | 154.71 |
|  21  |      [ShareGPT4V](https://arxiv.org/pdf/2311.12793.pdf)      | [Vicuna-13B](https://github.com/InternLM/InternLM-XComposer/tree/main/projects/ShareGPT4V) | 153.82 |
|  21  | [InternLM-XComposer2-VL](https://github.com/InternLM/InternLM-XComposer) | [InternLM2-7B](https://github.com/InternLM/InternLM-XComposer) | 153.82 |
|  22  |        [LLaVA](https://arxiv.org/pdf/2304.08485.pdf)         |      [Vicuna-13B](https://github.com/haotian-liu/LLaVA)      | 152.94 |
|  23  |    [Bunny-4B](https://huggingface.co/BAAI/Bunny-v1_1-4B)     | [Phi-3-Mini-4K-Instruct](https://github.com/BAAI-DCAI/Bunny) | 151.76 |
|  24  | [InternLM-XComposer-VL](https://github.com/InternLM/InternLM-XComposer) | [InternLM-7B](https://github.com/InternLM/InternLM-XComposer) | 150.29 |
|  25  |       [CogAgent](https://arxiv.org/pdf/2312.08914.pdf)       |         [Vicuna-7B](https://github.com/THUDM/CogVLM)         | 147.94 |
|  25  |      [MoE-LLaVA](https://arxiv.org/pdf/2401.15947.pdf)       |   [Phi-2.7B×4](https://github.com/PKU-YuanGroup/MoE-LLaVA)   | 147.94 |
|  26  | [Gemini Pro](https://storage.googleapis.com/deepmind-media/gemini/gemini_1_report.pdf) | [-](https://storage.googleapis.com/deepmind-media/gemini/gemini_1_report.pdf) | 147.35 |
|  27  |         [GIT2](https://arxiv.org/pdf/2205.14100.pdf)         | [VQAv2-finetuned](https://github.com/microsoft/GenerativeImage2Text) | 145.88 |
|  28  |  [TransCore-M](https://github.com/PCIResearch/TransCore-M)   | [PCITransGPT-13B](https://github.com/PCIResearch/TransCore-M) | 145.29 |
|  29  |     [Monkey-Chat](https://arxiv.org/pdf/2311.06607.pdf)      |       [Qwen-7B](https://github.com/Yuliang-Liu/Monkey)       | 142.65 |
|  30  |        [MMICL](https://arxiv.org/pdf/2309.07915.pdf)         |        [FlanT5xxl](https://github.com/HaozheZhao/MIC)        | 141.76 |
|  31  | [MiniCPM-V-2](https://github.com/OpenBMB/MiniCPM/#minicpm-v) | [MiniCPM-2B](https://github.com/OpenBMB/MiniCPM/#minicpm-v)  | 140.88 |
|  31  |        [BLIVA](https://arxiv.org/pdf/2308.09936.pdf)         |       [FlanT5xxl](https://github.com/mlpc-ucsd/BLIVA)        | 140.88 |
|  32  |    [InternVL-Chat-V1.5](https://arxiv.org/pdf/2404.16821)    |    [InternLM2-20B](https://github.com/OpenGVLab/InternVL)    | 138.53 |
|  33  |     [BELLE-VL](https://huggingface.co/BELLE-2/BELLE-VL)      |     [Qwen-14B](https://huggingface.co/BELLE-2/BELLE-VL)      | 136.76 |
|  33  |   [LLaMA-Adapter V2](https://arxiv.org/pdf/2304.15010.pdf)   | [LLaMA-Adapter-v2.1-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/llama_adapter_v2_multimodal7b) | 136.76 |
|  34  | [MindSource-VL-Chat](https://github.com/luogen1996/LLaVA-HR) |   [MindSource-7B](https://github.com/luogen1996/LLaVA-HR)    | 126.47 |
|  35  |      [Qwen-VL-Chat](https://github.com/QwenLM/Qwen-VL/)      |         [Qwen-7B](https://github.com/QwenLM/Qwen-VL)         | 120.59 |
|  36  |         [Lynx](https://arxiv.org/pdf/2307.02469.pdf)         |      [Vicuna-7B](https://github.com/bytedance/lynx-llm)      | 118.24 |
|  37  |        [CogVLM](https://arxiv.org/pdf/2311.03079.pdf)        |         [Vicuna-7B](https://github.com/THUDM/CogVLM)         | 115.29 |
|  38  |   [LRV-Instruction](https://arxiv.org/pdf/2306.14565.pdf)    |    [LRV-7B](https://github.com/FuxiaoLiu/LRV-Instruction)    | 112.65 |
|  39  |        [BLIP-2](https://arxiv.org/pdf/2301.12597.pdf)        | [Flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/blip2) | 105.59 |
|  40  |     [InstructBLIP](https://arxiv.org/pdf/2305.06500.pdf)     | [FlanT5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/instructblip) | 101.18 |
|  41  |      [mPLUG-Owl](https://arxiv.org/pdf/2304.14178.pdf)       | [LLaMA-7B](https://huggingface.co/MAGAer13/mplug-owl-llama-7b) | 100.29 |
|  42  |          [Muffin](https://github.com/thunlp/Muffin)          |        [Vicuna-13B](https://github.com/thunlp/Muffin)        | 81.76  |
|  43  | [ImageBind_LLM](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main) | [LLaMA-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/imagebind_LLM) | 76.47  |
|  44  |    [Multimodal-GPT](https://arxiv.org/pdf/2305.04790.pdf)    | [Multimodal-GPT-9B](https://github.com/open-mmlab/Multimodal-GPT) | 73.82  |
|  45  |       [PandaGPT](https://arxiv.org/pdf/2305.16355.pdf)       |       [Vicuna-7B](https://github.com/yxuansu/PandaGPT)       | 57.06  |
|  46  |      [MiniGPT-4](https://arxiv.org/pdf/2304.10592.pdf)       |    [Vicuna-13B](https://github.com/Vision-CAIR/MiniGPT-4)    | 54.41  |
|  47  |       [VPGTrans](https://arxiv.org/pdf/2305.01278.pdf)       |      [Vicuna-7B](https://github.com/VPGTrans/VPGTrans)       | 53.53  |
|  48  |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     | 53.24  |
|  49  |        [LaVIN](https://arxiv.org/pdf/2305.15023.pdf)         |       [LAVIN-13B](https://github.com/luogen1996/LaVIN)       | 47.35  |
|  50  | [GPT-4V](https://cdn.openai.com/papers/GPTV_System_Card.pdf) |   [-](https://cdn.openai.com/papers/GPTV_System_Card.pdf)    |  0.00  |

### Scene

| Rank |                            Model                             |                           Version                            | Score  |
| :--: | :----------------------------------------------------------: | :----------------------------------------------------------: | :----: |
|  🏅️   |       [InfMLLM](https://github.com/infly-ai/INF-MLLM)        |      [Vicuna-13B](https://github.com/infly-ai/INF-MLLM)      | 176.75 |
|  🥈   |          [WeMM](https://github.com/scenarios/WeMM)           |       [InternLM-7B](https://github.com/scenarios/WeMM)       | 176.25 |
|  🥉   | [Qwen-VL-Max](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start) | [-](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start) | 173.00 |
|  4   |      [ShareGPT4V](https://arxiv.org/pdf/2311.12793.pdf)      | [Vicuna-13B](https://github.com/InternLM/InternLM-XComposer/tree/main/projects/ShareGPT4V) | 168.00 |
|  5   | [ChatTruth-7B](https://huggingface.co/mingdali/ChatTruth-7B) |   [Qwen-7B](https://huggingface.co/mingdali/ChatTruth-7B)    | 167.75 |
|  6   |  [DataOptim-LLaVA](https://github.com/BAAI-DCAI/DataOptim)   |     [Vicuna-13B](https://github.com/BAAI-DCAI/DataOptim)     | 166.50 |
|  6   |      [HyperLLaVA](https://arxiv.org/pdf/2403.13447.pdf)      |     [Vicuna-13B](https://github.com/dcdmllm/hyperllava)      | 166.50 |
|  7   | [InternLM-XComposer2-VL](https://github.com/InternLM/InternLM-XComposer) | [InternLM2-7B](https://github.com/InternLM/InternLM-XComposer) | 164.75 |
|  7   | [360VL](https://github.com/360CVGroup/360VL?tab=readme-ov-file) | [LLaMA3-70B](https://github.com/360CVGroup/360VL?tab=readme-ov-file) | 164.75 |
|  8   |         [Lynx](https://arxiv.org/pdf/2307.02469.pdf)         |      [Vicuna-7B](https://github.com/bytedance/lynx-llm)      | 164.50 |
|  8   | [LLaVA-1.6](https://llava-vl.github.io/blog/2024-01-30-llava-1-6/) |      [Vicuna-34B](https://github.com/haotian-liu/LLaVA)      | 164.50 |
|  9   |    [Bunny-4B](https://huggingface.co/BAAI/Bunny-v1_1-4B)     | [Phi-3-Mini-4K-Instruct](https://github.com/BAAI-DCAI/Bunny) | 163.50 |
|  10  |   [LVIS-INSTRUCT4V](https://arxiv.org/pdf/2311.07574.pdf)    |    [Vicuna-13B](https://github.com/X2FD/LVIS-INSTRUCT4V)     | 163.25 |
|  11  |           [PureMM](https://github.com/Q-MM/PureMM)           |         [Vicuna-13B](https://github.com/Q-MM/PureMM)         | 162.75 |
|  12  |       [Honeybee](https://arxiv.org/pdf/2312.06742.pdf)       |     [Vicuna-13B](https://github.com/kakaobrain/honeybee)     | 162.00 |
|  13  |     [Monkey-Chat](https://arxiv.org/pdf/2311.06607.pdf)      |       [Qwen-7B](https://github.com/Yuliang-Liu/Monkey)       | 161.75 |
|  13  | [MindSource-VL-Chat](https://github.com/luogen1996/LLaVA-HR) |   [MindSource-7B](https://github.com/luogen1996/LLaVA-HR)    | 161.75 |
|  14  |        [LLaVA](https://arxiv.org/pdf/2304.08485.pdf)         |      [Vicuna-13B](https://github.com/haotian-liu/LLaVA)      | 161.25 |
|  15  |  [TransCore-M](https://github.com/PCIResearch/TransCore-M)   | [PCITransGPT-13B](https://github.com/PCIResearch/TransCore-M) | 161.00 |
|  16  |       [RBDash](https://github.com/RBDash-Team/RBDash)        |     [Vicuna-13B](https://github.com/RBDash-Team/RBDash)      | 160.25 |
|  17  | [SPHINX](https://github.com/Alpha-VLLM/LLaMA2-Accessory/tree/main/SPHINX) | [LLaMA2-13B](https://github.com/Alpha-VLLM/LLaMA2-Accessory/tree/main/SPHINX) | 160.00 |
|  18  | [InternLM-XComposer-VL](https://github.com/InternLM/InternLM-XComposer) | [InternLM-7B](https://github.com/InternLM/InternLM-XComposer) | 159.75 |
|  19  |        [CogVLM](https://arxiv.org/pdf/2311.03079.pdf)        |         [Vicuna-7B](https://github.com/THUDM/CogVLM)         | 159.25 |
|  20  |        [Otter](https://arxiv.org/pdf/2305.03726.pdf)         |    [OTTER-Image-MPT7B](https://github.com/Luodian/Otter)     | 158.75 |
|  21  |         [GIT2](https://arxiv.org/pdf/2205.14100.pdf)         | [VQAv2-finetuned](https://github.com/microsoft/GenerativeImage2Text) | 158.50 |
|  22  |   [MiniCPM](https://github.com/OpenBMB/MiniCPM/#minicpm-v)   | [MiniCPM-2B](https://github.com/OpenBMB/MiniCPM/#minicpm-v)  | 157.75 |
|  22  |    [JT-VL-Chat](https://github.com/jiutiancv/JT-VL-Chat)     |         [-](https://github.com/jiutiancv/JT-VL-Chat)         | 157.75 |
|  23  |   [LLaMA-Adapter V2](https://arxiv.org/pdf/2304.15010.pdf)   | [LLaMA-Adapter-v2.1-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/llama_adapter_v2_multimodal7b) | 156.25 |
|  23  |     [BELLE-VL](https://huggingface.co/BELLE-2/BELLE-VL)      |     [Qwen-14B](https://huggingface.co/BELLE-2/BELLE-VL)      | 156.25 |
|  24  |       [Cheetor](https://arxiv.org/pdf/2308.04152.pdf)        |       [Vicuna-7B](https://github.com/DCDmllm/Cheetah)        | 156.00 |
|  25  |  [InternVL-Chat-V1.1](https://arxiv.org/pdf/2312.14238.pdf)  |     [LLaMA2-13B](https://github.com/OpenGVLab/InternVL/)     | 155.75 |
|  26  |    [InternVL-Chat-V1.5](https://arxiv.org/pdf/2404.16821)    |    [InternLM2-20B](https://github.com/OpenGVLab/InternVL)    | 154.75 |
|  27  |      [MoE-LLaVA](https://arxiv.org/pdf/2401.15947.pdf)       |   [Phi-2.7B×4](https://github.com/PKU-YuanGroup/MoE-LLaVA)   | 154.50 |
|  28  |       [CogAgent](https://arxiv.org/pdf/2312.08914.pdf)       |         [Vicuna-7B](https://github.com/THUDM/CogVLM)         | 154.25 |
|  28  | [MiniCPM-V-2](https://github.com/OpenBMB/MiniCPM/#minicpm-v) | [MiniCPM-2B](https://github.com/OpenBMB/MiniCPM/#minicpm-v)  | 154.25 |
|  29  |        [MMICL](https://arxiv.org/pdf/2309.07915.pdf)         |        [FlanT5xxl](https://github.com/HaozheZhao/MIC)        | 153.75 |
|  29  | [MiniCPM-Llama3-V 2.5](https://github.com/OpenBMB/MiniCPM-V) |      [LLaMA3-8B](https://github.com/OpenBMB/MiniCPM-V)       | 153.75 |
|  29  | [Bunny-8B](https://huggingface.co/BAAI/Bunny-v1_1-Llama-3-8B-V) |       [LLaMA3-8B](https://github.com/BAAI-DCAI/Bunny)        | 153.75 |
|  30  |      [mPLUG-Owl2](https://arxiv.org/pdf/2311.04257.pdf)      | [LLaMA2-7B](https://github.com/X-PLUG/mPLUG-Owl/tree/main/mPLUG-Owl2) | 153.25 |
|  31  |     [InstructBLIP](https://arxiv.org/pdf/2305.06500.pdf)     | [FlanT5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/instructblip) | 153.00 |
|  32  |      [Qwen-VL-Chat](https://github.com/QwenLM/Qwen-VL/)      |         [Qwen-7B](https://github.com/QwenLM/Qwen-VL)         | 152.25 |
|  33  |        [BLIVA](https://arxiv.org/pdf/2308.09936.pdf)         |       [FlanT5xxl](https://github.com/mlpc-ucsd/BLIVA)        | 151.50 |
|  34  |          [Muffin](https://github.com/thunlp/Muffin)          |        [Vicuna-13B](https://github.com/thunlp/Muffin)        | 151.25 |
|  35  | [GPT-4V](https://cdn.openai.com/papers/GPTV_System_Card.pdf) |   [-](https://cdn.openai.com/papers/GPTV_System_Card.pdf)    | 151.00 |
|  35  | [Qwen-VL-Plus](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start) | [-](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start) | 151.00 |
|  36  |   [LRV-Instruction](https://arxiv.org/pdf/2306.14565.pdf)    |    [LRV-7B](https://github.com/FuxiaoLiu/LRV-Instruction)    | 147.98 |
|  37  |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     | 146.25 |
|  37  |   [OmniLMM](https://github.com/OpenBMB/MiniCPM/#minicpm-v)   | [Zephyr-7B-beta](https://github.com/OpenBMB/MiniCPM/#minicpm-v) | 146.25 |
|  38  |        [BLIP-2](https://arxiv.org/pdf/2301.12597.pdf)        | [Flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/blip2) | 145.25 |
|  39  | [Gemini Pro](https://storage.googleapis.com/deepmind-media/gemini/gemini_1_report.pdf) | [-](https://storage.googleapis.com/deepmind-media/gemini/gemini_1_report.pdf) | 144.75 |
|  40  |       [VPGTrans](https://arxiv.org/pdf/2305.01278.pdf)       |      [Vicuna-7B](https://github.com/VPGTrans/VPGTrans)       | 141.75 |
|  41  |        [LaVIN](https://arxiv.org/pdf/2305.15023.pdf)         |       [LAVIN-13B](https://github.com/luogen1996/LaVIN)       | 136.75 |
|  42  |      [mPLUG-Owl](https://arxiv.org/pdf/2304.14178.pdf)       | [LLaMA-7B](https://huggingface.co/MAGAer13/mplug-owl-llama-7b) | 135.50 |
|  43  |       [PandaGPT](https://arxiv.org/pdf/2305.16355.pdf)       |       [Vicuna-7B](https://github.com/yxuansu/PandaGPT)       | 118.00 |
|  44  | [ImageBind_LLM](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main) | [LLaMA-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/imagebind_LLM) | 113.25 |
|  45  |      [MiniGPT-4](https://arxiv.org/pdf/2304.10592.pdf)       |    [Vicuna-13B](https://github.com/Vision-CAIR/MiniGPT-4)    | 71.75  |
|  46  |    [Multimodal-GPT](https://arxiv.org/pdf/2305.04790.pdf)    | [Multimodal-GPT-9B](https://github.com/open-mmlab/Multimodal-GPT) | 68.00  |

### Landmark

| Rank |                            Model                             |                           Version                            | Score  |
| :--: | :----------------------------------------------------------: | :----------------------------------------------------------: | :----: |
|  🏅️   | [Qwen-VL-Plus](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start) | [-](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start) | 191.00 |
|  🥈   | [Qwen-VL-Max](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start) | [-](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start) | 187.50 |
|  🥉   | [ChatTruth-7B](https://huggingface.co/mingdali/ChatTruth-7B) |   [Qwen-7B](https://huggingface.co/mingdali/ChatTruth-7B)    | 185.75 |
|  4   |    [InternVL-Chat-V1.5](https://arxiv.org/pdf/2404.16821)    |    [InternLM2-20B](https://github.com/OpenGVLab/InternVL)    | 177.75 |
|  5   | [360VL](https://github.com/360CVGroup/360VL?tab=readme-ov-file) | [LLaMA3-70B](https://github.com/360CVGroup/360VL?tab=readme-ov-file) | 177.25 |
|  5   | [MiniCPM-Llama3-V 2.5](https://github.com/OpenBMB/MiniCPM-V) |      [LLaMA3-8B](https://github.com/OpenBMB/MiniCPM-V)       | 177.25 |
|  6   |     [Monkey-Chat](https://arxiv.org/pdf/2311.06607.pdf)      |       [Qwen-7B](https://github.com/Yuliang-Liu/Monkey)       | 176.50 |
|  7   | [InternLM-XComposer2-VL](https://github.com/InternLM/InternLM-XComposer) | [InternLM2-7B](https://github.com/InternLM/InternLM-XComposer) | 176.00 |
|  8   |   [OmniLMM](https://github.com/OpenBMB/MiniCPM/#minicpm-v)   | [Zephyr-7B-beta](https://github.com/OpenBMB/MiniCPM/#minicpm-v) | 175.25 |
|  9   | [MiniCPM-V-2](https://github.com/OpenBMB/MiniCPM/#minicpm-v) | [MiniCPM-2B](https://github.com/OpenBMB/MiniCPM/#minicpm-v)  | 175.00 |
|  10  |       [RBDash](https://github.com/RBDash-Team/RBDash)        |     [Vicuna-13B](https://github.com/RBDash-Team/RBDash)      | 174.25 |
|  11  |      [ShareGPT4V](https://arxiv.org/pdf/2311.12793.pdf)      | [Vicuna-13B](https://github.com/InternLM/InternLM-XComposer/tree/main/projects/ShareGPT4V) | 174.00 |
|  11  |     [BELLE-VL](https://huggingface.co/BELLE-2/BELLE-VL)      |     [Qwen-14B](https://huggingface.co/BELLE-2/BELLE-VL)      | 174.00 |
|  12  |    [JT-VL-Chat](https://github.com/jiutiancv/JT-VL-Chat)     |         [-](https://github.com/jiutiancv/JT-VL-Chat)         | 173.50 |
|  13  |          [WeMM](https://github.com/scenarios/WeMM)           |       [InternLM-7B](https://github.com/scenarios/WeMM)       | 172.25 |
|  13  |       [Honeybee](https://arxiv.org/pdf/2312.06742.pdf)       |     [Vicuna-13B](https://github.com/kakaobrain/honeybee)     | 172.25 |
|  13  |           [PureMM](https://github.com/Q-MM/PureMM)           |         [Vicuna-13B](https://github.com/Q-MM/PureMM)         | 172.25 |
|  14  |       [CogAgent](https://arxiv.org/pdf/2312.08914.pdf)       |         [Vicuna-7B](https://github.com/THUDM/CogVLM)         | 172.00 |
|  14  |      [HyperLLaVA](https://arxiv.org/pdf/2403.13447.pdf)      |     [Vicuna-13B](https://github.com/dcdmllm/hyperllava)      | 172.00 |
|  15  |        [LLaVA](https://arxiv.org/pdf/2304.08485.pdf)         |      [Vicuna-13B](https://github.com/haotian-liu/LLaVA)      | 170.50 |
|  16  | [Bunny-8B](https://huggingface.co/BAAI/Bunny-v1_1-Llama-3-8B-V) |       [LLaMA3-8B](https://github.com/BAAI-DCAI/Bunny)        | 170.25 |
|  17  | [SPHINX](https://github.com/Alpha-VLLM/LLaMA2-Accessory/tree/main/SPHINX) | [LLaMA2-13B](https://github.com/Alpha-VLLM/LLaMA2-Accessory/tree/main/SPHINX) | 168.09 |
|  18  |  [InternVL-Chat-V1.1](https://arxiv.org/pdf/2312.14238.pdf)  |     [LLaMA2-13B](https://github.com/OpenGVLab/InternVL/)     | 168.00 |
|  19  |   [LLaMA-Adapter V2](https://arxiv.org/pdf/2304.15010.pdf)   | [LLaMA-Adapter-v2.1-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/llama_adapter_v2_multimodal7b) | 167.84 |
|  20  |   [MiniCPM](https://github.com/OpenBMB/MiniCPM/#minicpm-v)   | [MiniCPM-2B](https://github.com/OpenBMB/MiniCPM/#minicpm-v)  | 167.75 |
|  21  |    [Bunny-4B](https://huggingface.co/BAAI/Bunny-v1_1-4B)     | [Phi-3-Mini-4K-Instruct](https://github.com/BAAI-DCAI/Bunny) | 167.50 |
|  22  |       [InfMLLM](https://github.com/infly-ai/INF-MLLM)        |      [Vicuna-13B](https://github.com/infly-ai/INF-MLLM)      | 166.75 |
|  23  | [InternLM-XComposer-VL](https://github.com/InternLM/InternLM-XComposer) | [InternLM-7B](https://github.com/InternLM/InternLM-XComposer) | 165.25 |
|  23  | [LLaVA-1.6](https://llava-vl.github.io/blog/2024-01-30-llava-1-6/) |      [Vicuna-34B](https://github.com/haotian-liu/LLaVA)      | 165.25 |
|  24  |      [Qwen-VL-Chat](https://github.com/QwenLM/Qwen-VL/)      |         [Qwen-7B](https://github.com/QwenLM/Qwen-VL)         | 164.00 |
|  25  |         [Lynx](https://arxiv.org/pdf/2307.02469.pdf)         |      [Vicuna-7B](https://github.com/bytedance/lynx-llm)      | 162.00 |
|  26  |   [LVIS-INSTRUCT4V](https://arxiv.org/pdf/2311.07574.pdf)    |    [Vicuna-13B](https://github.com/X2FD/LVIS-INSTRUCT4V)     | 161.50 |
|  27  |   [LRV-Instruction](https://arxiv.org/pdf/2306.14565.pdf)    |    [LRV-7B](https://github.com/FuxiaoLiu/LRV-Instruction)    | 160.53 |
|  28  |  [DataOptim-LLaVA](https://github.com/BAAI-DCAI/DataOptim)   |     [Vicuna-13B](https://github.com/BAAI-DCAI/DataOptim)     | 160.00 |
|  29  |      [mPLUG-Owl](https://arxiv.org/pdf/2304.14178.pdf)       | [LLaMA-7B](https://huggingface.co/MAGAer13/mplug-owl-llama-7b) | 159.25 |
|  29  |  [TransCore-M](https://github.com/PCIResearch/TransCore-M)   | [PCITransGPT-13B](https://github.com/PCIResearch/TransCore-M) | 159.25 |
|  30  | [Gemini Pro](https://storage.googleapis.com/deepmind-media/gemini/gemini_1_report.pdf) | [-](https://storage.googleapis.com/deepmind-media/gemini/gemini_1_report.pdf) | 158.75 |
|  31  |        [CogVLM](https://arxiv.org/pdf/2311.03079.pdf)        |         [Vicuna-7B](https://github.com/THUDM/CogVLM)         | 158.00 |
|  32  |      [mPLUG-Owl2](https://arxiv.org/pdf/2311.04257.pdf)      | [LLaMA2-7B](https://github.com/X-PLUG/mPLUG-Owl/tree/main/mPLUG-Owl2) | 157.25 |
|  33  | [MindSource-VL-Chat](https://github.com/luogen1996/LLaVA-HR) |   [MindSource-7B](https://github.com/luogen1996/LLaVA-HR)    | 150.75 |
|  34  |      [MoE-LLaVA](https://arxiv.org/pdf/2401.15947.pdf)       |   [Phi-2.7B×4](https://github.com/PKU-YuanGroup/MoE-LLaVA)   | 148.25 |
|  35  |          [Muffin](https://github.com/thunlp/Muffin)          |        [Vicuna-13B](https://github.com/thunlp/Muffin)        | 146.25 |
|  36  |       [Cheetor](https://arxiv.org/pdf/2308.04152.pdf)        |       [Vicuna-7B](https://github.com/DCDmllm/Cheetah)        | 145.73 |
|  37  |         [GIT2](https://arxiv.org/pdf/2205.14100.pdf)         | [VQAv2-finetuned](https://github.com/microsoft/GenerativeImage2Text) | 140.50 |
|  38  | [GPT-4V](https://cdn.openai.com/papers/GPTV_System_Card.pdf) |   [-](https://cdn.openai.com/papers/GPTV_System_Card.pdf)    | 138.25 |
|  39  |        [BLIP-2](https://arxiv.org/pdf/2301.12597.pdf)        | [Flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/blip2) | 138.00 |
|  40  |        [Otter](https://arxiv.org/pdf/2305.03726.pdf)         |    [OTTER-Image-MPT7B](https://github.com/Luodian/Otter)     | 137.25 |
|  41  |        [MMICL](https://arxiv.org/pdf/2309.07915.pdf)         |        [FlanT5xxl](https://github.com/HaozheZhao/MIC)        | 136.13 |
|  42  |        [LaVIN](https://arxiv.org/pdf/2305.15023.pdf)         |       [LAVIN-13B](https://github.com/luogen1996/LaVIN)       | 93.50  |
|  43  |        [BLIVA](https://arxiv.org/pdf/2308.09936.pdf)         |       [FlanT5xxl](https://github.com/mlpc-ucsd/BLIVA)        | 89.50  |
|  44  |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     | 83.75  |
|  45  |     [InstructBLIP](https://arxiv.org/pdf/2305.06500.pdf)     | [FlanT5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/instructblip) | 79.75  |
|  46  |    [Multimodal-GPT](https://arxiv.org/pdf/2305.04790.pdf)    | [Multimodal-GPT-9B](https://github.com/open-mmlab/Multimodal-GPT) | 69.75  |
|  46  |       [PandaGPT](https://arxiv.org/pdf/2305.16355.pdf)       |       [Vicuna-7B](https://github.com/yxuansu/PandaGPT)       | 69.75  |
|  47  |       [VPGTrans](https://arxiv.org/pdf/2305.01278.pdf)       |      [Vicuna-7B](https://github.com/VPGTrans/VPGTrans)       | 64.75  |
|  48  | [ImageBind_LLM](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main) | [LLaMA-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/imagebind_LLM) | 62.00  |
|  49  |      [MiniGPT-4](https://arxiv.org/pdf/2304.10592.pdf)       |    [Vicuna-13B](https://github.com/Vision-CAIR/MiniGPT-4)    | 54.00  |

### Artwork

| Rank |                            Model                             |                           Version                            | Score  |
| :--: | :----------------------------------------------------------: | :----------------------------------------------------------: | :----: |
|  🏅️   | [InternLM-XComposer2-VL](https://github.com/InternLM/InternLM-XComposer) | [InternLM2-7B](https://github.com/InternLM/InternLM-XComposer) | 185.50 |
|  🥈   |           [PureMM](https://github.com/Q-MM/PureMM)           |         [Vicuna-13B](https://github.com/Q-MM/PureMM)         | 183.50 |
|  🥉   |       [InfMLLM](https://github.com/infly-ai/INF-MLLM)        |      [Vicuna-13B](https://github.com/infly-ai/INF-MLLM)      | 167.50 |
|  4   | [Qwen-VL-Max](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start) | [-](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start) | 166.00 |
|  5   | [ChatTruth-7B](https://huggingface.co/mingdali/ChatTruth-7B) |   [Qwen-7B](https://huggingface.co/mingdali/ChatTruth-7B)    | 159.75 |
|  6   |          [WeMM](https://github.com/scenarios/WeMM)           |       [InternLM-7B](https://github.com/scenarios/WeMM)       | 156.00 |
|  6   | [Qwen-VL-Plus](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start) | [-](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start) | 156.00 |
|  7   |   [OmniLMM](https://github.com/OpenBMB/MiniCPM/#minicpm-v)   | [Zephyr-7B-beta](https://github.com/OpenBMB/MiniCPM/#minicpm-v) | 150.25 |
|  8   | [GPT-4V](https://cdn.openai.com/papers/GPTV_System_Card.pdf) |   [-](https://cdn.openai.com/papers/GPTV_System_Card.pdf)    | 148.00 |
|  9   |         [GIT2](https://arxiv.org/pdf/2205.14100.pdf)         | [VQAv2-finetuned](https://github.com/microsoft/GenerativeImage2Text) | 146.25 |
|  10  | [MiniCPM-V-2](https://github.com/OpenBMB/MiniCPM/#minicpm-v) | [MiniCPM-2B](https://github.com/OpenBMB/MiniCPM/#minicpm-v)  | 145.25 |
|  11  | [MiniCPM-Llama3-V 2.5](https://github.com/OpenBMB/MiniCPM-V) |      [LLaMA3-8B](https://github.com/OpenBMB/MiniCPM-V)       | 144.50 |
|  12  |     [Monkey-Chat](https://arxiv.org/pdf/2311.06607.pdf)      |       [Qwen-7B](https://github.com/Yuliang-Liu/Monkey)       | 144.25 |
|  13  |  [InternVL-Chat-V1.1](https://arxiv.org/pdf/2312.14238.pdf)  |     [LLaMA2-13B](https://github.com/OpenGVLab/InternVL/)     | 143.50 |
|  14  |    [InternVL-Chat-V1.5](https://arxiv.org/pdf/2404.16821)    |    [InternLM2-20B](https://github.com/OpenGVLab/InternVL)    | 143.00 |
|  15  |       [RBDash](https://github.com/RBDash-Team/RBDash)        |     [Vicuna-13B](https://github.com/RBDash-Team/RBDash)      | 140.50 |
|  16  |     [BELLE-VL](https://huggingface.co/BELLE-2/BELLE-VL)      |     [Qwen-14B](https://huggingface.co/BELLE-2/BELLE-VL)      | 139.50 |
|  17  | [LLaVA-1.6](https://llava-vl.github.io/blog/2024-01-30-llava-1-6/) |      [Vicuna-34B](https://github.com/haotian-liu/LLaVA)      | 139.00 |
|  18  |    [Bunny-4B](https://huggingface.co/BAAI/Bunny-v1_1-4B)     | [Phi-3-Mini-4K-Instruct](https://github.com/BAAI-DCAI/Bunny) | 136.75 |
|  19  |        [BLIP-2](https://arxiv.org/pdf/2301.12597.pdf)        | [Flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/blip2) | 136.50 |
|  20  | [Gemini Pro](https://storage.googleapis.com/deepmind-media/gemini/gemini_1_report.pdf) | [-](https://storage.googleapis.com/deepmind-media/gemini/gemini_1_report.pdf) | 135.75 |
|  21  |        [MMICL](https://arxiv.org/pdf/2309.07915.pdf)         |        [FlanT5xxl](https://github.com/HaozheZhao/MIC)        | 135.50 |
|  22  |       [Honeybee](https://arxiv.org/pdf/2312.06742.pdf)       |     [Vicuna-13B](https://github.com/kakaobrain/honeybee)     | 134.75 |
|  23  |     [InstructBLIP](https://arxiv.org/pdf/2305.06500.pdf)     | [FlanT5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/instructblip) | 134.25 |
|  23  |      [mPLUG-Owl2](https://arxiv.org/pdf/2311.04257.pdf)      | [LLaMA2-7B](https://github.com/X-PLUG/mPLUG-Owl/tree/main/mPLUG-Owl2) | 134.25 |
|  24  | [SPHINX](https://github.com/Alpha-VLLM/LLaMA2-Accessory/tree/main/SPHINX) | [LLaMA2-13B](https://github.com/Alpha-VLLM/LLaMA2-Accessory/tree/main/SPHINX) | 134.00 |
|  25  |        [BLIVA](https://arxiv.org/pdf/2308.09936.pdf)         |       [FlanT5xxl](https://github.com/mlpc-ucsd/BLIVA)        | 133.25 |
|  26  |    [JT-VL-Chat](https://github.com/jiutiancv/JT-VL-Chat)     |         [-](https://github.com/jiutiancv/JT-VL-Chat)         | 132.75 |
|  27  | [Bunny-8B](https://huggingface.co/BAAI/Bunny-v1_1-Llama-3-8B-V) |       [LLaMA3-8B](https://github.com/BAAI-DCAI/Bunny)        | 132.50 |
|  28  | [360VL](https://github.com/360CVGroup/360VL?tab=readme-ov-file) | [LLaMA3-70B](https://github.com/360CVGroup/360VL?tab=readme-ov-file) | 131.25 |
|  29  |  [TransCore-M](https://github.com/PCIResearch/TransCore-M)   | [PCITransGPT-13B](https://github.com/PCIResearch/TransCore-M) | 130.75 |
|  29  |   [MiniCPM](https://github.com/OpenBMB/MiniCPM/#minicpm-v)   | [MiniCPM-2B](https://github.com/OpenBMB/MiniCPM/#minicpm-v)  | 130.75 |
|  30  |   [LVIS-INSTRUCT4V](https://arxiv.org/pdf/2311.07574.pdf)    |    [Vicuna-13B](https://github.com/X2FD/LVIS-INSTRUCT4V)     | 130.25 |
|  31  |        [Otter](https://arxiv.org/pdf/2305.03726.pdf)         |    [OTTER-Image-MPT7B](https://github.com/Luodian/Otter)     | 129.00 |
|  32  |      [ShareGPT4V](https://arxiv.org/pdf/2311.12793.pdf)      | [Vicuna-13B](https://github.com/InternLM/InternLM-XComposer/tree/main/projects/ShareGPT4V) | 128.00 |
|  33  | [InternLM-XComposer-VL](https://github.com/InternLM/InternLM-XComposer) | [InternLM-7B](https://github.com/InternLM/InternLM-XComposer) | 126.25 |
|  34  |      [Qwen-VL-Chat](https://github.com/QwenLM/Qwen-VL/)      |         [Qwen-7B](https://github.com/QwenLM/Qwen-VL)         | 125.50 |
|  35  |   [LLaMA-Adapter V2](https://arxiv.org/pdf/2304.15010.pdf)   | [LLaMA-Adapter-v2.1-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/llama_adapter_v2_multimodal7b) | 123.75 |
|  36  | [MindSource-VL-Chat](https://github.com/luogen1996/LLaVA-HR) |   [MindSource-7B](https://github.com/luogen1996/LLaVA-HR)    | 119.75 |
|  37  |         [Lynx](https://arxiv.org/pdf/2307.02469.pdf)         |      [Vicuna-7B](https://github.com/bytedance/lynx-llm)      | 119.50 |
|  38  |      [HyperLLaVA](https://arxiv.org/pdf/2403.13447.pdf)      |     [Vicuna-13B](https://github.com/dcdmllm/hyperllava)      | 119.25 |
|  39  |        [LLaVA](https://arxiv.org/pdf/2304.08485.pdf)         |      [Vicuna-13B](https://github.com/haotian-liu/LLaVA)      | 117.75 |
|  40  |          [Muffin](https://github.com/thunlp/Muffin)          |        [Vicuna-13B](https://github.com/thunlp/Muffin)        | 116.50 |
|  41  |       [CogAgent](https://arxiv.org/pdf/2312.08914.pdf)       |         [Vicuna-7B](https://github.com/THUDM/CogVLM)         | 116.25 |
|  42  |  [DataOptim-LLaVA](https://github.com/BAAI-DCAI/DataOptim)   |     [Vicuna-13B](https://github.com/BAAI-DCAI/DataOptim)     | 113.75 |
|  43  |       [Cheetor](https://arxiv.org/pdf/2308.04152.pdf)        |       [Vicuna-7B](https://github.com/DCDmllm/Cheetah)        | 113.50 |
|  44  |      [MoE-LLaVA](https://arxiv.org/pdf/2401.15947.pdf)       |   [Phi-2.7B×4](https://github.com/PKU-YuanGroup/MoE-LLaVA)   | 105.50 |
|  45  |   [LRV-Instruction](https://arxiv.org/pdf/2306.14565.pdf)    |    [LRV-7B](https://github.com/FuxiaoLiu/LRV-Instruction)    | 101.25 |
|  46  |      [mPLUG-Owl](https://arxiv.org/pdf/2304.14178.pdf)       | [LLaMA-7B](https://huggingface.co/MAGAer13/mplug-owl-llama-7b) | 96.25  |
|  47  |        [CogVLM](https://arxiv.org/pdf/2311.03079.pdf)        |         [Vicuna-7B](https://github.com/THUDM/CogVLM)         | 88.75  |
|  48  |        [LaVIN](https://arxiv.org/pdf/2305.15023.pdf)         |       [LAVIN-13B](https://github.com/luogen1996/LaVIN)       | 87.25  |
|  49  |       [VPGTrans](https://arxiv.org/pdf/2305.01278.pdf)       |      [Vicuna-7B](https://github.com/VPGTrans/VPGTrans)       | 77.25  |
|  50  |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     | 75.25  |
|  51  | [ImageBind_LLM](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main) | [LLaMA-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/imagebind_LLM) | 70.75  |
|  52  |      [MiniGPT-4](https://arxiv.org/pdf/2304.10592.pdf)       |    [Vicuna-13B](https://github.com/Vision-CAIR/MiniGPT-4)    | 60.50  |
|  53  |    [Multimodal-GPT](https://arxiv.org/pdf/2305.04790.pdf)    | [Multimodal-GPT-9B](https://github.com/open-mmlab/Multimodal-GPT) | 59.50  |
|  54  |       [PandaGPT](https://arxiv.org/pdf/2305.16355.pdf)       |       [Vicuna-7B](https://github.com/yxuansu/PandaGPT)       | 51.25  |

### OCR

| Rank |                            Model                             |                           Version                            | Score  |
| :--: | :----------------------------------------------------------: | :----------------------------------------------------------: | :----: |
|  🏅️   | [GPT-4V](https://cdn.openai.com/papers/GPTV_System_Card.pdf) |   [-](https://cdn.openai.com/papers/GPTV_System_Card.pdf)    | 185.00 |
|  🏅️   | [Gemini Pro](https://storage.googleapis.com/deepmind-media/gemini/gemini_1_report.pdf) | [-](https://storage.googleapis.com/deepmind-media/gemini/gemini_1_report.pdf) | 185.00 |
|  🏅️   | [Qwen-VL-Max](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start) | [-](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start) | 185.00 |
|  🥈   |     [BELLE-VL](https://huggingface.co/BELLE-2/BELLE-VL)      |     [Qwen-14B](https://huggingface.co/BELLE-2/BELLE-VL)      | 177.50 |
|  🥈   |  [InternVL-Chat-V1.1](https://arxiv.org/pdf/2312.14238.pdf)  |     [LLaMA2-13B](https://github.com/OpenGVLab/InternVL/)     | 177.50 |
|  🥉   |    [JT-VL-Chat](https://github.com/jiutiancv/JT-VL-Chat)     |         [-](https://github.com/jiutiancv/JT-VL-Chat)         | 170.00 |
|  4   |  [DataOptim-LLaVA](https://github.com/BAAI-DCAI/DataOptim)   |     [Vicuna-13B](https://github.com/BAAI-DCAI/DataOptim)     | 162.50 |
|  4   |           [PureMM](https://github.com/Q-MM/PureMM)           |         [Vicuna-13B](https://github.com/Q-MM/PureMM)         | 162.50 |
|  4   | [ChatTruth-7B](https://huggingface.co/mingdali/ChatTruth-7B) |   [Qwen-7B](https://huggingface.co/mingdali/ChatTruth-7B)    | 162.50 |
|  4   | [MindSource-VL-Chat](https://github.com/luogen1996/LLaVA-HR) |   [MindSource-7B](https://github.com/luogen1996/LLaVA-HR)    | 162.50 |
|  5   |  [TransCore-M](https://github.com/PCIResearch/TransCore-M)   | [PCITransGPT-13B](https://github.com/PCIResearch/TransCore-M) | 155.00 |
|  5   |       [Honeybee](https://arxiv.org/pdf/2312.06742.pdf)       |     [Vicuna-13B](https://github.com/kakaobrain/honeybee)     | 155.00 |
|  5   |   [OmniLMM](https://github.com/OpenBMB/MiniCPM/#minicpm-v)   | [Zephyr-7B-beta](https://github.com/OpenBMB/MiniCPM/#minicpm-v) | 155.00 |
|  5   |    [Bunny-4B](https://huggingface.co/BAAI/Bunny-v1_1-4B)     | [Phi-3-Mini-4K-Instruct](https://github.com/BAAI-DCAI/Bunny) | 155.00 |
|  5   | [Bunny-8B](https://huggingface.co/BAAI/Bunny-v1_1-Llama-3-8B-V) |       [LLaMA3-8B](https://github.com/BAAI-DCAI/Bunny)        | 155.00 |
|  6   |          [WeMM](https://github.com/scenarios/WeMM)           |       [InternLM-7B](https://github.com/scenarios/WeMM)       | 147.50 |
|  6   | [Qwen-VL-Plus](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start) | [-](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start) | 147.50 |
|  6   | [InternLM-XComposer2-VL](https://github.com/InternLM/InternLM-XComposer) | [InternLM2-7B](https://github.com/InternLM/InternLM-XComposer) | 147.50 |
|  6   |        [CogVLM](https://arxiv.org/pdf/2311.03079.pdf)        |         [Vicuna-7B](https://github.com/THUDM/CogVLM)         | 147.50 |
|  7   |      [Qwen-VL-Chat](https://github.com/QwenLM/Qwen-VL/)      |         [Qwen-7B](https://github.com/QwenLM/Qwen-VL)         | 140.00 |
|  7   | [LLaVA-1.6](https://llava-vl.github.io/blog/2024-01-30-llava-1-6/) |      [Vicuna-34B](https://github.com/haotian-liu/LLaVA)      | 140.00 |
|  7   |    [InternVL-Chat-V1.5](https://arxiv.org/pdf/2404.16821)    |    [InternLM2-20B](https://github.com/OpenGVLab/InternVL)    | 140.00 |
|  7   | [MiniCPM-Llama3-V 2.5](https://github.com/OpenBMB/MiniCPM-V) |      [LLaMA3-8B](https://github.com/OpenBMB/MiniCPM-V)       | 140.00 |
|  8   |   [LVIS-INSTRUCT4V](https://arxiv.org/pdf/2311.07574.pdf)    |    [Vicuna-13B](https://github.com/X2FD/LVIS-INSTRUCT4V)     | 132.50 |
|  8   |      [ShareGPT4V](https://arxiv.org/pdf/2311.12793.pdf)      | [Vicuna-13B](https://github.com/InternLM/InternLM-XComposer/tree/main/projects/ShareGPT4V) | 132.50 |
|  8   |      [MoE-LLaVA](https://arxiv.org/pdf/2401.15947.pdf)       |   [Phi-2.7B×4](https://github.com/PKU-YuanGroup/MoE-LLaVA)   | 132.50 |
|  8   |      [HyperLLaVA](https://arxiv.org/pdf/2403.13447.pdf)      |     [Vicuna-13B](https://github.com/dcdmllm/hyperllava)      | 132.50 |
|  8   | [360VL](https://github.com/360CVGroup/360VL?tab=readme-ov-file) | [LLaMA3-70B](https://github.com/360CVGroup/360VL?tab=readme-ov-file) | 132.50 |
|  9   |        [LLaVA](https://arxiv.org/pdf/2304.08485.pdf)         |      [Vicuna-13B](https://github.com/haotian-liu/LLaVA)      | 125.00 |
|  9   | [InternLM-XComposer-VL](https://github.com/InternLM/InternLM-XComposer) | [InternLM-7B](https://github.com/InternLM/InternLM-XComposer) | 125.00 |
|  10  |        [BLIP-2](https://arxiv.org/pdf/2301.12597.pdf)        | [Flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/blip2) | 110.00 |
|  10  |   [LRV-Instruction](https://arxiv.org/pdf/2306.14565.pdf)    |    [LRV-7B](https://github.com/FuxiaoLiu/LRV-Instruction)    | 110.00 |
|  10  |       [InfMLLM](https://github.com/infly-ai/INF-MLLM)        |      [Vicuna-13B](https://github.com/infly-ai/INF-MLLM)      | 110.00 |
|  10  |   [MiniCPM](https://github.com/OpenBMB/MiniCPM/#minicpm-v)   | [MiniCPM-2B](https://github.com/OpenBMB/MiniCPM/#minicpm-v)  | 110.00 |
|  11  |        [LaVIN](https://arxiv.org/pdf/2305.15023.pdf)         |       [LAVIN-13B](https://github.com/luogen1996/LaVIN)       | 107.50 |
|  12  |   [LLaMA-Adapter V2](https://arxiv.org/pdf/2304.15010.pdf)   | [LLaMA-Adapter-v2.1-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/llama_adapter_v2_multimodal7b) | 102.50 |
|  12  |      [mPLUG-Owl2](https://arxiv.org/pdf/2311.04257.pdf)      | [LLaMA2-7B](https://github.com/X-PLUG/mPLUG-Owl/tree/main/mPLUG-Owl2) | 102.50 |
|  12  |       [RBDash](https://github.com/RBDash-Team/RBDash)        |     [Vicuna-13B](https://github.com/RBDash-Team/RBDash)      | 102.50 |
|  12  | [MiniCPM-V-2](https://github.com/OpenBMB/MiniCPM/#minicpm-v) | [MiniCPM-2B](https://github.com/OpenBMB/MiniCPM/#minicpm-v)  | 102.50 |
|  13  |       [Cheetor](https://arxiv.org/pdf/2308.04152.pdf)        |       [Vicuna-7B](https://github.com/DCDmllm/Cheetah)        | 100.00 |
|  13  |        [MMICL](https://arxiv.org/pdf/2309.07915.pdf)         |        [FlanT5xxl](https://github.com/HaozheZhao/MIC)        | 100.00 |
|  14  |        [BLIVA](https://arxiv.org/pdf/2308.09936.pdf)         |       [FlanT5xxl](https://github.com/mlpc-ucsd/BLIVA)        | 87.50  |
|  14  | [SPHINX](https://github.com/Alpha-VLLM/LLaMA2-Accessory/tree/main/SPHINX) | [LLaMA2-13B](https://github.com/Alpha-VLLM/LLaMA2-Accessory/tree/main/SPHINX) | 87.50  |
|  15  |    [Multimodal-GPT](https://arxiv.org/pdf/2305.04790.pdf)    | [Multimodal-GPT-9B](https://github.com/open-mmlab/Multimodal-GPT) | 82.50  |
|  16  | [ImageBind_LLM](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main) | [LLaMA-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/imagebind_LLM) | 80.00  |
|  16  |     [Monkey-Chat](https://arxiv.org/pdf/2311.06607.pdf)      |       [Qwen-7B](https://github.com/Yuliang-Liu/Monkey)       | 80.00  |
|  16  |       [CogAgent](https://arxiv.org/pdf/2312.08914.pdf)       |         [Vicuna-7B](https://github.com/THUDM/CogVLM)         | 80.00  |
|  17  |       [VPGTrans](https://arxiv.org/pdf/2305.01278.pdf)       |      [Vicuna-7B](https://github.com/VPGTrans/VPGTrans)       | 77.50  |
|  17  |         [Lynx](https://arxiv.org/pdf/2307.02469.pdf)         |      [Vicuna-7B](https://github.com/bytedance/lynx-llm)      | 77.50  |
|  18  |     [InstructBLIP](https://arxiv.org/pdf/2305.06500.pdf)     | [FlanT5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/instructblip) | 72.50  |
|  18  |        [Otter](https://arxiv.org/pdf/2305.03726.pdf)         |    [OTTER-Image-MPT7B](https://github.com/Luodian/Otter)     | 72.50  |
|  19  |      [mPLUG-Owl](https://arxiv.org/pdf/2304.14178.pdf)       | [LLaMA-7B](https://huggingface.co/MAGAer13/mplug-owl-llama-7b) | 65.00  |
|  19  |         [GIT2](https://arxiv.org/pdf/2205.14100.pdf)         | [VQAv2-finetuned](https://github.com/microsoft/GenerativeImage2Text) | 65.00  |
|  20  |      [MiniGPT-4](https://arxiv.org/pdf/2304.10592.pdf)       |    [Vicuna-13B](https://github.com/Vision-CAIR/MiniGPT-4)    | 57.50  |
|  20  |          [Muffin](https://github.com/thunlp/Muffin)          |        [Vicuna-13B](https://github.com/thunlp/Muffin)        | 57.50  |
|  21  |       [PandaGPT](https://arxiv.org/pdf/2305.16355.pdf)       |       [Vicuna-7B](https://github.com/yxuansu/PandaGPT)       | 50.00  |
|  22  |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     | 42.50  |

---

## Cognition

Sum of the scores of all cognition subtasks, including commonsense reasoning, numerical calculation, text translation, and code reasoning. The full score of each subtask is 200, and that of all cognition is 800.

| Rank |                            Model                             |                           Version                            | Score  |
| :--: | :----------------------------------------------------------: | :----------------------------------------------------------: | :----: |
|  🏅️   | [Qwen-VL-Max](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start) | [-](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start) | 643.57 |
|  🥈   |    [InternVL-Chat-V1.5](https://arxiv.org/pdf/2404.16821)    |    [InternLM2-20B](https://github.com/OpenGVLab/InternVL)    | 550.00 |
|  🥉   | [InternLM-XComposer2-VL](https://github.com/InternLM/InternLM-XComposer) | [InternLM2-7B](https://github.com/InternLM/InternLM-XComposer) | 530.71 |
|  4   | [GPT-4V](https://cdn.openai.com/papers/GPTV_System_Card.pdf) |   [-](https://cdn.openai.com/papers/GPTV_System_Card.pdf)    | 517.14 |
|  5   | [Qwen-VL-Plus](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start) | [-](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start) | 502.14 |
|  6   |          [WeMM](https://github.com/scenarios/WeMM)           |       [InternLM-7B](https://github.com/scenarios/WeMM)       | 445.00 |
|  7   | [Gemini Pro](https://storage.googleapis.com/deepmind-media/gemini/gemini_1_report.pdf) | [-](https://storage.googleapis.com/deepmind-media/gemini/gemini_1_report.pdf) | 436.79 |
|  8   |        [MMICL](https://arxiv.org/pdf/2309.07915.pdf)         |        [FlanT5xxl](https://github.com/HaozheZhao/MIC)        | 428.93 |
|  9   | [MiniCPM-V-2](https://github.com/OpenBMB/MiniCPM/#minicpm-v) | [MiniCPM-2B](https://github.com/OpenBMB/MiniCPM/#minicpm-v)  | 406.07 |
|  10  |     [Monkey-Chat](https://arxiv.org/pdf/2311.06607.pdf)      |       [Qwen-7B](https://github.com/Yuliang-Liu/Monkey)       | 401.43 |
|  11  | [MiniCPM-Llama3-V 2.5](https://github.com/OpenBMB/MiniCPM-V) |      [LLaMA3-8B](https://github.com/OpenBMB/MiniCPM-V)       | 400.71 |
|  12  | [LLaVA-1.6](https://llava-vl.github.io/blog/2024-01-30-llava-1-6/) |      [Vicuna-34B](https://github.com/haotian-liu/LLaVA)      | 397.14 |
|  13  | [InternLM-XComposer-VL](https://github.com/InternLM/InternLM-XComposer) | [InternLM-7B](https://github.com/InternLM/InternLM-XComposer) | 391.07 |
|  14  | [ChatTruth-7B](https://huggingface.co/mingdali/ChatTruth-7B) |   [Qwen-7B](https://huggingface.co/mingdali/ChatTruth-7B)    | 387.86 |
|  15  | [360VL](https://github.com/360CVGroup/360VL?tab=readme-ov-file) | [LLaMA3-70B](https://github.com/360CVGroup/360VL?tab=readme-ov-file) | 371.43 |
|  16  |       [InfMLLM](https://github.com/mightyzau/InfMLLM)        |      [Vicuna-13B](https://github.com/mightyzau/InfMLLM)      | 368.93 |
|  17  | [Bunny-8B](https://huggingface.co/BAAI/Bunny-v1_1-Llama-3-8B-V) |       [LLaMA3-8B](https://github.com/BAAI-DCAI/Bunny)        | 367.50 |
|  18  |  [DataOptim-LLaVA](https://github.com/BAAI-DCAI/DataOptim)   |     [Vicuna-13B](https://github.com/BAAI-DCAI/DataOptim)     | 361.07 |
|  19  |    [Bunny-4B](https://huggingface.co/BAAI/Bunny-v1_1-4B)     | [Phi-3-Mini-4K-Instruct](https://github.com/BAAI-DCAI/Bunny) | 361.07 |
|  20  |      [Qwen-VL-Chat](https://github.com/QwenLM/Qwen-VL/)      |         [Qwen-7B](https://github.com/QwenLM/Qwen-VL)         | 360.71 |
|  21  |           [PureMM](https://github.com/Q-MM/PureMM)           |         [Vicuna-13B](https://github.com/Q-MM/PureMM)         | 360.36 |
|  22  |   [LLaMA-Adapter V2](https://arxiv.org/pdf/2304.15010.pdf)   | [LLaMA-Adapter-v2.1-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/llama_adapter_v2_multimodal7b) | 356.43 |
|  23  |  [InternVL-Chat-V1.1](https://arxiv.org/pdf/2312.14238.pdf)  |     [LLaMA2-13B](https://github.com/OpenGVLab/InternVL/)     | 341.07 |
|  24  |    [JT-VL-Chat](https://github.com/jiutiancv/JT-VL-Chat)     |         [-](https://github.com/jiutiancv/JT-VL-Chat)         | 339.64 |
|  25  |     [BELLE-VL](https://huggingface.co/BELLE-2/BELLE-VL)      |     [Qwen-14B](https://huggingface.co/BELLE-2/BELLE-VL)      | 332.14 |
|  26  |        [BLIVA](https://arxiv.org/pdf/2308.09936.pdf)         |       [FlanT5xxl](https://github.com/mlpc-ucsd/BLIVA)        | 331.43 |
|  27  |       [RBDash](https://github.com/RBDash-Team/RBDash)        |     [Vicuna-13B](https://github.com/RBDash-Team/RBDash)      | 330.00 |
|  28  |   [LRV-Instruction](https://arxiv.org/pdf/2306.14565.pdf)    |    [LRV-7B](https://github.com/FuxiaoLiu/LRV-Instruction)    | 328.21 |
|  29  |   [OmniLMM](https://github.com/OpenBMB/MiniCPM/#minicpm-v)   | [Zephyr-7B-beta](https://github.com/OpenBMB/MiniCPM/#minicpm-v) | 322.14 |
|  30  |       [Cheetor](https://arxiv.org/pdf/2308.04152.pdf)        |       [Vicuna-7B](https://github.com/DCDmllm/Cheetah)        | 321.07 |
|  31  |       [Honeybee](https://arxiv.org/pdf/2312.06742.pdf)       |     [Vicuna-13B](https://github.com/kakaobrain/honeybee)     | 315.36 |
|  32  |  [TransCore-M](https://github.com/PCIResearch/TransCore-M)   | [PCITransGPT-13B](https://github.com/PCIResearch/TransCore-M) | 314.64 |
|  33  |   [MiniCPM](https://github.com/OpenBMB/MiniCPM/#minicpm-v)   | [MiniCPM-2B](https://github.com/OpenBMB/MiniCPM/#minicpm-v)  | 314.29 |
|  34  |        [CogVLM](https://arxiv.org/pdf/2311.03079.pdf)        |         [Vicuna-7B](https://github.com/THUDM/CogVLM)         | 313.21 |
|  35  |      [mPLUG-Owl2](https://arxiv.org/pdf/2311.04257.pdf)      | [LLaMA2-7B](https://github.com/X-PLUG/mPLUG-Owl/tree/main/mPLUG-Owl2) | 313.21 |
|  36  | [SPHINX](https://github.com/Alpha-VLLM/LLaMA2-Accessory/tree/main/SPHINX) | [LLaMA2-13B](https://github.com/Alpha-VLLM/LLaMA2-Accessory/tree/main/SPHINX) | 310.00 |
|  37  |        [Otter](https://arxiv.org/pdf/2305.03726.pdf)         |    [OTTER-Image-MPT7B](https://github.com/Luodian/Otter)     | 306.43 |
|  38  |      [HyperLLaVA](https://arxiv.org/pdf/2403.13447.pdf)      |     [Vicuna-13B](https://github.com/dcdmllm/hyperllava)      | 304.29 |
|  39  |      [ShareGPT4V](https://arxiv.org/pdf/2311.12793.pdf)      | [Vicuna-13B](https://github.com/InternLM/InternLM-XComposer/tree/main/projects/ShareGPT4V) | 303.21 |
|  40  | [MindSource-VL-Chat](https://github.com/luogen1996/LLaVA-HR) |   [MindSource-7B](https://github.com/luogen1996/LLaVA-HR)    | 301.43 |
|  41  |        [LLaVA](https://arxiv.org/pdf/2304.08485.pdf)         |      [Vicuna-13B](https://github.com/haotian-liu/LLaVA)      | 295.36 |
|  42  |     [InstructBLIP](https://arxiv.org/pdf/2305.06500.pdf)     | [FlanT5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/instructblip) | 291.79 |
|  43  |        [BLIP-2](https://arxiv.org/pdf/2301.12597.pdf)        | [Flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/blip2) | 290.00 |
|  44  |          [Muffin](https://github.com/thunlp/Muffin)          |        [Vicuna-13B](https://github.com/thunlp/Muffin)        | 290.00 |
|  45  |   [LVIS-INSTRUCT4V](https://arxiv.org/pdf/2311.07574.pdf)    |    [Vicuna-13B](https://github.com/X2FD/LVIS-INSTRUCT4V)     | 286.79 |
|  46  |      [mPLUG-Owl](https://arxiv.org/pdf/2304.14178.pdf)       | [LLaMA-7B](https://huggingface.co/MAGAer13/mplug-owl-llama-7b) | 276.07 |
|  47  |       [CogAgent](https://arxiv.org/pdf/2312.08914.pdf)       |         [Vicuna-7B](https://github.com/THUDM/CogVLM)         | 274.64 |
|  48  |      [MoE-LLaVA](https://arxiv.org/pdf/2401.15947.pdf)       |   [Phi-2.7B×4](https://github.com/PKU-YuanGroup/MoE-LLaVA)   | 262.14 |
|  49  |         [GIT2](https://arxiv.org/pdf/2205.14100.pdf)         | [VQAv2-finetuned](https://github.com/microsoft/GenerativeImage2Text) | 261.79 |
|  50  |        [LaVIN](https://arxiv.org/pdf/2305.15023.pdf)         |       [LAVIN-13B](https://github.com/luogen1996/LaVIN)       | 249.64 |
|  51  |       [VPGTrans](https://arxiv.org/pdf/2305.01278.pdf)       |      [Vicuna-7B](https://github.com/VPGTrans/VPGTrans)       | 249.29 |
|  52  |       [PandaGPT](https://arxiv.org/pdf/2305.16355.pdf)       |       [Vicuna-7B](https://github.com/yxuansu/PandaGPT)       | 228.57 |
|  53  |    [Multimodal-GPT](https://arxiv.org/pdf/2305.04790.pdf)    | [Multimodal-GPT-9B](https://github.com/open-mmlab/Multimodal-GPT) | 226.79 |
|  54  |         [Lynx](https://arxiv.org/pdf/2307.02469.pdf)         |      [Vicuna-7B](https://github.com/bytedance/lynx-llm)      | 215.71 |
|  55  | [ImageBind_LLM](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main) | [LLaMA-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/imagebind_LLM) | 213.57 |
|  56  |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     | 181.79 |
|  57  |      [MiniGPT-4](https://arxiv.org/pdf/2304.10592.pdf)       |    [Vicuna-13B](https://github.com/Vision-CAIR/MiniGPT-4)    | 144.29 |

### Commonsense Reasoning

| Rank |                            Model                             |                           Version                            | Score  |
| :--: | :----------------------------------------------------------: | :----------------------------------------------------------: | :----: |
|  🏅️   |       [InfMLLM](https://github.com/mightyzau/InfMLLM)        |      [Vicuna-13B](https://github.com/mightyzau/InfMLLM)      | 156.43 |
|  🥈   | [LLaVA-1.6](https://llava-vl.github.io/blog/2024-01-30-llava-1-6/) |      [Vicuna-34B](https://github.com/haotian-liu/LLaVA)      | 152.14 |
|  🥉   | [360VL](https://github.com/360CVGroup/360VL?tab=readme-ov-file) | [LLaMA3-70B](https://github.com/360CVGroup/360VL?tab=readme-ov-file) | 151.43 |
|  4   | [MiniCPM-Llama3-V 2.5](https://github.com/OpenBMB/MiniCPM-V) |      [LLaMA3-8B](https://github.com/OpenBMB/MiniCPM-V)       | 150.71 |
|  5   | [Qwen-VL-Max](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start) | [-](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start) | 148.57 |
|  6   | [InternLM-XComposer2-VL](https://github.com/InternLM/InternLM-XComposer) | [InternLM2-7B](https://github.com/InternLM/InternLM-XComposer) | 145.71 |
|  7   | [Qwen-VL-Plus](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start) | [-](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start) | 142.14 |
|  7   | [GPT-4V](https://cdn.openai.com/papers/GPTV_System_Card.pdf) |   [-](https://cdn.openai.com/papers/GPTV_System_Card.pdf)    | 142.14 |
|  8   |          [WeMM](https://github.com/scenarios/WeMM)           |       [InternLM-7B](https://github.com/scenarios/WeMM)       | 140.00 |
|  8   |       [RBDash](https://github.com/RBDash-Team/RBDash)        |     [Vicuna-13B](https://github.com/RBDash-Team/RBDash)      | 140.00 |
|  8   | [Bunny-8B](https://huggingface.co/BAAI/Bunny-v1_1-Llama-3-8B-V) |       [LLaMA3-8B](https://github.com/BAAI-DCAI/Bunny)        | 140.00 |
|  9   | [InternLM-XComposer-VL](https://github.com/InternLM/InternLM-XComposer) | [InternLM-7B](https://github.com/InternLM/InternLM-XComposer) | 138.57 |
|  10  |           [PureMM](https://github.com/Q-MM/PureMM)           |         [Vicuna-13B](https://github.com/Q-MM/PureMM)         | 137.86 |
|  11  |        [MMICL](https://arxiv.org/pdf/2309.07915.pdf)         |        [FlanT5xxl](https://github.com/HaozheZhao/MIC)        | 136.43 |
|  11  |        [BLIVA](https://arxiv.org/pdf/2308.09936.pdf)         |       [FlanT5xxl](https://github.com/mlpc-ucsd/BLIVA)        | 136.43 |
|  11  | [MindSource-VL-Chat](https://github.com/luogen1996/LLaVA-HR) |   [MindSource-7B](https://github.com/luogen1996/LLaVA-HR)    | 136.43 |
|  12  |    [InternVL-Chat-V1.5](https://arxiv.org/pdf/2404.16821)    |    [InternLM2-20B](https://github.com/OpenGVLab/InternVL)    | 135.00 |
|  13  |   [LVIS-INSTRUCT4V](https://arxiv.org/pdf/2311.07574.pdf)    |    [Vicuna-13B](https://github.com/X2FD/LVIS-INSTRUCT4V)     | 134.29 |
|  13  |      [HyperLLaVA](https://arxiv.org/pdf/2403.13447.pdf)      |     [Vicuna-13B](https://github.com/dcdmllm/hyperllava)      | 134.29 |
|  14  | [ChatTruth-7B](https://huggingface.co/mingdali/ChatTruth-7B) |   [Qwen-7B](https://huggingface.co/mingdali/ChatTruth-7B)    | 132.86 |
|  15  |  [TransCore-M](https://github.com/PCIResearch/TransCore-M)   | [PCITransGPT-13B](https://github.com/PCIResearch/TransCore-M) | 132.14 |
|  16  |     [Monkey-Chat](https://arxiv.org/pdf/2311.06607.pdf)      |       [Qwen-7B](https://github.com/Yuliang-Liu/Monkey)       | 131.43 |
|  17  |      [Qwen-VL-Chat](https://github.com/QwenLM/Qwen-VL/)      |         [Qwen-7B](https://github.com/QwenLM/Qwen-VL)         | 130.71 |
|  18  | [SPHINX](https://github.com/Alpha-VLLM/LLaMA2-Accessory/tree/main/SPHINX) | [LLaMA2-13B](https://github.com/Alpha-VLLM/LLaMA2-Accessory/tree/main/SPHINX) | 130.00 |
|  19  |     [InstructBLIP](https://arxiv.org/pdf/2305.06500.pdf)     | [FlanT5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/instructblip) | 129.29 |
|  19  | [Gemini Pro](https://storage.googleapis.com/deepmind-media/gemini/gemini_1_report.pdf) | [-](https://storage.googleapis.com/deepmind-media/gemini/gemini_1_report.pdf) | 129.29 |
|  20  | [MiniCPM-V-2](https://github.com/OpenBMB/MiniCPM/#minicpm-v) | [MiniCPM-2B](https://github.com/OpenBMB/MiniCPM/#minicpm-v)  | 128.57 |
|  21  |        [LLaVA](https://arxiv.org/pdf/2304.08485.pdf)         |      [Vicuna-13B](https://github.com/haotian-liu/LLaVA)      | 127.86 |
|  22  |     [BELLE-VL](https://huggingface.co/BELLE-2/BELLE-VL)      |     [Qwen-14B](https://huggingface.co/BELLE-2/BELLE-VL)      | 127.14 |
|  22  |   [OmniLMM](https://github.com/OpenBMB/MiniCPM/#minicpm-v)   | [Zephyr-7B-beta](https://github.com/OpenBMB/MiniCPM/#minicpm-v) | 127.14 |
|  23  |      [ShareGPT4V](https://arxiv.org/pdf/2311.12793.pdf)      | [Vicuna-13B](https://github.com/InternLM/InternLM-XComposer/tree/main/projects/ShareGPT4V) | 125.71 |
|  23  |        [CogVLM](https://arxiv.org/pdf/2311.03079.pdf)        |         [Vicuna-7B](https://github.com/THUDM/CogVLM)         | 125.71 |
|  24  |  [DataOptim-LLaVA](https://github.com/BAAI-DCAI/DataOptim)   |     [Vicuna-13B](https://github.com/BAAI-DCAI/DataOptim)     | 123.57 |
|  25  |  [InternVL-Chat-V1.1](https://arxiv.org/pdf/2312.14238.pdf)  |     [LLaMA2-13B](https://github.com/OpenGVLab/InternVL/)     | 123.57 |
|  25  |    [Bunny-4B](https://huggingface.co/BAAI/Bunny-v1_1-4B)     | [Phi-3-Mini-4K-Instruct](https://github.com/BAAI-DCAI/Bunny) | 123.57 |
|  26  |       [Honeybee](https://arxiv.org/pdf/2312.06742.pdf)       |     [Vicuna-13B](https://github.com/kakaobrain/honeybee)     | 122.86 |
|  27  |    [JT-VL-Chat](https://github.com/jiutiancv/JT-VL-Chat)     |         [-](https://github.com/jiutiancv/JT-VL-Chat)         | 122.14 |
|  28  |   [MiniCPM](https://github.com/OpenBMB/MiniCPM/#minicpm-v)   | [MiniCPM-2B](https://github.com/OpenBMB/MiniCPM/#minicpm-v)  | 119.29 |
|  29  |      [MoE-LLaVA](https://arxiv.org/pdf/2401.15947.pdf)       |   [Phi-2.7B×4](https://github.com/PKU-YuanGroup/MoE-LLaVA)   | 117.14 |
|  29  |       [CogAgent](https://arxiv.org/pdf/2312.08914.pdf)       |         [Vicuna-7B](https://github.com/THUDM/CogVLM)         | 117.14 |
|  30  |      [mPLUG-Owl2](https://arxiv.org/pdf/2311.04257.pdf)      | [LLaMA2-7B](https://github.com/X-PLUG/mPLUG-Owl/tree/main/mPLUG-Owl2) | 115.71 |
|  31  |         [Lynx](https://arxiv.org/pdf/2307.02469.pdf)         |      [Vicuna-7B](https://github.com/bytedance/lynx-llm)      | 110.71 |
|  32  |        [BLIP-2](https://arxiv.org/pdf/2301.12597.pdf)        | [Flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/blip2) | 110.00 |
|  32  |          [Muffin](https://github.com/thunlp/Muffin)          |        [Vicuna-13B](https://github.com/thunlp/Muffin)        | 110.00 |
|  33  |   [LLaMA-Adapter V2](https://arxiv.org/pdf/2304.15010.pdf)   | [LLaMA-Adapter-v2.1-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/llama_adapter_v2_multimodal7b) | 106.43 |
|  33  |        [Otter](https://arxiv.org/pdf/2305.03726.pdf)         |    [OTTER-Image-MPT7B](https://github.com/Luodian/Otter)     | 106.43 |
|  34  |   [LRV-Instruction](https://arxiv.org/pdf/2306.14565.pdf)    |    [LRV-7B](https://github.com/FuxiaoLiu/LRV-Instruction)    | 100.71 |
|  35  |         [GIT2](https://arxiv.org/pdf/2205.14100.pdf)         | [VQAv2-finetuned](https://github.com/microsoft/GenerativeImage2Text) | 99.29  |
|  36  |       [Cheetor](https://arxiv.org/pdf/2308.04152.pdf)        |       [Vicuna-7B](https://github.com/DCDmllm/Cheetah)        | 98.57  |
|  37  |        [LaVIN](https://arxiv.org/pdf/2305.15023.pdf)         |       [LAVIN-13B](https://github.com/luogen1996/LaVIN)       | 87.14  |
|  38  |      [mPLUG-Owl](https://arxiv.org/pdf/2304.14178.pdf)       | [LLaMA-7B](https://huggingface.co/MAGAer13/mplug-owl-llama-7b) | 78.57  |
|  39  |       [PandaGPT](https://arxiv.org/pdf/2305.16355.pdf)       |       [Vicuna-7B](https://github.com/yxuansu/PandaGPT)       | 73.57  |
|  40  |       [VPGTrans](https://arxiv.org/pdf/2305.01278.pdf)       |      [Vicuna-7B](https://github.com/VPGTrans/VPGTrans)       | 64.29  |
|  41  |      [MiniGPT-4](https://arxiv.org/pdf/2304.10592.pdf)       |    [Vicuna-13B](https://github.com/Vision-CAIR/MiniGPT-4)    | 59.29  |
|  42  |    [Multimodal-GPT](https://arxiv.org/pdf/2305.04790.pdf)    | [Multimodal-GPT-9B](https://github.com/open-mmlab/Multimodal-GPT) | 49.29  |
|  43  | [ImageBind_LLM](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main) | [LLaMA-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/imagebind_LLM) | 48.57  |
|  44  |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     | 39.29  |

### Numerical Calculation

| Rank |                            Model                             |                           Version                            | Score  |
| :--: | :----------------------------------------------------------: | :----------------------------------------------------------: | :----: |
|  🏅️   | [Qwen-VL-Max](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start) | [-](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start) | 155.00 |
|  🥈   | [InternLM-XComposer2-VL](https://github.com/InternLM/InternLM-XComposer) | [InternLM2-7B](https://github.com/InternLM/InternLM-XComposer) | 137.50 |
|  🥉   | [GPT-4V](https://cdn.openai.com/papers/GPTV_System_Card.pdf) |   [-](https://cdn.openai.com/papers/GPTV_System_Card.pdf)    | 130.00 |
|  4   |    [InternVL-Chat-V1.5](https://arxiv.org/pdf/2404.16821)    |    [InternLM2-20B](https://github.com/OpenGVLab/InternVL)    | 125.00 |
|  5   | [Qwen-VL-Plus](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start) | [-](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start) | 85.00  |
|  5   |    [Bunny-4B](https://huggingface.co/BAAI/Bunny-v1_1-4B)     | [Phi-3-Mini-4K-Instruct](https://github.com/BAAI-DCAI/Bunny) | 85.00  |
|  6   |        [MMICL](https://arxiv.org/pdf/2309.07915.pdf)         |        [FlanT5xxl](https://github.com/HaozheZhao/MIC)        | 82.50  |
|  7   |       [Cheetor](https://arxiv.org/pdf/2308.04152.pdf)        |       [Vicuna-7B](https://github.com/DCDmllm/Cheetah)        | 77.50  |
|  7   | [Gemini Pro](https://storage.googleapis.com/deepmind-media/gemini/gemini_1_report.pdf) | [-](https://storage.googleapis.com/deepmind-media/gemini/gemini_1_report.pdf) | 77.50  |
|  8   | [Bunny-8B](https://huggingface.co/BAAI/Bunny-v1_1-Llama-3-8B-V) |       [LLaMA3-8B](https://github.com/BAAI-DCAI/Bunny)        | 75.00  |
|  9   |        [Otter](https://arxiv.org/pdf/2305.03726.pdf)         |    [OTTER-Image-MPT7B](https://github.com/Luodian/Otter)     | 72.50  |
|  9   | [LLaVA-1.6](https://llava-vl.github.io/blog/2024-01-30-llava-1-6/) |      [Vicuna-34B](https://github.com/haotian-liu/LLaVA)      | 72.50  |
|  10  |   [LRV-Instruction](https://arxiv.org/pdf/2306.14565.pdf)    |    [LRV-7B](https://github.com/FuxiaoLiu/LRV-Instruction)    | 70.00  |
|  10  |  [InternVL-Chat-V1.1](https://arxiv.org/pdf/2312.14238.pdf)  |     [LLaMA2-13B](https://github.com/OpenGVLab/InternVL/)     | 70.00  |
|  10  | [360VL](https://github.com/360CVGroup/360VL?tab=readme-ov-file) | [LLaMA3-70B](https://github.com/360CVGroup/360VL?tab=readme-ov-file) | 70.00  |
|  11  |       [RBDash](https://github.com/RBDash-Team/RBDash)        |     [Vicuna-13B](https://github.com/RBDash-Team/RBDash)      | 67.50  |
|  11  |    [JT-VL-Chat](https://github.com/jiutiancv/JT-VL-Chat)     |         [-](https://github.com/jiutiancv/JT-VL-Chat)         | 67.50  |
|  12  |        [LaVIN](https://arxiv.org/pdf/2305.15023.pdf)         |       [LAVIN-13B](https://github.com/luogen1996/LaVIN)       | 65.00  |
|  13  |    [Multimodal-GPT](https://arxiv.org/pdf/2305.04790.pdf)    | [Multimodal-GPT-9B](https://github.com/open-mmlab/Multimodal-GPT) | 62.50  |
|  14  |      [mPLUG-Owl](https://arxiv.org/pdf/2304.14178.pdf)       | [LLaMA-7B](https://huggingface.co/MAGAer13/mplug-owl-llama-7b) | 60.00  |
|  14  |       [InfMLLM](https://github.com/mightyzau/InfMLLM)        |      [Vicuna-13B](https://github.com/mightyzau/InfMLLM)      | 60.00  |
|  14  |        [CogVLM](https://arxiv.org/pdf/2311.03079.pdf)        |         [Vicuna-7B](https://github.com/THUDM/CogVLM)         | 60.00  |
|  15  |        [BLIVA](https://arxiv.org/pdf/2308.09936.pdf)         |       [FlanT5xxl](https://github.com/mlpc-ucsd/BLIVA)        | 57.50  |
|  15  |          [WeMM](https://github.com/scenarios/WeMM)           |       [InternLM-7B](https://github.com/scenarios/WeMM)       | 57.50  |
|  15  |       [Honeybee](https://arxiv.org/pdf/2312.06742.pdf)       |     [Vicuna-13B](https://github.com/kakaobrain/honeybee)     | 57.50  |
|  17  | [ImageBind_LLM](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main) | [LLaMA-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/imagebind_LLM) | 55.00  |
|  17  | [InternLM-XComposer-VL](https://github.com/InternLM/InternLM-XComposer) | [InternLM-7B](https://github.com/InternLM/InternLM-XComposer) | 55.00  |
|  17  | [SPHINX](https://github.com/Alpha-VLLM/LLaMA2-Accessory/tree/main/SPHINX) | [LLaMA2-13B](https://github.com/Alpha-VLLM/LLaMA2-Accessory/tree/main/SPHINX) | 55.00  |
|  17  |  [TransCore-M](https://github.com/PCIResearch/TransCore-M)   | [PCITransGPT-13B](https://github.com/PCIResearch/TransCore-M) | 55.00  |
|  17  |   [OmniLMM](https://github.com/OpenBMB/MiniCPM/#minicpm-v)   | [Zephyr-7B-beta](https://github.com/OpenBMB/MiniCPM/#minicpm-v) | 55.00  |
|  18  |       [PandaGPT](https://arxiv.org/pdf/2305.16355.pdf)       |       [Vicuna-7B](https://github.com/yxuansu/PandaGPT)       | 50.00  |
|  18  |       [VPGTrans](https://arxiv.org/pdf/2305.01278.pdf)       |      [Vicuna-7B](https://github.com/VPGTrans/VPGTrans)       | 50.00  |
|  18  |         [GIT2](https://arxiv.org/pdf/2205.14100.pdf)         | [VQAv2-finetuned](https://github.com/microsoft/GenerativeImage2Text) | 50.00  |
|  18  |      [MoE-LLaVA](https://arxiv.org/pdf/2401.15947.pdf)       |   [Phi-2.7B×4](https://github.com/PKU-YuanGroup/MoE-LLaVA)   | 50.00  |
|  18  | [MiniCPM-Llama3-V 2.5](https://github.com/OpenBMB/MiniCPM-V) |      [LLaMA3-8B](https://github.com/OpenBMB/MiniCPM-V)       | 50.00  |
|  19  |   [LLaMA-Adapter V2](https://arxiv.org/pdf/2304.15010.pdf)   | [LLaMA-Adapter-v2.1-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/llama_adapter_v2_multimodal7b) | 47.50  |
|  19  |  [DataOptim-LLaVA](https://github.com/BAAI-DCAI/DataOptim)   |     [Vicuna-13B](https://github.com/BAAI-DCAI/DataOptim)     | 47.50  |
|  19  |     [BELLE-VL](https://huggingface.co/BELLE-2/BELLE-VL)      |     [Qwen-14B](https://huggingface.co/BELLE-2/BELLE-VL)      | 47.50  |
|  19  |   [MiniCPM](https://github.com/OpenBMB/MiniCPM/#minicpm-v)   | [MiniCPM-2B](https://github.com/OpenBMB/MiniCPM/#minicpm-v)  | 47.50  |
|  20  |      [MiniGPT-4](https://arxiv.org/pdf/2304.10592.pdf)       |    [Vicuna-13B](https://github.com/Vision-CAIR/MiniGPT-4)    | 45.00  |
|  20  |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     | 45.00  |
|  20  |          [Muffin](https://github.com/thunlp/Muffin)          |        [Vicuna-13B](https://github.com/thunlp/Muffin)        | 45.00  |
|  20  |      [ShareGPT4V](https://arxiv.org/pdf/2311.12793.pdf)      | [Vicuna-13B](https://github.com/InternLM/InternLM-XComposer/tree/main/projects/ShareGPT4V) | 45.00  |
|  20  |           [PureMM](https://github.com/Q-MM/PureMM)           |         [Vicuna-13B](https://github.com/Q-MM/PureMM)         | 45.00  |
|  20  |       [CogAgent](https://arxiv.org/pdf/2312.08914.pdf)       |         [Vicuna-7B](https://github.com/THUDM/CogVLM)         | 45.00  |
|  20  | [MindSource-VL-Chat](https://github.com/luogen1996/LLaVA-HR) |   [MindSource-7B](https://github.com/luogen1996/LLaVA-HR)    | 45.00  |
|  21  |        [LLaVA](https://arxiv.org/pdf/2304.08485.pdf)         |      [Vicuna-13B](https://github.com/haotian-liu/LLaVA)      | 42.50  |
|  21  |     [Monkey-Chat](https://arxiv.org/pdf/2311.06607.pdf)      |       [Qwen-7B](https://github.com/Yuliang-Liu/Monkey)       | 42.50  |
|  22  |        [BLIP-2](https://arxiv.org/pdf/2301.12597.pdf)        | [Flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/blip2) | 40.00  |
|  22  |     [InstructBLIP](https://arxiv.org/pdf/2305.06500.pdf)     | [FlanT5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/instructblip) | 40.00  |
|  22  |      [Qwen-VL-Chat](https://github.com/QwenLM/Qwen-VL/)      |         [Qwen-7B](https://github.com/QwenLM/Qwen-VL)         | 40.00  |
|  22  |   [LVIS-INSTRUCT4V](https://arxiv.org/pdf/2311.07574.pdf)    |    [Vicuna-13B](https://github.com/X2FD/LVIS-INSTRUCT4V)     | 40.00  |
|  22  | [ChatTruth-7B](https://huggingface.co/mingdali/ChatTruth-7B) |   [Qwen-7B](https://huggingface.co/mingdali/ChatTruth-7B)    | 40.00  |
|  23  |      [HyperLLaVA](https://arxiv.org/pdf/2403.13447.pdf)      |     [Vicuna-13B](https://github.com/dcdmllm/hyperllava)      | 37.50  |
|  24  |      [mPLUG-Owl2](https://arxiv.org/pdf/2311.04257.pdf)      | [LLaMA2-7B](https://github.com/X-PLUG/mPLUG-Owl/tree/main/mPLUG-Owl2) | 35.00  |
|  25  | [MiniCPM-V-2](https://github.com/OpenBMB/MiniCPM/#minicpm-v) | [MiniCPM-2B](https://github.com/OpenBMB/MiniCPM/#minicpm-v)  | 32.50  |
|  26  |         [Lynx](https://arxiv.org/pdf/2307.02469.pdf)         |      [Vicuna-7B](https://github.com/bytedance/lynx-llm)      | 17.50  |

### Text Translation

| Rank |                            Model                             |                           Version                            | Score  |
| :--: | :----------------------------------------------------------: | :----------------------------------------------------------: | :----: |
|  🏅️   | [Qwen-VL-Plus](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start) | [-](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start) | 185.00 |
|  🏅️   |    [InternVL-Chat-V1.5](https://arxiv.org/pdf/2404.16821)    |    [InternLM2-20B](https://github.com/OpenGVLab/InternVL)    | 185.00 |
|  🥈   | [Qwen-VL-Max](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start) | [-](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start) | 170.00 |
|  🥈   | [MiniCPM-V-2](https://github.com/OpenBMB/MiniCPM/#minicpm-v) | [MiniCPM-2B](https://github.com/OpenBMB/MiniCPM/#minicpm-v)  | 170.00 |
|  🥉   | [ChatTruth-7B](https://huggingface.co/mingdali/ChatTruth-7B) |   [Qwen-7B](https://huggingface.co/mingdali/ChatTruth-7B)    | 162.50 |
|  4   |      [Qwen-VL-Chat](https://github.com/QwenLM/Qwen-VL/)      |         [Qwen-7B](https://github.com/QwenLM/Qwen-VL)         | 147.50 |
|  4   | [InternLM-XComposer2-VL](https://github.com/InternLM/InternLM-XComposer) | [InternLM2-7B](https://github.com/InternLM/InternLM-XComposer) | 147.50 |
|  5   | [Gemini Pro](https://storage.googleapis.com/deepmind-media/gemini/gemini_1_report.pdf) | [-](https://storage.googleapis.com/deepmind-media/gemini/gemini_1_report.pdf) | 145.00 |
|  6   | [MiniCPM-Llama3-V 2.5](https://github.com/OpenBMB/MiniCPM-V) |      [LLaMA3-8B](https://github.com/OpenBMB/MiniCPM-V)       | 140.00 |
|  7   |     [Monkey-Chat](https://arxiv.org/pdf/2311.06607.pdf)      |       [Qwen-7B](https://github.com/Yuliang-Liu/Monkey)       | 137.50 |
|  8   |        [MMICL](https://arxiv.org/pdf/2309.07915.pdf)         |        [FlanT5xxl](https://github.com/HaozheZhao/MIC)        | 132.50 |
|  9   |          [WeMM](https://github.com/scenarios/WeMM)           |       [InternLM-7B](https://github.com/scenarios/WeMM)       | 130.00 |
|  10  |   [LLaMA-Adapter V2](https://arxiv.org/pdf/2304.15010.pdf)   | [LLaMA-Adapter-v2.1-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/llama_adapter_v2_multimodal7b) | 112.50 |
|  10  | [InternLM-XComposer-VL](https://github.com/InternLM/InternLM-XComposer) | [InternLM-7B](https://github.com/InternLM/InternLM-XComposer) | 112.50 |
|  11  |  [DataOptim-LLaVA](https://github.com/BAAI-DCAI/DataOptim)   |     [Vicuna-13B](https://github.com/BAAI-DCAI/DataOptim)     | 110.00 |
|  12  |    [JT-VL-Chat](https://github.com/jiutiancv/JT-VL-Chat)     |         [-](https://github.com/jiutiancv/JT-VL-Chat)         | 105.00 |
|  13  |      [mPLUG-Owl2](https://arxiv.org/pdf/2311.04257.pdf)      | [LLaMA2-7B](https://github.com/X-PLUG/mPLUG-Owl/tree/main/mPLUG-Owl2) | 102.50 |
|  13  |     [BELLE-VL](https://huggingface.co/BELLE-2/BELLE-VL)      |     [Qwen-14B](https://huggingface.co/BELLE-2/BELLE-VL)      | 102.50 |
|  13  |  [InternVL-Chat-V1.1](https://arxiv.org/pdf/2312.14238.pdf)  |     [LLaMA2-13B](https://github.com/OpenGVLab/InternVL/)     | 102.50 |
|  13  |    [Bunny-4B](https://huggingface.co/BAAI/Bunny-v1_1-4B)     | [Phi-3-Mini-4K-Instruct](https://github.com/BAAI-DCAI/Bunny) | 102.50 |
|  14  | [Bunny-8B](https://huggingface.co/BAAI/Bunny-v1_1-Llama-3-8B-V) |       [LLaMA3-8B](https://github.com/BAAI-DCAI/Bunny)        | 95.00  |
|  15  |           [PureMM](https://github.com/Q-MM/PureMM)           |         [Vicuna-13B](https://github.com/Q-MM/PureMM)         | 92.50  |
|  16  |       [Honeybee](https://arxiv.org/pdf/2312.06742.pdf)       |     [Vicuna-13B](https://github.com/kakaobrain/honeybee)     | 87.50  |
|  16  |      [HyperLLaVA](https://arxiv.org/pdf/2403.13447.pdf)      |     [Vicuna-13B](https://github.com/dcdmllm/hyperllava)      | 87.50  |
|  17  |   [LRV-Instruction](https://arxiv.org/pdf/2306.14565.pdf)    |    [LRV-7B](https://github.com/FuxiaoLiu/LRV-Instruction)    | 85.00  |
|  18  |   [MiniCPM](https://github.com/OpenBMB/MiniCPM/#minicpm-v)   | [MiniCPM-2B](https://github.com/OpenBMB/MiniCPM/#minicpm-v)  | 82.50  |
|  19  |      [mPLUG-Owl](https://arxiv.org/pdf/2304.14178.pdf)       | [LLaMA-7B](https://huggingface.co/MAGAer13/mplug-owl-llama-7b) | 80.00  |
|  19  |      [ShareGPT4V](https://arxiv.org/pdf/2311.12793.pdf)      | [Vicuna-13B](https://github.com/InternLM/InternLM-XComposer/tree/main/projects/ShareGPT4V) | 80.00  |
|  19  | [MindSource-VL-Chat](https://github.com/luogen1996/LLaVA-HR) |   [MindSource-7B](https://github.com/luogen1996/LLaVA-HR)    | 80.00  |
|  20  |        [LLaVA](https://arxiv.org/pdf/2304.08485.pdf)         |      [Vicuna-13B](https://github.com/haotian-liu/LLaVA)      | 77.50  |
|  20  |       [VPGTrans](https://arxiv.org/pdf/2305.01278.pdf)       |      [Vicuna-7B](https://github.com/VPGTrans/VPGTrans)       | 77.50  |
|  20  |        [BLIVA](https://arxiv.org/pdf/2308.09936.pdf)         |       [FlanT5xxl](https://github.com/mlpc-ucsd/BLIVA)        | 77.50  |
|  20  |       [InfMLLM](https://github.com/mightyzau/InfMLLM)        |      [Vicuna-13B](https://github.com/mightyzau/InfMLLM)      | 77.50  |
|  20  |   [OmniLMM](https://github.com/OpenBMB/MiniCPM/#minicpm-v)   | [Zephyr-7B-beta](https://github.com/OpenBMB/MiniCPM/#minicpm-v) | 77.50  |
|  21  | [GPT-4V](https://cdn.openai.com/papers/GPTV_System_Card.pdf) |   [-](https://cdn.openai.com/papers/GPTV_System_Card.pdf)    | 75.00  |
|  21  | [SPHINX](https://github.com/Alpha-VLLM/LLaMA2-Accessory/tree/main/SPHINX) | [LLaMA2-13B](https://github.com/Alpha-VLLM/LLaMA2-Accessory/tree/main/SPHINX) | 75.00  |
|  21  |        [CogVLM](https://arxiv.org/pdf/2311.03079.pdf)        |         [Vicuna-7B](https://github.com/THUDM/CogVLM)         | 75.00  |
|  22  |          [Muffin](https://github.com/thunlp/Muffin)          |        [Vicuna-13B](https://github.com/thunlp/Muffin)        | 72.50  |
|  22  |       [RBDash](https://github.com/RBDash-Team/RBDash)        |     [Vicuna-13B](https://github.com/RBDash-Team/RBDash)      | 72.50  |
|  22  | [LLaVA-1.6](https://llava-vl.github.io/blog/2024-01-30-llava-1-6/) |      [Vicuna-34B](https://github.com/haotian-liu/LLaVA)      | 72.50  |
|  22  | [360VL](https://github.com/360CVGroup/360VL?tab=readme-ov-file) | [LLaMA3-70B](https://github.com/360CVGroup/360VL?tab=readme-ov-file) | 72.50  |
|  23  |   [LVIS-INSTRUCT4V](https://arxiv.org/pdf/2311.07574.pdf)    |    [Vicuna-13B](https://github.com/X2FD/LVIS-INSTRUCT4V)     | 70.00  |
|  24  |         [GIT2](https://arxiv.org/pdf/2205.14100.pdf)         | [VQAv2-finetuned](https://github.com/microsoft/GenerativeImage2Text) | 67.50  |
|  25  |        [BLIP-2](https://arxiv.org/pdf/2301.12597.pdf)        | [Flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/blip2) | 65.00  |
|  25  |     [InstructBLIP](https://arxiv.org/pdf/2305.06500.pdf)     | [FlanT5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/instructblip) | 65.00  |
|  26  |       [CogAgent](https://arxiv.org/pdf/2312.08914.pdf)       |         [Vicuna-7B](https://github.com/THUDM/CogVLM)         | 62.50  |
|  27  |    [Multimodal-GPT](https://arxiv.org/pdf/2305.04790.pdf)    | [Multimodal-GPT-9B](https://github.com/open-mmlab/Multimodal-GPT) | 60.00  |
|  28  |        [Otter](https://arxiv.org/pdf/2305.03726.pdf)         |    [OTTER-Image-MPT7B](https://github.com/Luodian/Otter)     | 57.50  |
|  28  |       [PandaGPT](https://arxiv.org/pdf/2305.16355.pdf)       |       [Vicuna-7B](https://github.com/yxuansu/PandaGPT)       | 57.50  |
|  28  |       [Cheetor](https://arxiv.org/pdf/2308.04152.pdf)        |       [Vicuna-7B](https://github.com/DCDmllm/Cheetah)        | 57.50  |
|  28  |      [MoE-LLaVA](https://arxiv.org/pdf/2401.15947.pdf)       |   [Phi-2.7B×4](https://github.com/PKU-YuanGroup/MoE-LLaVA)   | 57.50  |
|  29  |  [TransCore-M](https://github.com/PCIResearch/TransCore-M)   | [PCITransGPT-13B](https://github.com/PCIResearch/TransCore-M) | 55.00  |
|  30  | [ImageBind_LLM](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main) | [LLaMA-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/imagebind_LLM) | 50.00  |
|  30  |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     | 50.00  |
|  31  |        [LaVIN](https://arxiv.org/pdf/2305.15023.pdf)         |       [LAVIN-13B](https://github.com/luogen1996/LaVIN)       | 47.50  |
|  32  |         [Lynx](https://arxiv.org/pdf/2307.02469.pdf)         |      [Vicuna-7B](https://github.com/bytedance/lynx-llm)      | 42.50  |
|  33  |      [MiniGPT-4](https://arxiv.org/pdf/2304.10592.pdf)       |    [Vicuna-13B](https://github.com/Vision-CAIR/MiniGPT-4)    |  0.00  |

### Code Reasoning

| Rank |                            Model                             |                           Version                            | Score  |
| :--: | :----------------------------------------------------------: | :----------------------------------------------------------: | :----: |
|  🏅️   | [GPT-4V](https://cdn.openai.com/papers/GPTV_System_Card.pdf) |   [-](https://cdn.openai.com/papers/GPTV_System_Card.pdf)    | 170.00 |
|  🏅️   | [Qwen-VL-Max](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start) | [-](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start) | 170.00 |
|  🥈   |          [WeMM](https://github.com/scenarios/WeMM)           |       [InternLM-7B](https://github.com/scenarios/WeMM)       | 117.50 |
|  🥉   |    [InternVL-Chat-V1.5](https://arxiv.org/pdf/2404.16821)    |    [InternLM2-20B](https://github.com/OpenGVLab/InternVL)    | 105.00 |
|  4   | [InternLM-XComposer2-VL](https://github.com/InternLM/InternLM-XComposer) | [InternLM2-7B](https://github.com/InternLM/InternLM-XComposer) | 100.00 |
|  4   | [LLaVA-1.6](https://llava-vl.github.io/blog/2024-01-30-llava-1-6/) |      [Vicuna-34B](https://github.com/haotian-liu/LLaVA)      | 100.00 |
|  5   |   [LLaMA-Adapter V2](https://arxiv.org/pdf/2304.15010.pdf)   | [LLaMA-Adapter-v2.1-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/llama_adapter_v2_multimodal7b) | 90.00  |
|  5   |     [Monkey-Chat](https://arxiv.org/pdf/2311.06607.pdf)      |       [Qwen-7B](https://github.com/Yuliang-Liu/Monkey)       | 90.00  |
|  5   | [Qwen-VL-Plus](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start) | [-](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start) | 90.00  |
|  6   |       [Cheetor](https://arxiv.org/pdf/2308.04152.pdf)        |       [Vicuna-7B](https://github.com/DCDmllm/Cheetah)        | 87.50  |
|  7   | [InternLM-XComposer-VL](https://github.com/InternLM/InternLM-XComposer) | [InternLM-7B](https://github.com/InternLM/InternLM-XComposer) | 85.00  |
|  7   | [Gemini Pro](https://storage.googleapis.com/deepmind-media/gemini/gemini_1_report.pdf) | [-](https://storage.googleapis.com/deepmind-media/gemini/gemini_1_report.pdf) | 85.00  |
|  7   |           [PureMM](https://github.com/Q-MM/PureMM)           |         [Vicuna-13B](https://github.com/Q-MM/PureMM)         | 85.00  |
|  8   |  [DataOptim-LLaVA](https://github.com/BAAI-DCAI/DataOptim)   |     [Vicuna-13B](https://github.com/BAAI-DCAI/DataOptim)     | 80.00  |
|  9   |        [MMICL](https://arxiv.org/pdf/2309.07915.pdf)         |        [FlanT5xxl](https://github.com/HaozheZhao/MIC)        | 77.50  |
|  9   | [360VL](https://github.com/360CVGroup/360VL?tab=readme-ov-file) | [LLaMA3-70B](https://github.com/360CVGroup/360VL?tab=readme-ov-file) | 77.50  |
|  10  |        [BLIP-2](https://arxiv.org/pdf/2301.12597.pdf)        | [Flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/blip2) | 75.00  |
|  10  |       [InfMLLM](https://github.com/mightyzau/InfMLLM)        |      [Vicuna-13B](https://github.com/mightyzau/InfMLLM)      | 75.00  |
|  10  | [MiniCPM-V-2](https://github.com/OpenBMB/MiniCPM/#minicpm-v) | [MiniCPM-2B](https://github.com/OpenBMB/MiniCPM/#minicpm-v)  | 75.00  |
|  11  |   [LRV-Instruction](https://arxiv.org/pdf/2306.14565.pdf)    |    [LRV-7B](https://github.com/FuxiaoLiu/LRV-Instruction)    | 72.50  |
|  11  |  [TransCore-M](https://github.com/PCIResearch/TransCore-M)   | [PCITransGPT-13B](https://github.com/PCIResearch/TransCore-M) | 72.50  |
|  12  |        [Otter](https://arxiv.org/pdf/2305.03726.pdf)         |    [OTTER-Image-MPT7B](https://github.com/Luodian/Otter)     | 70.00  |
|  13  |   [MiniCPM](https://github.com/OpenBMB/MiniCPM/#minicpm-v)   | [MiniCPM-2B](https://github.com/OpenBMB/MiniCPM/#minicpm-v)  | 65.00  |
|  14  |          [Muffin](https://github.com/thunlp/Muffin)          |        [Vicuna-13B](https://github.com/thunlp/Muffin)        | 62.50  |
|  14  |   [OmniLMM](https://github.com/OpenBMB/MiniCPM/#minicpm-v)   | [Zephyr-7B-beta](https://github.com/OpenBMB/MiniCPM/#minicpm-v) | 62.50  |
|  15  | [ImageBind_LLM](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main) | [LLaMA-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/imagebind_LLM) | 60.00  |
|  15  |        [BLIVA](https://arxiv.org/pdf/2308.09936.pdf)         |       [FlanT5xxl](https://github.com/mlpc-ucsd/BLIVA)        | 60.00  |
|  15  |      [mPLUG-Owl2](https://arxiv.org/pdf/2311.04257.pdf)      | [LLaMA2-7B](https://github.com/X-PLUG/mPLUG-Owl/tree/main/mPLUG-Owl2) | 60.00  |
|  15  | [MiniCPM-Llama3-V 2.5](https://github.com/OpenBMB/MiniCPM-V) |      [LLaMA3-8B](https://github.com/OpenBMB/MiniCPM-V)       | 60.00  |
|  16  |      [mPLUG-Owl](https://arxiv.org/pdf/2304.14178.pdf)       | [LLaMA-7B](https://huggingface.co/MAGAer13/mplug-owl-llama-7b) | 57.50  |
|  16  |     [InstructBLIP](https://arxiv.org/pdf/2305.06500.pdf)     | [FlanT5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/instructblip) | 57.50  |
|  16  |       [VPGTrans](https://arxiv.org/pdf/2305.01278.pdf)       |      [Vicuna-7B](https://github.com/VPGTrans/VPGTrans)       | 57.50  |
|  16  | [Bunny-8B](https://huggingface.co/BAAI/Bunny-v1_1-Llama-3-8B-V) |       [LLaMA3-8B](https://github.com/BAAI-DCAI/Bunny)        | 57.50  |
|  17  |    [Multimodal-GPT](https://arxiv.org/pdf/2305.04790.pdf)    | [Multimodal-GPT-9B](https://github.com/open-mmlab/Multimodal-GPT) | 55.00  |
|  17  |     [BELLE-VL](https://huggingface.co/BELLE-2/BELLE-VL)      |     [Qwen-14B](https://huggingface.co/BELLE-2/BELLE-VL)      | 55.00  |
|  18  |      [ShareGPT4V](https://arxiv.org/pdf/2311.12793.pdf)      | [Vicuna-13B](https://github.com/InternLM/InternLM-XComposer/tree/main/projects/ShareGPT4V) | 52.50  |
|  18  |        [CogVLM](https://arxiv.org/pdf/2311.03079.pdf)        |         [Vicuna-7B](https://github.com/THUDM/CogVLM)         | 52.50  |
|  18  | [ChatTruth-7B](https://huggingface.co/mingdali/ChatTruth-7B) |   [Qwen-7B](https://huggingface.co/mingdali/ChatTruth-7B)    | 52.50  |
|  19  |        [LaVIN](https://arxiv.org/pdf/2305.15023.pdf)         |       [LAVIN-13B](https://github.com/luogen1996/LaVIN)       | 50.00  |
|  19  | [SPHINX](https://github.com/Alpha-VLLM/LLaMA2-Accessory/tree/main/SPHINX) | [LLaMA2-13B](https://github.com/Alpha-VLLM/LLaMA2-Accessory/tree/main/SPHINX) | 50.00  |
|  19  |       [RBDash](https://github.com/RBDash-Team/RBDash)        |     [Vicuna-13B](https://github.com/RBDash-Team/RBDash)      | 50.00  |
|  19  |       [CogAgent](https://arxiv.org/pdf/2312.08914.pdf)       |         [Vicuna-7B](https://github.com/THUDM/CogVLM)         | 50.00  |
|  19  |    [Bunny-4B](https://huggingface.co/BAAI/Bunny-v1_1-4B)     | [Phi-3-Mini-4K-Instruct](https://github.com/BAAI-DCAI/Bunny) | 50.00  |
|  20  |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     | 47.50  |
|  20  |       [PandaGPT](https://arxiv.org/pdf/2305.16355.pdf)       |       [Vicuna-7B](https://github.com/yxuansu/PandaGPT)       | 47.50  |
|  20  |        [LLaVA](https://arxiv.org/pdf/2304.08485.pdf)         |      [Vicuna-13B](https://github.com/haotian-liu/LLaVA)      | 47.50  |
|  20  |       [Honeybee](https://arxiv.org/pdf/2312.06742.pdf)       |     [Vicuna-13B](https://github.com/kakaobrain/honeybee)     | 47.50  |
|  21  |         [Lynx](https://arxiv.org/pdf/2307.02469.pdf)         |      [Vicuna-7B](https://github.com/bytedance/lynx-llm)      | 45.00  |
|  21  |         [GIT2](https://arxiv.org/pdf/2205.14100.pdf)         | [VQAv2-finetuned](https://github.com/microsoft/GenerativeImage2Text) | 45.00  |
|  21  |  [InternVL-Chat-V1.1](https://arxiv.org/pdf/2312.14238.pdf)  |     [LLaMA2-13B](https://github.com/OpenGVLab/InternVL/)     | 45.00  |
|  21  |      [HyperLLaVA](https://arxiv.org/pdf/2403.13447.pdf)      |     [Vicuna-13B](https://github.com/dcdmllm/hyperllava)      | 45.00  |
|  21  |    [JT-VL-Chat](https://github.com/jiutiancv/JT-VL-Chat)     |         [-](https://github.com/jiutiancv/JT-VL-Chat)         | 45.00  |
|  22  |      [Qwen-VL-Chat](https://github.com/QwenLM/Qwen-VL/)      |         [Qwen-7B](https://github.com/QwenLM/Qwen-VL)         | 42.50  |
|  22  |   [LVIS-INSTRUCT4V](https://arxiv.org/pdf/2311.07574.pdf)    |    [Vicuna-13B](https://github.com/X2FD/LVIS-INSTRUCT4V)     | 42.50  |
|  23  |      [MiniGPT-4](https://arxiv.org/pdf/2304.10592.pdf)       |    [Vicuna-13B](https://github.com/Vision-CAIR/MiniGPT-4)    | 40.00  |
|  23  | [MindSource-VL-Chat](https://github.com/luogen1996/LLaVA-HR) |   [MindSource-7B](https://github.com/luogen1996/LLaVA-HR)    | 40.00  |
|  24  |      [MoE-LLaVA](https://arxiv.org/pdf/2401.15947.pdf)       |   [Phi-2.7B×4](https://github.com/PKU-YuanGroup/MoE-LLaVA)   | 37.50  |
