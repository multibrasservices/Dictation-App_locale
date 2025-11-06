# Notes Vocales IA

**Votre voix, vos idées, parfaitement rédigées.**

---

## Description

Cette application de dictée intelligente transforme vos enregistrements vocaux en notes claires et bien structurées. 
Parlez librement, et laissez l'IA de Gemini transcrire, nettoyer et formater vos idées pour vous. 
Elle est conçue pour tous ceux qui pensent mieux à voix haute : étudiants, professionnels ,créatifs, devellopeurs.

## Fonctionnalités Clés

- **Visualisation Audio en Direct :** Voyez votre voix en temps réel pendant que vous enregistrez.
- **Transcription Instantanée :** Obtenez une transcription brute de votre audio dès que vous avez terminé l'enregistrement.
- **Correction par IA :** Gemini affine automatiquement la transcription brute pour en faire une note soignée,
   en supprimant les mots de remplissage, en corrigeant les répétitions et en ajoutant une mise en forme (titres, listes, etc.).
- **Notes Modifiables :** Vous pouvez modifier la transcription brute et la note finale directement dans l'application.
- **Exportation Markdown :** Sauvegardez vos notes formatées en tant que fichier Markdown (`.md`) en un seul clic. Le titre de la note est utilisé comme nom de fichier.
- **Mode Clair / Sombre :** Une expérience visuelle confortable dans n'importe quel environnement lumineux.

## Comment l'utiliser

1.  Cliquez sur le bouton du **microphone** pour commencer à enregistrer.
2.  Exprimez vos idées. L'application visualisera votre audio en direct.
3.  Cliquez sur le bouton **d'arrêt** lorsque vous avez terminé.
4.  L'application générera d'abord une transcription **brute** (`Raw`).
5.  Ensuite, elle créera automatiquement une version **polie** (`Polished`) de la note.
6.  Vous pouvez basculer entre les onglets pour voir et modifier les deux versions.
7.  Cliquez sur le bouton **Sauvegarder** (`Save`) pour télécharger votre note polie en tant que fichier Markdown.
8.  Cliquez sur le bouton **Nouveau** (`New`) pour tout effacer et recommencer.

## Technologies Utilisées

- **Frontend :** HTML5, CSS3, TypeScript
- **Modèle d'IA :** Google Gemini API (`gemini-2.5-flash`)
- **Bibliothèques :**
  - `marked`: Pour convertir le Markdown en HTML.
  - `turndown`: Pour reconvertir le HTML en Markdown lors de la sauvegarde.
