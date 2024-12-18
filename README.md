**Cahier des Charges pour une Application React.js affichant les taux des Cryptomonnaies**

---

## 1. Contexte et Objectifs
L'objectif de ce projet est de développer une application web en React.js permettant de récupérer les données d'une API de cryptomonnaies (telles que CoinGecko ou CoinMarketCap) et d'afficher les taux actuels des différentes cryptomonnaies en temps réel. L'application doit offrir une interface simple et intuitive pour permettre aux utilisateurs de consulter les cours, les variations et les informations clés.

---

## 2. Spécifications Fonctionnelles

### 2.1 Fonctionnalités Principales
- **Affichage des taux en temps réel** :
  - Récupération des données depuis une API publique de cryptomonnaies.
  - Affichage des prix actuels, variations sur 24h, et capitalisation de marché.

- **Recherche et Filtrage** :
  - Recherche par nom ou symbole de cryptomonnaie.
  - Filtrage par classement ou variations.

- **Détails d'une cryptomonnaie** :
  - Informations complètes sur une cryptomonnaie sélectionnée (prix, volume, historique).

- **Conversion** :
  - Conversion d'une cryptomonnaie vers une autre ou vers des monnaies fiduciaires (USD, EUR, etc.).

### 2.2 Fonctionnalités Complémentaires
- **Graphiques** :
  - Affichage des courbes de prix historiques (sur 7 jours, 30 jours, etc.).

- **Notifications** :
  - Alerte sur les grandes variations (>5% sur 24h).

---

## 3. Spécifications Techniques

### 3.1 Frontend
- **Technologie** : React.js.
- **Langage** : JavaScript (avec ES6+) et JSX.
- **Bibliothèques** :
  - Axios pour les appels API.
  - Chart.js ou Recharts pour les graphiques.
  - Tailwind CSS ou Material-UI pour le design.

### 3.2 API Externe
- **Source de Données** :
  - Utilisation de l'API CoinGecko ou CoinMarketCap.
  - Données sur les prix, variations, et classement des cryptomonnaies.

### 3.3 Infrastructure
- **Hébergement** :
  - Local pour développement et test.

---

## 4. User Stories

### Utilisateur : Anonyme
1. **En tant qu'utilisateur, je veux voir les taux des cryptomonnaies en temps réel**
   - Critères d'acceptation :
     - Les taux sont affichés avec leur nom, symbole, et variation.

2. **En tant qu'utilisateur, je veux rechercher une cryptomonnaie par nom ou symbole**
   - Critères d'acceptation :
     - Le champ de recherche filtre dynamiquement les résultats.

3. **En tant qu'utilisateur, je veux consulter les détails d'une cryptomonnaie**
   - Critères d'acceptation :
     - Le clic sur une cryptomonnaie affiche les informations complètes.

4. **En tant qu'utilisateur, je veux convertir une cryptomonnaie vers une autre**
   - Critères d'acceptation :
     - Le système affiche le montant équivalent après conversion.

5. **En tant qu'utilisateur, je veux voir l'évolution des prix sous forme de graphique**
   - Critères d'acceptation :
     - Les graphiques affichent les données correctement avec une échelle adaptée.

---

