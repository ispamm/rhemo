# Transferable Quaternion Embeddings for Speech Emotion Recognition
This repository supports the [paper](arxiv_link) "Transferable Quaternion Embeddings for Speech Emotion Recognition" submitted to IEEE Transactions of Audio, Speech and Language processing. Here you can find easy instructions for the download of the required data  and our pre-trained weights, for training from scratch R2Hemo on Iemocap and for the application of our approach to a generic speech emotion recognition dataset.


## Installation
Our code is based on Python 3.7.

To install all required dependencies run:
```bash
pip install -r requirements.txt
```


## Data download and preprocessing
* Follow these instructions to download the Iemocap dataset: https://sail.usc.edu/iemocap/
* Run the following scripts to pre-process the dataset:
```bash
python3 preprocessing_IEMOCAP_vad.py
python3 preprocessing_IEMOCAP.py
```

It is possible to download our pre-trained R2Hemo weights with this command:
```bash
python3 download_weights.py --output_path models/
```
These weights are also available for manual download [here](https://drive.google.com/file/d/1vCX0KHW44Q9plKTdkgyKZRcyjfgVA7jX/view?usp=sharing).

If you use our pretrained skip the following section.


## R2Hemo pretraining
To run the R2Hemo pretraining


WORK IN PROGRESS...
