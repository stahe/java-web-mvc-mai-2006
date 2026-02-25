# Programmation Web MVC en Java

Ce dépôt contient des ressources et des exercices pour découvrir les bases du développement web en Java, en utilisant les **servlets** et les **pages JSP**.

> [!TIP]
> **Accéder au cours complet :** [https://stahe.github.io/java-web-mvc-mai-2006/](https://stahe.github.io/java-web-mvc-mai-2006/)

---

## 📖 Présentation

L'objectif de ce support est d'acquérir les concepts fondamentaux de la programmation web Java à travers une architecture **MVC 3-tier**. Ce document s'appuie sur l'article de janvier 2005 « Développement web en Java avec Eclipse et Tomcat », en y ajoutant :

* L'utilisation du plugin **WTP d'Eclipse**.


* Une structure orientée **architecture 3-tier**.


* Un exemple concret utilisant un **SGBD**.



## 🏗️ Architecture de l'application

Le projet suit une structure en trois couches distinctes pour assurer la modularité et la stabilité du code:

| Couche | Description |
| --- | --- |
| **Couche Web [web]** | Interface permettant à l'utilisateur de piloter l'application et de recevoir des informations.

 |
| **Couche Métier [metier]** | Contient les algorithmes métier. Indépendante de l'interface (web, console, etc.), elle est la couche la plus stable.

 |
| **Couche d'Accès aux Données [dao]** | Gère l'accès aux données persistantes (SGBD) ou externes (capteurs, réseau).

 |

## 🚀 Méthodes d'apprentissage

Plusieurs approches sont possibles pour aborder ce contenu, de la plus rapide à la plus efficace :

1. 
**Approche Expérimentée :** Installation des outils et test direct des codes téléchargés (réservé aux développeurs familiers avec Eclipse/WTP).


2. **Approche Rapide :** Copier/coller les codes en suivant le document. Permet d'avancer vite, mais certains concepts peuvent rester "magiques".


3. 
**Approche Guidée :** Identique à la méthode 2, mais en consultant le document de référence `[ref1]` (Introduction à la programmation web en Java) dès que conseillé.


4. **Approche Recommandée :** Saisir manuellement l'intégralité du code en lisant attentivement. C'est la méthode la plus efficace pour comprendre la logique et corriger ses propres erreurs de syntaxe.

