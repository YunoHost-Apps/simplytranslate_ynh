<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# Simply Translate pour YunoHost

[![Niveau d’intégration](https://dash.yunohost.org/integration/simplytranslate.svg)](https://dash.yunohost.org/appci/app/simplytranslate) ![Statut du fonctionnement](https://ci-apps.yunohost.org/ci/badges/simplytranslate.status.svg) ![Statut de maintenance](https://ci-apps.yunohost.org/ci/badges/simplytranslate.maintain.svg)

[![Installer Simply Translate avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=simplytranslate)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer Simply Translate rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

L'interface du moteur SimplyTranslate, que vous pouvez utiliser pour la traduction de nombreux moteurs de traduction, comprend les moteurs DeepL, Reverso, ICIBA, Google Translate et LibreTranslate (dont l'instance de récupération de LibreTranslate peut être configurée).

**Version incluse :** 2023.4.9~ynh4

## Captures d’écran

![Capture d’écran de Simply Translate](./doc/screenshots/st_id-en.png)

## :red_circle: Anti-fonctionnalités

- **Application non maintenue **: Ce logiciel n'est plus maintenu. Attendez-vous à ce qu'il ne fonctionne plus avec le temps, et que l'on découvre des failles de sécurité qui ne seront pas corrigées, etc.
- **Services réseau non libres **: Promeut ou utilise des services réseau non libres.

## Documentations et ressources

- Site officiel de l’app : <https://simplytranslate.org/>
- Dépôt de code officiel de l’app : <https://codeberg.org/SimpleWeb/SimplyTranslate-Web>
- YunoHost Store : <https://apps.yunohost.org/app/simplytranslate>
- Signaler un bug : <https://github.com/YunoHost-Apps/simplytranslate_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/simplytranslate_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/simplytranslate_ynh/tree/testing --debug
ou
sudo yunohost app upgrade simplytranslate -u https://github.com/YunoHost-Apps/simplytranslate_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
