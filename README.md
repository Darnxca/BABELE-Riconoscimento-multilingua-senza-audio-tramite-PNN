# BABELE-Riconoscimento-multilingua-senza-audio-tramite-PNN

## Descrizione del progetto
Questo repository contiene il progetto universitario del corso di Biometria. Il progetto si focalizza sull'implementazione e l'analisi di una PNN (Probabilistic Neural Network) per il riconoscimento delle lingue senza audio utilizzando tre diverse metodologie:
- estrazione feature geometriche tramite i landmark di mediapipe;
- estrazione feature tramite l'uso di sparse coding;
- estrazione feature tramite l'uso di optical flow.

## Preprocessing
La cartella "preprocessing" contiene i file necessari per il preprocessamento dei dati. Tuttavia, le path dei file di BABELE sono relative a Google Drive. Pertanto, se si desidera eseguire il test del preprocessamento, è necessario modificare le path dei file di input per puntare ai corrispondenti file di dati di BABELE sulla propria macchina.

## Risultati intermedi
All'interno del repository sono presenti diverse cartelle con denominazione "CSV", in cui sono contenuti i risultati intermedi delle varie esecuzioni della PNN. Ogni cartella CSV corrisponde a un'istanza diversa di esecuzione della PNN, e i risultati sono salvati in file CSV facilmente accessibili.

## Implementazione della PNN
La cartella "CODICI_PNN" contiene l'implementazione della Probabilistic Neural Network (PNN) utilizzata per la classificazione delle lingue.

## Istruzioni per l'esecuzione
1. Clonare questo repository sul proprio ambiente locale.
2. Se necessario, modificare le path dei file di input nella sezione di preprocessing per puntare ai corrispondenti file di dati di BABELE sulla propria macchina.
3. Eseguire il preprocessamento dei dati eseguendo i vari file "Estrazione_feature_*.ipynb".
4. Analizzare i risultati intermedi ottenuti dalle diverse esecuzioni della PNN nella cartella "CSV".
5. Esplorare l'implementazione della PNN nella cartella "CODICI_PNN" per comprendere il funzionamento della rete neurale.
6. Eseguire il file "PNN_*.ipynb" per addestrare e testare la PNN sui dati biometrici.

Si consiglia di leggere il codice e i commenti all'interno dei file per una migliore comprensione del progetto.

## Contributi
Questo progetto è stato realizzato come parte del corso di Biometria universitario. 

## Contatti
Per qualsiasi domanda o ulteriori informazioni, si prega di contattare gli autori del progetto:

- Carmine D'Angelo [https://github.com/Darnxca](url)
- Matteo Della Rocca [https://github.com/mattdr5](url)
- Francesco Aurilio

-----------------------

# BABELE - Multilingual Recognition without Audio using PNN

## Project Description
This repository contains the university project for the Biometrics course. The project focuses on the implementation and analysis of a Probabilistic Neural Network (PNN) for multilingual recognition without audio, using three different methodologies:
- Geometric feature extraction using Mediapipe landmarks.
- Feature extraction using sparse coding.
- Feature extraction using optical flow.

## Preprocessing
The "preprocessing" folder contains the necessary files for data preprocessing. However, the paths to BABELE files are relative to Google Drive. Therefore, if you want to test the preprocessing, you need to modify the input file paths to point to the corresponding BABELE data files on your machine.

## Intermediate Results
Within the repository, there are several folders named "CSV" that contain the intermediate results of various PNN executions. Each CSV folder corresponds to a different PNN execution instance, and the results are saved in easily accessible CSV files.

## PNN Implementation
The "CODICI_PNN" folder contains the implementation of the Probabilistic Neural Network (PNN) used for language classification.

## Execution Instructions
1. Clone this repository to your local environment.
2. If necessary, modify the input file paths in the preprocessing section to point to the corresponding BABELE data files on your machine.
3. Perform data preprocessing by running the various "Feature_Extraction_*.ipynb" files.
4. Analyze the intermediate results obtained from different PNN executions in the "CSV" folder.
5. Explore the PNN implementation in the "CODICI_PNN" folder to understand the functioning of the neural network.
6. Run the "PNN_*.ipynb" file to train and test the PNN on the biometric data.

It is recommended to read the code and comments within the files for a better understanding of the project.

## Contributions
This project was developed as part of the university Biometrics course.

## Contact
For any questions or further information, please contact the project authors:

- Carmine D'Angelo [https://github.com/Darnxca](url)
- Matteo Della Rocca [https://github.com/mattdr5](url)
- Francesco Aurilio [https://github.com/Frazzy](url)
  
Thank you for your interest in the BABELE project!
