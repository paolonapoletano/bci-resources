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

Below is a table summarizing key datasets for BCI research. Each dataset includes details like the number of subjects, recording devices, sampling rate, and specific tasks.

| Dataset Name                           | Year | Subjects | Device                | Task Type                | Sampling Rate | Additional Info                                      |
|---------------------------------------|----------|----------|-----------------------|--------------------------|---------------|----------------------------------------------------|
| [BCI Competition Datasets](http://www.bbci.de/competition/) |2003 | Varies   | Various               | Motor Imagery, P300     | Varies        | Includes multiple competition datasets.            |
| [OpenBCI Sample Data](https://openbci.com/data-sharing/) |2003 | Varies   | OpenBCI               | Various BCI tasks       | 125-250 Hz    | Ideal for hardware experimentation.                |
| [PhysioNet EEG Motor Imagery Dataset](https://physionet.org/content/eegmmidb/1.0.0/) |2003 | 109      | BCI2000 System        | Motor Imagery           | 160 Hz        | Designed for machine learning experiments.         |
| [TUH EEG Corpus](https://www.isip.piconepress.com/projects/tuh_eeg/html/downloads.shtml) |2003 | Thousands| Various               | Clinical (e.g., seizures)| Varies        | Largest open-source EEG dataset.                   |
| [SEED Dataset](http://bcmi.sjtu.edu.cn/~seed/) |2003 | 15       | ESI NeuroScan         | Emotion Recognition     | 1000 Hz       | Focuses on EEG-based emotion recognition.          |
| [WAUC: A Multi-Modal Database for Mental Workload Assessment Under Physical Activity](https://www.frontiersin.org/journals/neuroscience/articles/10.3389/fnins.2020.549524/full) | 2020 | 48 | Enobio portable 8-channel wireless EEG headset | Mental and physical induced perceived stress | 500 Hz | |
| [PASS: A Multimodal Database of Physical Activity and Stress for Mobile Passive Body/ Brain-Computer Interface Research](https://www.frontiersin.org/journals/neuroscience/articles/10.3389/fnins.2020.542934/full) | 2020 | 48 | Muse headband | Mental and physical induced perceived stress | 220 Hz | | 
| [SAM 40: Dataset of 40 subject EEG recordings to monitor the induced-stress while performing Stroop color-word test, arithmetic task, and mirror image recognition task](https://www.sciencedirect.com/science/article/pii/S2352340921010465) | 2022 | 40 | Emotiv Epoc Flex gel kit | Mental induced perceived stress | 128 Hz | |
| [A Dataset of Scalp EEG Recordings of Alzheimer’s Disease, Frontotemporal Dementia and Healthy Subjects from Routine EEG](https://www.mdpi.com/2306-5729/8/6/95) | 2023 | 88 | Nihon Kohden 2100 | Clinical (Alzheimer, Frontotemporal dementia, Control) | 500 Hz | Raw and pre-processed data available |


Feel free to suggest additional datasets or update this table via a pull request!

---

## 📊 Datasets new
| Dataset | Year | Task |#Classes | #Subjects | #Channels | Freq (Hz) | TotalTime (h) | LabSetting | Available in |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [A continuous pursuit dataset for online deep learning-based EEG brain-computer interface](https://doi.org/10.1038/s41597-024-04090-6) | 2024 | Motor Imagery | - | 28 | 64 | 1000 | 168.0 | yes | - |
| [Liu2024](https://doi.org/10.6084/m9.figshare.21679035.v5) | 2024 | Motor Imagery | 2 | 50 | 29 | 500 | 2.22 | yes | Moabb |
| [Stieger2021](https://doi.org/10.1038/s41597-021-00883-1) | 2021 | Motor Imagery | 4 | 62 | 64 | 1000 | 208.33 | yes | Moabb |
| [Lee2019_Motor Imagery](https://doi.org/10.1093/gigascience/giz002) | 2019 | Motor Imagery | 2 | 54 | 62 | 1000 | 12.22 | yes | Moabb |
| [The largest SCP data of Motor-Imagery](https://doi.org/10.6084/m9.figshare.c.3917698) | 2018 | Motor Imagery |  | 13 | 19 | 1000 | 60.0 | yes | - |
| [CHO2017](https://doi.org/10.1093/gigascience/gix034) | 2017 | Motor Imagery | 2 | 52 | 64 | 512 | 8.17 | yes | Moabb |
| [High-Gamma Dataset](https://github.com/robintibor/high-gamma-dataset) | 2017 | Motor Imagery | 4 | 14 | 128 | 250 | 67.0 |  |  |
| [Left/Right Hand Motor Imagery](http://gigadb.org/dataset/100295) | 2017 | Motor Imagery | 2 | 52 | 64 | 512 | 109.2 | yes | - |
| [Ofner2017](https://doi.org/10.1371/journal.pone.0182578) | 2017 | Motor Imagery | 7 | 15 | 61 | 512 | 52.5 | yes | Moabb |
| [Schirrmeister2017](https://doi.org/10.1002/hbm.23730) | 2017 | Motor Imagery | 4 | 14 | 128 | 500 | 14.93 | yes | Moabb |
| [Shin2017A-B](https://doi.org/10.1109/TNSRE.2016.2628057) | 2017 | Motor Imagery | 2 | 29 | 30 | 200 | 14.5 | yes | Moabb |
| [Zhou2016](https://doi.org/10.1371/journal.pone.0162657) | 2016 | Motor Imagery | 3 | 4 | 14 | 200 | 15.97 | yes | Moabb |
| [BNCI2015 001]() | 2015 | Motor Imagery | 2 | 12 | 13 | 512 | 20.0 | yes | Moabb |
| [BNCI2015 004]() | 2015 | Motor Imagery | 5 | 9 | 30 | 256 | 14.0 | yes | Moabb |
| [BNCI2014 001]() | 2014 | Motor Imagery | 4 | 9 | 22 | 250 | 69.12 | yes | Moabb, Torcheeg |
| [BNCI2014 002]() | 2014 | Motor Imagery | 2 | 14 | 15 | 512 | 24.89 | yes | Moabb |
| [BNCI2014 004]() | 2014 | Motor Imagery | 2 | 9 | 3 | 250 | 40.5 | yes | Moabb |
| [Grasp and Lift EEG Challenge](https://www.nature.com/articles/sdata201447) | 2014 | Motor Imagery |  | 12 | 32 | 500 | 11.72 | yes | - |
| [Weibo2014](https://doi.org/10.1371/journal.pone.0114853) | 2014 | Motor Imagery | 7 | 10 | 60 | 200 | 6.22 | yes | Moabb |
| [AlexMotor Imagery](https://theses.hal.science/tel-01196752/) | 2012 | Motor Imagery | 3 | 8 | 16 | 512 | 0.24 | yes | Moabb |
| [GrosseWentrup2009](https://doi.org/10.1109/TBME.2008.2009768) | 2009 | Motor Imagery | 2 | 10 | 128 | 500 | 5.83 | yes | Moabb |
| [EEG Motor Movement/Imagery Dataset](https://doi.org/10.1109/TBME.2004.827072) | 2004 | Motor Imagery | 4 | 109 | 64 | 160 | 58.13 | yes | Moabb |
| [ZuCo v1.0 and v2.0](https://doi.org/10.1038/sdata.2018.291) | 2018 | Brain to Text |  | 12 | 21 | 500 | 25.0 | yes | - |
| [Frank et al. ](https://doi.org/10.1016/j.bandl.2014.10.006) | 2015 | Brain to Text |  | 24 | 32 | 250 | 36.0 | yes | link |
| [Bren and Hale](https://doi.org/10.1371/journal.pone.0207741) | 2019 | Brain to Text |  | 49 | 61 | 500 | 9.8 | yes | link |
| [Thinking out loud](https://www.nature.com/articles/s41597-022-01147-2#MOESM1) | 2022 | Brain to Text |  | 22 | 128 | 256 | 423.0 | yes |  |
| [Emobrain](https://www.isca-archive.org/einterface_2006/savran06_einterface.html) | 2006 | Emotion Recognition | V/A | 16 | 64 | 1024 | 4.94 | yes |  |
| [Dreamer ](https://doi.org/10.1109/JBHI.2017.2688239) | 2018 | Emotion Recognition | V/A | 23 | 16 | 128 | 6.9 | yes |  |
| [FACED](https://doi.org/10.7303/syn50614194) | 2023 | Emotion Recognition | V/A | 55 | 32 | 250 | 787.4533333 | yes |  |
| [FACED](https://doi.org/10.7303/syn50614194) | 2023 | Emotion Recognition | V/A | 68 | 32 | 1000 | 973.5786667 |  |  |
| [SAFE](https://doi.org/10.1016/j.aei.2020.101047) | 2020 | Emotion Recognition | V/A | 6 | 14 | 128 | 8.1 | yes |  |
| [DEAP](https://www.eecs.qmul.ac.uk/mmv/datasets/deap/) | 2011 | Emotion Recognition | V/A | 32 | 32 | 512 | 21.0 | yes |  |
| [MANHOB](https://doi.org/10.1109/T-AFFC.2011.25) | 2012 | Emotion Recognition | V/A - agreement | 27 | 32 | 256 | 138.6 | yes |  |
| [SEED](https://bcmi.sjtu.edu.cn/~seed/index.html) | 2015 | Emotion Recognition |  | 15 | 62 | 200 | 12.0 |  |  |
| [SEED-IV]() | 2019 | Emotion Recognition |  | 15 | 62 | 200 | 51.0 |  |  |
| [SEED-V]() | 2021 | Emotion Recognition |  | 20 | 62 | 200 | 50.0 |  |  |
| [SEED-VII]() | 2024 | Emotion Recognition |  | 20 | 62 | 1000 | 313.2 |  |  |
| [Response to Oil Paintings](https://doi.org/10.1109/EMBC48229.2022.9871630) | 2022 | Emotion Recognition | V/A | 22 | 62 | 1000 | 11.0 | yes |  |
| [MAET Dataset](https://doi.org/10.1145/3581783.3613797) | 2023 | Emotion Recognition | V/A | 20 | 62 | 1000 | 78.32 | yes |  |
| [IAPS](https://dx.doi.org/10.21227/haar-1q96) | 2020 | Emotion Recognition |  | 28 | 64 | 500 | 53.3 |  |  |
| [AMIGOS](http://www.eecs.qmul.ac.uk/mmv/datasets/amigos/index.html) | 2018 | Emotion Recognition |  | 40 | 14 | 128 | 1.9 |  |  |
| [MPED](https://doi.org/10.1109/ACCESS.2019.2891579) | 2019 | Emotion Recognition |  | 23 | 62 | 1000 | 41.93 |  |  |
| [DREAMER](https://doi.org/10.1109/JBHI.2017.2688239) | 2017 | Emotion Recognition |  | 23 | 14 | 128 | 6.9 |  |  |
| [CAUEEG](https://doi.org/10.1016/j.neuroimage.2023.120054) | 2023 | Neurodegenerative Disease | 2 (abnormality) or 3 (dementia) | 1155 | 19 | 200 | 306.5976667 |  |  |
| [Miltiadous (ADFD)](http://doi.org/10.3390/data8060095) | 2023 | Neurodegenerative Disease | 3 | 88 | 19 | 500 | 19.4 |  |  |
| [ADSZ (AD)](http://doi.org/10.1088/2632-072X/ac5f8d) | 2022 | Neurodegenerative Disease | 2 | 48 | 19 | 128 | 0.1066666667 |  |  |
| [ADSZ (SZ)](http://doi.org/10.1088/2632-072X/ac5f8d) | 2022 | Neurodegenerative Disease | 2 | 84 | 16 | 128 | 1.4 |  |  |
| [APAVA](https://doi.org/10.1088/0967-3334/27/11/004) | 2006 | Neurodegenerative Disease | 2 | 22 | 19 | 256 | 0.92 |  |  |
| [Alessandrini](https://doi.org/10.3390/s22103696) | 2022 | Neurodegenerative Disease | 2 | 35 | 16 | 128 | 12.92166667 | yes |  |
| [NMT Scalp EEG](https://doi.org/10.3389/fnins.2021.755817) | 2022 | Neurodegenerative Disease | 2 | 2417 | 19 | 200 | 625.0 | yes |  |
| [Siena Scalp EEG Database](https://doi.org/10.3390/pr8070846) | 2020 | Seizure Prediction |  | 14 | 31 | 512 | 30.47 |  |  |
| [TUAR](https://doi.org/10.1109/SPMB52430.2021.9672302) | 2021 | Seizure Prediction | 5 | 14 | 23 | 256 | 92.22 |  |  |
| [TUEP](https://doi.org/10.1109/SPMB.2017.8257044) | 2017 | Seizure Prediction |  | 100 | 19 | 256 | 591.22 |  |  |
| [TUSZ](https://doi.org/10.3389/fninf.2018.00083) | 2018 | Seizure Prediction |  | 315 | 19 | 256 | 1138.53 |  |  |
| [TUSL](https://doi.org/10.1109/SPMB.2017.8257018) | 2017 | Seizure Prediction |  | 112 | 23 | 256 | 20.59 |  |  |
| [NICU](https://doi.org/10.1038/sdata.2019.39) | 2019 | Seizure Prediction |  | 79 | 19 | 256 | 79.0 |  |  |
| [EEG sample data](http://dx.doi.org/10.13140/RG.2.2.14280.32006) | 2016 | Seizure Prediction |  | 10 | 21 | 200 | 0.22 |  |  |
| [CHB-MIT scalp EEG database](https://doi.org/10.13026/C2K01R) | 2010 | Seizure Prediction |  | 22 | 23 | 256 | 916.0 |  |  |
| [University of Bonn](https://doi.org/10.1103/PhysRevE.64.061907) | 2001 | Seizure Prediction |  | 10 | 1 | 174 | 3.277777778 | scalp / intracranial |  |
| [Neurology and Sleep Centre Hauz Khas](https://doi.org/10.1109/TNSRE.2018.2818123) | 2018 | Seizure Prediction |  | 10 | 1 | 200 | 0.1422222222 | scalp |  |
| [Helsinki University Hospital EEG](https://doi.org/10.1038/sdata.2019.39) | 2019 | Seizure Prediction |  | 79 | 19 | 256 | 97.43333333 | scalp |  |
| [A large and rich EEG dataset for modeling human visual object recognition](https://doi.org/10.1016/j.neuroimage.2022.119754) | 2022 | Brain to Image |  | 10 | 64 | 1000 | 63.0 | yes |  |
| [Envisioned speech recognition using EEG sensors](https://doi.org/10.1007/s00779-017-1083-4) | 2017 | Brain to Image |  | 23 | 14 | 128 | 3.83 | yes |  |
| [Brain2Image](https://doi.org/10.1145/3123266.3127907) | 2017 | Brain to Image |  | 6 | 128 | 1000 | 2.3 | yes |  |
| [Image classification and reconstruction from low-density EEG](https://doi.org/10.1038/s41598-024-66228-1) | 2024 | Brain to Image |  | 9 | 8 | 250 | 54.0 | yes |  |
| [EEG-ImageNet](https://arxiv.org/abs/2406.07151) | 2024 | Brain to Image |  | 16 | 62 | 1000 | 8.86 | yes |  |
| [Alljoined1](https://arxiv.org/abs/2404.05553) | 2024 | Brain to Image |  | 8 | 64 | 512 | 61.01 | yes |  |
| [THINGS-EEG](https://doi.org/10.1038/s41597-021-01102-7) | 2021 | Brain to Image |  | 50 | 64 | 1000 | 36.05 | yes |  |
| [A Representational Similarity Analysis of the Dynamics of Object Processing Using Single-Trial EEG Classification](https://doi.org/10.1371/journal.pone.0135697) | 2015 | Brain to Image |  | 10 | 128 | 1000 | 18.0 | yes |  |
| [Multivariate pattern analysis of MEG and EEG: A comparison of representational structure in time and space](https://doi.org/10.1016/j.neuroimage.2017.07.023) | 2017 | Brain to Image |  | 16 | 74 | 1000 | 19.33 | yes |  |



## Software tools

- **Braindecode**: (https://braindecode.org/stable/index.html) Braindecode is an open-source Python toolbox for decoding raw electrophysiological brain data with deep learning models. It includes dataset fetchers, data preprocessing and visualization tools, as well as implementations of several deep learning architectures and data augmentations for analysis of EEG, ECoG and MEG.
- **PyEDFlib**: (https://pyedflib.readthedocs.io/en/latest/) PyEDFlib is a Python library to read/write EDF/EDF+/BDF files based on EDFlib. The PyEDFlib Python toolbox is a fork of the python-edf toolbox from Christopher Lee-Messer. and uses the EDFlib from Teunis van Beelen.
- **MNE-Python**: (https://mne.tools/stable/index.html) MNE-Python is an open-source Python package for exploring, visualizing, and analyzing human neurophysiological data such as MEG, EEG, sEEG, ECoG, and more. It includes modules for data input/output, preprocessing, visualization, source estimation, time-frequency analysis, connectivity analysis, machine learning, statistics, and more.
- **TorchEEG**: (https://torcheeg.readthedocs.io/en/latest/) TorchEEG is a library built on PyTorch for EEG signal analysis. TorchEEG aims to provide a plug-and-play EEG analysis tool, so that researchers can quickly reproduce EEG analysis work and start new EEG analysis research without paying attention to technical details unrelated to the research focus. TorchEEG specifies a unified data input-output format (IO) and implement commonly used EEG databases, allowing users to quickly access benchmark datasets and define new custom datasets. The datasets that have been defined so far include emotion recognition and so on.
- **EEGLAB**: (https://sccn.ucsd.edu/eeglab/) EEGLAB is an interactive Matlab toolbox for processing continuous and event-related EEG, MEG and other electrophysiological data incorporating independent component analysis (ICA), time/frequency analysis, artifact rejection, event-related statistics, and several useful modes of visualization of the averaged and single-trial data. EEGLAB runs under Linux, Unix, Windows, and Mac OS X.
- **MetaBCI**: (https://github.com/TBC-TJU/MetaBCI) MetaBCI is an open-source platform for non-invasive brain computer interface. The project of MetaBCI is led by Prof. Minpeng Xu from Tianjin University, China. MetaBCI has 3 main parts: 1) brainda: for importing dataset, pre-processing EEG data and implementing EEG decoding algorithms; 2) brainflow: a high speed EEG online data processing framework; 3) brainstim: a simple and efficient BCI experiment paradigms design module.
- **MOABB Mother of all BCI Benchmarks**: (https://moabb.neurotechx.com/docs/index.html) MOABB is an open-source Python framework designed to facilitate **reproducible research** in Brain-Computer Interfaces (BCI), specifically for EEG-based decoding. It provides a standardized environment for benchmarking machine learning algorithms on publicly available EEG datasets. MOABB includes a variety of EEG datasets, eliminating the need for manual data collection, and ensures fair comparison between different decoding algorithms through standardized pipelines. It simplifies EEG data handling using MNE-Python and provides reliable performance comparisons under the same experimental conditions. MOABB is a powerful tool for researchers and developers working on EEG decoding and BCI applications.

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
