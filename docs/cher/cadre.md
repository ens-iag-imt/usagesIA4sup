---
title: Caractéristiques générales
layout: default
parent: Chercheur
nav_order: 2
---

# Caractéristiques générales \- l’IA générative en quelques points 

## Son fonctionnement 

L'intelligence artificielle générative (IAg) est une branche de l'IA qui couvre de nouveaux outils capables de générer des contenus, comme des textes, des images, de la musique ou des vidéos. De manière simplifiée, un outil d’IA générative de texte comme ChatGPT est basé sur ce qu'on appelle un grand modèle de langage “LLM” (tel que GPT 4, LLaMa, LaMDA, etc). Ce modèle a été construit à partir d'énormes quantités de textes existants (web, livres, wikipedia, forums…). L’objectif d’un tel modèle est de **prédire le prochain mot le plus probable** étant donné une suite de mots préalables initiée par une requête appelée **prompt**, et ce sur base de son apprentissage. L’outil peut ainsi générer une réponse au prompt initial **souvent conventionnelle et générale, mais parfois étonnante**. Un prompt précis et complet conduit souvent à une réponse plus affinée et spécifique. Au-delà des modèles de langage, des modèles multimodaux permettent d’associer différentes modalités (texte, image, vidéo, son) et de générer sur le même principe les images, vidéos ou sons les plus probables sur base d’une requête d’entrée donnée.   
Lors de la génération d’une réponse, le modèle n’accède en principe pas à Internet. Ces IA génératives sont par contre déjà souvent intégrées dans des applications existantes. Ainsi, un navigateur peut intégrer une IA générative afin de résumer les résultats de la recherche et d‘offrir des réponses conversationnelles. 

Les IA génératives permettent d’obtenir des réponses détaillées à toutes sortes de questions, des aides précieuses pour générer ou corriger du contenu. 

## Ses limites et ses risques 
Les outils basés sur l’IA générative peuvent être très puissants. Il ne faut cependant pas perdre de vue les limites suivantes : 

* Ces outils ne sont **pas capables de compréhension**, ni des questions posées, a ni de ce qui est généré. Ils n’ont pas de représentation du monde et ne sont pas une base de connaissances. Dès lors, la fiabilité, la qualité et la précision ne sont pas nécessairement au rendez-vous dans les réponses générées.  
* Ces outils s’appuient sur de **gros volumes de données** parfois décontextualisées.. Ils n’intègrent pas l’ironie, l’humour ou le second degré. De fait, ils peuvent interpréter de travers certaines informations.   
* Ces outils peuvent avoir des **biais**. Ce qui est généré par le modèle dépend des données utilisées lors de l’apprentissage (reproduction des biais présents dans les données d’entraînement) et de la façon dont la supervision a été réalisée, ainsi que des règles imposées (reproduction des biais et choix des concepteurs du modèle).   
* Les résultats et le processus de génération ne sont **pas explicables** et ne peuvent être documentés. Les modèles en tant que tels ne sont pas en mesure d’indiquer la source des contenus ayant servi à la génération de la réponse et il est impossible de remonter des résultats aux prémisses et points de départ (effet de boîte noire).   
* Les réponses sont dérivées des données utilisées lors de l’entraînement et leur **originalité est donc discutable**. 

Il est également important de souligner les risques induits par les outils basés sur l’IA générative : 

* **Génération de contenus inadéquats**. Les réponses générées ou le comportement de ces outils peuvent être inadéquats.  
* **Éthique et droits d’auteur**. L’entraînement de ces outils est souvent basé sur des œuvres protégées et les autorisations pour la phase d’entraînement n’ont souvent pas été clairement obtenues. De plus, les défauts d’explicabilité et de documentation indiqués ci-dessus ne permettent pas, pour un résultat donné, d’identifier si des contenus de ce type ont été utilisés.  
* **Atteinte à la confidentialité des données**. Les outils ne garantissent pas tous la confidentialité des questions posées ni des informations sur l’utilisateur·rice. Intégrer des données personnelles, confidentielles ou sensibles dans un prompt peut donc être risqué.   
* **Reproduction et amplification de discriminations et de stéréotypes**. Les biais statistiques présents dans les données d’entraînement peuvent renforcer les stéréotypes et les discriminations traversant déjà notre société. La supervision de ces modèles par un nombre réduit d’opérateurs privés (situés pour la plupart sur la côte Ouest des Etats-Unis) contribue à une homogénéisation culturelle au détriment de la diversité et de la richesse de cultures locales.   
* **Renforcement des fractures numériques**. L'utilisation de ces outils nécessite certaines compétences numériques. Une généralisation de tels outils peut renforcer la fracture numérique entre les citoyens.   
* **Concentration des acteurs de l’IA générative**. Les coûts élevés de développement des outils technologiques pourraient concentrer le pouvoir entre les mains de quelques grandes entreprises d'intelligence artificielle, influençant ainsi les prix, les technologies, et les orientations de recherche. Ce phénomène pourrait également biaiser les normes techniques, éthiques et réglementaires, augmentant les risques d'abus de pouvoir.   
* **Coût environnemental**. Le bilan carbone de ces outils est actuellement déplorable. En effet, la puissance de calcul nécessaire à l’entraînement des modèles est très grande et proportionnelle à leur taille (qui a tendance à augmenter exponentiellement). L’utilisation d’un modèle pour répondre à une question occasionne lui aussi un coût énergétique. 

Des utilisations déviantes peuvent conduire au risques suivants : 

* **Désordre informationnel et désinformation**. La frontière de plus en plus floue entre contenus synthétiques et authentiques engendre une plus grande confusion informationnelle, réduisant la possibilité pour les individus et citoyen·nes de prendre des décisions éclairées et autonomes.   
* **Utilisation malveillante**. Ces outils peuvent être utilisés de façon malveillante, pour propager de fausses informations, pour générer de la propagande, de l’influence, des contrefaçons, des deep fakes, etc.   
* **Sécurité**. Ces outils peuvent fournir des instructions efficaces ainsi que générer des programmes pour les hackers amateurs.

Dans le cadre de la recherche, d’autres limites spécifiques sont à citer : 

* **Potentiel de falsification des données**. Les IAg peuvent également être utilisées pour créer de fausses données ou manipuler des données existantes. Les chercheurs doivent évaluer chaque donnée de manière critique.  
* **Problèmes de reproductibilité**. Les résultats des IAg peuvent ne pas être reproductibles, car un même modèle peut produire des résultats différents à chaque exécution en raison de la nature aléatoire du processus génératif. Cela peut compliquer la reproduction des résultats et les déclarations de reproductibilité pour les chercheurs.  
* **Ne fonctionne pas comme une bibliothèque de recherche**. Pour les agents conversationnels généralistes, il n'existe pas de référentiel de recherche scientifique ni de bibliothèque sous-jacente que les outils utilisent pour effectuer des recherches. Certains outils se basent sur la bibliothèque proposée par le projet [SemanticScholar](https://www.semanticscholar.org/), mais celle-ci ne couvre pas l’ensemble des ressources scientifiques. Il est indispensable d'utiliser des bases de données de recherche de bibliothèques pour compléter une revue de littérature, mais qui sera d’autant plus efficace que vous aurez mené un travail préalable d’exploration (avec ou sans IA générative).   
* **Criticité**. Les chercheurs débutants risquent de ne pas développer certaines compétences lorsqu'ils utilisent l'IA générative dans leur processus de recherche. Cela affecte leur capacité à rendre des comptes et à évaluer de manière critique les résultats générés par les outils d'IA (voir la conclusion du [guide de l’étudiant](/docs/etu/)). 

## IA générative et science ouverte {#ia-générative-et-science-ouverte}

* todo  
+ citer urfist sur recherche de sources

## Quelques exemples d’IA génératives 

* [ChatGPT](https://chat.openai.com/auth/login) est le premier **agent conversationnel** (chatbot ou ACG) basé sur cette technologie proposé au grand public en novembre 2022\. Il est le service **généraliste** le plus populaire, et propose un accès limité gratuit. Il est capable de répondre à des questions, de tenir des conversations, et de générer du code informatique, d'écrire, de traduire ou encore de synthétiser des textes, des images, … Différentes alternatives, comme [Mistral](https://chat.mistral.ai/chat) (Europe), [Claude](https://claude.ai/), [Gemini](https://gemini.google.com/) (Google), [DeepSeek](https://chat.deepseek.com/) (Chine) existent, avec leurs spécificités. Ne pas hésiter à comparer leurs résultats.   
* [Deepl](https://www.deepl.com/fr/translator) est un service plus ancien (2017), mais spécialisé dans la traduction.   
* [Github Copilot](https://github.com/education/students) permet une génération de code informatique directement dans les environnements de développement, et est gratuit pour les étudiants et les enseignants.  
* [Heygen](https://www.heygen.com/) permet de générer des vidéos.  
* [Perplexity](http://perplexity.ai) pour la recherche internet.

Quelques outils intéressants pour la recherche : 

* [NotebookLM](https://notebooklm.google/) permet de charger un ensemble de documents (au moins jusqu’à 50\) et d’obtenir des réponses basées sur les informations de ces documents. Il propose ainsi des synthèses sous forme pratique : résumé audio ou vidéo, carte mentale, guide d’étude. Vérifiez néanmoins que vous avez le droit de charger les documents dans ce service.   
* Des projets comme [SemanticScholar](https://www.semanticscholar.org/) ou des services comme [SciSpace](https://scispace.com/) permettent d'assister des  tâches de recherche bibliographiques sur les bases de données d’articles scientifiques.  
* Plus de services sont proposés dans la 3ème partie de ce document. 

Pour l’instant, très peu d’établissements proposent une solution souveraine accessible dans le cadre des études, mais cela pourrait évoluer rapidement. 
