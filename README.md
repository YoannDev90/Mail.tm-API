# Gestionnaire d'E-mails Temporaires

Ce script Python permet de créer et gérer des adresses e-mail temporaires en utilisant l'API de mail.tm. Il offre des fonctionnalités pour créer des comptes, lister les messages reçus et lire le contenu des e-mails.

## Fonctionnalités

- Création de comptes e-mail temporaires
- Génération de noms d'utilisateur et mots de passe aléatoires
- Récupération de tokens d'authentification
- Listage des messages reçus
- Lecture du contenu des messages (texte et HTML)

## Prérequis

- Python 3.6 ou supérieur
- Les bibliothèques listées dans `requirements.txt`

## Installation

1. Clonez ce dépôt ou téléchargez le script.
2. Installez les dépendances :

```bash
pip install -r requirements.txt
```

## Utilisation
Pour utiliser le script, exécutez-le simplement avec Python :

```bash
python nom_du_script.py
```

Le script effectuera automatiquement les opérations suivantes :

    Création d'un nouveau compte e-mail temporaire
    Obtention d'un token d'authentification
    Listage des messages reçus (s'il y en a)
    Lecture du premier message (s'il existe)

## Structure du Code

    generate_random_username() : Génère un nom d'utilisateur aléatoire.
    generate_random_password() : Génère un mot de passe aléatoire.
    get_domain() : Récupère un domaine disponible pour la création de l'adresse e-mail.
    create_account() : Crée un nouveau compte e-mail temporaire.
    get_token() : Obtient un token d'authentification pour un compte.
    list_messages() : Liste les messages reçus pour un compte donné.
    get_text_from_html() : Extrait le texte lisible d'un contenu HTML.
    read_message() : Lit le contenu d'un message spécifique.
