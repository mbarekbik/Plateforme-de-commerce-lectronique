# Projet E-commerce SPA avec Laravel et Vue

J'ai développé cette plateforme e-commerce sous forme d'application monopage (SPA) en utilisant Laravel pour le backend et Vue.js pour le frontend. Ce projet inclut une API REST, la gestion de plusieurs rôles d'utilisateur, et un panneau d’administration complet, permettant ainsi une gestion fluide et sécurisée de l’e-commerce.

## Fonctionnalités
- **Authentification et Autorisation** : Mise en place via le kit Breeze Starter pour gérer les accès utilisateurs.
- **Gestion Multi-Utilisateurs** : Administration, éditeur, et utilisateur, chacun avec des droits spécifiques.
- **Recherche Avancée** : Les produits peuvent être recherchés par nom, tag, ou SKU pour une navigation plus intuitive.
- **Rapports et Statistiques** : Intégration de rapports graphiques pour le suivi des performances de la plateforme.
- **Attributs de Produit Dynamiques** : Possibilité d’ajouter et de personnaliser des attributs spécifiques aux produits.
- **Gestion des Coupons** : Ajout et gestion de coupons de réduction pour les utilisateurs.
- **Options de Livraison** : Configuration des frais et modalités de livraison.
- **Passerelle de Paiement** : Intégration d'une solution de paiement sécurisée.
- **Paramètres du Site** : Configuration facile et personnalisable des options globales du site.
- **Design Mobile-First** : Interface pensée en priorité pour les utilisateurs mobiles.

![Tableau de bord](https://i.ibb.co/zb5z8jw/spa1.png)

## Installation en Local

Pour exécuter ce projet en local, voici les étapes à suivre :

1. **Cloner le Projet :**
   ```bash
   git clone https://github.com/mbarekbik/Plateforme-de-commerce-lectronique.git
# Configuration du Projet

## Configuration du Frontend :

1. Rendez-vous dans le répertoire `frontend` :
   ```bash
   cd Laravel-Vue-SPA-Ecommerce/frontend
   
2. Installez les dépendances nécessaires pour le frontend :

   ```bash
npm install

Lancez le serveur frontend en mode développement :

   ```bash
npm run dev

Configuration du Backend :
Dans un nouveau terminal, allez dans le répertoire backend :

   ```bash
cd Laravel-Vue-SPA-Ecommerce/backend
Installez les dépendances backend :

   ```bash
composer install
npm install
Configuration de l'environnement :

Créez un fichier .env en copiant .env.example.
Ajoutez le nom de votre base de données dans le fichier .env.
Générez la clé d'application :

   ```bash
php artisan key:generate
Créez le lien de stockage :

   ```bash
php artisan storage:link
Effectuez les migrations et ajoutez les données initiales :

   ```bash
php artisan migrate --seed
Lancez le serveur backend :

   ```bash
php artisan serve
Lancer Vite pour le Backend :
Dans un autre terminal, exécutez :

   ```bash
cd Laravel-Vue-SPA-Ecommerce/backend
npm run dev
Accéder à l’Application :
Ouvrez votre navigateur et allez sur http://127.0.0.1:8000.

![Admin Dashboard](https://i.ibb.co/zb5z8jw/spa1.png)
![Orders Table](https://i.ibb.co/LhMVYzY/spa2.png)
![Customers Orders Reports](https://i.ibb.co/9WNRVmw/spa3.png)
![Orders Chart](https://i.ibb.co/phgCVbw/spa7.png)
![Settings](https://i.ibb.co/vsGPXpN/spa5.png)

Stack Technique
Client : Vue.js, Pinia, Axios, Bootstrap, SweetAlert2
Serveur : PHP 8.2, Laravel 10.x, Livewire, Bootstrap
