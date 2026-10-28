# La Foire de Liège — famille 1 (applis élèves)

Séquence de cours pour iPad sur la Foire d'octobre de Liège. Version 1.0,
pas encore publiée (adresse prévue : https://ludo1104-rp.github.io/foire-liege/).

## Contenu
- **Je découvre** : récit animé en 10 parties (`PARTIES`). Chaque partie a une
  scène SVG qui s'anime au défilement (`SCENES` : roue, calendrier, carte,
  compteur 1594 → 2026, déménagement, attractions, nourriture, visiteurs,
  trésor). Les phrases apparaissent l'une après l'autre.
  Texte complet par défaut (`t`), « Texte facile » FALC en option (`l`).
- Partie 6 = vidéo YouTube « À quoi ressemblait la Foire de Liège autrefois ? »
  (Qu4tre – Liège Média, Short h2vPRoAUzhQ) : la partie dit quoi y chercher,
  le texte ne la répète pas. Contenu tiré de sa description (sous-titres bloqués).
- **Je comprends** : écran « Je choisis mon défi », puis 36 questions (q1…q36,
  q31-36 sur la vidéo, c:1 = seulement en texte complet). « Mes questions difficiles ».
- **Je présente** : fiche guidée en 7 étapes, « Montrer en grand » pour le TVI.
- `GUIDE-PROF.md` : déroulé des 4 séances et autres prolongements.

## Pièges
- Sources de l'appli : scratchpad de session (contenu.js, scenes.js, ecrans.js…)
  assemblées avec le gabarit. Pour une retouche, modifier `index.html` directement.
- `q.p` = numéro de l'identifiant de la partie (p10 = la vidéo), pas sa position.
- Dates : départ de La Batte en 1854 (Wikipédia), installation définitive
  en 1865 (vidéo). 2026 : plus de 160 attractions (vidéo).
- La vidéo demande Internet ; elle ne se lance pas depuis un fichier local.
- Clé de stockage `foire-liege` : ne plus la changer.

## Prochaine étape
- Ludo relit les textes et teste sur iPad (animation au doigt, vidéo, voix), puis dit « publie ».
