Birds-identification
<br/>
<br/>

[Birds-identification](https://github.com/isabelleysseric/Birds-identification) (GitHub)
&nbsp; • &nbsp;[Birds-identification](https://github.com/isabelleysseric/Birds-identification/wiki) (Wiki)
&nbsp; • &nbsp;[isabelleysseric.com](https://isabelleysseric.com) (Portfolio)
&nbsp; • &nbsp;[isabelle-eysseric](https://www.linkedin.com/in/isabelle-eysseric/) (Linkedin)
&nbsp; • &nbsp;[isabelleysseric](https://hub.docker.com/u/isabelleysseric) (Docker)
<br/>
<br/>


## Resume

<p align="justify">BirdCLEF 2021, concours Kaggle est une compétition Kaggle[1] qui a pour but de classifier des chants d’oiseaux par espèce. Cette tâche est très complexe en raison des enregistrements très bruités. Nous proposons d’extraire le mel-spectrogramme des fichiers audio et d’utiliser un réseau à couches de convolution afin d’effectuer la classification. Les modèles ResNet semblent les plus prometteurs bien que le pré-entraînement de ces réseaux ne semble pas être bénéfique. Le Resnet 34 obtient une accuracy en test de 52.48%. Ce qui laisse entendre que la tâche est réalisable mais qu’il y a toujours place à amélioration.</p>
<br/>
<br/>


# Repertoire

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


