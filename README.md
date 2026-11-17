# SOUNDLAB V3 — Creative Pop Deluxe

Application éducative autonome, à héberger sur GitHub Pages.

## Installation
Publier `index.html` à la racine du dépôt, puis activer GitHub Pages (branche `main`, dossier `/`). Aucun build ni compte n'est nécessaire.

## Fonctionnalités
Six machines (Sound Mixer, Mouth Lab, Beat Machine, Voice Wave, Word Forge, Accent Switch), huit mini-jeux aux interactions distinctes, PhonoCodex, progression DISCOVER/PRACTISE/MASTER, badges, sauvegarde locale et import/export JSON, studio d'enregistrement avec `MediaRecorder` et visualisation réelle de l'amplitude. Les enregistrements ne quittent pas le navigateur.

## Audio et rigueur scientifique
Les démonstrations utilisent les voix de synthèse **disponibles sur l'appareil** (Web Speech API). Elles ne sont **pas des modèles phonétiques vérifiés** ; une voix UK/US peut manquer. Les exemples de transcription présentent des variantes de référence simplifiées (anglais britannique non rhotique et anglais américain général). Le microphone nécessite HTTPS ou localhost, une autorisation et un navigateur compatible. Le studio compare des écoutes, **sans attribuer de score automatique de prononciation**. Les enregistrements restent en mémoire durant la session ; leur téléchargement est proposé avant de quitter.

## Compatibilité et limites
Application responsive. Tester microphone et synthèse vocale sur les appareils visés ; aucun test physique navigateur ou microphone n'a pu être exécuté dans cet environnement. La sauvegarde JSON contient la progression, pas les fichiers audio. Le fonctionnement du moteur vocal varie selon le système d'exploitation.
