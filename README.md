Gabarits JSON-LD / Schema.org pour QuébecSpectacles
======

Contexte
----

S'applique au contexte et au CMS de QuébecSpectacles.


Notes générales
----

L'utilisation de doubles crochets (`{{ }}`) signifie que la donnée à cet endroit doit être remplacé par une valeur tirée de la base de données, ou qu'on donne une consigne sur la répétion d'un bloc.

Lorsqu'il y a une date, elle est au format ISO-8601 à moins d'avis contraire.

Lorsqu'une donnée n'est pas disponible, il faut simplement retirer la clé du JSON.


Gabarits
----

Pour les événements:

* [spectacles ou séries](./evenement-sauf-event_span-long.json) (modèle evenement, sauf si event_span est long)
* [expositions](./evenement-event_span-long.json) (modèle evenement, avec event_span est long)
* [représentations](./representation.json)

Pour les autres types d'objets:

* [personnes ou organizations](./person-ou-organization.json)
* [lieux de diffusion](/.place.json)
