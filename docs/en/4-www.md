---
layout: page
title: The WEB CONFERENCE
permalink: /docs/en/www
key: docs-www
article_header:
  type: cover
  theme: dark
  image:
    src:  /docs/assets/images/www_conf.png
---

<!--
<head>
    <style>
        .container {
            display: flex;
            justify-content: space-between; Creates space around items
        }

        .image-with-caption {
            width: 100%;
            margin: auto;
        }

        .image-with-caption img {
            width: 100%;
            height: auto;
        }

        .image-with-caption figcaption {
            text-align: center;
        }
    </style>
</head>
<figure class="image-with-caption">
    <img src="../assets/images/www_conf.png">
    <!-- <figcaption>Spatial Annotation</figcaption> -->
<!-- </figure> -->


## Invitation to Join the CV-ISLR Challenge

We are excited to invite you to participate in our **Cross-View Isolated Sign Language Recognition Challenge (CV-ISLR)**, hosted as part of **The Web Conference**.

<br><br>

### Date
- **Event**: Cross-View Isolated Sign Language Recognition Challenge
- **Host**: The Web Conference & The University of Queensland
- **Timeline**:
  - **Challenge End Date**: 11 December, 2024
  - **Workshop Paper Submission**: 18 December, 2024
  - **Workshop Paper Notification**: 13 January, 2025
  - **Workshop Paper Camera-Ready**: 2 February, 2025
  - **Workshops**: 28 April - 29 April, 2025


All submission deadlines are end-of-day in the *Anywhere on Earth (AoE)* time zone.

<br><br>

### About the CV-ISLR Challenge
This challenge focuses on advancing the field of sign language recognition by addressing the unique complexities of cross-view scenarios. Participants will have the opportunity to push the boundaries of machine learning and computer vision while contributing to the inclusivity and accessibility of technology.

Cross-View Isolated Sign Language Recognition (CV-ISLR) aims to tackle a significant issue in the current field of isolated sign language recognition (ISLR). Most commonly used datasets for ISLR capture sign language videos from a frontal view. However, in real-life situations, it is not always feasible to ensure the camera is positioned directly in front of the signer. As a result, recognition models need to be capable of understanding sign language from various viewpoints, making cross-view ISLR a critical challenge.

To address this, we have curated the [**MM-WLAuslan**](https://arxiv.org/pdf/2410.19488) dataset, which was specifically recorded with cross-view recognition in mind. MM-WLAuslan is **the first** large-scale Multi-view Multi-modal Word-Level Australian Sign Language recognition dataset. We recorded **282K+** sign videos covering **3,215** commonly used Auslan glosses presented by **73** signers in a studio environment. Our filming system includes two different types of cameras, i.e., three Kinect-V2 cameras and a RealSense camera. Cameras were positioned hemispherically around the front half of the signer, and all four cameras simultaneously recorded videos.

As shown in the accompanying figures, different camera angles were utilized to reflect the diversity of potential viewpoints encountered outside controlled environments.

During testing, we further simulate real-life scenarios by setting different test conditions to evaluate model performance across various views. We provide a diverse test set with four distinct subsets, including:
1. **Studio (STU) set**: Consistent scene settings with the training set.
2. **In-the-wild (ITW) set**: Dynamic or static backgrounds replace the green screens to simulate videos recorded in diverse environments.
3. **Synthetic background (SYN) set**: A background remover extracts signers from videos, and indoor or outdoor backgrounds are synthesized.
4. **Temporal disturbance (TED) set**: This set simulates potential recording time discrepancies in real-world scenarios by randomly adjusting video segments through removal or altering playback speed.

Please see more datasets [here](https://uq-cvlab.github.io/MM-WLAuslan-Dataset/docs/en/dataset-source).

<br><br>

### Challenge Details

To encourage research in this area, we are launching the Cross-View Isolated Sign Language Recognition Challenge, which will feature two competition settings:
1. **RGB-based ISLR**: Participants will develop models using only the front Kinect-V2 RGB data from the dataset, aiming to recognize signs from different views (left-front and right-front Kinect-V2) based on pixel information alone.
2. **RGB-D-based ISLR**: Participants will have access to both RGB and depth data, allowing them to leverage multi-modal information to improve recognition performance across views.

We will use **Top-1 & Top-5 Accuracy** to evaluate participants' ISLR models.

<br><br>

### Dataset Download

We have divided the dataset into three subsets: Train, Valid, and Test.

- **Train and Valid**: These subsets provide RGB and depth data from the front view, along with the corresponding gloss annotations.
- **Test**: This subset only includes RGB and depth data from the left and right views, without annotations.

<br><br>

The download links for each subset **(Click to enter Google Drive)**:
  - [Train, Valid Test Labels](https://drive.google.com/drive/folders/1fa7tu7PfNl8JVLkRa5pUAzR7uMtVkGkk?usp=drive_link) (Please note that the **base names of the videos** are used in the labels. To correctly map the labels to the corresponding videos, make sure to read the [ReadMe.ipynb](https://drive.google.com/file/d/175vajwxFUz4nW8q6U-QVMp_NfTyiQZ5U/view?usp=drive_link) file included in the dataset.)
  - [Train](https://drive.google.com/drive/folders/1SaNlubIwnf8ciWIJ-tc4lYsK8F1P9IrM?usp=drive_link)
  - [Valid](https://drive.google.com/drive/folders/1VJilwDWCVIbVnOnAcbyoHN4EZOfnS5Db?usp=drive_link)
  - [Test-STU-Left](https://drive.google.com/drive/folders/1TLyN_esKh2gwThFVul7rfVE1CGqYmv7U?usp=drive_link)
  - [Test-ITW-Left](https://drive.google.com/drive/folders/18A8wEcRPJ2e5T8lMM2F_isu9qP-NyuSY?usp=drive_link)
  - [Test-SYN-Left](https://drive.google.com/drive/folders/1mYpoXTmXXIHUmRBzdq-iFVVhPAQFY4vx?usp=drive_link)
  - [Test-TED-Left](https://drive.google.com/drive/folders/1BLbi1imlSxKkWR1Hi3Fnl_L6tnDz-g_q?usp=drive_link)
  - [Test-STU-Right](https://drive.google.com/drive/folders/1RpJxVMFiOM8wVjxYimlvoH-SOI3Ve06i?usp=drive_link)
  - [Test-ITW-Right](https://drive.google.com/drive/folders/17P8v0qKVXYuy4hXeWivFWRGcvh_j0FBO?usp=drive_link)
  - [Test-SYN-Right](https://drive.google.com/drive/folders/1zYksp5QlloVlcKdTGQs9Mt4qZUYnlO_Y?usp=drive_link)
  - [Test-TED-Right](https://drive.google.com/drive/folders/1ygy5JJs4K495QYk_X-I0HbOKqy1B36Z2?usp=drive_link)

<br><br>

### Why Participate?
- **Exciting Research Opportunities**: Tackle a cutting-edge problem in sign language recognition.
- **Global Exposure**: Showcase your work at The Web Conference, a premier international venue for researchers and practitioners.
- **Generous Awards**: Compete for prizes while gaining recognition in the field.
- **Collaborative Community**: Engage with fellow researchers and practitioners passionate about creating impactful solutions.

<br><br>

### How to Participate
1. Visit our challenge page: [Insert challenge link]
2. Register your team.
3. Download the dataset and guidelines.
4. Submit your solutions before the deadline.

Whether you're a researcher, student, or enthusiast, your participation will contribute to advancing sign language recognition and fostering a more inclusive technological future.

We look forward to seeing your innovative solutions!

**Join us today and make a difference.**

[Learn More & Register](Insert link here)
