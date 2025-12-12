# Spanish MEACorpus 2023
## A multi-modal speech-text corpus for emotion analysis in Spanish from natural environments

### Highlights
- Multimodal corpus for Emotion Recognition in Spanish in natural environments.
- Evaluation of textual and audio features for Speech Emotion Recognition.
- Evaluation of different LLMs for Speech Emotion Recognition.
- Evaluation of a multimodal model with a late fusion approach.
- The multimodal approach improves the overall performance.

### Authors

- **Ronghao Pan** — University of Murcia  
  [Google Scholar](https://scholar.google.com/citations?user=80lntLMAAAAJ) · [ORCID](https://orcid.org/0009-0008-7317-7145)

- **José Antonio García-Díaz** — University of Murcia  
  [Google Scholar](https://scholar.google.com/citations?user=ek7NIYUAAAAJ) · [ORCID](https://orcid.org/0000-0002-3651-2660)

- **Miguel Ángel Rodríguez-García** — UNED
  [Google Scholar](https://scholar.google.com/citations?user=Rn1YH4cAAAAJ&hl=en) · [ORCID](https://orcid.org/0000-0001-6244-6532)

- **Rafael Valencia-García** — University of Murcia  
  [Google Scholar](https://scholar.google.com/citations?user=GLpBPNMAAAAJ) · [ORCID](https://orcid.org/0000-0003-2457-1791)  

> **Affiliations:**  
> \* *Departamento de Informática y Sistemas, Universidad de Murcia, Campus de Espinardo, Murcia, Spain*  
> \* *Universidad Nacional de Educacion a Distancia, Madrid, Spain*

### Publication
https://www.sciencedirect.com/science/article/pii/S0920548924000254

### Abstract
In human–computer interaction, emotion recognition provides a deeper understanding of the user’s emotions, enabling empathetic and effective responses based on the user’s emotional state. While deep learning models have improved emotion recognition solutions, it is still an active area of research. One important limitation is that most emotion recognition systems use only text as input, ignoring features such as voice intonation. Another limitation is the limited number of datasets available for multimodal emotion recognition. In addition, most published datasets contain emotions that are simulated by professionals and produce limited results in real-world scenarios. In other languages, such as Spanish, hardly any datasets are available. Therefore, our contributions to emotion recognition are as follows. First, we compile and annotate a new corpus for multimodal emotion recognition in Spanish (Spanish MEACorpus 2023), which contains 13.16 h of speech divided into 5129 segments labeled by considering Ekman’s six basic emotions. The dataset is extracted from YouTube videos in natural environments. Second, we explore several deep learning models for emotion recognition using text- and audio-based features. Third, we evaluate different multimodal techniques to build a multimodal recognition system that improves the results of unimodal models, achieving a Macro F1-score of 87.745%, using late fusion with concatenation strategy approach.

### Dataset
To request the dataset for academic purposes, please fill this form:
https://forms.gle/M668aLqHEuA4Qp1k7


#### Dataset statistics

The table below summarizes the structure of the Spanish MEACorpus 2023 dataset. The corpus contains a total of 5,129 emotionally annotated speech segments, distributed into training and test splits following speaker-independent criteria. Emotion categories show natural imbalance—particularly for fear—reflecting realistic emotional distributions in spontaneous speech. The corpus includes more than 790 minutes of labeled audio, with an average segment duration of approximately 9.2 seconds across all emotion classes.

| Emotion  | Train | Test | Total | Total Length (min) | Avg Length (s) |
|----------|------:|-----:|------:|--------------------:|----------------:|
| anger    |  534  | 134  |  668  | 106.24             | 9.54            |
| disgust  |  960  | 240  | 1200  | 174.82             | 8.74            |
| fear     |   29  |  8   |   37  |  5.13              | 8.31            |
| joy      |  514  | 129  |  643  | 101.84             | 9.50            |
| neutral  | 1600  | 399  | 1999  | 312.66             | 9.38            |
| sadness  |  465  | 117  |  582  |  89.38             | 9.21            |
| **Total**| **4102** | **1027** | **5129** | **790.08** | **9.24** |


### Acknowledgments
This work is part of the research projects **LaTe4PoliticES (PID2022-138099OB-I00)** funded by *MCIN/AEI/10.13039/501100011033* and the *European Fund for Regional Development (FEDER)-a way to make Europe* and **LT-SWM (TED2021-131167B-I00)** funded by *MCIN/AEI/10.13039/501100011033* and by the *European Union NextGenerationEU/PRTR*. In addition, this work has been also funded by **``Programa para la Recualificación del Sistema Universitario Español 2021-2023''**, and the *Community of Madrid*, through the **Young Researchers R+D Project. Ref. M2173 – SGTRS** (co-funded by *Rey Juan Carlos University*) and **PEJD-2019-PRE/TIC-16151**.


### Citation
```
@article{pan2024spanish,
  title={Spanish MEACorpus 2023: A multimodal speech--text corpus for emotion analysis in Spanish from natural environments},
  author={Pan, Ronghao and Garc{\'\i}a-D{\'\i}az, Jos{\'e} Antonio and Rodr{\'\i}guez-Garc{\'\i}a, Miguel {\'A}ngel and Valencia-Garc{\'\i}a, Rafel},
  journal={Computer Standards \& Interfaces},
  volume={90},
  pages={103856},
  year={2024},
  publisher={Elsevier}
}
```

