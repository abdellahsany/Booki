## Booki

<p align="center">
  <img src="./assets/icônes/booki_welcome.png" alt="Page d’accueil Booki" width="100%">
</p>

---

### 📑 Table des matières

* [Mission](#mission)
* [Objectifs](#objectifs)
* [Points forts de l’interface](#points-forts-interface)
* [Stacks techniques](#stacks-techniques)
* [Fonctionnalités et bonnes pratiques](#fonctionnalites-pratiques)
* [Aspects techniques & automatisation](#aspects-techniques-automatisation)
* [Points techniques spécifiques](#points-techniques-specifiques)

---

<a id="mission"></a>

### 🎯 Mission

Développer la page d’accueil du site **Booki**, une agence de voyage spécialisée dans les hébergements en ligne. L’objectif est de transformer une maquette Figma en un site web complet, conforme aux standards du W3C, et offrant une expérience entièrement responsive sur desktop, tablette et mobile.

---

<a id="objectifs"></a>

### 🧭 Objectifs

* Intégrer une interface moderne avec **HTML5 & CSS3**
* Respecter la **charte graphique** et l’accessibilité
* Mettre en place un design **desktop-first** puis adapté tablette et mobile
* Assurer une compatibilité avec les navigateurs récents (Chrome, Firefox)

---

<a id="points-forts-interface"></a>

### ✨ Points forts de l’interface

* Barre de navigation avec liens ancrés (**Hébergements**, **Activités**)
* Champ de recherche intégré dans un **formulaire valide W3C**
* **Cartes cliquables** (hébergements et activités)
* **Filtres interactifs** (effet hover, non fonctionnels)
* Interface testée et optimisée pour **desktop, tablette et mobile**

---

<a id="stacks-techniques"></a>

### 🛠️ Stacks techniques

| Outils                                                            | Fonctions                            |
| :---------------------------------------------------------------- | :----------------------------------- |
| <span style="color:#E34F26; font-weight:bold">HTML5</span>        | Structure et balisage sémantique     |
| <span style="color:#1572B6; font-weight:bold">CSS3</span>         | Mise en page responsive avec Flexbox |
| <span style="color:#2C9ACD; font-weight:bold">Font Awesome</span> | Icônes via CDN                       |
| <span style="color:#000000; font-weight:bold">GitHub Pages</span> | Hébergement et déploiement           |
| <span style="color:#2C9ACD; font-weight:bold">W3C</span>          | Validation et conformité HTML/CSS    |
| <span style="color:#0065FC; font-weight:bold">UI Design</span>    | Respect de la charte graphique       |
| <span style="color:#4CAF50; font-weight:bold">Responsive</span>   | Breakpoints 992px et 768px           |

---

<a id="fonctionnalites-pratiques"></a>

### ✅ Fonctionnalités et bonnes pratiques

* Recherche d’hébergements via un **champ de saisie éditable** (non fonctionnel)
* Hébergements et activités sous forme de **cartes entières cliquables**
* Filtres dynamiques au **survol (hover)**
* Navigation interne avec liens d’ancrage vers les sections principales
* Design **desktop-first**, adapté en tablette et mobile via Media Queries

---

<a id="aspects-techniques-automatisation"></a>

### ⚙️ Aspects techniques & automatisation

* Intégration **desktop first**, puis adaptation tablette et mobile
* Utilisation de **Flexbox** (pas de Grid, pas de framework type Bootstrap/Tailwind)
* Pas de préprocesseurs CSS (Sass, Less)
* Organisation claire : `index.html` + `style.css`
* Gestion optimisée des images (tailles multiples selon résolution)
* Code validé aux **outils de validation W3C**

---

<a id="points-techniques-specifiques"></a>

### 🔍 Points techniques spécifiques

* Couleurs de la charte :
* Bleu principal `#0065FC`
* Bleu clair `#DEEBFF`
* Gris fond `#F2F2F2`
* Texte toujours lisible sur mobile (pas d’éléments coupés)
* Icônes intégrées via **Font Awesome (CDN)**
* Unités utilisées : **px et %** (pas de rem/em)
