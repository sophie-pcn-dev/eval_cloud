# Rapport de déploiement - Sophie PONCIN
## Liens
- **Application en ligne :** [https://projet-cloud-sp.osc-fr1.scalingo.io/]
- **Dépôt de code :** [https://github.com/sophie-pcn-dev/eval_cloud.git]

## Prérequis techniques
- PHP 8.5
- Composer 2.9.7
- Symfony CLI 5.17.1
- GIT
- Un compte Scalingo
- Une application sur Scalingo

## Fichier de configuration CI

Utilisation du fichier de configuration "ci.yaml" dans le dossier "workflows" du dossier à la source du projet ".github"

## Procédure de déploiement pas à pas

- Création d'un compte Scalingo
- Création d'une application sur Scalingo
- Liaison à un repository github
- Activer le déploiement automatique sur Scalingo
- Déclenchement manuel du déploiement
- Vérification de l'accessibilité au site en ligne via "https://projet-cloud-sp.osc-fr1.scalingo.io/"