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

## 4. Fonctionnalités attendues
- S’inscrire / Se connecter (authentification sécurisée).

- Ajouter des revenus et des dépenses manuellement.

- Définir les dépenses/revenus récurrents (quotidiens, hebdomadaires, mensuels...).

- Catégoriser chaque entrée (loyer, alimentation, transport, etc.).

- Visualiser le solde du mois en temps réel.

- Générer des rapports mensuels avec graphiques.

- Voir l’historique avec filtrage.

- Alertes lorsque certaines limites sont atteintes.

- Responsive design .

## 5. Contraintes techniques
**Technologies imposées :**

1. **Frontend :** React.js / CSS pur
1. **Backend :** laravel (API avec le front-end, sanctume pour l'authentification)
1. **Autres :** Chart.js ou Recharts pour les graphiques


**Base de données prévue :** MySQL ou PostgreSQL



**Mobilité / Responsiveness :** Doit fonctionner parfaitement sur smartphones (priorité), mais aussi accessible sur tablette et PC.

**Sécurité :** Données chiffrées, sécurisation de l’API, validation serveur et client.

# Tableau des utilisateurs et rôles

|Type d’utilisateur|Description|Rôles / Actions autorisées dans l’application|
|------------------|-----------|---------------------------------------------|
|Guest|Un visiteur qui souhaite utiliser rapidement l'application pour partager une facture avec des amis, sans créer de compte|- Access app without full registration <br>- Create a temporary group for bill splitting <br> - Enter and split expenses <br>- Upgrade to full account to save data permanently |
|Utilisateur simple|Étudiant, salarié ou freelance souhaitant suivre ses finances personnelles|- Créer un compte / Se connecter <br>- Ajouter/modifier/supprimer des revenus et dépenses <br>- Créer des catégories personnalisées <br>- Générer un rapport mensuel <br>- Visualiser les statistiques par période <br>- Définir des dépenses récurrentes (loyer, abonnements...) <br>- Recevoir des alertes de dépassement de budget <br> - Créer ou rejoindre un groupe de dépenses partagées (fonctionnalité future) <br> - Diviser les dépenses et suivre les remboursements |
|Administrateur|ME|- Gérer les utilisateurs <br> - Surveiller toutes les transactions et l’activité du système <br> - Gérer les groupes partagés <br> - Configurer les paramètres globaux de l’application <br> - Modifier ou réinitialiser les budgets ou les données des utilisateurs si nécessaire|
