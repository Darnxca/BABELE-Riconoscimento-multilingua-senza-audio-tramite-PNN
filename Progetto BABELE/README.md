# Readme
## 1) Struttura delle directory
- Nella directory globale si trovano i vari script per l'estrazione delle feature
- CODICI_PNN: è dove si trovano gli script della PNN utilizzata sui vari dataset generati
- CSV_DATASET, CSV_DATASET_CODIFICA_SPARSA, CSV_DATASET_MERGED, CSV_DATASET_CH-SIMS_CMU-MOSEI, CSV_DATASET_OPTICAL_FLOW: contiene i vari dataset con le featurue estratte
- CSV_PNN_RESULT,CSV_PNN_RESULT_CODIFICA_SPARSA, CSV_PNN_RESULT_MERGED : sono presenti i file csv contententi le informazioni sulle presetazioni della PNN sulle varie configurazioni

## 2) Script estrazioni feature
- Estrazione_Feature_labbra_babele_con_landmark.ipynb: Script che contiene i metodi per estrarre tramite l'uso di mediapipe le feature delle labbra. Applicato sul ddataset BABELE.
- Estrazione_Feature_labbra_babele_xVSMondo_con_landmark.ipynb: Script che genera i dataset per i confronti binari tra le lingue. Applicato sul dataset BABELE.
- Estrazione_Feature_codifica_sparsa.ipynb: Script che contiene i metodi per estrarre tramite codifica sparsa delle feature. Sono precesenti anche i metodi per ridurre tramite l'uso della PCA il dataset generato. Applicato sul dataset BABELE.
- Estrazione_Feature_labbra_CHSIM CHMOSEI.ipynb: Script che contiene i metodi per estrarre tramite l'uso di mediapipe le feature delle labbra. Applicato sul dataset CHSIM CHMOSEI.
- Estrazione_Feature_Optical Flow.ipynb: Script che contiene i metodi per estrarre tramite optical flow delle feature. Applicato sul dataset BABELE.
- requirements_pnn.txt, requirements_estrazioneFeatures.txt, requirements_estrazioneSparse_coding.txt: Contengono le librerie necessari per eseguire  i  vari script.



##  3) Directory  codici PNN
- Sigma Ottimi: Contiene i file csv dei vari sigma ottimi trovati per la configurazione ottimale.
- Previsioni Errate:Contiene i file csv delle varie previsione errate della PNN. Sono contenuti  tutti i video che sono stati rpedetti in modo errato.
- Matrici Confusione: Contiene le immagini delle varie matrici di confusione generate
- PNN_BABELE.ipynb: Contiene tutti i metodi per eseguire la PNN sui file csv di BABELE con le feature estratte tramite i landmark di mediapipe su BABELE.
- PNN_SPARSE_CODING.ipynb: Contiene tutti i metodi per eseguire la PNN sui file csv di BABELE con le feature estratte tramit sparse coding, e utilizza anche i dataset ridotti tramite l'uso della PCA. 
- PNN_CHSIM-MOSEI.ipynb: Contiene tutti i metodi per eseguire la PNN sui file csv di  CHSIM-MOSEI con le feature estratte tramite i landmark di mediapipe.
- PNN_OF.ipynb: Contiene tutti i metodi per eseguire la PNN sui file csv di BABELE con le feature estratte tramit optical flow.