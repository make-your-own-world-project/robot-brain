> Français: Traduction assistée par machine de la source anglaise faisant autorité. Native-language corrections are welcome. [Anglais](../../02-A-Lasting-Record-Outside-the-Model.md) | [Toutes les langues](../README.md)

# Ce que fait chaque pièce et ce qu'aucun modèle ne contrôle

![Les sources originales soutiennent une histoire durable tandis que les outils remplaçables effectuent un travail limité.](../../illustrations/core-architecture-layers.png)

Robot Brain est une collection de pièces coopérantes construites autour d’un disque durable. Il ne s’agit pas d’un grand modèle linguistique, d’un groupe de modèles prétendant n’en être qu’un, ou d’un service de chat avec recherche supplémentaire.

La distinction est importante car les problèmes résolus proviennent du fait de demander à un service de modèle de langage temporaire de servir à la fois de mémoire, de chercheur, d'écrivain, de vérificateur et de juge. Ce logiciel sépare ces tâches et conserve l'historique de la personne en dehors de chaque modèle.

## Sauvegarder l'événement avant de l'interpréter

Le gardien source enregistre la conversation, la note, l'image, le document, la tâche ou tout autre élément tel qu'il est arrivé. Il enregistre également les faits réellement connus, tels que l'heure d'arrivée, la source, le créateur une fois établi et l'autorisation une fois enregistrée.

Un nom de fichier, une supposition de modèle ou une interprétation ultérieure ne peuvent pas devenir silencieusement un fait concernant la source. Les informations manquantes restent manquantes.

## Rendre la recherche utile sans remplacer la source

Le logiciel crée des copies consultables telles que du texte extrait, des descriptions et des index. Ces copies renvoient à la source inchangée. Ils pourront être reconstruits lorsqu’une meilleure méthode sera disponible.

Ceci est différent de demander à un modèle de langage de résumer une pile de fichiers, puis de traiter le résumé comme la mémoire. Un résumé est une vue ultérieure. Il ne remplace jamais le matériel qu’il décrit.

## Laisser les lecteurs locaux ciblés faire des conclusions limitées

Des méthodes locales distinctes examinent les caractéristiques définies de la source. Certains s'intéressent à la structure du langage. D'autres identifient des déclarations, des relations possibles, des raisonnements, des changements au fil du temps ou des observations sur l'expérience et les valeurs humaines.

Ces méthodes ne sont pas de petits chatbots. Ils effectuent des travaux restreints sur du matériel sauvegardé. Chaque constatation identifie le passage examiné, la méthode utilisée, la date et les limites connues. Une méthode peut trouver quelque chose, ne rien trouver, refuser de répondre ou échouer. Il ne peut pas réécrire le travail d'une autre méthode.

## Gardez l'histoire comme l'histoire

De nouvelles découvertes s’ajoutent aux événements antérieurs. Les corrections n’effacent pas les erreurs. Une conclusion ultérieure peut devenir actuelle tandis que la conclusion antérieure reste visible avec les preuves et les circonstances qui la soutenaient autrefois.

Cela permet aux travaux ultérieurs de répondre non seulement à « que croit-on maintenant ? » mais aussi « qu’est-ce qui a changé, pourquoi cela a-t-il changé et combien a coûté le changement ? »

## Rassembler des preuves pour une demande

Le générateur de requêtes commence par l'objectif de la réponse ou du document. Il identifie ce dont le lecteur a besoin, rassemble les sources et les conclusions qui portent sur ces questions et enregistre ce qui a été inclus et omis.

Un service de chat commercial demande généralement au modèle de travailler à partir du texte qui correspond à la demande actuelle. Ici, la sélection des preuves est une étape enregistrée en dehors du modèle. Le modèle ne peut pas décider tranquillement que l’absence d’histoire n’a pas d’importance.

## Utiliser des modèles en tant que contributeurs

Un modèle de langage peut être utile pour la recherche, une formation générale ou la rédaction. Il reçoit le matériel sélectionné pour un travail déclaré.

L'installation actuelle utilise également un petit localQwenmodèle dans un but précis : après qu'une analyse locale ciblée a examiné une conversation terminée,Qwenajoute des connaissances de base ordinaires qui aident à relier les résultats séparés. Il ne s'agit pas de mémoire, de récupération de pensées cachées ou de décision sur la signification de l'échange.

Qu'elle soit locale ou en ligne, une réponse modèle est enregistrée en tant que contribution datée. Il peut être vérifié, corrigé, rejeté ou remplacé sans changer de source.

## Vérifier le travail en dehors de l'écrivain

Des contrôles distincts comparent une réponse ou un document terminé avec ses sources, la couverture requise et les limites indiquées. La version exacte qui a réussi est enregistrée.

Un modèle de langage ne peut pas faire valoir ses propres affirmations en écrivant avec confiance. Il ne peut pas non plus faire accepter son propre travail en affirmant qu'il a suivi les instructions.

## Utilisez n’importe quel écran approprié

Le inclusLibreChatfork fournit un écran conversationnel pour demander des résultats de travail et de lecture. Il ne stocke pas le dossier durable, ne dirige pas toutes les autres parties et n'approuve pas les réponses.

LibreChatpeut être remplacé par un autre écran.Qwenpeut être remplacé par un autre modèle adapté. Un fournisseur en ligne peut être modifié ou omis. L'historique source et les travaux acceptés restent utilisables car aucune de ces parties n'en est propriétaire.

## La limite qui définit le projet

Les modèles de langage génèrent des contributions temporaires à partir du matériel qui leur est présenté.Robot Brain préserve la source, organise le travail autour d'elle, enregistre les modifications, prépare des demandes limitées et vérifie ce qui revient.

C'est pourquoi il ne s'agit pas d'un autre modèle de langage, d'un modèle proxy ou d'un meilleur chatbot. Les modèles peuvent participer aux travaux. Le travail ne dépend d’aucun modèle.
