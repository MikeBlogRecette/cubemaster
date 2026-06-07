# Spécifications du site CubeMaster

## 1. Objectif du site

CubeMaster est un site pédagogique en français autour des cubes de type Rubik's Cube.

Le site doit aider les débutants à :

- résoudre différents cubes étape par étape ;
- comprendre la composition des cubes ;
- apprendre à les nettoyer et les entretenir ;
- progresser avec des contenus simples, visuels et accessibles.

## 2. Cible

Le site s'adresse principalement à :

- des enfants ou adolescents qui débutent ;
- des parents qui cherchent une solution simple à suivre ;
- des débutants curieux ;
- des joueurs qui veulent entretenir ou comprendre leur cube.

## 3. Ton éditorial

Le ton doit être :

- clair ;
- pédagogique ;
- accessible ;
- dynamique ;
- rassurant pour les débutants.

Les contenus doivent expliquer les étapes simplement, sans vocabulaire trop technique au départ.

## 4. Direction artistique

Le design doit être moderne, géométrique et coloré, inspiré de l'univers du cube.

Principes visuels :

- blocs graphiques nets ;
- angles, grilles, cartes et formes cubiques ;
- contraste fort ;
- interface lisible sur mobile et desktop ;
- univers jeune, propre et pédagogique.

Le site ne doit pas utiliser la marque Rubik's comme élément central d'identité visuelle. Le vocabulaire peut rester descriptif : cube 3x3, cube de type Rubik's Cube, solution cube, etc.

## 5. Couleurs principales

| Usage | Couleur | Code hexadécimal |
|---|---:|---:|
| Noir principal | Noir | `#000000` |
| Bleu principal | Bleu | `#2f46b0` |
| Vert principal | Vert | `#2aae34` |

### Recommandation d'utilisation

- `#000000` : textes, header, contrastes forts.
- `#2f46b0` : éléments principaux, boutons, liens, sections importantes.
- `#2aae34` : accents visuels, badges, pictogrammes, états positifs.
- Prévoir un fond clair neutre pour garder une bonne lisibilité.

## 6. Typographie

Typographie principale : **Space Grotesk**.

Recommandation technique :

```html
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Space+Grotesk:wght@400;500;600;700&display=swap" rel="stylesheet">
```

CSS recommandé :

```css
body {
  font-family: 'Space Grotesk', system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif;
}
```

## 7. Arborescence prévue

> Important : les URLs sont normalisées en minuscules pour un rendu plus propre et plus cohérent.  
> Exemple : `/solution/3X3-debutant` devient `/solution/3x3-debutant/`.

### Accueil

| Page | URL recommandée | URL source |
|---|---|---|
| Accueil | `/` | `https://cubemaster.fr/hp` |

### Solution

| Catégorie | Sous-catégorie | URL recommandée | URL source |
|---|---|---|---|
| Solution | 2x2 | `/solution/2x2/` | `https://cubemaster.fr/solution/2x2` |
| Solution | 3x3 débutant | `/solution/3x3-debutant/` | `https://cubemaster.fr/solution/3X3-debutant` |
| Solution | 4x4 | `/solution/4x4/` | `https://cubemaster.fr/solution/4X4` |
| Solution | 5x5 | `/solution/5x5/` | `https://cubemaster.fr/solution/5X5` |
| Solution | Pyramix | `/solution/pyramix/` | `https://cubemaster.fr/solution/pyramix` |
| Solution | Mégaminx | `/solution/megaminx/` | `https://cubemaster.fr/solution/megaminx` |
| Solution | Gear Cube | `/solution/gearcube/` | `https://cubemaster.fr/solution/gearcube` |

### Nettoyage

| Catégorie | Sous-catégorie | URL recommandée | URL source |
|---|---|---|---|
| Nettoyage | 2x2 | `/nettoyage/2x2/` | `https://cubemaster.fr/nettoyage/2x2` |
| Nettoyage | 3x3 | `/nettoyage/3x3/` | `https://cubemaster.fr/nettoyage/3X3` |
| Nettoyage | 4x4 | `/nettoyage/4x4/` | `https://cubemaster.fr/nettoyage/4X4` |
| Nettoyage | 5x5 | `/nettoyage/5x5/` | `https://cubemaster.fr/nettoyage/5X5` |
| Nettoyage | Pyramix | `/nettoyage/pyramix/` | `https://cubemaster.fr/nettoyage/pyramix` |
| Nettoyage | Mégaminx | `/nettoyage/megaminx/` | `https://cubemaster.fr/nettoyage/megaminx` |
| Nettoyage | Gear Cube | `/nettoyage/gearcube/` | `https://cubemaster.fr/nettoyage/gearcube` |

### Composition

| Catégorie | Sous-catégorie | URL recommandée | URL source |
|---|---|---|---|
| Composition | 2x2 | `/composition/2x2/` | `https://cubemaster.fr/composition/2x2` |
| Composition | 3x3 | `/composition/3x3/` | `https://cubemaster.fr/composition/3X3` |
| Composition | 4x4 | `/composition/4x4/` | `https://cubemaster.fr/composition/4X4` |
| Composition | 5x5 | `/composition/5x5/` | `https://cubemaster.fr/composition/5X5` |
| Composition | Pyramix | `/composition/pyramix/` | `https://cubemaster.fr/composition/pyramix` |
| Composition | Mégaminx | `/composition/megaminx/` | `https://cubemaster.fr/composition/megaminx` |
| Composition | Gear Cube | `/composition/gearcube/` | `https://cubemaster.fr/composition/gearcube` |

## 8. Navigation principale recommandée

Navigation de premier niveau :

- Accueil
- Solutions
- Nettoyage
- Composition

Navigation secondaire possible :

- 2x2
- 3x3
- 4x4
- 5x5
- Pyramix
- Mégaminx
- Gear Cube

## 9. Structure type d'une page

Chaque page peut suivre cette logique :

1. **Hero / slider**
   - titre clair ;
   - promesse de la page ;
   - visuel ou bloc graphique.

2. **Introduction**
   - explication simple du sujet ;
   - niveau de difficulté ;
   - ce que le visiteur va apprendre.

3. **Contenu principal**
   - étapes détaillées ;
   - explications courtes ;
   - blocs visuels ;
   - conseils pratiques.

4. **Photos**
   - visuels du cube ;
   - étapes de démontage, nettoyage ou résolution ;
   - schémas si nécessaire.

5. **Vidéo**
   - vidéo tutorielle intégrée si disponible ;
   - complément visuel à l'explication texte.

6. **FAQ courte**
   - questions fréquentes ;
   - réponses directes.

## 10. Contraintes techniques

Le site doit rester simple pour le lancement :

- site statique ;
- HTML, CSS et JavaScript simple ;
- pas de framework ;
- pas de build step ;
- compatible Netlify ;
- `index.html` à la racine du repo ;
- structure de fichiers claire ;
- code lisible et facile à reprendre.

Structure de départ recommandée :

```text
cubemaster/
├── README.md
├── index.html
├── style.css
└── specs-cubemaster.md
```

Structure évolutive possible :

```text
cubemaster/
├── README.md
├── index.html
├── style.css
├── script.js
├── assets/
│   ├── images/
│   └── icons/
├── solution/
│   ├── 2x2.html
│   ├── 3x3-debutant.html
│   ├── 4x4.html
│   ├── 5x5.html
│   ├── pyramix.html
│   ├── megaminx.html
│   └── gearcube.html
├── nettoyage/
│   ├── 2x2.html
│   ├── 3x3.html
│   ├── 4x4.html
│   ├── 5x5.html
│   ├── pyramix.html
│   ├── megaminx.html
│   └── gearcube.html
└── composition/
    ├── 2x2.html
    ├── 3x3.html
    ├── 4x4.html
    ├── 5x5.html
    ├── pyramix.html
    ├── megaminx.html
    └── gearcube.html
```

## 11. SEO

Chaque page doit prévoir :

- une balise `<title>` unique ;
- une meta description unique ;
- un seul H1 ;
- une structure H2/H3 claire ;
- une URL courte, descriptive et en minuscules ;
- un contenu utile et pédagogique ;
- des liens internes vers les pages proches.

### Exemples de title

- `Solution cube 3x3 débutant : méthode simple | CubeMaster`
- `Nettoyer un cube 3x3 : démontage et entretien | CubeMaster`
- `Composition d'un cube 3x3 : pièces et mécanisme | CubeMaster`

## 12. Première version à produire

Pour la première version, créer uniquement la page d'accueil.

La page d'accueil doit présenter :

- le nom du site : **CubeMaster** ;
- une accroche pédagogique ;
- les trois grandes familles de contenus : Solutions, Nettoyage, Composition ;
- les principaux cubes traités : 2x2, 3x3, 4x4, 5x5, Pyramix, Mégaminx, Gear Cube ;
- une navigation claire ;
- un design moderne, géométrique et coloré.

Ne pas encore créer toutes les pages secondaires. Les liens peuvent pointer vers les futures URLs.

## 13. Brief Codex prêt à l'emploi

```text
Tu travailles sur le repo cubemaster.

Contexte :
- Site statique hébergé sur Netlify.
- Nom de domaine : cubemaster.fr.
- Le fichier index.html doit rester à la racine.
- Pas de framework.
- Pas de build step.
- Le site doit rester en HTML/CSS/JS simple.
- Respecter les spécifications présentes dans specs-cubemaster.md.

Objectif :
Créer une première vraie page d'accueil pour CubeMaster, un site pédagogique en français autour des cubes de type Rubik's Cube : solutions, nettoyage, composition et progression.

À faire :
1. Améliorer index.html.
2. Améliorer style.css.
3. Utiliser la typo Space Grotesk via Google Fonts.
4. Utiliser les couleurs principales : noir #000000, bleu #2f46b0, vert #2aae34.
5. Créer une navigation principale : Accueil, Solutions, Nettoyage, Composition.
6. Créer un hero moderne avec le titre CubeMaster et une accroche claire.
7. Créer 3 blocs principaux : Solutions, Nettoyage, Composition.
8. Mettre en avant les cubes : 2x2, 3x3, 4x4, 5x5, Pyramix, Mégaminx, Gear Cube.
9. Donner une direction graphique moderne, géométrique et colorée.
10. Garder une excellente lisibilité mobile et desktop.
11. Ne pas créer encore toutes les pages secondaires.
12. Ne pas déplacer index.html.
13. Ne pas ajouter de dépendances.
```
