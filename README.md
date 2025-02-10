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
<!---
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
-->
## 📊 Datasets
The tables below, one for each task, provides an overview of key datasets used in BCI research. It includes details such as the year of publication, task type, number of classes, participants, and channels, as well as the sampling frequency, total recording time, whether the data was collected in a lab setting, and its availability in BCI frameworks.

### Motor Imagery
Motor Imagery (MI) in Brain-Computer Interface (BCI) applications refers to the mental simulation of movement without actual muscle activity. When a person imagines moving a limb (e.g., their left or right hand), specific patterns of brain activity, primarily in the sensorimotor cortex, can be detected using EEG. These patterns, often represented as event-related desynchronization (ERD) and event-related synchronization (ERS) in specific frequency bands (e.g., mu and beta), are used to decode the intended movement. MI-based BCIs enable applications like neurorehabilitation, prosthetic control, and communication for individuals with motor impairments.

### Emotion Recognition
Emotion recognition is the task of identifying and classifying human emotions from physiological or behavioral signals, such as EEG, facial expressions, or speech.

| Dataset | Year | Task | #Classes | #Subjects | #Channels | Freq (Hz) | TotalTime (?) | LabSetting |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [SEED-VII](https://bcmi.sjtu.edu.cn/~seed/seed-vii.html) | 2024 | ER | Discrete | 20 | 62.0 | 1000.0 | 313.2 | yes |
| [FACED](https://doi.org/10.7303/syn50614194) | 2023 | ER | V/A | 55 | 32.0 | 250.0 | 787.4533333333333 | yes |
| [FACED](https://doi.org/10.7303/syn50614194) | 2023 | ER | V/A | 68 | 32.0 | 1000.0 | 973.5786666666667 | yes |
| [Imagined Emotion Study](https://openneuro.org/datasets/ds003004/versions/1.1.1) | 2023 | ER | Discrete | 34 | 199.0 | 128.0 |  | yes |
| [MAET Dataset](https://doi.org/10.1145/3581783.3613797) | 2023 | ER | V/A | 20 | 62.0 | 1000.0 | 78.32 | yes |
| [Response to Oil Paintings](https://doi.org/10.1109/EMBC48229.2022.9871630) | 2022 | ER | V/A | 22 | 62.0 | 1000.0 | 11 | yes |
| [BCI2022]() | 2022 | ER | Discrete | 80 | 30.0 | 250.0 | ? link 404 |  |
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

### Neurodegenerative diseases
Detection of neurodegenerative diseases involves identifying biomarkers and patterns of neural deterioration using methods like neuroimaging (MRI, PET), electrophysiology (EEG, MEG), fluid biomarkers (CSF, blood), and cognitive assessments. Machine learning and AI are increasingly used to analyze these data for early diagnosis and progression tracking.

### Seizure Prediction
Seizure prediction involves analyzing brain activity, typically from EEG, to detect patterns that precede epileptic seizures. Machine learning models and signal processing techniques identify preictal states, enabling early warnings and potential intervention to prevent or mitigate seizures.

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
