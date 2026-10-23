
# Terraform Certifications & Learning Notes

Notes de formation, synthèses techniques, exercices pratiques et révisions pour les certifications HashiCorp Terraform.

L'objectif de ce dépôt est de construire une compréhension approfondie de Terraform, de son langage, de son fonctionnement interne et de ses bonnes pratiques, afin de réussir les certifications et d'appliquer ces connaissances en conditions réelles.

Les notes sont rédigées en français, en conservant les termes techniques officiels en anglais. Elles s'appuient sur les formations suivies, la documentation officielle HashiCorp et des expérimentations pratiques.


## Certifications

### Terraform Associate (004)

Certification de niveau Associate validant les connaissances fondamentales de Terraform, de l'Infrastructure as Code (IaC), du langage HCL, des providers, des modules, de la gestion du state et des workflows Terraform.

#### Détails de l'examen

| Information | Détail |
|---|---|
| Type d'évaluation | Questions à choix multiples |
| Format | Examen surveillé en ligne (*Online Proctored*) |
| Durée | 1 heure |
| Langue | Anglais |
| Validité | 2 ans |
| Prix | 70,50 USD, hors taxes et frais locaux éventuels |
| Rattrapage gratuit | Non |
| Version de Terraform évaluée | Terraform 1.12 |

#### Prérequis

- Compétences de base en ligne de commande.
- Compréhension des architectures sur site (*on-premises*) et cloud.
- Expérience professionnelle recommandée, mais préparation possible au moyen d'exercices personnels.

#### Objectifs officiels de l'examen

- [ ] **1. Infrastructure as Code (IaC) avec Terraform**
  - [ ] Expliquer le principe de l'Infrastructure as Code.
  - [ ] Décrire les avantages des approches IaC.
  - [ ] Expliquer la gestion des environnements multicloud, hybrides et indépendants des services.

- [ ] **2. Fondamentaux de Terraform**
  - [ ] Comprendre l'architecture et les composants de Terraform.

- [ ] **3. Workflow Terraform**
  - [ ] Maîtriser les étapes d'initialisation, de planification et d'application.

- [ ] **4. Configuration Terraform**
  - [ ] Comprendre la syntaxe HCL et les éléments de configuration.

- [ ] **5. Modules Terraform**
  - [ ] Comprendre la création, la réutilisation et l'organisation des modules.

- [ ] **6. Gestion du state**
  - [ ] Comprendre le rôle du state et ses mécanismes de gestion.

- [ ] **7. Maintien de l'infrastructure**
  - [ ] Comprendre la mise à jour et la gestion du cycle de vie des ressources.

- [ ] **8. HCP Terraform**
  - [ ] Comprendre les fonctionnalités et les usages de HCP Terraform.

#### Renouvellement de la certification

La certification est valide pendant 2 ans.

Pour une certification Associate (004) encore valide, trois possibilités sont proposées par HashiCorp :

1. Réussir l'examen Terraform Infrastructure Engineer Professional.
2. Réussir l'examen Terraform Authoring and Operations Advanced, version AWS ou Azure.
3. Repasser l'examen Terraform Associate (004) à partir des 6 derniers mois avant expiration.

La réussite à l'une des deux certifications de niveau supérieur prolonge la validité des identifiants Associate existants et permet d'obtenir le nouveau badge correspondant.

Pour une certification Associate (002 ou 003) encore valide, le renouvellement par l'examen 004 délivre un nouveau jeu d'identifiants distinct, sans prolonger la date d'expiration de l'ancien.

Une certification expirée doit être renouvelée en réussissant la version actuelle de l'examen Associate. De nouveaux identifiants sont alors délivrés.

<br />

---

<br />

### Terraform Authoring and Operations Advanced

Certification avancée validant la capacité à concevoir, développer, maintenir et exploiter des configurations Terraform en production.

Deux variantes sont proposées : AWS et Azure. Les deux permettent d'obtenir le même titre de certification.

#### Détails de l'examen

| Information | Détail |
|---|---|
| Type d'évaluation | Scénarios pratiques en laboratoire et questions à choix multiples |
| Format | Examen surveillé en ligne (*Online Proctored*) |
| Durée | 4 heures, avec une pause de 15 minutes |
| Langue | Anglais |
| Validité | 2 ans |
| Prix | 295 USD, hors taxes et frais locaux éventuels |
| Rattrapage gratuit | Oui, une tentative supplémentaire incluse |
| Version de Terraform évaluée | Terraform 1.6 |
| Variantes disponibles | AWS ou Azure |
| Clavier | Dispositions QWERTY non américaines courantes prises en charge sur demande |

#### Prérequis

- Certification Terraform Associate recommandée, ou expérience équivalente.
- Maîtrise des commandes Linux de base et de l'édition de fichiers depuis le terminal.
- Expérience dans l'utilisation de credentials cloud.
- Connaissance des formats YAML, JSON, HCL et CSV.
- Compréhension des réseaux et des protocoles TCP/IP et UDP.
- Maîtrise avancée de la rédaction de configurations Terraform et des workflows.
- Expérience pratique de Terraform en production indispensable.

#### Objectifs officiels de l'examen

- [ ] **1. Gérer le cycle de vie des ressources**
  - [ ] Initialiser une configuration avec `terraform init` et ses options.
  - [ ] Générer un plan avec `terraform plan` et ses options.
  - [ ] Appliquer les changements avec `terraform apply` et ses options.
  - [ ] Détruire des ressources avec `terraform destroy` et ses options.
  - [ ] Gérer le state, importer des ressources et réconcilier la dérive d'infrastructure (*resource drift*).

- [ ] **2. Développer et dépanner des configurations dynamiques**
  - [ ] Utiliser les fonctionnalités du langage pour valider une configuration.
  - [ ] Interroger les providers avec des data sources.
  - [ ] Calculer et interpoler des données avec les fonctions HCL.
  - [ ] Utiliser les méta-arguments Terraform.
  - [ ] Configurer les variables d'entrée et les outputs, y compris les types complexes.
  - [ ] Appliquer les bonnes pratiques de gestion des données sensibles, notamment avec Vault.

- [ ] **3. Développer des workflows Terraform collaboratifs**
  - [ ] Gérer les versions du binaire Terraform, des providers et des modules.
  - [ ] Configurer le state distant (*remote state*).
  - [ ] Utiliser Terraform dans des workflows automatisés.
  - [ ] Partager des données entre plusieurs configurations et workspaces.

- [ ] **4. Créer, maintenir et utiliser des modules Terraform**
  - [ ] Créer un module.
  - [ ] Utiliser un module dans une configuration.
  - [ ] Refactoriser un module et gérer son versionnement.
  - [ ] Refactoriser une configuration existante en modules.

- [ ] **5. Configurer et utiliser les providers**
  - [ ] Comprendre l'architecture de Terraform fondée sur les plugins.
  - [ ] Configurer les providers : alias, versions, sources et mises à niveau.
  - [ ] Gérer l'authentification des providers.
  - [ ] Diagnostiquer les erreurs des providers.

- [ ] **6. Collaborer avec HCP Terraform**
  - [ ] Analyser le workflow d'exécution HCP Terraform.
  - [ ] Comprendre les workspaces et leurs options de configuration et d'accès.
  - [ ] Gérer les credentials des providers dans HCP Terraform.
  - [ ] Comprendre les politiques as code et les fonctionnalités de gouvernance.

#### Renouvellement de la certification

La certification est valide pendant 2 ans.

- Certification encore valide : l'examen peut être repassé à partir des 6 derniers mois avant expiration.
- En cas de réussite, la date d'expiration des identifiants existants est prolongée.
- Certification expirée : l'examen peut être repassé à tout moment. La réussite délivre de nouveaux identifiants avec une nouvelle date d'expiration.
- Le renouvellement est possible avec la variante AWS ou Azure, indépendamment de la variante initialement passée.

<br /><br />

---

<br /><br />

## Organisation du dépôt

```text
terraform-certifications-learning-notes/
├── README.md
├── docs/
│   ├── 01-fundamentals/
├── labs/
│   ├── 01-first-infrastructure/
└── .gitignore
```

- `docs/` : concepts, synthèses, documentation et révisions.
- `docs/01-fundamentals/` : notions communes aux deux certifications.