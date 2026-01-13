# V-JEPA 2 Zero-Shot Video Anomaly Detection

**AISHII** – AI-Powered Imaging Solutions  
https://aishii.tech 

## Description
Détection d'anomalies vidéo **zero-shot** avec V-JEPA 2 (Meta FAIR, 2025) :  
- Encoder frozen + adapter entraîné uniquement sur données normales  
- Dataset : UCSD Ped2  
- Résultats : ratio 4.53× | AUC-ROC 0.90 | F1 0.95

## Dataset
UCSD Ped2 (archive complète) :  
[Télécharger depuis Google Drive](https://drive.google.com/file/d/14rHgikHqRKmwayuJnusAYWk7K9xsnQ7x/view?usp=drive_link)  
(Placez le fichier `UCSD_Anomaly_Dataset.tar.gz` dans le dossier POC_VJEPA2_AnomalyDetection avant de lancer le notebook.)


## Installation
```bash
pip install -r requirements.txt

