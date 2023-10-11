# CLAP_Analysis

## A very brief introduction with CLAP model architecture and music data

**Author**: [Mahbub Ul Alam](https://www.linkedin.com/in/anondo),
 Email: mahbub.ul.alam.anondo@gmail.com

"[**CLAP (Contrastive Language-Audio Pretraining)**](https://github.com/microsoft/CLAP) is a model that learns acoustic concepts from natural language supervision and enables **Zero-Shot inference**. The model has been extensively evaluated in 26 audio downstream tasks achieving SoTA in several of them including classification, retrieval, and captioning."

CLAP connects language and audio by using **two encoders** and a **contrastive learning** objective, bringing audio and text descriptions into a **joint multimodal** space. More can be read from the paper entitled [**CLAP: Learning Audio Concepts from Natural Language Supervision**](https://ieeexplore.ieee.org/abstract/document/10095889).

**The following tasks will be covered in this notebook,**

1. Zero-shot prediction using CLAP

2. Extracting audio encodings using CLAP from a music dataset

3. Clustering and visualizing the audio encodings

4. Using the dataset as a training dataset for pretrained CLAP model

5. Proposing two other open-source models simillar for the tasks mentioned above

**CLAP pretrained-models (weights) can be obtained using this link**,

a. https://zenodo.org/record/8378278

**The music dataset can be obtained using the following links,**

b. [CSV file with annotations for 67 genres on 670 tracks](https://drive.google.com/file/d/1Qeb1li9IY8skmuMFA9FM8RyM3KGrte8g/view?usp=sharing)

c. [The audio files for these tracks as mp3 files](https://drive.google.com/file/d/1AOZ8IwNo8nSbIRFr8rqzjnbQQ2bnxKNN/view?usp=sharing)

This notebook should be run from **inside the 'src/' directory of the [CLAP](https://github.com/microsoft/CLAP)** github project repository.