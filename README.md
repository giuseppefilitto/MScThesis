# MScThesis
 Thesis for the Master's Degree in Applied Physics

| **Author**  | **Project** |  **Supervisor** | **Co-Supervisor** | **Build Status** |
|:------------:|:-----------:|:-----------------:|:-----------:| :-----------:
| [**Giuseppe Filitto**](https://github.com/giuseppefilitto) | **MScthesis**| [**Prof. G. Castellani**](https://www.unibo.it/sitoweb/gastone.castellani) |[**Dr. N. Curti**](https://github.com/Nico-Curti) | **MacOS** : miss |


# MScthesis
Master's Degree final dissertantion in Applied Physics

## Abstract

Colorectal cancer is a malignant neoplasm of the large intestine resulting from the uncontrolled proliferation of the cells making up the colorectal tract.
Colorectal cancer is the second malignant tumor per number of deaths after the lung cancer and the third for number of new cases after the breast and lung cancer. Risk factors for this kind of cancer include colon polyps, long-standing ulcerative colitis, diabetes of type II and also genetic history (HNPCC or Lynch syndrome). 

<p float="left">
  <img src=tex/images/cancerstats.png width="690" />
</p>

In order to get information about diagnosis, therapeutic effect evaluation on colorectal cancer, radiomic analysis can be performed on radiological images through the application of dedicated radiomic algorithms based on segmentation and features extraction. By segmentation we mean the determination of the regions of interest (ROI) in images that are going to be analyzed. In clinical routines, it is carried with manual or semi-manual techniques by radiologists, but this process is time-consuming, highly operator-dependent and subject to operator expertise. By Radiomic features we meant the features coming from radiographic medical images, which can potentially uncover disease characteristics that fail to be appreciated by the naked eye.

<p float="left">
  <img src=tex/images/T2AX_Alta_8.png width="230" />
  <img src=tex/images/T2AX_BO11_5.png width="230" />
  <img src=tex/images/T2AX_BO1_9.png width="230" /> 
</p>

The aim of this project is to implement an automated pipeline based on automatic segmentation of T2 weighted Magnetic Resonance (MR) images exploiting Convolutional Neural Networks in order to predict the response to neo-adjuvant chemo-radiotherapy of colorectal cancer using radiomics features.
