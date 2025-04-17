# Deliveroo Backend (Mock)

Ce dépôt contient une API simple qui fournit des données mock pour un clone de l'application Deliveroo.

## Description

Ce n'est pas un vrai backend, mais plutôt un serveur Express qui renvoie des données statiques simulant l'API de Deliveroo. Il permet aux développeurs frontend de travailler sur l'interface utilisateur sans avoir besoin d'une vraie connexion au backend de Deliveroo.

## Technologies utilisées

- Node.js
- Express
- CORS

## Installation

```bash
# Installation des dépendances
npm install

# Démarrage du serveur
node index.js
```

## Utilisation

Une fois le serveur démarré, l'API est disponible à l'adresse suivante :

- `http://localhost:3000/` - Renvoie les données du restaurant "Le Pain Quotidien" avec ses catégories et plats.
