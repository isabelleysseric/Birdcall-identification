<h1 align="center">Birdcall identification (Kaggle Competition)<br><i>Analysis, Extraction of spectrogram image information</i></h1>
<p align="center">
  <img src="https://github.com/isabelleysseric/Birdcall-identification/blob/main/images/bird-experimentation.png" />
</p> 

<h2 align="center">    

  <!-- GitHub -->
  <a href="https://github.com/isabelleysseric/">
    <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" >
  </a>  

  <!-- Project Repo -->
  <a href="https://github.com/isabelleysseric/Birdcall-identification/">
    <img src="https://img.shields.io/badge/Repo-Birdcall_identification-green?style=for-the-badge&logo={Birdcall-identification}&logoColor=white" >
  </a>

  <!-- Wiki Project -->
  <a href="https://github.com/isabelleysseric/Birdcall-identification/wiki/">
    <img src="https://img.shields.io/badge/Wiki-Birdcall_identification-green?style=for-the-badge&logo={Birdcall-identification}&logoColor=white" >
  </a><br>
  
</h2>
<br/>


## Introduction

<p align="justify"><a href="https://www.kaggle.com/c/birdclef-2021" target="_blank">BirdCLEF 2021</a> is a Kaggle competition[1] that aims to classify bird songs by species. This task is very complex due to the very noisy recordings. We propose to extract the mel-spectrogram from the audio files and use a convolutional layer network to perform the classification. ResNet models seem the most promising although pre-training these networks does not seem to be beneficial. Resnet 34 obtains a test accuracy of 52.48%. This suggests that the task is feasible but that there is always room for improvement.</p>
<br/>
<br/>


## Repository

In the **data** folder, there are the **input** and **output** subfolders.

In **input**, there are the files necessary to run the program. In **output**, it is the result of the transformation of sound data into images used during the classification.

In **code**, there is the program code. There are two identical files, one of which is executable with Jupyter Notebook and another with Python.

In the **images** folder, there are three images used in the wiki to visualize the results of each step.


- **code**
  - *birdcall_identification.ipynb*
  - *birdcall_identification.py*

- **data**
  - **input**
    - **test_soundscapes**
      - *COL_recording_location.txt*
      - *COR_recording_location.txt*
      - *SNE_recording_location.txt*
      - *SSW_recording_location.txt*
      - *test_set_recording_dates.csv*
    - **train_soundscapes**
      - *2782_SSW_20170701.ogg*
      - *7019_COR_20190904.ogg*
      - *...*
      - *54955_SSW_20170617.ogg*
      - *57610_COR_20190904.ogg*
    - **train_short_audio**
      - **acafly**
         - *XC6671.ogg*
         - *...*
         - *XC600277.ogg*
      - ... (*not here*)
    - *sample_submission.csv*
    - *train_soundscape_labels.csv*
    - *train_metadata.csv*
    - *test.csv*
  - **output**
    - **train_img**
      - **acafly**
        - *27_0.jpg*
        - *...*
        - *131_2.jpg*
      - ...
      - yetvir
        - *22_0.jpg*
        - *...*
        - *106_2.jpg*
    - **test_img**
      - **acafly**
        - *0_0.jpg*
        - *...*
        - *26_1.jpg*
      - ...
      - **yetvir**
        - *0_0.jpg*
        - *...*
        - *21_2.jpg*
  
- **images**
  - *bird-discussion.png*
  - *bird-validation.png*
  - *bird-experimentation.png*


