
# Electronic Components Detectors : CNN in Edge Impulse

# Projet Overview
Ce projet explore l'utilisation d'un réseau neuronal convolutif (CNN) via Edge Impulse, visant à élargir les horizons au-delà des réseaux neuronaux denses classiques. Notre focus était sur un ensemble de données de composants électroniques pour entraîner notre CNN, incluant les étapes de transformation d'images, téléchargement des données, création d'une impulsion, extraction de caractéristiques, et l'entraînement du modèle.

#Téléchargement des Données
Nous avons commencé par lancer un nouveau projet dans Edge Impulse et navigué vers la section Acquisition de données. L'option "Télécharger des données existantes" a été utilisée pour intégrer nos images de composants électroniques, en veillant à activer la répartition automatique entre les ensembles d'entraînement et de test. Chaque catégorie, comme les résistances, a été soigneusement un label avant de procéder au téléchargement. Ce processus a été répété pour chaque catégorie de composant.
![Texte alternatif]([URL_de_l'image](https://github.com/GhozlenBY/-Electronic-components-dectetors/issues/1#issue-2000583448))

#Création de l'Impulse
Dans cette phase, nous avons configuré les dimensions des images et ajusté les paramètres de redimensionnement pour les images non carrées. Des blocs essentiels tels que le traitement d'image et la classification (Keras) ont été ajoutés, établissant la base pour l'impulsion.
![Texte alternatif](https://github.com/GhozlenBY/-Electronic-components-dectetors/issues/3#issue-2000587162)

#Extraction de Caractéristiques
Nous avons défini les images en niveaux de gris et généré des caractéristiques, en convertissant les images en pixels de 28x28 en niveaux de gris, les préparant ainsi pour la phase d'entraînement.

#Entraînement du Modèle
Le CNN a été entraîné avec le classificateur NN. Nous avons expérimenté avec différents hyperparamètres, ajustant le nombre de cycles d'entraînement, les filtres et les tailles de noyau. Des ajustements ont 
été apportés à l'architecture du modèle, notamment l'ajout d'une couche de désactivation après la première couche de convolution et la modification de la deuxième couche pour incorporer 28 filtres.
![Texte alternatif](https://github.com/GhozlenBY/-Electronic-components-dectetors/issues/2#issue-2000587063)
![Texte alternatif](https://github.com/GhozlenBY/-Electronic-components-dectetors/issues/5#issue-2000587353)

#Test du model
Pendant le collect des données d'entrainement on a télécharger des données de test pour les différents label pour tester le model entrainé.
![Texte alternatif](https://github.com/GhozlenBY/-Electronic-components-dectetors/issues/9#issue-2000588110)

#Déploiment et Observation:
![Texte alternatif](https://github.com/GhozlenBY/-Electronic-components-dectetors/issues/7#issue-2000587520)
![Texte alternatif](https://github.com/GhozlenBY/-Electronic-components-dectetors/issues/8#issue-2000587578)
![Texte alternatif](https://github.com/GhozlenBY/-Electronic-components-dectetors/issues/6#issue-2000587451)
