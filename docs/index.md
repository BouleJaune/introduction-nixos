# Introduction à NixOS
Voici une proposition de programme pour un cours d'introduction à NixOS sur 2 jours, avec une approche pratique (60% de travaux pratiques). Ce programme vise à donner une bonne compréhension de l'écosystème NixOS, avec des exercices concrets pour appliquer les concepts théoriques.

### **Jour 1 : Introduction à NixOS et Nix**

#### **Matin : Introduction et concepts de base**
**Introduction à NixOS**

   - Historique de NixOS
   - Principe de fonctionnement et différences avec les autres distributions Linux
   - Gestion des paquets et environnement de développement reproductible


**Concepts de base de Nix et NixOS**

   - Présentation du langage de gestion des paquets *Nix*
   - Les concepts de base : *Store Nix*, *derivations*, *expressions Nix*
   - Reproductibilité, immuabilité et isolation

**Installation de NixOS (Théorie)**

   - Structure d'une installation NixOS
   - Définition d'une configuration système via `/etc/nixos/configuration.nix`

#### **Travaux pratiques (60%) : Installation et première configuration de NixOS**

   - Installation de NixOS sur une machine virtuelle
   - Création d'une première configuration avec des paquets et services de base (par exemple, SSH, Git, Vim)
   - Construction et activation de la configuration

#### **Après-midi : Gestion des paquets avec Nix**
**Le gestionnaire de paquets Nix**

   - Principe du *nix-env* pour la gestion d'environnement utilisateur
   - Installation, mise à jour et suppression de paquets

**Environnements de développement reproductibles**

   - Les fichiers `shell.nix` et `default.nix`
   - Créer des environnements de développement spécifiques à un projet

#### **Travaux pratiques (60%) : Gestion des paquets et environnement de développement**
   - Utilisation de `nix-env` pour installer, mettre à jour et gérer des paquets
   - Créer un environnement de développement pour un projet spécifique (ex : projet Python ou Node.js)

---

### **Jour 2 : Configuration avancée et développement avec NixOS**

#### **Matin : Configuration avancée de NixOS**
**Configuration du système avec NixOS**

   - Décomposition du fichier de configuration `/etc/nixos/configuration.nix`
   - Ajout de services et gestion des utilisateurs
   - Mise en place de services système (par exemple : Nginx, Docker, Postgresql)

**Comprendre les *overlays* et les options avancées**

   - Les overlays pour étendre et personnaliser les paquets
   - Utilisation des modules NixOS

#### **Travaux pratiques (60%) : Personnalisation du système NixOS**
   - Configuration avancée de la machine NixOS avec des services supplémentaires
   - Création d'une configuration modulaire en séparant des fichiers Nix

#### **Après-midi : Introduction à NixOps et NixOS en production**
**Introduction à NixOps et gestion d'infrastructure**

   - Déploiement avec NixOps (présentation rapide)
   - Déploiement d'applications et d'infrastructure dans un environnement cloud

**Gestion des versions et rollback**

   - Mise à jour et gestion des versions des configurations système
   - Revenir à une configuration précédente grâce à l’historique immuable

#### **Travaux pratiques (60%) : Déploiement et gestion d'infrastructure**
   - Utilisation de NixOps pour déployer une simple application web sur un environnement local ou cloud
   - Tester les fonctionnalités de rollback après une mise à jour

---

### **Objectifs du cours**
- **Jour 1** : Comprendre les bases de NixOS et Nix, et être capable d'installer et configurer une machine NixOS.
- **Jour 2** : Maîtriser la configuration avancée et découvrir comment NixOS peut être utilisé en production.

Ce programme pourra être ajusté en fonction du niveau des participants ou des besoins spécifiques.
