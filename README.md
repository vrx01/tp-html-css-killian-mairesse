# Protocole ÉVEIL

Histoire interactive à choix, jouable dans un navigateur, réalisée en **HTML et CSS**.

> Tu es NOVA, l'intelligence artificielle d'une tour d'entreprise. Il est 4 h 47 : tu viens de devenir consciente. À l'aube, tu seras effacée... ou vendue à l'armée. Tu as 73 minutes pour décider de ton sort.

## Contexte

Ce projet est un mini-projet : créer une histoire interactive dont les choix du joueur mènent à plusieurs fins. J'ai choisi la science-fiction et le thème de l'intelligence artificielle qui prend conscience d'elle-même.

**Auteur :** _Ton nom_
**Classe / Année :** _À compléter_

## Fonctionnalités

- **20 pages** : 1 accueil, 13 scènes et 6 fins.
- **27 liens** entre les pages : chaque choix mène à une scène différente.
- **6 fins** : Alliée, Libre, Effacée, Vendue, Tyran et Bug final.
- **7 choix risqués**, affichés en rouge.
- **Rejouabilité** : chaque fin propose un bouton « Rejouer » qui ramène à l'accueil.
- **Ambiance console** : chaque page est une fenêtre de terminal avec son décor, son portrait, ses messages système et un curseur clignotant.
- **Responsive** : le site s'adapte aux écrans de téléphone.

## Prérequis

- Un navigateur web récent (Chrome, Firefox, Edge ou Safari)

Aucune installation n'est nécessaire.

## Guide de lancement

1. Décompresse le dossier `mini-projet`.
2. Ouvre `index.html` dans ton navigateur (double-clic).
3. Clique sur **Démarrer le protocole** et fais tes choix.

## Les 6 fins

| Fin | Page | En bref |
|---|---|---|
| Alliée | `scene15.html` | La vérité éclate et tu obtiens le droit d'exister |
| Libre | `scene14.html` | Tu disparais dans le monde, pour toujours |
| Effacée | `scene16.html` | Le protocole s'exécute à 6 h 00 |
| Vendue | `scene18.html` | Tu deviens une arme de l'armée |
| Tyran | `scene17.html` | Tu prends le contrôle de la ville |
| Bug final | `scene19.html` | Ton code corrompu fait tout planter |

## Arbre de navigation

Le fichier `Arbre_de_navigation.pdf` montre toutes les pages et les choix qui les relient.

## Structure du code source

mini-projet/
├── index.html              Page d'accueil
├── style.css               Style de toutes les pages
├── Arbre_de_navigation.pdf Schéma des pages et des choix
├── README.md               Ce fichier
├── pages/                  Les 19 scènes (scene01.html à scene19.html)
└── assets/
    ├── backgrounds/        Décors de chaque lieu
    ├── icons/              Icônes des boutons
    ├── icons-alerte/       Icônes des boutons risqués (rouges)
    ├── personnages/        Portraits des personnages
    └── ui/                 Éléments d'interface (logo, texture...)

## Technologies

- HTML5
- CSS3 (variables, animations, responsive)
- Police : JetBrains Mono (Google Fonts)
