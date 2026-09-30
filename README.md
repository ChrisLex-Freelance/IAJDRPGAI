## Licence

Cet article est sous licence [Creative Commons Attribution - Pas d'utilisation commerciale - Pas de modification (CC BY-NC-ND)](https://creativecommons.org/licenses/by-nc-nd/4.0/). Vous êtes libre de partager cet article avec attribution, mais aucune utilisation commerciale ou modification n'est autorisée.

# Usage des LLM et de l'IA dans le Jeu de Rôle

Ce dépôt documente l'usage des LLM et de l'écosystème d'outils IA pour le jeu de rôle sur table. Il est organisé selon le framework **[Diátaxis](https://diataxis.fr)** — quatre sections qui répondent à quatre besoins différents — et chaque document affiche ses objectifs selon la **taxonomie de Bloom** (Se souvenir → Comprendre → Appliquer → Analyser → Évaluer → Créer).

## Comment naviguer ?

```mermaid
flowchart TD
    subgraph Diataxis [Framework Diátaxis]
        T["🎓 00 · Tutoriels<br><i>Apprendre — je débute</i><br>Bloom : Appliquer"]
        G["🛠️ 10 · Guides pratiques<br><i>Faire — j'ai un problème précis</i><br>Bloom : Appliquer → Créer"]
        R["📚 20 · Référence<br><i>Consulter — j'ai besoin d'une définition</i><br>Bloom : Se souvenir → Comprendre"]
        E["💡 30 · Explication<br><i>Comprendre — je veux la théorie</i><br>Bloom : Comprendre → Analyser"]
    end
    USR([Lecteur]) -->|première fois| T
    USR -->|en cours de partie| G
    USR -->|un mot inconnu| R
    USR -->|curiosité| E
    T --> G --> E
```

## Le parcours d'apprentissage en niveau Bloom

```mermaid
flowchart LR
    B1[Se souvenir<br>Glossaire] --> B2[Comprendre<br>Explications]
    B2 --> B3[Appliquer<br>Tutoriel & Guides]
    B3 --> B4[Analyser<br>Audits · comptes rendus]
    B4 --> B5[Évaluer<br>Critique de scénario]
    B5 --> B6[Créer<br>Univers · systèmes · Skills]
```

## Sommaire du dépôt

### 🎓 Tutoriels — apprendre en faisant

* [Tutoriel : premiers pas avec un LLM pour le JDR](00-tutoriels/Tutoriel%20premiers%20pas.md) — produire votre premier scénario en 15 minutes.

### 🛠️ Guides pratiques — résoudre un problème précis

* [Guides pratiques pour le MJ](10-guides/Guides%20pratiques%20pour%20le%20MJ.md) — carte de tous les « Comment faire X ? » (scénario, PNJ, audit, compte rendu, univers…).

### 📚 Référence — vérifier un terme ou une notion

* [Glossaire du JDR augmenté](20-reference/Glossaire.md) — tous les termes du dépôt, du NLP au MCP.

### 💡 Explication — comprendre la théorie et l'architecture

* [Usage des LLM dans le JDR](Usage%20des%20LLM%20dans%20le%20JDR.md) — l'article fondateur : fondamentaux, prompt engineering, cas d'usages, Chartopia.
* [Skills et MCP dans le JDR](30-explication/Skills%20et%20MCP%20dans%20le%20JDR.md) — compétences agentiques et protocole de connexion des outils.
* [Écosystème d'outils IA pour le JDR](30-explication/%C3%89cosyst%C3%A8me%20d'outils%20IA%20pour%20le%20JDR.md) — RAG/bibliothèque, harnais, IDE, GitHub/GitLab, Mermaid, LM Studio : six briques avec leurs branches d'évolution.

***

## Vue d'ensemble : le poste de MJ augmenté

```mermaid
flowchart LR
    MJ[Meneur de jeu]
    H[Harnais d'agent]
    MJ --> H
    H -->|Skills| S[Méthodes de jeu]
    H -->|MCP| O[Dés · VTT · Drive]
    H --> IDE[VS Code / Vibe]
    IDE --> G[Git · GitHub/GitLab]
    G --> M[Mermaid · site de campagne]
    B[Bibliothèque RAG] --> H
    L[LM Studio · modèles locaux] --> H
```
