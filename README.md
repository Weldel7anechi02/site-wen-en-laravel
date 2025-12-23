

---

 **Aziz Hannechi — Plateforme de petites annonces**

## Description

**Aziz Hannechi** est une plateforme web de petites annonces développée avec **Laravel (MVC)**.
Elle permet aux utilisateurs de publier des annonces, de communiquer via messages et de gérer leur profil.

---

## Fonctionnalités principales

### Authentification

* Inscription utilisateur
* Connexion / Déconnexion
* Confirmation de compte par email
* Réinitialisation du mot de passe par email
* Rôles : **Admin / User**

### Annonces

* Création, consultation, modification et suppression d’annonces
* Upload jusqu’à 5 images par annonce
* Annonces associées à un utilisateur
* Système CRUD avec base de données SQL

### Recherche & filtres

* Recherche par mots-clés (priorité au titre)
* Filtrage par :

  * Catégorie
  * Utilisateur
  * Annonces avec images uniquement
  * Fourchette de prix

### Messagerie

* Envoi et réception de messages liés à une annonce
* Consultation et gestion des messages

---

## Technologies utilisées

* PHP
* Laravel
* MySQL
* Blade
* HTML / CSS / JavaScript
* Composer
* NPM

---

## Durée du projet

**5 jours**

---

## Installation (local)

1. Cloner le projet

```bash
git clone <repo-url>
cd aziz-hannechi
```

2. Installer les dépendances

```bash
composer install
```

3. Configuration

```bash
copy .env.example .env
php artisan key:generate
```

4. Base de données

```bash
php artisan migrate
```

5. Lancer le serveur

```bash
php artisan serve
```

Accès :

```
http://127.0.0.1:8000/
```

---

## Auteur

**Aziz Hannechi**


