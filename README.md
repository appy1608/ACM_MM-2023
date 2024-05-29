# ACM_MM-2023

**AbCoRD: Exploiting multimodal generative approach for Aspect-based Complaint and Rationale Detection**

**Dataset**

We extended the **CESAMARD-Aspect** dataset (https://github.com/appy1608/ECIR2023\_Complaint-Detection). The dataset contains 3962 reviews, with 1321 of them in the complaint category and 2641 in the non-complaint category. It includes information such as image URLs, review titles, review texts, and relevant complaint, sentiment, and emotion labels. The dataset is divided into several domains, including electronics, edibles, fashion, books, and miscellaneous, which makes it ideal for aspect-level complaint and rationale analysis. 

The five domains in the dataset are electronics, edibles, fashion, books, and miscellaneous. There are three common aspects shared between all the domains namely, packaging, price, and quality. The annotated causal span is selected such that best explains the reason for the complaint label in each aspect-level complaint instance in the dataset.


**Software**

The proposed model **HAMMER**, a Hierarchical Approach for Multi-Modal generative Extraction of Rationale and complaints which reframes the multitasking problem as a multimodal text-to-text generation task and addresses aspect class detection (ACD), aspect-level complaint classification (ACC), and aspect-level rationale detection (ARD). The HAMMER model serves as a benchmark for aspect-level complaint and rationale detection (AlCR), evaluation results demonstrate that the proposed generative model consistently achieves significantly better performance than other baselines and state-of-the-art models in both full and few-shot settings. The software file consists of the implementation files as well as commonsense inference files.



**CITE**

@inproceedings{jain2023abcord,
  title={AbCoRD: Exploiting multimodal generative approach for Aspect-based Complaint and Rationale Detection},
  author={Jain, Raghav and Singh, Apoorva and Gangwar, Vivek and Saha, Sriparna},
  booktitle={Proceedings of the 31st ACM International Conference on Multimedia},
  pages={8571--8579},
  year={2023}
}
