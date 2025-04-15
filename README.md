# Postal SMTP Server - Déploiement Coolify

Déploiement de Postal (serveur SMTP open source) via Coolify.

## Configuration

- Domaine SMTP : smtp.1001.tattoo
- Utilisateur admin : mattim
- Mot de passe : 1234567890
- Email admin : contact@1001.tattoo

## Instructions

1. Ajoutez un A record : smtp.1001.tattoo → IP de votre serveur Coolify.
2. Déployez ce projet Docker Compose dans Coolify.
3. Accédez à `http://smtp.1001.tattoo:8080` pour finaliser l’installation.
4. Ajoutez votre domaine, configurez SPF/DKIM/DMARC dans Postal.