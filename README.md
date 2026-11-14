# L’Houcine El Assri

### Élève ingénieur INSEA · Cloud & DevOps

En dernière année de Data & Software Engineering, je me spécialise en Cloud & DevOps : automatisation des tests et des déploiements, conteneurisation, infrastructure déclarative et observabilité. Je recherche un **stage PFE de six mois en Cloud/DevOps**, dans la région **Rabat–Casablanca et environs** ; je suis aussi ouvert à d’autres villes et au télétravail.

## Projet principal — [PFA chez OCP](https://github.com/elassri538/pfa-ci-cd-cloud-devops)

**Conception d’un pipeline CI/CD sécurisé et réutilisable pour les applications Java/Maven.**

- Workflow GitHub Actions paramétrable : compilation, tests, détection de secrets et scan des images avec Trivy.
- Construction d’une image Docker validée, transmise aux étapes suivantes sans reconstruction.
- Configuration Terraform et mécanismes de publication et de déploiement AWS avec OIDC, ECR et Systems Manager.
- Déploiement avec contrôles de santé et restauration de l’image précédente.
- Tasks API comme application de référence ; Skill Exchange comme second cas d’intégration de la CI Java.

**Technologies DevOps :** GitHub Actions, Docker, Nginx, Trivy, Terraform, AWS.

[Voir le dépôt public de présentation du PFA](https://github.com/elassri538/pfa-ci-cd-cloud-devops) et [la fiche détaillée](projects/pfa-pipeline.md). Le code source et les détails d’infrastructure restent privés.

## [Skill Exchange](projects/skill-exchange-devops.md) — contribution DevOps

Plateforme académique d’échange de compétences entre étudiants, réalisée avec EL KIHEL Mehdi et CHARAF Said.

Contribution DevOps : sécurisation des accès, tests automatisés, conteneurisation et intégration de la CI réutilisable du PFA.

[Voir la fiche du projet et les résultats vérifiés](projects/skill-exchange-devops.md). Le dépôt source est privé ; le dernier déploiement local automatique reste en échec.

## Projets publics à explorer

| Projet | Ce qu’il montre | Pour commencer |
| --- | --- | --- |
| **[Cabinet médical](https://github.com/elassri538/cabinet-medical-docker)** | Contribution DevOps à une application en équipe : Docker multistage, Compose, MySQL persistant, configuration et tests locaux | [Guide et vérifications](https://github.com/elassri538/cabinet-medical-docker#readme) |
| **[Efficacité énergétique](https://github.com/elassri538/insea-ml-energy-efficiency)** | Comparaison de cinq modèles de régression sur 768 observations UCI ; pipelines de prétraitement et validation croisée | [Notebook exécuté](https://github.com/elassri538/insea-ml-energy-efficiency/blob/main/Projet_03_Efficacite_Energetique.ipynb) |
| **[Mini Shell en C](https://github.com/elassri538/mini_shell)** | Commandes internes, entrées standard, exécution de commandes via le shell système, compilation et tests de régression | [Compiler et essayer](https://github.com/elassri538/mini_shell#compiler-et-lancer) |

## Compétences mobilisées

| Domaine | Pratique dans les projets |
| --- | --- |
| CI/CD | Git, GitHub Actions, tests, publication d’images et restauration |
| Conteneurs | Docker, Docker Compose, Nginx |
| Sécurité | Trivy, gestion des secrets, OIDC et contrôle des permissions |
| Infrastructure | Linux, Bash, Terraform, AWS |

**En cours d’apprentissage :** Kubernetes et approfondissement de l’observabilité.

Les projets en équipe précisent le périmètre de contribution. Les README donnent les étapes de lancement, les vérifications disponibles et les limites techniques.

