# Portfolio — Garance Guinet

Portfolio personnel de Garance Guinet, conceptrice développeuse d'applications en formation CDA chez Diginamic.

## Stack du site

- HTML5
- CSS3
- JavaScript
- Responsive Design
- GitHub Pages

Le portfolio est volontairement réalisé sans framework frontend.

## Structure

```text
portfolio-garance/
├── assets/
│   ├── css/
│   │   └── style.css
│   ├── docs/
│   │   └── CV_Garance_Guinet.pdf
│   ├── images/
│   │   └── garance-guinet.jpg
│   └── js/
│       └── main.js
├── projects/
│   ├── cinema-jpa.html
│   └── weather-api.html
├── index.html
└── README.md
```

## Projets présentés

- Cinema JPA — Java 21, JPA/Hibernate, MariaDB, JPQL, Maven, JUnit
- Weather API — Node.js, Express, REST, Swagger/OpenAPI, CSV, tests
- ProjectBoost — JavaScript, DOM, LocalStorage
- Atelier Céramique — HTML/CSS, responsive design

## Lancement local

Ouvrir `index.html` avec Live Server dans VS Code.

## Déploiement GitHub Pages

1. Créer un dépôt GitHub nommé `portfolio-garance`.
2. Pousser le projet sur la branche `main`.
3. GitHub → Settings → Pages.
4. Source : `Deploy from a branch`.
5. Branche : `main` / dossier `/root`.
6. L'URL sera normalement :

`https://garanceguinet.github.io/portfolio-garance/`


## Cohérence des informations

Les informations techniques affichées dans le portfolio ont été alignées sur les README et le code des projets :

- Cinema JPA : modèle JPA, import CSV, architecture DAO/service, JPQL et 11 tests.
- Weather API : architecture routes/controllers/services/repositories/models, stockage CSV, Swagger/OpenAPI, CLI et 12 tests.
- Les compétences générales (dont Spring et MongoDB) sont présentées comme compétences de formation/projets, sans les attribuer à un projet qui ne les utilise pas.


## Ajustements V3

- dates de stage affichées précisément : 26/10/2026 → 02/02/2027 ;
- compétences alignées sur le CV et la formation ;
- terminologie « Projet détaillé » utilisée à la place de « Étude de cas » ;
- Cinema JPA : formulation factuelle et lien vers le diagramme UML complet ;
- Weather API : flux principal corrigé en routes → controllers → services → repositories → CSV, avec le modèle Relevé présenté comme support de représentation/validation ;
- parcours professionnel complété ;
- portrait réduit pour mieux équilibrer le hero.
