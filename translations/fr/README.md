> Français: Traduction assistée par machine de la source anglaise faisant autorité. Native-language corrections are welcome. [Anglais](../../README.md) | [Toutes les langues](../README.md)

# Gardez le dossier. Remplacez le modèle.

![Les dossiers d'une personne restent au même endroit tandis que des parties distinctes gèrent des tâches limitées.](../../illustrations/specialist-assembly-line-vs-giant-chatbot.png)

Robot Brain est un logiciel permettant de préserver l'histoire et le sens du travail humain de longue date. Il ne s'agit pas d'un modèle de langage, d'un chatbot ou d'un service qui transmet chaque question à un modèle.

Les grands modèles linguistiques peuvent rechercher, écrire, expliquer et aider à résoudre des problèmes difficiles. Les services payants construits autour d’eux restent des espaces de travail temporaires. Ils peuvent raccourcir une longue conversation, perdre des instructions antérieures, séparer les conclusions de leurs preuves et continuer à écrire comme si l’histoire manquante était toujours présente. Une personne passe alors plus de temps et d’utilisation payante à reconstruire le contexte déjà fourni.

Ce logiciel change là où réside la valeur durable. Les conversations, documents, décisions, tentatives infructueuses, corrections et questions sans réponse de la personne restent dans les enregistrements qu'elle contrôle. Les programmes locaux peuvent examiner ces dossiers. Un modèle de langage peut être utile pour une tâche sélectionnée, mais sa contribution revient au dossier sous forme de travail daté et révisable. Le modèle peut alors être remplacé sans emporter l’historique avec lui.

[Lisez cette documentation dans une autre langue.](../README.md)

## La différence en un seul point de vue

| Un service de modèle de langage commercial | Robot Brain |
|---|---|
| Produit une réponse à partir du matériel actuellement dans sa vue de travail. | Conserve la source complète et l'historique qui l'entoure. |
| Peut raccourcir ou perdre une conversation antérieure à mesure que le travail augmente. | Enregistre les conversations en dehors de chaque modèle afin qu'elles puissent être réutilisées. |
| Mélange les connaissances acquises à partir de nombreuses sources sans un chemin complet vers chaque source et ses circonstances. | Conserve chaque source connue, découverte ultérieure, correction et désaccord dans un enregistrement distinct. |
| Peut rédiger, rechercher, planifier et juger sa propre réponse en un seul échange. | Permet d'enregistrer, de rechercher, d'analyser, d'écrire, de vérifier et d'approuver des parties séparées avec une autorité limitée. |
| Contrôle le modèle, les règles de service, les limites d'utilisation et les modifications du produit. | Laisse le dossier durable sous le contrôle de la personne. |
| Est rémunéré pour les tentatives infructueuses et les échanges correctifs ainsi que pour le travail utile. | Conserve les échecs et les corrections afin que leurs leçons n'aient pas besoin d'être rachetées. |

Robot Brain peut appeler un modèle linguistique local ou en ligne. Cela n’en fait pas un proxy modèle. Il peut conserver, rechercher, comparer, organiser et reconstruire des travaux antérieurs sans appeler le modèle qui a participé à la conversation d'origine. Lorsqu'un modèle est utile, la demande constitue une étape dans un processus plus vaste qui existe indépendamment de ce modèle.

## Pourquoi cela a été construit

Les modèles polyvalents les mieux rémunérés disponibles au cours du développement étaient des gardiens capables mais peu fiables d'un long travail.

Les échecs enregistrés comprenaient des instructions perdues, des preuves manquantes, des connexions inventées, des réclamations prématurées d'achèvement, des modifications indésirables et des dommages aux fichiers de travail. Corriger ces échecs a nécessité plus de demandes, plus de tests, plus d'indemnités versées et plus de temps et d'énergie de la part de la personne. Les services ne restituaient pas automatiquement l'utilisation dépensée pour un travail inutilisable ni les échanges nécessaires à sa réparation.

Le problème était plus important que n’importe quelle mauvaise réponse. Il était demandé à un générateur de texte temporaire de servir de mémoire, d'historien, de chercheur, d'écrivain, de vérificateur et de juge final. Changer de modèle n’a pas changé cet arrangement.

Robot Brain a été construit autour d'un arrangement différent : conserver d'abord le dossier humain, laisser plusieurs pièces remplaçables y contribuer et exiger des preuves en dehors du modèle générateur avant d'accepter un travail important.

## Ce qu'un modèle entraîné ne peut pas garder

Un grand modèle de langage apprend des modèles à partir d’énormes collections de travaux humains. Ces modèles rendent le modèle utile, mais celui-ci n’est pas une bibliothèque des œuvres complètes qui l’ont façonné.

À l’intérieur du modèle, l’influence des livres, des articles, des conversations, des traductions, des communautés, des labels et des commentaires humains est mélangée. Le modèle ne peut généralement pas montrer quelles sources ont façonné une phrase particulière. Il ne peut pas restaurer le but, le public, les preuves, les désaccords, les corrections ultérieures ou les points de vue manquants de chaque auteur.

C’est une perte de sens même lorsque l’œuvre originale existe encore ailleurs. Le modèle conserve une certaine utilité du travail tout en écartant le chemin fiable vers son environnement humain.

Le même problème apparaît lors d’une utilisation ordinaire. Une réponse finale peut survivre après que la conversation qui lui a donné un sens ait été raccourcie. La conclusion demeure, mais les tentatives infructueuses, l'incertitude et les raisons qui la sous-tendent disparaissent de la vision opérationnelle du modèle.

Ce projet ne répond pas à ce problème en formant un autre modèle sur la vie d'une personne. L'histoire personnelle reste lisible et traçable au lieu d'être intégrée à un autre modèle formé. Les modèles fonctionnent avec des enregistrements sélectionnés ; ils ne deviennent pas des disques.

## Ce que fait chaque partie

Le logiciel fonctionnel sépare les tâches qu'un service de chat fait souvent ressembler à une seule activité :

1. **Le gardien de source enregistre ce qui s'est passé.** Il conserve la conversation, le document, l'image ou tout autre élément sans le remplacer par un résumé.
2. **Les copies consultables facilitent la recherche de la source.** Le texte, les descriptions et les index copiés renvoient à la source inchangée et peuvent être reconstruits.
3. **Des lecteurs locaux ciblés examinent des caractéristiques spécifiques.** Des méthodes distinctes examinent le langage, les déclarations, les relations, le raisonnement, le temps, l'expérience humaine et les valeurs. Chacun ne rapporte que ses propres découvertes et les passages qui les sous-tendent.
4. **L'historique maintient les modifications visibles.** De nouvelles découvertes, corrections, désaccords, tentatives infructueuses et questions ouvertes sont ajoutées sans réécrire les événements antérieurs.
5. **Le générateur de requêtes rassemble ce dont un travail a besoin.** Il sélectionne les sources et les conclusions pertinentes et enregistre ce qui a été inclus ou omis.
6. **Un modèle linguistique peut apporter une aide limitée.** Un modèle local peut fournir un aperçu général. Un modèle en ligne peut faciliter les recherches ou la rédaction difficiles. L’une ou l’autre réponse reste une contribution datée qui peut être vérifiée, rejetée ou remplacée.
7. **Des contrôles séparés comparent le résultat avec la demande et les preuves.** Le modèle qui a rédigé une réponse ne peut pas déclarer son propre travail accepté.
8. **Un écran permet à une personne d'utiliser le logiciel.** LeLibreChatfork est l’un de ces écrans. Le remplacer ne remplace pas les disques ou les autres pièces fonctionnelles.

Aucune partie n’est présentée comme un assistant omniscient. Leurs tâches limitées sont ce qui rend chaque pièce remplaçable.

## Rendre une conversation terminée utile à nouveau

Une conversation terminée contient la demande de la personne, les réponses réelles du modèle de langage, le travail tenté, les échecs, les corrections et le point où l'échange s'est terminé. Ces messages préservent ce que le modèle original a apporté sans nécessiter que ce modèle s'explique plus tard.

Des lecteurs locaux ciblés examinent l’échange enregistré sous plusieurs angles. Ils peuvent trouver des modèles et des relations détaillés sans s’appuyer sur une vaste connaissance du monde. Leurs conclusions distinctes restent liées à des parties exactes de la conversation.

Ces résultats peuvent encore nécessiter des connaissances de base ordinaires avant de constituer un compte rendu clair. Pour cette étape limitée, un petitQwenle modèle s'exécute localement à traversvLLM. Il ajoute un aperçu daté qui permet de relier les résultats détaillés et d’expliquer ce que l’échange a accompli.

Qwenne récupère pas les pensées cachées ni l'historique d'entraînement du modèle en ligne. Il fournit de vastes connaissances de base qui ne sont pas propres au modèle original. L'apport utile du modèle original est déjà préservé dans les mots qu'il a produits.

LeQwenl’aperçu est stocké à côté de la source et des résultats antérieurs. Il peut être corrigé ou remplacé. La conversation originale et l’analyse locale détaillée restent inchangées.

## Qu'est-ce qui fonctionne maintenant

L'implémentation actuelle peut conserver une conversation terminée, l'examiner via des méthodes locales distinctes, ajouter une lecture locale de connaissances générales et rassembler chaque contribution retenue dans un enregistrement pouvant être reconstruit ultérieurement.

Il peut également préparer une demande limitée de modèle en ligne lorsqu'une aide extérieure s'avère utile. Ce service reçoit uniquement le matériel sélectionné. Sa réponse renvoie aux archives locales, où les contrôles et l'approbation humaine: et non le modèle: décident de ce qui est conservé.

Il s’agit là de l’accomplissement central : un travail qui dépendait autrefois d’une conversation temporaire peut rester utile après la disparition de son écran de discussion, de son modèle et de son fournisseur.

## Lire l'explication complète

- [Pourquoi les grands modèles de langage ne peuvent pas préserver l'intégralité de l'histoire](01-Why-Large-Language-Models-Cannot-Preserve-the-Full-Story.md)
- [Ce que fait chaque pièce et ce qu'aucun modèle ne contrôle](02-A-Lasting-Record-Outside-the-Model.md)
- [Conserver la correction sans effacer l'erreur](03-How-Knowledge-Changes-Without-Erasing-History.md)
- [Suivre une réclamation jusqu'aux preuves](04-How-Every-Claim-Can-Be-Checked.md)
- [Construisez le document avant d’écrire la prose](05-How-Evidence-Becomes-a-Finished-Document.md)
- [Expliquez la même vérité à différents lecteurs](06-One-Meaning-Different-Readers.md)
- [Garder l'historique privé sous le contrôle de la personne](07-Privacy-and-Control-Stay-With-People.md)
- [Ce que fait la mise en œuvre actuelle](08-What-Works-Today.md)
- [Pourquoi le design s'inspire de nombreux domaines](09-How-Research-Strengthens-the-System.md)
- [Aide sans remettre des dossiers privés](11-Contribute-Without-Giving-Up-Control.md)
- [Mots utilisés dans ces documents](12-A-Short-Guide-to-Key-Terms.md)
- [Suivre une demande à travers les pièces de travail](13-The-Parts-Running-Today.md)
- [Utilisez un modèle de langage pour le travail, pas comme mémoire](15-Why-a-Language-Model-Is-a-Replaceable-Tool.md)
- [Les échecs observés dans les services de modèles linguistiques payants et les garanties qu'ils ont apportées](16-What-Commercial-Language-Model-Services-Got-Wrong.md)
- [Des leçons qui ont changé la conception](17-How-Language-Models-Lose-Meaning-and-How-to-Preserve-It.md)
- [Notes d'utilisation publique, de crédit et de confidentialité](18-Use-Attribution-and-Limits.md)
- [Comment une conversation terminée devient une connaissance durable](19-What-the-System-Accomplishes.md)
- [Ce qui vient ensuite](20-Where-the-System-Goes-Next.md)

## Crédits, sources et droits

- [Qu'est-ce qui a contribué à façonner ce travail](10-What-Helped-Shape-This-Work.md)
- [Recherche derrière la conception](14-Sources-Behind-the-Design.md)
- [Sources, licences et vérifications de diffusion publique](../../SOURCES-LICENSES-AND-PRIVACY.md)

## Licence

Les textes originaux, les diagrammes et les illustrations du projet sont disponibles sous le lien de l'organisation.[Licence Creative Commons Attribution 4.0 Internationale](../../LICENSE.md), sauf si un document indique des termes différents. Le matériel créé par d’autres conserve ses propres droits et conditions.

## Indépendance et confidentialité

Il s'agit d'un projet personnel indépendant développé sur le temps personnel, l'équipement, les comptes et les services payants. Aucun employeur n'y a participé. La mention d’une personne, d’un employeur, d’une institution, d’un fournisseur de modèles, d’un groupe de recherche, d’une règle partagée ou d’un projet extérieur n’implique pas la participation, l’approbation, le partenariat ou l’approbation.

La version publique exclut les enregistrements privés, les détails d'identification, les mots de passe, les informations de connexion privée, les informations sur l'employeur et les instructions pour accéder aux services privés. Les descriptions des échecs du modèle se limitent au comportement enregistré et à ses effets ; ils ne revendiquent pas de causes ou de motifs non divulgués. Les documents ne constituent pas des conseils professionnels ni une promesse de résultats.

![Un chemin depuis la mémoire contrôlée par le fournisseur vers les enregistrements qui restent avec les personnes concernées.](../../illustrations/open-door-human-future.png)
