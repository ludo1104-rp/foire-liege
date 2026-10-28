# La Foire de Liège — famille 1 (applis élèves)

Public : **Tous** (étiquettes : Tous, Ma classe, Les deux — à confirmer par Ludo).

Séquence de cours pour iPad sur la Foire d'octobre de Liège. Version 1.0,
publiée le 28/10/2026 :
https://ludo1104-rp.github.io/foire-liege/ (dépôt ludo1104-rp/foire-liege).

## Contenu
- **Je découvre** : récit animé en 10 parties (`PARTIES`). Chaque partie a une
  scène SVG qui s'anime au défilement (`SCENES` : roue, calendrier, carte,
  compteur 1594 → 2026, déménagement, attractions, nourriture, visiteurs,
  trésor). Les phrases apparaissent l'une après l'autre.
  Texte complet par défaut (`t`), « Texte facile » FALC en option (`l`).
  Mot de vocabulaire (`p.d`) = petite pastille discrète, la définition
  s'ouvre au toucher (`<details class="sc-def">`).
- Partie 6 = vidéo YouTube « À quoi ressemblait la Foire de Liège autrefois ? »
  (Qu4tre – Liège Média, Short h2vPRoAUzhQ), en grand dans la carte de texte
  (pas dans la scène), + bouton blanc « Regarder sur YouTube » (logo rouge). Le texte donne
  les informations (pas de questions dans la lecture).
- Accueil : réglages dans une fenêtre, tuiles sur 1 ou 2 lignes (`rangerTuiles()`).
- **Je comprends** : écran « Je choisis mon défi », puis 36 questions (q1…q36,
  q31-36 sur la vidéo, c:1 = seulement en texte complet). « Mes questions difficiles ».
- **Je présente** : fiche guidée en 7 étapes, « Montrer en grand » pour le TVI.
- `GUIDE-PROF.md` : déroulé des 4 séances et autres prolongements.

## Pièges
- Sources de l'appli : scratchpad de session (contenu.js, scenes.js, ecrans.js…)
  assemblées avec le gabarit. Pour une retouche, modifier `index.html` directement.
- `q.p` = numéro de l'identifiant de la partie (p10 = la vidéo), pas sa position.
- Faits vérifiés le 28/10/2026 (sources dans `SOURCES`, bouton « Sources »
  de l'accueil). 1854 = départ de La Batte, d'abord provisoire (Wikipédia) ;
  1865 = « pour de bon », dit seulement par la vidéo (texte : « D'après la
  vidéo »). Année du patrimoine FWB non confirmée : pas de date dans le texte.
- Étiquettes : majuscule au début (`majuscule()` à l'affichage, les valeurs
  enregistrées de `MOTS` ne changent pas).
- La vidéo demande Internet. Ouverte comme fichier (file://), YouTube refuse
  (erreur 153) : l'appli montre alors seulement le bouton YouTube. Tester via
  `python3 -m http.server`.
- Coches et croix = SVG (`COCHE`, `CROIX`), jamais « ✓ » (ressemble à un « v »).
- Clé de stockage `foire-liege` : ne plus la changer.

## Prochaine étape
- Version 1.1 publiée le 28/10/2026 (étiquettes, faits vérifiés, sources).
- Ludo teste en classe sur iPad (animation au doigt, vidéo, voix) et donne ses retours.
