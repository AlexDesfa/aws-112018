# AWS 11-2018

**Notes de formation**

<!-- toc -->

## Environnement

* https://github.com/goffinet/aws-112018
* Installation Centos
* yum -y install epel-release ; yum -y upgrade
* Atom.io : https://atom.io/
* chromium
* compte github
* https://github.com/goffinet/virt-scripts
* vagarant, vagrant-libvirt, vagrant-mutate

## Administration Linux : 1e partie

### [I. Administration système](https://linux.goffinet.org/00_administration_systeme/)

- [1. Introduction à Linux](https://linux.goffinet.org/01-00-introduction-a-linux/)
    - [1.1. Evolution de Linux](https://linux.goffinet.org/01-01-evolution-de-linux/)
    - [1.2. Distributions Linux](https://linux.goffinet.org/01-02-distributions-linux-et-cycles-de-maintenance/)
    - [1.3. Licences Open Source](https://linux.goffinet.org/01-03-licences-open-source/)
    - [1.4. Applications Open Source](https://linux.goffinet.org/01-04-applications-open-source/)
    - [1.5. Utiliser Linux en console graphique (Centos7)](https://linux.goffinet.org/01-05-utiliser-linux-en-console-graphique-centos7/)
    - [1.6. Environnements de bureau](https://linux.goffinet.org/01-06-environnements-de-bureau/)
    - [1.7. Installation Linux Debian](https://linux.goffinet.org/01-07-installation-linux-debian/)
- [2. Le Shell](https://linux.goffinet.org/02-00-le-shell/)
    - [2.1. La ligne de commande](https://linux.goffinet.org/02-01-la-ligne-de-commande/)
    - [2.2. Filtres sur les fichiers (globbing)](https://linux.goffinet.org/02-02-filtres-sur-les-fichiers-globbing/)
    - [2.3. Premier script shell](https://linux.goffinet.org/02-03-premier-script-shell/)
    - [2.4. Configuration des langues, locales et clavier](https://linux.goffinet.org/02-04-langues-locales-clavier/)
    - [2.5. Aide sous Linux](https://linux.goffinet.org/02-05-aide-sous-linux/)
    - [2.6. Prendre connaissance de la version de la distribution](https://linux.goffinet.org/02-06-prendre-connaissance-de-la-version-de-la-distribution/)
- [3. Traitement du texte](https://linux.goffinet.org/03-00-traitement-du-texte/)
    - [3.1. Outils de base de traitement du texte](https://linux.goffinet.org/03-01-outils-de-base-traitement-du-texte/)
    - [3.2. Outils avancés de traitement du texte](https://linux.goffinet.org/03-02-outils-avances-traitement-du-texte/)
    - [3.3. L'éditeur de texte VI](https://linux.goffinet.org/03-03-editeur-de-texte-vi/)
- [4. Arborescence de fichiers](https://linux.goffinet.org/04-00-arborescence-de-fichiers/)
    - [4.1. Filesystem Hierachy Standard (FHS)](https://linux.goffinet.org/04-01-filesystem-hierachy-standard/)
    - [4.2. Opérations sur les fichiers](https://linux.goffinet.org/04-02-operations-sur-les-fichiers/)
    - [4.3. Recherche de fichiers](https://linux.goffinet.org/04-03-recherche-de-fichiers/)
    - [4.4. Archivage et compression](https://linux.goffinet.org/04-04-archivage-et-compression/)
- [5. Sécurité locale](https://linux.goffinet.org/05-00-securite-locale/)
    - [5.1. Utilisateurs et groupes Linux](https://linux.goffinet.org/05-01-utilisateurs-et-groupes-linux/)
    - [5.2. Opérations sur les utilisateurs et les groupes](https://linux.goffinet.org/05-02-operations-sur-les-utilisateurs-et-les-groupes/)
    - [5.3. Permissions Linux](https://linux.goffinet.org/05-03-permissions-linux/)
    - [5.4. Access control lists (ACLs) Linux](https://linux.goffinet.org/05-04-access-control-lists-acls-linux/)
    - [5.5. Pluggable Authentication Modules (PAM)](https://linux.goffinet.org/05-05-pluggable-authentication-modules-pam/)
- [6. Processus et démarrage](https://linux.goffinet.org/06-00-processus-et-demarrage/)
    - [6.1. Noyau Linux](https://linux.goffinet.org/06-01-noyau-linux/)
    - [6.2. Démarrage du système Linux](https://linux.goffinet.org/06-02-demarrage-du-systeme-linux/)
    - [6.3. Processus Linux](https://linux.goffinet.org/06-03-processus-linux/)
    - [6.4. Console virtuelles Screen](https://linux.goffinet.org/06-04-consoles-virtuelles-screen/)
- [7. Installation de logiciels](https://linux.goffinet.org/07-00-installation-logiciels/)
    - [7.1. Paquets Linux](https://linux.goffinet.org/07-01-paquets-linux/)
    - [7.2. Installation par les sources](https://linux.goffinet.org/07-02-installation-par-les-sources/)
    - [7.3. Mettre en place un dépôt de paquets](https://linux.goffinet.org/07-03-mettre-en-place-un-depot-de-paquets/)
    - [7.4. Installations automatiques](https://linux.goffinet.org/07-04-installations-automatiques/)
- [8. Scripts Shell](https://linux.goffinet.org/08-scripts-shell/)
- [9. Virtualisation KVM](https://linux.goffinet.org/09-virtualisation-kvm/)
- [10. Disques et Stockage LVM](https://linux.goffinet.org/10-disques-et-stockage-lvm/)
- [11. Configuration du réseau](https://linux.goffinet.org/11-00-configuration-du-reseau/)
    - [11.1. Introduction à TCP/IP](https://linux.goffinet.org/11-01-introduction-a-tcp-ip/)
    - [11.2. Synthèse rapide des commandes réseau sous Linux](https://linux.goffinet.org/11-02-synthese-des-commandes-reseau/)
    - [11.3. Gestion du réseau Linux avec NetworkManager](https://linux.goffinet.org/11-03-gestion-du-reseau-linux-avec-networkmanager/)
    - [11.4. Gestion du réseau Linux avec la librairie iproute2](https://linux.goffinet.org/11-04-gestion-du-reseau-linux-avec-la-librairie-iproute2/)
    - [11.5. Outils Linux réseau](https://linux.goffinet.org/11-05-outils-linux-reseau/)
- [12. Secure Shell](https://linux.goffinet.org/12-secure-shell/)
- [13. Gestion sécurisée](https://linux.goffinet.org/13-gestion-securisee/)
- [14. Routage et Pare-feu](https://linux.goffinet.org/14-routage-et-pare-feu/)
- [15. Confidentialité](https://linux.goffinet.org/41_securite_linux_confidentialite/)
- [16. PKI et TLS ](https://linux.goffinet.org/42_securite_linux_pki_et_tls/)
- [17. Audit](https://linux.goffinet.org/43_securite_linux_audit/)

### [II. Services Réseau](https://linux.goffinet.org/20_services_reseau/)

- [1. Laboratoires Services Réseau](https://linux.goffinet.org/20a_laboratoires_services_reseau/)
- [2. Services de passerelle](https://linux.goffinet.org/21_services_de_passerelle/)
- [3. Services d'infrastructure](https://linux.goffinet.org/22_services_infrastructure/)
- [4. Services de partage](https://linux.goffinet.org/23_services_partage/)
- [5. Authentification centralisée](https://linux.goffinet.org/24_services_authentification_centralisee/)
- [6. Services de Messagerie](https://linux.goffinet.org/25_services_messagerie/)
- [7. Services de surveillance](https://linux.goffinet.org/26_services_de_surveillance/)
- [8. Services Web](https://linux.goffinet.org/30_services_web/)
- [9. Apache HTTP Server](https://linux.goffinet.org/31_services_apache_http_server/)
- [10. Nginx comme Proxy](https://linux.goffinet.org/32_services_nginx/)
- [11. Services de Base de Données](https://linux.goffinet.org/33_services_base_de_donnees/)


## Administration Linux : 2e partie

* [Lab Automation LAMP Wordpress](lab-automation-wordpress.md)

## Docker

En préparation

## Puppet

En prépration

## [Ansible](https://ansible.goffinet.org)

En travail.

## Git

* [Création d'un compte Github](https://nexus-coding.blogspot.com/2015/10/tutoriel-creation-dun-compte-github-et.html)
* [git - petit guide](http://rogerdudler.github.io/git-guide/index.fr.html)
* [Ajouter une clé SSH à son compte github](https://help.github.com/articles/adding-a-new-ssh-key-to-your-github-account/)
* [Changer d'origine https en ssh](https://help.github.com/articles/changing-a-remote-s-url/)

## Jenkins

En préparation.

## [Amazon Web Services](https://aws-dev.goffinet.org)

En travail.
