---
title: Interagir avec une IAg
layout: default
parent: Interagir 
nav_order: 2
--- 

# Interagir avec une IA générative 

## Comprendre les IA génératives pour mieux interagir[^1] 

### Son fonctionnement  

L'intelligence artificielle générative est une branche de l'IA qui couvre de nouveaux outils capables de générer des contenus, comme des textes, des images, de la musique ou des vidéos. De manière simplifiée, un outil d’IA générative de texte comme ChatGPT est basé sur ce qu'on appelle un modèle de langage (tel que GPT 4, LLaMa, LaMDA, etc). Ce modèle a été construit à partir d'énormes quantités de textes existants (web, livres, wikipedia…). L’objectif d’un tel modèle est de prédire le prochain mot le plus probable étant donné une suite de mots préalables initiée par une requête appelée **prompt**, et ce sur base de son apprentissage. L’outil peut ainsi générer une réponse au prompt initial souvent conventionnelle et générale, mais parfois étonnante. Un prompt précis et complet conduit à une réponse plus affinée et spécifique. Au-delà des modèles de langage, des modèles multimodaux permettent d’associer différentes modalités (texte, image, vidéo, son) et de générer sur le même principe les images, vidéos ou sons les plus probables sur base d’une requête d’entrée donnée.   
Lors de la génération d’une réponse, le modèle n’accède en principe pas à Internet. Ces IA génératives sont par contre déjà souvent intégrées dans des applications existantes. Ainsi, un navigateur peut intégrer une IA générative afin de résumer les résultats de la recherche et d‘offrir des réponses conversationnelles. 

Les IA génératives permettent d’obtenir des réponses détaillées à toutes sortes de questions, des aides précieuses pour générer ou corriger du contenu. 

### Ses limites et ses risques  

Les outils basés sur l’IA générative peuvent être très puissants. Il ne faut cependant pas perdre de vue les limites suivantes : 

* Ces outils ne sont **pas capables de compréhension**, ni des questions posées, ni de ce qui est généré. Ils n’ont pas de représentation du monde et ne sont pas une base de connaissances. Dès lors, la fiabilité, la qualité et la précision ne sont pas nécessairement au rendez-vous dans les réponses générées.   
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
* **Utilisation malveillante**. Ces outils peuvent être utilisés de façon malveillante, pour propager de fausses informations, pour générer de la propagande, de l’influence, des contrefaçons, des deep fakes …   
* **Sécurité**. Ces outils peuvent fournir des instructions efficaces ainsi que générer des programmes pour les hackers amateurs. 


En synthèse, une IA générative permet de générer toute forme de contenu, avec un niveau de qualité potentiellement intéressant, mais avec plusieurs limites potentielles qu’il faut connaître pour pouvoir les détecter avant de valider le résultat, suite à une relecture attentive.

## Maîtriser votre discussion 

Nous présentons ici les étapes principales pour interagir efficacement avec une IA générative. Cette interaction se déroule généralement au travers d’une conversation (chat) qui peut donc comporter plusieurs échanges.

### Introduire le sujet 

Une bonne pratique est de proposer une phrase d’introduction permettant de présenter le sujet, et ainsi de vérifier que le sujet de l’échange est bien partagé. 

Exemple : “Le concept de robustesse proposé par Olivier Hamant se popularise dans de nombreux milieux, y compris l'université. Comment cela pourrait se décliner dans une institution universitaire ?”

### Formuler sa demande (le “prompt engineering”) 

Plus la question est claire, meilleure sera la réponse. L’idée ici est de rendre toutes les contraintes explicites. Plusieurs structures sont proposées, nous proposons ici 4 éléments clés : 

| Elément | Objectif | Exemple |
| :---- | :---- | :---- |
| 🎭 Rôle | Qui parle | « Tu es un tuteur en communication scientifique. » |
| 🎯 Tâche | Définir l’objectif | « Explique la différence entre corrélation et causalité …  » |
| 🧱 Contexte  | Fournir les informations utiles (voir section suivante) | « … à un étudiant de master. Voici un extrait du cours à reformuler… » |
| 🗂️ Format | Définir la sortie attendue | « En 5 points, sous forme de tableau comparatif. » |

Si la réponse obtenue n’est pas satisfaisante, n’hésitez pas à itérer l’échange : 

* Pour corriger   
* Pour ajuster  : “Classe les points par ordre d’importance ?”  
* Pour demander des éléments supplémentaires : “Quels auraient été un sixième et un septième point ?”, “Donne deux exemples dans le domaine de la physique”  
* En donnant des exemples pour cadrer la réponse   
* …

### Apporter le bon contexte (le “context engineering”) 

La pertinence de la réponse dépend des éléments de contexte de la conversation. L’introduction permettait une première contextualisation. 

* Il est également possible d’ajouter des fichiers, des données (attention à ce qu’elles ne soient ni personnelles, ni sensibles), parfois l’URL d’une page ou d’un site web. L’outil est également capable d’interpréter des schémas, des images.  
  Exemple : “propose moi un schéma en te basant sur la charte graphique que je te fournis”  
* Encadrer l’usage : “appuie toi uniquement sur ce texte”  
* Préciser le ton de la réponse : “L’étudiant est un débutant”, “écris comme un auteur de roman policier”, “voici des articles que j’ai écris, utilise le même style”  
* Il peut être intéressant de passer par une requête générale avant d’aborder une question spécifique.   
* L’IA générative se base sur l’historique de la conversation, ne pas hésiter à rappeler des échanges précédents qui eux seront sans doute hors contexte actuel. 


### Affiner par la discussion \- collaboration itérative

Interagir avec une IAg, c’est construire une pensée de manière itérative. Il est donc intéressant de relancer la conversation. Par exemple : 

* “Donne un exemple plus simple.”  
* “Explique avec un schéma.”  
* “Adapte pour un public non spécialiste.”  
* “Rends la réponse plus concise ou plus nuancée.”

Une fois un résultat obtenu, n’hésitez pas à le reprendre, à le compléter et à l’adapter en fonction de vos attentes. Vous pourrez ensuite le soumettre à nouveau à l’IAg, pour correction, mais aussi pour challenger le document, en lui demandant des suggestions d’amélioration, ou d’éléments à ajouter. 

### Évaluer et valider la production  

Vous êtes responsable du résultat que vous avez demandé à une IAg. Il est donc indispensable d’effectuer une analyse critique du résultat pour vérifier qu’il n’y a pas d’erreur et que la qualité du résultat est conforme à vos attentes et à celles des personnes à qui vous donnerez accès au résultat.

Si vous diffusez, n’oubliez pas de préciser en quoi l’IAg a contribué au résultat. 

## Maîtrisez les limites 

### La frontière technologique irrégulière de l’IA

Dell'Acqua et al (2023), chercheurs du MIT ont proposé la formule dans leur article [Navigating the Jagged Technological Frontier](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4573321), popularisée par Ethan Mollick dans un article sur Substack, [Centaurs and Cyborgs on the Jagged Frontier](https://www.oneusefulthing.org/p/centaurs-and-cyborgs-on-the-jagged), et reprise récemment dans le domaine de la conception pédagogique par Philippa Hardman [Defining & Navigating the Jagged Frontier in Instructional Design (October, 2025\)](https://drphilippahardman.substack.com/p/defining-and-navigating-the-jagged), et dans le domaine de la [littératie de l’IA](https://libguides.okanagan.bc.ca/c.php?g=743006&p=5383248) par David William.   
L’idée est que l’usage de L'IA crée une frontière technologique irrégulière car elle excelle dans certaines tâches, tout en échouant dans d'autres qui semblent présenter un niveau de difficulté similaire. Ses capacités peuvent varier considérablement, même avec de légères modifications de la formulation, des contraintes ou du contexte de la tâche.   
Il est important de connaître l’existence de cette frontière irrégulière et de suivre son évolution pour pouvoir proposer des usages efficaces.   
Des usages à l’intérieur de cette frontière donneront de bons résultats, permettant un gain de temps. Des usages à la limite de cette frontière donneront des résultats plausibles, mais qui nécessitent un travail de finalisation qui pourra être important, ou s' il n’est pas effectué des résultats qui seront inutiles ou faux. L’usage au delà amène à une dégradation des performances. Cette frontière est évidemment variable suivant les différents modèles utilisés, et avec le temps. 

Au moment de la [rédaction de son article](https://drphilippahardman.substack.com/p/defining-and-navigating-the-jagged) (octobre  2025), Philippa Hardmann propose 3 catégories et des exemples liés à la pédagogie : 

| à l'intérieur de la frontière | dans la zone incertaine | au delà de la frontière |
| :---- | :---- | :---- |
| Identifier les tâches où l'IA est rapide et fiable avec une cohérence minimale et une supervision humaine (attention : produit des résultats moyens par définition). | Identifier les tâches à la limite, où les résultats de l'IA semblent acceptables mais incluent généralement des erreurs et des omissions. | Identifier les tâches où sans une expertise humaine significative à la fois en IA et en conception pédagogique, l'IA dégrade la performance globale.  |
| • Idéation et brainstorming • Mise en forme de contenu • Exécution de tâches techniques | • Génération de contenu • Objectifs d'apprentissage • Questions d'évaluation • Plans de cours et storyboards | • Analyse de besoins • Entretiens avec les parties prenantes et les apprenants • Prise de décision pédagogique • Tâches d'évaluation, par ex. analyse de données |

L’expérience prouve que de nombreuses personnes ont tendance à utiliser les IAg hors de leurs limites sans en avoir conscience, amenant à des résultats décevant en termes de qualité et/ou d’efficacité.

### Accompagner le processus de réponse 

Si une tâche est trop complexe, n’hésitez pas à la décomposer, et à considérer quelles parties peuvent être déléguées à l’IAg.   
Les techniques de [“prompt engineering”](https://www.promptingguide.ai/fr) visent à encourager cette démarche pour permettre de résoudre une tâche plus complexe en conduisant le processus. C’est là que votre expertise peut jouer, mais avec la nécessité d’expliciter tous les tenants utiles à la construction de la réponse, au travers du “context engineering”. 

Une des premières interactions, peut également être de demander à l’IAg de suggérer une telle décomposition. Cette interaction pourra être renouvelée lorsque vous le souhaiterez nécessaire. A vous d‘évaluer cette décomposition pour construire le processus qui vous convient.   
Les modèles les plus récents ont intégré cette démarche en proposant un mode dit de recherche approfondie (deep research), dans lequel l’IAg va d’abord affiner votre requête, vous proposer un plan de recherche, les effectuer, évaluer les résultats, générer un rapport avec des références correctes. Ce mode permet d’obtenir de meilleurs résultats, et de [rendre moins utiles les techniques](https://www.oneusefulthing.org/i/175771315/quick-tips) de “prompt engineering”. 

![](https://substackcdn.com/image/fetch/$s_!FK2m!,w_1456,c_limit,f_webp,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F81d31041-6e92-40a7-878d-c1816535b5f0_2634x1208.png)  
**Figure** : la recherche approfondie en 6 étapes (d’après [Deep Research with AI: 9 Ways to Get Started](https://wondertools.substack.com/p/deepresearch)) 

### Utilisez le bon modèle 

Si le mode “recherche approfondi” donne de meilleurs résultats, il est par contre particulièrement coûteux, car basé sur de multiples requêtes des modèles de langage les plus avancés.   
Le développement des IAg pose de manière aiguë la question de la sobriété numérique. Pour cette raison, mais aussi pour des raisons de performances, il est important de développer une pratique du juste nécessaire. Un modèle plus simple peut donner des résultats satisfaisants pour de nombreux usages.   
 

### N’oubliez pas les alternatives

Les limites présentées ici (la frontière technologique d’une part et la question de la sobriété d’autre part) rappellent que si l’usage de l’IAg peut rendre des services, elle ne s’impose pas d'elle-même. 

Le [Guide d'usages de l'intelligence artificielle générative (IAg) pour des tâches pédagogiques en enseignement supérieur](https://cpu.umontreal.ca/fileadmin/cpu/documents/enseignement-apprentissage/enseigner-numerique/ia/utiliser-iag/GUI_PIM_Usages-IAg.pdf) proposé par CPU Montréal (2025) propose la définition d'usages judicieux.  
 Un usage de l’IAg est jugé judicieux lorsqu’il est perçu par la personne utilisatrice comme un levier et non comme un substitut à l’expertise humaine. Cela signifie qu’elle reste consciente de la manière dont l’outil d’IAg est utilisé : elle est capable de déterminer les tâches réalisées par l’outil et celles7accomplies par un être humain. Cette conscience lui permet de garder le contrôle sur la production et de choisir de déléguer certaines tâches à l’outil. Le produit généré par l’IAg fait systématiquement l’objet d’une validation, cela demeure central pour assurer la pertinence et la qualité des contenus générés. On parle ici **d’agentivité humaine**.

Le développement de l’agentivité fait partie des fondements pédagogiques, et par extension est un [principe de base pour le métier d’enseignant](https://discovery.ucl.ac.uk/id/eprint/10212907/1/1149_25_Promoting%20and%20Protecting%20Teacher%20Agency_Cukurova.pdf). 

Par ailleurs, nos établissements s’engagent dans les usages des IAg pour mieux apprécier les bénéfices, mais aussi les risques apportés par cette technologie. Ce point impose bien que les usages doivent être contrôlés et évalués, mais aussi qu’il soit possible de revenir sur des usages. Un **principe de réversibilité** s’impose donc dans les usages des IAg. 

[^1]:  Beaucoup de documents sur le sujet proposent des explications pertinentes pour décrire le fonctionnement des IA génératives. Cette section reprend en grand partie la section correspondante du [rapport de l’UCL sur l’utilisation responsable de l’IA générative](https://oer.uclouvain.be/jspui/bitstream/20.500.12279/1079.2/1/IAGenerative_Groupe_de_Travail_UCLouvain_2024_06.pdf). 
