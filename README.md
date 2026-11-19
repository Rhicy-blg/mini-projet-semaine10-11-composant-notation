# Mini-projet : composant de notation interactif

Bienvenue dans un nouveau genre d'exercice. À partir de cette semaine, tous les deux semaines,
tu auras un petit projet comme celui-ci en parallèle de tes notes de cours habituelles : un
vrai défi, avec une maquette à reproduire au pixel près, pas un exercice isolé que tu codes et
que tu oublies. L'objectif n'est pas de prendre la place de ton portfolio (fil rouge de toute la
formation), mais de pratiquer sur un terrain différent, pendant que tu avances sur le
JavaScript, sans jamais perdre la main sur le HTML et le CSS que tu maîtrises déjà.

Ce format vient d'un vrai site utilisé par des milliers de développeurs en apprentissage,
[Frontend Mentor](https://www.frontendmentor.io) : des maquettes réelles, avec leurs propres
petits pièges, pensées pour être reproduites fidèlement. Ce dossier est une version francisée
de l'un de leurs défis de niveau débutant (« Newbie »), pour que la langue ne s'ajoute pas à la
difficulté. Le crédit du design revient entièrement à Frontend Mentor et à son auteur ; le défi
original est consultable ici si tu veux voir à quoi il ressemble sur leur site :
[frontendmentor.io/challenges/interactive-rating-component-koxpeBUmI](https://www.frontendmentor.io/challenges/interactive-rating-component-koxpeBUmI)

## Le défi

Construire un petit composant qui permet de noter quelque chose de 1 à 5, comme on en croise
sur beaucoup de sites après un achat ou un service. Le visiteur doit pouvoir :

- voir la mise en page adaptée à la taille de son écran (mobile et ordinateur, les deux
  maquettes sont fournies) ;
- voir un effet visuel sur chaque élément interactif au survol de la souris (comme tes boutons
  depuis la semaine 3) ;
- choisir une note en cliquant sur un chiffre, puis valider son choix avec le bouton
  « Submit » ;
- voir apparaître une carte de remerciement une fois la note envoyée, qui rappelle la note
  choisie.

C'est volontairement un projet plus court que ton portfolio : compte-le comme 4 à 6 heures de
travail réel, étalées sur les deux semaines, pas un deuxième projet à temps plein.

## Deux semaines, deux usages du temps

**Semaine 10 (cette semaine) :** priorité aux notes de cours et au menu mobile de ton
portfolio. Si tu as un peu de temps en fin de semaine, commence juste le HTML et le CSS de ce
composant, sans te presser sur l'interactivité : tu n'as pas encore vu tout ce qu'il faut pour
la partie « sélectionner une note et l'envoyer ».

**Semaine 11 :** une fois les boucles et les fonctions vues en cours, reviens sur ce projet pour
la partie JavaScript : marquer la note cliquée, gérer le bouton Submit, et basculer entre la
carte de notation et la carte de remerciement. Tu reconnaîtras le même mécanisme que ton menu
mobile (`classList`, `addEventListener`), appliqué à un cas un peu différent.

Rien d'obligatoire dans ce découpage : si tu avances plus vite, tant mieux. L'idée est juste de
ne pas sacrifier la régularité de tes notes de cours pour ce projet, ni l'inverse.

## Ce que tu as dans ce dossier

- `design/` : les maquettes à reproduire. `mobile-design.jpg` et `desktop-design.jpg` montrent
  l'état de départ (aucune note choisie), `active-states.jpg` montre à quoi doit ressembler un
  chiffre survolé ou sélectionné, `mobile-thank-you-state.jpg` et
  `desktop-thank-you-state.jpg` montrent la carte affichée après l'envoi.
- `images/` : l'étoile utilisée à côté de chaque note (`icon-star.svg`), l'illustration de la
  carte de remerciement (`illustration-thank-you.svg`), et un favicon si tu veux tester ce
  composant comme une mini-page à part.
- `style-guide.md` : les couleurs exactes (en HSL, comme tu les as apprises), la police, les
  tailles. Pas de fichier Figma cette fois (réservé aux comptes payants de Frontend Mentor),
  mais tout ce qu'il faut pour reproduire fidèlement la maquette est dans ce fichier et dans les
  images.
- `index.html`, `style.css`, `script.js` : ton point de départ, volontairement vide. À toi de
  construire, comme pour ton portfolio.

## Comment je vais le relire

Comme pour ton portfolio : une revue de code à chaque envoi, avec des captures d'écran et des
comparaisons directes à la maquette. Les mêmes réflexes que tu as construits ces dix dernières
semaines s'appliquent ici à l'identique : mesurer plutôt que deviner, vérifier plusieurs
largeurs d'écran, un nom de classe pour un seul rôle.
