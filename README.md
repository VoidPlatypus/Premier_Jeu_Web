# Protocole Awakening

> *« Analyste Rang Stagiaire — Gravissez les couches du réseau. Devenez l'Élite, ou soyez effacé. »*

Protocole Awakening est un jeu narratif interactif en HTML/CSS, inspiré de l'univers des *Solo Leveling* / RPG, dans lequel tu incarnes un analyste de SOC (Security Operations Center). Une nuit, un malware inconnu infiltre le réseau de ton entreprise et active un mystérieux « Système » qui te propose de monter en puissance… ou d'être effacé.

Le jeu a une vocation **pédagogique** : à travers l'histoire, tu progresses étage par étage (les couches du réseau) et tu apprends des notions de cybersécurité et de réseaux.

---

## ✨ Fonctionnalités

- 📖 **Narration interactive** : scènes à choix menant à différentes pages
- 🧑‍💻 **Fiche de personnage** : rang, niveau, XP, points de vie et compétences
- 🎨 **Ambiance cyberpunk / terminal** : police monospace, néons vert et rose, effets de lueur
- ✨ **Animations CSS** : respiration du personnage, lueur d'écran, message clignotant
- 📱 **Responsive** : la mise en page s'adapte aux écrans de moins de 1300 px
- ♿ **Accessibilité** : respect de `prefers-reduced-motion` (animations désactivées si demandé)

---

## 🗂️ Structure du projet
protocole-awakening/
├── index.html            # Page d'accueil (introduction)
├── style.css             # Feuille de style principale
├── README.md
└── Pages/
    ├── étage1.html       # Premier niveau
    └── image/
        ├── background.png
        └── FLUX-2026-10-03-09-39-59.png   # Avatar du personnage

---

## 🚀 Installation et lancement

Aucune dépendance, aucun build : c'est du HTML/CSS pur.

1. **Cloner le dépôt**
   ```bash
   git clone https://github.com/[ton-pseudo]/protocole-awakening.git
   cd protocole-awakening

Ouvrir le projet
Double-clique sur index.html, ou
Utilise l'extension Live Server de VS Code pour un rechargement automatique.




🎮 Comment jouer

Lis l'introduction sur la page d'accueil.
Clique sur « Accepter le protocole » pour commencer ta formation.
Fais tes choix à chaque étage et surveille ta fiche de personnage :

Copier le tableau


Statistique
Description



Rang
Ton grade actuel (commence à Stagiaire)


Niveau
Ton niveau de progression


XP
Points d'expérience (0/100 au départ)


Vie
5 cœurs ❤️ : perds-les tous et tu es « effacé »


Compétence
Capacités débloquées au fil de l'aventure



🛠️ Technologies utilisées

HTML5
CSS3 (Grid, Flexbox, animations @keyframes, media queries)


🎨 Palette de couleurs
Copier le tableau


Couleur
Code
Usage



Vert menthe
#c8f5d8 / #7affc9
Texte principal, accents


Rose néon
#ff6fc9 / #ff4fa3
Messages du Système, libellés


Rouge
#ff5577
Alertes


Bleu cyan
#4fd8ff
Bouton d'action


Noir bleuté
#0a0e14
Fond



🗺️ Roadmap

 Page d'introduction
 Fiche de personnage
 Animations du personnage
 Étage 1 – [thème, ex : couche physique]
 Étages suivants (modèle OSI ?)
 Système de vie et de game over
 Sauvegarde de la progression (JavaScript / localStorage)
 Gain d'XP et montée de niveau dynamiques


📝 Crédits

Auteur : [Ton nom]
Illustrations : généré avec FLUX (à confirmer / adapter)
Police : Courier New# Premier_Jeu_Web
