> Français: Traduction assistée par machine de la source anglaise faisant autorité. Native-language corrections are welcome. [Anglais](../../15-Why-a-Language-Model-Is-a-Replaceable-Tool.md) | [Toutes les langues](../README.md)

# Utilisez un modèle de langage pour le travail, pas comme mémoire

![Les outils, les fichiers entraînés et les collections de sources conservent des enregistrements séparés de leur origine et de leurs termes.](../../illustrations/tool-model-source-index.png)

Robot Brain n'est pas un modèle de langage avec de la mémoire supplémentaire. C'est le logiciel de tenue de dossiers, d'analyse, d'assemblage et de vérification qui décide quand un modèle de langage serait utile et quel travail limité il peut effectuer.

Le modèle disponible le plus puissant n’est pas toujours le meilleur choix pour ce travail.

Un modèle de langage payant peut convenir aux recherches ou à l’écriture difficiles. Un petit modèle local peut suffire pour une explication générale. Une recherche peut suffire à trouver un passage. Un processus fixe peut être plus sûr lorsque la réponse doit suivre une règle exacte. Parfois, la meilleure réponse est celle qui a déjà été vérifiée et enregistrée.

Le générateur de requêtes fait ce choix en fonction des besoins du travail. Il peut utiliser un modèle, combiner plusieurs méthodes limitées, réutiliser le travail vérifié ou ne faire aucun appel de modèle. C'est pourquoi il ne s'agit pas d'un proxy qui transmet simplement les requêtes à un autre service.

## Modèles en ligne payants

Les services de modèles linguistiques commerciaux ont aidé à construire ce projet. Ils ont soutenu la recherche, le codage, la rédaction et la révision.

Ils ont également perdu des instructions antérieures, raccourci des conversations, deviné des causes, enfoui des réponses courtes dans des remplissages et signalé le travail comme terminé avant de le vérifier. La correction de ces échecs a nécessité davantage d’indemnités versées et plus de temps humain.

Leur limite plus profonde n’est pas une mauvaise invitation. Un modèle entraîné ne peut pas reconstruire l’histoire complète du travail humain qui lui a été enseigné. Il conserve des modèles tout en perdant les liens fiables avec chaque auteur, objectif, public, litige, correction et point de vue manquant.

Cette vaste connaissance est toujours utile. Cela ne devrait tout simplement pas devenir le seul endroit où existe l’histoire d’une personne.

Pour une demande en ligne,Robot Brain enregistre quel modèle a été utilisé, ce qu'il a reçu, ce qu'il a retourné, le coût du service, quels contrôles ont été effectués et si le résultat a été conservé. Le contexte non étayé reste la suggestion du modèle plutôt qu'un fait source.

## Le modèle local n'est pas formé sur la personne

L'installation actuelle exécute un petitQwenmodèle de langage à traversvLLMsur le matériel local.Qwenest un contributeur remplaçable, pas le projet lui-même.

Il n’apprend pas en s’entraînant sur les conversations, le travail ou la vie de la personne. La formation mélangerait cette histoire dans un modèle et affaiblirait le chemin vers les mots et les événements originaux.

Plutôt,Qwenreçoit le matériel sélectionné pour un travail après la fin d'une conversation. D'autres méthodes locales ont déjà examiné la langue, les déclarations, les relations, le raisonnement, le temps, l'expérience humaine et les valeurs de l'échange.Qwenajoute le vaste contexte que ces méthodes ne partagent pas. Il est ainsi plus facile d’expliquer ce qui s’est passé et pourquoi.

Qwenne révèle pas les pensées cachées, la formation ou le raisonnement privé de l'assistant en ligne. La contribution utile de l'assistant en ligne est déjà présente dans la conversation enregistrée. Les connaissances générales ne sont pas propres à cet assistant, donc un autre modèle approprié peut aider à relier les morceaux enregistrés.

LeQwenla lecture est enregistrée avec le nom du modèle et la date. Il reste distinct de la conversation et peut être corrigé ou remplacé ultérieurement. La requête ne doit jamais quitter le matériel local.

## La recherche n'est pas une explication

La recherche peut trouver des passages contenant des mots ou des sujets apparentés. Il ne peut pas décider pourquoi un événement est important, si une action en a provoqué une autre ou ce que quelqu'un voulait dire.

Ces conclusions ont besoin de preuves, d’histoire et de marge de correction.

## Le coût comprend le temps de la personne

Le prix et la rapidité ne sont pas les seuls coûts. Une réponse bon marché devient coûteuse lorsque quelqu'un passe des heures à trouver l'erreur, à expliquer à nouveau l'historique et à réparer le résultat.

Le générateur de requêtes prend donc en compte les frais de service, l'attente, les tentatives, la consommation d'énergie et la vérification humaine. Un modèle plus petit, une méthode locale fixe ou un résultat enregistré peuvent créer plus de valeur lorsque son travail est plus facile à inspecter.

## Les sources restent identifiables

Les documents originaux, les textes copiés, les réponses modèles, les recherches publiques, les citations et les critiques ultérieures restent des choses différentes.

Lorsqu'il est connu et autorisé, le dossier conserve le créateur, le but, l'audience, la date, la langue, les preuves, les désaccords, les droits et les corrections ultérieures. La disponibilité publique et le crédit n'autorisent pas en eux-mêmes la redistribution du matériel protégé.

Ce référentiel comprend de la documentation publique et des illustrations créées par le projet. Il laisse de côté les enregistrements privés, les mots de passe, les détails d'accès, les secrets des fournisseurs et les documents externes dont la publication n'a pas été autorisée.
