# SFT Datasets

<font size=5><center><b> Table of Contents </b> </center></font>
- [SFT Datasets](#sft-datasets)
- [Awesome SFT Datasets](#awesome-sft-datasets)
  - [Caption](#caption)
  - [General VQA](#general-vqa)
  - [Mathematics](#mathematics)
  - [Chart \& Table](#chart--table)
  - [OCR](#ocr)
  - [Knowledge](#knowledge)
  - [Grounding](#grounding)
  - [Science](#science)
  - [Conversation](#conversation)
  - [Medical](#medical)
  - [GUI](#gui)
- [Awesome Reasoning Datasets](#)
- [Awesome Thinking With Images Datasets](#sft-datasets)
   - [SFT Date](#gui)
   - [RL Date](#gui)
---

# Awesome SFT Datasets

## Caption

| Name                           | Paper                                                        | Year | Volume | Language | Modality | Link                                                         |
| ------------------------------ | ------------------------------------------------------------ | ---- | ------ | -------- | -------- | ------------------------------------------------------------ |
| **TextCaps**                   | [TextCaps](https://arxiv.org/abs/2003.12462)                 | 2020 | 145K   | en       | Image    | [TextCaps](https://textvqa.org/textcaps/)                    |
| **ShareGPT4o**                 | [ShareGPT4o](https://sharegpt4o.github.io/)                  | 2024 | 200K   | en & zh  | Image    | [ShareGPT-4o](https://huggingface.co/datasets/OpenGVLab/ShareGPT-4o) |
| **CoCo Caption**               | [CoCo Caption](https://arxiv.org/abs/1504.00325)             | 2015 | 118K   | en & zh  | Image    | [coco-caption](https://github.com/tylin/coco-caption)        |
| **New YorkerCaptionContest**   | [New YorkerCaptionContest](https://arxiv.org/abs/2209.06293) | 2022 | 148K   | en       | Image    | [newyorker_caption_contest](https://huggingface.co/datasets/jmhessel/newyorker_caption_contest) |
| **MMInstruct**                 | [MMInstruct](https://arxiv.org/abs/2407.15838)               | 2024 | 161K   | en & zh  | Image    | [MMInstruct](https://huggingface.co/datasets/yuecao0119/MMInstruct-GPT4V) |
| **Image Paragraph Captioning** | [Image Paragraph Captioning](https://arxiv.org/abs/1611.06607) | 2016 | 19K    | en       | Image    | [**Image Paragraph Captioning**](http://visualgenome.org/static/data/dataset/paragraphs_v1.json.zip) |
| **ShareGPT4V-100K**            | [ShareGPT4V-100K](https://arxiv.org/abs/2311.12793)          | 2023 | 100K   | en       | Image    | [ ShareGPT4V](https://huggingface.co/datasets/Lin-Chen/ShareGPT4V) |
| **Vript**                      | [Vript](https://arxiv.org/abs/2406.06040)                    | 2024 | 1.39M  | en & zh  | Video    | **[Vript_Multilingual](https://huggingface.co/datasets/Mutonix/Vript_Multilingual/)** |
| **OpenVid**                    | [OpenVid](https://arxiv.org/abs/2407.02371)                  | 2024 | 1M     | en       | Video    | [OpenVid-1M](https://huggingface.co/datasets/nkp37/OpenVid-1M) |
| **ShareGPT4o-Video**           | [ShareGPT4o-Video](https://sharegpt4o.github.io/)            | 2024 | 10K    | en & zh  | Video    | [ShareGPT-4o](https://huggingface.co/datasets/OpenGVLab/ShareGPT-4o) |
| **ShareGPT4-Video**            | [ShareGPT4-Video](https://arxiv.org/abs/2406.04325)          | 2024 | 40K    | en & zh  | Video    | [ShareGPT4Video](https://huggingface.co/datasets/ShareGPT4Video/ShareGPT4Video) |
| **VideoGPT+**                  | [VideoGPT+](https://arxiv.org/abs/2406.09418)                | 2024 | 112K   | en       | Video    | [VideoGPT-plus_Training_Dataset](https://huggingface.co/datasets/MBZUAI/VideoGPT-plus_Training_Dataset) |
| **MSR-VTT**                    | [MSR-VTT](https://openaccess.thecvf.com/content_cvpr_2016/papers/Xu_MSR-VTT_A_Large_CVPR_2016_paper.pdf) | 2016 | 200K   | en       | Video    | [MSR-VTT](https://huggingface.co/datasets/friedrichor/MSR-VTT) |

## General VQA

| Name                | Paper                                                        | Year     | Volume   | Language | Modality  | Link                                                         |
| ------------------- | ------------------------------------------------------------ | -------- | -------- | -------- | --------- | ------------------------------------------------------------ |
| **GQA**             | **[GQA](https://arxiv.org/abs/1902.09506)**                  | **2019** | **22M**  | **en**   | **Image** | [GQA: Visual Reasoning in the Real World](https://cs.stanford.edu/people/dorarad/gqa/download.html) |
| **VQAv2**           | **[VQAv2](https://arxiv.org/abs/1612.00837)**                | **2016** | **1M**   | **en**   | **Image** | [VQA: Visual Question Answering](https://visualqa.org/download.html) |
| **ALLaVA**          | **[ALLaVA](https://arxiv.org/abs/2402.11684)**               | **2024** | **660K** | **en**   | **Image** | [ALLaVA-4V](https://huggingface.co/datasets/FreedomIntelligence/ALLaVA-4V) |
| **SVIT**            | **[SVIT](https://arxiv.org/abs/2307.04087)**                 | **2023** | **4.2M** | **en**   | **Image** | [SVIT](https://huggingface.co/datasets/BAAI/SVIT)            |
| **LVIS-Instruct4V** | **[LVIS-Instruct4V](https://arxiv.org/abs/2311.07574)**      | **2023** | **220K** | **en**   | **Image** | [LVIS-Instruct4V](https://huggingface.co/datasets/X2FD/LVIS-Instruct4V) |
| **Img-Diff**        | **[Img-Diff](https://arxiv.org/abs/2408.04594)**             | **2024** | **12K**  | **en**   | **Image** | [Img-Diff](https://huggingface.co/datasets/datajuicer/Img-Diff) |
| **Spot-the-diff**   | **[Spot-the-diff](https://arxiv.org/abs/1808.10584)**        | **2018** | **13K**  | **en**   | **Image** | [spot-the-diff](https://github.com/harsh19/spot-the-diff)    |
| **NLVR2**           | **[NLVR2](https://arxiv.org/abs/1811.00491)**                | **2018** | **107K** | **en**   | **Image** | [Natural Language for Visual Reasoning](https://lil.nlp.cornell.edu/nlvr/) |
| **FSC147**          | **[Learning to count everything](http://openaccess.thecvf.com/content/CVPR2021/html/Ranjan_Learning_To_Count_Everything_CVPR_2021_paper.html)** | **2021** | **6135** | **en**   | **Image** | [FSC147](https://drive.google.com/file/d/1ymDYrGs9DSRicfZbSCDiOu0ikGDh5k6S/view?usp=sharing) |
| VSR                 | [Visual spatial reasoning](https://direct.mit.edu/tacl/article/doi/10.1162/tacl_a_00566/116470) | 2023     | 11K      | en       | Image     | [vsr_random](https://huggingface.co/datasets/cambridgeltl/vsr_random) & [vsr_zeroshot](https://huggingface.co/datasets/cambridgeltl/vsr_zeroshot) |
| Visual7W            | [Visual7w: Grounded question answering in images](http://openaccess.thecvf.com/content_cvpr_2016/html/Zhu_Visual7W_Grounded_Question_CVPR_2016_paper.html) | 2016     | 47300    | en       | Image     | [Visual7w ](https://huggingface.co/datasets/geoskyr/visual7w) |
| VideoInstruct       | [VideoInstruct](https://arxiv.org/abs/2306.05424)            | 2023     | 100K     | en       | Video     | [VideoInstruct-100K](https://huggingface.co/datasets/MBZUAI/VideoInstruct-100K) |
| EgoTaskQA           | [EgoTaskQA](https://arxiv.org/abs/2210.03929)                | 2022     | 40K      | en       | Video     | [EgoTaskQA - Download](https://sites.google.com/view/egotaskqa/download) |
| MovieQA             | [MovieQA](https://arxiv.org/abs/1512.02902)                  | 2015     | 15K      | en       | Video     | [movie_QA](https://huggingface.co/datasets/HiTruong/movie_QA) |
| CLEVERER            | [CLEVERER](https://arxiv.org/abs/1910.01442)                 | 2019     | 305K     | en       | Video     | [CLEVRER](http://clevrer.csail.mit.edu/#Dataset)             |
| LLaVA-Video         | [Video instruction tuning with synthetic data](https://arxiv.org/abs/2410.02713) | 2024     | 178k     | en       | Video     | [LLaVA-Video](https://drive.google.com/file/d/1ymDYrGs9DSRicfZbSCDiOu0ikGDh5k6S/view?usp=sharing) |
| PerceptionTes       | [Perception test: A diagnostic benchmark for multimodal video models](https://proceedings.neurips.cc/paper_files/paper/2023/hash/8540fba4abdc7f9f7a7b1cc6cd60e409-Abstract-Datasets_and_Benchmarks.html) | 2024     | 11620    | en       | Video     | [perception_test](https://github.com/google-deepmind/perception_test) |
| STAR                | [Star: A benchmark for situated reasoning in real-world videos](https://arxiv.org/abs/2405.09711) | 2024     | 60k      | en       | Video     | [STAR](https://bobbywu.com/STAR/)                            |


## Mathematics

| Name            | Paper                                                 | Year | Volume | Language | Modality | Link                                                         |
| --------------- | ----------------------------------------------------- | ---- | ------ | -------- | -------- | ------------------------------------------------------------ |
| **GeoQA+**      | [GeoQA+](https://aclanthology.org/2022.coling-1.130/) | 2022 | 12K    | en       | Image    | [GeoQA-Plus](https://github.com/SCNU203/GeoQA-Plus)          |
| **CLEVR-Math**  | [CLEVR-Math](https://arxiv.org/abs/2208.05358)        | 2022 | 68.3K  | en       | Image    | [clevr-math](https://huggingface.co/datasets/dali-does/clevr-math) |
| **Super-CLEVR** | [Super-CLEVR](https://arxiv.org/abs/2212.00259)       | 2022 | 600K   | en       | Image    | [Super-CLEVR](https://github.com/Lizw14/Super-CLEVR)         |
| **MapQA**       | [MapQA](https://arxiv.org/abs/2211.08545)             | 2022 | 800K   | en       | Image    | [MapQA](https://buckeyemailosu-my.sharepoint.com/:f:/g/personal/chang_1692_buckeyemail_osu_edu/EvJWDbG5_5ZMlA1mJVtZceEBqO1TiZaUUuFxKXeIQYQgig?e=pyV1Ad) |
| **MAVIS**       | [MAVIS](https://arxiv.org/abs/2407.08739)             | 2024 | 1.39M  | en       | Image    | [ MAVIS-Instruct-Geometry](https://huggingface.co/datasets/CaraJ/MAVIS-Geometry)   && [ MAVIS-Instruct-Function](https://huggingface.co/datasets/CaraJ/MAVIS-Function) |
| **Geometry3K**  | [Geometry3K](https://arxiv.org/abs/2105.04165)        | 2021 | 3K     | en       | Image    | [Inter-GPS](https://lupantech.github.io/inter-gps/)          |
| **TallyQA**     | [TallyQA](https://arxiv.org/abs/1810.12440)           | 2018 | 28.8K  | en       | Image    | [tallyqa-test](https://huggingface.co/datasets/vikhyatk/tallyqa-test) |
| **GEOS**        | [GEOS](https://aclanthology.org/D15-1171/)            | 2015 | 395K   | en       | Image    | [GeoS - Geometry Problem Solver](http://geometry.allenai.org/) |
| **UniGeo**      | [UniGeo](https://arxiv.org/abs/2212.02746)            | 2022 | 14.5K  | en       | Image    | [UniGeo](https://github.com/chen-judge/UniGeo)               |
| **GeomVerse**   | [GeomVerse](https://arxiv.org/abs/2312.12241)         | 2023 | 12K    | en       | Image    | [**GeomVerse**](https://storage.googleapis.com/gresearch/GeomVerseV0/GeomVerse.zip) |
| **CMM-Math**    | [CMM-Math](https://arxiv.org/abs/2409.02834)          | 2024 | 28K    | zh       | Image    | [EduChat-Math](https://github.com/ECNU-ICALK/EduChat-Math)   |
| **MathQA**      | [MathQA](https://arxiv.org/abs/1905.13319)            | 2019 | 37.2K  | en       | Image    | [MathQA-Dataset](https://math-qa.github.io/math-QA/)         |

## Chart & Table

|      Name       | Paper                                                        | Year | Volume | Language | Modality | Link                                                         |
| :-------------: | ------------------------------------------------------------ | ---- | ------ | -------- | -------- | ------------------------------------------------------------ |
|   **ChartQA**   | [Chartqa: A benchmark for question answering about charts with visual andlogical reasoning](https://arxiv.org/pdf/2203.10244) | 2022 | 32.7K  | en       | Image    | [ChartQA](https://huggingface.co/datasets/ahmed-masry/ChartQA) |
|    **DVQA**     | [Dvqa: Understanding data visualizations via question answering](https://openaccess.thecvf.com/content_cvpr_2018/papers/Kafle_DVQA_Understanding_Data_CVPR_2018_paper.pdf) | 2018 | 3.487M | en       | Image    | [ DVQA](https://huggingface.co/datasets/DavidNguyen/DVQA)    |
|   **PlotQA**    | [Plotqa: Reasons over scientific plots](http://openaccess.thecvf.com/content_WACV_2020/papers/Methani_PlotQA_Reasoning_over_Scientific_Plots_WACV_2020_paper.pdf) | 2020 | 28M    | en       | Image    | [PlotQA](https://github.com/NiteshMethani/PlotQA/blob/master/PlotQA_Dataset.md) |
|  **FigureQA**   | [FigureQA: An annotated figure dataset for visual reasoning](https://arxiv.org/pdf/1710.07300) | 2018 | 1M     | en       | Image    | [figureqa](https://huggingface.co/datasets/vikhyatk/figureqa) |
|   **TabMWP**    | [Dynamic prompt learning via policy gradient for semi-structured mathematical reasoning](https://arxiv.org/pdf/2209.14610) | 2023 | 38K    | en       | Image    | [PromptPG](https://promptpg.github.io/)                      |
|  **MMC-Inst**   | [Mmc: Advancing multimodal chart understanding with large-scale instruction tuning](https://arxiv.org/pdf/2311.10774) | 2024 | 600K   | en       | Image    | [MMC](https://huggingface.co/datasets/xywang1/MMC)           |
|  **UniChart**   | [Unichart: A universal vision-language pretrained model for chart comprehension and reasoning](https://arxiv.org/pdf/2305.14761) | 2023 | 189K   | en       | Image    | [unichart-pretrain-data](https://huggingface.co/datasets/ahmed-masry/unichart-pretrain-data)  && [UniChart-pretrain-images](https://huggingface.co/datasets/ahmed-masry/UniChart-pretrain-images) |
|     VisText     | [Vistext: A benchmark for semantically rich chart captioning](https://arxiv.org/abs/2307.05356) | 2023 | 12441  | en       | Image    | [mitvis/vistext: VisText is a benchmark dataset for semantically rich chart captioning.](https://github.com/mitvis/vistext) |
| LRV-Instruction | [Mitigating Hallucination in Large Multi-Modal Models via Robust Instruction Tuning](http://arxiv.org/abs/2306.14565) | 2024 | 400k   | en       | Image    | [LRV-Instruction](https://github.com/FuxiaoLiu/LRV-Instruction/blob/main/download.txt#L28) |
|     ArxivQA     | [Multimodal arxiv: A dataset for improving scientific comprehension of large vision-language models](https://arxiv.org/abs/2403.00231) | 2024 | 100k   | en       | Image    | [ArxivQA](https://huggingface.co/datasets/MMInstruction/ArxivQA) |


## OCR

| Name         | Paper                                                        | Year | Volume | Language | Modality | Link                                                     |
| ------------ | ------------------------------------------------------------ | ---- | ------ | -------- | -------- | ------------------------------------------------------------ |
| **TextCaps** | [TextCaps](https://arxiv.org/abs/2003.12462)                 | 2020 | 28K    | en       | Image    | [TextCaps](https://textvqa.org/textcaps/dataset/)            |
| **LSVT**     | [LSVT](https://arxiv.org/abs/1909.07741)                     | 2019 | 450K   | zh       | Image    | [LSVT-2019](https://huggingface.co/datasets/1398listener/LSVT-2019) |
| **RCTW-17**  | [RCTW-17](https://arxiv.org/abs/1708.09585)                  | 2017 | 12K    | zh       | Image    | [rctw](http://rctw.vlrlab.net/)                              |
| **InfoVQA**  | [InfoVQA](https://arxiv.org/abs/2104.12756)                  | 2021 | 30K    | en       | Image    | [InfographicVQA](https://www.docvqa.org/datasets/infographicvqa) |
| **DocVQA**   | [DocVQA](https://arxiv.org/abs/2007.00398)                   | 2020 | 50K    | en       | Image    | [DocVQA ](https://www.docvqa.org/datasets)                   |
| **MPDocVQA** | [MPDocVQA](https://arxiv.org/abs/2212.05935)                 | 2022 | 46K    | en       | Image    | [MP-DocVQA](https://github.com/rubenpt91/MP-DocVQA-Framework) |
| HME100K      | [Syntax-aware network for handwritten mathematical expression recognition](http://openaccess.thecvf.com/content/CVPR2022/html/Yuan_Syntax-Aware_Network_for_Handwritten_Mathematical_Expression_Recognition_CVPR_2022_paper.html) | 2022 | 100k   | en       | Image    | [HME100K](https://ai.100tal.com/dataset)                     |
| POIE         | [Visual information extraction in the wild: practical dataset and end-to-end solution](https://link.springer.com/chapter/10.1007/978-3-031-41731-3_3) | 2023 | 111K   | en       | Image    | [POIE](https://drive.google.com/file/d/1eEMNiVeLlD-b08XW_GfAGfPmmII-GDYs/view?usp=share_link.) |

## Knowledge

| Name                | Paper                                                        | Year | Volume | Language      | Modality | Link                                                         |
| ------------------- | ------------------------------------------------------------ | ---- | ------ | ------------- | -------- | ------------------------------------------------------------ |
| **iNaturalist2018** | [iNaturalist](https://arxiv.org/abs/1707.06642)              | 2017 | 675K   | en            | Image    | [iNaturalist](https://www.inaturalist.org/)                  |
| **MovieNet**        | [MovieNet](https://arxiv.org/abs/2007.10937)                 | 2020 | 1.1M   | en            | Image    | [MovieNet](https://movienet.github.io/)                      |
| **ART500K**         | [DeepArt](https://dl.acm.org/doi/10.1145/3123266.3123405)    | 2017 | 500K   | en            | Image    | [deepart](http://deepart.ece.ust.hk/)                        |
| **KonIQ-10K**       | [KonIQ-10k](https://arxiv.org/abs/1910.06180)                | 2019 | 10K    | en            | Image    | [KonIQ-10k Database](https://database.mmsp-kn.de/koniq-10k-database.html) |
| **WorldArt**        | [WordArt](https://arxiv.org/abs/2208.00438)                  | 2022 | 4.8K   | en            | Image    | [WorldArt](https://drive.google.com/file/d/1SanxRwTxd2q7UrQxlbC3BmP3nhFXwZ3g/view?usp=sharing) |
| **KVQA**            | [KVQA](https://ojs.aaai.org/index.php/AAAI/article/view/4915) | 2019 | 183K   | en            | Image    | [KVQA](http://malllabiisc.github.io/resources/kvqa/)         |
| **A-OKVQA**         | [A-OKVQA](https://arxiv.org/abs/2206.01718)                  | 2022 | 25K    | en            | Image    | [A-OKVQA](https://huggingface.co/datasets/HuggingFaceM4/A-OKVQA) |
| **ViQuAE**          | [ViQuAE](https://dl.acm.org/doi/10.1145/3477495.3531753)     | 2022 | 3.7K   | en            | Image    | [viquae_dataset](https://huggingface.co/datasets/PaulLerner/viquae_dataset) |
| **WIT**             | [WIT](https://arxiv.org/abs/2103.01913)                      | 2021 | 37.6M  | 108 languages | Image    | [wit](https://github.com/google-research-datasets/wit/blob/main/DATA.md) |
| **STEM-QA**         | [STEM-QA](https://arxiv.org/abs/2402.17205)                  | 2024 | 1M     | en            | Image    | [STEM](https://huggingface.co/datasets/stemdataset/STEM)     |


## Grounding

| Name                  | Paper                                                       | Year | Volume | Language | Modality | Link                                                         |
| --------------------- | ----------------------------------------------------------- | ---- | ------ | -------- | -------- | ------------------------------------------------------------ |
| **RefCOCO**           | [Paper](https://arxiv.org/abs/1511.02283)                   | 2016 | 130K   | en       | Image    | [Google_Refexp_toolbox](https://github.com/mjhucla/Google_Refexp_toolbox) |
| **GPT4Gen-RD-BoxCoT** | [Paper](https://arxiv.org/abs/2306.15195)                   | 2023 | 5.9K   | en       | Image    | [shikra](https://github.com/shikras/shikra/blob/main/docs/data.md) |
| **All-Seeing-V2**     | [Paper](https://arxiv.org/abs/2402.19474)                   | 2024 | 127K   | en       | Image    | [AS-V2](https://huggingface.co/datasets/OpenGVLab/AS-V2)     |
| **V3Det**             | [Paper](https://arxiv.org/abs/2304.03752)                   | 2023 | 1.7M   | en & zh  | Image    | [V3Det](https://huggingface.co/datasets/yhcao/V3Det_ImageNet21k_Cls_100) |
| **DsLMF**             | [Paper](https://www.nature.com/articles/s41597-023-02322-9) | 2023 | 16K    | en       | Image    |                                                              |
| **COCO-ReM**          | [Paper](https://arxiv.org/abs/2403.18819)                   | 2024 | 1.09M  | en & zh  | Image    | [COCO-ReM](https://cocorem.xyz/)                             |
| **TolokaVQA**         | [Paper](https://arxiv.org/abs/2309.16511)                   | 2023 | 45K    | en       | Image    | [Toloka VQA](https://www.kaggle.com/datasets/dustalov/toloka-wsdm-cup-2023-vqa) |

## Science

| Name             | Paper                                                        | Year | Volume | Language | Modality | Link                                                         |
| ---------------- | ------------------------------------------------------------ | ---- | ------ | -------- | -------- | ------------------------------------------------------------ |
| **AI2D**         | [AI2D](https://arxiv.org/abs/1603.07396)                     | 2016 | 15K    | en       | Image    | [ai2d](https://huggingface.co/datasets/lmms-lab/ai2d)        |
| **ScienceQA**    | [ScienceQA](https://arxiv.org/abs/2209.09513)                | 2022 | 21K    | en       | Image    | [**ScienceQA**](https://scienceqa.github.io/)                |
| **TQA**          | [TQA](https://openaccess.thecvf.com/content_cvpr_2017/papers/Kembhavi_Are_You_Smarter_CVPR_2017_paper.pdf) | 2017 | 26K    | en       | Image    | [TQA](http://textbookqa.org/)                                |
| **ChemVLM Data** | [ChemVLM Data](https://arxiv.org/abs/2408.07246)             | 2024 | 257K   | en & zh  | Image    | [ChemVLM_test_data](https://huggingface.co/datasets/Duke-de-Artois/ChemVLM_test_data) |

## Conversation

| Name             | Paper                                                        | Year | Volume | Language  | Modality | Link                                                         |
| ---------------- | ------------------------------------------------------------ | ---- | ------ | --------- | -------- | ------------------------------------------------------------ |
| ALLaVA           | [Allava: Harnessing gpt4v-synthesized data for a lite vision-language model](https://arxiv.org/pdf/2402.11684) | 2024 | 664K   | en & zh   | Image    | [ALLaVA-4V](https://huggingface.co/datasets/FreedomIntelligence/ALLaVA-4V) |
| Viet-ShareGPT4o  | [Vintern-1b: An efficient multimodal large language model for vietnamese](https://arxiv.org/pdf/2408.12480) | 2024 | -      | vi        | Image    | [Vintern-1B-v2](https://huggingface.co/5CD-AI/Vintern-1B-v2) |
| Cambrain-GPT4o   | [Cambrian-1: A fully open, vision-centric exploration of multimodal llms](https://arxiv.org/pdf/2406.16860?) | 2024 | 10M    | en        | Image    | [Cambrian-10M](https://huggingface.co/datasets/nyu-visionx/Cambrian-10M) |
| RLAIF-V          | [Rlaif-v: Aligning mllms through open-source ai feedback for super gpt-4v trustworthiness](https://arxiv.org/pdf/2405.17220) | 2024 | 33.8k  | en        | Image    | [RLAIF-V-Dataset](https://huggingface.co/datasets/openbmb/RLAIF-V-Dataset) |
| WildVision-GPT4o | [Wildvision: Evaluating vision-language models in the wild with human preferences](https://arxiv.org/pdf/2406.11069) | 2024 | 45.2k  | en        | Image    | [wildvision-chat](https://huggingface.co/datasets/WildVision/wildvision-chat) |
| UniMM-Chat       | [Reformulating vision-language foundation models and datasets towards universal multimodal assistants](https://arxiv.org/abs/2310.00653) | 2023 | 117k   | en        | Image    | [ UniMM-Chat](https://huggingface.co/datasets/Yirany/UniMM-Chat) |
| Shikra           | [Shikra: Unleashing multimodal llm's referential dialogue magic](https://arxiv.org/abs/2306.15195) | 2023 | 640M   | en        | Image    | [Google Driver](https://drive.google.com/file/d/1CNLu1zJKPtliQEYCZlZ8ykH00ppInnyN/view?usp=drive_link) or [Baidu Netdisk](https://pan.baidu.com/s/1qGTIqgJ54eijzT4-XJJIyg?pwd=9ri4) |
| Viet-ShareGPT4o  | https://arxiv.org/pdf/2408.12480                             | 2024 | 1.9k   | vi 越南语 | Image    | [Viet-ShareGPT-4o-Puzzle-VQA ](https://huggingface.co/datasets/5CD-AI/Viet-ShareGPT-4o-Puzzle-VQA) |

## Medical

| Name             | Paper                                                        | Year | Volume | Language | Modality | Link                                                         |
| ---------------- | ------------------------------------------------------------ | ---- | ------ | -------- | -------- | ------------------------------------------------------------ |
| PMC-VQA          | [Pmc-vqa](https://arxiv.org/pdf/2305.10415)                  | 2023 | 227K   | en       | Image    | [pmc_vqa_base](https://huggingface.co/datasets/withcomment/pmc_vqa_base) |
| VQA-RAD          | [A dataset of clinically generated visual questions and answers about radiology images](https://www.nature.com/articles/sdata2018251.pdf) | 2018 | 3.5K   | en       | Image    | [vqa-rad](https://huggingface.co/datasets/flaviagiammarino/vqa-rad) |
| PathVQA          | [Pathvqa](https://arxiv.org/pdf/2003.10286)                  | 2020 | 32.8K  | en       | Image    | [path-vqa](https://huggingface.co/datasets/flaviagiammarino/path-vqa) |
| VQA-Med          | [Vqa-med](https://arodes.hes-so.ch/record/4214/files/Published version.pdf) | 2019 | 15K    | en       | Image    | [VQA-Med-2019](https://github.com/abachaa/VQA-Med-2019)      |
| SLAKE            | [Slake](https://arxiv.org/pdf/2102.09542)                    | 2021 | 14K    | en & zh  | Image    | [SLAKE](https://www.med-vqa.com/slake/)                      |
| GMAI-VL          | [Gmai-vl & gmai-vl-5.5 m](https://arxiv.org/pdf/2411.14522)  | 2024 | 5.5M   | en & zh  | Image    |                                                              |
| PMC-CaseReport   |                                                              | 2023 | 438k   | en       | Image    | [PMC-CaseReport](https://huggingface.co/datasets/chaoyi-wu/PMC-CaseReport) |
| Medical-Diff-VQA | [Medical-Diff-VQA: A Large-Scale Medical Dataset for Difference Visual Question Answering on Chest X-Ray Images v1.0.1](https://physionet.org/content/medical-diff-vqa/1.0.1/) | 2023 | 700k   | en       | Image    | [Medical-Diff-VQA](https://physionet.org/content/medical-diff-vqa/1.0.1/) |


## GUI

| Name               | Paper                                                  | Year | Volume | Language | Modality | Link                                                         |
| ------------------ | ------------------------------------------------------ | ---- | ------ | -------- | -------- | ------------------------------------------------------------ |
| **Screen2Words**   | [Screen2words](https://arxiv.org/abs/2108.03353)       | 2021 | 112K   | en       | Image    | [screen2words](https://github.com/google-research-datasets/screen2words) |
| **Widget-Caption** | [Widget captioning](https://arxiv.org/abs/2010.04295)  | 2020 | 162.8K | en       | Image    | [widget-caption](https://github.com/google-research-datasets/widget-caption) |
| **UIBert**         | [UIBert](https://arxiv.org/abs/2107.13731)             | 2021 | 537K   | en       | Image    | [uibert](https://github.com/google-research-datasets/uibert) |
| **RICO**           | [Rico](https://dl.acm.org/doi/10.1145/3126594.3126651) | 2017 | 72.2K  | en       | Image    | [RICO ](https://www.interactionmining.org/archive/rico)      |
| **AITW**           | [AndroidInTheWild](https://arxiv.org/abs/2307.10088)   | 2023 | 715    | en       | Image    | [android_in_the_wild at master ](https://github.com/google-research/google-research/tree/master/android_in_the_wild) |
| **Mind2Web**       | [Mind2Web](https://arxiv.org/abs/2306.06070)           | 2023 | 2K     | en       | Image    | [Mind2Web](https://huggingface.co/datasets/osunlp/Mind2Web)  |
| **SeeClick**       | [SeeClick](https://arxiv.org/abs/2401.10935)           | 2024 | 1.2K   | en       | Image    | [SeeClick](https://github.com/njucckevin/SeeClick)           |
| **ScreenQA**       | [ScreenQA](https://arxiv.org/abs/2209.08199)           | 2022 | 86K    | en       | Image    | **[screen_qa](https://github.com/google-research-datasets/screen_qa)** |
| **AMEX**           | [AMEX](https://arxiv.org/abs/2407.17490)               | 2024 | 2.4M   | en       | Image    | [AMEX-8k](https://huggingface.co/datasets/zonghanHZH/AMEX-8k) |
| **Odyssey**        | [GUI Odyssey](https://arxiv.org/abs/2406.08451)        | 2024 | 7.7K   | en       | Image    | [GUIOdyssey](https://huggingface.co/datasets/hflqf88888/GUIOdyssey) |
| **WebSight**       | [WebSight](https://arxiv.org/abs/2403.09029)           | 2024 | 2M     | en       | Image    | [GUIOdyssey](https://huggingface.co/datasets/hflqf88888/GUIOdyssey) |
| **AndroidControl** | [AndroidControl](https://arxiv.org/abs/2406.03679)     | 2024 | 15.3K  | en       | Image    | [android_control](https://github.com/google-research/google-research/tree/master/android_control) |
| **OmniACT**        | [OmniACT](https://arxiv.org/abs/2402.17553)            | 2024 | 9.8K   | en       | Image    | [omniact](https://huggingface.co/datasets/Writer/omniact)    |
| **GUI-World**      | [GUI-World](https://arxiv.org/abs/2406.10819)          | 2024 | 12.4K  | en       | Video    | [GUI-World](https://huggingface.co/datasets/ONE-Lab/GUI-World) |

# Reasoning

|                             Name                             |                            Paper                             | Year | Volume |                             Link                             |
| :----------------------------------------------------------: | :----------------------------------------------------------: | :--: | :----: | :----------------------------------------------------------: |
|                      **LLaVA-CoT-100k**                      | [Llava-cot: Let vision language models reason step-by-step](https://arxiv.org/abs/2411.10440) | 2024 |  100K  | [LLaVA-CoT-100k](https://huggingface.co/datasets/Xkev/LLaVA-CoT-100k) |
|        **ReClor (Reasoning with Commonsense Logic)**         | [Reclor: A reading comprehension dataset requiring logical reasoning](https://arxiv.org/abs/2002.04326) | 2020 |  6138  | [Download Link](https://github.com/yuweihao/reclor/releases/download/v1/reclor_data.zip) |
|       **AQUA-RAT (AQUA Reasoning and Answering Task)**       | [Program induction by rationale generation: Learning to solve and explain algebraic word problems](https://arxiv.org/abs/1705.04146) | 2021 |  100K  | [google-deepmind/AQuA: A algebraic word problem dataset, with multiple choice questions annotated with rationales.](https://github.com/google-deepmind/AQuA) |
|                        **cot_gsm8k**                         |                                                              | 2023 | 7.22K  | [cot_gsm8k](https://huggingface.co/datasets/Dahoas/cot_gsm8k) |
|               **GSM8K (Grade-School Math 8K)**               | [Training verifiers to solve math word problems](https://arxiv.org/abs/2110.14168) | 2022 |  8.5K  | [openai/grade-school-math](https://github.com/openai/grade-school-math?tab=readme-ov-file) |
|                         **cot_flan**                         |                                                              | 2023 | 67.3K  |      https://huggingface.co/datasets/causal-lm/cot_flan      |
|                **MATH (Mathematics Dataset)**                | [Measuring mathematical problem solving with the math dataset](https://arxiv.org/abs/2103.03874) | 2021 | 12.5K  | [competition_math](https://huggingface.co/datasets/qwedsacf/competition_math) |
|                      **CoT-Collection**                      | [The cot collection: Improving zero-shot and few-shot learning of language models via chain-of-thought fine-tuning](https://arxiv.org/abs/2305.14045) | 2023 | 1.84M  | [CoT-Collection](https://huggingface.co/datasets/kaist-ai/CoT-Collection) |
|                      **NuminaMath-CoT**                      | [Numinamath: The largest public dataset in ai4maths with 860k pairs of competition math problems and solutions](http://faculty.bicmr.pku.edu.cn/~dongbin/Publications/numina_dataset.pdf) | 2024 |  860K  | [NuminaMath-CoT](https://huggingface.co/datasets/AI-MO/NuminaMath-CoT) |
|                        NuminaMath 1.5                        |                                                              | 2025 |  896K  | [NuminaMath-1.5](https://huggingface.co/datasets/AI-MO/NuminaMath-1.5) |
|                  DeepScaleR-Preview-Dataset                  | [DeepScaleR: Surpassing O1-Preview with a 1.5B Model by Scaling RL](https://pretty-radio-b75.notion.site/DeepScaleR-Surpassing-O1-Preview-with-a-1-5B-Model-by-Scaling-RL-19681902c1468005bed8ca303013a4e2) | 2025 |  40K   | [DeepScaleR-Preview-Dataset](https://huggingface.co/datasets/agentica-org/DeepScaleR-Preview-Dataset) |
|                   STILL-3-Preview-RL-Data                    | [Imitate, Explore, and Self-Improve: A Reproduction Report on Slow-thinking Reasoning Systems]([[2412.09413\] Imitate, Explore, and Self-Improve: A Reproduction Report on Slow-thinking Reasoning Systems](https://arxiv.org/abs/2412.09413)) | 2024 |  30K   | [STILL-3-Preview-RL-Data](https://huggingface.co/datasets/RUC-AIBOX/STILL-3-Preview-RL-Data) |
|                          Omni-Math                           | [Omni-math: A universal olympiad level mathematic benchmark for large language models](https://arxiv.org/abs/2410.07985) | 2024 |  4.4K  | [Omni-Math](https://huggingface.co/datasets/KbsdJames/Omni-MATH) |
|                 AIME problems prior to 2024                  |                                                              | 2023 |  933   | [AIME problems prior to 2024](https://huggingface.co/datasets/gneubig/aime-1983-2024) |
|                       LeetCodeDataset                        | [Leetcodedataset: A temporal dataset for robust evaluation and efficient training of code llms](https://arxiv.org/abs/2504.14655) | 2025 |  2.6K  | [LeetCodeDataset](https://huggingface.co/datasets/newfacade/LeetCodeDataset) |
|                             TACO                             | [Taco: Topics in algorithmic code generation dataset](https://arxiv.org/abs/2312.14852) | 2023 |  26K   |      [TACO](https://huggingface.co/datasets/BAAI/TACO)       |
| [MMPR-v1.2](https://huggingface.co/datasets/OpenGVLab/MMPR-v1.2) | [Enhancing the reasoning ability of multimodal large language models via mixed preference optimization](https://arxiv.org/abs/2411.10442) | 2025 | 3.25M  | [MMPR-v1.2](https://huggingface.co/datasets/OpenGVLab/MMPR-v1.2) |
|                        VisualPRM400K                         | [Visualprm: An effective process reward model for multimodal reasoning](https://arxiv.org/abs/2503.10291) | 2025 |  400K  | [VisualPRM400K](https://huggingface.co/datasets/OpenGVLab/VisualPRM400K) |
|                          MMPR-Tiny                           | [Internvl3. 5: Advancing open-source multimodal models in versatility, reasoning, and efficiency](https://arxiv.org/abs/2508.18265) | 2025 |  70K   | [MMPR-Tiny](https://huggingface.co/datasets/OpenGVLab/MMPR-Tiny) |

# Thinking With Images


### SFT Date

| Name           | Paper                                                        | Year    | Volume | link                                                         |
| -------------- | ------------------------------------------------------------ | ------- | ------ | ------------------------------------------------------------ |
| VTS            | [Multi-Step Visual Reasoning with Visual Tokens Scaling and Verification](https://arxiv.org/abs/2506.07235) | 2025-06 | 315K   | [ VTS_SFT_Data](https://huggingface.co/datasets/vtsvnips2025/VTS_SFT_Data) |
| VGR            | [VGR: Visual Grounded Reasoning](https://arxiv.org/abs/2506.11991) | 2025-06 | 90K    | [ VGR](https://huggingface.co/datasets/BytedanceDouyinContent/VGR) |
| Pixel Reasoner | [Pixel Reasoner: Incentivizing Pixel-Space Reasoning with Curiosity-Driven Reinforcement Learning](https://arxiv.org/abs/2505.15966) | 2025-05 | 7.85k  | [PixelReasoner-SFT-Data](https://huggingface.co/datasets/TIGER-Lab/PixelReasoner-SFT-Data) |
| COF            | [Chain-of-Focus: Adaptive Visual Search and Zooming for Multimodal Reasoning via RL](https://arxiv.org/abs/2505.15436) | 2025-05 | 5.4k   | [CoF-SFT-Data-5.4k](https://huggingface.co/datasets/xintongzhang/CoF-SFT-Data-5.4k) |
| OpenThinkIMG   | [OpenThinkIMG: Learning to Think with Images via Visual Tool Reinforcement Learning](https://arxiv.org/abs/2505.08617) | 2025-05 | 2.94k  | [OpenThinkIMG-Chart-SFT-2942](https://huggingface.co/datasets/hitsmy/OpenThinkIMG-Chart-SFT-2942) |
| Thyme          | [Thyme: Think Beyond Images](https://arxiv.org/abs/2508.11630) | 2025-08 | 152k   | [Thyme-SFT](https://huggingface.co/datasets/Kwai-Keye/Thyme-SFT) |

### RL Date



| Name           | Paper                                                        | Year    | Volume   | link                                                         |
| -------------- | ------------------------------------------------------------ | ------- | -------- | ------------------------------------------------------------ |
| Orsta          | [One RL to See Them All: Visual Triple Unified Reinforcement Learning](https://arxiv.org/abs/2505.18129) | 2025-06 | 47k      | [Orsta-Data-47k](https://huggingface.co/datasets/One-RL-to-See-Them-All/Orsta-Data-47k) |
| Pixel Reasoner | [Pixel Reasoner: Incentivizing Pixel-Space Reasoning with Curiosity-Driven Reinforcement Learning](https://arxiv.org/abs/2505.15966) | 2025-05 | 15.4k    | [ PixelReasoner-RL-Data](https://huggingface.co/datasets/TIGER-Lab/PixelReasoner-RL-Data) |
| DeepEyes       | [DeepEyes: Incentivizing "Thinking with Images" via Reinforcement Learning](https://arxiv.org/abs/2505.14362) | 2025-05 | 47K      | [DeepEyes-Datasets-47k](https://huggingface.co/datasets/ChenShawn/DeepEyes-Datasets-47k) |
| OpenThinkIMG   | [OpenThinkIMG: Learning to Think with Images via Visual Tool Reinforcement Learning](https://arxiv.org/abs/2505.08617) | 2025-05 | 14.5k    | [ OpenThinkIMG-Chart-RL-14501](https://huggingface.co/datasets/hitsmy/OpenThinkIMG-Chart-RL-14501) |
| Seg-Zero       | [Seg-Zero: Reasoning-Chain Guided Segmentation via Cognitive Reinforcement](https://arxiv.org/abs/2503.06520) | 2025-03 | 9K && 7k | [refCOCOg_9k_840](https://huggingface.co/datasets/Ricky06662/refCOCOg_9k_840) &&  [VisionReasoner_multi_object_7k_840](https://huggingface.co/datasets/Ricky06662/VisionReasoner_multi_object_7k_840) |
| Thyme          | [Thyme: Think Beyond Images](https://arxiv.org/abs/2508.11630) | 2025-08 | 55.2k    | [Thyme-RL](https://huggingface.co/datasets/Kwai-Keye/Thyme-RL) |
| PyVision       | [PyVision: Agentic Vision with Dynamic Tooling](https://arxiv.org/abs/2507.07998) | 2025-07 | 50K      | [ PyVision-RL-Data-50K](https://huggingface.co/datasets/Agents-X/PyVision-RL-Data-50K) |
| MathCoder-VL   | [MathCoder-VL: Bridging Vision and Code for Enhanced Multimodal Mathematical Reasoning](https://arxiv.org/abs/2505.10557) | 2025-05 | 2.54M    | [MM-MathInstruct](https://huggingface.co/datasets/MathLLMs/MM-MathInstruct) |
