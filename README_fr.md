# Encryptor-Decryptor pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/encryptor-decryptor.svg)](https://dash.yunohost.org/appci/app/encryptor-decryptor) ![](https://ci-apps.yunohost.org/ci/badges/encryptor-decryptor.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/encryptor-decryptor.maintain.svg)  
[![Installer Encryptor-Decryptor avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=encryptor-decryptor)

*[Read this readme in english.](./README.md)*
*[Lire ce readme en français.](./README_fr.md)*

> *Ce package vous permet d'installer Encryptor-Decryptor rapidement et simplement sur un serveur YunoHost.
Si vous n'avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble

Encrypts and decrypts your files and text.

**Version incluse :** 1.0~ynh1

**Démo :** https://prizz.github.io/Easy-File-Encryptor-Decryptor/

## Captures d'écran

![](./doc/screenshots/.DS_Store)
![](./doc/screenshots/screenshot.png)

## Avertissements / informations importantes

# Disclaimer

This webapp does not store or transmit your data. But to be safe, in case of malware, or rogue browser extensions, follow these steps:

- [Download this webapp](https://github.com/pRizz/Easy-File-Encryptor-Decryptor/archive/master.zip) for offline use
- Disconnect from the internet
- Open this webapp (the index.html file) in incognito, or private browsing mode, with no extensions, or all extensions disabled
- Encrypt and Decrypt
- Quit your browser

## Documentations et ressources

* Site officiel de l'app : https://prizz.github.io/Easy-File-Encryptor-Decryptor/
* Dépôt de code officiel de l'app : https://github.com/pRizz/Easy-File-Encryptor-Decryptor
* Documentation YunoHost pour cette app : https://yunohost.org/app_encryptor-decryptor
* Signaler un bug : https://github.com/YunoHost-Apps/encryptor-decryptor_ynh/issues

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/encryptor-decryptor_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/encryptor-decryptor_ynh/tree/testing --debug
ou
sudo yunohost app upgrade encryptor-decryptor -u https://github.com/YunoHost-Apps/encryptor-decryptor_ynh/tree/testing --debug
```

**Plus d'infos sur le packaging d'applications :** https://yunohost.org/packaging_apps