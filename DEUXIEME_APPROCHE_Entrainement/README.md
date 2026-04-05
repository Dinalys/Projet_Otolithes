# Approche Intermédiaire — Segmentation d'otolithes par DL

## Description
Ce projet implémente une approche de segmentation automatique 
des stries d'otolithes par Deep Learning, suivie d'un comptage 
algorithmique pour estimer l'âge du poisson.

## Données
Les données sont importées depuis Google Drive et ne sont pas 
incluses dans ce dépôt.

### U-Net ResNet18
- 2017/ : images brutes des otolithes
- unet_rapid/ : masques binarisés annotés par des experts
- df_final.csv : métadonnées biologiques

### DeepLab V3+ ResNet34
- unet_deeplab_fcn/ : images prétraitées 512×512
- df_final.csv : métadonnées biologiques

## Notebooks
- Unetrapid_projtech.ipynb : pipeline U-Net ResNet18
- Approche2projettech_unetdeeplab.ipynb : pipeline DeepLab V3+
