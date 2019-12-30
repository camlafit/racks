# racks

Plugin racks pour GLPI < 9.3

*******************

## Fonctionnalités integrées dans GLPI 9.3

Ce plugin doit être retiré si vous utilisez une version récent de GLPI ( >= 9.3) 

Depuis GLPI 9.3, cette fonctionnalité a été intégrée dans le coeur de GLPI.
Un [script de migration](https://github.com/glpi-project/glpi/blob/9.4/bugfixes/scripts/migrations/racks_plugin.php) est fourni pour mettre à jour vos données :
```
scripts/migrations/racks_plugin.php [--update_plugin]
```

Pour plus d'information consultez [les informations officielles relatives à la version 9.3](https://glpi-project.org/fr/glpi-9-3/)


*******************

## Features integrated into GLPI 9.3

This plugin should be remove if you use a recent GLPI version

Since GLPI 9.3 version, this feature is in GLPI core.
You can find a [script migration ](https://github.com/glpi-project/glpi/blob/9.4/bugfixes/scripts/migrations/racks_plugin.php) to update your data from plugin to core feature : 
```
scripts/migrations/racks_plugin.php [--update_plugin]
```

More information in [9.3 release information](https://glpi-project.org/glpi-9-3-itsm-software/)


*******************

## In GLPI < 9.3 use case

Ce plugin est sur Transifex - Aidez-nous à le traduire :
https://www.transifex.com/tsmr/GLPI_racks/

This plugin is on Transifex - Help us to translate :
https://www.transifex.com/tsmr/GLPI_racks/

Ce plugin vous permet de créer des baies. Gérer l'emplacement de vos matériels dans vos baies. Et ainsi connaitre l'espace disponible, ainsi que sa consommation électrique et sa dissipation calorifique.
> * Détail d'une baie : hauteur - largeur - profondeur - poids - nombre de U.
> * Gestion de l'avant et de l'arrière.
> * Définition de modèles de matériel utilisable et spécifications (Courant consommé, nombre d'alimentations, dissipation calorifique, Débit d'air frais, taille (U), poids, longueur)
> * GLPI > 0.84 : Utilisable avec le plugin "Cartographie":https://github.com/InfotelGLPI/positions
> * GLPI > 0.84 : Utilisable avec le plugin "Arborescence":https://forge.glpi-project.org/projects/show/treeview

This plugin allows you to create bays. Manage the placement of your materials in your bays. And so know the space and its power consumption and heat dissipation.
> * Rack detail : height - width - depth - weight - number of U.
> * Front and back management.
> * Definition of model specifications and materials used (power consumption, numbre of power supply, calorific waste, flow Rate, size (U), weight, depth)
> * GLPI > 0.84 : Can be used with "Positions":https://github.com/InfotelGLPI/positions
> * GLPI > 0.84 : Can be used with "Tree View":https://forge.glpi-project.org/projects/show/treeview
