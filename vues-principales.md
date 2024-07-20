# Vues principales

Ethos permet à l'utilisateur une grande flexibilité dans l'affichage de différentes vues. Dans un premier temps, seules les informations de base présentées ci-dessous sont affichées, jusqu'à ce que l'utilisateur personnalise ou ajoute des vues et des widgets à afficher. Notez qu'il est possible de définir jusqu'à 12 vues principales.

Les vues principales partagent normalement les barres supérieure et inférieure, mais d'autres options sont possibles, voire même configurables par l'utilisateur. Reportez vous à la section Configurer les écrans pour plus de détails sur la configuration des affichages et la programmation LUA.

![Exemple de vue principale](.gitbook/assets/mainviews1.png)

## La barre supérieure

La barre supérieure affiche le nom du modèle sur la gauche, ainsi que la phase de vol active si ces dernières sont utilisées.

![Barre supérieure](https://github.com/user-attachments/assets/ad0ca0d6-8fd5-4f75-8149-870fcbe58ef6)

Sur la droite se trouvent des icônes pour :

* l'enregistrement des données
* l'écolage (maître ou l'élève selon le cas)
* RSSI 2.4G
* RSSI 900M
* le volume sonore
* l'état de la batterie radio

Un appui sur les icônes du haut-parleur ou de la batterie permet d'accéder aux options Général ou Batterie de la radio.

### Avertissement d'erreur

Une icône d'avertissement d'erreur en triangle rouge s'affiche dans la barre supérieure de la vue principale lorsque ETHOS détecte une des erreurs suivantes:

* Erreurs de script Lua
* Erreur de sauvegarde de la RAM
* Exécution d'une version de test du firmware non utilisable pour le vol.

Les détails relatifs à l'avertissement sont affichés dans la page Système / Infos. Veuillez vous référer à la section Erreurs.

## La barre inférieure

![Barre inférieure](https://github.com/user-attachments/assets/7984970d-4c06-44cd-aeb4-c4bb824e04e5)

La barre inférieure comporte quatre icones pour accéder aux fonctions suivantes,de gauche à droite : Ecran d'accueil du modèle, Configuration du modèle, Configurer les écrans du modèle et Configuration du système. L'heure système s'affiche à droite. Un appui sur l'heure permet d'accéder aux options de date et d'heure de la radio.

## La zone des widgets
La zone centrale des vues principales se compose de widgets qui peuvent être configurés pour afficher des images, des chronos, des données de télémétrie, des valeurs radio, etc. L'écran principal par défaut comporte un widget sur la gauche pour une image de modèle et trois widgets pour les chronos, ainsi que l'affichage des trims et des potentiomètres. Les widgets sont configurables par l'utilisateur pour afficher d'autres informations. Une fois que plusieurs écrans ont été configurés, ils sont accessibles à l'aide d'un geste de balayage tactile ou de commandes de navigation.

Reportez-vous à la section Configurer les écrans pour plus de détails.

Note : Le widget 'Throttle ACTIVE' ci-dessus est le widget Status disponible dans le fil de discussion FrSky - ETHOS Lua Script Programming sur rcgroups.

