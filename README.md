# SOUNDLAB V1 — by BROT2YOU

Nouvelle application indépendante de SOUNDQUEST, sans dépendances externes.

## Utilisation

Ouvrir `index.html` pour explorer les contenus. Pour enregistrer au microphone, **publier sur GitHub Pages en HTTPS** (ou utiliser un serveur local `localhost`). Sur iPhone, ouvrir la page dans Safari si un navigateur intégré bloque les autorisations.

Le bouton Enregistrer demande l'autorisation au clic, enregistre avec `MediaRecorder`, puis Arrêter finalise un fichier audio réécoutable et téléchargeable. Les erreurs d'autorisation ou d'incompatibilité sont expliquées à l'écran. Le format audio dépend du navigateur (WebM ou MP4/M4A). Les enregistrements restent dans l'onglet, ils ne sont pas téléversés ni sauvegardés automatiquement.

## Limites explicites

- Les voix de démonstration proviennent de la synthèse vocale du navigateur : disponibilité, timbre et accent varient selon l'appareil.
- La notation IPA représente des accents de référence et ne couvre pas toutes les variétés.
- Il n'existe pas de notation automatique fiable de la prononciation dans cette version.
- V1 contient un tableau de 41 phonèmes, 18 fiches de règles, 8 comparaisons UK/US et quelques exercices de répétition ; une référence exhaustive demanderait un corpus enrichi et une validation linguistique.

## Déploiement

Créer un dépôt GitHub Pages (par exemple `Soundlab`), déposer `index.html` à la racine et activer Pages sur la branche principale. Aucune installation ni clé API.
