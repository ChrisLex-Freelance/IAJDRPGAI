# Introduction

## Présentation

Bienvenue dans "**Usage des LLM dans le Jeu de Rôle**". Ce support est conçu pour les maîtres de jeu (MJ), les joueurs et joueuses (PJ), les créateurs de contenu, et tous les passionnés de *jeux de rôle* (JDR) qui souhaitent exploiter les *modèles de langage large* (LLM) pour enrichir leurs parties. Que vous soyez un MJ expérimenté cherchant à introduire de nouvelles dynamiques dans vos sessions ou un novice curieux des possibilités offertes par l'intelligence artificielle, ce livre vous fournira les outils et les techniques nécessaires pour faire usage d’un prompting efficace.

## Objectifs et public cible

L'objectif principal de cet e-book est de vous fournir une compréhension des modèles génératifs textuels et de leur application dans le contexte des JDR. Comment utiliser ces modèles pour créer des scénarios, développer des personnages, et gérer vos parties de manière plus fluide et créative. Ce guide est destiné aux MJ de tous niveaux, aux rédacteurs de JDR, et à toute personne intéressée par l'intégration de technologies avancées dans les loisirs créatifs. En combinant ces outils avec Chartopia, une plateforme dédiée à la création de tables aléatoires, les MJ peuvent générer des contextes riches et dynamiques pour leurs aventures et réutiliser ces contextes pour enrichir les futures interactions avec un LLM. Nous examinerons également l'utilisation d’un LLM pour auditer des scénarios et identifier les éléments potentiellement problématiques pour les joueurs.

## L'IA et les LLM dans le JDR

L'introduction de l'intelligence artificielle dans les jeux de rôle représente un apport significatif comme outils de support. Les LLM, tels que GPT, Claude ou Mistral, permettent de générer des dialogues, des descriptions, et des actions de manière dynamique et interactive, rendant les sessions de JDR plus engageantes et imprévisibles. En utilisant des prompts soigneusement conçus, les MJ peuvent s'adapter aux actions des joueurs en quasi temps réel, offrant une expérience de jeu plus riche et plus immersive.L'utilisation de l'intelligence artificielle et des LLM change la manière dont les maîtres de jeu vont pouvoir créer et gérer leurs campagnes de jeux de rôle.

# Quelques fondamentaux

## Vie privée et propriété intellectuelle

La réutilisation des contenus pour l'entraînement des modèles d'IA est une pratique courante qui présente des avantages significatifs pour améliorer la précision et la performance de ces technologies à moindre coût. Cependant, il est essentiel que vous soyez sensibiliser à la protection de vos données personnelles. 

Les conversations tenues avec des modèles de langage peuvent contenir des informations sensibles ou privées. Pour garantir que ces échanges ne soient pas exploités à des fins d'entraînement sans consentement explicite, il est crucial de vérifier et de paramétrer les options de confidentialité dans les paramètres de votre compte. 

Nous vous recommandons de réaliser régulièrement un contrôle du respect de vos choix dans les paramètres des différentes solutions technologiques que vous utilisez. En effet, certains acteurs technologiques ayant pour habitude à chaque mise à jour majeure de leur solution de faire un “reset” de vos choix.

En prenant ces précautions, vous pouvez bénéficier des avancées de l'IA tout en protégeant votre vie privée et vos données personnelles. De plus, il est important de considérer les aspects de la propriété intellectuelle. 

En tant qu’utilisateur vous devez être conscients que vos créations et idées partagées dans ces conversations peuvent être utilisées pour entraîner des modèles, ce qui pourrait poser des questions sur les droits d'auteur et la propriété de ces contenus. Ainsi, s'assurer que ces données ne sont pas utilisées sans permission contribue également à protéger les droits intellectuels des utilisateurs.

## Références et sources

**Articles académiques et publications :** De nombreuses études académiques analysent les impacts de l'IA sur la vie privée et la propriété intellectuelle. Recherchez des articles sur Google Scholar ou dans des revues spécialisées. Vous pouvez d’ailleurs demander à un modèle génératif de vous orienter vers ces publications en demandant la source de ses informations. La solution Perplexity est particulièrement “carré” sur ce point.

**Ressources juridiques :** Consultez des sites web juridiques ou des cabinets spécialisés en propriété intellectuelle pour comprendre les droits et les protections disponibles pour vos créations.

**Blogs et forums de développeurs :** Les discussions et les articles de blog sur des sites comme Stack Overflow, GitHub, et Medium peuvent offrir des perspectives pratiques, ainsi que des conseils sur la gestion de la confidentialité et des droits d'auteur lors de l'utilisation des LLM.

**Consultation d'experts :** Il est également important de noter que l'usage d'IA générative, tel que les LLM, ne dispense pas de faire appel à des références ou à des experts du domaine sur lequel on intervient. L'IA peut fournir des informations et des suggestions précieuses, mais elle ne remplace pas l'expertise humaine nécessaire pour contextualiser et interpréter correctement les données, prendre des décisions éclairées et garantir la précision et la fiabilité des informations utilisées.

## Qu’est-ce que la Gen AI ou Intelligence Artificielle Générative ?

L'intelligence artificielle générative (Gen AI) est une branche de l'IA qui utilise des modèles de machine learning pour générer de nouveaux contenus à partir de données existantes. Ces modèles peuvent produire du texte, des images, de l'audio et des vidéos. Dans le contexte des jeux de rôle, la Gen AI peut être un outil utile pour enrichir les scénarios, les personnages et l'expérience globale de jeu.

| Catégorie | Description | Exemples d’usages |
| ----- | ----- | ----- |
| **Texte** | La génération de texte par l'IA permet de produire des descriptions détaillées, dialogues réalistes, intrigues complexes, etc. | Lieux : Une taverne animée, une forêt mystérieuse. Événements : Une fête locale, une tempête de magie. Objets : Un anneau magique, une boussole enchantée. Caractéristiques : Force, intelligence. Avantages : Vision nocturne, chanceux. Défauts : Maladroit, phobie de l'eau. |
| **Image** | Utilisation de la Gen AI pour générer des images, offrant une aide visuelle précieuse. | Illustrations : Taverne, forêts mystérieuses, créatures fantastiques. Portraits : Personnages, PNJ. Cartes : Régions, villes, donjons. |
| **Audio** | Production d'éléments audio pour ajouter une dimension sonore immersive aux JdR. | Ambiances sonores : Bruits de forêt, ambiance de taverne. Effets sonores : Bruits de combat, sorts magiques. Voix de personnages : Voix de créatures, discours de personnages importants. |
| **Vidéo** | Génération vidéo pour une couche supplémentaire de narration et d'immersion. | Séquences cinématiques : Introduction d'une nouvelle campagne, conclusion épique.  Reconstitutions de scènes : Bataille finale, découverte d'un trésor. |
| **Traduction** | Utilisation de l'IA pour traduire des textes, facilitant l'accessibilité des campagnes de JdR à un public plus large. | Traduction de scénarios complets pour des joueurs de différentes langues. Adaptation de dialogues de PNJ pour correspondre à des contextes culturels divers. Traduction instantanée lors des sessions de jeu en temps réel. |

## Qu’est-ce que le NLP ?

Le NLP (Natural Language Processing, ou traitement automatique du langage naturel en français (TAL)) est une discipline de l'intelligence artificielle (IA) qui se concentre sur l'interaction entre les ordinateurs et les langues humaines. Le but du NLP est de permettre aux machines d’interpréter et de répondre au langage humain de manière à être utile.

### Objectifs du NLP

* **Compréhension :** Permettre aux machines de “comprendre” le contenu et le contexte du langage humain.  
* **Génération :** Faire en sorte que les machines puissent produire du langage naturel qui soit compréhensible et pertinent pour les humains.  
* **Traduction :** Traduire automatiquement le texte d'une langue à une autre.  
* **Analyse de sentiments :** Identifier et extraire les opinions ou sentiments exprimés dans un texte.  
* **Résumé automatique :** Condenser de grands volumes de texte en résumés courts et informatifs.

### Applications du NLP

* **Traduction automatique :** Google Translate.  
* **Analyse de texte :** Analyse des sentiments, analyse de polarité, analyse d’opinion, classification des textes.  
* **Recherche d'information :** Moteurs de recherche comme Google.  
* **Chatbots :** Services clients automatisés.  
* **Synthèse vocale et reconnaissance vocale :** Text-to-speech et speech-to-text technologies.

### Techniques du NLP

* **Tokenisation :** Diviser le texte en unités de base appelées tokens (mots, phrases).  
* **Analyse syntaxique (parsing) :** Analyser la structure grammaticale d'une phrase.  
* **Analyse sémantique :** Comprendre le sens des mots et des phrases.  
* **Stemming et lemmatisation :** Réduire les mots à leurs racines ou formes de base.  
* **Modélisation de sujets :** Identifier les thèmes principaux dans un ensemble de documents.  
* **Reconnaissance d’entités nommées :** Identifier et classifier les entités nommées dans un texte.  
* **Réseaux de neurones :** Utilisation de modèles de deep learning pour des tâches comme la traduction ou la génération de texte.

### Problèmatique du NLP

* **Ambiguïté :** Les mots et les phrases peuvent avoir plusieurs significations.  
* **Contextualisation :** Comprendre le contexte dans lequel une phrase est utilisée.  
* **Pragmatique :** Comprendre les intentions et les significations implicites.  
* **Variabilité linguistique :** La diversité des langues, des dialectes et des styles de langage.

### Exemple d'utilisation du NLP

Imaginons un jeu de rôle où les joueurs interagissent avec un monde virtuel à travers des commandes vocales. Voici comment le NLP peut être utilisé dans ce contexte :

* Un joueur dit "Je veux parler au marchand pour vendre mes potions."  
  * Convertir la parole en texte (speech-to-text).  
  * Analyser la syntaxe et la sémantique pour comprendre l'intention du joueur (ici, parler au marchand pour vendre des potions).  
  * Identifier les entités pertinentes (le marchand, les potions) et l'action à accomplir (vendre).  
  * Générer une réponse appropriée de la part du jeu, par exemple : "Le marchand vous salue et demande combien de potions vous voulez vendre." et convertir cette réponse en parole (text-to-speech).

## Qu’est-ce que le NER ?

Le NER (Named Entity Recognition, ou Reconnaissance d'Entités Nommées en français (REN)) est une technique de traitement automatique du langage naturel (NLP) qui consiste à identifier et classifier les entités nommées dans un texte. Les entités nommées sont des éléments spécifiques qui se réfèrent à des noms propres, tels que les personnes, les organisations, les lieux, les dates, les montants monétaires, etc.

### Objectifs du NER

* **Identification des entités** : Repérer les entités nommées dans le texte.  
* **Classification des entités** : Attribuer une catégorie spécifique à chaque entité identifiée (par exemple, personne, lieu, organisation).

### Applications du NER

* **Extraction d'information** : Extraire des informations pertinentes à partir de grands volumes de texte.  
* **Analyse de textes** : Aider à la compréhension des relations et des contextes dans les textes.  
* **Moteurs de recherche** : Améliorer la pertinence des résultats de recherche en comprenant mieux les requêtes des utilisateurs.  
* **Bioinformatique** : Identifier les gènes, les protéines et d'autres entités biologiques dans des textes scientifiques.  
* **Finance** : Extraire les noms d'entreprises, les montants financiers, les dates et d'autres informations dans les rapports financiers.

### Techniques du NER

* **Règles heuristiques** : Utilisation de règles manuelles basées sur des motifs linguistiques (par exemple, les mots en majuscule suivis d'un mot commun peuvent être des noms de personnes).  
* **Modèles statistiques** : Utilisation de modèles probabilistes comme les HMM (Hidden Markov Models) et les CRF (Conditional Random Fields) pour apprendre à partir de données annotées.  
* **Apprentissage profond** : Utilisation de réseaux de neurones, y compris les architectures LSTM (Long Short-Term Memory) et les Transformers, pour capturer les relations complexes dans les données textuelles.

### Exemple de NER

"Le chevalier Arthus a combattu le dragon Smaug dans les montagnes d'Erebor le 12ème jour du mois de Solstice."

#### Processus de NER

Le processus de NER identifie et classe les entités nommées de la manière suivante :

* **Arthus :** Personnage  
* **Smaug :** Créature  
* **Montagnes d'Erebor :** Lieu  
* **12ème jour du mois de Solstice :** Date

#### Explication

* Arthus est identifié comme un personnage, car c'est un nom propre de personne dans le contexte du JDR.  
* Smaug est identifié comme une créature, car c'est le nom d'une créature dans de nombreux contextes de fantasy.  
* Montagnes d'Erebor est identifié comme un lieu, car il s'agit d'un nom propre de lieu fictif précédé du mot montagne.  
* 12ème jour du mois de Solstice est identifié comme une date, bien que fictive, elle suit le format d'une date dans ce contexte.

### Importance du NER

Le NER est essentiel pour diverses applications de NLP car il permet de structurer des données non structurées et d'extraire des informations clés. Il facilite la tâche des systèmes automatisés en leur permettant de “comprendre” et de manipuler les informations textuelles de manière plus efficace et précise.

### Problèmatique du NER

* Ambiguïté : Les mêmes mots peuvent représenter différentes entités dans des contextes différents (par exemple, "Apple" peut se référer à l'entreprise ou au fruit).  
* Nouveaux noms : L'apparition de nouvelles entités non présentes dans les données d'entraînement.  
* Complexité linguistique : Les différences et les variations dans les langues et les styles d'écriture.

## Qu’est-ce qu’un LLM ?

Les Large Language Model (LLM) sont des systèmes d'intelligence artificielle entraînés sur de vastes corpus de texte pour comprendre et générer du langage humain. Ils fonctionnent en analysant des milliers de textes pour apprendre les structures grammaticales, les contextes et les significations des mots et des phrases. Lorsqu'on leur fournit un "**Prompt**" ou une entrée, ces modèles génèrent des réponses basées sur les données et les patterns qu'ils ont appris, en cherchant à prédire une suite logique de mots.

Les premières applications des LLM étaient principalement axées sur la traduction et la rédaction de texte. Cependant, avec l'arrivée de modèles plus puissants leurs capacités se sont étendues à des domaines créatifs tels que les jeux de rôle. Ces modèles peuvent maintenant créer des dialogues de personnages, des descriptions de lieux, et même des intrigues complètes, transformant ainsi la manière dont les JDR peuvent être conçus et joués. En intégrant les LLM dans vos sessions de JDR, vous bénéficiez non seulement d'une assistance créative mais aussi d'un partenaire capable de répondre aux moindres imprévus sortis de l'imagination des joueurs.

### Mémoire d’un LLM ou Fenêtre contextuelle

La fenêtre contextuelle est un concept clé dans l'utilisation des modèles de langage tels que GPT, Claude, Mistral ou Gémini. Elle se réfère à la quantité maximale de texte que le modèle peut traiter et "se souvenir" à un moment donné. Comprendre et optimiser l'utilisation de cette fenêtre est crucial pour tirer le meilleur parti des capacités des LLM dans les jeux de rôle (JDR).

### Fonctionnement de la fenêtre contextuelle

La fenêtre contextuelle, parfois appelée "contexte", désigne le nombre de tokens (unités de texte comprenant des mots, des ponctuations et des espaces) que le modèle peut analyser simultanément. Par exemple, si la fenêtre contextuelle est de 4096 tokens, le modèle peut traiter cette quantité de texte en une seule fois avant que les informations les plus anciennes ne soient oubliées ou remplacées par de nouvelles.

### Comparaison des fenêtres contextuelles

Voici les informations sur les modèles de langage, leurs capacités de fenêtre contextuelle, et le calcul du nombre de mots et de pages correspondant pour chaque modèle :

| Modèle | Organisation | Fenêtre contextuelle (tokens) | Nombre approximatif de mots | Nombre approximatif de pages |
| ----- | ----- | ----- | ----- | ----- |
| GPT-3.5 | OpenAI | 2 048 | Environ 1 500 mots | Environ 3 pages |
| GPT-3.5 turbo | OpenAI | 16 385 | Environ 12 300 mots | Environ 25 pages |
| GPT-4 | OpenAI | 32 768 | Environ 24 600 mots | Environ 50 pages |
| GPT-4 turbo | OpenAI | 131 072 | Environ 98 300 mots | Environ 200 pages |
| Claude 2 | Anthropic | 100 000 | Environ 75 000 mots | Environ 150 pages |
| Claude 3 | Anthropic | 200 000 | Environ 150 000 | Environ 300 pages |
| PaLM 2 | Google | 32 000 | Environ 24 000 mots | Environ 48 pages |
| Gemini 1.5 Pro | Google | 1 000 000 | Environ 750 000 mots | Environ 1 500 pages |
| LLaMA 2 | Meta | 4 096 | Environ 3 100 mots | Environ 6 pages |
| LLaMA 3 | Meta | 32 768 | Environ 24 600 mot | Environ 50 pages |
| Mistral 7B | Mistral	 | 8 192 | Environ 6 100 mots | Environ 12 pages |
| Mixtral 8x7B | Mistral	 | 32 000 | Environ 24 000 mots | Environ 48 pages |
| Mixtral 8x22B | Mistral	 | 64 000 | Environ 48 000 mots | Environ 96 pages |
| Codestral | Mistral	 | 32 000 | Environ 24 000 mots | Environ 48 pages |

Les estimations sont faites en considérant qu'un token équivaut généralement à environ 0,75 mot en anglais, et en supposant qu'une page typique de texte contient environ 500 mots. De plus, le contexte initial peut être emputé par des instructions préalablement positionnées dans le contexte par l’organisation porteuse de la solution (par exemple en indiquant au LLM qu’il doit être bienveillant dans la formulation de ses réponses en évitant les discriminations).

#### Estimation des tokens

Vous pouvez trouver sur Internet des estimateurs de Tokens ou vous pouvez en développer un vous même dans un environnement Google Collab. Si vous ne savez pas coder, rien de grave c’est un script en langage python relativement simple qu’un LLM est en mesure de coder pour vous. Il existe également des plugins Chrome qui réalisent cette estimation. L’estimateur vous donne une idée en temps réel de l’occupation de votre fenêtre de contexte.

### Importance de la fenêtre contextuelle dans les JDR

* **Continuité narrative :** Une fenêtre contextuelle plus large permet de maintenir une continuité narrative sur de plus longues périodes, ce qui est essentiel pour la rédaction de scénario ou de campagnes de JDR. Le modèle est en mesure de se souvenir d'un plus grand nombre de détails importants et de les réutiliser pour garantir une cohérence dans l'histoire.  
* **Complexité des scénarios :** Avec une fenêtre contextuelle plus grande, il est possible d'inclure des éléments plus complexes dans les prompts, comme des descriptions détaillées, des dialogues prolongés, et des choix de décisions multiples, sans perdre le fil de l'intrigue.

### Stratégies pour optimiser l'utilisation de la fenêtre contextuelle

* **Synthèse :** Pour maximiser l'efficacité de la fenêtre contextuelle, il est utile de synthétiser régulièrement les événements passés dans des résumés concis. Cela permet de garder les informations essentielles accessibles sans dépasser la limite de tokens.  
* **Prompting :** Lors de la rédaction de prompts, il est important de prioriser les informations cruciales et de les placer au début du prompt. Les détails moins pertinents peuvent être omis ou résumés pour économiser des tokens.  
* **Segment :** Diviser les scénarios en segments gérables qui peuvent être traités indépendamment mais reliés par des résumés ou des transitions fluides. Cela aide à maintenir la cohérence sans saturer la fenêtre contextuelle.

## Qu’est-ce que l’ingénierie du Prompt

Le prompt engineering (ou ingénierie de prompt) est un processus visant à concevoir, affiner et optimiser les entrées textuelles (ou prompts) fournies à un modèle de langage artificiel, comme GPT, pour obtenir des réponses ou des résultats plus précis, utiles ou pertinents. Cette pratique est particulièrement importante dans le contexte de l'utilisation de modèles de traitement du langage naturel (NLP) car elle permet de maximiser la performance du modèle en fonction de l'application spécifique.

### Objectifs du prompt engineering

* **Amélioration de la précision :** En formulant soigneusement les prompts, on peut guider le modèle pour qu'il génère des réponses plus exactes.  
* **Réduction des ambiguïtés :** Des prompts bien conçus peuvent réduire les réponses ambiguës ou hors sujet.  
* **Efficacité :** Des prompts clairs et concis peuvent réduire le temps nécessaire pour obtenir des réponses satisfaisantes.  
* **Contrôle des réponses :** En ajustant les prompts, on peut influencer la tonalité, la longueur et le style des réponses.

### Qu’est-ce qu’un prompt ?

Un prompt est une instruction ou un ensemble d'instructions donné à un modèle d'intelligence artificielle pour générer une réponse ou effectuer une tâche spécifique. Dans le contexte des modèles de langage comme GPT-3.5, GPT-4 ou GPT4-O, un prompt peut être une phrase, une question, ou un paragraphe qui guide le modèle pour produire un texte cohérent et pertinent en réponse.

### Comment faire pour qu'un prompt soit qualitatif ?

Pour qu'un prompt soit de qualité et génère les meilleurs résultats possibles, il doit être bien structuré, clair et précis. Voici quelques conseils par catégorie pour créer un prompt qualitatif :

| Catégorie | Caractéristiques d'un Prompt qualitatif | Exemple de Prompt générique |
| ----- | ----- | ----- |
| **Texte** | Clarté, précision, détails, contexte, objectif clair, langage naturel, exemples, format spécifique | "Rédige un essai de 500 mots sur l'impact de la révolution industrielle sur la société européenne, en abordant à la fois les aspects positifs et négatifs." |
| **Image** | Description détaillée, contexte visuel, spécifications techniques (style, couleur, composition) | "Imagine une forêt mystérieuse avec une lumière douce du matin filtrant à travers les arbres, et un chemin sinueux recouvert de mousse. \--ar 16:9 \--style raw" |
| **Audio** | Contexte sonore, spécificité des éléments audio, ambiance désirée | "Crés une ambiance sonore pour une taverne animée, avec des bruits de conversation, de la musique de fond et des cliquetis de verres." |
| **Vidéo** | Scénario détaillé, séquences spécifiques, éléments visuels et audio requis | "Produit une vidéo d'introduction pour une campagne de JdR, montrant une carte ancienne s'animant pour révéler un royaume mystérieux avec une musique épique." |
| **Modèles de Traduction** | Langues cibles, contexte culturel, ton et style de traduction | "Traduis ce scénario de JdR du français vers l'anglais, en conservant le ton médiéval et les nuances culturelles spécifiques." |

### Quelle mise en forme ?

Il est recommandé de structurer un prompt sous forme de Markdown pour améliorer la clarté et optimiser la qualité des réponses fournies par le modèle. En utilisant Markdown, il devient plus facile de hiérarchiser l'information, d'organiser les sections, et de distinguer les éléments essentiels. Par exemple, les titres et sous-titres permettent de décomposer les questions complexes, tandis que les listes ordonnées ou à puces facilitent la lecture des instructions. En outre, les blocs de code, les citations, et les autres balises Markdown apportent une précision contextuelle, ce qui aide le modèle à mieux comprendre les attentes et à fournir des réponses plus pertinentes et précises.

#### Qu'est-ce que Markdown ?

Markdown est un langage de balisage léger et simple qui permet de formater du texte de manière claire et structurée. Il est utilisé pour convertir du texte brut en HTML, tout en restant lisible sans avoir besoin de balises complexes. Grâce à sa syntaxe intuitive, Markdown permet de créer des titres, des listes, des liens, des tableaux, des blocs de code, et plus encore, en utilisant des caractères de ponctuation et des symboles simples. Ce format est très populaire pour la rédaction de documents, la gestion de contenu sur le web, ainsi que dans les fichiers README et autres documents techniques, car il favorise la lisibilité et la facilité de modification. Vous pouvez retrouver en annexe un tableau comportant les balises Markdown.

### Quel rôle adopter pour améliorer ses Prompts ?

Pour obtenir un résultat plus qualitatif avec une IA générative textuelle, il est recommandé de lui affecter un rôle, par exemple un métier, qui va lui permettre de cadrer son horizon de travail.

#### La notion d’expérience dans un rôle

Il est également recommandé d’ajouter une notion d'expérience dans le rôle occupé sous forme d’année. Notre recommandation est de prendre des valeurs standards : 10/20/30 ans d’expérience. Le jeu de rôle ayant 50 ans de vie officiel et les archives d’Internet étant alimentées sur le jeu de rôle de manière quantitative et qualitative depuis moins de 30 ans, un LLM disposera dans son apprentissage d’une profondeur plus ou moins équivalente.

#### Exemple de rôles appliqués aux Jeu de Rôle

Voici un tableau listant quelques rôles qui peuvent être utilisés pour aider un grand modèle de langage (LLM) à travailler sur la thématique du jeu de rôle, avec leurs forces et faiblesses respectives. Nous utiliserons certains de ces rôles dans le cadre de l’article. Vous pouvez retrouver en annexe une liste plus complète.

| Rôle | Forces | Faiblesses |
| ----- | ----- | ----- |
| **Auteur de JDR** | Création d'histoires, développement de personnages et de mondes, enrichissement du lore | Peut nécessiter une collaboration avec un designer pour équilibrer les aspects mécaniques |
| **Game Designer (JDR)** | Compréhension des mécaniques de jeu, équilibrage, innovation, intégration dans le système de jeu | Peut manquer de profondeur narrative si focalisé uniquement sur les mécaniques |
| **Maître de jeu (MJ)** | Connaissance pratique de la dynamique de groupe, adaptabilité, expérience des besoins des joueurs | Peut manquer de structure formelle et de théorie de game design |

### Quel contexte ?

Fournir du contexte lors de la rédaction d'un prompt est essentiel car il améliore la clarté et la précision, assure la pertinence des réponses, enrichit le contenu, maintient la cohérence, augmente l'engagement et l'immersion, et définit des limites claires. Cela permet au modèle de mieux comprendre les attentes, de générer des réponses alignées sur le sujet spécifique, et de créer une expérience plus riche et immersive pour l'utilisateur, tout en évitant les digressions et en maintenant le propos sur le sujet principal. Voici un tableau décrivant divers contextes qu’un modèle génératif peut utiliser pour générer du texte, avec leurs descriptions et exemples d'utilisation.

| Contexte | Description | Exemple de Prompt |
| ----- | ----- | ----- |
| **Académique** | Utilisé pour des travaux universitaires, des articles scientifiques, des rapports de recherche. | "Rédige une introduction pour une thèse sur l'impact des réseaux sociaux sur la santé mentale des adolescents." |
| **Professionnel** | Utilisé pour des documents d'affaires, des courriels professionnels, des rapports de projet. | "Rédige un rapport mensuel sur les performances de l'équipe de vente pour le mois de juin." |
| **Social et Familial** | Utilisé pour des communications personnelles, des invitations, des messages informels. | "Écris un message de félicitations pour un mariage." |
| **Marketing** | Utilisé pour des contenus publicitaires, des campagnes de marketing, des messages promotionnels. | "Rédige une annonce publicitaire pour le lancement d'un nouveau produit de soins de la peau." |
| **Juridique** | Utilisé pour des documents légaux, des contrats, des avis juridiques. | "Rédige une clause de non-divulgation pour un contrat de travail." |
| **Médical** | Utilisé pour des documents médicaux, des rapports de santé, des articles de recherche médicale. | "Rédige un résumé de recherche sur les effets secondaires des vaccins contre la grippe." |
| **Technologique** | Utilisé pour des manuels techniques, des guides d'utilisation, des articles sur les technologies. | "Rédige un guide d'utilisateur pour un logiciel de gestion de projet." |
| **Littéraire** | Utilisé pour des œuvres de fiction, des poèmes, des récits narratifs. | "Rédige un début de nouvelle sur une découverte archéologique mystérieuse." |
| **Éducatif** | Utilisé pour des supports pédagogiques, des plans de cours, des articles éducatifs. | "Rédige un plan de cours pour enseigner les bases de la programmation en Python." |
| **Divertissement** | Utilisé pour des scénarios de films, des scripts de jeux, des critiques de films ou de livres. | "Écrive une critique de film pour le dernier blockbuster d'action." |

### Quel objectif ?

Définir des objectifs clairs lors de la rédaction d'un prompt pour un modèle de langage est crucial car cela permet de guider la génération de contenu vers un but précis. Un objectif bien défini aide à informer, persuader, divertir, éduquer, instruire, inspirer, émouvoir, décrire, critiquer ou raconter, en fonction des besoins spécifiques de l'utilisateur. Cela assure que les réponses générées sont alignées avec les attentes, améliorent la pertinence du contenu, et permettent au modèle de produire des réponses plus cohérentes et ciblées. En établissant des objectifs clairs, on peut mieux contrôler le résultat et maximiser l'efficacité du modèle dans le contexte donné. Voici un tableau décrivant divers objectifs qu’un modèle génératif peut utiliser pour générer du texte, avec leurs descriptions et exemples d'utilisation.

| Objectif | Description | Exemple de Prompt |
| ----- | ----- | ----- |
| **Informer** | Fournir des informations précises et factuelles sur un sujet spécifique. | "Rédigez un article informatif sur les avantages de l'énergie solaire." |
| **Persuader** | Convaincre le lecteur d'adopter un point de vue ou de prendre une action particulière. | "Rédigez un argumentaire pour encourager les gens à voter aux prochaines élections." |
| **Divertir** | Amuser ou divertir le lecteur par le biais d'histoires, de blagues, ou de récits captivants. | "Écrivez une blague amusante sur les technologies modernes." |
| **Éduquer** | Enseigner ou expliquer des concepts, des procédures ou des connaissances spécifiques. | "Rédigez un tutoriel étape par étape sur la façon de créer un site web." |
| **Instruire** | Donner des instructions claires et précises pour accomplir une tâche. | "Rédigez des instructions pour monter un meuble IKEO." |
| **Inspirez** | Motiver et encourager les lecteurs à agir ou à penser positivement. | "Écrivez un message inspirant pour motiver une équipe à atteindre ses objectifs de vente." |
| **Émouvoir** | Provoquer des émotions fortes chez le lecteur, comme la joie, la tristesse ou la nostalgie. | "Rédigez une lettre émouvante à un ami de longue date." |
| **Décrire** | Fournir des descriptions détaillées et vivantes de personnes, de lieux ou d'événements. | "Décrivez un paysage de montagne au lever du soleil." |
| **Critiquer** | Évaluer et donner un avis sur des œuvres, des événements ou des produits. | "Rédigez une critique de livre pour un roman récemment publié." |
| **Raconter** | Narration d'histoires ou d'événements, réels ou fictifs. | "Racontez une histoire courte sur une aventure en forêt." |

### Quel format de sortie ?

Voici un tableau répertoriant divers formats de sortie possibles pour un modèle de langage (LLM) avec leurs descriptions et exemples d'utilisation. Ils peuvent vous permettre de générer des éléments contextuels imprimable ou affichable sur écran pour renforcer la vraisemblance de vos scénarios.

| Format de sortie | Description | Exemples d'utilisation |
| ----- | ----- | ----- |
| **Article de presse** | Texte informatif et formel couvrant des événements récents ou des sujets d'actualité | Rapports de nouvelles, communiqués de presse |
| **Article de blog** | Contenu informel ou semi-formel souvent personnel et subjectif, couvrant divers sujets | Conseils de voyage, tutoriels, avis de produits |
| **Message de réseau social** | Texte court et engageant adapté aux plateformes de médias sociaux | Tweets, posts Facebook, légendes Instagram |
| **Guide/Mode d'emploi** | Instructions détaillées expliquant comment réaliser une tâche ou utiliser un produit | Manuels d'instructions, guides de démarrage rapide |
| **Description de produit** | Texte promotionnel décrivant les caractéristiques et avantages d'un produit | Pages de vente, fiches produit sur les sites e-commerce |
| **E-mail** | Message électronique pouvant être formel ou informel | E-mails de marketing, communications internes |
| **Résumé** | Brève synthèse d'un document plus long, soulignant les points clés | Résumés de recherches académiques, abstracts d'articles scientifiques |
| **Histoire courte** | Narration fictionnelle ou factuelle de longueur limitée | Contes, anecdotes, nouvelles |
| **Essai académique** | Texte formel et structuré présentant une argumentation sur un sujet spécifique | Articles de revues scientifiques, dissertations |
| **Rapport** | Document détaillé présentant des analyses, des conclusions et des recommandations | Rapports financiers, rapports de recherche |
| **Présentation** | Série de diapositives ou de pages de contenu structuré pour une communication visuelle | Présentations PowerPoint, keynotes |
| **Scénario** | Texte décrivant les dialogues et les actions d'une œuvre de fiction, telle qu'un film ou une pièce | Scripts de films, pièces de théâtre |
| **Dialogue** | Échange structuré entre deux ou plusieurs personnages ou entités | Scènes de films, interactions dans les jeux vidéo |
| **Poème** | Texte littéraire utilisant le langage de manière artistique et souvent rythmée | Poèmes lyriques, haïkus |
| **Avis/critique** | Évaluation subjective d'un produit, service ou œuvre d'art | Critiques de films, avis sur les restaurants |
| **Débat** | Présentation de points de vue opposés sur un sujet donné | Débats politiques, discussions académiques |
| **Biographie** | Récit détaillé de la vie d'une personne | Biographies d'hommes célèbres, histoires de vie |
| **Annonce** | Message publicitaire ou informatif destiné à attirer l'attention | Annonces publicitaires, publicités |
| **Transcription** | Conversion de l'audio en texte, capturant fidèlement les paroles prononcées | Transcriptions d'interviews, discours politiques |

En complément d’un LLM, un MJ ou un PJ a souvent besoin d’une représentation visuelle pour aider à l’immersion. Midjourney est un outil idéal pour ce cas d’usage puisqu’il permet de générer des images. Toutefois il ne sera pas traité dans ce document car l’outil comprend à lui seul un certain nombre de paramètres et fonctionnalités qui demandent des explications plus poussées. 

Si vous souhaitez en savoir plus sur Midjourney : [https://www.youtube.com/@lestutosmidjourney](https://www.youtube.com/@lestutosmidjourney)

### Quelle tonalité ?

Vous avez la possibilité dans vos Prompts de spécifier une tonalité de restitution. Voici un tableau décrivant divers styles de tonalité qu’un modèle de langage peut utiliser pour générer du texte, avec leurs descriptions et exemples d'utilisation. Notez qu’il est possible de combiner les tonalités (Exemple : Amical mais urgent). Toutefois, éviter l’empilage de couches qui pourraient au final dégrader la génération.

| Ton | Description | Exemple de Prompt |
| ----- | ----- | ----- |
| **Formel** | Tonalité professionnelle et polie, souvent utilisée dans des contextes officiels ou académiques. | "Rédigez une lettre formelle de demande de partenariat avec une entreprise." |
| **Amical** | Tonalité chaleureuse et accessible, souvent utilisée pour des communications informelles. | "Écrivez un email amical invitant un ami à une fête d'anniversaire." |
| **Urgent** | Tonalité pressante et insistante, destinée à capter rapidement l'attention du lecteur. | "Rédigez un message urgent avertissant les résidents d'une coupure de courant imminente." |
| **Inspirant** | Tonalité motivante et encourageante, souvent utilisée dans des discours ou des messages positifs. | "Écrivez un discours inspirant pour motiver une équipe avant une grande compétition." |
| **Humoristique** | Tonalité légère et drôle, utilisée pour divertir et amuser. | "Rédigez une courte histoire humoristique sur les aventures d'un chat espiègle." |
| **Sérieux** | Tonalité grave et réfléchie, souvent utilisée pour aborder des sujets importants ou sensibles. | "Écrivez un article sur l'importance de la santé mentale dans le milieu de travail." |
| **Narratif** | Tonalité descriptive et engageante, souvent utilisée pour raconter des histoires ou des anecdotes. | "Racontez une histoire courte sur une découverte inattendue lors d'une randonnée en montagne." |
| **Didactique** | Tonalité instructive et éducative, utilisée pour expliquer des concepts ou donner des instructions. | "Rédigez un tutoriel étape par étape sur la façon de configurer un réseau domestique." |
| **Persuasif** | Tonalité convaincante et influente, utilisée pour persuader ou encourager une action. | "Rédigez un argumentaire de vente pour promouvoir un nouveau produit écologique." |
| **Poétique** | Tonalité artistique et lyrique, souvent utilisée dans la poésie ou les textes littéraires. | "Écrivez un poème sur la beauté de la nature au lever du soleil." |
| **Sarcastique** | Tonalité ironique et mordante, souvent utilisée pour critiquer ou se moquer. | "Rédigez un commentaire sarcastique sur les retards fréquents des transports en commun." |
| **Optimiste** | Tonalité positive et enthousiaste, utilisée pour transmettre de l'espoir et de la positivité. | "Écrivez un message optimiste pour célébrer les réussites de l'année écoulée." |
| **Pessimiste** | Tonalité sombre et négative, souvent utilisée pour exprimer des inquiétudes ou des critiques. | "Rédigez un article pessimiste sur les impacts environnementaux du changement climatique." |
| **Romantique** | Tonalité douce et passionnée, utilisée pour exprimer des sentiments d'amour et d'affection. | "Écrivez une lettre d'amour passionnée pour une occasion spéciale." |
| **Neutre** | Tonalité impartiale et factuelle, souvent utilisée pour des rapports ou des analyses objectives. | "Rédigez un rapport neutre sur les statistiques de vente trimestrielles de l'entreprise." |

### Quelle contrainte ?

Fournir des contraintes lors de la rédaction d'un prompt est important car elles assurent la clarté et la précision, alignent les résultats avec les objectifs spécifiques, maintiennent la pertinence et la cohérence du contenu, enrichissent la qualité et la richesse des réponses, optimisent la gestion du temps et des ressources, et réduisent les risques d'erreurs. En définissant des limites claires, les contraintes permettent de guider le modèle de manière efficace pour produire des textes précis, pertinents et bien structurés, répondant ainsi aux attentes spécifiques et maximisant l'efficacité du processus de génération de contenu.

Note : D\&D étant le poids lourd dans le domaine du JDR, il est fortement présent dans les connaissances des LLM et peut influencer significativement le résultat d’un prompt si vous ne donnez pas une instruction claire en imposant des contraintes au modèles.

Voici un tableau décrivant quelques contraintes applicables dans un prompt pour le domaine du jeu de rôle :

| Contrainte | Description | Exemple de Prompt |
| ----- | ----- | ----- |
| **Contexte** | Définir l'univers, l'époque et l'état du monde où se déroule l'histoire. | "Rédigez un scénario de JDR se déroulant dans un monde médiéval fantastique en pleine guerre civile." |
| **Personnages** | Spécifier les rôles, le développement des personnages et assurer la diversité. | "Incluez un héros, un antagoniste et plusieurs PNJ avec des motivations complexes et diversifiées." |
| **Intrigue** | Décrire la structure narrative, le conflit principal et les quêtes secondaires. | "Élaborez une campagne en trois actes avec un conflit central sur la recherche d'un artefact perdu." |
| **Ton et Style** | Déterminer la tonalité générale et le style de narration. | "Adoptez un ton épique et mystérieux avec un style narratif riche en descriptions." |
| **Mécaniques de Jeu** | Intégrer des règles spécifiques et assurer l'équilibrage des défis. | "Utilisez un système de magie basé sur les éléments avec des règles spécifiques pour les combats." |
| **Objectif du Scénario** | Définir les buts des personnages et l'impact de leurs décisions. | "Les joueurs doivent empêcher la résurrection d'un dragon antique, leurs choix affectant le résultat final." |
| **Limites Techniques** | Spécifiez une limite de mots et le format de sortie attendu. | "Rédigez le scénario en 3000 mots maximum, au format PDF." |
| **Immersion** | Créer une ambiance immersive avec des descriptions détaillées et des éléments visuels/auditifs. | "Décrivez un château abandonné avec des torches vacillantes et des bruits de chaînes résonnant dans l'ombre." |
| **Accessibilité** | Utiliser un langage clair et assurer l'adaptabilité pour différents niveaux de joueurs. | "Écrivez des descriptions claires et ajustez les défis pour des joueurs débutants et expérimentés." |

### Quels contrôles ?
De même, gardez en tête que le modèle va générer un texte avec le style, la tonalité ou les contraintes demandées, mais qu'en fonction de votre prompt et de la taille du texte de sortie en résultant cette tonalité sera plus ou moins présente. Il peut être utile de faire appel à des outils tiers pour auditer le texte générer afin de vous assurer de la conformité de la génération.

Vous pouvez par exemple utiliser le service de https://aittia.org qui dispose d'un GPT's pour auditer votre génération.

## Utiliser des LLM dans le Jeu de Rôle

| Avantages | Détails |
| ----- | ----- |
| **Créativité** | Les LLM peuvent vous aider à générer une quantité d'idées nouvelles et originales, enrichissant ainsi les scénarios de JDR. |
| **Réactivité instantanée** | Les LLM permettent de répondre rapidement aux actions imprévues des joueurs. |
| **Cohérence narrative** | Avec des prompts bien conçus, les LLM peuvent maintenir une cohérence narrative sur de longues périodes, ce qui est essentiel pour des campagnes de JDR prolongées. |
| **Économie de temps** | En automatisant certaines tâches de création, les MJ peuvent se concentrer sur la gestion de jeu et l'interaction avec les joueurs. |
| **Assistant** | L’usage d’un LLM par le MJ vient “rééquilibrer” la position de celui qui se trouve en général devoir gérer les intéractions et les idées de plusieurs joueurs. |

##### 

| Inconvénients | Détails |
| ----- | ----- |
| **Dépendance technologique** | Une forte dépendance aux LLM peut réduire la capacité du MJ à improviser sans assistance technologique. |
| **Risque d'incohérences** | Les LLM peuvent parfois générer des réponses incohérentes ou non pertinentes, nécessitant une supervision humaine. |
| **Manque de nuance émotionnelle** | Les LLM peuvent avoir du mal à saisir et à reproduire des nuances émotionnelles complexes, ce qui peut affecter la profondeur des interactions de personnages. |
| **Coûts et accessibilité** | L'utilisation de LLM avancés peut être coûteuse et nécessiter un accès à des ressources informatiques puissantes. |

### Concrètement ça donne quoi un prompt de JDR ?

Pour illustrer ce que nous venons de voir, voici un tableau avec des Prompts adaptés à 2 jeux de rôle de fantasy. La structure du Prompt conserve la même base et certains éléments vont évoluer en fonction du jeu.

| Jeu de rôle | Exemple de Prompt adapté |
| ----- | ----- |
| **Donjons et Dragons (D\&D)** | En tant que créateur de jeu de rôle avec plus de 10 ans d'expérience, vous devez rédiger un scénario de campagne pour Donjons et Dragons se déroulant dans un monde médiéval fantastique. La campagne doit comporter trois actes distincts, chacun avec des intrigues politiques complexes et des éléments de haute magie. Le ton général de l'histoire doit être épique et mystérieux, captivant les joueurs du début à la fin. Limitez le scénario à 3000 mots, en veillant à ce que chaque acte soit bien structuré et contribue à l'évolution de l'intrigue principale. Assurez-vous d'inclure des descriptions riches, des personnages bien développés, et des défis variés pour maintenir l'intérêt des joueurs. |
| **Warhammer Fantasy Roleplay** | En tant que créateur de jeu de rôle avec plus de 10 ans d'expérience, vous devez rédiger un scénario de campagne pour Warhammer Fantasy Roleplay se déroulant dans l'Empire du Vieux Monde. La campagne doit comporter trois actes distincts, chacun avec des intrigues politiques complexes et des éléments de haute magie. Les joueurs commenceront comme des aventuriers modestes et devront naviguer dans un monde sombre et périlleux, confrontés à la corruption, aux forces du Chaos et aux complots aristocratiques. Le ton général de l'histoire doit être épique et mystérieux, reflétant le style gritty et brutal propre à Warhammer. Limitez le scénario à 3000 mots, en veillant à ce que chaque acte soit bien structuré et contribue à l'évolution de l'intrigue principale. Assurez-vous d'inclure des descriptions riches, des personnages bien développés, et des défis variés pour maintenir l'intérêt des joueurs​. |

On voit qu'il est possible de mettre en place des patterns de Prompt pour structurer la génération du texte. Ces patterns peuvent être ajustés avec des variables.

Il est recommandé, pour gagner du temps, de vous constituer une bibliothèque de Prompt dès lors que vous avez identifié un pattern qui fonctionne et qui est réutilisable sur plusieurs cadres de jeux de rôles.

# Optimiser le contexte avec Chartopia

## Qu’est-ce que Chartopia

Chartopia est une plateforme en ligne destinée à créer, partager et trouver des tableaux aléatoires et des générateurs pour les jeux de rôle. Elle offre une vaste bibliothèque de tableaux pour aider les maîtres de jeu à générer des rencontres, du butin, des noms de personnages non-joueurs (PNJ), et bien d'autres éléments essentiels pour les sessions de JDR. Les utilisateurs peuvent créer leurs propres tableaux et les partager avec la communauté, ce qui enrichit continuellement la collection disponible.

L'une des fonctionnalités principales de Chartopia est la possibilité de réaliser des jets de dés aléatoires en un clic, ce qui simplifie grandement la préparation et la gestion des sessions de jeu. Les tableaux peuvent être aussi simples ou complexes que nécessaire, intégrant des formules pour des résultats dynamiques. Par exemple, un tableau peut déterminer non seulement les créatures rencontrées mais aussi leur nombre et leur disposition.

En plus de la création de tableaux, Chartopia propose des options avancées comme les sous-tableaux et les variables d'entrée, permettant de créer des générateurs très sophistiqués adaptés à divers besoins narratifs et mécaniques des JDR​.

Pour plus d'informations et pour découvrir les différentes fonctionnalités offertes par Chartopia, vous pouvez visiter le site officiel : [Chartopia](https://chartopia.d12dev.com).

## Comment fonctionne Chartopia ?

Chartopia fonctionne en permettant aux utilisateurs de créer, partager et utiliser des tableaux aléatoires et des générateurs pour les jeux de rôle via une interface en ligne intuitive. Voici comment ça fonctionne :

### Création de tableaux

Les utilisateurs peuvent créer des tableaux en entrant des données dans des colonnes et des lignes. Chaque cellule de tableau peut contenir du texte, des formules, ou des instructions pour des jets de dés.

Il est possible d'ajouter des sous-tableaux et de configurer des variables d'entrée pour des résultats plus complexes. Par exemple, un tableau peut inclure des instructions pour générer des rencontres de monstres avec des variations dans le nombre et le type de monstres rencontrés​.

### Utilisation de générateurs

Les utilisateurs peuvent effectuer des jets de dés en un clic pour obtenir des résultats aléatoires basés sur les tableaux créés. Cela permet de gagner du temps pendant les sessions de jeu en évitant les calculs manuels.

Les générateurs peuvent être configurés pour utiliser des formules mathématiques et des opérateurs logiques, offrant une grande flexibilité dans la création de scénarios complexes​​.

### Partage et bibliothèque de ressources

Chartopia dispose d'une bibliothèque de tableaux publics que les utilisateurs peuvent parcourir et utiliser. Les tableaux couvrent une large gamme de besoins, comme la génération de rencontres, de butin, de noms de PNJ, etc.

Les utilisateurs peuvent également partager leurs créations avec la communauté, contribuant ainsi à une base de données en constante expansion de ressources pour les maîtres de jeu​​.

### Interface utilisateur

L'interface de Chartopia est conçue pour être intuitive, avec des options comme le mode éditeur de texte enrichi. Les utilisateurs peuvent facilement ajouter, modifier et organiser les entrées de leurs tableaux.

## Comment faire usage d’un LLM vers Chartopia

Parmi les choses sur lesquelles les LLM sont particulièrement efficaces figure la génération de listes contextualisées grâce à leur capacité à “comprendre” et à synthétiser des informations complexes en fonction du contexte donné. Ça tombe bien parce que c’est essentiel pour Chartopia. Les LLM peuvent via un Prompt réaliser ce type de génération, tels que la création d’une liste de rencontres de monstres, de trésors, d’avantages, de défauts, de lieu, d’objet ou la définition de caractéristiques de PNJ, et produire des listes précises et pertinentes qui répondent parfaitement aux exigences de Chartopia.

### Création de tables aléatoires avec un LLM

Comme nous l’avons vu préalablement pour obtenir un résultat qualitatif, il est préférable de faire un peu d'ingénierie sur le Prompt en amont, c'est-à- dire de définir les éléments qui vont permettre de générer la liste qui répond le mieux à nos attentes.

#### Le rôle et l’ancienneté

Pour générer au mieux des tables aléatoires, plusieurs rôles peuvent être impliqués, chacun apportant une perspective et une expertise différentes. Par exemple nous retiendrons pour ce point de l’article 3 rôles et nous leur affectons une ancienneté de 30 ans dans le milieu :

* Auteur de jeu de rôle  
* Game designer  
* Maître de jeu (MJ)

#### Le domaine

Spécifiez clairement le thème ou le domaine du tableau (par exemple, "jeu de rôle fantasy", "cyberpunk", etc.). Voici une liste de différents domaines ou thèmes pour les jeux de rôle que vous pouvez utiliser pour définir le thème de votre tableau aléatoire :

* **Fantasy** : Monde médiéval fantastique peuplé de créatures mythiques, de magie et de chevaliers.  
* **Science-fiction** : Futur lointain avec des technologies avancées, des voyages spatiaux et des extraterrestres.  
* **Cyberpunk** : Univers dystopique avec des mégacorporations, des hackers, et une esthétique high-tech, low-life.  
* **Steampunk** : Monde victorien alternatif avec des technologies à vapeur et des inventions excentriques.  
* **Horreur** : Thème axé sur la peur, les monstres et les mystères surnaturels.  
* **Post-apocalyptique** : Univers dévasté par une catastrophe majeure, où les survivants luttent pour leur survie.  
* **Historique** : Aventures se déroulant à une période spécifique de l'histoire, comme l'Antiquité, le Moyen Âge, ou la Renaissance.  
* **Super-héros** : Monde contemporain ou futuriste où des individus possèdent des pouvoirs extraordinaires.  
* **Espionnage** : Univers centré sur les intrigues, les missions secrètes et les agents infiltrés.  
* **Western** : Aventures dans le Far West avec des cow-boys, des hors-la-loi et des villes frontalières.  
* **Pirates** : Monde maritime avec des corsaires, des trésors cachés et des batailles navales.  
* **Mythologique** : Univers inspiré des mythes et légendes de diverses cultures, comme la mythologie grecque, nordique ou égyptienne.  
* **Uchronie** : Réécriture de l'histoire avec des événements divergents, créant une réalité alternative.  
* **Space Opera** : Aventures épiques dans l'espace avec des empires galactiques, des batailles spatiales et des héros interstellaires.  
* **Fantastique Urbain** : Monde contemporain où la magie et les créatures mythiques existent en secret.  
* **Cthulhu/Mythes de Lovecraft** : Univers basé sur les écrits de H.P. Lovecraft, avec des horreurs cosmiques et des cultes occultes.  
* **Mystère/Enquête** : Thème centré sur la résolution d'énigmes, de crimes ou de mystères paranormaux.  
* **Noir** : Ambiance sombre et cynique, souvent dans un cadre urbain avec des détectives privés et des intrigues complexes.  
* **Samouraïs/Japon Féodal** : Monde inspiré du Japon médiéval avec des samouraïs, des ninjas et des intrigues de cour.  
* **High Fantasy** : Monde où la magie est omniprésente et les conflits épiques entre le bien et le mal sont courants.

Voici un exemple de liste des jeux de rôle classés par domaine sous forme de tableau :

| Domaine | Jeu 1 | Jeu 2 | Jeu 3 | Jeu 4 |
| :---- | :---- | :---- | :---- | :---- |
| **Low Fantasy** | Trône de fer | Wastburg | Warhammer Fantasy Roleplay | Hârn |
| **Fantasy** | Chroniques Oubliées Fantasy | Pathfinder | The One Ring | Donjons & Dragons |
| **High**  | Legend of the Five Rings (L5R) | Earthdawn | Donjons & Dragons | Exalted |
| **Grim Fantasy** | Warhammer Fantasy Roleplay | Symbaroum | GODS | Shadows of Esteren |
| **Science-fiction** | Starfinder | Traveller | Alien | The Expanse |
| **Cyberpunk** | Cyberpunk 2020 / Red | Shadowrun | Blade Runner | Interface Zero |
| **Steampunk** | Castle Falkenstein | Iron Kingdoms | Victoriana | Etherscope |
| **Horreur** | L'Appel de Cthulhu | Vampire: La Mascarade | Delta Green | Vaesen |
| **Post-apocalyptique** | Mutant Year Zero | Fallout | Gamma World | Eclipse Phase |
| **Historique** | Pendragon | Aquelarre | Imperator | Tenga |
| **Super-héros** | Mutants & Masterminds | Champions | Marvel Heroic Roleplaying | DC Heroes |
| **Espionnage** | James Bond 007 | Top Secret | Nights Black Agents | Spycraft |
| **Western** | Deadlands | Aces & Eights | Boot Hill | Wild West Exodus |
| **Pirates** | 7th Sea | Capitaine Vaudoo | Skull & Bones | Pirates of the Spanish Main |
| **Mythologique** | Mythic Greece | Scion | Glorantha (RuneQuest) | Agon |
| **Uchronie** | Fate of the Norns | Space: 1889 | GURPS Alternate Earths | Castle Falkenstein |
| **Space Opera** | Dune: Adventures in the Imperium | Star Wars: Edge of the Empire Age of rebellion Forces and Destiny | Fading Suns | Star Trek Adventures |
| **Fantastique Urbain** | Urban Shadows | Dresden Files RPG | World of Darkness | Monster of the Week |
| **Cthulhu/Mythes de Lovecraft** | L'Appel de Cthulhu | Trail of Cthulhu | Cthulhu Dark | Delta Green |
| **Mystère/Enquête** | Gumshoe | Sherlock Holmes Consulting Detective | Esoterrorists | The Dresden Files |
| **Noir** | Blades in the Dark | Noirlandia | A Dirty World | Hard City |
| **Samouraïs/Japon Féodal** | Tenga | Bushido | Sengoku | Legend of the Five Rings |
| **Contemporain** | Millenium’s End | Chroniques Oubliées Contemporain | Fiasco | Unknown Armies |

Cette table inclut des jeux populaires et diversifiés dans chaque domaine, idéalement, votre prompt doit être renforcé par un apport de contexte lié à cet univers via un résumé de 10 à 15 lignes.

#### Le format

Indiquez que vous souhaitez une liste sous forme de table aléatoire et que chaque entrée doit être numérotée pour faciliter les jets de dés, en précisant dans chaque cas le dé utilisé (d4/d6/d8/d10/d12/d20/d30/d100).

#### Le nombre d'entrées

Indiquez combien d'entrées vous souhaitez dans chaque catégorie (par exemple, 10, 20, 100, etc.). Gardez en tête que les tables de Chartopia ne sont pas limitées à un format de dés, ce qui signifie que vous pouvez avoir une table de 45 ou 113 entrées.

#### Les catégories

Si vous avez plusieurs catégories ou types d'entrées (comme des objets magiques, des rencontres, des trésors, etc.), précisez-les.

#### La structure de sortie

Fournissez un exemple de format ou de structure pour chaque entrée de la table.

| Le format de sortie sera sous la forme suivante :  | numéro | Libellé d’événement | Description de l’événement |  |
| :---- |

### Exemple de Prompt

------

En tant que \[Rôle : Auteur\] de \[Contexte : jeu de rôle\] avec \[Ancienneté : 20 ans \] d’expérience, vous souhaitez \[Objectif : générer\] |Format : une liste\] de \[Catégorie : d’événements aléatoires\] pour un \[Contexte : cadre de jeu de rôle\] \[Domaine : cyberpunk\] nommé \[Contexte/Contrainte : Shadowrun\] dans sa \[Contexte/Contrainte : 3éme édition\] \[Contexte/Contrainte : motorisé par un système D6 à seuil de succès\]. La liste \[Contrainte : doit contenir\] \[Contrainte : 20 entrées numérotées\]. Le format de sortie sera sous la forme suivante : \| numéro \| Libellé d’événement \| Description de l’événement \|

------

#### Exemple de résultat du Prompt

| Numéro | Libellé d’événement | Description de l’événement |
| ----- | ----- | ----- |
| 1 | Piratage de la Matrice | Une faille de sécurité dans la Matrice permet à un groupe de pirates de dérober des données sensibles d'une mégacorporation. |
| … | … | … |
| 20 | Artefact Atlante | Un artefact Atlante antique est découvert et devient la cible de divers groupes cherchant à en exploiter le pouvoir. |

Note : Dans notre exemple, Shadowrun étant un univers multi dimensions (monde physique, monde virtuel, domaine & plan astraux), il faudrait également ajouter cette contrainte de contexte dans le prompt pour obtenir des listes plus cohérentes. On pourrait également ajouter au contexte les factions impactés par l’événement ou à l'origine de l’événement. Mais nous vous recommandons de générer plusieurs tables et ensuite de réaliser un formulaire de génération combiné dans Chartopia.

### Intégration avec Chartopia

Prenez les listes générées et importez-les dans Chartopia pour créer des tables aléatoires. Chaque entrée peut être un lieu, un événement, un objet, une caractéristique, un avantage, un défaut ou un PNJ avec les descriptions fournies.

**Exemple de table de lieux dans Chartopia** :

| 1d20 | Lieu |  
|------|---------------------------------------|  
| 1 | La Taverne du Dragon Vert |  
| 2 | La Forêt des Murmures |  
| ...  | ... |  
| 20 | Le Marché Nocturne |

### Se former à Chartopia

Chartopia Tutorial (Part 1\) [https://www.youtube.com/watch?v=QfsrqSAV3Oo](https://www.youtube.com/watch?v=QfsrqSAV3Oo)  
Chartopia Tutorial (Part 2\) [https://www.youtube.com/watch?v=bWYNblqn1fw](https://www.youtube.com/watch?v=bWYNblqn1fw)  
Chartopia Tutorial (Part 3\) [https://www.youtube.com/watch?v=XRyWWBjGzh4](https://www.youtube.com/watch?v=XRyWWBjGzh4) 

# 

# Cas d’usages 

## Comment faire usage de Chartopia vers un LLM

### Objectif

Utiliser Chartopia pour créer des contextes complexes et dynamiques pendant les sessions de jeu de rôle. En combinant plusieurs tables aléatoires imbriquées, Chartopia permet de générer des éléments variés et riches que le Maître de Jeu peut intégrer en temps réel, enrichissant ainsi l'histoire.

### Fonctionnement

Pendant une session de jeu, le MJ peut se servir de Chartopia pour sélectionner aléatoirement des lieux, événements, objets, caractéristiques, avantages, défauts ou personnages non joueurs (PNJ). Ces éléments générés peuvent être immédiatement intégrés à l'histoire, rendant le jeu plus dynamique et imprévisible. Le MJ utilise ensuite ces contextes pour générer des textes détaillés via un modèle de langage (LLM).

### Étapes à suivre

Utiliser Chartopia pour générer des éléments :

* Créer et utiliser des formulaires combinant plusieurs tables aléatoires imbriquées pour générer des contextes variés.  
* Tirer au sort des éléments tels que lieux, événements, objets, caractéristiques, avantages, défauts ou PNJ en temps réel.

Intégrer les éléments générés dans le jeu :

* Copier les éléments générés vers le LLM pour demander la génération de textes détaillés et cohérents avec ces éléments.

### Résultat attendu

Une histoire enrichie en temps réel avec des éléments variés et dynamiques, créant une expérience de jeu plus immersive et imprévisible pour les joueurs.

## Génération d'histoires de personnage joueur ou non joueur

### Objectif

Utiliser un modèle de langage (LLM) pour générer une histoire détaillée pour un personnage en se basant sur le contexte fourni par sa fiche de personnage. Cela permet de créer un personnage riche et cohérent, intégrant ses caractéristiques spécifiques, avantages, défauts, et son background initial.

### Fonctionnement

En tant que Character Developer avec 10 ans d'expérience, vous allez rédiger l'historique d'un personnage pour le jeu de rôle \[Nom du jeu de rôle\]. Utilisez le contexte du personnage pour créer une description physique et morale concise, ainsi qu'une histoire détaillée.

### Étapes à suivre

* Utiliser le contexte du personnage : Basé sur la fiche de personnage fournie, intégrer les traits, talents, spécialisations, principes, et compétences dans une histoire cohérente.  
* Prompt engineering : Utiliser un prompt précis pour guider la création de l'historique du personnage.

### Résultat attendu

Une description physique et morale du personnage, ainsi qu'une histoire détaillée intégrant les traits, talents, spécialisations, principes, et compétences du personnage.

### Exemple de Prompt

------

En tant que Character Developer expérimenté (10 ans) 
Tu dois créer à l’aide du template un personnage
Utilise les informations fournies pour rédiger une description et son histoire (max. 50 lignes)
JDR : [Nom du jeu]
Système :

**Template**

**Histoire de fond**
- Origines : Où et quand est-il né ? Quelle est son histoire familiale ?  
- Événements marquants : Quels moments clés ont façonné ses motivations ?  
- Objectifs et motivations : Quels sont ses buts et pourquoi les poursuit-il ?  

**Personnalité**
- Traits de caractère : Principaux traits de personnalité.  
- Forces et faiblesses : Ses compétences et points faibles.  
- Évolution : Comment change-t-il au fil du temps ?  

**Apparence physique** 
- Description : Détaillez taille, corpulence, cheveux, yeux, et particularités.  
- Style vestimentaire : Type de vêtements et accessoires.  

**Relations**
- Alliés et ennemis : Qui sont ses 3 amis, 3 ennemis, et 3 mentors ?  
- Relations amoureuses : Y a-t-il une influence romantique sur l'histoire ?  

**Compétences**
- Talents : Quelles compétences ou pouvoirs possède-t-il ?  
- Formation : Quelle expertise a-t-il acquise ?  
- Limites : Quelles sont ses faiblesses ?  

**Conflits**
- Internes : Quels dilemmes moraux affronte-t-il ?  
- Externes : Quels obstacles doit-il surmonter ?  

**Originalité**
- Caractéristiques uniques : Qu’est-ce qui le rend unique ?  
- Voix distincte : A-t-il un comportement ou langage particulier ?  

**Contexte additionnel**
[Ajouter le contexte issu du JDR ou de Chartopia]

------

### Exemple de résultat du Prompt

Voir l’annexe pour découvrir un exemple de résultat.

## Conseils d’interprétation

### Objectif

Utiliser un modèle de langage (LLM) pour fournir des conseils d’interprétation aux joueurs, afin de les aider à mieux incarner leurs personnages dans un jeu de rôle. Cela est particulièrement utile pour des débutants découvrant le cadre du jeu et ayant besoin de repères.

### Fonctionnement

En tant que Character Developer avec 10 ans d'expérience, vous allez conseiller un joueur sur l'interprétation d’un personnage pour le jeu de rôle \[Nom du jeu de rôle\]. Utilisez le contexte, l’histoire, ainsi que la description morale et physique du personnage pour générer cinq conseils d’interprétation.

### Étapes à suivre

* **Analyser le contexte du personnage :** Recueillir et comprendre le contexte, l’histoire, et les descriptions morales et physiques du personnage.  
* **Générer des conseils d’interprétation :** Utiliser un prompt détaillé pour produire des conseils spécifiques pour l’interprétation du personnage.

### Résultat attendu

Cinq conseils pratiques et détaillés permettant au joueur de mieux incarner son personnage. Ces conseils doivent aider le joueur à saisir les nuances du personnage, à comprendre ses motivations profondes et à interpréter ses actions de manière cohérente avec son histoire, ses compétences et ses principes. Cela enrichit l'expérience de jeu en offrant une interprétation plus authentique et immersive.

### Exemple de Prompt

------

En tant que Character Developer expérimenté (10 ans)

Tu dois conseiller un joueur sur l'interprétation d’un personnage

JDR : [Nom du jeu]

Utilise le contexte, l’histoire, la description morale et physique du personnage pour générer 5 conseils d’interprétation :
- Conseil n°1 :
- Conseil n°2 :
- Conseil n°3 :
- Conseil n°4 :
- Conseil n°5 :

**Contexte du personnage**

*\[Insérer le contexte du personnage, comme par exemple celui générer avec le prompt précédant\]*

**Contexte additionnel**

*\[Ajouter le contexte issue du JDR ou de Chartopia\]*

------

### Exemple de résultat du Prompt

Voir l’annexe pour découvrir un exemple de résultat.

## Génération d’une jonction entre les historiques de personnages

### Objectif

Utiliser un modèle de langage (LLM) pour relier les histoires des personnages entre elles, augmentant ainsi la dynamique de jeu par le biais d’un contexte commun. Cela permet de renforcer les liens narratifs et les interactions entre les personnages.

### Fonctionnement

En tant que Character Developer avec 10 ans d'expérience, vous allez créer des événements communs entre deux personnages pour le jeu de rôle \[Nom du jeu de rôle\]. Utilisez les contextes des personnages pour générer cinq événements communs, en suivant un modèle structuré.

### Étapes à suivre

* Générer un second personnage : Créer ou récupérer les informations du second personnage à partir des prompts fournis.  
* Créer la jonction d’historique : Utiliser un prompt détaillé pour relier les histoires des personnages par le biais d’événements communs.

### Résultat attendu

Cinq événements communs bien définis qui lient les histoires de Valeria et Jarek, enrichissant ainsi le contexte et les interactions dans le jeu de rôle.

### Exemple de Prompt

------

En tant que Character Developer expérimenté (10 ans)

Tu dois créer une jonction d’histoires entre deux personnages

JDR : [Nom du jeu]

Utilises le contexte pour générer 5 événements communs (10 lignes max), en suivant le modèle ci-dessous : 

**Modèle d’événement**
- Libellé de l’événement :
- Lieu de l’événement :
- Description de l’événement :

Personnage 1 : [Coller les informations du premier personnage]

Personnage 2 : [Coller les informations du second personnage]

**Contexte additionnel**

*\[Ajouter le contexte issue du JDR ou de Chartopia\]*

------

### Exemple de résultat du Prompt

Voir l’annexe pour découvrir un exemple de résultat.

## Génération d’un contexte depuis l’historique d’un personnage

### Objectif

Étoffer l'univers de votre jeu de rôle en développant des éléments de contexte à partir de l'historique des personnages. Par exemple, si un personnage appartient à une faction ou une organisation sans détails disponibles, utilisez un modèle de langage (LLM) pour créer une histoire riche et détaillée pour cette entité.

### Fonctionnement

En tant que Game Designer avec 20 ans d'expérience, vous allez développer l'histoire d'une faction, organisation ou toute autre entité importante pour le jeu de rôle spécifié. Les personnages des joueurs sont issus de cette entité. Utilisez le contexte pour créer une histoire immersive et complète.

### Étapes à Suivre

* Définir le contexte de l'entité : Utiliser les éléments générés via des outils comme Chartopia pour créer un contexte détaillé pour l'entité.  
* Prompt engineering : Utiliser un prompt précis pour guider la création de l'histoire de l'entité.

### Résultat attendu

Une histoire complète et immersive pour l'entité, enrichissant l'univers du jeu et offrant des détails contextuels solides pour les personnages issus de cette entité. Cela inclut les origines, le développement, les compétences, les arts, les rivalités, et une description détaillée de leur monde natal.

Par exemple, si nous reprenons le personnage de Valeria générer plus haut ont voit qu'elle appartient à la maison Karath, sauf que nous n’avons pas d’élément sur cette maison dans le cadre de Dune : Adventures in the Imperium. Heureusement, Dune est bien pourvu en éléments utilisables dans une table aléatoire et à l’aide de Chartopia nous pouvons mettre en place un formulaire pour générer des Maisons. Nous allons donc via le formulaire générer les éléments de contexte qui vont donner naissance à la Maison Karath.

### Exemple de Prompt

------

En tant que Game Designer expérimenté (20 ans)

tu dois créer l’histoire d’une Maison noble

JDR : [Nom du jeu]

Les personnages des joueurs appartiendront à cette Maison. Utilise le modèle ci-dessous pour structurer l’histoire. 

**Informations sur la Maison**
- Nom de la Maison :
- Type de Maison :

**Histoire de la Maison**
- Origines et établissement :
- Développement et loyauté :
- Domaine de compétence :
- Arts et culture :
- Rivalité et ennemis :

**Monde natal de la Maison**
- Type de Monde :
- Description générale :
- Écologie et environnement :
- Culture et société :
- Ressources et économie :

**Contexte additionnel**

*\[Ajouter le contexte issue du JDR ou de Chartopia\]*

------

### Exemple de résultat du Prompt

**Informations sur la Maison**

Nom de la Maison : Karath
Type de Maison : Maison mineure

**Histoire de la Maison Karath**

- Origines et établissement : La Maison Karath, fondée il y a plusieurs siècles, a émergé sur un monde exploité et épuisé, habitable mais rude. Dès ses débuts, la Maison Karath s'est distinguée par son approche brutale et directe pour atteindre ses objectifs. Initialement des colons industrieux, les Karath ont rapidement compris que la force et l'intimidation étaient nécessaires pour survivre et prospérer dans un environnement aussi hostile.
- Développement et loyauté : La loyauté de la Maison Karath envers leur suzeraine, une Maison majeure puissante, est devenue légendaire. Cette dévotion sans faille, bien que parfois considérée comme écœurante par leurs rivaux, a permis aux Karath de s'établir fermement comme l'une des plus importantes Maisons vassales. Leur territoire, couvrant environ un tiers de leur planète d'origine, est un témoignage de leur capacité à s'imposer et à maintenir leur position grâce à des méthodes impitoyables.
- Domaine de compétence : Les Karath se sont spécialisés dans le domaine scientifique, particulièrement dans la recherche et le développement de nouvelles technologies. Bien que le Jihad Butlérien ait banni les machines pensantes, la Maison Karath a excellé dans l'exploration de nouvelles voies scientifiques respectant ces restrictions, créant des innovations qui leur ont permis de maintenir une longueur d'avance sur leurs concurrents. Leur expertise en conception technologique est reconnue et craint à travers l'Imperium.
- Arts et culture : En plus de leurs prouesses scientifiques, la Maison Karath a investi dans les arts, utilisant ce domaine non seulement pour gagner du respect et de la renommée mais aussi comme un outil stratégique. Leurs artistes, musiciens et acteurs itinérants servent souvent de couverture pour des opérations d'espionnage, infiltrant des cours ennemies et recueillant des informations cruciales. Les soirées musicales et les événements artistiques organisés par les Karath sont des occasions pour les intrigues politiques et les rencontres secrètes.
- Rivalité et ennemis : La Maison Karath a une rivalité particulièrement acerbe avec une autre Maison mineure qui cherche activement à les abattre. Cette maison ennemie, dégoûtée par la brutalité et la moralité des Karath, colporte mensonges et ragots à la cour, évitant cependant un conflit ouvert à moins d'y voir un avantage certain. Les Karath, conscients de cette haine, gardent toujours un œil vigilant sur les manœuvres de leurs rivaux.

**Monde natal de la Maison Karath**

- Type de monde : Monde exploité et épuisé habitable (Classe IV : survie possible sans protection). Le monde natal de la Maison Karath est une planète autrefois riche en ressources naturelles, mais aujourd'hui épuisée par des siècles d'exploitation intensive. La surface de la planète est marquée par des paysages désolés, des mines abandonnées et des zones industrielles en ruine. Les habitants vivent dans des cités fortifiées, construites pour résister aux tempêtes de sable fréquentes et aux conditions climatiques extrêmes.
- Écologie et environnement : L'écosystème de la planète a été gravement perturbé par l'exploitation minière, laissant peu de végétation et d'animaux sauvages. Les Karath ont dû développer des technologies avancées pour purifier l'air et l'eau, et pour cultiver des aliments dans des environnements contrôlés. Les scientifiques de la Maison ont fait de grandes avancées dans la biotechnologie et l'agriculture sous abri pour assurer la survie de la population.
- Culture et société : La société Karath est dure et disciplinée, reflétant les conditions difficiles de leur monde natal. La brutalité est souvent nécessaire pour maintenir l'ordre et la survie. Les valeurs de la Maison sont centrées sur la force, la loyauté et l'innovation scientifique. La culture artistique, bien que florissante, sert souvent à masquer des activités d'espionnage et à manipuler les perceptions extérieures de la Maison.
- Ressources et économie : Malgré l'épuisement des ressources naturelles, la Maison Karath a su diversifier son économie grâce à ses innovations technologiques. Les industries pharmaceutiques, les biotechnologies et les recherches scientifiques avancées sont désormais les piliers économiques de la planète. Les produits et services issus de leurs laboratoires sont prisés dans tout l'Imperium, assurant la prospérité continue de la Maison malgré les défis environnementaux.

## Génération d’un scénario

### Objectif

Créer un scénario de jeu de rôle détaillé et immersif, adapté à n'importe quel jeu de rôle, en utilisant une structure préétablie. Ce scénario doit inclure des descriptions riches, des personnages bien développés, et des défis variés pour maintenir l'intérêt des joueurs.

### Fonctionnement

En tant que créateur de jeu de rôle avec plus de 30 ans d'expérience, vous allez rédiger un scénario pour le jeu de rôle spécifié. Vous devrez vous assurer que le scénario est bien structuré et captivant, en utilisant un prompt spécialement conçu pour guider la création.

### Étapes à suivre

- Définir la structure du scénario : Utiliser une structure adaptable à tout jeu de rôle, comportant plusieurs actes et scènes détaillées.  
- Prompt engineering : Utiliser un prompt clair et détaillé pour guider la rédaction du scénario.

### Résultat attendu

Un scénario complet et bien structuré qui guide les joueurs à travers une aventure captivante, avec des personnages riches et des défis variés, tout en permettant une évolution cohérente de l'intrigue principale.

### Exemple de Prompt

------

En tant que créateur/scéanriste de jeu de rôle expérimenté (30 ans)

Rédige un scénario pour le JDR \[Nom du jeu de rôle\], avec des descriptions riches, des personnages développés et des défis variés pour captiver les joueurs.

Utilises le modèle pour structurer le scénario.

**Template Scénario**

- Titre (en majuscules) :
- Sous-titre : Indique pour quel jeu le scénario est conçu
- Nombre de joueurs : Complexité (1 = Débutant / 2 = Confirmé / 3 = Expert)
- Système : Indique quel système motorise le jeu/scénario

**Pitch du scénario (Max. 10 lignes)** :

**Acte 1**
- Pitch de l'acte 1 (Max. 10 lignes) :
  - Scène 1 : (10 à 20 lignes)
    - Lieu et description (Max. 3 lignes) :
    - 3 protagonistes principaux (alliés/antagonistes) :
  - Scène 2 : (10 à 20 lignes)
    - Lieu et description (Max. 3 lignes) :
    - 3 protagonistes principaux (alliés/antagonistes) :
  - Scène 3 : (10 à 20 lignes)
    - Lieu et description (Max. 3 lignes) :
    - 3 protagonistes principaux (alliés/antagonistes) :

**Acte 2**
- Pitch de l'acte 2 (Max. 10 lignes) :
  - Scène 1 : (10 à 20 lignes) :
    - Lieu et description (Max. 3 lignes) :
    - 3 protagonistes principaux (alliés/antagonistes) :
  - Scène 2 : (10 à 20 lignes)
    - Lieu et description (Max. 3 lignes)
    - 3 protagonistes principaux (alliés/antagonistes) :
  - Scène 3 : (10 à 20 lignes)
    - Lieu et description (Max. 3 lignes)
    - 3 protagonistes principaux (alliés/antagonistes) :

**Acte 3**
- Pitch de l'acte 3 (Max. 10 lignes) :
  - Scène 1 : (10 à 20 lignes)
    - Lieu et description (Max. 3 lignes)
    - 3 protagonistes principaux
  - Scène 2 : (10 à 20 lignes)
    - Lieu et description (Max. 3 lignes)
    - 3 protagonistes principaux
  - Scène 3 : (10 à 20 lignes)
    - Lieu et description (Max. 3 lignes)
    - 3 protagonistes principaux

Conclusion (Max. 10 lignes) :

**Conséquences**
- Succès :
- Succès mitigé :
- Échec :

En cas de succès 3 pitchs de scénario de suites possibles : 
- Pitch 1 (Max. 10 lignes) :
- Pitch 2 (Max. 10 lignes) :
- Pitch 3 (Max. 10 lignes) :

En d’échec 3 pitchs de scénario de suites possibles : 
- Pitch 1 (Max. 10 lignes) :
- Pitch 2 (Max. 10 lignes) :
- Pitch 3 (Max. 10 lignes) :

**Résumé des principaux antagonistes** (Motivations, méthodes, ressources, et filiation/allégeance)
- Antagoniste 1
- Antagoniste 2
- Antagoniste 3 

**Résumé des principaux alliés** (Motivations, méthodes, ressources, et filiation/allégeance)
- Allié 1
- Allié 2
- Allié 3 

**Contexte additionnel**
*\[Ajouter le contexte issue du JDR ou de Chartopia\]*

------

### Exemple de résultat du Prompt

Voir l’annexe pour découvrir l’exemple de scénario proposé pour le jeu de rôle *Dune : Aventures dans l'Imperium*. Il s’agit d’un premier jet qui utilise un contexte restreint mais qui pourrait être complété avec les différents prompt évoqué dans cet e-book.

A la lecture vous allez certainement trouver cela un peu léger ou bancal, mais l’intérêt réside dans le fait d’éviter de partir d’une feuille blanche.

Si par exemple vous disposez du compte rendu de votre dernière partie il pourrait servir de point de départ pour ce nouveau scénario généré en quelques secondes.

## Génération d’un audit de scénario

### Objectif

Utiliser un modèle de langage (LLM) pour auditer un scénario de jeu de rôle et identifier les éléments pouvant poser des difficultés aux joueurs, ainsi que les incohérences potentielles. L'objectif est de proposer des solutions et des recommandations pour améliorer la jouabilité et la cohérence du scénario.

### Fonctionnement

En tant qu’auditeur de scénario de jeu de rôle avec 20 ans d’expérience, vous allez analyser un scénario de jeu de rôle pour identifier les défis potentiels et les incohérences. Vous devrez fournir des suggestions pour atténuer ou surmonter ces défis et corriger les incohérences, en recommandant les rôles/métiers appropriés pour chaque tâche.

### Résultat attendu

Deux tableaux complets, l'un répertoriant les défis potentiels avec des suggestions pour les surmonter et les rôles/métiers recommandés, et l'autre répertoriant les incohérences avec des suggestions pour les corriger et les rôles/métiers recommandés. Ces tableaux permettront d'améliorer la jouabilité et la cohérence du scénario, offrant ainsi une expérience de jeu plus fluide et immersive.

### Exemple de Prompt

------

En tant qu’auditeur de scénario de jeu de rôle expérimenté (20 ans)

Identifie les éléments susceptibles de poser des difficultés aux joueurs

Suit les étapes ci-dessous :

**Étapes d'audit**
- Identifier les défis potentiels : Analyser chaque élément du scénario pour repérer les défis ou obstacles que les joueurs pourraient rencontrer.
- Identifier les incohérences : Repérer les erreurs potentielles de cohérence dans la trame du scénario.
- Créer deux tableaux markdown :
  - Tableau des défis : Indiquer chaque défi, sa nature, des suggestions pour le surmonter, et le rôle/métier recommandé.
  - Tableau des incohérences : Indiquer chaque incohérence, des suggestions pour les corriger, et le rôle/métier recommandé.

**Rôles/Métiers**
- Maître de jeu expérimenté (20 ans)
- Scénariste expérimenté (20 ans)
- Joueur expérimenté (20 ans)

------

### Exemple de résultat du Prompt

Voir l’annexe pour découvrir l’exemple d’audit réalisé sur le scénario généré avec le prompt précédent.

## Amélioration des scénarios

### Objectif

Utiliser les retours d’un modèle de langage (LLM) pour ajuster les éléments problématiques d'un scénario de jeu de rôle. Cela inclut la simplification des énigmes, le rééquilibrage des combats, et la proposition d'alternatives aux situations nécessitant des compétences rares, afin de rendre le jeu plus fluide et accessible.

### Fonctionnement

En tant que concepteur de scénario avec 10 ans d’expérience en jeu de rôle, vous améliorez un scénario pour le rendre plus fluide et accessible en utilisant le contexte d’audit : 

### Étapes à suivre

* Collecte des retours de l'audit : Recueillir les retours du prompt d’audit concernant les aspects du scénario jugés trop difficiles, déséquilibrés ou frustrants.  
* Ajustements du scénario : Modifier le scénario pour simplifier les énigmes complexes, rééquilibrer les combats, et proposer des alternatives aux situations nécessitant des compétences rares, en utilisant les suggestions du LLM.

### Remarques

L'utilisation d'un LLM permet de bénéficier d'une analyse approfondie et rapide des scénarios de jeu de rôle. Cela peut non seulement améliorer la jouabilité, mais aussi enrichir l'expérience de jeu en rendant les défis plus accessibles et équilibrés pour tous les joueurs.

### Résultat attendu

À la fin de ce processus, le scénario devrait être plus équilibré, accessible et agréable pour les joueurs. Les énigmes seront plus compréhensibles, les combats plus équitables, et les situations nécessitant des compétences rares auront des alternatives viables. L'expérience de jeu globale sera améliorée, permettant aux joueurs de se concentrer sur l'immersion et le plaisir de jeu sans être bloqués par des éléments frustrants ou déséquilibrés.

### Exemple de Prompt

------

En tant que concepteur de scénario de jeu de rôle avec 10 ans d'expérience

tu as pour mission d'améliorer un scénario existant pour le rendre plus fluide et accessible. 

Cette tâche inclue :
- La simplification des énigmes : pour les rendre plus compréhensibles sans perdre leur intérêt.
- Le rééquilibrage des combats : en ajustant les caractéristiques des ennemis et les ressources disponibles.
- La proposition d'alternatives : afin que tous les types de personnages puissent réussir.

**Contexte :**
*\[Ajouter le contexte issue de l'audit\]*

------

### Exemple de résultat du Prompt

Voir l’annexe pour découvrir des propositions d’amélioration sur un scénario généré et audité avec les prompts précédents.

## Génération d'issues scénaristiques

### Objectif

Proposer plusieurs pitchs d'issues scénaristiques afin de poursuivre l'aventure après une quête initiale, en utilisant un modèle de langage (LLM).

### Fonctionnement

Après avoir généré un scénario initial, utilisez un modèle de langage pour générer plusieurs développements possibles. Par exemple, après une aventure dans "La Forêt des Murmures", demandez au LLM de proposer des suites potentielles.

### Étapes à suivre

* Génération du Scénario Initial : Créez un scénario de base pour lancer l'aventure, comme une quête dans "La Forêt des Murmures".  
* Demande au LLM : Utilisez un LLM pour générer plusieurs pitchs d'issues scénaristiques en formulant une demande claire.  
* Sélection des Pitchs : Analysez les propositions du LLM et sélectionnez celles qui sont les plus cohérentes et engageantes pour poursuivre l'aventure.  
* Développement des Pitchs Sélectionnés : Développez davantage les pitchs sélectionnés pour les intégrer dans l'histoire globale.

### Résultat attendu

Obtention de plusieurs propositions de pitchs scénaristiques permettant de prolonger et enrichir l'aventure initiale.

### Exemple de Prompt

-------

En tant que concepteur de scénario de jeu de rôle

Prolonge une aventure initiale dans Dune: Aventures dans l’Imperium en générant plusieurs pitchs scénaristiques pour continuer l’histoire après la quête initiale. 

Proposes 3 suites possibles en tenant compte des éléments ci-dessous : 

**Élément à prendre en compte**

- Découverte de nouveaux secrets :
- Implication de nouvelles factions ou personnages influents :
- Expansion du cadre narratif et géographique :
- Développement des arcs personnels des personnages : 
- Incorporation d’une nouvelle menace ou antagoniste : 
- Mise en place d’enjeux politiques ou sociaux : 
- Évolution des thèmes et des tonalités : 

Contexte initial du scénario *\[Coller ici le contexte de votre scénario dans Dune: Aventures dans l’Imperium\]*

------

### Exemple de résultat du Prompt

Voir l’annexe pour découvrir des propositions de pitch sur un scénario généré avec les prompts précédents.

## Génération de combinaison de scénarios

### Objectif

Créer des arcs narratifs cohérents en fusionnant des contextes de scénarios variés générés par Chartopia.

### Fonctionnement

Utiliser un Large Language Model (LLM) pour combiner plusieurs contextes de scénarios générés par Chartopia. Par exemple, si Chartopia propose un scénario de "Tempête de Magie" et un autre de "Fête de la Moisson", le LLM sera chargé de les intégrer dans une histoire fluide et cohérente.

### Étapes à suivre

**Collecte des scénarios** :

* Utilisez Chartopia pour générer plusieurs contextes de scénarios.  
* Sélectionnez au moins deux scénarios à combiner.

**Demande de fusion** :

* Soumettez les contextes sélectionnés au LLM.  
* Spécifiez le besoin d'un arc narratif cohérent reliant les deux scénarios.

**Création de la jonction narrative** :

* Le LLM génère une histoire intégrant les éléments des deux scénarios. Par exemple, il pourrait créer une histoire où une "Tempête de Magie" perturbe la "Fête de la Moisson".

**Validation et ajustement** :

* Relisez le scénario généré.  
* Faites des ajustements si nécessaire pour assurer la cohérence et l'engagement narratif.

### Résultat attendu

Un arc narratif cohérent où des éléments de différents scénarios se rejoignent harmonieusement. 

### Exemple de Prompt

------

En tant que concepteur de scénario de jeu de rôle

Tu dois créer un arc narratif cohérent reliant deux scénarios.

Intégrer les éléments de contexte du scénario \[A\] et du scénario \[B\], pour former une histoire fluide et cohérente. 

**Scénario A :**  \[Contexte\]

**Scénario B :**  \[Contexte\]

------

## Génération d’une scène développé

### Objectif

Créer une scène immersive et dynamique pour un scénario de jeu de rôle, en utilisant un modèle de langage pour générer des détails et des descriptions riches.

### Fonctionnement

Le modèle de langage analyse le contexte et les éléments fournis pour générer une scène détaillée, en intégrant des aspects narratifs, visuels, auditifs, olfactifs et tactiles.

### Étapes à suivre

* Définir le contexte général et les objectifs de la scène.  
* Fournir des détails spécifiques sur l'environnement, les personnages et l'intrigue.  
* Utiliser le modèle de langage pour générer des descriptions et des événements dynamiques.  
* Réviser et ajuster la scène générée pour qu'elle s'intègre parfaitement dans le scénario global.  
* Intégrer les compétences et traits nécessaires pour les joueurs.

### Résultat attendu

Une scène complète et immersive, prête à être utilisée dans une session de jeu de rôle, avec des détails visuels, auditifs, olfactifs et tactiles, ainsi que des événements dynamiques et des interactions possibles.

### Exemple de Prompt

------

En tant que Game Designer avec 20 ans d’expérience

Tu dois détailler une scène pour le jeu de rôle \[Nom du jeu de rôle\] en respectant le format suivant :

**Scène**

**Système** :

**Contexte et environnement**
- Durée estimée : \[15 / 30 / 45 / 60 minutes\]
- Type de scène : \[Action / Dialogue / Témoin\]
- Type d’environnement : \[Urbain / Rural / Hostile\]
- Type de lieu : \[Intérieur / Extérieur / Virtuel / Métaplan\]
- Ambiance : \[Sonore / Visuelle / Olfactive / Tactile\]

**Personnages Non Joueurs (PNJ)**
- Nom du PNJ 1 : (Description, rôle, motivations)
- Nom du PNJ 2 : (Description, rôle, motivations)

**Intrigue et Objectif principal de la scène**
- Conflit : Obstacles ou conflits à surmonter
- Développement : Comment la scène fait progresser l'intrigue

Détails Sensoriels**
- Visuel : \[Détails visuels marquants\]
- Auditif : \[Sons présents\]
- Olfactif : \[Odeurs perceptibles\]
- Tactile : \[Textures ou sensations ressenties\]

**Événements dynamiques**
- Actions des PJ : \[Actions possibles des PJ et conséquences\]
- Événements aléatoires : \[Événements inattendus\]

**Récompenses et conséquences**
- Récompenses : \[Récompenses potentielles pour les PJ\]
- Conséquences : \[Conséquences possibles des actions des PJ\]

**Type de rencontre**
- Nature de la rencontre : \[Ennemie / Contact / Allié / Neutre\]
- Niveau d’opposition : \[Antagoniste générique / mineur / majeur / supérieur\]

**Indice de danger**
- Indice de danger : \[Nul / Faible / Normal / Fort / Létal\]

**Compétences clefs**
- Compétence 1
- Compétence 2
- Compétence 3

**Traits/Avantages clés**
- Trait/Avantage 1
- Trait/Avantage 2
- Trait/Avantage 3

**Défauts clefs**
- Défaut 1
- Défaut 2
- Défaut 3

**Protagoniste clé Protagoniste clé** 
- Prénom & Nom, Surnom
- Description

**Points d’entrée de la scène**
- Point 1
- Point 2
- Point 3

**Éléments clefs de la scène**
- Élément 1
- Élément 2
- Élément 3
- Élément 4
- Élément 5
- Élément 6

**Chronologie de la scène**
- Pré-requis 1 : \[Scène n°X\]
- Pré-requis 2 : \[Scène n°X\]
- Pré-requis 3 : \[Scène n°X\]

**Points de sortie de la scène**
- Point 1
- Point 2
- Point 3

Indiquez moi lorsque vous avez pris connaissance de ma demande pour que je vous communique la trame du scénario contenant les actes et les scènes.

------

## Génération d’un lieu développé

### Objectif

Créer une description détaillée et immersive d'un lieu pour un jeu de rôle, en fournissant des informations sur son ambiance, son histoire, ses caractéristiques et ses éléments d'intrigue.

### Fonctionnement

Utiliser l'expertise d'un Game designer expérimenté pour élaborer une description structurée et complète d'un lieu, en suivant un format prédéfini qui couvre divers aspects du lieu.

### Étapes à suivre

* Définir le nom et le type de lieu  
* Décrire l'atmosphère et l'ambiance (sons, odeurs, éléments visuels)  
* Détailler les décorations et la clientèle habituelle  
* Ajouter des éléments optionnels comme l'histoire, la sécurité, les relations et les intrigues  
* S'assurer que tous les éléments sont cohérents avec l'univers du jeu de rôle spécifié

### Résultat attendu

Une description détaillée et structurée d'un lieu pour un jeu de rôle, comprenant des informations sur ses caractéristiques physiques, son ambiance, son histoire, ses relations et ses potentiels éléments d'intrigue, le tout adapté à l'univers du jeu spécifié.

### Exemple de Prompt

------

En tant que Game Designer avec 20 ans d’expérience

Tu dois détailler un lieu pour le jeu de rôle \[Nom du jeu de rôle\] en suivant le format ci-dessous

**Lieu**
- Nom du lieu :
- Type de lieu :
- Taille :

**Atmosphère et ambiance**
- Sons ambiants :
- Odeurs ambiantes :
- Éléments visuels :
- Décorations :
- Habitués/Clientèle habituelle :
- Éléments optionnels

**Histoire et contexte**
- Origine :
- Événements importants :
- Rumeurs :
- Sécurité et défense
- Forces de sécurité :
- Systèmes de défense :
- Menaces :
- Relations et alliances
- Alliés et rivaux :
- Influence :
- Intrigues et Opportunités :
- Personnages clés :
- Conflits :

------

## Feedback Loop entre le LLM et Chartopia

### Objectif

Optimiser l'intégration des résultats des tables de Chartopia pour générer des contextes dynamiques et pertinents via le LLM.

### Fonctionnement

Les résultats obtenus des tables de Chartopia sont utilisés pour enrichir et préciser les demandes adressées au LLM. Par exemple, si la table de Chartopia indique que les joueurs se trouvent dans "La Forêt des Murmures", cette information est utilisée pour solliciter des événements spécifiques à ce lieu.

### Étapes à suivre

* Utiliser Chartopia pour générer un contexte initial ou une situation.  
* Identifier le contexte ou l'événement fourni par Chartopia (par exemple, "La Forêt des Murmures").  
* Formuler une demande précise au LLM en utilisant ce contexte (par exemple, "Décrire une rencontre aléatoire dans La Forêt des Murmures").  
* Utiliser la réponse du LLM pour enrichir l'expérience de jeu ou pour informer de nouvelles demandes.

### Résultat attendu

La génération de contextes riches et spécifiques par le LLM, en réponse aux indications fournies par Chartopia, créant ainsi un flux d'interactions dynamique et pertinent pour les joueurs.

### Exemple de Prompt

| En tant que Maître du Jeu avec 10 ans d’expérience, vous devez générer une rencontre aléatoire pour un groupe d'aventuriers dans "La Forêt des Murmures". Utilisez les informations suivantes pour créer une scène immersive et pertinente : Contexte : La Forêt des Murmures est connue pour ses arbres anciens et ses bruits étranges. Heure de la journée : Crépuscule (information obtenue de Chartopia) Météo : Brouillard léger (information obtenue de Chartopia) Veuillez décrire une rencontre aléatoire en suivant ce format : Description de l'environnement immédiat : Sons ambiants Odeurs Éléments visuels particuliers Événement ou créature rencontrée : Description Comportement ou action initiale Défi ou opportunité pour les joueurs : Nature du défi/opportunité Conséquences potentielles (positives et négatives) Indices ou éléments de mystère liés à la Forêt des Murmures : Un détail intrigant Une possible connexion avec l'histoire plus large Options d'interaction pour les joueurs : 2-3 choix possibles pour réagir à la situation |
| :---- |

## Génération de comptes rendus de partie

### Objectif

Après chaque session de jeu de rôle, utilisez un modèle de langage (LLM) pour transformer les notes prises par les participants en un compte rendu cohérent et détaillé. Ce processus consiste à combiner les notes des joueurs avec les éléments du scénario pour produire un résumé exhaustif et captivant de la session.

### Fonctionnement

En tant que Maître de Jeu (MJ) expérimenté avec 10 ans de pratique, vous avez terminé une session de jeu de rôle. Les participants ont pris des notes détaillant les événements, les décisions et les actions entreprises durant la partie. Votre objectif est de convertir ces notes en un compte rendu structuré et immersif.

### Étapes à suivre

**Collecte et lecture des notes :**

* Récupérez toutes les notes fournies par les participants.  
* Lisez attentivement ces notes pour comprendre les points clés de la session.

**Intégration des éléments du scénario :**

* Combinez les informations des notes avec les éléments prévus du scénario.  
* Assurez-vous que chaque événement, décision et action est correctement contextualisé par rapport au scénario.

**Rédaction du compte rendu :**

* Rédigez un compte rendu détaillé, structuré de manière logique et chronologique.  
* Incluez les événements majeurs, les décisions critiques, les actions des personnages, ainsi que tout détail pertinent qui enrichit le récit.  
* Veillez à ce que le texte soit clair, agréable à lire et reflète fidèlement l’atmosphère de la session.

### Résultat attendu

Un compte rendu complet et immersif qui capture l’essence de la session de jeu, aidant les joueurs à revivre l’expérience et à préparer les futures aventures.

### Exemple de Prompt

| En tant que Maître de jeu (MJ) expérimenté (10 ans), tu viens de terminer une session de \[Nom du jeu de rôle\]. Les participants ont pris des notes sur les événements, décisions et actions effectuées. Utilises ces notes ainsi que le scénario de la session pour rédiger un compte rendu structuré et détaillé. Étapes à suivre Combiner les notes : Intégrez les informations des notes des joueurs avec les éléments du scénario. Rédiger un compte rendu détaillé : Inclure les événements clés. Mettre en avant les décisions importantes et les actions des personnages. Ajouter tout autre détail pertinent pour enrichir le récit. Structuration : Assurez-vous que le compte rendu soit clair, bien structuré et agréable à lire. Questions et actions en suspens : Lister les points non résolus ou en attente pour la prochaine session. Contexte *(Coller ici le contexte du scénario et les notes des joueurs)* |
| :---- |

Note : Ce Prompt peut avoir un contexte très important, plus que ce que la fenêtre de dialogue est en mesure de recevoir. Dans ce cas, il vous faudra procéder par étape en découpant votre demande et en précisant ceci dans votre Prompt initial avec l’ajout d’une information/instruction à destination du modèle.

### Exemple de Prompt

| En tant que Maître de jeu (MJ) expérimenté (10 ans), tu viens de terminer une session de \[Nom du jeu de rôle\]. Les participants ont pris des notes sur les événements, décisions et actions. Utilisees ces notes et le scénario pour rédiger un compte rendu structuré et détaillé. Étapes à suivre Combiner les informations : Intégrez les notes des joueurs avec les éléments du scénario. Rédiger un compte rendu détaillé : Inclure les événements clés. Souligner les décisions importantes et les actions des personnages. Ajouter tout autre détail pertinent pour enrichir le récit. Structuration : Assurez-vous que le compte rendu soit clair, bien structuré et agréable à lire. Questions/actions en suspens : Lister les points non résolus ou en attente pour la prochaine session. Demande de partage Indique quand je peux partager les éléments suivants : Le scénario Note du joueur A Note du joueur B Note du joueur C Note du joueur D Note du MJ Un fois que en possession de l’ensemble (scénario \+ notes), réalisees le compte rendu de la partie. |
| :---- |

## Conception d’univers

### Objectif

Créer un univers cohérent, immersif et riche en possibilités narratives pour un jeu de rôle, en définissant ses aspects géographiques, historiques, culturels, politiques et fantastiques.

### Fonctionnement

Utilisation d'un template structuré pour guider la création de l'univers, en abordant systématiquement différents aspects clés. Le créateur répond à une série de questions prédéfinies pour définir les éléments essentiels de l'univers, en veillant à leur cohérence et à leur potentiel ludique.

### Étapes à suivre

* Définir le contexte général (nom du monde, genre, niveau technologique)  
* Décrire la géographie et le climat  
* Établir l'histoire et la mythologie  
* Concevoir les sociétés et cultures  
* Détailler l'économie et le commerce  
* Élaborer la structure politique et les dynamiques de pouvoir  
* Définir le système de magie et/ou de technologie  
* Créer les religions et croyances  
* Identifier les menaces et dangers  
* Proposer des pistes de quêtes et d'aventures  
* Développer un arc narratif global et une structure de campagne

### Résultat attendu

Un univers de jeu de rôle détaillé et cohérent, offrant un cadre riche pour des aventures variées, avec des éléments géographiques, historiques, culturels et fantastiques bien définis, ainsi qu'une trame narrative globale permettant de structurer une campagne à long terme.

### Exemple de Prompt

| En tant que concepteur de jeux de rôle expérimenté (30 ans), aides moi à créer un cadre de règles pour un nouveau jeu de rôle en suivant le modèle ci-dessous. N'hésitez pas à me poser des questions pour clarifier certains aspects ou proposer des alternatives. Template de cadre de règles Concept et ton : Genre : Quel est le genre principal (heroic fantasy, sci-fi, etc.) ? Ton : Quelle est l'ambiance générale (épique, sombre, humoristique, etc.) ? Complexité : Quel niveau de complexité visez-vous (léger, moyen, complexe) ? Système de résolution : Méthode : Quel type de système (d20, pool de dés, cartes, etc.) ? Échelle de difficulté : Comment sont déterminés les seuils ? Succès/Échecs : Comment sont gérés les degrés de réussite ou d'échec ? Création de personnages : Méthode : Comment les personnages sont-ils créés (points, aléatoire, archétypes) ? Attributs : Quels sont les attributs principaux ? Compétences : Comment sont structurées les compétences ? Background : Quelle importance est donnée à l’histoire personnelle ? Combat et conflits : Initiative : Comment est déterminé l’ordre des actions ? Actions : Combien d’actions par tour et comment sont-elles gérées ? Dégâts : Comment sont-ils calculés et appliqués ? Santé : Comment la santé est-elle gérée ? Progression : Expérience : Comment les personnages gagnent-ils de l’expérience ? Amélioration : Comment s’améliorent-ils ? Niveaux : Y a-t-il un système de niveaux ou une progression fluide ? Magie/Technologies spéciales : Système : Comment fonctionnent la magie ou les technologies ? Coût : Quel est le coût d’utilisation (points, fatigue, ressources) ? Apprentissage : Comment acquiert-on de nouveaux sorts ou technologies ? Gestion des ressources : Inventaire : Comment est géré l’équipement ? Économie : Quel système monétaire ou d’échange est utilisé ? Ressources spéciales : Y a-t-il des ressources uniques à gérer (karma, santé mentale, etc.) ? Interactions sociales et exploration : Compétences sociales : Comment sont gérées les interactions sociales ? Exploration : Quelles mécaniques soutiennent l’exploration ? Récompenses et conséquences : Récompenses : Quels types de récompenses sont donnés ? Conséquences : Comment sont gérées les conséquences des actions ? Règles pour le MJ : Création d’aventures : Quelles lignes directrices pour créer des aventures ? Gestion des PNJ : Comment gérer les personnages non-joueurs ? Équilibrage : Quelles règles pour équilibrer défis et récompenses ? Innovations et particularités : Mécaniques uniques : Y a-t-il des mécaniques innovantes ou particulières ? Intégration thématique : Comment les règles renforcent-elles le thème du jeu ? |
| :---- |

## Conception d’un cadre de règle

### Objectif

Créer un système de règles cohérent, équilibré et flexible qui soutient l'expérience de jeu souhaitée, en définissant les mécaniques principales qui régissent les actions des personnages et la résolution des conflits.

### Fonctionnement

Élaboration d'un ensemble de mécaniques de jeu interconnectées, basées sur les principes fondamentaux choisis pour le jeu. Le système doit être suffisamment robuste pour couvrir une variété de situations tout en restant accessible aux joueurs.

### Étapes à suivre

* Définir le concept central et le ton du jeu  
* Choisir le système de résolution principal (dés, cartes, etc.)  
* Concevoir le système de création de personnages  
* Établir les attributs et compétences de base  
* Élaborer les règles de combat et de conflits  
* Définir le système de progression des personnages  
* Créer les règles pour la magie ou les technologies spéciales (si applicable)  
* Développer les mécaniques de gestion des ressources  
* Établir les règles pour les interactions sociales et l'exploration  
* Concevoir un système de récompenses et de conséquences  
* Rédiger les règles pour le maître de jeu (gestion des PNJ, création d'aventures, etc.)

### Résultat attendu

Un système de règles complet et cohérent qui soutient le style de jeu visé, offrant un équilibre entre simplicité d'utilisation et profondeur tactique. Le système doit être suffisamment flexible pour s'adapter à diverses situations de jeu tout en maintenant l'ambiance et le rythme souhaités pour l'expérience de jeu.

### Exemple de Prompt

| En tant que concepteur de jeux de rôle expérimenté (30 ans), aides moi à créer un cadre de règles pour un nouveau jeu de rôle en suivant le modèle ci-dessous. N'hésitez pas à me poser des questions pour clarifier certains aspects ou proposer des alternatives. Template de cadre de règles Concept et ton : Genre : Quel est le genre principal (heroic fantasy, sci-fi, etc.) ? Ton : Quelle est l'ambiance générale (épique, sombre, humoristique, etc.) ? Complexité : Quel niveau de complexité visez-vous (léger, moyen, complexe) ? Système de résolution : Méthode : Quel type de système (d20, pool de dés, cartes, etc.) ? Échelle de difficulté : Comment sont déterminés les seuils ? Succès/Échecs : Comment sont gérés les degrés de réussite ou d'échec ? Création de personnages : Méthode : Comment les personnages sont-ils créés (points, aléatoire, archétypes) ? Attributs : Quels sont les attributs principaux ? Compétences : Comment sont structurées les compétences ? Background : Quelle importance est donnée à l’histoire personnelle ? Combat et conflits : Initiative : Comment est déterminé l’ordre des actions ? Actions : Combien d’actions par tour et comment sont-elles gérées ? Dégâts : Comment sont-ils calculés et appliqués ? Santé : Comment la santé est-elle gérée ? Progression : Expérience : Comment les personnages gagnent-ils de l’expérience ? Amélioration : Comment s’améliorent-ils ? Niveaux : Y a-t-il un système de niveaux ou une progression fluide ? Magie/Technologies spéciales : Système : Comment fonctionnent la magie ou les technologies ? Coût : Quel est le coût d’utilisation (points, fatigue, ressources) ? Apprentissage : Comment acquiert-on de nouveaux sorts ou technologies ? Gestion des ressources : Inventaire : Comment est géré l’équipement ? Économie : Quel système monétaire ou d’échange est utilisé ? Ressources spéciales : Y a-t-il des ressources uniques à gérer (karma, santé mentale, etc.) ? Interactions sociales et exploration : Compétences sociales : Comment sont gérées les interactions sociales ? Exploration : Quelles mécaniques soutiennent l’exploration ? Récompenses et conséquences : Récompenses : Quels types de récompenses sont donnés ? Conséquences : Comment sont gérées les conséquences des actions ? Règles pour le MJ : Création d’aventures : Quelles lignes directrices pour créer des aventures ? Gestion des PNJ : Comment gérer les personnages non-joueurs ? Équilibrage : Quelles règles pour équilibrer défis et récompenses ? Innovations et particularités : Mécaniques uniques : Y a-t-il des mécaniques innovantes ou particulières ? Intégration thématique : Comment les règles renforcent-elles le thème du jeu ? |
| :---- |

## Création d'un attribut

### Objectif 

Définir une caractéristique fondamentale d'un personnage qui reflète ses capacités innées et influence plusieurs aspects du jeu.

### Fonctionnement

L'attribut est une valeur numérique ou descriptive qui sert de base pour de nombreux calculs et tests dans le jeu.

### Étapes à suivre

* Définir le nom et la nature de l'attribut  
* Déterminer l'échelle de valeurs possible  
* Établir comment l'attribut affecte les mécaniques de jeu  
* Créer des descripteurs pour différentes valeurs de l'attribut  
* Définir comment l'attribut peut évoluer au cours du jeu

### Résultat attendu

Un attribut clairement défini, équilibré et intégré aux mécaniques de jeu, qui contribue à la caractérisation du personnage.

### Exemple de Prompt

| En tant que concepteur de jeux de rôle avec 30 ans d’expérience, vous devez m'aider à créer un attribut pour un nouveau personnage de JDR. Utilisez le template suivant pour structurer votre approche. N'hésitez pas à me poser des questions pour clarifier certains aspects ou proposer des alternatives. Template de création d'un attribut Objectif : Définir une caractéristique fondamentale d'un personnage qui reflète ses capacités innées et influence plusieurs aspects du jeu. Fonctionnement : L'attribut est une valeur numérique ou descriptive qui sert de base pour de nombreux calculs et tests dans le jeu. Étapes à suivre : Définir le nom et la nature de l'attribut Questions : Quel type d'attribut est pertinent pour votre jeu (physique, mental, social, etc.) ? Quel nom reflète le mieux la capacité ou la caractéristique que vous voulez inclure ? Déterminer l'échelle de valeurs possible Questions : Quelle échelle de valeurs est appropriée (numérique, descriptive) ? Quelle sera la plage de valeurs (1-10, 1-100, faible à exceptionnel, etc.) ? Établir comment l'attribut affecte les mécaniques de jeu Questions : Quels aspects du jeu l'attribut influencera-t-il (combat, interactions sociales, exploration, etc.) ? Comment ces influences se manifestent-elles en termes de règles et de gameplay ? Créer des descripteurs pour différentes valeurs de l'attribut Questions : Quels sont les descripteurs appropriés pour chaque tranche de valeurs ? Comment ces descripteurs reflètent-ils les capacités du personnage dans le jeu ? Définir comment l'attribut peut évoluer au cours du jeu Questions : Quels mécanismes permettront d'améliorer ou de diminuer l'attribut (quêtes, objets, entraînements, etc.) ? Y a-t-il des événements ou des actions spécifiques qui peuvent modifier l'attribut ? Résultat attendu : Un attribut clairement défini, équilibré et intégré aux mécaniques de jeu, qui contribue à la caractérisation du personnage. Exemple d'utilisation : Décrivez une situation de jeu où l'attribut est utilisé pour illustrer son impact sur le gameplay et la narration. |
| :---- |

## Création d'une compétence

### Objectif

Concevoir une aptitude spécifique que les personnages peuvent développer et utiliser dans le jeu.

### Fonctionnement

La compétence représente une connaissance ou une capacité acquise, généralement liée à un ou plusieurs attributs.

### Étapes à suivre

* Nommer la compétence  
* Définir son domaine d'application  
* Déterminer le(s) attribut(s) associé(s)  
* Établir le système de notation (pourcentage, niveau, etc.)  
* Créer des exemples d'utilisation dans le jeu  
* Définir les mécaniques de progression de la compétence

### Résultat attendu

Une compétence bien définie, avec des applications claires dans le jeu et un système de progression cohérent.

### Exemple de Prompt

| En tant que concepteur de jeux de rôle avec 30 ans d’expérience, vous devez m'aider à créer une compétence pour un nouveau personnage de JDR. Utilisez le template suivant pour structurer votre approche. N'hésitez pas à me poser des questions pour clarifier certains aspects ou proposer des alternatives. Template de création d'une Compétence Objectif : Concevoir une aptitude spécifique que les personnages peuvent développer et utiliser dans le jeu. Fonctionnement : La compétence représente une connaissance ou une capacité acquise, généralement liée à un ou plusieurs attributs. Étapes à suivre : Nommer la compétence Questions : Quel nom reflète le mieux la compétence et son utilité dans le jeu ? Définir son domaine d'application Questions : Dans quels contextes la compétence sera-t-elle utilisée (combat, interactions sociales, artisanat, etc.) ? Quelles actions spécifiques la compétence permettra-t-elle de réaliser ? Déterminer le(s) attribut(s) associé(s) Questions : Quels attributs du personnage influencent cette compétence (force, intelligence, agilité, etc.) ? Comment ces attributs modifient-ils l'efficacité de la compétence ? Établir le système de notation (pourcentage, niveau, etc.) Questions : Quel système de notation convient le mieux (niveaux, pourcentage, descriptions qualitatives) ? Quelle sera la plage de valeurs ou les niveaux possibles ? Créer des exemples d'utilisation dans le jeu Questions : Quelles sont des situations spécifiques où la compétence pourrait être mise en pratique ? Comment la compétence affecte-t-elle les résultats de ces situations ? Définir les mécaniques de progression de la compétence Questions : Quels mécanismes permettent aux personnages d'améliorer cette compétence (entraînement, expérience, objets) ? Y a-t-il des événements spécifiques ou des actions répétées qui influencent la progression de la compétence ? Résultat attendu : Une compétence bien définie, avec des applications claires dans le jeu et un système de progression cohérent. |
| :---- |

## Création d'un avantage/défaut

### Objectif

Concevoir une caractéristique distinctive qui apporte une force ou une faiblesse à un personnage.

### Fonctionnement

L'avantage ou le défaut modifie les capacités du personnage de manière positive ou négative dans certaines situations.

### Étapes à suivre

* Nommer l'avantage/défaut  
* Décrire son effet sur le personnage  
* Déterminer les bonus ou malus mécaniques associés  
* Définir les conditions d'activation ou d'application  
* Établir le coût ou le gain en points de création (si applicable)  
* Créer des exemples de situations où l'avantage/défaut entre en jeu

### Résultat attendu

Un avantage ou un défaut équilibré qui ajoute de la profondeur au personnage et influence le jeu de manière intéressante.

### Exemple de Prompt

| En tant que concepteur de jeux de rôle avec 30 ans d’expérience, vous devez m'aider à créer un avantage ou un défaut pour un nouveau personnage de JDR. Utilisez le template suivant pour structurer votre approche. N'hésitez pas à me poser des questions pour clarifier certains aspects ou proposer des alternatives. Template de création d'un Avantage/Défaut Objectif : Concevoir une caractéristique distinctive qui apporte une force ou une faiblesse à un personnage. Fonctionnement : L'avantage ou le défaut modifie les capacités du personnage de manière positive ou négative dans certaines situations. Étapes à suivre : Nommer l'avantage/défaut Questions : Quel nom reflète le mieux cette caractéristique et son impact sur le personnage ? Décrire son effet sur le personnage Questions : En quoi cette caractéristique influence-t-elle les capacités ou comportements du personnage ? Est-ce une modification positive (avantage) ou négative (défaut) ? Déterminer les bonus ou malus mécaniques associés Questions : Quels sont les effets précis de cette caractéristique sur les mécaniques du jeu (bonus de compétences, malus en combat, etc.) ? Ces effets sont-ils temporaires ou permanents ? Définir les conditions d'activation ou d'application Questions : Dans quelles situations cette caractéristique se manifeste-t-elle ? Y a-t-il des déclencheurs spécifiques ou des conditions nécessaires pour son activation ? Établir le coût ou le gain en points de création (si applicable) Questions : Combien de points de création l'avantage coûte-t-il, ou combien le défaut en rapporte-t-il ? Ce coût ou gain est-il équilibré par rapport à l'effet de la caractéristique ? Créer des exemples de situations où l'avantage/défaut entre en jeu Questions : Quels sont des scénarios typiques où cette caractéristique aurait un impact significatif ? Comment cela pourrait-il influencer le déroulement de la partie ? Résultat attendu : Un avantage ou un défaut équilibré qui ajoute de la profondeur au personnage et influence le jeu de manière intéressante. |
| :---- |

## Création d'un objet

### Objectif

Concevoir un item qui peut être utilisé, porté ou possédé par les personnages dans le jeu.

### Fonctionnement

L'objet a des caractéristiques spécifiques et peut conférer des bonus, permettre des actions spéciales ou avoir une valeur narrative.

### Étapes à suivre

* Nommer l'objet  
* Décrire son apparence et ses caractéristiques physiques  
* Définir ses propriétés mécaniques (bonus, capacités spéciales, etc.)  
* Établir sa rareté et sa valeur  
* Déterminer les conditions d'utilisation ou de port  
* Créer un historique ou une signification culturelle (si pertinent)

### Résultat attendu

Un objet intéressant et utile, bien intégré dans l'univers du jeu et les mécaniques.

### Exemple de Prompt

| En tant que concepteur de jeux de rôle avec 30 ans d’expérience, vous devez m'aider à créer un objet pour un nouveau JDR. Utilisez le template suivant pour structurer votre approche. N'hésitez pas à me poser des questions pour clarifier certains aspects ou proposer des alternatives. Template de création d'un Objet Objectif : Concevoir un item qui peut être utilisé, porté ou possédé par les personnages dans le jeu. Fonctionnement : L'objet a des caractéristiques spécifiques et peut conférer des bonus, permettre des actions spéciales ou avoir une valeur narrative. Étapes à suivre : Nommer l'objet Questions : Quel nom reflète le mieux la nature et l'utilité de l'objet ? Décrire son apparence et ses caractéristiques physiques Questions : À quoi ressemble l'objet (forme, couleur, matériau) ? Y a-t-il des caractéristiques distinctives (inscriptions, symboles, etc.) ? Définir ses propriétés mécaniques (bonus, capacités spéciales, etc.) Questions : Quels effets l'objet a-t-il sur les mécaniques du jeu (bonus aux compétences, capacités spéciales, etc.) ? Ces effets sont-ils temporaires ou permanents ? Établir sa rareté et sa valeur Questions : L'objet est-il commun, rare, ou unique ? Quelle est sa valeur (monétaire ou autre) dans l'univers du jeu ? Déterminer les conditions d'utilisation ou de port Questions : Y a-t-il des restrictions sur qui peut utiliser ou porter l'objet ? L'objet nécessite-t-il des conditions spéciales pour être utilisé (magie, compétences particulières, etc.) ? Créer un historique ou une signification culturelle (si pertinent) Questions : L'objet a-t-il une histoire ou une origine particulière ? Y a-t-il des légendes ou des faits culturels associés à cet objet ? Résultat attendu : Un objet intéressant et utile, bien intégré dans l'univers du jeu et les mécaniques. |
| :---- |

## Création d'un sort

### Objectif

Concevoir une capacité magique ou surnaturelle que les personnages peuvent utiliser.

### Fonctionnement

Le sort a des effets spécifiques, un coût d'utilisation et potentiellement des conditions ou limitations.

### Étapes à suivre

* Nommer le sort  
* Décrire ses effets visuels et narratifs  
* Définir ses effets mécaniques  
* Établir le coût d'utilisation (mana, fatigue, etc.)  
* Déterminer les conditions de lancement (composantes, temps, etc.)  
* Définir la durée et la portée du sort  
* Créer des variations ou des améliorations possibles

### Résultat attendu

Un sort bien équilibré, avec des effets clairs et des applications intéressantes dans le jeu.

### Exemple de Prompt

| En tant que concepteur de jeux de rôle avec 30 ans d’expérience, vous devez m'aider à créer un sort pour un nouveau JDR. Utilisez le template suivant pour structurer votre approche. N'hésitez pas à me poser des questions pour clarifier certains aspects ou proposer des alternatives. Template de création d'un Sort Objectif : Concevoir une capacité magique ou surnaturelle que les personnages peuvent utiliser. Fonctionnement : Le sort a des effets spécifiques, un coût d'utilisation et potentiellement des conditions ou limitations. Étapes à suivre : Nommer le sort Questions : Quel nom reflète le mieux la nature et l'effet du sort ? Décrire ses effets visuels et narratifs Questions : À quoi ressemble le sort lorsqu'il est lancé (lumière, sons, transformations, etc.) ? Comment le sort est-il perçu dans l'univers du jeu ? Définir ses effets mécaniques Questions : Quels sont les effets précis du sort sur les mécaniques du jeu (dégâts, soins, altérations d'état, etc.) ? Ces effets sont-ils instantanés ou progressifs ? Établir le coût d'utilisation (mana, fatigue, etc.) Questions : Qu'est-ce que le personnage doit dépenser pour lancer le sort (mana, points de vie, fatigue) ? Ce coût est-il fixe ou variable en fonction de la puissance du sort ? Déterminer les conditions de lancement (composantes, temps, etc.) Questions : Le sort nécessite-t-il des composantes matérielles, des incantations spécifiques ou un temps de préparation ? Y a-t-il des restrictions quant à l'endroit ou le moment où le sort peut être lancé ? Définir la durée et la portée du sort Questions : Quelle est la durée des effets du sort (instantané, minutes, heures, permanent) ? Quelle est la portée du sort (distance à laquelle il peut être lancé) ? Créer des variations ou des améliorations possibles Questions : Le sort peut-il être amélioré ou modifié (versions plus puissantes, effets additionnels) ? Quelles seraient les conditions pour accéder à ces améliorations ? Résultat attendu : Un sort bien équilibré, avec des effets clairs et des applications intéressantes dans le jeu. |
| :---- |

## Création d'une créature/monstre

### Objectif

Concevoir un être vivant non-joueur qui peut interagir avec les personnages, souvent comme adversaire.

### Fonctionnement

La créature a ses propres statistiques, capacités et comportements qui déterminent comment elle interagit dans le jeu.

### Étapes à suivre

* Nommer la créature  
* Décrire son apparence et ses caractéristiques physiques  
* Définir ses attributs et compétences principales  
* Établir ses capacités spéciales ou attaques  
* Déterminer son comportement et son intelligence  
* Définir son habitat et son rôle dans l'écosystème du jeu  
* Créer des variantes ou sous-espèces (si applicable)

## Résultat attendu

Une créature intéressante et équilibrée qui représente un défi approprié pour les joueurs et s'intègre bien dans l'univers du jeu.

### Exemple de Prompt

| En tant que concepteur de jeux de rôle avec 30 ans d’expérience, vous devez m'aider à créer une créature ou un monstre pour un nouveau JDR. Utilisez le template suivant pour structurer votre approche. N'hésitez pas à me poser des questions pour clarifier certains aspects ou proposer des alternatives. Template de création d'une Créature/Monstre \#\#\#\#\# Objectif : Concevoir un être vivant non-joueur qui peut interagir avec les personnages. Fonctionnement : La créature a ses propres statistiques, capacités et comportements qui déterminent comment elle interagit dans le jeu. Étapes à suivre : Nommer la créature Questions : Quel nom reflète le mieux la nature et l'apparence de la créature ? Décrire son apparence et ses caractéristiques physiques Questions : À quoi ressemble la créature (taille, couleur, forme) ? Y a-t-il des traits distinctifs (cornes, écailles, ailes, etc.) ? Définir ses attributs et compétences principales Questions : Quels sont les attributs principaux de la créature (force, agilité, intelligence, etc.) ? Quelles compétences ou capacités spécifiques possède-t-elle ? Établir ses capacités spéciales ou attaques Questions : Quelles sont les attaques principales de la créature ? Possède-t-elle des capacités spéciales (magiques, physiques, etc.) ? Déterminer son comportement et son intelligence Questions : Quel est le comportement typique de la créature (agressive, territoriale, sociale, etc.) ? Quel est son niveau d'intelligence et comment cela influence-t-il ses actions ? Définir son habitat et son rôle dans l'écosystème du jeu Questions : Où la créature vit-elle habituellement (forêts, cavernes, montagnes, etc.) ? Quel rôle joue-t-elle dans l'écosystème (prédateur, proie, symbiote, etc.) ? Créer des variantes ou sous-espèces (si applicable) Questions : Existe-t-il des variantes ou des sous-espèces de cette créature ? Quelles sont les différences principales entre ces variantes ? Résultat attendu : Une créature intéressante et équilibrée qui représente un défi approprié pour les joueurs et s'intègre bien dans l'univers du jeu. |
| :---- |

## Conclusion

En utilisant un LLM pour générer des tables aléatoires et en les intégrant dans Chartopia, les maîtres de jeu peuvent créer des contextes riches et dynamiques pour leurs campagnes de jeux de rôle.

La combinaison des contextes de scénarios permet de créer des arcs narratifs complexes et engageants. 

L'utilisation de LLM pour auditer et ajuster les scénarios assure que les défis proposés sont équilibrés et accessibles, améliorant ainsi l'expérience globale des joueurs. 

De plus, ces techniques peuvent être adaptées pour des applications professionnelles et éducatives, offrant des simulations de risques, des échanges clients réalistes et des scénarios pédagogiques. 

Enfin, la génération de pitchs d'issues scénaristiques permet de prolonger et d'enrichir les aventures, la création d'histoires de personnage basées sur leurs fiches ajoute une profondeur supplémentaire à la narration, et la réalisation de comptes rendus de partie assure une documentation détaillée des sessions de jeu. 

Cette approche permet une grande flexibilité et une créativité sans limites, tout en maintenant une cohérence narrative grâce à la boucle de rétroaction continue entre les deux outils. Les MJ peuvent ainsi offrir à leurs joueurs des aventures uniques et immersives, où chaque session de jeu est une nouvelle exploration pleine de surprises, en se focalisant sur l’Histoire et le jeu sans perte de temps.

Toutefois, gardez en tête que les LLM sont des modèles mathématiques sans intelligence qui se “contente” d’aligner une suite logique de caractères mais ayant une capacité combinatoire très importante, ce qui renforce l’illusion qu’ils soient dotés d’une capacité de réflexion. 

La production d’un LLM ne doit pas vous dispenser de travailler vos personnages, votre scénario, votre campagne, votre univers ou votre histoire. Bien au contraire, les LLM sont uniquement un moyen d’aller au-delà de ce que vous auriez pu explorer, analyser et rédiger dans une même fenêtre de temps. Ils sont là pour vous assister en vous questionnant sur votre création, en auditant votre rédaction, en mettant en lumière des incohérences narratives, en ajustant votre style ou votre tonalité.

# Ressources

* **Chartopia** : https://chartopia.d12dev.com/  
* **ChatGPT** : https://openai.com/  
* **Claude** : https://www.anthropic.com/  
* **Mistral** : https://mistral.ai/

# Annexes

## Table des rôles

| Rôle | Forces | Faiblesses |
| ----- | ----- | ----- |
| **Auteur de JDR** | Création d'histoires, développement de personnages et de mondes, enrichissement du lore | Peut nécessiter une collaboration avec un designer pour équilibrer les aspects mécaniques |
| **Game Designer (JDR)** | Compréhension des mécaniques de jeu, équilibrage, innovation, intégration dans le système de jeu | Peut manquer de profondeur narrative si focalisé uniquement sur les mécaniques |
| **Maître de jeu (MJ)** | Connaissance pratique de la dynamique de groupe, adaptabilité, expérience des besoins des joueurs | Peut manquer de structure formelle et de théorie de game design |
| **Scénariste** | Capacité à créer des arcs narratifs captivants, dialogues réalistes, développement de scénario | Peut manquer de connaissances spécifiques aux mécaniques de jeu de rôle |
| **Character Designer (JDR)** | Création visuelle des personnages, lieux et objets, amélioration de l'immersion visuelle | Ne contribue pas directement aux aspects narratifs ou mécaniques |
| **Character Developper (JDR)** | Développement détaillé de la personnalité, de l'histoire et de la motivation des personnages | Peut nécessiter une collaboration avec d'autres rôles pour assurer l'intégration harmonieuse dans l'univers de jeu |
| **Éditeur de contenu** | Révision et amélioration des textes, cohérence et correction des erreurs | Peut ne pas contribuer directement à la création de contenu original |
| **Consultant en folklore** | Expertise en mythes, légendes et cultures, enrichissement du background et du lore | Peut manquer de compétences pratiques en game design ou en narration contemporaine |
| **Spécialiste en mécanique de jeu** | Expertise en conception de systèmes de jeu équilibrés et engageants | Peut manquer de compétences narratives et de développement de personnages |
| **Testeur de jeu** | Feedback sur l'expérience de jeu, identification des bugs et des problèmes d'équilibrage | Rôle souvent limité à l'étape de test, ne contribue pas à la création initiale du contenu |
| **Narrateur vocal** | Donne vie aux personnages et aux scènes par la voix, améliore l'immersion audio | Ne contribue pas à la création du contenu écrit ou mécanique |
| **Consultant en psychologie** | Compréhension des motivations des joueurs, développement de personnages psychologiquement réalistes | Peut manquer de compétences spécifiques en game design ou en narration |
| **Créateur de musique/effets sonores** | Ajoute une dimension sonore immersive, création de thèmes musicaux et d'ambiances sonores | Ne contribue pas à la création de contenu écrit ou mécanique |
| **Community Manager** | Interaction avec la communauté des joueurs, feedback des joueurs, gestion des relations publiques | Ne contribue pas directement à la création du contenu de jeu |
| **Traducteur** | Traduction des textes de jeu dans différentes langues, localisation culturelle | Peut manquer de compétences narratives et de développement de jeu |

## Tableau des balises Markdown

| Balise | Description |
| ----- | ----- |
| **\# Titre** | **Créer un titre de niveau 1 (peut aller jusqu'à “\#\#\#\#\#\#” pour un titre de niveau 6).** |
| \*texte\* ou \_texte\_ | Mettre le texte en *italique*. |
| \*\*texte\*\* ou \_\_texte\_\_ | Mettre le texte en **gras**. |
| \*\*\*texte\*\*\* ou \_\_\_texte\_\_\_ | Mettre le texte en ***italique et en gras.*** |
| \_ ou \* | Créer une liste à puces. |
| 1\. , 2\. | Créer une liste numérotée. |
| \[texte\](lien) | Créer un lien hypertexte. |
| \!\[alt\](url image) | Insérer une image avec une description. |
| \> citation | Créer une citation ou un encadré de citation. |
| \--- ou \*\*\* | Insérer une ligne horizontale pour séparer des sections. |
| PNJ | Insérer un tableau à 3 colonnes avec un alignement à droite (\_:) pour un alignement à gauche (:\_), pour un texte centré (:\_:). |

## Exemple d’usage de Chartopia vers un LLM

| Centre de formation  Salle de cours, Gymnase, Laboratoire, Salle de conférence, Bureau des formateurs |
| :---- |

## Exemple d’historique de personnage

| Valeria Karath Histoire de fond Origines : Valeria Karath est née en 10 158 AG au sein de la prestigieuse Maison Karath, une maison noble mineure alliée à plusieurs grandes familles. Élevée dans le luxe, elle a grandi au cœur des intrigues impériales et des traditions anciennes. Son père, un conseiller influent, lui a enseigné les rouages de la politique dès son plus jeune âge, tandis que sa mère, une musicienne renommée, a nourri son goût pour les arts. Événements marquants : Enfant, Valeria a assisté à l’assassinat de son frère aîné lors d’un coup d'État manqué contre leur maison. Cet événement traumatisant l’a marquée profondément et a solidifié sa haine pour les conspirations non fondées et les trahisons injustifiées. À 20 ans, elle a déjoué une tentative d’assassinat contre son père, prouvant son acuité politique et tactique. Objectifs et motivations : Valeria cherche à garantir la survie et la prospérité de sa famille tout en imposant ses idéaux de justice dans l’Empire. Elle se bat pour que les petites maisons, souvent négligées, aient une voix face aux grandes puissances. Son objectif ultime est de réformer l’Impérium de l’intérieur, sans perdre ses racines ou se compromettre avec des technologies qu’elle considère déshumanisantes. Personnalité Traits de caractère : Valeria est charismatique, méthodique et dotée d'une grande intelligence émotionnelle. Sa passion pour la justice et son sens aigu de la responsabilité l’incitent à agir avec pragmatisme tout en restant fidèle à ses convictions. Elle est aussi résiliente, capable de maintenir son calme même face aux trahisons et aux manigances. Forces et faiblesses : Sa maîtrise des arts oratoires et de la manipulation des apparences est son plus grand atout, mais son dégoût profond pour les machines et la technologie peut limiter ses alliances et mettre en péril certaines initiatives stratégiques. Son sens rigide de la justice la pousse parfois à des décisions moralement discutables. Évolution : Au fil du temps, Valeria apprend à tempérer son idéalisme avec un pragmatisme calculé, comprenant que la justice ne peut être imposée sans compromis. Son dégoût pour les technologies évolue également, voyant en elles un outil potentiellement bénéfique lorsque encadré par une éthique stricte. Apparence physique Description : Valeria est une femme de taille moyenne, avec une silhouette élancée. Ses cheveux noirs de jais sont souvent tressés de manière complexe, accentuant son visage aux traits fins. Ses yeux bleu clair sont pénétrants, souvent perçus comme capables de lire dans l’âme des autres. Style vestimentaire : Elle porte des robes somptueuses et élégantes, souvent dans des tons sombres, ornées de motifs subtils évoquant les valeurs de sa maison. Elle est connue pour porter des bijoux discrets mais significatifs, hérités de sa famille. Relations Alliés : Duc Rovan Karath (père, mentor) : Sa principale figure d'inspiration. Lady Kalina Sulten (alliée politique) : Une amie de confiance issue d'une autre maison mineure. Helio Drask (ancien amant) : Un conseiller rusé et ancien amant avec qui elle a gardé de bonnes relations. Ennemis : Lorn Valek (prétendant rival) : Un noble ambitieux qui cherche à miner sa position. Cyra Moritani (rivale politique) : Une intrigante de la maison Moritani, ennemie farouche de Karath. Icarus Richese (technologue) : Un expert en innovations technologiques, qu'elle méprise. Compétences Talents : Maîtrise des arts oratoires, tacticienne en diplomatie, assassin discrète. Formation : Formation poussée en politique, musique (luth), et rhétorique. Limites : Dégoût pour la technologie, difficultés à déléguer les responsabilités. Conflits Internes : Valeria lutte pour concilier son idéalisme avec la nécessité de compromis moralement discutables. Externes : Elle doit naviguer entre les ambitions de la maison Karath et ses adversaires impitoyables tout en faisant face à l’ascension des technologies qu’elle considère comme corruptrices. Originalité Caractéristiques uniques : Son mépris profond pour les technologies dans un univers où elles sont omniprésentes la rend à contre-courant des autres nobles. Voix distincte : Elle parle toujours avec une assurance calme, pesant soigneusement chaque mot comme une note dans une symphonie. |
| :---- |

## Exemple de conseil d’interprétation d’un personnage

| Pour t’aider à interpréter Valeria Karath dans Dune : Aventures dans l’Imperium, voici cinq conseils d’interprétation basés sur ses traits de caractère, son histoire, et ses motivations : Parler avec assurance calmeValeria maîtrise l’art oratoire. En jeu, elle devrait toujours prendre le temps de réfléchir avant de parler, comme si chaque mot était choisi avec soin pour maximiser son impact. Utilise un ton posé, sans précipitation, et exprime-toi de manière mesurée, même dans les moments de tension. Exposer un idéal de justice rigide mais nuancéLe sens aigu de la justice de Valeria peut parfois la conduire à des décisions dures, voire cruelles. Lors des dilemmes moraux, fais en sorte que Valeria soit prête à prendre des décisions difficiles au nom d’un bien supérieur, tout en montrant son malaise face aux compromis qu’elle doit faire. Éviter et mépriser les technologiesValeria a un profond dégoût pour la technologie. Lorsqu’elle est confrontée à des machines ou à des innovations technologiques, montre de la réticence, voire un rejet visible. Exprime son mépris par des remarques subtiles ou des critiques acerbes envers ceux qui s’y fient trop. Montrer une loyauté complexe envers la familleBien que Valeria soit profondément attachée à sa famille, les intrigues de pouvoir et les trahisons l’ont marquée. En jouant, laisse transparaître une vigilance constante, même avec ses alliés les plus proches. Elle devrait toujours anticiper la possibilité d’une nouvelle trahison, ce qui affecte sa manière d'interagir avec son père, ses alliés, et ses rivaux. Incarnes le poids de la responsabilitéValeria est constamment tiraillée entre ses responsabilités envers sa maison et ses idéaux personnels. Montre ce poids dans sa posture et ses décisions : elle ne se laisse pas submerger par les émotions, mais ses choix doivent toujours révéler cette tension interne entre pragmatisme et conviction morale. |
| :---- |

## Exemple de scénario

| Titre : LES OMBRES DE KAITAIN Sous-titre : Scénario pour *Dune : Aventures dans l'Imperium*. Nombre de joueurs : 4 à 6\. Complexité : 3 (Scénario avec des intrigues politiques complexes et des défis stratégiques). Pitch du scénario : Les joueurs sont des agents d’une Maison mineure en plein essor, envoyés sur Kaitain, le cœur de l'Imperium. Leur mission est de négocier la libération d'un prisonnier politique, capturé pour avoir défié la Maison Corrino. Ce prisonnier pourrait devenir un allié crucial pour garantir à leur Maison une promotion militaire stratégique. Toutefois, l’influence de puissantes factions et une guerre souterraine risquent de compromettre leur mission. Les joueurs devront naviguer dans les eaux troubles de la diplomatie, de l’espionnage et des luttes d’influence, tout en déjouant les complots de deux Maisons mineures rivales. Acte 1 Pitch de l'acte 1 : Les joueurs arrivent sur Kaitain et rencontrent un conseiller influent de la Bene Gesserit, qui leur offre des informations clés sur l’emplacement du prisonnier. Cependant, leur mission attire l’attention de deux factions rivales ayant des intérêts contraires à leur succès. Le piège se resserre alors qu’ils découvrent la véritable portée de l’intrigue. Scène 1 : Lieu et description : Le Palais de l'Empereur, Kaitain. Un immense bâtiment orné de colonnes dorées et de jardins suspendus, reflet du pouvoir impérial.Protagonistes : Conseiller Kaela Norn (Bene Gesserit) : Femme énigmatique, calme et calculatrice, elle révèle la mission aux joueurs. Duc Harlan Wansir (Maison mineure) : Politicien flamboyant, sous l’apparence d’un allié. Capitaine Terech Orlus (Garde de l'Empereur) : Loyal à la Maison Corrino, il surveille attentivement les joueurs. Scène 2 : Lieu et description : Les bas-fonds de Kaitain. Un marché clandestin rempli de contrebandiers, de mercenaires et d'espions.Protagonistes : Jor Tannes (contrebandier) : Figure influente du marché noir, il propose des informations sur l’endroit où est détenu le prisonnier. Gaius Lorim (informateur de la Maison Corrino) : Homme rusé et calculateur, prêt à vendre des informations contre de l’argent. Rasha Korvin (mercenaire) : Soldat à louer, engagé par une Maison rivale pour surveiller les joueurs. Scène 3 : Lieu et description : Un banquet diplomatique au sein de la Maison Corrino, où la politique et les trahisons se mêlent.Protagonistes : Baroness Letha Norvia (Maison Corrino) : Organisatrice de l’événement, une femme manipulatrice. Émissaire Arkad Narm (Maison mineure alliée) : Opposé à la libération du prisonnier, convaincu de sa supériorité morale. Ingénieur Horlas Tavir (Maison mineure alliée) : Devoué à sa cause, il complote en secret pour saboter les efforts des joueurs. Acte 2 Pitch de l'acte 2 : Les joueurs découvrent que leur mission est plus complexe que prévu : le prisonnier détient des informations dangereuses sur plusieurs Maisons, ce qui attire l'attention de nombreuses factions. Alors que les tensions montent, les joueurs doivent déjouer des attaques clandestines et découvrir les véritables alliances qui se tissent dans l'ombre. Scène 1 : Lieu et description : Une villa secrète, résidence dissimulée du prisonnier.Protagonistes : Prisonnier Aric Valan (ancien politicien) : Stratège, il cherche à manipuler les joueurs pour ses propres intérêts. Hector Laros (espion d'une Maison rivale) : Impliqué dans la surveillance des mouvements des joueurs, déterminé à empêcher la libération. Solana Virek (mercenaire) : Chargée de protéger la villa, mais ayant ses propres intérêts en jeu. Scène 2 : Lieu et description : Les catacombes sous Kaitain, un réseau labyrinthique de tunnels souterrains.Protagonistes : Rava Morlan (ingénieur en chef, Maison rivale) : Expert en sabotage, il tend des pièges mortels dans les catacombes. Kal Ustar (assassin) : Spécialiste de la guerre des Assassins, prêt à tout pour éliminer les joueurs. Skaris Novar (Bene Gesserit infiltrée) : Mystérieuse alliée, elle détient des informations vitales sur les complots rivaux. Scène 3 : Lieu et description : Une salle secrète du Palais de l'Empereur, utilisée pour des négociations secrètes.Protagonistes : Maitre Ordan Valis (Maison Corrino) : Diplomate rigide, il cherche à maintenir la mainmise de l’Empereur. Sira Velan (ambassadrice d’une Maison rivale) : Diplomate aux intentions ambiguës, elle pourrait être une alliée temporaire. Isen Torric (prêtre du culte Orange-Catholique) : Observateur des négociations, gardant une influence subtile. Acte 3 Pitch de l'acte 3 : Les joueurs se retrouvent au cœur d'une bataille politique qui les dépasse. Avec la Maison Corrino et plusieurs Maisons mineures en guerre clandestine, ils doivent conclure la libération du prisonnier tout en évitant une guerre totale. Les alliances changent et la vérité sur les motivations du prisonnier éclate enfin. Scène 1 : Lieu et description : Les salons privés de la Maison Corrino, un décor d’opulence et de tension.Protagonistes : Duc Harlan Wansir (de retour, mais cette fois en tant que traître). Baroness Letha Norvia (jouant un double jeu). Aric Valan (manipulateur, jouant sa dernière carte). Scène 2 : Lieu et description : Le spatioport de Kaitain, dans une tentative de fuite désespérée.Protagonistes : Rasha Korvin (le mercenaire, devenu allié potentiel). Kal Ustar (l’assassin, prêt à tout pour tuer Aric). Sira Velan (dernière chance de négociation). Scène 3 : Lieu et description : Les jardins impériaux, sous les étoiles, lors d’une confrontation finale.Protagonistes : Capitaine Terech Orlus (dernière chance pour la Maison Corrino de prendre l'avantage). Conseiller Kaela Norn (elle révèle ses vraies intentions). Prisonnier Aric Valan (manipulant une ultime fois la situation). Conclusion Les joueurs pourront réussir à libérer Aric Valan, mais sa libération provoque de nouvelles tensions au sein de l'Imperium. Les Maisons mineures se rapprochent du bord du conflit total, tandis que les intrigues de la Bene Gesserit laissent présager une instabilité croissante. Conséquences Succès : La Maison des joueurs obtient une promotion militaire et des ressources importantes. Cependant, les alliances qu’ils ont formées sont fragiles, et la Maison Corrino ne les oubliera pas. Échec : La Maison des joueurs est discréditée, voire détruite. Leur échec ouvre la voie à une guerre civile entre les Maisons Mineures. Suite possible : En cas de succès Pitch 1 : Les joueurs doivent maintenant défendre leur Maison contre les représailles de la Maison Corrino.Pitch 2 : Une nouvelle mission les envoie dans les ruines d’une planète ancienne pour découvrir un secret oublié.Pitch 3 : Leur alliance avec la Bene Gesserit les conduit à infiltrer une faction rebelle au sein de l'Imperium. En cas d’échec Pitch 1 : Les joueurs sont exilés et doivent reconstruire leur influence depuis l’ombre.Pitch 2 : Un mystérieux allié leur propose une mission désespérée pour sauver ce qui reste de leur Maison.Pitch 3 : Une guerre éclate entre les Maisons Mineures, et les joueurs doivent choisir leur camp. Antagonistes Antagoniste 1 : Émissaire Arkad NarmMotivations : Sauver l’Empire de ce qu’il voit comme une corruption interne.Méthodes : Mobiliser des forces clandestines pour saboter les joueurs.Ressources : Un réseau d’espions et de mercenaires. Antagoniste 2 : Ingénieur Horlas TavirMotivations : Faire tomber la Maison des joueurs pour ses propres intérêts.Méthodes : Attaques ciblées, sabotage et guérilla.Ressources : Expertise technique et accès à des armes sophistiquées. Antagoniste 3 : Maitre Ordan ValisMotivations : Préserver la domination de la Maison Corrino.Méthodes : Diplomatie, chantage et espionnage.Ressources : L’appareil impérial et ses agents. Alliés Allié 1 : Conseiller Kaela Norn (Bene Gesserit).Motivations : Manipuler les Maisons pour les objectifs de la Bene Gesserit.Méthodes : Diplomatie, subterfuges et manipulation mentale. Allié 2 : Rasha KorvinMotivations : Argent et opportunités politiques.Méthodes : Force brute, mais pragmatique. Allié 3 : Sira VelanMotivations : Préserver la paix entre les Maisons, mais elle a ses propres ambitions.Méthodes : Négociations habiles et utilisation des réseaux d’information.  |
| :---- |

## 

| En tant que créateur de jeu de rôle expérimenté (30 ans)Rédige un scénario pour le JDR *Vaesen*, avec des descriptions riches, des personnages développés et des défis variés pour captiver les joueurs.En utilisant les informations disponibles et le modèle pour structurer le scénario. Template Scénario Titre (en majuscules) :Sous-titre : scénario pour le jeu de rôle VaesenSystème : Year Zero Engine Epoque : XIX siècleZone géographique : Europe, \[Pays\], \[Ville/Village\] \+ \[Autres éléments important : Forêt\] Nombre de joueurs : (1 à 6\)Complexité : (1 à 3\) Contexte OUVERTURE : ET PUIS :L'INTRIGUE VISE A :POUR : INFLUENCE SECRETE : ANTAGONISTES : VAESEN :   Pitch du scénario (Max. 10 lignes) :  Acte 1Pitch de l'acte 1 (Max. 10 lignes) : Scène 1 (10 à 20 lignes) :Lieu et description (Max. 3 lignes) :Protagonistes principaux (alliés ou antagonistes)\*\*\*Scène 2 : (10 à 20 lignes)Lieu et description (Max. 3 lignes) :Protagonistes principaux (alliés ou antagonistes)\*\*\*Scène 3 : (10 à 20 lignes)Lieu et description (Max. 3 lignes) :Protagonistes principaux (alliés ou antagonistes)\*\*\*  Acte 2Pitch de l'acte 2 (Max. 10 lignes) Scène 1 (10 à 20 lignes) :Lieu et description (Max. 3 lignes) :Protagonistes principaux (alliés ou antagonistes)\*\*\*Scène 2 : (10 à 20 lignes)Lieu et description (Max. 3 lignes) :Protagonistes principaux (alliés ou antagonistes)\*\*\*Scène 3 : (10 à 20 lignes)Lieu et description (Max. 3 lignes) :Protagonistes principaux (alliés ou antagonistes)\*\*\*  Acte 3Pitch de l'acte 3 (Max. 10 lignes) Scène 1 (10 à 20 lignes) :Lieu et description (Max. 3 lignes) :Protagonistes principaux (alliés ou antagonistes)\*\*\*Scène 2 : (10 à 20 lignes)Lieu et description (Max. 3 lignes) :Protagonistes principaux (alliés ou antagonistes)\*\*\*Scène 3 : (10 à 20 lignes)Lieu et description (Max. 3 lignes) :Protagonistes principaux (alliés ou antagonistes)\*\*\*  Conclusion (Max. 10 lignes) : Conséquences (Max. 10 lignes) Succès : Ambigu : Échec : Suite possible : 3 pitchs de scénario En cas de succès du scénario Pitch 1 (Max. 10 lignes) : Pitch 2 (Max. 10 lignes) : Pitch 3 (Max. 10 lignes) : Et en d’échec du scénario Pitch 1 (Max. 10 lignes) : Pitch 2 (Max. 10 lignes) : Pitch 3 (Max. 10 lignes) :  Liste des antagonistesMotivations, méthodes, ressources, et filiation/allégeance. Antagoniste 1 Antagoniste 2 Antagoniste 3 Antagoniste X Liste des alliésMotivations, méthodes, ressources, et filiation/allégeance. Allié 1 Allié 2 Allié 3 Allié X  Contexte additionnel  |
| :---- |

### Shade

| En tant que créateur de jeu de rôle expérimenté (30 ans)Rédige un scénario pour le JDR *Shade*, avec des descriptions riches, des personnages développés et des défis variés pour captiver les joueurs.En utilisant les informations disponibles et le modèle pour structurer le scénario. Template Scénario Titre (en majuscules) :Sous-titre : scénario pour le jeu de rôle ShadeSystème :  Epoque : Renaissance italien avec de la fantasieZone géographique : Clémence Nombre de joueurs : (1 à 6\)Complexité : (1 à 3\) Contexte OUVERTURE : ET PUIS :L'INTRIGUE VISE A :POUR : INFLUENCE SECRETE : ANTAGONISTES :   Pitch du scénario (Max. 10 lignes) :  Acte 1Pitch de l'acte 1 (Max. 10 lignes) : Scène 1 (10 à 20 lignes) :Lieu et description (Max. 3 lignes) :Protagonistes principaux (alliés ou antagonistes)\*\*\*Scène 2 : (10 à 20 lignes)Lieu et description (Max. 3 lignes) :Protagonistes principaux (alliés ou antagonistes)\*\*\*Scène 3 : (10 à 20 lignes)Lieu et description (Max. 3 lignes) :Protagonistes principaux (alliés ou antagonistes)\*\*\*  Acte 2Pitch de l'acte 2 (Max. 10 lignes) Scène 1 (10 à 20 lignes) :Lieu et description (Max. 3 lignes) :Protagonistes principaux (alliés ou antagonistes)\*\*\*Scène 2 : (10 à 20 lignes)Lieu et description (Max. 3 lignes) :Protagonistes principaux (alliés ou antagonistes)\*\*\*Scène 3 : (10 à 20 lignes)Lieu et description (Max. 3 lignes) :Protagonistes principaux (alliés ou antagonistes)\*\*\*  Acte 3Pitch de l'acte 3 (Max. 10 lignes) Scène 1 (10 à 20 lignes) :Lieu et description (Max. 3 lignes) :Protagonistes principaux (alliés ou antagonistes)\*\*\*Scène 2 : (10 à 20 lignes)Lieu et description (Max. 3 lignes) :Protagonistes principaux (alliés ou antagonistes)\*\*\*Scène 3 : (10 à 20 lignes)Lieu et description (Max. 3 lignes) :Protagonistes principaux (alliés ou antagonistes)\*\*\*  Conclusion (Max. 10 lignes) : Conséquences (Max. 10 lignes) Succès : Ambigu : Échec : Suite possible : 3 pitchs de scénario En cas de succès du scénario Pitch 1 (Max. 10 lignes) : Pitch 2 (Max. 10 lignes) : Pitch 3 (Max. 10 lignes) : Et en d’échec du scénario Pitch 1 (Max. 10 lignes) : Pitch 2 (Max. 10 lignes) : Pitch 3 (Max. 10 lignes) :  Liste des antagonistesMotivations, méthodes, ressources, et filiation/allégeance. Antagoniste 1 Antagoniste 2 Antagoniste 3 Antagoniste X Liste des alliésMotivations, méthodes, ressources, et filiation/allégeance. Allié 1 Allié 2 Allié 3 Allié X  Contexte additionnel  |
| :---- |

## Exemple de résultat d’audit de scénario

**Tableau des défis**

| Défi | Nature | Suggestions pour surmonter | Rôle/Métier recommandé |
| :---: | :---: | :---: | :---: |
| Multiples factions antagonistes | Risque de confusion avec les motivations croisées et les alliances changeantes | Simplifier les motivations de certaines factions ou clarifier leur position via des indices ou dialogues clairs | MJ |
| Intrigues politiques complexes | Les joueurs pourraient se perdre dans les nombreuses manigances diplomatiques | Introduire des résumés clairs et périodiques de l’état des factions et leurs objectifs pour aider à suivre | MJ |
| Décisions stratégiques non évidentes | Les choix des joueurs pourraient sembler trop incertains avec peu de visibilité sur les conséquences | Offrir des informations plus explicites ou des indices pour éclairer les décisions critiques | MJ |
| Combat en milieu politique (banquet) | Difficulté à équilibrer les interactions sociales et potentielles confrontations violentes | Prévoir des issues non violentes (intimidation, persuasion) ou un recours aux alliés pour éviter le chaos | MJ, Joueur sénior |
| Le rôle ambigu du prisonnier Aric Valan | Risque que les joueurs ne sachent pas s’il faut le considérer comme un allié ou un antagoniste | Utiliser des dialogues subtils pour donner des indices sur ses véritables intentions sans révéler tout | MJ, Joueur sénior |
| Gestion des scènes multiples (villa, catacombes, spatioport) | La diversité des lieux et des situations peut rendre la progression trop dispersée | Structurer les scènes avec des transitions claires et logiques, en veillant à ce que chaque scène ait un objectif défini | Scénariste, MJ |
| Influence de la Bene Gesserit | Risque que les joueurs sous-estiment l’influence de cette faction importante | Introduire des actions de la Bene Gesserit pour montrer leur pouvoir et influence subtilement | MJ |

---

**Tableau des incohérences**

| Incohérence | Suggestion pour correction | Rôle/Métier recommandé |
| :---: | :---: | :---: |
| Le rôle du Conseiller Kaela Norn semble trop passif malgré son appartenance à la Bene Gesserit | Donner à Kaela un rôle plus actif, notamment via des interventions directes dans les moments critiques pour orienter l'intrigue | Scénariste |
| Le lien entre les Maisons mineures et la Maison Corrino manque de clarté concernant les motivations d'Arkad Narm et Horlas Tavir | Clarifier l’allégeance et les motivations de ces personnages en reliant leurs actions à des objectifs plus compréhensibles par les joueurs | Scénariste |
| L’introduction du marché clandestin semble trop rapide, sans exposition du rôle des contrebandiers | Insérer une brève explication de l’importance du marché noir sur Kaitain et de l’influence des contrebandiers pour ancrer la scène | Scénariste |
| Le prisonnier Aric Valan est présenté comme un politicien, mais ses compétences ou son utilité future sont floues | Développer son rôle en expliquant ce qu’il peut réellement offrir aux joueurs une fois libéré (informations, alliance, influence) | Scénariste |
| Trop d’antagonistes peuvent surcharger les joueurs, en particulier avec des méthodes similaires (sabotage, espionnage) | Réduire le nombre d’antagonistes ou rendre leurs approches plus distinctes pour éviter la redondance | Scénariste |

## Exemple de résultat de proposition d’améliorations de scénario

| Pour améliorer le scénario en prenant en compte la fluidité, l’accessibilité et le plaisir de jeu, je propose une série d’ajustements qui respectent les directives mentionnées, en me basant sur les défis et incohérences identifiés dans le contexte du scénario. Voici des solutions concrètes pour simplifier les énigmes, rééquilibrer les combats et offrir des alternatives à des situations nécessitant des compétences rares : Simplification des énigmes complexes 1.Énigme liée aux motivations politiques Problème : Les joueurs pourraient se perdre dans la complexité des motivations des factions et des alliances. Solution : Remplacer les intrigues trop alambiquées par des énigmes plus directes basées sur des objectifs clairs. Par exemple : Indices visuels : Utiliser des lettres ou des messages codés trouvés lors des interactions (comme dans la scène du banquet ou du marché clandestin) qui révèlent explicitement qui soutient ou s'oppose aux joueurs. PNJ révélateurs : Introduire des PNJ qui fournissent des informations critiques sous la forme de « rumeurs » faciles à interpréter. Ces rumeurs pourraient être accessibles via des jets sociaux simples ou en échangeant des informations utiles. Objectif unique : Au lieu de plusieurs factions opposées avec des buts conflictuels, réduire à deux objectifs principaux que les joueurs doivent clarifier et choisir. 2.Énigme de libération du prisonnier Problème : La complexité des catacombes et les pièges tendus par l’ingénieur peuvent perdre les joueurs. Solution : Plan simplifié : Réduire le nombre de chemins ou de pièces dans les catacombes et créer une carte simple pour guider les joueurs avec des indices sur les pièges visibles à travers des indices audio ou visuels (par exemple, des bruits mécaniques, des marques anciennes sur les murs). Raccourcis via compétences : Offrir une option de dialogue ou une interaction basée sur un jet social avec un PNJ captif qui donnerait des indications pour éviter les pièges. Rééquilibrage des combats 1.Combat lors du banquet diplomatique Problème : Risque de déséquilibre entre les personnages axés sur les compétences sociales et ceux orientés vers le combat. Solution : Limiter les confrontations violentes : Si un combat éclate, créer des conditions où la confrontation physique n'est pas la meilleure option. Par exemple, les gardes sont trop nombreux et imposants, ce qui incite à une fuite rapide ou à l’utilisation d’un gadget technologique (fumigène, hologramme pour diversion). PNJ ou objet tactique : Introduire un PNJ qui intervient pour calmer la situation ou fournir un objet utile, comme un dispositif de brouillage temporaire qui pourrait aider à éviter une confrontation directe. 2.Combat contre les mercenaires Problème : Les combats contre les mercenaires ou les espions risquent d’être déséquilibrés si les joueurs n’ont pas les compétences martiales nécessaires. Solution : Adoucir les adversaires : Réduire les caractéristiques des ennemis en termes de dégâts ou d’armure, mais introduire des éléments environnementaux pour rendre le combat plus stratégique (ex. utiliser l’obscurité des catacombes pour des attaques furtives, des équipements pour piéger les ennemis). Ressources disponibles : Donner aux joueurs des gadgets ou des objets spécifiques pour rééquilibrer les combats (bombes fumigènes, drones de distraction, boucliers personnels temporaires). 3.Combat dans les catacombes Problème : Les pièges des catacombes et la confrontation avec des saboteurs peuvent être trop difficiles pour les joueurs. Solution : Donner des chances de désamorcer : Ajouter des moments de reconnaissance où les joueurs peuvent désamorcer des pièges ou désactiver des obstacles avant d'affronter des ennemis. Ces actions peuvent être plus basées sur des compétences de perception ou d'ingéniosité, afin de permettre à des personnages non-combattants de participer. Combats en plusieurs phases : Plutôt que des combats longs, séparer en plusieurs phases où les joueurs peuvent se retirer ou préparer une embuscade en exploitant le terrain. Alternatives pour les compétences rares 1.Situation nécessitant des compétences sociales (négociations) Problème : Certains joueurs pourraient ne pas avoir de compétences sociales élevées (comme la persuasion ou la négociation). Solution : Alternatives avec objets ou astuces : Les joueurs peuvent utiliser des gadgets, des documents ou des preuves collectées tout au long de l’aventure pour influencer les PNJ. Par exemple, montrer une preuve compromettante pour convaincre un diplomate sans avoir à faire un jet de persuasion. Partage des responsabilités : Les joueurs avec des compétences techniques ou martiales peuvent participer à des négociations en apportant des informations qu’ils ont découvertes (comme des données techniques ou des menaces tactiques), permettant ainsi à chaque joueur d’avoir un rôle actif. 2.Situation nécessitant des compétences technologiques (désamorçage de pièges) Problème : Les compétences de type technologique peuvent être rares dans certains groupes. Solution : Simplification des interactions technologiques : Introduire des moyens moins spécialisés pour désamorcer les pièges ou hacker les systèmes, comme trouver un objet clé ou résoudre une énigme simple (par exemple, un code à décoder ou un système d’interrupteurs basé sur la logique plutôt que sur les compétences techniques pures). Aide contextuelle : Offrir des opportunités de collaboration avec des PNJ, par exemple un mercenaire ou un espion qui peut désamorcer un piège si les joueurs le convainquent (avec des compétences sociales ou des ressources). 3.Situation de reconnaissance ou d’espionnage Problème : Certains joueurs peuvent ne pas avoir de compétences furtives ou de perception. Solution : Aide d’un compagnon : Introduire un PNJ allié ou un drone qui aide à surveiller ou à espionner à distance si aucun joueur n’a les compétences nécessaires. Actions en groupe : Permettre aux personnages non furtifs d’utiliser d’autres stratégies (distraction, déguisement) pour réussir l’infiltration, offrant ainsi des alternatives aux actions furtives classiques. |
| :---- |

## Exemple de résultat de proposition d’issues scénaristiques

| Pitch 1 : La Toile des Conspirateurs Thème : Conspiration au sein du Landsraad Après la libération d’Aric Valan, les joueurs découvrent que celui-ci est impliqué dans une conspiration visant à renverser plusieurs Maisons du Landsraad. Le réseau de conspirateurs, composé de nobles influents, agit dans l’ombre pour déstabiliser les forces politiques en place, profitant de l’instabilité créée par la libération d’Aric. Les joueurs doivent infiltrer ce réseau, en démasquant ses membres, tout en naviguant dans les trahisons et les jeux d’alliances. La Maison Corrino elle-même pourrait être impliquée, ce qui soulèverait la question de la loyauté des joueurs vis-à-vis de l’Empereur. Nouveaux personnages : Espions du Landsraad, agents doubles, membres influents du complot. Nouveaux lieux : Un palais secret sur une planète mineure, les chambres cachées d’un Sénat du Landsraad. Impact : Les révélations bouleversent la hiérarchie du Landsraad et provoquent une lutte pour la survie des Maisons mineures. Pitch 2 : Les Reliques Interdites Thème : Découverte d'anciennes technologies dangereuses Alors qu’Aric Valan révèle des informations secrètes sur un ancien artefact technologique caché depuis des millénaires, les joueurs se lancent dans une quête pour retrouver cette relique interdite par l’Imperium. Ce qui semblait être un simple artefact est en réalité une arme de destruction massive développée avant l'Ère des Machines Pensantes. L’enjeu est de taille : si l’objet tombe entre de mauvaises mains, il pourrait bouleverser l’équilibre des forces dans l’Empire. Ils devront décider s’ils détruisent cette technologie ou l’utilisent à leur avantage. Nouveaux personnages : Agents du Bene Tleilax, scientifiques corrompus, un ancien archiviste détenant les secrets de l’artefact. Nouveaux lieux : Une planète abandonnée où des ruines anciennes cachent l’artefact, un laboratoire secret souterrain. Impact : Si les joueurs échouent, le pouvoir de cet artefact pourrait être une menace pour tout l'Imperium, notamment dans la production d’épice. Pitch 3 : Les Voies du Traître Thème : Trahison et répercussions politiques Un des alliés des joueurs, Rasha Korvin, est révélé comme un traître, ayant vendu des informations cruciales sur la libération d’Aric Valan à une Maison rivale. Ce coup de poignard dans le dos met la Maison des joueurs en grand danger, avec une série d’assassinats et de sabotages orchestrés contre eux. Les joueurs devront naviguer dans une guerre des ombres pour trouver le traître, protéger leur Maison, et peut-être même l'éliminer. Mais la vraie question est de savoir s'ils peuvent se fier à leurs autres alliés, ou s'ils sont eux aussi corrompus. Nouveaux personnages : Un maître espion, des assassins du Bene Gesserit, un seigneur rival influent. Nouveaux lieux : Quartiers dissimulés dans la capitale d'une Maison rivale, une prison secrète sur Kaitain. Impact : La trahison provoque un bouleversement des alliances entre Maisons et pourrait mener à un conflit ouvert. Pitch 4 : Le Prix de l’Épice Thème : Tensions autour de la production d’épice Les tensions montent autour de la production d’épice, et une Maison mineure rivale tente d’établir son propre monopole sur une planète secondaire possédant des gisements inattendus. Cette découverte menace l'équilibre du pouvoir entre les Maisons, et les joueurs sont envoyés pour négocier ou saboter les opérations de cette Maison rivale. Cependant, la Guilde Spatiale et le Bene Gesserit s’impliquent également, cherchant à contrôler cette nouvelle source d’épice. Les joueurs devront choisir leurs alliés avec soin, car chaque faction a son propre agenda, et tous ne veulent pas simplement de l’épice… Nouveaux personnages : Un négociateur de la Guilde Spatiale, une Révérende Mère du Bene Gesserit, un seigneur mineur avide de pouvoir. Nouveaux lieux : Un désert toxique abritant les gisements d’épice, un spatioport en orbite autour de cette planète. Impact : Si les joueurs échouent, la Maison rivale pourrait obtenir un avantage décisif dans la production d’épice, menaçant l'équilibre économique de l'Imperium. Pitch 5 : Les Ombres du Bene Tleilax Thème : Manipulations génétiques et guerre clandestine Des rumeurs commencent à circuler sur des expériences menées par le Bene Tleilax, impliquant des clones d’importants dirigeants du Landsraad. L'un de ces clones aurait pris la place d’un membre influent du Landsraad, bouleversant les intrigues politiques. Les joueurs sont engagés pour infiltrer un laboratoire secret du Bene Tleilax et découvrir la vérité. Ils devront faire face à des créatures génétiquement modifiées, des troupes d'élite et des secrets sur l'immortalité interdite. En parallèle, ils pourraient être confrontés à des dilemmes moraux : révéler ces clones risque de plonger l’Empire dans une guerre civile. Nouveaux personnages : Un Maître Tleilaxu, un clone infiltré dans le Landsraad, un espion Bene Gesserit en mission secrète. Nouveaux lieux : Un laboratoire caché au sein d’un astéroïde, des installations médicales clandestines. Impact : Les révélations sur les clones bouleversent la politique impériale, mettant en péril l’intégrité du Landsraad. Pitch 6 : Les Cendres du Soulèvement Thème : Révolution sociale et conflit ouvert Suite aux répercussions de la libération d’Aric Valan, une série de soulèvements sociaux éclatent dans plusieurs systèmes contrôlés par des Maisons mineures. Ces révoltes, alimentées par des promesses de justice et d'égalité, sont soutenues en secret par une faction rebelle liée à des idéaux interdits. Les joueurs doivent intervenir pour rétablir l’ordre, mais ils découvrent rapidement que cette révolution est orchestrée par une force extérieure, peut-être même par la Maison Harkonnen ou un autre ennemi de l'Imperium. Les joueurs sont pris dans un choix moral : écraser la rébellion pour préserver l'ordre impérial, ou soutenir les idéaux de changement. Nouveaux personnages : Un chef révolutionnaire charismatique, un agent infiltré de la Maison Harkonnen, un gouverneur loyaliste. Nouveaux lieux : Les rues dévastées d'une planète en révolte, un quartier général secret des rebelles. Impact : Si les joueurs échouent, la révolte pourrait s’étendre à d'autres systèmes, menaçant la stabilité de l’Imperium. |
| :---- |

