# cours6035LivreNum
Ici tous les documents pour créer la maquette intéractive du cours.

Le seul grand avantage d'utiliser reveal au lieu de GgSlides c'est pouvoir utiliser bootstrap pour créer du responsive. DONC si c'est très compliqué, ça ne vaut pas la peine.

Sur ce dossier tu trouves les maquettes visuelles crées en Illustrator et mon test sur reveal.

La dernière version de la maquette c'est la 2.1. Le résultat sur ordinateur ou tablette ressemblera aux slides que j'ai developpé sur google :
https://docs.google.com/presentation/d/18OQydbfWAIh85ECRKjFjEuidtOzmUUKd7CBtUeEVXsQ/edit?usp=sharing

La version de maquette que j'ai crée en Reveal.js c'est Maquette 1.3. Même si, suite à des demandes de Renée, la maquette  a variée, les souci de codes pour moi restent similaires. Les détails :

*Simple*

- Faire des images à ras-board d'une demi page en `cover` et pas en `contain`. Soit en general, pouvoir placer les contenus relatifs au bord de l'écran.

- Faire un keyword highlight au lieu de avec background-color avec un background-image. En ayant une image plus grande que le mot mais sans modifier l'apparence du line-height ni l'espacement avec le mot suivant.

*Moyen*

- Barre d'avancement personnalisée.

**Compliqué** ?
- *Responsive avec bootstrap* : Que mes 2-3 colonnes deviennent une seule colonne en scroll vers le bas lorsque j'utilise un mobile.

En fait ce qui définit si aller sur reveal vaut la peine c'est la partie de responsive avec bootstrap. Si ça c'est trop complexe alors les avantages sur Reveal.js par rapport à GoogleSlides seront trop faibles. 

La partie que j'ai modifié se trouve principalement dans le dossier

cours6035LivreNum/Maquette_1.3_TestReveal/index.html
cours6035LivreNum/Maquette_1.3_TestReveal/css/theme/simple.css

****
My classes
****

