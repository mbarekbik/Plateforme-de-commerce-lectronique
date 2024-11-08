Projet E-commerce Laravel Vue SPA
Un projet de plateforme e-commerce en application monopage (SPA) utilisant Laravel et Vue.js. Ce projet inclut une API REST, plusieurs types d’authentification (admin, éditeur, utilisateur) et un panneau d’administration complet.

Fonctionnalités
Authentification et Autorisation avec Breeze Starter Kit
Gestion Multi-Utilisateurs : rôles d'Administrateur, Éditeur, Utilisateur
Recherche Avancée par nom, tag, et SKU
Rapports et Statistiques : incluant des rapports graphiques
Attributs Produits Dynamiques : ajout et personnalisation d'attributs de produit
Gestion des Coupons
Options de Livraison
Intégration de Passerelle de Paiement
Paramètres du Site
Design Mobile-First pour une expérience optimale sur tous les appareils


Installation en Local
Cloner le Projet :

bash
Copier le code
git clone https://github.com/DevAmirul/Laravel-Vue-SPA-Ecommerce.git
Configuration du Frontend :

Rendez-vous dans le répertoire frontend :
bash
Copier le code
cd Laravel-Vue-SPA-Ecommerce/frontend
Installez les dépendances frontend :
bash
Copier le code
npm install
Lancez le frontend :
bash
Copier le code
npm run dev
Configuration du Backend :

Dans un nouveau terminal, accédez au répertoire backend :
bash
Copier le code
cd Laravel-Vue-SPA-Ecommerce/backend
Installez les dépendances backend :
bash
Copier le code
composer install
npm install
Configurez le fichier .env :
Créez le fichier .env en copiant .env.example.
Définissez le nom de votre base de données et ajoutez-le dans le fichier .env.
Générez une clé d’application :
bash
Copier le code
php artisan key:generate
Créez un lien de stockage :
bash
Copier le code
php artisan storage:link
Effectuez les migrations et ajoutez des données initiales :
bash
Copier le code
php artisan migrate --seed
Lancez le serveur backend :
bash
Copier le code
php artisan serve
Configuration de Vite :

Dans un autre terminal, exécutez :
bash
Copier le code
cd Laravel-Vue-SPA-Ecommerce/backend
npm run dev
Accéder à l’Application :

Ouvrez http://127.0.0.1:8000 dans votre navigateur.
Stack Technique
Client : Vue.js, Pinia, Axios, Bootstrap, SweetAlert2
Serveur : PHP 8.2, Laravel 10.x, Livewire, Bootstrap
