# Birdcall identification
<br/>
<br/>


<p align='center'>
  <a href="https://github.com/isabelleysseric/Birdcall-identification">Birdcall-identification</a> (GitHub)
  &nbsp; • &nbsp;<a href="https://github.com/isabelleysseric/Birdcall-identification/wiki">Birdcall-identification</a> (Wiki)<br/>
  <a href="https://github.com/isabelleysseric">isabelleysseric</a> (GitHub)
  &nbsp; • &nbsp;<a href="https://isabelleysseric.com/">isabelleysseric.com</a> (Portfolio)
  &nbsp; • &nbsp;<a href="https://www.linkedin.com/in/isabelle-eysseric/">isabelle-eysseric</a> (LinkedIn) <br/>
</p>
<br/>
<br/>


## Resume

<p align="justify">BirdCLEF 2021, concours Kaggle est une compétition Kaggle[1] qui a pour but de classifier des chants d’oiseaux par espèce. Cette tâche est très complexe en raison des enregistrements très bruités. Nous proposons d’extraire le mel-spectrogramme des fichiers audio et d’utiliser un réseau à couches de convolution afin d’effectuer la classification. Les modèles ResNet semblent les plus prometteurs bien que le pré-entraînement de ces réseaux ne semble pas être bénéfique. Le Resnet 34 obtient une accuracy en test de 52.48%. Ce qui laisse entendre que la tâche est réalisable mais qu’il y a toujours place à amélioration.</p>
<br/>
<br/>


## Repertoire

Dans le dossier **data**, il y a le sous dossier **input** et **output**. 

Dans **input**, il y a les fichiers necessaire à l'execution du programme. Dans **output**, c'est le résutat de la transformation des données sonores en images utilisée lors de la classification.

Dans **code**, il y a le code du programme. On y trouve deux fichiers identiques dont un est executabler avec Jupyter Notebook et un autre avec Python. 

Dans le dossier **images**, il y a trois images utilisées dans le wiki pour visualiser les résultats de chaque étapes. 


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


