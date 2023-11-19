
# Electronic Components Detectors : CNN in Edge Impulse
![image](https://github.com/GhozlenBY/-Electronic-components-dectetors/assets/148441001/5b119b2f-8bc7-48c1-8c28-d71624c188f1)

# Projet Overview
Ce projet explore l'utilisation d'un réseau neuronal convolutif (CNN) via Edge Impulse, visant à élargir les horizons au-delà des réseaux neuronaux denses classiques. Notre focus était sur un ensemble de données de composants électroniques pour entraîner notre CNN, incluant les étapes de transformation d'images, téléchargement des données, création d'une impulsion, extraction de caractéristiques, et l'entraînement du modèle.

# Téléchargement des Données
Nous avons commencé par lancer un nouveau projet dans Edge Impulse et navigué vers la section Acquisition de données. L'option "Télécharger des données existantes" a été utilisée pour intégrer nos images de composants électroniques, en veillant à activer la répartition automatique entre les ensembles d'entraînement et de test. Chaque catégorie, comme les résistances, a été soigneusement un label avant de procéder au téléchargement. Ce processus a été répété pour chaque catégorie de composant.
![data](https://github.com/GhozlenBY/-Electronic-components-dectetors/assets/148441001/9ae11c69-0752-4ce5-982f-b6c768ad45a2)


# Création de l'Impulse
Dans cette phase, nous avons configuré les dimensions des images et ajusté les paramètres de redimensionnement pour les images non carrées. Des blocs essentiels tels que le traitement d'image et la classification (Keras) ont été ajoutés, établissant la base pour l'impulsion.
![impulse](https://github.com/GhozlenBY/-Electronic-components-dectetors/assets/148441001/2cad8bbf-517d-43f8-b7fb-ea11eadf79e8)

# Extraction de Caractéristiques
Nous avons défini les images en niveaux de gris et généré des caractéristiques, en convertissant les images en pixels de 28x28 en niveaux de gris, les préparant ainsi pour la phase d'entraînement.

# Entraînement du Modèle
Le CNN a été entraîné avec le classificateur NN. Nous avons expérimenté avec différents hyperparamètres, ajustant le nombre de cycles d'entraînement, les filtres et les tailles de noyau. Des ajustements ont 
été apportés à l'architecture du modèle, notamment l'ajout d'une couche de désactivation après la première couche de convolution et la modification de la deuxième couche pour incorporer 28 filtres.
![features](https://github.com/GhozlenBY/-Electronic-components-dectetors/assets/148441001/962b7471-47ed-47ca-9cfa-7bf203cb1793)
![model](https://github.com/GhozlenBY/-Electronic-components-dectetors/assets/148441001/e6885679-80c0-49c8-9cc6-30816f68f6f9)

# Test du model
Pendant le collect des données d'entrainement on a télécharger des données de test pour les différents label pour tester le model entrainé.
![testing](https://github.com/GhozlenBY/-Electronic-components-dectetors/assets/148441001/72914955-952c-482a-9da9-36c3fbf6bc09)

# Déploiment et Observation:
![resistor](https://github.com/GhozlenBY/-Electronic-components-dectetors/assets/148441001/2f1aec02-9fbd-4a5f-b1a6-c9ac71456101)![image](https://github.com/GhozlenBY/-Electronic-components-dectetors/assets/148441001/afed8343-ea1a-497b-8a29-63f36d84f2dc)![test_Led](https://github.com/GhozlenBY/-Electronic-components-dectetors/assets/148441001/280bc024-459a-463e-9e5b-ef63fccc6b50)


