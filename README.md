# Projet N°4 : Segmentez des clients d'un site e-commerce

## Mise en Situation :
- **Entreprise :** Olist
- **Logo :**
- **But :** Fournir à ses équipes d'e-commerce une segmentation des clients qu’elles pourront utiliser au quotidien pour leurs campagnes de communication.
- **Jeux de données :** [Base de données](https://www.kaggle.com/olistbr/brazilian-ecommerce)
- **Objectifs :**
    - Comprendre les différents types d’utilisateurs grâce à leur comportement et à leurs données personnelles.
    - Fournir à l’équipe marketing une description actionable de votre segmentation et de sa logique sous-jacente pour une utilisation optimale
    - Fournir une proposition de contrat de maintenance basée sur une analyse de la stabilité des segments au cours du temps.

## Réalisations :
- **Librairies principales :** Pandas, Seaborn, Datetime, Numpy, KNNImputer
- **Etapes réalisées :**
    - **Exploration des données :**
      - Ouverture, analyse et merge des fichiers
      - Création de nouvelles variables ou transposition des données (Dates diverses, différents types de paiements ...)
      - Divers graphiques
      - Etude de la géolocalisation des acheteurs et vendeurs et création d'une mesure de distance (Harvesine) :
      - Etude de l'assymétrie des données via **Skew** :
  
