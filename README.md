# oc_Projet4

**Objectif:**

Concevoir l'architecture de la base de donnée d'une application de livraison de plats en utilisant UML pour modéliser les besoins, puis en créant un MPD (modèle physique de donnée).

* Diagramme de cas d'utilisations
* Diagramme de séquence
* Diagramme de classe
* Modèle physique de donnée

**Commentaire de l'évaluateur:**

*Avis général et verdict:*

Le projet présenté est de bonne qualité, et la présentation orale est au niveau. Projet validé!

Les livrables sont très complets et correspondent aux demandes de l'énoncé. L'approche UML est cohérente, même si la logique choisie pour le passage de commande un peu "déroutante" (choix du livreur avant validation finale du panier - possible 'race condition').

L'oral était clair et professionnel.

*Points positifs:*

Thomas s'est investi dans l'UML et a acquis l'ensemble des notions du langage (liens identifiants, cardinalité, etc)

*Axes d'amélioration:*

Attention à la structure de la base - sans champ 'date' ou un flag 'disponible / indisponible' on peut se retrouver avec une base qui a des références potentiellement manquantes - point discuté en soutenance et Thomas a bien compris qu'un élément était manquant.
