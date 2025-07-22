# Projet Copilot pour Odoo

## Transfert vers GitHub
- Date du transfert : 21/07/2025
- Dépôt GitHub : https://github.com/gregson/copilot_core
- Branche principale : main
- Branche Odoo : 18.0 (requise pour l'intégration avec Odoo)

## Structure du projet
Le projet est un module Odoo nommé "copilot_core" qui contient les éléments suivants :
- Documentation (GUIDE_UTILISATION.md, INSTALLATION.md, etc.)
- Modèles Python dans le dossier "models"
- Vues XML dans le dossier "views"
- Fichiers de traduction dans le dossier "i18n"
- Fichiers de sécurité dans le dossier "security"
- Ressources statiques dans le dossier "static"

## Gestion du code source
Pour mettre à jour le dépôt GitHub après des modifications locales :
```
git add .
git commit -m "Description des modifications"
git push origin 18.0  # Utiliser la branche 18.0 pour Odoo
```

Pour récupérer les dernières modifications depuis GitHub :
```
git pull origin 18.0  # Utiliser la branche 18.0 pour Odoo
```

Note : La branche 18.0 est spécifiquement requise par Odoo pour l'intégration du module.
