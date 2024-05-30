# ACM_MM-2023

[AbCoRD: Exploiting multimodal generative approach for Aspect-based Complaint and Rationale Detection](https://dl.acm.org/doi/10.1145/3581783.3613776)

**Dataset**

We extend the _CESAMARD-Aspect_ dataset (https://github.com/appy1608/ECIR2023\_Complaint-Detection). The dataset contains 3962 reviews, with 1321 of them in the complaint category and 2641 in the non-complaint category. It includes information such as image URLs, review titles, review texts, and relevant aspect categories, aspect-level complaint labels. The five domains in the dataset are electronics, edibles, fashion, books, and miscellaneous. There are three common aspects shared between all the domains namely, packaging, price, and quality. 

The annotated causal span is selected such that best explains the reason for the complaint label in each aspect-level complaint instance based on the review text and review image for each instance in the dataset. Th new dataset is named as **CESAMARD-Rationale**.


**Software**

The proposed model HAMMER reframes the multitasking problem as a multimodal text-to-text generation task. HAMMER serves as a benchmark for Aspect-Level Complaint and Rationale detection (AlCR). It addresses three key aspects:

a) Aspect Class Detection (ACD) 

b) Aspect-Level Complaint Classification (ACC)

c) Aspect-Level Rationale Detection (ARD)


**_Files_**

The repository includes:

Implementation files for the HAMMER model

Commonsense inference files

CESAMARD-Rationale dataset

      
**CITE**

@inproceedings{jain2023abcord,
  title={AbCoRD: Exploiting multimodal generative approach for Aspect-based Complaint and Rationale Detection},
  author={Jain, Raghav and Singh, Apoorva and Gangwar, Vivek and Saha, Sriparna},
  booktitle={Proceedings of the 31st ACM International Conference on Multimedia},
  pages={8571--8579},
  year={2023}
}
