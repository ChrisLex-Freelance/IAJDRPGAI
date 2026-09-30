> 🗂️ **Section Diátaxis** : Référence (consultation) · **Niveau Bloom** : Se souvenir → Comprendre
> **Objectifs pédagogiques** : *définir* les termes clés, *identifier* à quel concept renvoie chaque mot rencontré dans le dépôt.

# Glossaire du JDR augmenté

Consultez ce glossaire au fil de la lecture des articles. Chaque terme pointe vers le développement correspondant dans [Usage des LLM dans le JDR](../Usage%20des%20LLM%20dans%20le%20JDR.md) ou dans la section [Explication](../30-explication/Skills%20et%20MCP%20dans%20le%20JDR.md).

| Terme | Définition courte | Approfondir |
|---|---|---|
| **IA Générative** | Système produisant du contenu nouveau (texte, image) à partir d'un prompt. | [Article principal](../Usage%20des%20LLM%20dans%20le%20JDR.md#quest-ce-que-la-gen-ai-ou-intelligence-artificielle-generative-) |
| **NLP** | Traitement automatique du langage naturel : compréhension et génération de texte. | [Article principal](../Usage%20des%20LLM%20dans%20le%20JDR.md#quest-ce-que-le-nlp-) |
| **NER** | Reconnaissance d'entités nommées : extraire personnes, lieux, organisations d'un texte. | [Article principal](../Usage%20des%20LLM%20dans%20le%20JDR.md#quest-ce-que-le-ner-) |
| **LLM** | Grand modèle de langage : moteur statistique générant du texte mot à mot. | [Article principal](../Usage%20des%20LLM%20dans%20le%20JDR.md#quest-ce-quun-llm-) |
| **Fenêtre contextuelle** | Quantité de texte (mémoire) que le LLM peut traiter simultanément. | [Article principal](../Usage%20des%20LLM%20dans%20le%20JDR.md#mémoire-dun-llm-ou-fenêtre-contextuelle) |
| **Prompt engineering** | Méthode de rédaction des requêtes : rôle, contexte, objectif, format. | [Article principal](../Usage%20des%20LLM%20dans%20le%20JDR.md#quest-ce-que-lingénierie-du-prompt) |
| **Chartopia** | Plateforme de tables aléatoires en ligne, utilisable en boucle avec un LLM. | [Article principal](../Usage%20des%20LLM%20dans%20le%20JDR.md#quest-ce-que-chartopia) |
| **Skill** | Paquet d'instructions (SKILL.md + fichiers annexes) apprenant une méthode récurrente à un agent. | [Skills et MCP](../30-explication/Skills%20et%20MCP%20dans%20le%20JDR.md#quest-ce-quun-skill-) |
| **MCP** | *Model Context Protocol* : standard ouvert connectant les LLM à des outils et données externes. | [Skills et MCP](../30-explication/Skills%20et%20MCP%20dans%20le%20JDR.md#quest-ce-que-le-mcp-) |
| **Agent** | LLM embarqué dans un harnais qui l'autorise à raisonner, appeler des outils et agir. | [Écosystème](../30-explication/%C3%89cosyst%C3%A8me%20d'outils%20IA%20pour%20le%20JDR.md#les-harnais-dagents) |
| **Harnais** | Couche logicielle (boucle, outils, permissions, mémoire) qui transforme un LLM en agent. | [Écosystème](../30-explication/%C3%89cosyst%C3%A8me%20d'outils%20IA%20pour%20le%20JDR.md#les-harnais-dagents) |
| **RAG / bibliothèque** | Génération augmentée par récupération : recherche sémantique dans une base documentaire avant réponse. | [Écosystème](../30-explication/%C3%89cosyst%C3%A8me%20d'outils%20IA%20pour%20le%20JDR.md#le-rag-ou-la-bibliothèque-du-meneur-de-jeu) |
| **Embedding** | Représentation vectorielle d'un texte permettant la recherche par similarité. | [Écosystème](../30-explication/%C3%89cosyst%C3%A8me%20d'outils%20IA%20pour%20le%20JDR.md#le-rag-ou-la-bibliothèque-du-meneur-de-jeu) |
| **IDE** | Environnement de développement intégré (VS Code) devenu atelier de pilotage de l'IA. | [Écosystème](../30-explication/%C3%89cosyst%C3%A8me%20d'outils%20IA%20pour%20le%20JDR.md#ide-et-environnements-vs-code-et-mistral-vibe) |
| **Git / GitHub / GitLab** | Versionnement distribué et plateformes d'hébergement collaboratif. | [Écosystème](../30-explication/%C3%89cosyst%C3%A8me%20d'outils%20IA%20pour%20le%20JDR.md#github-et-gitlab-versionner-sa-campagne) |
| **Mermaid** | Langage textuel de diagrammes (flowchart, timeline, mindmap…) rendu par GitHub. | [Écosystème](../30-explication/%C3%89cosyst%C3%A8me%20d'outils%20IA%20pour%20le%20JDR.md#mermaid-des-diagrammes-pour-lunivers-et-les-scénarios) |
| **LM Studio** | Application locale pour faire tourner des modèles ouverts (GGUF) hors ligne. | [Écosystème](../30-explication/%C3%89cosyst%C3%A8me%20d'outils%20IA%20pour%20le%20JDR.md#lm-studio-des-modèles-locaux-à-la-table) |
| **GGUF** | Format de fichier compact pour modèles quantifiés exécutables en local. | [Écosystème](../30-explication/%C3%89cosyst%C3%A8me%20d'outils%20IA%20pour%20le%20JDR.md#lm-studio-des-modèles-locaux-à-la-table) |

## Comment ce glossaire s'articule avec le reste du dépôt

```mermaid
flowchart LR
    LECT[Lecture d'un article] -->?"Terme inconnu ?"
    -->|oui| G[Glossaire<br>Se souvenir · Comprendre]
    -->|puis| EX[Explication<br>Comprendre · Analyser]
    LECT -->|besoin concret| GU[Guides pratiques<br>Appliquer · Créer]
```
