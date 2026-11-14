# PFA chez OCP — pipeline CI/CD Java réutilisable

## Objectif

Concevoir un pipeline GitHub Actions commun à plusieurs applications Java/Maven, avec contrôles de sécurité et chemin de déploiement sur AWS. Le dépôt source du PFA est privé ; cette page décrit le travail et son état vérifié.

## Ma contribution

- Structuration d’un workflow réutilisable avec paramètres pour l’application, les tests et l’image Docker.
- Compilation et tests Maven, détection de secrets et analyse de l’image avec Trivy avant publication.
- Construction d’une image Docker unique, puis transmission de cette image validée aux étapes suivantes.
- Infrastructure déclarative Terraform et mécanismes d’authentification AWS par OIDC pour ECR et Systems Manager.
- Contrôles de santé et procédure de restauration de l’image précédente après un échec de déploiement.
- Application de référence Tasks API et intégration de la CI Java dans Skill Exchange.

## Parcours technique

`code → tests et scans → image Docker validée → publication ECR → déploiement SSM → contrôle de santé → restauration si nécessaire`

**Outils :** GitHub Actions, Maven, Docker, Trivy, Terraform, AWS ECR, OIDC, Systems Manager, Linux et Bash.

## État et limites

Une exécution réussie de la CI de référence a été vérifiée. Les tests locaux et la configuration du pipeline ne prouvent pas, à eux seuls, qu’un déploiement cloud est actuellement disponible. Le code source et les détails d’infrastructure demeurent privés.

[Retour au profil](../README.md)
