> Français: Traduction assistée par machine de la source anglaise faisant autorité. Native-language corrections are welcome. [Anglais](../../14-Sources-Behind-the-Design.md) | [Toutes les langues](../README.md)

# Recherche derrière la conception

![Différentes traditions de recherche apportent des méthodes limitées tout en conservant leur propre histoire.](../../illustrations/academic-framework-lineages.png)

Cette page est destinée aux lecteurs qui souhaitent suivre le parcours de recherche. L’explication principale ne l’exige pas.

La liste comprend des idées et des outils qui ont été utilisés, testés, comparés, rejetés ou simplement étudiés. Ces relations ne sont pas les mêmes. Répertorier une source ne signifie pas que ses auteurs ont participé ou approuvé le projet.

## Conserver les sources et les changements dans le temps

- La recherche sur l’historique des sources et l’évolution des informations a façonné la manière dont les documents conservent l’origine du matériel, la date d’application et ce qui l’a remplacé par la suite.
- [Graphite](https://github.com/getzep/graphiti)a été examinée comme une approche pour enregistrer les connexions qui changent au fil du temps.
- Les méthodes établies d'enregistrement des modifications ont établi la règle selon laquelle un résumé actuel ne doit pas remplacer la source qui le sous-tend.

Ces idées aident à préserver le chemin qu’une nouvelle réponse modèle ou un résumé réécrit cacherait autrement.

## Séparer les réclamations, le soutien et le désaccord

- [Théorie de la structure rhétorique de Mann et Thompson](https://aclanthology.org/J88-2003/)fourni des noms pour les relations entre les parties d'un document, comme un point principal et son explication.
- [Schémas d'argumentation de Walton, Reed et Macagno](https://www.cambridge.org/core/books/abs/argumentation-schemes/introduction/745B75B5933D17D86AC2E85971DA34A2)fourni des questions ciblées pour examiner le soutien et les conclusions.
- [oAMF](https://github.com/arg-tech/oAMF)et xAIF a fourni des approches pour enregistrer les réclamations et leurs connexions.
- [PropBank](https://aclanthology.org/J05-1004/)influencé la façon dont les déclarations et les rôles qu’elles contiennent sont enregistrés.
- [RSTancien](https://aclanthology.org/2023.acl-long.306/)et les travaux connexes ont été testés pour trouver la structure du document. Ils n’étaient pas utilisés comme juges finaux du sens ou du raisonnement.

Ces sources aident à éviter qu’un paragraphe raffiné ne cache la différence entre une affirmation, son soutien, une correction et un désaccord.

## Trouver du matériel utile sans confondre la ressemblance avec la vérité

- [La pertinence marginale maximale de Carbonell et Goldstein](https://aclanthology.org/X98-1025/)des moyens éclairés pour équilibrer la pertinence et la répétition.
- [Lin et Bilmes sur le résumé de documents sous-modulaires](https://aclanthology.org/P11-1052/)des moyens éclairés de choisir un groupe de passages utile dans une limite de taille.
- [FaitScore](https://aclanthology.org/2023.emnlp-main.741/)des questions éclairées sur la précision avec laquelle les allégations sont étayées.
- La recherche sur des résumés construits à partir de relations enregistrées a permis de réaliser des tests qui raccourcissent le contenu sans supprimer les liens qui comptent.

La recherche et le résumé peuvent orienter une personne vers des preuves. Ils ne peuvent pas décider pourquoi quelque chose est important ou rendre un passage vrai.

## Planifier avant d'écrire

- [Reiter et Dale construisent des systèmes de génération de langage naturel](https://www.cambridge.org/core/books/building-natural-language-generation-systems/0AE70C709A9BFBDC80B349B2D22A78CD)influencé la séparation entre le choix du contenu, la planification et la rédaction des phrases.
- [NLG étape par étape](https://aclanthology.org/N19-1236/)et[Planification macro données-texte](https://aclanthology.org/D19-1318/)comparaisons éclairées des méthodes de planification de documents.
- [SimpleNLG](https://github.com/simplenlg/simplenlg),[Cadre grammatical](https://www.grammaticalframework.org/), et[OuvrirCCG](https://github.com/OpenCCG/openccg)ont été évalués comme moyens de transformer le contenu prévu en phrases.
- La recherche sur les informations connues et nouvelles, les liens entre les phrases, les types de communication et les formes de documents ont influencé la manière dont les explications sont ordonnées pour différents lecteurs.

Ensemble, ce travail prend en charge la planification d'un document avant de demander à un modèle de langage de l'écrire.

## Compréhension humaine et coût de la lecture

- Les recherches sur la façon dont les gens développent leur compréhension et gèrent l'effort mental ont permis d'établir les limites de la longueur, des nouveaux concepts et de la répétition.
- [Coh-Métrix](https://www.cambridge.org/core/books/automated-evaluation-of-text-and-discourse-with-cohmetrix/AE4A1D5DCCBA1AE3A9632E9D4D380270),[TAAC](https://www.linguisticanalysistools.org/taaco.html),[DocuScope](https://docuscope.github.io/), TextDescriptives et LFTK ont été évalués comme moyens de comparer l'écriture.
- La théorie de l'autodétermination, la recherche sur le sens de la vie et la recherche sur les valeurs ont éclairé des questions limitées sur le sens personnel. Ils ne prennent pas en charge le diagnostic automatique ou les profils généraux de personnes.

## Outils d'édition limités

[LaserTagger](https://github.com/google-research/lasertagger),[GECTOR](https://github.com/grammarly/gector), et[EditT5](https://aclanthology.org/2022.findings-acl.260/)ont été évalués pour les tâches de révision qui limitent la quantité de nouveaux mots pouvant être introduits.

## Droits et dossiers plus complets

Cette documentation n'inclut pas de copies des livres, articles, programmes, fichiers de modèles formés ou collections de recherche nommés.[Sources, licences et confidentialité](../../SOURCES-LICENSES-AND-PRIVACY.md)enregistre l'examen des licences pour les programmes et les fichiers formés qui ont été réellement utilisés ou testés.

Le dossier de recherche privé contient davantage d'articles, de normes publiques, d'outils, de collections, d'œuvres culturelles, d'approches rejetées et de résultats de tests. Le crédit public peut croître à mesure que ces dossiers sont vérifiés, y compris les idées qui ont aidé principalement en montrant ce qui n'a pas fonctionné.
