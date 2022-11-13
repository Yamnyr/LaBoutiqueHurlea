# **projet symfony "Apprendre Symfony 5 par la création d'un site e-commerce"**

## **WAROQUET Quentin**

#### https://www.udemy.com/course/apprendre-symfony-par-la-creation-dun-site-ecommerce/

## (projet réalsé a 75 %)

### prérequis :

- PHP 8.1.0 ou supérieur
- Symfony 5.4.17
- mysql
- composer

### installer base de donné:

- fichier .env:\
- changer cette ligne:
    - <code>DATABASE_URL="mysql://app:!ChangeMe!@127.0.0.1:3306/app?serverVersion=8&charset=utf8mb4"</code>

- <code>symfony console doctrine:database:create
- symfony console make:migration\
- symfony console doctrine:migration:migrate</code>

### Lancement du serveur de développement

- <code>symfony serve</code>\
  ou
- <code>symfony server:start</code>

### Contenu du projet

- #### gestion des utilisateurs :
  - création de compte
  - connexion au compte
  - deconnexion du compte
  - modification du mot de passe
  - modification des addresse
- #### boutique :
  - système de filre et de recherche
  - système de panier
  - tunnel d'achat
- #### partie admin (EasyAdmin) -> http://127.0.0.1:8000/admin
  - supression/ ajout/ modifiaction de:
    - utilisateur
    - orders
    - catégories
    - products
    - carriers
#### base de donée
  - utilisation de doctrine

#### pas encore fait
  - système de paiment
  - système d' envoie d'email avec mailjet