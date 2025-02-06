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
