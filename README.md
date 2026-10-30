# Easy Dentaire — Sauvegardes

Documentation de l’intégration Vercel interne de WEEZYO. Version du 30 octobre 2026.

**État : qualification en cours.** La publication de cette documentation n’atteste pas une sauvegarde Vercel active, complète ou restaurable. L’intégration reste privée ; ces documents sont publics pour permettre leur consultation avant toute installation.

## Fonction

L’intégration permet aux personnes habilitées par WEEZYO de contrôler les versions déployées de deux projets : la console d’administration Easy Dentaire et le relais de formulaires Easy Dentaire. Ces contrôles servent à rapprocher les déploiements des archives de sources préparées séparément.

Ce dépôt contient uniquement la documentation, les conditions d’utilisation et la notice de confidentialité. Il ne contient ni logiciel, ni identifiant de connexion, ni fichier de sauvegarde.

## Permissions

| Permission Vercel | Finalité |
|---|---|
| Integration Configuration — Read | Vérifier l’identité, l’état et le périmètre de l’installation |
| Deployments — Read | Vérifier les déploiements des deux projets sélectionnés |

Tous les autres droits sont désactivés. La permission Deployments — Read peut permettre l’accès à des métadonnées, événements et fichiers techniques des projets concernés ; elle est plus large que la seule lecture de deux alias. Le collecteur doit se limiter aux opérations nécessaires à la sauvegarde et à sa vérification.

L’installation doit sélectionner individuellement les deux projets prévus. Elle ne doit pas donner accès à tous les projets. Aucun droit de modification, de suppression ou de publication n’est demandé. L’intégration ne fournit pas d’accès autonome aux bases métier ou au stockage de médias, qui relèvent d’autorisations distinctes.

## Utilisation par un opérateur habilité

1. Lire les [conditions d’utilisation](conditions-utilisation.md) et la [notice de confidentialité](confidentialite.md).
2. Vérifier que l’intégration est privée et que seuls les deux droits de lecture ci-dessus sont demandés.
3. Sélectionner uniquement la console Easy Dentaire et son relais de formulaires.
4. Terminer le parcours d’autorisation depuis le dispositif de raccordement prévu par l’exploitant. Les secrets doivent être saisis dans l’espace confidentiel prévu, jamais dans un message ou dans ce dépôt.
5. Faire contrôler les identités, la portée et l’état de l’installation avant de remettre son accès au lecteur de sauvegarde.
6. Vérifier séparément la collecte, les copies chiffrées et la récupération d’une archive. Un message de réussite ou l’obtention d’un jeton ne suffisent pas à valider ces opérations.

Une portée inattendue, une réponse incohérente ou un échec de contrôle entraîne l’arrêt du raccordement. Aucun accès plus puissant ne doit être substitué automatiquement. Les droits ne sont pas extensibles par l’opérateur depuis cette documentation : une évolution requiert une décision explicite de WEEZYO et la mise à jour des informations applicables.

## Qualification, sauvegarde et arrêt

Les essais de préparation ne constituent pas la preuve d’un fonctionnement réel. L’intégration seule ne sauvegarde pas l’ensemble du système d’information. Les archives de sources, les données métier, les médias et les preuves de restauration doivent être qualifiés dans leurs périmètres respectifs.

Le dispositif vise la création d’archives chiffrées et leur contrôle sur des espaces séparés. La sauvegarde Vercel régulière ne doit pas être activée avant la validation des accès, de la couverture, de la récupération et des règles de conservation.

L’exploitant peut arrêter le lecteur et révoquer l’installation. La révocation empêche les lectures futures mais ne supprime pas automatiquement les copies déjà conservées. Toute restauration en production exige une décision distincte.

## Exploitant et assistance

**WEEZYO SAS**, SIREN 531 819 480, 199 rue Hélène Boucher, Parc Mermoz — Immeuble Le Millénaire, 34170 Castelnau-le-Lez, France. Easy Dentaire est une marque de WEEZYO.

Assistance et signalement : [gerald.chosson@easydentaire.fr](mailto:gerald.chosson@easydentaire.fr). Ne joindre aucun mot de passe, clé ou code d’autorisation à une demande.
