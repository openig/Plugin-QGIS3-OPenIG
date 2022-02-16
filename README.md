Plugin-QGIS3-OPenIG
=======================

Plugin pour QGIS 3 fournissant un accès simplifié aux adhérents d'OPenIG à des flux géographiques WMS d'OPenIG.


Installation
-------
Pré-requis :
* Installation opérationnelle de QGIS 3.0 a minima (utilisez une version LTR récente de préférence).

Installation via le gestionnaire d'extensions de QGIS :
* Déclarer et activer le dépôt suivant : https://www.openig.org/sites/default/files/Plugin_QGIS/plugins.xml
![alt text](/openig/images/ajout_depot_qgis.PNG)

* Rechercher et charger l'extension intitulée "OPenIG"


Utilisation
-------
Affichage des ressources mises à disposition des utilisateurs via l'extension :
* Dans le menu de QGIS : Extension > OPenIG > Afficher le panneau OPenIG

Un nouveau panneau latéral apparaît contenant une arborescence des ressources mises à disposition des adhérents d'OPenIG via le plugin en flux WMS.   

Pour ajouter une couche WMS ou une classe d'entités WFS sur la carte courante de QGIS vous pouvez utiliser l'une des opérations suivantes :
* double-clic sur le nœud en question
* clic-droit sur le nœud en question et menu contextuel "Ajouter à la carte"
* glisser-déposer du nœud sur la carte de QGIS

Il est possible de trier les couches sur leur nom avec la barre de recherche placée au dessus de l'arborescence.

Pour consulter les métadonnées associées à une couche : clic droit sur la couche puis "Afficher les métadonnées".

Si vous avez fermé le panneau OPenIG et que vous voulez l'afficher à nouveau, 2 possibilités :

* menu Extensions, OPenIG, Afficher le panneau latéral
* menu Vue, Panneaux, cocher OPenIG

Paramètres
-------
Les paramètres de ce plugin sont accessibles en allant dans le menu Extensions > OPenIG > Paramétrer le plugin :

Par défaut, le fichier de configuration de l'extension est téléchargé à chaque lancement de QGIS, ce qui vous assure que l'arborescence soit à jour par rapport au contenu mis à disposition par OPenIG. Vous pouvez également décider de masquer ou non les dossiers vides, ou bien les couches en cours d'intégration.

Auteurs
-------
Equipe [OPenIG](https://www.openig.org/).

Ceci est un fork du projet réalisé par [DataGrandEst](https://github.com/geograndest/qgis-plugin). Nous nous sommes aussi aidés du plugin de [Geo2France](https://github.com/geo2france/idg-qgis3-plugin/blob/main/README.md) ainsi que d'[INDIGEO](https://gitlab.in2p3.fr/letg/indigeo-for-qgis). Nous remercions l'ensemble des auteurs et contributeurs !

N'hésitez pas à nous faire des retours et/ou des suggestions sur cet outil à l'adresse suivante : webmestre@openig.org
