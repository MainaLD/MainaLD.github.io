# Portfolio de MainaLD

## 1) Traitement de Nuages de Points
Présentation de l'application de traitement de nuages de points par segmentation sémantique. Projet de recherche dans le cadre de mon alternance au L@bISEN, que j'ai également présenté comme projet chef-d'œuvre pour l'obtention de mon diplôme de développeuse en intelligence artificielle.

Lien vers la présentation et la vidéo de démonstration : [Traitement de Nuages de Points](https://drive.google.com/file/d/1HWaCDoZdQkt2sv8ooS2gg-9OwQ0G_HAK/view?usp=sharing)
![Image Traitement](images/Traitement_nuages_de_points_Application.png)
![Image visualisation](images/Traitement_nuages_de_points_Visualisation.png)


## 2) Cas Pratique : Vérificateur d’uniforme
Pour l'obtention de mon diplôme de développeuse en intelligence artificielle, j'avais pour objectif d'améliorer une application existante.
L'application doit permettre de contrôler que le port de l'uniforme est conforme : port du casque et du gilet. Dans la version de base, elle ne permettait pas de détecter les gilets (app_original.py).
Après avoir repris la labellisation des images en ajoutant le label "gilet", puis augmenté le dataset (accès restreint), j'ai entraîné différents modèles de l'algorithme YOLOv5 avec différents hyperparamètres pour obtenir le "meilleur" modèle pour la prédiction.  J'ai ainsi déployé le modèle YOLOv5s_b64 dans la nouvelle application de Streamlit, car il obtenait le meilleur compromis entre sa taille et ses performances.

Lien vers le projet : [Projet Vérificateur d’Uniforme](https://github.com/MainaLD/Cas_pratique_Verificateur_d_uniforme#cas-pratique--v%C3%A9rificateur-duniforme)

![Image uniforme_ omplet](images/Verificateur_uniforme_complet.JPG) ![Image uniforme incomplet](images/Verificateur_uniforme_incomplet.JPG)


## 3) Projet n°18 : Modèle IA Detection Masks - version 2
Il s'agit de l'évolution d'un précédent projet. Application avec Streamlit et OpenCV de Transfer Learning pour la détection des masques.
Contexte du projet : Nous cherchons à améliorer l’application développée au projet 14 (Modèle Détection Masques). L'objectif est de développer une application Streamlit capable de détecter et localiser le ou les visages dans une image, puis de déterminer la présence ou l'absence du masque pour chaque visage détecté.
Lien vers le projet : [Projet Modèle IA Detection Masks 2](https://github.com/MainaLD/18_Model_IA_detection_masks_2)


