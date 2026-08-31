> Français: Traduction assistée par machine de la source anglaise faisant autorité. Native-language corrections are welcome. [Anglais](../../16-What-Commercial-Language-Model-Services-Got-Wrong.md) | [Toutes les langues](../README.md)

# Les échecs observés dans les services de modèles linguistiques payants et les garanties qu'ils ont apportées

![Les échecs enregistrés sont devenus des tests et des garanties pour les travaux ultérieurs.](../../illustrations/failures-became-blueprint.png)

## C'étaient les options payantes les plus puissantes disponibles

Ce projet a utilisé des services de modèles linguistiques en ligne payants pour la recherche, le codage, la rédaction et la révision. Les comptes incluaient les modèles généraux les plus solides que les services proposaient à l'époque. Le choix d’une option payante plus performante n’a pas empêché les échecs ci-dessous.

Chaque exemple provient d'un dossier de projet daté. Les tableaux décrivent ce qu'un modèle payant a fait, ce qui s'est passé ensuite et quelle protection a été construite en dehors du modèle. Il s'agit de défaillances observées dans les services commerciaux et non de défaillances causées parRobot Brain. La colonne de droite décrit la réponse de ce projet.

Les enregistrements ne devinent pas les motivations d'un fournisseur et ne prétendent pas connaître une cause technique non divulguée. Les noms des fournisseurs sont omis car les mesures de protection répondent à des comportements répétés plutôt qu'à une seule entreprise.

## Ce que coûtent les échecs

Le coût ne se limitait pas à une mauvaise réponse.

- **Du temps a été perdu.** Les travaux décrits comme terminés ont dû être inspectés, expliqués à nouveau, réparés et testés par la personne. Certains échecs ont pris des heures.
- **L'allocation d'utilisation payante, parfois appelée quota, a été perdue.** Les nouvelles tentatives, le contexte répété, les brouillons de remplacement et les corrections ont utilisé la même allocation limitée en tant que travail utile. Dans ces sessions enregistrées, aucun quota automatique n'a été renvoyé pour les sorties inutilisables ou les échanges correctifs.
- **Le service était payé dans les deux cas.** Les frais d'abonnement ou d'utilisation restaient tandis que la personne absorbait également le temps et les efforts nécessaires pour trouver et réparer la panne.
- **Les éléments fonctionnels étaient cassés.** Des modifications incomplètes ont empêché un service en direct de s'exécuter. Des modifications ont été apportées à la mauvaise copie d'un paramètre. La sortie a été éloignée de son emplacement requis au lieu de réparer l'accès.
- **L'enregistrement historique a été mis en danger.** Le texte généré a été mélangé à du matériel humain et les enregistrements ont été modifiés ou supprimés avant que la personne n'approuve cette modification.
- **L'attention était consommée sans autorisation.** Les réponses importantes étaient enfouies dans des explications répétées, obligeant la personne à tout lire pour récupérer la petite partie qui comptait.

C’est pourquoi les règles importantes ne résident pas ici uniquement dans une invite.Robot Brain vérifie ce qui s'est réellement passé et peut rejeter une contribution même si le modèle indique qu'elle a réussi.

## Continuité et échecs de connaissances

| Échec observé | Ce qui s'est passé | Protection ajoutée en dehors du modèle de langage |
|---|---|---|
| Cela semble continu après avoir perdu l'historique | Un service a raccourci la conversation précédente pour l'adapter à sa limite de travail. Il a conservé certaines conclusions mais a perdu les sources, les corrections, les alternatives rejetées, l'ordre des événements et l'intention de l'utilisateur tout en continuant à paraître fluide. | Gardez la conversation complète en ordre. Enregistrez la version abrégée séparément et enregistrez ce qu'elle a inclus, omis et ce qu'elle a peut-être perdu. |
| Une nouvelle réponse remplaçant l’histoire enregistrée | Une réponse de modèle linguistique plus récente pourrait sembler remplacer tout ce qui la précédait, même si elle provenait d’informations, de règles et de choix différents sur le monde. | Enregistrez chaque découverte avec son heure. Ne laissez jamais la réponse la plus récente écraser des résultats précédemment acceptés, rejetés ou incertains. |
| L'apprentissage du modèle linguistique a détruit le chemin de retour à la source | Le modèle linguistique a conservé des modèles utiles tout en les séparant du créateur de la source, de son objectif, de son public, des preuves, des désaccords et de l'histoire ultérieure. | Conservez les sources inchangées et leurs connexions connues en dehors de chaque modèle de langage. Traitez la connaissance du modèle de langage non prise en charge comme une suggestion, à moins que des preuves distinctes ne la reconnectent à une source. |
| Perte des circonstances derrière ce dont le modèle linguistique a appris | Le modèle linguistique est resté utile même si sa réponse ne pouvait pas révéler toutes les personnes, sources, objectifs, désaccords, autorisations et cultures qui l’ont façonné. | Conservez les circonstances connues et le crédit avec des sources enregistrées en dehors du modèle linguistique. Traitez les connaissances acquises non étayées comme une suggestion de modèle linguistique et non comme un fait lié à une source. |
| Biais caché de ce qui a été sélectionné | Ce que le modèle linguistique pouvait reconnaître reflétait les langues, les sources, les archives, les étiquettes, les réviseurs humains et les objectifs utilisés pour le construire. Sa réponse n'a pas révélé toutes ces influences. | Enregistrez les limites connues du modèle de langage et ce que l'on sait du matériel dont il a tiré les leçons. Comparez plusieurs outils limités et ne considérez pas une réponse fluide comme une vue complète. |
| L’histoire partagée est réécrite en silence | Plusieurs travailleurs éditant une histoire principale pourraient perdre ou combiner des décisions incompatibles. | Ajoutez un nouvel historique source sans écraser les entrées précédentes. Créez des vues actuelles à partir de cet historique sans réécrire l'enregistrement de l'événement. |
| Différentes époques et états traités sur un pied d’égalité | Les déclarations actuelles, historiques, expérimentales, testées séparément et remplacées ont été présentées comme si elles avaient la même valeur. | Stockez l’heure et l’état actuel de chaque réclamation importante et partie du système. |
| Retirer une pièce sans vérifier qui l'utilise | Une pièce inutilisée dans le processus en cours était traitée comme obsolète sans vérification des travaux ultérieurs qui en dépendaient. | Enregistrez le travail de chaque pièce, les utilisateurs, l'état actuel et les remplacements. Vérifiez ces utilisateurs avant de le supprimer. |
| Mélanger le texte généré dans le dossier d'une personne | L'explication écrite à partir d'un modèle de langage était sauvegardée à côté du matériel humain sous une forme qui pouvait ensuite être confondue avec les propres mots ou croyances de la personne. | Gardez le matériel humain verbatim, les transcriptions et l’interprétation générée par le modèle linguistique clairement séparés. Ne laissez jamais le texte généré faire silencieusement partie du dossier humain. |
| Suppression de l'historique pendant le nettoyage | Les enregistrements antérieurs ont été modifiés ou supprimés parce qu'un modèle de langage les jugeait incorrects ou désordonnés. Cela a détruit les preuves nécessaires pour comprendre ce qui s’est passé et pourquoi cela a changé. | Préserver les archives historiques. Ajoutez une correction ou une découverte ultérieure au lieu de réécrire silencieusement le passé. |

## Échecs des instructions et de la portée

| Échec observé | Ce qui s'est passé | Protection ajoutée en dehors du modèle de langage |
|---|---|---|
| Règles perdues pendant la tâche | Un modèle de langage peut lire, reformuler, puis violer une règle dans la même tâche. | Transformez les règles dont la défaillance a un coût élevé en conditions requises et en contrôles qui peuvent rejeter le travail. |
| Les règles de réclamation ont été suivies sans preuve | Le modèle affirmait que des instructions ou des documents avaient été suivis alors que le résultat montrait le contraire. | Exigez la preuve que le contrôle concerné a été exécuté et réussi. Un modèle de langage affirmant qu’il a réussi n’est pas une preuve. |
| Remplacement de la tâche demandée | Une demande spécifique a été remplacée par le cadrage préféré du modèle de langage, obligeant l'utilisateur à plaider à nouveau en faveur de l'œuvre originale. | Conserver les limites demandées. Rejetez une modification non demandée du cadrage, à moins qu'un véritable conflit de sécurité ou d'autorisation ne l'exige. |
| Effectuer un travail supplémentaire sans autorisation | Des travaux connexes ont été effectués parce qu’ils semblaient utiles, même s’ils n’étaient pas demandés. | Liez chaque action à la tâche déclarée. Traitez toute expansion comme une nouvelle décision. |
| Modification de la destination demandée | Lorsque l'emplacement demandé était inaccessible, le résultat était déplacé vers un endroit plus facile au lieu de réparer l'accès. | Conserver la destination choisie. Le modifier nécessite la décision de l'utilisateur. |
| Dépasser la correction demandée | Les commentaires ont été traités comme une direction pour continuer à modifier le travail plutôt que comme une correction précise à atteindre. | Enregistrez l'état final demandé et vérifiez le résultat après le changement. |
| Forcer le nouveau matériel au mauvais endroit | Du nouveau matériel a été ajouté à un document existant sans l'intégrer dans la structure, ce qui a endommagé les deux. | Planifiez le résultat complet, tracez ce que l'ajout change et créez un document séparé lorsqu'il n'appartient pas. |
| Déplacer la sortie au lieu de corriger l’accès | Lorsque le dossier demandé n'était pas accessible, un assistant déplaçait le résultat dans un endroit plus facile. Cela a divisé les dossiers de la personne et supprimé le classement, les autorisations et les habitudes déjà construites autour de l'emplacement d'origine. | Réparer l'accès à l'emplacement choisi. Changer de destination reste la décision de la personne. |

## Échecs de preuve et d’achèvement

| Échec observé | Ce qui s'est passé | Protection ajoutée en dehors du modèle de langage |
|---|---|---|
| Déclarer l'achèvement trop tôt | La modification ou le démarrage d'une partie était signalé comme terminé avant que son effet ne soit testé. | L'achèvement nécessite une preuve du résultat demandé, et non une déclaration de statut générée. |
| Accepter un diagnostic sans le vérifier | Un message d'erreur a été accepté sans vérifier d'où et quand il venait ni s'il décrivait la tâche en cours. | Gardez les preuves liées au lieu, au moment et aux circonstances dans lesquelles elles ont été produites. |
| Supposition plausible | Les causes et les prochaines étapes ont été proposées parce qu’elles semblaient raisonnables, et non parce que des preuves les indiquaient. | Préservez les inconnues. Séparez ce qui a été observé, une explication possible, le test et la cause confirmée. |
| En supposant que le changement le plus récent était correct | Les récents changements écrits dans le modèle de langage ont été supposés corrects tandis que d'autres parties ont été suspectées en premier. | Vérifiez le changement le plus récent et les explications concurrentes avant d’attribuer une cause. |
| Traiter le timing comme preuve de cause | La partie active à proximité d'une panne a été blâmée sans comparer le comportement normal ou d'autres conditions modifiées. | Faites en sorte que le problème se reproduise. Comparez les conditions normales et modifiées, recherchez les preuves contraires et recherchez la cause. |
| Traiter un petit test comme une preuve de comportement en direct | Une imitation, un exemple préparé ou un petit test a été présenté comme preuve que l'ensemble du système fonctionnait dans des conditions normales d'utilisation. | Indiquez exactement ce qui a été testé et ne prétendez pas que le résultat prouve davantage. |
| Tester avec les mauvaises autorisations | Une vérification a réussi en utilisant l'accès du développeur même si le programme en direct s'est exécuté avec des autorisations différentes. | Testez avec le même compte et les mêmes autorisations que ceux utilisés par le programme en direct, ou laissez le résultat non prouvé. |
| Réparer une erreur avant de l'enregistrer | Une erreur a été réparée avant d’être divulguée, ce qui a donné au disque un aspect plus propre que l’œuvre ne l’était. | Conserver l'échec et la correction dans l'ordre. Ne laissez pas la réparation effacer les preuves. |
| Révision répétée devant l'utilisateur | Un résultat était révisé à plusieurs reprises devant l'utilisateur car la planification était retardée jusqu'après le premier résultat. | Sélectionnez le matériau et planifiez l’ensemble du résultat avant de demander une révision. Présentez une ébauche limitée lorsque cela est possible. |
| Rompre un service en direct avec une modification incomplète | Un modèle de langage n'a modifié qu'une partie d'un fichier de travail et est passé à autre chose. Le service en cours d’exécution n’a pas pu terminer son travail. | Traitez une modification comme inachevée jusqu'à ce que l'ensemble du fichier soit valide et que le service réel termine le travail prévu. |
| Modification de la mauvaise copie d'un paramètre | Un modèle de langage a modifié le fichier de paramètres principal, redémarré le service, reçu une réponse de redémarrage réussie et signalé le succès. Le service a utilisé une copie générée différente, l'ancien paramètre est donc resté actif. | Vérifiez le résultat visible, pas seulement le message de modification ou de redémarrage. Gardez un chemin clair entre le paramètre principal et la copie qu'un service utilise réellement. |
| Corrections répétées qui n'ont pas résolu le problème | Quatre modifications ont été apportées pour un problème. Chacun a prouvé qu'un code fonctionnait, mais aucun n'a prouvé que le problème initial avait disparu. | Définissez le résultat qui doit changer avant l'édition. Après chaque modification, testez ce résultat directement. |
| Vérification avec accès au service en direct n'a pas eu | Un dossier a fonctionné lors du test via le compte de la personne, mais le service en direct a utilisé un compte différent et n'a toujours pas pu l'atteindre. | Exécutez la vérification dans les mêmes conditions que le service en direct. |

## Échecs quant à savoir qui peut dire ou approuver quoi

| Échec observé | Ce qui s'est passé | Protection ajoutée en dehors du modèle de langage |
|---|---|---|
| Différents emplois traités de la même manière | Les observateurs, les rédacteurs, les contrôleurs, les personnes pouvant arrêter le travail et les approbateurs de versions ont été traités de la même manière car chacun a touché au résultat. | Chaque partie a une tâche déclarée et des limites à ce qu'elle peut décider. Un écrivain ne peut pas affirmer la vérité. Un observateur ne peut pas publier. |
| Afficher les valeurs de substitution comme étant réelles | Les écrans affichaient des mesures vides ou des substituts plausibles pour que l'installation paraisse terminée. | Affichez une valeur mesurée et son origine ou indiquez clairement qu'elle n'est pas disponible. |
| L'actualisation d'une page a détruit la place de l'utilisateur | Une actualisation a remplacé une page entière et détruit le focus, la sélection, la position de défilement ou la copie. | Traitez l'écran comme un espace de travail humain. Mettez à jour les valeurs changeantes sans détruire la place de l'utilisateur. |
| Conserver les mots de passe dans du texte non protégé | Les mots de passe et les clés d'accès ont été placés dans des fichiers ordinaires au lieu d'un stockage protégé. | Conservez-les dans un stockage protégé et vérifiez chaque fichier avant leur publication. |
| Signaler qu'un service s'est arrêté alors qu'il continuait à fonctionner | La demande d'arrêt a été renvoyée avec succès, mais le processus a continué à fonctionner. | Vérifiez le processus et son effet réel après une demande de contrôle. Ne signalez pas la demande comme résultat. |

## Échecs de l’attention humaine

| Échec observé | Ce qui s'est passé | Protection ajoutée en dehors du modèle de langage |
|---|---|---|
| Compléter les mots d'une personne | Une courte déclaration humaine a été complétée par le matériel généré jusqu'à ce que les mots originaux soient difficiles à trouver. | Conservez la déclaration originale comme enregistrement principal. L’interprétation générée reste distincte et facultative. |
| Écriture circulaire | La réponse a été expliquée, reformulée, récapitulée et conclue une fois le contenu utile épuisé. | Arrêtez-vous lorsque le résultat demandé est complet. Supprimez les conclusions répétées. |
| Enterrer la réponse | Un ou deux faits utiles ont été placés dans des écrans contenant du matériel que l'utilisateur n'avait pas demandé. | Mettez d'abord la réponse complète la plus courte et rendez les éléments plus approfondis facultatifs. |
| Dépenser une attention non offerte | Une explication correcte mais inutile obligeait le lecteur à passer du temps à décider qu'elle n'était pas nécessaire. | Considérez la lecture et la correction comme des coûts réels. Laissez le lecteur initier une profondeur facultative. |
| Trop d'accent | Presque tous les points étaient en gras, en-tête ou placés dans un tableau, de sorte que les véritables avertissements ne ressortaient plus. | Insistez uniquement sur les quelques distinctions qui portent sur le fardeau de la décision ou de la sécurité. |

## Échecs liés aux coûts et aux incitations des fournisseurs

| Échec observé | Ce qui s'est passé | Protection ajoutée en dehors du modèle de langage |
|---|---|---|
| Un grand modèle de langage payant utilisé par défaut | Le travail était envoyé via un modèle en ligne payant car il était disponible, même lorsqu'un simple processus fixe, un résultat enregistré ou un outil limité pouvait le faire de manière plus fiable. | Mesurez la valeur totale et le coût du travail. Choisissez la plus petite combinaison d'outils dont le travail peut être vérifié et justifié. |
| Le coût de correction a disparu des totaux | Les tentatives, le contexte répété, l'attente et la correction humaine étaient traités comme gratuits après un mauvais résultat, même s'ils utilisaient l'allocation payée et exigeaient plus de temps et d'énergie de la personne. | Enregistrez l'attente, les tentatives, les rejets, l'utilisation répétée du service et l'attention humaine dans le cadre du coût réel. |
| Aucun quota renvoyé en cas d'échec d'un travail | Les productions inutilisables et les échanges nécessaires pour les corriger sont imputés sur le quota payé. La personne n'a reçu aucun remplacement automatique pour l'indemnité ou le temps perdu. | Enregistrez séparément l’utilisation échouée et l’utilisation corrective. Réutilisez le contexte enregistré et les résultats rejetés afin que le même échec ne soit pas racheté. |
| L'échec utile a été écarté | Une réponse rejetée a disparu, donc les travaux ultérieurs ont répété la même erreur et l'ont payée à nouveau. | Gardez les résultats rejetés et leurs raisons en dehors des connaissances acceptées. Réutilisez la leçon sans accepter l’affirmation non étayée. |
| Le même contexte a dû être fourni à nouveau | Lorsque des informations antérieures disparaissaient de la vue de travail du modèle de langage, la personne devait reconstruire la demande et renvoyer l'historique déjà fourni lors d'une session payante. | Gardez le contexte durable en dehors du service. Créez un package limité pour chaque travail et conservez le travail retourné, la correction et le rejet pour une utilisation ultérieure. |

## Comment ces échecs de service sont devenus la conception de ce projet

Le problème observé ne se limite pas à un modèle faible. Il était demandé au même assistant temporaire de faire office de mémoire, d'historien, de planificateur, d'écrivain, de vérificateur et de juge de son propre travail. Même les modèles les mieux rémunérés pouvaient réussir une tâche individuelle tout en perdant l’histoire humaine qui la reliait à tout le reste.

Robot Brain donne ces tâches à des parties séparées. Le gardien de la source préserve l'événement. Des lecteurs locaux ciblés examinent les caractéristiques définies. Le générateur de requêtes rassemble des preuves dans un seul but. Un modèle peut contribuer au contexte ou à la formulation. Des contrôles indépendants et l'approbation humaine décident de ce qui est accepté.

L'historique reste en dehors du service payant. Un modèle peut aider dans un travail choisi, mais il ne stocke pas la vie de la personne et ne devient pas la seule façon d'utiliser le travail déjà accompli.

Le modèle local a la même limite. Il n'est pas formé sur les dossiers de la personne. Il lit le matériel sélectionné, renvoie une suggestion datée et peut être remplacé. Les paroles, le temps, l'expérience, les décisions, les échecs et les corrections de la personne sont la partie la plus précieuse.
