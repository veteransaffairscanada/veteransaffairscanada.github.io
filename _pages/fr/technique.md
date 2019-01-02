---
layout: page
title:  "Aperçu technique"
lang: fr
permalink: "/technique/"
trans_url: "/technical/"
---

**Aperçu**

*Rechercher des avantages et des services* est une application Web développée à l’aide du cadre d’applications `Next.js`. Dans ce qui suit, l’application sera désignée sous le nom d’*App*.

Les données sur les avantages associées à l’*App* sont stockées à l’aide d’`Airtable`, un produit SaaS qui sert à la fois de base de données relationnelle et de système de gestion de contenu. L’*App* lit les données et, dans de rares cas (par exemple, lorsqu’un utilisateur soumet une rétroaction), écrit les données à `Airtable` au moyen d’une interface de programmation d’applications (API) Web.

**Données sur les avantages**

`Airtable` comprend une interface Web pratique (qui, dans une large mesure, fonctionne comme un tableur) que les administrateurs de l’*App* (c’est-à-dire le personnel d’ACC) peuvent utiliser pour maintenir les données sur les avantages exactes et à jour. Cela comprend l’association des prestations à un petit ensemble de critères et de catégories d’admissibilité, ces associations étant reflétées dans l’interface utilisateur de l’*App* sous forme de filtres. De plus, la plupart des titres et des étiquettes de l’interface utilisateur de l’*App* peuvent également être modifiés dans `Airtable`, ce qui permet d’apporter des modifications textuelles simples à l’application sans manipuler le code. Les changements apportés aux données `Airtable` peuvent être reflétés dans l’*App* immédiatement pour l’AQ ou la diffusion aux utilisateurs finaux.

**L’App**

L'*App* est essentiellement une application Web côté client, bien que ses pages constituantes puissent être et soient parfois rendues sur le serveur Web pour divers gains de performance et scénarios de connectivité/navigateur. Le code qui le définit est disponible publiquement sur  [GitHub](https://github.com/cds-snc/vac-benefits-directory). Le référentiel contient également d’autres informations sur la pile et la méthodologie utilisée pour développer l’application, y compris :

* la façon d’exécuter le code ;
* les arguments expliquant les raisons pour lesquelles les principaux composants de la pile ont été choisis ;
* le processus de déploiement observé lors du développement et les outils qui l’accompagnent ;
* la couverture de test automatisée et les modèles utilisés dans la base de code
