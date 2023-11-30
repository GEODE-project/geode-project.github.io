---
layout: post
title: Offre de stage M2 Informatique
subtitle: Classification automatique des domaines de connaissance d'entrées lexicographiques
tags: [recrutement]
---



<p style='text-align: justify;'>
Ce stage s'inscrit dans un projet interdisciplinaire dont l’objectif consiste à conduire des études exploratoires en traitement automatique de données lexicographiques extraites du Dictionnaire Universel François-Latin de Trévoux (DUFLT).
Dans ce contexte, le travail de stage s'intéressera à l'expérimentation de méthodes d'apprentissage automatique pour l'entraînement de modèles de classification afin d'identifier automatiquement les domaines de connaissance dans les articles du DUFLT.
De manière générale, nous souhaitons dresser une liste des domaines et sous-domaines de connaissances mentionnés dans chacune des éditions du corpus, afin de quantifier et de comparer la place qu'ils occupent. Cela permettra de mettre en évidence l'évolution qualitative et quantitative de ces domaines dans la série DUFLT entre 1704 et 1771. Dans le cadre du stage, l'expérimentation portera sur les éditions de 1743 et 1771 que nous avons au format numérique.
</p>
<img height="80px" src="/assets/img/logos/logo-aslan.png" alt="ASLAN" />
<img height="80px" src="/assets/img/logos/logo-cnrs.png" alt="CNRS"/>
<img height="80px" src="/assets/img/logos/logo-liris.png" alt="LIRIS"/>
<img height="80px" src="/assets/img/logos/logo-eric.jpg" alt="ERIC"/>
<img height="80px" src="/assets/img/logos/logo-icar.png" alt="ICAR"/>


## Objectifs du stage


<p style='text-align: justify;'>
Le ou la stagiaire devra s'appuyer sur les récentes avancées en intelligence artificielle et en TAL pour proposer des solutions pour la classification des textes. 
Nous nous intéresserons en particulier aux approches neuronales pour la modélisation thématique et aux plongements de mots (ainsi que d’unités plus grandes : phrases, alinéas, articles) pour la modélisation et la spécialisation de modèles de langues. Le volume limité et la segmentation temporelle d’un corpus historique en ancien français rendra difficile l’utilisation pure et simple des modèles pré-entraînés sur des données modernes comme CamemBERT, FlauBERT, BARthez. 
Un premier objectif sera alors d'évaluer les performances de ces modèles de langues pour la tâche de classification supervisée et de comparer les résultats entre les deux éditions du corpus.
Pour cette tâche, le ou la stagiaire pourra s'appuyer sur nos premiers résultats obtenus dans le cadre du projet <a href="https://geode-project.github.io">GEODE</a> sur l’Encyclopédie de Diderot et d’Alembert  [Brenon et al., 2022].
Pour réaliser cette tâche, il sera au préalable nécessaire de construire le jeu de données labellisé à partir des marqueurs de domaines identifiés au sein des documents. La présence des marqueurs (labels) n'est pas systématique dans la version structurée de nos données et peut être implicite dans le contenu des articles. Il sera ainsi nécessaire de développer une méthode pour enrichir la classification du jeu de données en s'appuyant sur des ressources telle qu'une liste de marqueurs de domaines constituée par des experts de ce dictionnaire. Cette étape pourra faire appel aux modèles de langue et à des calculs de similarité sémantique pour annoter les entrées non classées du dictionnaire et constituer les jeux d'entraînement et d'évaluation.
En complément, nous nous intéresserons à la comparaison des modèles entraînés indépendamment sur les deux éditions du corpus et sur l'analyse de l'évolution des domaines d'une édition à l'autre.
Ces analyses pourront amener au développement de solutions adaptées pour intégrer la dimension diachronique du corpus et permettre l’étude de l’évolution de la sémantique et stylistique en fonction de leurs contextes [Christophe et al., 2021, Terreau et al., 2021].
L’enrichissement des données devrait nous aider à construire des espaces de représentation du corpus, possiblement à plusieurs niveaux de granularité (phrase, alinéa, article), qui pourront nous aider à mieux identifier les domaines. Pour cela, étant donné les volumes dont nous disposons et du côté fluctuant des catégories, des approches non ou peu supervisées, comme le clustering par contrainte pourront être explorer. 
</p>

<p style='text-align: justify;'>
Ce stage sera réalisé dans l'équipe DM2L (Data Mining et Machine Learning) du laboratoire <a href="https://liris.cnrs.fr">LIRIS</a> et l'équipe DMD (Data Mining & Decision) du laboratoire <a href="https://eric.msh-lse.fr/">ERIC</a> et en collaboration avec le laboratoire <a href="http://icar.cnrs.fr">ICAR</a>.
</p>

<p style='text-align: justify;'>
Des compétences sont attendues en programmation et en science des données (Machine Learning et Deep Learning). Des connaissances en traitement automatique de la langue (TAL) seront appréciées.
</p>

**Profil recherché** : Master 2 Informatique   
**Lieu du stage** : Laboratoire ERIC, Université Lyon 2, Bron (principalement), avec des visites au laboratoire LIRIS, INSA Lyon, Campus La Doua, Villeurbanne.   
**Période de stage** : 5 à 6 mois entre février et juillet 2024   
**Candidature** : Envoyer un mail présentant votre parcours et vos motivations, votre CV et vos derniers relevés de notes à : <a href="mailto:ludovic.moncla@insa-lyon.fr">ludovic.moncla@insa-lyon.fr</a> et <a href="mailto:julien.velcin@univ-lyon2.fr">julien.velcin@univ-lyon2.fr</a>



## Encadrants

**Ludovic Moncla**, Maître de conférences en Informatique (Laboratoire LIRIS, INSA Lyon)   
**Julien Velcin​**, Professeur en Informatique (Laboratoire ERIC, Université Lyon 2)



## Références


* Brenon, A., Moncla, L., and McDonough, K. (2022). Classifying encyclopedia articles: Comparing machine and deep learning methods and exploring their predictions. Data & Knowledge Engineering, 142 :102098.
* Christophe, C., Velcin, J., Cugliari, J., Boumghar, M., and Suignard, P. (2021). Monitoring geometrical properties of word embeddings for detecting the emergence of new topics. In Moens, M.-F., Huang, X., Specia, L., and Yih, S. W.-t., editors, Proceedings of the 2021 Conference on Empirical Methods in Natural Language Processing, pages 994–1003, Online and Punta Cana, Dominican Republic. Association for Computational Linguistics.
* Terreau, E., Gourru, A., and Velcin, J. (2021). Writing style author embedding evaluation. In Gao, Y., Eger, S., Zhao, W., Lertvittayakumjorn, P., and Fomicheva, M., editors, Proceedings of the 2nd Workshop on Evaluation and Comparison of NLP Systems, pages 84–93, Punta Cana, Dominican Republic. Association for Computational Linguistics
