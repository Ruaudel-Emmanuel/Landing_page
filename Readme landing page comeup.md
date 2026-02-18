<img src="https://r2cdn.perplexity.ai/pplx-full-logo-primary-dark%402x.png" style="height:64px;margin-right:32px"/>

# Créer un readme qui me servira de document de base pour créer les landing page pour mes clients comeup. Il faut qu'un llm le comprenne bien pour lui faciliter le travail

Voici un modèle de `README.md` que tu pourras déposer à la racine de chaque projet de landing page ComeUp, pensé pour être très clair pour un LLM et pour toi. Il est rédigé pour décrire ton service “landing page HTML/CSS assumée IA” tel que dans ton doc.[^1]

***

# README – Génération de landing page HTML/CSS pour clients ComeUp

## 1. Objectif de ce dépôt

Ce dépôt sert de **base de travail** pour générer une landing page statique pour un client ComeUp.[^1]
Il doit être facilement compréhensible par un LLM (Perplexity, GPT, etc.) afin de l’aider à :[^1]

- Comprendre le contexte du service proposé au client.[^1]
- Structurer le contenu marketing de la landing page.[^1]
- Produire du code HTML5/CSS propre, réutilisable et prêt à déployer sur un hébergement statique (Netlify, Vercel, o2switch, etc.).[^1]

***

## 2. Positionnement du service

Le service correspond à :[^1]

- Création d’une **landing page HTML/CSS** statique, moderne et responsive.[^1]
- Code **assumé IA** : génération assistée par IA, mais relue et validée par un développeur humain.[^1]
- Page **complètement codée, testée dans le navigateur**, prête à être mise en ligne sur un hébergement statique.[^1]
- Code pensé pour la **réutilisation** : classes CSS cohérentes, sections réplicables, structure sémantique utile pour le SEO de base.[^1]

Le LLM doit **respecter ce positionnement** et ne pas proposer de CMS (WordPress, etc.) ni de fonctionnalités backend complexes.[^1]

***

## 3. Structure générale attendue de la page

La landing page est une **page unique** (`index.html`) structurée en sections claires :[^1]

Sections minimales pour le pack de base :

1. Hero (accroche principale, promesse, CTA).[^1]
2. Bénéfices / avantages principaux.[^1]
3. Preuves / réassurance (éléments de confiance, mini témoignages, logos, chiffres, etc. si disponibles).[^1]
4. Section contact / appel à l’action (formulaire ou lien vers email / ComeUp / autre).[^1]
5. Footer simple (mentions, lien vers profils, etc.).[^1]

Sections optionnelles (packs supérieurs) :

- FAQ.[^1]
- Témoignages.[^1]
- Galerie / portfolio / réalisations.[^1]
- Timeline / étapes.[^1]
- Bloc “À propos” plus détaillé.[^1]

***

## 4. Conventions techniques pour le LLM

### 4.1 HTML

```
- Utiliser du **HTML5 sémantique** (`<header>`, `<main>`, `<section>`, `<footer>`, etc.).[^1]
```

- Toujours définir :
    - Une balise `<title>` claire.[^1]
    - Des balises `<meta>` de base (description, charset, viewport).[^1]
    - Une hiérarchie de titres cohérente (`h1` unique, puis `h2`, `h3` si besoin).[^1]
- Ne pas intégrer de backend (PHP, Node, etc.).[^1]


### 4.2 CSS

- Un fichier `style.css` séparé, chargé dans le `<head>`.[^1]
- Classes CSS **cohérentes et réutilisables** (exemples : `.section`, `.section--hero`, `.btn`, `.btn--primary`, `.container`, etc.).[^1]
- Mise en page responsive simple (flexbox, éventuellement grid) sans framework externe (pas de Bootstrap, Tailwind par défaut).[^1]


### 4.3 JavaScript

- Optionnel, uniquement pour de **petites interactions** (scroll doux, petites animations, etc.).[^1]
- Pas de dépendance lourde (pas de React/Vue/Angular).[^1]

***

## 5. Packs et variations possibles

Le LLM doit adapter la complexité de la page selon le **pack** choisi pour le client.[^1]

### Pack de base : “Landing page simple”

- 1 page HTML statique.[^1]
- 3–4 sections max (hero, bénéfices, contact/CTA, footer).[^1]
- Design simple mais moderne, responsive, peu ou pas de JS.[^1]


### Options payantes (packs supérieurs)

Selon ce qui est commandé sur ComeUp, le LLM peut ajouter :[^1]

- Plus de sections (FAQ, témoignages, galerie, etc.).[^1]
- Version “optimisée conversion” : texte et structure orientés marketing (titre plus accrocheur, sections orientées bénéfices, CTA multiples).[^1]
- Intégration de formulaires (Netlify Forms, Formspree, ou simple `<form>` prêt à connecter).[^1]
- Micro-fonctionnalités JS (scroll vers ancre, petits effets au survol, etc.).[^1]
- Aide au déploiement (texte explicatif, mini tutoriel à intégrer dans un fichier séparé ou dans la documentation pour le client).[^1]

***

## 6. Livrables standards du projet

Le dépôt doit au minimum contenir :[^1]

- `index.html` : page HTML principale.[^1]
- `style.css` : styles globaux.[^1]
- `README.md` : ce fichier, éventuellement enrichi de détails spécifiques au client.[^1]

Selon les options :

- `script.js` : micro-interactions.[^1]
- `assets/` : images, logos, icônes, etc.[^1]
- `deploy-notes.md` : instructions de déploiement pour le client (Netlify, Vercel, o2switch).[^1]

***

## 7. Brief client à fournir au LLM

Avant de générer la landing, ce README doit être accompagné d’un **brief client** que tu ajouteras soit dans ce fichier (sous cette section), soit dans un fichier séparé (`brief-client.md`).[^1]

Le brief doit contenir, autant que possible :

- Secteur d’activité du client.
- Offre principale (produit, service) et promesse clé.
- Cible (type de clients, localisation, niveau de conscience du problème).
- Ton à adopter (pro, décontracté, technique, rassurant, etc.).
- Objectif principal de la landing (capturer des leads, prise de rendez-vous, achat direct, etc.).
- Éléments de preuve disponibles (avis clients, chiffres, logos partenaires).
- Packs/options ComeUp choisis (pour que le LLM sache quelles sections/complexités activer).

***

## 8. Attentes de qualité

Le LLM doit viser :[^1]

- Un code **clair, lisible, commenté avec parcimonie** (uniquement si utile pour le client ou pour toi).[^1]
- Une structure logique, prête à dupliquer des sections si le client étend sa landing plus tard.[^1]
- Une page testable facilement dans un navigateur moderne, sans configuration complexe.[^1]

***

## 9. Checklist pour génération par LLM

Avant de valider la génération, le LLM doit vérifier :

- [ ] La page contient toutes les sections prévues pour le pack choisi.[^1]
- [ ] Le HTML est valide et sémantique (au minimum pas d’erreurs flagrantes).[^1]
- [ ] Les textes sont cohérents avec le brief client et adaptés au public cible.[^1]
- [ ] Les CTA sont clairs et visibles.[^1]
- [ ] La structure des fichiers respecte ce README.[^1]

***

Si tu veux, je peux te proposer une **version alternative plus courte** spécialement optimisée pour être collée en “system prompt” d’un LLM quand tu lui demandes de générer la page.

<div align="center">⁂</div>

[^1]: Service-comeup-landing-page.md

