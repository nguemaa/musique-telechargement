# Musique — Téléchargement & Catalogue Officiel

Plateforme de sortie musicale hébergée sur *GitHub Pages* pour la diffusion des morceaux, instrumentaux et packs bonus.

##  travail en équipe

- *main* : branche de référence (mise en ligne officielle). *Ne pas modifier directement sans validation.*
- Chacun travaille dans sa propre branche dédiée (feat/...).
- Quand une tâche est terminée et testée, on ouvre une *Pull Request* vers main pour vérifier ensemble avant fusion.

---

## Consignes par branche

### 1. Branche feat/catalogue-sons

*Objectif :* préparer et structurer la liste complète des pistes de la sortie.
- Lister tous les titres à publier (son principal, version instru, version clean/radio, pack pochette & paroles, etc.).
- Renseigner pour chaque élément dans index.html (defaultTracks) :
  - id et code (01, 02, 03...)
  - title (titre exact)
  - artist (artiste / feat.)
  - category ("Audio" ou "Bonus")
  - format (ex. MP3 • 320 kbps, WAV, ZIP)
  - size (taille approximative, ex. 8.4 Mo)
- Vérifier que la recherche par mot-clé, le filtre par catégorie et le tri fonctionnent bien avec ces titres.

### 2. Branche feat/liens-audio-telechargement

*Objectif :* brancher les vrais liens d'écoute et de téléchargement.
- Récupérer et vérifier chaque lien audio (aperçu) et chaque lien de fichier téléchargeable.
- Mettre à jour previewUrl et downloadUrl dans defaultTracks sur cette branche.
- Tester chaque bouton *Écouter* et *Télécharger* pour s'assurer qu'aucun lien n'est cassé ou bloqué.
- Vérifier que le compteur de téléchargements et les statistiques globales s'incrémentent bien au clic.

### 3. Branche feat/design-mobile-infos

*Objectif :* soigner le rendu visuel (surtout sur téléphone) et les textes de sortie.
- Vérifier l'affichage sur écran mobile et ordinateur (cartes, boutons, lecteur audio, zone commentaires).
- Mettre à jour les textes d'annonce de la sortie (titre principal, date de sortie, message aux auditeurs, crédits / réseaux).
- S'assurer que les contrastes, marges et boutons restent confortables à cliquer sur smartphone.

---

## Checklist avant le lancement

- [ ] Tous les titres, artistes et catégories sont complets sans faute d'orthographe.
- [ ] Tous les liens d'écoute et de téléchargement ont été testés.
- [ ] L'affichage mobile a été vérifié.
- [ ] Les branches validées ont été fusionnées proprement dans main.
