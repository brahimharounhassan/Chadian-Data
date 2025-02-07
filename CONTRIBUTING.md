# Guide de contribution

Merci pour votre intérêt à enrichir ce dépôt de données ouvertes sur le Tchad. Votre contribution, qu'il s'agisse d'ajouter de nouvelles données, d'améliorer celles existantes ou de corriger des erreurs, est essentielle pour faire évoluer ce projet et renforcer la communauté.

---

## Table des matières

- [Introduction](#introduction)
- [Processus de contribution](#processus-de-contribution)
  - [1. Cloner ce repository en local](#2-cloner-ce-repository-en-local)
  - [2. Ajouter ou mettre à jour les données](#3-ajouter-ou-mettre-à-jour-les-données)
  - [3. Documenter vos ajouts](#4-documenter-vos-ajouts)
  - [4. Committer et pousser vos modifications](#5-committer-et-pousser-vos-modifications)
  - [5. Ouvrir une Pull Request](#6-ouvrir-une-pull-request)
- [Bonnes pratiques](#bonnes-pratiques)
- [Format et structuration des données](#format-et-structuration-des-données)
- [Questions et support](#questions-et-support)
- [Licence](#licence)

---

## Introduction

Ce dépôt centralise des données ouvertes issues de divers secteurs du Tchad, tels que l'agriculture, la santé, l'éducation, l'énergie, et bien d'autres. Pour garantir la qualité, la cohérence et la facilité d'utilisation de ces informations, nous vous invitons à suivre les recommandations présentées dans ce guide de contribution.

---

## Processus de contribution

### 1. Cloner ce repository en local

- Clonez ce repository sur votre machine locale à l'aide de la commande suivante :

  ```bash
  git clone https://github.com/Chad-AI-Network/Chadain-Data.git
  ```

### 2. Ajouter ou mettre à jour les données
- Rendez-vous dans le dossier correspondant au secteur concerné (par exemple, `Agriculture/`, `Santé/`, `Éducation/`, etc.).
- Ajoutez de nouveaux fichiers ou mettez à jour les fichiers existants tout en respectant la structure du dépôt.
- Assurez-vous que les données ajoutées sont fiables et formatées de manière cohérente.

### 3. Documenter vos ajouts

- Pour chaque contribution, ajoutez un fichier de métadonnées dans le dossier concerné (par ex `metadata_agriculture_2025.txt`). Ce document doit détailler :
  - La provenance des données.
  - La méthode de collecte.
  - La date de mise à jour ou de création.
  - Toute information contextuelle utile à leur interprétation.

### 4. Committer et pousser vos modifications

- Une fois vos modifications effectuées, effectuez un commit avec un message clair et descriptif et n'oubliez pas de créer une `nouvelle branche` avec la commande `git chekout -b <nom de votre branche>`. Par exemple :

  ```bash
  git add .
  git commit -m "Ajout des données du secteur santé - mise à jour du 05/02/2025"
  git push origin votre-branche-de-modification
  ```

### 5. Ouvrir une Pull Request

- Rendez-vous sur votre dépôt GitHub et ouvrez une **Pull Request** vers le dépôt original si vous avez créer un `Fork`. Par ex:

  ```bash
  https://github.com/Chad-AI-Network/Chadain-Data/pulls
  ```
- Décrivez en détail les modifications apportées et leur justification.
- Un membre de l'équipe examinera votre contribution et pourra vous demander des ajustements si nécessaire.

---

## Bonnes pratiques

- **Respect de la structure :** Conservez la structure des dossiers existante ou proposez des ajouts en cohérence avec l’organisation du dépôt.
- **Clarté et précision :** Rédigez des descriptions détaillées pour faciliter la compréhension et l’utilisation des données.
- **Qualité des données :** Vérifiez l'exactitude et la pertinence des données avant de soumettre votre contribution.
- **Tests et validation :** Si vous apportez des modifications sur des scripts ou des outils d'analyse, assurez-vous qu'ils fonctionnent correctement.

---

## Format et structuration des données

- **Formats recommandés :**  
  - Pour les données tabulaires : CSV, JSON, XLSX.  
  - Pour les documents ou rapports : PDF, DOCX, Markdown.
- **Nomenclature :** Utilisez des noms de fichiers explicites et uniformes (ex. : `sante_statistiques_2025.csv`).
- **Documentation Interne :** Chaque dossier doit idéalement contenir un fichier `README.md` expliquant la provenance et le contenu des données.

---

## Questions et support

Si vous avez des questions ou avez besoin d'assistance concernant votre contribution :

- **Ouvrez une issue :** [Créez une nouvelle issue](https://github.com/Chad-AI-Network/Chadain-Data/issues) pour poser vos questions ou signaler des problèmes.
- **Contactez l’équipe :** Vous pouvez également contacter l'équipe via les moyens de communication indiqués sur le dépôt principal ou via directement [Discussions](https://github.com/orgs/Chad-AI-Network/discussions)

---

## Licence

En contribuant à ce dépôt, vous acceptez que vos ajouts soient publiés sous la licence [CC-BY-4.0](https://creativecommons.org/licenses/by/4.0/). Veuillez vous assurer que vos contributions respectent cette licence.

---

**Merci pour votre engagement et vos contributions ! Grâce à vous que nous renforçons l’accès aux données et favorisons l’innovation au Tchad**.
