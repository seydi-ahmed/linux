# Linux Project

## Installation de la Virtualisation
- Télécharge et installe le logiciel de virtualisation correspondant à ton architecture :
  - VirtualBox (pour architecture X86-64).
  - UTM (pour architecture Apple Silicon).
- Vérifie si la virtualisation est activée sur ton ordinateur (cela se fait généralement dans le BIOS/UEFI).

## Création de la machine virtuelle (VM)
- Ouvre le logiciel de virtualisation.
- Crée une nouvelle machine virtuelle (en choisissant Debian comme système d'exploitation).
- Alloue de la mémoire (RAM) et des ressources (par exemple, 2 Go de RAM, 10 Go d'espace disque, etc.).
- Attache l'ISO de Debian (fichier "netinst") comme lecteur optique (CD/DVD).

## Démarrer la machine virtuelle et installer Debian
- Démarre la VM.
- Le programme d'installation de Debian s'affiche. Suis les étapes de l'installation (choix de la langue, partitionnement du disque, paramètres réseau, etc.).
- À la fin de l'installation, le système redémarrera et tu devrais pouvoir accéder à un système Debian prêt à l'emploi.

## Connexion et arrêt du système via la ligne de commande
- Une fois Debian démarré, connecte-toi à la console en utilisant les identifiants définis pendant l'installation.
- Pour arrêter la machine virtuelle, utilise la commande suivante dans la console :
```
sudo shutdown -h now
```

## Développeur
- Prénom NOM: Mouhamed DIOUF
- email: seydiahmedelcheikh@gmail.com