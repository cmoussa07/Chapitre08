# BookShelf - Gestion de bibliothèque

## Description
Application Java de gestion d'une bibliothèque permettant de :
- Ajouter des livres
- Trier les livres par titre (ordre naturel)
- Trier les livres selon un critère personnalisé (Comparator)
- Trier les livres par date de publication

## Technologies utilisées
- Java 21
- JUnit 5
- AssertJ

## Structure du proje
src/
├── bookstoread/
│ ├── Book.java
│ ├── BookShelf.java
│ └── BookShelfSpec.java
└── README.md

## Fonctionnalités

### 1. Gestion des livres
- Ajout de livres dans la bibliothèque
- Retourne une liste immuable des livres

### 2. Tris disponibles
- **Tri par titre** : ordre alphabétique naturel
- **Tri personnalisé** : utilisation d'un Comparator
- **Tri par date de publication** : du plus ancien au plus récent

### 3. Tests unitaires
Les tests couvrent les cas suivants :
- Bibliothèque vide à l'initialisation
- Ajout de plusieurs livres
- Immutabilité de la liste retournée
- Tri alphabétique par titre
- Tri personnalisé (ordre décroissant)
- Tri par date de publication

## Exécution des tests

### Avec IntelliJ IDEA
1. Ouvrir le projet
2. Faire un clic droit sur `BookShelfSpec.java`
3. Sélectionner `Run 'BookShelfSpec'
