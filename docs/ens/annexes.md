---
title: Annexes
layout: default
parent: Enseignant
nav_order: 5
---

## L’IA générative en quelques points[^2] 

### Son fonctionnement  

L'intelligence artificielle générative est une branche de l'IA qui couvre de nouveaux outils capables de générer des contenus, comme des textes, des images, de la musique ou des vidéos. De manière simplifiée, un outil d’IA générative de texte comme ChatGPT est basé sur ce qu'on appelle un modèle de langage (tel que GPT 4, LLaMa, LaMDA, etc). Ce modèle a été construit à partir d'énormes quantités de textes existants (web, livres, wikipedia…). L’objectif d’un tel modèle est de prédire le prochain mot le plus probable étant donné une suite de mots préalables initiée par une requête appelée **prompt**, et ce sur base de son apprentissage. L’outil peut ainsi générer une réponse au prompt initial souvent conventionnelle et générale, mais parfois étonnante. Un prompt précis et complet conduit à une réponse plus affinée et spécifique. Au-delà des modèles de langage, des modèles multimodaux permettent d’associer différentes modalités (texte, image, vidéo, son) et de générer sur le même principe les images, vidéos ou sons les plus probables sur base d’une requête d’entrée donnée.   
Si vous voulez comprendre techniquement les fondements des IA génératives, n’hésitez pas à consulter cette [page de ressources pour comprendre l’IA](https://ia4sup.notion.site/Ressources-pour-faire-comprendre-l-IA-73bda07500624d438790eacc14afeccc).  
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

### Principes de base  

Quelques principes de base permettent de s’inscrire dans cette perspective d’assistance et de limiter les risques liés aux usages des IA génératives cités plus haut : 

* **Responsabilité** :   
  * **Autorisation**. N’utilisez une IA générative pour une activité que si cela vous est autorisé. Si nécessaire, vérifiez quelle est la politique de votre établissement, et les consignes de votre enseignant.  
  * **Vérification**. Tout document issu d’une IA générative doit faire l’objet d’une relecture critique et attentive pour éviter les contenus inadéquats et les biais. Les propositions, les références, les faits énoncés doivent être vérifiés.  
  * **Protection des données.** Il ne faut pas transmettre de données personnelles, ni de documents professionnels, *a fortiori* confidentiels à une IA générative qui pourrait les réutiliser. Plus de détails en [annexe](#usages-de-données-avec-les-outils-d’ia-génératives)  
* **Transparence** :   
  * **Indiquez quand vous avez utilisé** une IA générative, et si vous reprenez une partie d’un document généré par une IA, considérez le comme une citation (mettre entre guillemets et citer l’outil, voire partager l’url de la conversation dont elle est issue). Ne pas le faire revient à faire du plagiat.   
  * Il est souvent admis qu’un travail d’amélioration de texte, ou d’aide à la traduction (si ce n’est pas un objectif d’apprentissage) n’ont pas à être mentionnés.  
* **Intégrité académique** et scientifique  
  * L’IA générative ne doit pas compromettre l'authenticité du travail académique. Dans tous les cas, vous devez être en mesure d’expliquer chaque étape du travail et de justifier toutes les notions utilisées.  
* **Développement de compétences :**   
  * L'IA générative doit accompagner, non remplacer, l'apprentissage humain. Les outils d’IAG doivent être vus comme des assistants dans les activités universitaires et non comme substitut au travail et à l’implication de chacun.  
  * Leur utilisation doit être envisagée comme un encouragement au développement de l’esprit d’analyse, de synthèse et de critique.   
* **Maîtrise de l’impact**  
  * Les IA génératives consomment beaucoup de ressources. Limitez son usage à ce qui est réellement nécessaire. Posez-vous la question si une autre solution ne vous permettrait pas d’apprendre aussi bien.

### Dans votre établissement 

Une charte, un cadre d’usage ou une modification du règlement intérieur, qu’elle soit adoptée ou en cours d’adoption reprend sans doute les principes précédents. Renseignez-vous pour vérifier si des règles spécifiques s’appliquent. L’enseignant responsable d’un cours doit pouvoir vous renseigner sur les consignes qui s’appliquent dans son cadre. 

## Comment citer l’usage de l’IA générative 

Pour garantir la transparence et l'intégrité académique, il est essentiel de mentionner explicitement leur usage dans vos productions. Voici quelques recommandations sur comment procéder.

Préciser la nature de l’usage que ce soit dans une section méthodologique ou une section dédiée en fin de document.  
"Certaines parties de ce rapport ont été générées avec l’aide de ChatGPT (OpenAI),  
puis éditées et vérifiées par l’auteur."   
"L’outil ChatGPT a été utilisé pour assister à la rédaction de certaines sections de ce  
document. Les contenus générés ont été vérifiés et adaptés selon les besoins."

Les recommandations actuelles font que l’IA générative n’est pas considérée comme auteur à part entière, notamment parce que vous devez vérifier les résultats. Elle n'apparaît donc pas dans les références d’un document. Néanmoins, si vous utilisez des productions directement issues d’une IA générative, il convient d’indiquer clairement ce contenu (un texte entre guillemets, dans la légende une figure, …) et de citer complètement la source : titre de la conversation, nom et version de l’outil, date de génération du contenu, et localisation du contenu généré (URL partageable). 

Voici un exemple tiré de la [recommandation de MLA](https://style.mla.org/citing-generative-ai-updated-revised/) :  
   
![A digital illustration of two people standing on a beach and facing an ocean and a sky made up of colorful swirls.](https://d1oemxqau9vshd.cloudfront.net/app/uploads/sites/6/2024/09/DALL-E-Expressionist-Painting_9-23-24-768x768.png)
Fig. 1\. “Create an expressionist-style image of two people standing on a beach looking at the ocean” prompt, DALL-E, version 3, OpenAI, 23 Sept. 2024, chatgpt.com/share/66f1c3a3-3f90-8000-9750-82c57c4a6592.

**Ressource**

[How do I cite generative AI in MLA style? (Updated and Revised)](https://style.mla.org/citing-generative-ai-updated-revised/)

## Usages de données avec les outils d’IA génératives

nous reprenons ici la formulation de la charte proposée par l’université d’Orléans:   
“Ne jamais transmettre de **données personnelles[^3]** **ni de documents professionnels**, a fortiori de données ou de documents **confidentiels**. Des données relevant du domaine public peuvent être transmises. Pour tout autre type de document, même sous licence ouverte (par exemple Créative Commons), la transmission est déconseillée (une licence ouverte ne signifie pas nécessairement que tous les droits soient cédés). En cas de doute sur le caractère confidentiel ou public d'une information, il est possible de s’adresser au fournisseur de l'information.  
Dans le cas de la **transmission à l’IA de données ou documents rédigés par l’utilisateur**, il est conseillé à ce dernier d’utiliser toutes les mesures à sa disposition pour qu’ils ne soient pas réutilisés par l’IA dans un contexte autre que celui du dialogue avec l’utilisateur susnommé. Si vous apportez de la propriété intellectuelle (une nouvelle méthode, ou la description d'un matériau unique, une autre invention, etc.) qui n'est pas encore protégée, il y a de fortes chances que vous ne puissiez pas la protéger par la suite.  
En d’autres termes, il est conseillé de faire en sorte que le document ne soit pas intégré au système d’apprentissage global de l’IA (perte de propriété intellectuelle, voire partage de données personnelles). (…) Fondamentalement, ne pas transmettre des informations à une IA générative reste le meilleur moyen de protéger ces informations.”



[^2]:  Beaucoup de documents sur le sujet proposent des explications pertinentes pour décrire le fonctionnement des IA génératives. Cette section reprend en grand partie la section correspondante du [rapport de l’UCL sur l’utilisation responsable de l’IA générative](https://oer.uclouvain.be/jspui/bitstream/20.500.12279/1079.2/1/IAGenerative_Groupe_de_Travail_UCLouvain_2024_06.pdf). 

[^3]:  Une donnée personnelle est toute information se rapportant à une personne physique identifiée ou identifiable(issue du site de la CNIL [https://www.cnil.fr/fr/definition/donnee-personnelle](https://www.cnil.fr/fr/definition/donnee-personnelle) )
