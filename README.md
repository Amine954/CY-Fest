# 🎪 CY'FEST

> Application de gestion de festival — organisez vos scènes, réservez vos places.

CY'FEST est un projet de gestion de festival qui permet aux **organisateurs** de gérer les différentes scènes du festival, et aux **festivaliers** de réserver et de payer leurs places pour les concerts.

---

## 📋 Sommaire

- [Prérequis](#-prérequis)
- [Introduction](#-introduction)
- [Fonctionnement](#-fonctionnement)
  - [Côté Manager](#-côté-manager)
  - [Côté Festivalier](#-côté-festivalier)

---

## ⚙️ Prérequis

Pour le bon fonctionnement de CY'FEST, il est nécessaire de disposer de :

- La bibliothèque **NCurses**
- Un terminal **Linux**

---

## 🎬 Introduction

CY'FEST est une application de gestion de festival. Elle offre deux expériences distinctes :

- **Les organisateurs** gèrent les différentes scènes du festival CY'FEST.
- **Les festivaliers** réservent et paient leurs places pour les concerts de leur choix.

---

## 🚀 Fonctionnement

### 🎤 Côté Manager

Le Manager peut créer différentes salles de concert en renseignant les informations souhaitées :

- Le **nombre de salles** à créer
- Le **nom de la salle**
- Le **nom de l'artiste** performant
- Les **horaires** de début et de fin du concert
- Le **nombre de rangées** de la salle
- Le **nombre de sièges** par rangée
- L'**emplacement des catégories**, sachant que :
  - La **catégorie A** se trouve devant la scène
  - La **catégorie B** au milieu
  - La **catégorie C** au fond de la salle
- Le **prix** de chacune des catégories

Le Manager peut également ajouter une **fosse**, qui remplace la catégorie A en **multipliant par deux** son nombre de places initial.

Une fois les salles créées, le Manager peut :

- **Naviguer** entre les différentes salles
- **Modifier** une salle existante
- **Afficher les informations** d'une salle choisie, notamment :
  - Le **ratio des sièges**
  - Le **chiffre d'affaires potentiel**
  - Le **chiffre d'affaires actuel**
  - Le **nombre de sièges disponibles**
  - Toutes les informations saisies lors de la création
- **Afficher un plan détaillé** de chaque salle

> 💡 Ces informations détaillées sont réservées au Manager.

### 🎟️ Côté Festivalier

Une fois les salles créées, les festivaliers peuvent réserver leurs places. Ils peuvent :

- **Choisir le concert** en saisissant le numéro inscrit à côté du nom de l'artiste
- **Choisir le nombre de places** à réserver
- **Choisir la catégorie** ainsi que son emplacement

> 🎓 Une **réduction de 20 %** est appliquée pour tout étudiant réservant une place.

En cas d'imprévu, il est possible de se faire **rembourser**. Il suffit d'avoir préalablement noté l'emplacement de la place à supprimer.

---

**Bon festival ;)**
