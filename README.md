# KOHTD: Kazakh Offline Handwritten Text Dataset
[![PWC](https://img.shields.io/badge/PyTorch-v1.8-red)](https://pytorch.org/)
[![PWC](https://img.shields.io/badge/Tensorflow-v2.3-red)](https://pytorch.org/)
[![PWC](https://img.shields.io/badge/KOHTD-v1.0-red)](https://pytorch.org/)





> **KOHTD: Kazakh Offline Handwritten Text Dataset**<br>
> [Nazgul Toiganbayeva](https://github.com/abdoelsayed2016), 
> [Mahmoud Kasem](),
> [Galymzhan Abdimanap](),
> [Kairat Bostanbekov](),
> [Abdelrahman Abdallah](https://github.com/abdoelsayed2016),
> [Anel Alimova](),
> [Daniyar Nurseitov](),
> <br>

    



## Abstract 
Despite the transition to digital information exchange, many documents, such as invoices, taxes, memos and questionnaires, historical data, and answers to exam questions, still require handwritten inputs. In this regard, there is a need to implement Handwritten Text Recognition (HTR) - this is an automatic way to decrypt records using a computer. Handwriting recognition is challenging because of the virtually infinite number of ways a person can write the same message. For this proposal we introduce Kazakh handwritten text recognition research, a comprehensive dataset of Kazakh handwritten texts is necessary. This is particularly true given the lack of a dataset for handwritten Kazakh text. In this paper,  we provide our extensive Kazakh offline Handwritten Text dataset (KOHTD), which has 3000 handwritten exam papers. The sources of all the exam papers in the datasets were written by students. The database consists of more than 140335 images and there are approximately 922010 symbols. It can serve researchers in the field of handwriting recognition tasks by using deep and machine learning.We used a variety of popular text recognition methods for word and line recognition in our studies, including CTC-based and attention-based methods. The findings demonstrate KOHTD's diversity.

## KOHTD Dataset

You can download the dataset through this  <a href="https://drive.google.com/file/d/1BD2Nx2kn79xJLKJRKlmAFASdAb03ODIH/view">link</a> 

Our database consists of a large collection of exam papers filled by students at Satbayev University and Al-Farabi Kazakh National University, this exam was made and answered in the Kazakh Language (99%) and Russian Language (1%) as shown in Fig.  1, after we received this exam answer, we scanned it and make experiments that related to pre-processing of the examination lists to automatically identifying lists, evaluate the contours of lists,recovering rotations, and also segmentation by line and by words so we can apply our Deep Learning model to recognize each word and remove the artifacts in the edges at the boundaries of segmented words. We have developed our intelligent software using state-of-the-art deep learning models to solve the problem of recognizing and processing natural language, which consists of optical character recognition of the manuscript texts in Kazakh and Russian languages.

