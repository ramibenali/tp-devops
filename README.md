# Titre du projet : « Mise en place d'une chaîne d'intégration continue et déploiement continue CI/CD »

Les micro-services désignent à la fois une architecture et une approche de développement logiciel qui consiste à décomposer les applications en éléments les plus simples, indépendants les uns des autres. Contrairement à une approche monolithique classique, selon laquelle tous les composants forment une entité indissociable.

C’est dans ce contexte que s’intègre ce projet par le biais des applications monolithiques et applications à base de microservices, dans une première étape, fonctionnant en synergie afin d’accomplir une ou plusieurs tâches. 

Dans une deuxième étape, la mise en place d’une usine de développement qui se basera essentiellement sur l’intégration et le déploiement continu.

L’intégration continue sera la pièce maîtresse et le socle indispensable de ce projet. Que ce soit Jenkins ou Gitlab-CI, cela assurera la bonne compilation du code, le jeu des tests unitaires, le packaging, le déploiement et l’exécution des tests dans un environnement d’intégration.

L’intégration continue fiabilisera les activités de développement. Une fois en place, elle autorisera l’organisation du projet à pousser l’industrialisation au-delà des frontières de l’équipe de développement. Ainsi, le code packagé est ainsi archivé dans un référentiel central qui sera utilisée pour le déploiement sur l’ensemble des environnements, y compris la production.

Le déploiement automatisé, une nécessité, permettra d’automatiser progressivement les actions de déploiements auparavant réalisées manuellement par l’équipe d’exploitation (mise à jour de bases de données, déploiement dans un serveur d’applications, etc.).

Ces déploiements automatisés peuvent aller de scripts de déploiement dans les cas les plus simples jusqu’à la recréation complète de l’environnement cible (via des outils comme Docker et Kubernetes). Tout comme le code, ces scripts et paramétrages ont leur place dans un gestionnaire de sources.

L’intégration de Kubernetes, au sein de cette usine de développement, permettra ainsi d’automatiser et de simplifier plusieurs tâches et permettra de composer l’application à partir d’un ensemble de containers. Ainsi cette plateforme, prendra en charge le déploiement et assurera la synchronisation des composants entre eux.

Le schéma suivant illustre l’architecture à mettre en place : [lien](TP-Projet-ArchitectureCI-CD.pdf)

