---
title: 'Soutenance de Thèse'
date: 2022-08-31
permalink: /posts/2022/08/soutenance/
---

***Analyse des conséquences sur les bornes de latences des combinaisons de mécanismes d'ordonnancement, de redondance et de synchronisation dans les réseaux temps-réel.***

Date
----

12 Septembre 2022 à 13h30

Diffusion en direct
-------------------

Les détails seront postés bientôt

Lieu
-----

Salle des thèses de l'[ISAE-SUPAERO](https://goo.gl/maps/E7S9nqRoXpencSFB7)
10 Av.Edouard Belin, 31400 Toulouse, France

Si vous n'avez pas déjà accès à l'ISAE-SUPAERO, merci de compléter [ce formulaire pour le badge visiteur](https://forms.gle/M9DjoZmAGXxhghbF7).

Jury
----

Rapporteurs:

- M. Ye-Qiong SONG, Professeur at University of Lorraine
- Mr Jens B. SCHMITT, Professeur at University of Kaiserslautern

Examinatrices:

- Mme. Claire PAGETTI, Ingénieure de recherche à l'ONERA Toulouse
- Mme. Liliana CUCU-GROSJEAN, Directrice de recherche à l'INRIA Paris

Encadrants:

- Mme. Ahlem MIFDAOUI, Professeure à l'ISAE-SUPAERO, Toulouse
- Mr. Jean-Yves LE BOUDEC, Professeur à l'EPFL, Lausanne

Résumé
------

Les réseaux temps-réels, comme ceux spécifiés par *IEEE Time-Sensitive Networking* (TSN) et IETF *Deterministic Networking* (DetNet), fournissent aux applications critiques un service déterministe avec des bornes de latence garanties.
Plusieurs mécanismes comme les ordonnanceurs et les régulateurs de trafic (TSN ATS, *asynchronous traffic shaping*) ont été développés et leurs effets sur les bornes de latences pire-cas ont été abondamment étudiés dans la littérature en utilisant la théorie du calcul réseau.
Toutefois, les réseaux temps-réels doivent désormais aussi offrir une reconfiguration simplifiée avec des chemins alternatifs, un haut niveau de fiabilité et parfois un service de synchronisation du temps.
Pour répondre à ces besoins, l'utilisation de topologies à plusieurs chemins a été encouragée pour faciliter la reconfiguration et des mécanismes de redondance et de synchronisation ont été développés pour fournir un haut niveau de fiabilité et une synchronisation du temps.
Tandis que chacun de ces mécanismes dispose d'une théorie pour valider son efficacité dans son objectif respectif, la littérature n'a que peu étudié leurs effets secondaires sur les bornes de latences et leurs interactions avec les ordonnanceurs et les régulateurs de trafic.
Dans cette thèse, nous utilisons la théorie du calcul réseau pour analyser les combinaisons de mécanismes et leurs effets sur les bornes de latences dans les réseaux temps-réel avec des topologies à plusieurs chemins.
Nos principales contributions sur le plan théorique sont :
1/ Nous développons un algorithme (FP-TFA) qui calcule des bornes de latence dans les réseaux dans lesquels la variété des chemins crée des dépendances cycliques.
Nous proposons et analysons l'approche de déploiement partielle des régulateurs de trafic (soit par flux, soit avec TSN ATS) ainsi qu'un autre algorithme (LCAN) qui casse toutes les dépendances cycliques à coût minimal.
2/ Nous analysons les effets des mécanismes de redondance sur les bornes de latence en modélisant leur comportement dans la théorie du calcul réseau.
Nous analysons aussi leurs interactions avec les régulateurs de trafic.
En particulier, nous observons que TSN ATS peut mener à des latences non bornées lorsqu'il est utilisé avec les mécanismes de redondances.
3/ Nous proposons un modèle d'horloge qui décrit, au sein de la théorie du calcul réseau, les imperfections des horloges des réseaux synchronisés ou non.
Nous montrons que l'usage de régulateurs de trafic avec des horloges imparfaites occasionne une pénalité dans les bornes de latence.
Avec TSN ATS, cette pénalité n'est pas bornée, y compris dans les réseaux synchronisés avec une grande précision.
Nous proposons deux méthodes (cascade et ADAM) pour adapter les paramètres des régulateurs et ainsi résoudre ce problème.

Nous fournissons également des contributions d'intérêt pratique :
a) l'outil modulaire xTFA, qui calcule des bornes de latences en utilisant les résultats de la thèse,
b) un module pour simuler l'effet des horloges locales dans le simulateur à évènements discrets ns-3, et
c) une application de nos résultats sur une étude de cas industrielle.