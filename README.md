# [ESX] FBI Job

Ce script pour ESX ajoute des armureries, des garages de véhicules et la possibilité pour les agents du FBI de fouiller, menotter des personnes et bien plus encore.

## Prérequis
* Mode automatique
  * [esx_billing](https://github.com/esx-framework/esx_billing)
  * [esx_vehicleshop](https://github.com/esx-framework/esx_vehicleshop)

* Gestion des joueurs (actions du chef et armurerie avec armes achetables)
  * [esx_addoninventory](https://github.com/esx-framework/esx_addoninventory)
  * [esx_datastore](https://github.com/esx-framework/esx_datastore)
  * [esx_society](https://github.com/esx-framework/esx_society)

* Support de l'identité ESX
  * [esx_identity](https://github.com/esx-framework/esx_core/tree/main/%5Bcore%5D/esx_identity)

* Support de la licence ESX
  * [esx_license](https://github.com/esx-framework/esx_license)

* Support du service ESX
  * [esx_service](https://github.com/esx-framework/esx_service)

* Support de l'état ESX
  * [esx_status](https://github.com/esx-framework/esx_status)

## Téléchargement & Installation
- Téléchargez [esx_fbijob]
- Placez-le dans le répertoire `[esx]`

## Installation
- Importez `esx_fbijob.sql` dans votre base de données
- Ajoutez ceci à votre `server.cfg`:
ensure esx_policejob

   * Si vous souhaitez une gestion des joueurs, vous devez définir `Config.EnablePlayerManagement` sur `true` dans `config.lua`
   * Si vous souhaitez une gestion de l'armurerie, vous devez définir `Config.EnableArmoryManagement` sur `true` dans `config.lua`
   * Si vous souhaitez une gestion des licences, vous devez définir `Config.EnableLicenses` sur `true` dans `config.lua`
   * Si vous souhaitez une gestion des services, vous devez définir `Config.MaxInService` sur une valeur supérieure à `-1` dans `config.lua`

## Licence
Ce projet est sous licence MIT

## Support
Pour toute question ou assistance, veuillez ouvrir une issue dans ce dépôt.

## Contribuer
Les contributions sont les bienvenues ! N'hésitez pas à ouvrir une pull request pour proposer des améliorations ou des correctifs.

---
## Crédits
© 2024 ChouCookieSan