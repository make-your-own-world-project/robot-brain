> Français: Traduction assistée par machine de la source anglaise faisant autorité. Native-language corrections are welcome. [Anglais](../../01-Why-Large-Language-Models-Cannot-Preserve-the-Full-Story.md) | [Toutes les langues](../README.md)

# Pourquoi les grands modèles de langage ne peuvent pas préserver l'intégralité de l'histoire

![Les pièces enregistrées perdent de la valeur lorsque leurs sources, leurs relations et leur historique sont séparés.](../../illustrations/ordinary-storage-loses-context.png)

Les modèles de langage payants les plus puissants utilisés lors de la construction de ce projet pourraient faire un travail impressionnant. Ils pouvaient écrire, rechercher, expliquer et aider à résoudre des problèmes difficiles. Ils ne parvenaient toujours pas à préserver toute l’histoire d’un long projet.

Une réponse ultérieure pourrait mémoriser la conclusion mais perdre les tentatives infructueuses, les corrections et les preuves qui y ont conduit. Les instructions antérieures pouvaient disparaître lorsqu'une conversation devenait trop longue. Le modèle continuerait à écrire comme si rien d’important n’avait été perdu.

C'est un problème sérieux lorsque l'histoire manquante représente le temps, les connaissances ou l'expérience de quelqu'un.

## Les fichiers ne suffisent pas

Un dossier peut contenir chaque note, conversation, image et tâche tout en perdant l'histoire qui les relie.

Des mois plus tard, une personne peut avoir besoin de savoir :

- qu'est-ce qui a commencé le travail
- quelles idées ont été prises en compte
- pourquoi une tentative a échoué
- quelles preuves ont changé le plan
- quelle conclusion est actuelle
- ce qui est encore inconnu
- pourquoi une vieille note est importante maintenant

La recherche peut trouver un fichier contenant des mots similaires. Il ne peut pas répondre de manière fiable à ces questions. L'envoi d'une plus grande pile de fichiers à un modèle de langage ne crée pas non plus de mémoire permanente. Le service voit ce qui a été sélectionné pour cette demande. Une fois la requête terminée, les connexions utiles peuvent à nouveau disparaître.

## La formation perd également le paramètre d'origine

Les modèles de langage apprennent des modèles à partir d’énormes collections de travaux humains. C'est ce qui les rend utiles. C’est aussi pourquoi ils ne peuvent pas servir d’archives fidèles de tout ce qui les a façonnés.

Les idées d’un livre, d’un article, d’une conversation, d’une traduction ou d’une communauté se mélangent aux idées de nombreux autres. Le modèle ne conserve pas chaque œuvre intacte, avec son auteur, son objectif, son public, ses preuves, ses désaccords et les corrections ultérieures qui y sont attachées.

L’œuvre originale peut encore exister ailleurs. Un fournisseur peut également conserver des copies séparées. La perte décrite ici se produit à l'intérieur du modèle formé : il conserve l'influence utile de l'œuvre mais ne peut pas reconstruire la signification humaine complète autour d'elle.

Répéter une phrase n’est pas la même chose que préserver son sens. Un modèle peut reproduire des mots familiers sans savoir pourquoi ils ont été écrits, quelle situation ils décrivent, quelle vision manquait ou ce qui s'est passé plus tard.

## L’histoire manquante cache également des préjugés

Aucun modèle de langage appris du monde entier.

Ses connaissances reflètent ce qui a été écrit, conservé, collecté, traduit, autorisé, étiqueté et sélectionné. Cela reflète également ce qui manquait. Certaines langues et communautés ont beaucoup plus de matériel publié que d’autres. Les archives préservent plus souvent les opinions d’institutions puissantes que les connaissances privées, locales ou orales.

Les personnes qui construisent le modèle font davantage de choix quant à ce qu’il faut supprimer, récompenser, décourager ou considérer comme une bonne réponse. Les règles produit ajoutent une autre couche. Une réponse terminée peut véhiculer toutes ces influences sans montrer laquelle a affecté une phrase particulière.

Une citation trouvée lors d'une nouvelle demande ne révèle pas cet historique complet. Il montre une source utilisée ou nommée pour cette demande, et non tout ce qui a appris au modèle comment interpréter le sujet.

## Ce que ce projet garde à la place

Robot Brain conserve la source avant de demander de l’aide à n’importe quel modèle pour l’interpréter. La source ne change pas lorsqu'un résumé, une correction ou une nouvelle interprétation est ajouté.

Les travaux ultérieurs sont enregistrés à côté avec une date et un lien vers le passage concerné. Une tentative échouée peut rester visible. Une conclusion corrigée peut mettre en évidence les preuves qui l’ont modifiée. Si la raison d'un changement est inconnue, le dossier l'indique.

Lorsqu'une personne a besoin d'une réponse ou d'un document, le générateur de requêtes rassemble la partie de cet historique nécessaire au travail. Le résultat peut être plus court que le disque complet sans prétendre le remplacer.

Un modèle de langage peut aider à obtenir ce résultat. Il ne peut pas effacer les sources, réécrire le passé ou intégrer une supposition non étayée au dossier accepté.

## L'épreuve pratique

Un résultat utile devrait permettre au lecteur de répondre à quatre questions :

1. Ce qui s'est passé?
2. Quelles preuves soutiennent ce récit ?
3. Qu’est-ce qui a changé, échoué ou reste controversé ?
4. Qu'est-ce qui est encore inconnu ?

Si le dossier ne peut pas répondre à l’une de ces questions, un langage soigné ne doit pas masquer la lacune.
