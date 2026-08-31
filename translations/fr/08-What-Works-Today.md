> Français: Traduction assistée par machine de la source anglaise faisant autorité. Native-language corrections are welcome. [Anglais](../../08-What-Works-Today.md) | [Toutes les langues](../README.md)

# Ce que fait la mise en œuvre actuelle

![Les idées, les tests, les échecs et les capacités éprouvées restent clairement séparés.](../../illustrations/evidence-implementation-gates.png)

Robot Brain exécute un logiciel permettant de préserver et de reconstruire le sens des œuvres enregistrées. Il ne s’agit pas d’une proposition de chatbot, et sa mise en œuvre actuelle n’est pas un modèle de langage.

## Capacités dans la mise en œuvre actuelle

Les exécutions enregistrées montrent que le logiciel peut :

- conserver une conversation terminée sans la remplacer par un résumé
- garder les mots de la personne séparés des réponses modèles et des interprétations ultérieures
- créer des découvertes détaillées sur le langage, le sens, le raisonnement, le temps, l'expérience humaine et les valeurs
- relier chaque découverte retenue à la partie de la conversation qui la sous-tend
- conserver les corrections, les désaccords, les travaux ratés et les questions sans réponse
- ajouter un aperçu des connaissances générales locales datées sans appeler le modèle en ligne d'origine
- rassembler les contributions retenues pour une reconstruction demandée
- enregistrer ce qui a été vérifié, rejeté, corrigé et accepté
- remplacer un écran ou un modèle de langue participant sans remplacer l'historique enregistré

Ce sont des fonctions du logiciel autour des modèles. Ce ne sont pas des capacités revendiquées pourQwen,LibreChat, ou un assistant en ligne.

## Que s'est-il passé au cours du jalon de conversation terminée ?

La conversation testée a été enregistrée avec les messages de la personne et les réponses du modèle en ligne dans l'ordre.

Des méthodes locales ciblées ont ensuite produit des enregistrements séparés sur l'échange. Leurs travaux portaient sur le langage et le sens, le raisonnement, les observations psychologiques, les observations philosophiques, les relations et le changement au fil du temps. Chaque contribution retenue restait liée au matériel source et à la méthode qui l'avait produit.

Ces méthodes détaillées ne comportent intentionnellement pas les vastes connaissances de base d’un modèle à usage général. Un petit localQwenmodèle, servi parvLLM, lu le matériel sélectionné et ajouté un aperçu daté. Son travail consistait à fournir un contexte ordinaire qui reliait les différentes découvertes et rendait l'échange compréhensible dans son ensemble.

Qwenn'a pas récupéré les pensées cachées du modèle d'origine, l'historique de formation ou l'état interne privé. La contribution utile du modèle original était déjà présente dans ses messages enregistrés. De vastes connaissances de base ont été fournies par un modèle local remplaçable, car ces connaissances n'étaient pas propres au fournisseur d'origine.

## Ce que signifie « terminé » pour cette étape

Le mot fait référence à la liste maintenue des contributions pour cette course. Chaque message source et chaque contribution que le processus a retenu pour la reconstruction peuvent être retrouvés et rassemblés.

Cela ne signifie pas qu’un seul modèle ait fourni une interprétation complète. La réussite est que les pièces acceptées sont préservées, séparées par source et méthode, et disponibles pour la reconstruction sans relancer l'échange en ligne d'origine.

## Comment la demande est soutenue

L'exécution enregistre les parties exécutées, ce que chacune a reçu, ce que chacune a retourné, quelles contributions ont été rejetées et quels contrôles ont été réussis. La reconstruction est mesurée par rapport à sa propre liste enregistrée d'enregistrements attendus.

Un test de composant est décrit comme un test de composant. Une analyse connectée est décrite comme une analyse connectée. Les travaux prévus restent distincts de la mise en œuvre actuelle.

Les prochains travaux incluent des tests indépendants plus larges, la prise en charge d'un plus grand nombre de types d'enregistrements, davantage de langues et de cultures, des écrans de révision plus clairs et une meilleure mesure du temps passé par les utilisateurs à lire et à corriger les résultats.
