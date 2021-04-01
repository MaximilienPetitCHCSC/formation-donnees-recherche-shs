---
title: Enjeux et acteurs des données de la recherche
linktitle: Enjeux et acteurs des données de la recherche
type: book
date: "2019-05-05T00:00:00+01:00"
# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 2
---
## Acteurs des données - PNSO, FNSO

La [Plan national pour la Science Ouverte](https://cache.media.enseignementsup-recherche.gouv.fr/file/Actus/67/2/PLAN_NATIONAL_SCIENCE_OUVERTE_978672.pdf) est une initiative de Frédérique Vidal, en 2018, qui tend à rendre obligatoire l’accès ouvert pour les publications et les données issues de recherches financées sur projets. C’est notamment via ce plan que se met en place le Comité pour la science ouverte (CoSO). Cette action constitue en quelques sortes une feuille de route pour les financeurs et institutions de la recherche. Quelques points de ce plan qui concernent les données (le deuxième axe) : 

- La mise en avant des principes FAIR ( Facile à trouver, Accessible, Interopérable, Réutilisable).
- Le principe d’ouverture par défaut pour les données.
- La prise en compte, dans le cadre des appels à projets, des dépenses liées au traitement des données.
- Le fait de favoriser les collaborations entre grandes infrastructures de recherche.
- La stratégie de déploiement des plans de gestion des données (PGD) et le développement des *data papers*.
***
## ANR, Science ouverte et données de la recherche

L’Agence nationale de la recherche est un financeur incontournable pour les SHS et un bon exemple du financement de la recherche sur projets et de l’incitation, puis de l’obligation, aux bonnes pratiques de gestion et de partage des données de la recherche. En tant que financeur, l’ANR a une feuille de route et ne manque pas d’indiquer les recommandations et obligations qui vont structurer ses appels à projets. 

Le plan d’action 2021 rappelle que l’agence s’appuie sur [l’article 30 de la Loi « Pour une République numérique »](https://www.legifrance.gouv.fr/jorf/article_jo/JORFARTI000033202841). Cette loi de 2016 ajoute un droit d’exploitation secondaire. On peut disposer, ou ne pas disposer, de ce droit. C’est un cadre qui vise à faciliter le dépôt en accès ouvert des articles, recensions, communications, compte-rendus, interventions, etc. Les conditions à respecter : cela doit concerner une périodique publiant au moins une fois par an. Et ce périodique doit être financé pour moitié au moins par de l’argent public. La loi permet donc à l’auteur de déposer «la version finale de son manuscrit accepté pour publications » (version finale, après les révisions intégrées, sans le travail de mise en forme de l’éditeur). Si toutes les conditions sont respectées, la loi permet de déposer en respectant une période d’embargo : pour les SHS, il s’agit de 12 mois à compter de la date de la première publication par l’éditeur (6 mois pour les STM).

Depuis janvier 2021, et concernant les publications financées par l’ANR, le dépôt doit se faire sans délai.

Ce cadre ne concerne pas les monographies et les contributions à des ouvrages collectifs qui, on le sait, jouent un rôle très important pour les communautés scientifiques des SHS. L’ANR mentionne néanmoins, et les financeurs européens avec elle, que des pistes sont en cours de réflexion pour inclure les monographies dans les prochaines stratégies (fin 2021).
***
## CINES

Le [Centre informatique national de l’enseignement supérieur](https://www.cines.fr/ ) intervient sur une point particulier, qui sera développé plus loin : l’accompagnement des porteurs de projet pour ce qui concerne l’archivage pérenne des données de la recherche. Nous manipulerons également l’outil [FACILE](https://www.cines.fr/corriger-vos-fichiers-pdf-avec-facile/) qui nous permet d’identifier les formats de fichier éligibles sur ce point.
***
## Huma-Num

Huma-Num est une Très Grande Infrastructure de Recherche (TGIR) qui se concentre plus particulièrement sur les SHS. Elle dispose d'un pilotage scientifique, favorise la création de consortiums (exemple : [consortium 3D-SHS](https://shs3d.hypotheses.org/)) et bénéficie de relais dans d'autres structures (Maison des Sciences de l'Homme). Les missions d'Huma-Num visent à accompagner les communautés SHS concernant le développement, la réalisation et la préservation des programmes et données de recherches et leurs outils. 

Contexte et principes qui structurent les missions d'Huma-Num : la science ouverte, le partage des données, les principes FAIR.

Le cœur des chantiers d'Huma Num : l'interopérabilité. Historiquement, la TGIR fait le constat que des acteurs incontournables font évoluer les pratiques sur les publications scientifiques (HAL, OpenEdition, Persée, Cairn, etc.), mais avance que l'effort reste à produire pour ce qui est de la gestion des corpus de sources (primaires et secondaires), archives, fonds de bibliothèques et données de la recherche.

Concrètement, la TGIR développe et permet l’accès à des services et outils sur la gestion des données pour les communautés des SHS. Cette mutualisation permise par la TGIR, et accessible aux porteurs de projets (et également doctorants), s’accompagne bien évidemment de conditions, critères et repose sur une sensibilisation aux bonnes pratiques de gestion des données.

Huma Num accompagne les projets français et internationaux (avec porteur français) validés par un comité scientifique et ayant des besoins particuliers sur la gestion des données. Les projets doivent également s’inscrire dans une démarche de préservation des données et utiliser autant que possible les bases et entrepôts de la TGIR (Nakala, Isidore).

L’Infrastructure, par ses missions et moyens, vise avant tout à mutualiser. C’est un point important, car les moyens financiers, techniques et humains des laboratoires SHS se raréfient. Huma Num est une proposition pertinente dans ce contexte précis.
***
### Organisation

Permettre aux communautés SHS d’accéder à des outils et plateformes pour faciliter le travail collaboratif.

- ShareDocs (gestion collaborative de fichiers, faible volume, stockage sécurisé).
- GitLab : héberger et partager des fichiers de code (entre autres).
- Kanboard : outil de gestion de projet (type Trello).
- Outil de listes de diffusion.
- Mattermost : messagerie instantanée (type Slack). 
***
### Collecte

Permettre aux communautés SHS de collecter des données existantes, d’en créer de nouvelles. On se concentre ici sur le stockage de données (volume important). L’objectif étant ici de sortir du « stockage artisanal » des données pour les SHS.

- Huma-Num Box : service de stockage sur serveur, protocole SFTP pour y accéder.
***
### Traitement

Permettre aux communautés SHS de transformer et analyser les données en fonction de leurs besoins disciplinaires : extraction de données, puissance de calcul, annotation multimédia, audio/vidéo, 3D, cartographie, visualisation, etc.

- Accès à des machines virtuelles pour faire fonctionner des logiciels intégrés (et souvent onéreux).
- En fonction des besoins :  logiciels pour le traitement et l’analyse des données d’enquête, l’OCR.
***
### Préservation

Permettre aux communautés SHS d’utiliser des outils efficients et de suivre les bonnes pratiques liées à la préservation des données de la recherche. 

- Sur ce point, Huma-Num met en avant son entrepôt de données (stockage sécurisé) : Nakala. Cette base facilite l’import, l’export, la description de données dans un entrepôt. Cette base garantit l’interopérabilité, la citabilité et facilite également l’exposition de données. C’est le « nœud » des services de la TGIR.
- Pour des projets d’envergure, avec de très gros volumes de données, Huma-Num peut servir de relais avec le CINES concernant l’archivage des données.
***
### Publication

Permettre aux SHS d’exposer leurs données sur le web pour les communautés scientifiques et le grand public.

- Le pack Nakala-Press (remplace Nakalona) : articuler l’entrepôt Nakala avec un outil de publication de contenus (basé sur Omeka ?). La TGIR peut mettre à disposition  également un nom de domaine (https://nom.nakala.fr).
- Hébergement web mutualisé : hébergement des bases/sites des projets de recherche sur les serveurs de la TGIR, à la demande.
***
### Réutilisation

Permettre la réutilisation des données, notamment via les outils de la TGIR : 

- Nakala, encore. La base facilite l’attribution de licences ouvertes, identifiants pérennes, métadonnées standards, et donc, une réutilisation efficiente.
- Isidore : moteur de recherche se concentrant sur la collecte, l’enrichissement, le signalement des documents et données des SHS. Cette base ambitionne d’offrir un accès unifié (par « moissonnage »). Les données moissonnées par Isidore sont en français, en anglais, en espagnol. Isidore gagne à être utilisé par le biais de sa recherche avancée : [ici](https://isidore.science/as).

Isidore moissonne (entre autres) : OpenEdition, Cairn, Persée, Erudit, etc.

Lorsqu’un outil est mis à disposition par Huma-Num : soit par installation sur son ordinateur, soit via un accès en ligne.

La procédure pour accéder aux outils et services de la TGIR : adresser une demande par mail (cogrid@humanum.fr), qui est ensuite examinée par les personnels de la TGIR. Un accompagnement se met ensuite en place en fonction de vos besoins.

Ajout récent pour accéder à certains services d’Huma-Num : l’[HumanID](https://humanid.huma-num.fr/). Une interface d’authentification qui centralise les demandes d’accès. La procédure de demande sur le mail cogrid ne se fait que si l’outil n’est pas présent sur l’HumanID. Sur l’interface, nous retrouvons : Isidore, ShareDocs, Nakala, stylo, GitLab, Mattermost, matomo.

**Quelques liens utiles** : 

- [La base de connaissance de la TGIR concernant ses services et outils.](https://documentation.huma-num.fr/)
- [La liste des sites web hébergés par Huma-Num](https://www.huma-num.fr/annuaire-des-sites-web/).
- [Présentation et liste des consortiums Huma-Num](https://www.huma-num.fr/les-consortiums-hn/) : la TGIR facilite la création de consortiums qui mettent en place des guides de bonnes pratiques et des outils sur des thématiques de recherche précises.
- [Présentation de l’Huma-Num Lab](https://www.huma-num.fr/hnlab/) : dispositif récent qui va permettre  d’accueillir des chercheurs et ingénieurs de recherche en résidence afin  de travailler sur des thématiques qui relèvent des humanités numériques.

 

