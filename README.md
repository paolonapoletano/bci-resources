# BCI Resources Repository

## 🧠 Overview
This is a curated collection of tools, datasets, research papers, tutorials, and software for anyone interested in **Brain-Computer Interface (BCI)** technologies. Whether you're a beginner or an experienced researcher, this repository is designed to be your go-to resource for exploring and innovating in the field of BCI.

---

## 📂 Contents

The repository is organized into the following sections:

1. [Datasets](#datasets)
   - Public EEG/BCI datasets for research and experimentation.
   - Includes motor imagery, visual evoked potentials (VEP), and more.

2. **Software Tools**  
   - Libraries and frameworks for signal processing and analysis.
   - Examples: EEGLab, OpenBCI, MNE-Python, BCILAB.

3. **Tutorials & Guides**  
   - Step-by-step guides to get started with BCI.
   - Advanced tutorials on signal processing and machine learning.

4. **Research Papers**  
   - A collection of foundational and cutting-edge BCI publications.

5. **Hardware**  
   - Recommendations for EEG devices and other BCI hardware.
   - Guides on DIY and open-source setups.

6. **Community & Events**  
   - Links to conferences, workshops, and online forums.

---

## 🚀 Getting Started

To begin your BCI journey:

1. Browse the repository structure and explore the resources.
2. Check out the [Tutorials](#tutorials--guides) section for hands-on learning.
3. Use the [Datasets](#datasets) to experiment with real-world EEG/BCI data.
4. Dive deeper into the [Research Papers](#research-papers) for academic insights.

---

## 📊 Datasets
The tables below, one for each task, provides an overview of key datasets used in BCI research. It includes details such as the year of publication, task type, number of classes, participants, and channels, as well as the sampling frequency, total recording time, whether the data was collected in a lab setting, and its availability in BCI frameworks.

### Motor Imagery
Motor Imagery (MI) in Brain-Computer Interface (BCI) applications refers to the mental simulation of movement without actual muscle activity. When a person imagines moving a limb (e.g., their left or right hand), specific patterns of brain activity, primarily in the sensorimotor cortex, can be detected using EEG. These patterns, often represented as event-related desynchronization (ERD) and event-related synchronization (ERS) in specific frequency bands (e.g., mu and beta), are used to decode the intended movement. MI-based BCIs enable applications like neurorehabilitation, prosthetic control, and communication for individuals with motor impairments.

| Dataset | Year | Task | #Classes | #Subjects | #Channels | Freq (Hz) | TotalTime (h) | LabSetting | Available in |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [A continuous pursuit dataset for online  deep learning-based EEG  brain-computer interface](https://doi.org/10.1038/s41597-024-04090-6) | 2024 | Motor Imagery | - | 28.0 | 64.0 | 1000.0 | 168.0 | yes | - |
| [Liu2024](https://doi.org/10.6084/m9.figshare.21679035.v5) | 2024 | Motor Imagery | 2 | 50.0 | 29.0 | 500.0 | 2.22 | yes | Moabb |
| [Stieger2021](https://doi.org/10.1038/s41597-021-00883-1) | 2021 | Motor Imagery | 4 | 62.0 | 64.0 | 1000.0 | 208.33 | yes | Moabb |
| [Lee2019_Motor Imagery](https://doi.org/10.1093/gigascience/giz002) | 2019 | Motor Imagery | 2 | 54.0 | 62.0 | 1000.0 | 12.22 | yes | Moabb |
| [The largest SCP data of Motor-Imagery](https://doi.org/10.6084/m9.figshare.c.3917698) | 2018 | Motor Imagery |  | 13.0 | 19.0 | 1000.0 | 60.0 | yes |  |
| [CHO2017](https://doi.org/10.1093/gigascience/gix034) | 2017 | Motor Imagery | 2 | 52.0 | 64.0 | 512.0 | 8.17 | yes | Moabb |
| [High-Gamma Dataset](https://github.com/robintibor/high-gamma-dataset) | 2017 | Motor Imagery | 4 | 14.0 | 128.0 | 250.0 | 67.0 |  |  |
| [Left/Right Hand Motor Imagery](http://gigadb.org/dataset/100295) | 2017 | Motor Imagery | 2 | 52.0 | 64.0 | 512.0 | 109.2 | yes |  |
| [Ofner2017](https://doi.org/10.1371/journal.pone.0182578) | 2017 | Motor Imagery | 7 | 15.0 | 61.0 | 512.0 | 52.5 | yes | Moabb |
| [Schirrmeister2017](https://doi.org/10.1002/hbm.23730) | 2017 | Motor Imagery | 4 | 14.0 | 128.0 | 500.0 | 14.93 | yes | Moabb |
| [Shin2017A-B](https://doi.org/10.1109/TNSRE.2016.2628057) | 2017 | Motor Imagery | 2 | 29.0 | 30.0 | 200.0 | 14.5 | yes | Moabb |
| [Zhou2016](https://doi.org/10.1371/journal.pone.0162657) | 2016 | Motor Imagery | 3 | 4.0 | 14.0 | 200.0 | 15.97 | yes | Moabb |
| [BNCI2015 001]() | 2015 | Motor Imagery | 2 | 12.0 | 13.0 | 512.0 | 20.0 | yes | Moabb |
| [BNCI2015 004]() | 2015 | Motor Imagery | 5 | 9.0 | 30.0 | 256.0 | 14.0 | yes | Moabb |
| [BNCI2014 001]() | 2014 | Motor Imagery | 4 | 9.0 | 22.0 | 250.0 | 69.12 | yes | Moabb, Torcheeg |
| [BNCI2014 002]() | 2014 | Motor Imagery | 2 | 14.0 | 15.0 | 512.0 | 24.89 | yes | Moabb |
| [BNCI2014 004]() | 2014 | Motor Imagery | 2 | 9.0 | 3.0 | 250.0 | 40.5 | yes | Moabb |
| [Grasp and Lift EEG Challenge](https://www.nature.com/articles/sdata201447) | 2014 | Motor Imagery |  | 12.0 | 32.0 | 500.0 | 11.72 | yes |  |
| [Weibo2014](https://doi.org/10.1371/journal.pone.0114853) | 2014 | Motor Imagery | 7 | 10.0 | 60.0 | 200.0 | 6.22 | yes | Moabb |
| [AlexMotor Imagery](https://theses.hal.science/tel-01196752/) | 2012 | Motor Imagery | 3 | 8.0 | 16.0 | 512.0 | 0.24 | yes | Moabb |
| [GrosseWentrup2009](https://doi.org/10.1109/TBME.2008.2009768) | 2009 | Motor Imagery | 2 | 10.0 | 128.0 | 500.0 | 5.83 | yes | Moabb |
| [EEG Motor Movement/Imagery Dataset](https://doi.org/10.1109/TBME.2004.827072) | 2004 | Motor Imagery | 4 | 109.0 | 64.0 | 160.0 | 58.13 | yes | Moabb |


### Emotion Recognition
Emotion recognition is the task of identifying and classifying human emotions from physiological or behavioral signals, such as EEG, facial expressions, or speech.

| Dataset | Year | Task | #Classes | #Subjects | #Channels | Freq (Hz) | TotalTime (h) | LabSetting |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [SEED-VII](https://bcmi.sjtu.edu.cn/~seed/seed-vii.html) | 2024 | ER | Discrete | 20 | 62.0 | 1000.0 | 313.2 | yes |
| [FACED](https://doi.org/10.7303/syn50614194) | 2023 | ER | V/A | 55 | 32.0 | 250.0 | 787.45 | yes |
| [FACED](https://doi.org/10.7303/syn50614194) | 2023 | ER | V/A | 68 | 32.0 | 1000.0 | 973.57 | yes |
| [Imagined Emotion Study](https://openneuro.org/datasets/ds003004/versions/1.1.1) | 2023 | ER | Discrete | 34 | 199.0 | 128.0 |  | yes |
| [MAET Dataset](https://doi.org/10.1145/3581783.3613797) | 2023 | ER | V/A | 20 | 62.0 | 1000.0 | 78.32 | yes |
| [Response to Oil Paintings](https://doi.org/10.1109/EMBC48229.2022.9871630) | 2022 | ER | V/A | 22 | 62.0 | 1000.0 | 11 | yes |
| [BCI2022]() | 2022 | ER | Discrete | 80 | 30.0 | 250.0 |  |  |
| [SEED-V](https://bcmi.sjtu.edu.cn/~seed/seed-v.html) | 2021 | ER | Discrete | 20 | 62.0 | 200.0 | 50 | yes |
| [IAPS](https://dx.doi.org/10.21227/haar-1q96) | 2020 | ER | Genuine/Acted | 28 | 64.0 | 500.0 | 53.3 | yes |
| [SAFE](https://doi.org/10.1016/j.aei.2020.101047) | 2020 | ER | V/A | 6 | 14.0 | 128.0 | 8.1 | yes |
| [SEED-IV](https://bcmi.sjtu.edu.cn/~seed/seed-iv.html) | 2019 | ER | Discrete | 15 | 62.0 | 200.0 | 51 | yes |
| [MPED](https://doi.org/10.1109/ACCESS.2019.2891579) | 2019 | ER | V/A | 23 | 62.0 | 1000.0 | 41.93 | yes |
| [AMIGOS](http://www.eecs.qmul.ac.uk/mmv/datasets/amigos/index.html) | 2018 | ER | V/A | 40 | 14.0 | 128.0 | 1.9 | yes |
| [DREAMER](https://doi.org/10.1109/JBHI.2017.2688239) | 2017 | ER | V/A | 23 | 14.0 | 128.0 | 6.9 | yes |
| [Neuromarketing](https://doi.org/10.1007/s11042-017-4580-6) | 2017 | ER | Discrete | 25 | 14.0 | 128.0 | 1.16 | yes |
| [SEED](https://bcmi.sjtu.edu.cn/~seed/index.html) | 2015 | ER | Discrete | 15 | 62.0 | 200.0 | 12 | yes |
| [MANHOB](https://doi.org/10.1109/T-AFFC.2011.25) | 2012 | ER | V/A - agreement | 27 | 32.0 | 256.0 | 138.6 | yes |
| [DEAP](https://www.eecs.qmul.ac.uk/mmv/datasets/deap/) | 2011 | ER | V/A | 32 | 32.0 | 512.0 | 21 | yes |
| [Emobrain](https://www.isca-archive.org/einterface_2006/savran06_einterface.html) | 2006 | ER | V/A | 16 | 64.0 | 1024.0 | 4.94 | yes |





### Brain-to-text
Brain-to-text is the process of decoding neural signals, such as EEG or ECoG, to translate brain activity into written or spoken language. It enables direct communication by mapping brain patterns to text, often using machine learning and neural decoding techniques.

| Dataset | Year | Task | #Subjects | #Channels | Freq (Hz) | TotalTime (h) | LabSetting | 
| --- | --- | --- | --- | --- | --- | --- | --- | 
| [Thinking out loud](https://www.nature.com/articles/s41597-022-01147-2) | 2022 | EEG2T | 22 | 128 | 256 | 423.0 | yes | 
| [Bren and Hale](https://doi.org/10.1371/journal.pone.0207741) | 2019 | EEG2T | 49 | 61 | 500 | 9.8 | yes | 
| [ZuCo v1.0 and v2.0](https://doi.org/10.1038/sdata.2018.291) | 2018 | EEG2T | 12 | 21 | 500 | 25.0 | yes | 
| [Frank et al. ](https://doi.org/10.1016/j.bandl.2014.10.006) | 2015 | EEG2T | 24 | 32 | 250 | 36.0 | yes | 


### Neurodegenerative diseases
Detection of neurodegenerative diseases involves identifying biomarkers and patterns of neural deterioration using methods like neuroimaging (MRI, PET), electrophysiology (EEG, MEG), fluid biomarkers (CSF, blood), and cognitive assessments. Machine learning and AI are increasingly used to analyze these data for early diagnosis and progression tracking.

| Dataset | Year | Task | #Classes | #Subjects | #Channels | Freq (Hz) | TotalTime (h) | LabSetting | #Recordings |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [Falaschetti2024](https://doi.org/10.3390/s24206721) | 2024 | Dementia | 6 | 97 | 16 | 128 | 35.39 | yes | 97 |
| [Miltiadous (ADFD)](http://doi.org/10.3390/data8060095) | 2023 | Dementia | 3 | 88 | 19 | 500 | 19.4 | yes | 88 |
| [CAUEEG](https://doi.org/10.1016/j.neuroimage.2023.120054) | 2023 | Abnormality and Dementia | 2 (abnormality) or 3 (dementia) | 1155 (abnormality) | 19 | 200 | 306.59 | yes | 1379 (abnormality) or 1189 (dementia) |
| [Alessandrini2023](https://doi.org/10.1109/SSP53291.2023.10208023) | 2023 | Dementia (AD, FTD) | 4 | 68 | 16 | 128 | 25.29 | yes | 68 |
| [BrainLat (EEG-only portion)](https://doi.org/10.1038/s41597-023-02806-8) | 2023 | AD, bvFTD, PD, MS, HC | 5 | 157 | 128 | 512 | 235.5 |  |  |
| [ADSZ (AD)](http://doi.org/10.1088/2632-072X/ac5f8d) | 2022 | Dementia (Alzheimer's) | 2 | 48 | 19 | 128 | 0.10 | yes | 48? |
| [NMT Scalp EEG](https://doi.org/10.3389/fnins.2021.755817) | 2022 | Abnormality | 2 | 2417 | 19 | 200 | 625.0 | yes | 2417 |
| [Alessandrini](https://doi.org/10.3390/s22103696) | 2022 | Dementia (Alzheimer's) | 2 | 35 | 16 | 128 | 12.92 | yes | 35 |
| [ADSZ (SZ)](http://doi.org/10.1088/2632-072X/ac5f8d) | 2022 | Schizophrenia | 2 | 84 | 16 | 128 | 1.4 | yes | 84? |
| [Cejnek2021](https://doi.org/10.1007/s11517-021-02427-6) | 2021 | Dementia | 3 | 168 | 21 | 128 | 42.0 |  |  |
| [UC San Diego Resting State EEG Data from Patients with Parkinson's Disease](https://doi.org/10.18112/openneuro.ds002778.v1.0.5) | 2020 | Parkinson's | 2025-03-02 00:00:00 | 31 | 32 | 512 | 2.42 | yes | 46 |
| [Lower-limb pedaling](https://doi.org/10.1016/j.clinph.2019.12.399) | 2020 | Parkinson's | 2025-03-02 00:00:00 | 39 | 64 | 500 |  |  |  |
| [University of Iowa](https://doi.org/10.1016/j.parkreldis.2020.08.001) | 2020 | Parkinson's | 2 | 28 | 64 | 500 |  |  |  |
| [Ieracitano2020](https://doi.org/10.1016/j.neunet.2019.12.006) | 2020 | Dementia | 3 | 189 | 19 | 1024 |  |  |  |
| [catch 22" right now - in order for the GP agent to get the new setting it needs to connect to GP portal, but it ca]() | 2020 | Parkinson's | 2 | 54 | 64 | 500 |  |  |  |
| [Durongbhan](https://doi.org/10.1109/TNSRE.2019.2909100) | 2019 | Dementia (Alzheimer's) | 2 | 40 | 128 | 2000 | 0.26 | yes |  |
| [Hospital Universiti Kebangsaan Malaysia]() | 2018 | Parkinson's | 2 | 40 | 14 | 128 | 3.33 |  | 40 |
| [AFAVA (nome di ADformer: APAVA)](https://doi.org/10.1088/0967-3334/27/11/004) | 2006 | Dementia (Alzheimer's) | 2 | 22 | 19 (16?) | 256 | 0.91 | yes |  |
| [noname]() | 1996 | Dementia | 2025-03-02 00:00:00 | 15 | 9 | 256 | 1.0 |  |  |


### Seizure Prediction
Seizure prediction involves analyzing brain activity, typically from EEG, to detect patterns that precede epileptic seizures. Machine learning models and signal processing techniques identify preictal states, enabling early warnings and potential intervention to prevent or mitigate seizures.

| Dataset | Year | Task | #Classes | #Subjects | #Channels | Freq (Hz) | TotalTime (h) | LabSetting |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [TUAR](https://doi.org/10.1109/SPMB52430.2021.9672302) | 2021 | SP | 5.0 | 14 | 23 | 256 | 92.22 |  |
| [Siena Scalp EEG Database](https://doi.org/10.3390/pr8070846) | 2020 | SP |  | 14 | 31 | 512 | 30.47 |  |
| [NICU](https://doi.org/10.1038/sdata.2019.39) | 2019 | SP |  | 79 | 19 | 256 | 79.0 |  |
| [Helsinki University Hospital EEG](https://doi.org/10.1038/sdata.2019.39) | 2019 | SP |  | 79 | 19 | 256 | 97.43 | scalp |
| [Neurology and Sleep  Centre Hauz Khas](https://doi.org/10.1109/TNSRE.2018.2818123) | 2018 | SP |  | 10 | 1 | 200 | 0.14 | scalp |
| [TUSZ](https://doi.org/10.3389/fninf.2018.00083) | 2018 | SP |  | 315 | 19 | 256 | 1138.53 |  |
| [TUEP](https://doi.org/10.1109/SPMB.2017.8257044) | 2017 | SP |  | 100 | 19 | 256 | 591.22 |  |
| [TUSL](https://doi.org/10.1109/SPMB.2017.8257018) | 2017 | SP |  | 112 | 23 | 256 | 20.59 |  |
| [Kaggle American Epilepsy  Society Seizure Prediction Challenge](https://doi.org/10.1093/brain/aww045) | 2016 | SP |  | 3 | 16 | 400 | 841.16 | intracranial |
| [EEG sample data](http://dx.doi.org/10.13140/RG.2.2.14280.32006) | 2016 | SP |  | 10 | 21 | 200 | 0.22 |  |
| [Kaggle American Epilepsy  Society Seizure Prediction Challenge](https://doi.org/10.1093/brain/aww045) | 2016 | SP |  | 4 | 16 | 5000 | 841.16 | intracranial |
| [UPenn and Mayo Clinic's  Seizure Detection Challenge ](https://www.kaggle.com/c/seizure-detection/overview) | 2014 | SP |  | 8 | 16 | 5000 | 16.55 | intracranial |
| [UPenn and Mayo Clinic's  Seizure Detection Challenge ](https://www.kaggle.com/c/seizure-detection/overview) | 2014 | SP |  | 4 | 16 | 400 | 16.55 | intracranial |
| [Neuro Vista Ictal](https://doi.org/10.1016/S1474-4422(13)70075-9) | 2013 | SP |  | 12 | 16 | 400 | 88.54 | intracranial |
| [CHB-MIT scalp EEG database](https://doi.org/10.13026/C2K01R) | 2010 | SP |  | 22 | 23 | 256 | 916.0 |  |
| [University of Bonn](https://doi.org/10.1103/PhysRevE.64.061907) | 2001 | SP |  | 10 | 1 | 174 | 3.27 | scalp / intracranial |


### Brain-to-image
Brain-to-image is the process of reconstructing visual perceptions or mental imagery from brain activity using techniques like fMRI, EEG, or MEG. Machine learning models, including deep neural networks, map neural signals to visual representations, enabling applications in neuroscience, BCI, and artificial vision.

| Dataset | Year | Task | #Subjects | #Channels | Freq (Hz) | TotalTime (?) | LabSetting |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [Image classification and reconstruction from low-density EEG](https://doi.org/10.1038/s41598-024-66228-1) | 2024 | Brain-to-image | 9 | 8 | 250 | 54.0 | yes |
| [EEG-ImageNet](https://arxiv.org/abs/2406.07151) | 2024 | Brain-to-image | 16 | 62 | 1000 | 8.86 | yes |
| [Alljoined1](https://arxiv.org/abs/2404.05553) | 2024 | Brain-to-image | 8 | 64 | 512 | 61.01 | yes |
| [A large and rich EEG dataset for modeling human visual object recognition](https://doi.org/10.1016/j.neuroimage.2022.119754) | 2022 | Brain-to-image | 10 | 64 | 1000 | 63.0 | yes |
| [THINGS-EEG](https://doi.org/10.1038/s41597-021-01102-7) | 2021 | Brain-to-image | 50 | 64 | 1000 | 36.05 | yes |
| [Object classification from randomized EEG trials](https://doi.org/10.1109/CVPR46437.2021.00384) | 2021 | Brain-to-image | 1 | 96 | 4096 | 33.88 | yes |
| [Reading into the mind�s eye](https://doi.org/10.1016/j.neucom.2019.12.076) | 2019 | Brain-to-image | 6 | 14 | 2048 | 4.0 | yes |
| [The representational dynamics of visual objects in rapid serial visual processing streams](https://doi.org/10.1016/j.neuroimage.2018.12.046) | 2019 | Brain-to-image | 16 | 64 | 1000 | 13.33 | yes |
| [The set of 22 sessions of 14-channel eeg signals recorded during watching pictures](https://doi.org/10.34808/1e5c-pp74) | 2018 | Brain-to-image | 10 | 14 |  | 338.0 | yes |
| [IMAGENET of The Brain](https://mindbigdata.com/opendb/imagenet.html) | 2018 | Brain-to-image | 1 | 5 | 128 | 58.38 | yes |
| [Envisioned speech recognition using EEG sensors](https://doi.org/10.1007/s00779-017-1083-4) | 2017 | Brain-to-image | 23 | 14 | 128 | 3.83 | yes |
| [Brain2Image](https://doi.org/10.1145/3123266.3127907) | 2017 | Brain-to-image | 6 | 128 | 1000 | 2.3 | yes |
| [Multivariate pattern analysis of MEG and EEG: A comparison of representational structure in time and space](https://doi.org/10.1016/j.neuroimage.2017.07.023) | 2017 | Brain-to-image | 16 | 74 | 1000 | 19.33 | yes |
| [A Representational Similarity Analysis of the Dynamics of Object Processing Using Single-Trial EEG Classification](https://doi.org/10.1371/journal.pone.0135697) | 2015 | Brain-to-image | 10 | 128 | 1000 | 18.0 | yes |
| ["MNIST" of Brain Digits](https://mindbigdata.com/opendb/index.html) | 2015 | Brain-to-image | 1 | vari | 128 - 512 | 670.0 | yes |


### Other
This section includes a variety of tasks.

| Dataset | Year | Task | #Subjects | #Channels | Freq (Hz) | TotalTime (?) | LabSetting | Available in |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [BOAS](https://doi.org/10.18112/openneuro.ds005555.v1.0.0) | 2024 | Sleep stages | 128 | 2 | 256 | 1024 | no |  |
| [The slowest wave](https://link.springer.com/article/10.1186/s12868-024-00864-1) | 2023 | Dance | 5 | 28 | 1000 | > 26 | no |  |
| [A test-retest resting and cognitive state](https://www.nature.com/articles/s41597-022-01607-9) | 2022 | Test-retest | 60 | 64 | 500 | 75 | yes |  |
| [HMCDataset](https://doi.org/10.1371/journal.pone.0256111) | 2022 | Sleep stages | 151 | 8 | 256 | 1057 | no | torcheeg |
| [SPIS Resting State](https://doi.org/10.1109/JBHI.2020.2980056) | 2020 | Sustained attention | 10 | 64 | 2048 | 0.83 | yes |  |
| [Target Versus Non-Target](https://hal.science/hal-02172347) | 2019 | P300 BCI | 50 | 32 | 512 | 16 | yes |  |
| [P2018Dataset](https://doi.org/10.22489/CinC.2018.049) | 2018 | Sleep stages | 1985 | 6 | 200 | 13895 | no | torcheeg |
| [Resting State EEG Data](https://doi.org/10.3389/fnins.2017.00425) | 2017 | No task | 22 | 64 | 256 | 3.04 | yes |  |
| [A Benchmark Dataset for SSVEP-Based Brain-Computer Interfaces](https://doi.org/10.1109/TNSRE.2016.2627556) | 2017 | SSVEP | 35 | 64 | 250 | 11.6 | yes | torcheeg |
| [ISRUCDataset](https://doi.org/10.1016/j.cmpb.2015.10.013) | 2016 | Sleep stages | 118 | 19 | 200 | 1008 | no | torcheeg |
| [SanDiegoSSVEPDataset](https://doi.org/10.1371/journal.pone.0140703) | 2015 | SSVEP | 10 | 8 | 256 | 2 | yes | torcheeg |
| [SleepEDFxDataset](https://doi.org/10.1109/10.867928) | 2000 | Sleep stages | 197 | 2 | 100 | 1379 | no | torcheeg |




Feel free to suggest additional datasets or update this table via a pull request!
---


## Software tools

- **Braindecode**: (https://braindecode.org/stable/index.html) Braindecode is an open-source Python toolbox for decoding raw electrophysiological brain data with deep learning models. It includes dataset fetchers, data preprocessing and visualization tools, as well as implementations of several deep learning architectures and data augmentations for analysis of EEG, ECoG and MEG.
- **PyEDFlib**: (https://pyedflib.readthedocs.io/en/latest/) PyEDFlib is a Python library to read/write EDF/EDF+/BDF files based on EDFlib. The PyEDFlib Python toolbox is a fork of the python-edf toolbox from Christopher Lee-Messer. and uses the EDFlib from Teunis van Beelen.
- **MNE-Python**: (https://mne.tools/stable/index.html) MNE-Python is an open-source Python package for exploring, visualizing, and analyzing human neurophysiological data such as MEG, EEG, sEEG, ECoG, and more. It includes modules for data input/output, preprocessing, visualization, source estimation, time-frequency analysis, connectivity analysis, machine learning, statistics, and more.
- **TorchEEG**: (https://torcheeg.readthedocs.io/en/latest/) TorchEEG is a library built on PyTorch for EEG signal analysis. TorchEEG aims to provide a plug-and-play EEG analysis tool, so that researchers can quickly reproduce EEG analysis work and start new EEG analysis research without paying attention to technical details unrelated to the research focus. TorchEEG specifies a unified data input-output format (IO) and implement commonly used EEG databases, allowing users to quickly access benchmark datasets and define new custom datasets. The datasets that have been defined so far include emotion recognition and so on.
- **EEGLAB**: (https://sccn.ucsd.edu/eeglab/) EEGLAB is an interactive Matlab toolbox for processing continuous and event-related EEG, MEG and other electrophysiological data incorporating independent component analysis (ICA), time/frequency analysis, artifact rejection, event-related statistics, and several useful modes of visualization of the averaged and single-trial data. EEGLAB runs under Linux, Unix, Windows, and Mac OS X.
- **MetaBCI**: (https://github.com/TBC-TJU/MetaBCI) MetaBCI is an open-source platform for non-invasive brain computer interface. The project of MetaBCI is led by Prof. Minpeng Xu from Tianjin University, China. MetaBCI has 3 main parts: 1) brainda: for importing dataset, pre-processing EEG data and implementing EEG decoding algorithms; 2) brainflow: a high speed EEG online data processing framework; 3) brainstim: a simple and efficient BCI experiment paradigms design module.
- **MOABB Mother of all BCI Benchmarks**: (https://moabb.neurotechx.com/docs/index.html) MOABB is an open-source Python framework designed to facilitate **reproducible research** in Brain-Computer Interfaces (BCI), specifically for EEG-based decoding. It provides a standardized environment for benchmarking machine learning algorithms on publicly available EEG datasets. MOABB includes a variety of EEG datasets, eliminating the need for manual data collection, and ensures fair comparison between different decoding algorithms through standardized pipelines. It simplifies EEG data handling using MNE-Python and provides reliable performance comparisons under the same experimental conditions. MOABB is a powerful tool for researchers and developers working on EEG decoding and BCI applications.
- **EEGUnity**: (https://github.com/Baizhige/EEGUnity) is an open-source tool designed to streamline the management and processing of multiple EEG datasets. It features modular components, including the **EEG Parser**, **Correction**, **Batch Processing**, and **Large Language Model Boost**, enabling intelligent data structure inference, automated cleaning, and seamless unification of EEG data. By ensuring high data quality and consistency, EEGUnity provides a robust foundation for large-scale EEG research and analysis.
## 🤝 Contributing

Contributions are welcome to help expand and maintain this repository!  
Here’s how you can contribute:

- Add new resources or suggest improvements.
- Report broken links or outdated content.
- Submit pull requests with tutorials, datasets, or tools.

Please follow the contribution guidelines in the [CONTRIBUTING.md](CONTRIBUTING.md) file.

---

## 📜 License

This repository is licensed under the [MIT License](LICENSE).

---

## 📬 Feedback & Contact

Have suggestions, feedback, or found a broken link?  
Feel free to [open an issue](https://github.com/your-repo/issues) or reach out via email at [paolo.napoletano@unimib.it](mailto:paolo.napoletano@unimib.it).

---

## 🤝 Acknowledgments

Special thanks to the open-source community and researchers who made these resources possible.
