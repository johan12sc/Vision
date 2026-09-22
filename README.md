best.pt représente une première version du modèle.

Le projet peut continuer à évoluer grâce à de nouvelles données.

📊 Enrichir le jeu de données

Ajouter de nouveaux exemples avec :

différents éclairages ;
différents angles ;
différentes distances ;
différents environnements ;
plusieurs bouteilles ;
différentes conditions de prise de vue.

Plus les données représentent les situations réelles, plus l'entraînement peut être adapté à ces situations.

🧠 Réentraîner le modèle

Les nouvelles données peuvent ensuite être annotées et utilisées pour poursuivre l'entraînement.

Nouvelles données
       ↓
Annotation
       ↓
Nouveau dataset
       ↓
Réentraînement
       ↓
Nouveau modèle
📱 Déploiement mobile

Une évolution possible est de rendre le modèle utilisable directement sur smartphone.

Par exemple :

YOLOv8
   ↓
Conversion / optimisation
   ↓
Modèle mobile
   ↓
Application Android
   ↓
Caméra du téléphone

L'objectif serait de pouvoir effectuer les prédictions directement sur le téléphone.

🤖 Vers l'IA + matériel

Une autre évolution serait de connecter le modèle à un système physique.

Par exemple :

Caméra
   ↓
Modèle IA
   ↓
Détection
   ↓
Arduino
   ↓
Capteur / LED / Servo / Actionneur

Le projet pourrait alors évoluer vers un système capable de :

Détecter → Analyser → Décider → Agir

Cette approche permettrait de connecter IA, développement logiciel et matériel dans un même système.

🛠️ Technologies
Python
YOLOv8
Ultralytics
PyTorch
OpenCV
AnyLabeling
Computer Vision
Apprentissage supervisé
📦 Contenu du dépôt
awa-vision/
│
├── best.pt
├── data.yaml
└── README.md
best.pt

Le modèle YOLOv8 entraîné.

data.yaml

La configuration des classes utilisées pendant l'entraînement.

README.md

La documentation du modèle et les exemples d'utilisation.

👨‍💻 Auteur

Johan Kouassi

L3 Développement d'Applications et e-Services — UVCI
Développeur Data & IA — Simplon Côte d'Ivoire

Je m'intéresse au développement d'applications combinant :

Data + IA + Full Stack

🎯 Actuellement à la recherche d'un stage en Data, IA ou Développement Full Stack.

⭐ Le modèle peut être utilisé comme base pour expérimenter, développer une application ou poursuivre l'entraînement avec de nouvelles données.
