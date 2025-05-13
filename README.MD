# Source Code
1. [Front End](https://github.com/4db444/SBB_frontEnd)
1. [Back End](https://github.com/4db444/SBB_backEnd)

# Cahier des charges simplifié
## 1. Présentation du projet
**Nom du projet :** Student Budget Buddy

**Brève description :**
Application web intuitive permettant aux étudiants de suivre leurs revenus et dépenses, organisés par catégories, afin de mieux gérer leur budget mensuel.

**Objectif principal de l’application :**
Permettre aux étudiants de surveiller et maîtriser leurs finances personnelles en visualisant clairement leurs entrées et sorties d’argent.

## 2. Problèmes à résoudre / besoins exprimés
- Manque de visibilité sur les dépenses quotidiennes chez les étudiants.

- Difficulté à savoir combien il reste à dépenser chaque mois.

- Besoin d’une gestion simple, rapide et visuelle du budget personnel.

- Organisation automatique des dépenses (loyer, alimentation, transport …) et des revenus (salaire, bourse …).

- Statistiques utiles et claires à la fin de chaque mois pour aider à ajuster les dépenses.

## 3. Utilisateurs cibles
**Étudiants souhaitant gérer leur budget :**
Étudiants vivant seuls ou en colocation, souhaitant maîtriser leurs dépenses mensuelles (loyer, nourriture, transports, loisirs, etc.) et éviter les difficultés financières à la fin du mois.

**Utilisateurs individuels :**
Toute personne (salarié, freelance, jeune actif, etc.) recherchant une application simple et efficace pour organiser ses revenus et ses dépenses au quotidien.

**Groupes d'amis (fonctionnalité à venir) :**
Une prochaine mise à jour vous permettra de partager vos dépenses avec d'autres utilisateurs, facilitant ainsi la gestion des dépenses de groupe (voyages, colocation, sorties, séjours).

## 4. Fonctionnalités attendues + temps estimé

|Fonctionnalités|temps estimé|
|---------------|:------------:|
|S’inscrire / Se connecter (authentification sécurisée).|3h|
|Ajouter des revenus et des dépenses manuellement.|4h|
|Définir les dépenses/revenus récurrents (quotidiens, mensuels...).|5h|
|Catégoriser chaque entrée (loyer, alimentation, transport, etc.).|2h|
|Visualiser le solde du mois en temps réel.|5h|
|Générer des rapports mensuels avec graphiques.|5h|
|Voir l’historique avec filtrage.|4h|
|Alertes lorsque certaines limites sont atteintes.|4h|
|Créer des groupes avec des amis.|7h|
|Sélectionner les bénéficiaires et répartir la facture.|8h|
|Suivre les soldes et régler les comptes.| 8h|
|Responsive design .|5h|

## 5. Contraintes techniques
**Technologies imposées :**

1. **Frontend :** React.js / CSS pur
1. **Backend :** laravel (API avec le front-end, sanctume pour l'authentification)
1. **Autres :** Chart.js ou Recharts pour les graphiques

**Base de données prévue :** MySQL.

**Mobilité / Responsiveness :** Doit fonctionner parfaitement sur smartphones (priorité), mais aussi accessible sur tablette et PC.

**Sécurité :** Données chiffrées, sécurisation de l’API, validation serveur et client.

# Tableau des utilisateurs et rôles

|Type d’utilisateur|Description|Rôles / Actions autorisées dans l’application|
|------------------|-----------|---------------------------------------------|
|Guest|Un visiteur qui souhaite utiliser rapidement l'application pour partager une facture avec des amis, sans créer de compte|- Créer un groupe temporaire pour le partage de facture <br>- Saisir et diviser les dépenses <br>- Passer à un compte complet pour sauvegarder les données de manière permanente |
|Utilisateur simple|Étudiant, salarié ou freelance souhaitant suivre ses finances personnelles|- Créer un compte / Se connecter <br>- Ajouter/modifier/supprimer des revenus et dépenses <br>- Créer des catégories personnalisées <br>- Générer un rapport mensuel <br>- Visualiser les statistiques par période <br>- Définir des dépenses récurrentes (loyer, abonnements...) <br>- Recevoir des alertes de dépassement de budget <br> - Créer ou rejoindre un groupe de dépenses partagées (fonctionnalité future) <br> - Diviser les dépenses et suivre les remboursements |
|Administrateur|ME|- Gérer les utilisateurs <br> - Surveiller toutes les transactions et l’activité du système <br> - Gérer les groupes partagés <br> - Configurer les paramètres globaux de l’application <br> - Modifier ou réinitialiser les budgets ou les données des utilisateurs si nécessaire|


# Diagrammes  
Ce projet comporte deux diagrammes principaux :

1. [Diagramme de cas d'utilisation](https://lucid.app/lucidchart/217ede86-dbcf-4516-ba52-2f2ec69a63fd/edit?viewport_loc=-2606%2C-858%2C7994%2C3800%2C0_0&invitationId=inv_dc428848-5f7d-4b6d-be30-03ba79a4a1f6)
1. [Conception de base de données](https://lucid.app/lucidchart/308214da-29ff-42ae-a295-966333af3613/edit?viewport_loc=63%2C-216%2C5116%2C2432%2C0_0&invitationId=inv_a2490311-c2ba-425a-ba70-f01cc3d38781)
1. [Conception d'interfaces utilisateurs](https://www.figma.com/design/2I6dAhqNzGaQRs2l4bywcf/Untitled?node-id=0-1&t=GoUcJbdzkyLB470t-1)
