---
addons:
  style_goodies: yes
---
## TP Docker
### à faire :
Utilisation de docker au sein d’une machine virtuelle virtualBox
 vm Linux debian 8.9
documentez la progression de votre travail avec le temps de
réalisation pour chaque étape.
à rendre un document pdf « nom-tp-docker.pdf :
### Forme:
- un sommaire
- une entête et pied de page
- numérotation des pages
- aucune Impression écran

## Fond:
- Notez chaque étapes du déroulement du tp
- Time line sur l’ensemble du tp ( heure début - heure fin)
- Temps de réalisation par étapes
- Présentez chaque commandes utilisés
- Notez chaque résultat de commande

## Prérequis

Une machine virtuelle virtualbox debian 8.9 sans environnement
graphique
image : \\192.168.10.108\ISO\Debian

## 1 - Installation

Réalisez les installations de VM en simultané
Installation de docker sous Windows
Téléchargez puis installez l’application docker pour
[windows](https://store.docker.com/editions/community/docker-cedesktop-windows)

## Installation de docker sous linux

[source] (https://docs.docker.com/engine/installation/linux/docker-ce/debian/#set-up-the-repository)

_Mode root_

    $ su
    
_Avec le profil administrateur (root)_

    # apt-get install software-properties-common apt-transport-https
    # add-apt-repository "deb [arch=amd64] http://download.docker.com/linux/debian $(lsb_release -cs) \stable"
    # apt-get update
    # apt-get install docker-ce

## 2- Utilisation

L’utilisation des commandes devrait être semblable entre linux et
windows. Notez le si il en est autrement.
Accès à la documentation
La commande docker seul vous affiche:
- les options disponibles
- les commandes d’administration ( Management commands )
- les commandes


      $ docker version 
      Client:
      Version: 17.09.0-ce
      API version: 1.32
      Go version: go1.8.3
      Git commit: afdb6d4
      Built: Tue Sep 26 22:40:09 2017
      OS/Arch: darwin/amd64
      Server:
      Version: 17.09.0-ce
      API version: 1.32 (minimum version 1.12)
      Go version: go1.8.3
      Git commit: afdb6d4
      Built: Tue Sep 26 22:45:38 2017
      OS/Arch: linux/amd64
      Experimental: true
      Utilisation sous linux

https://docs.docker.com/get-started/




--- nE PAS FAIRE --

Réalisez le tutoriel
http://imikado.developpez.com/tutoriels/mkframework/utilisationAvecDocker/
Utilisation windows
https://www.grafikart.fr/tutoriels/docker/hyper-v-643
