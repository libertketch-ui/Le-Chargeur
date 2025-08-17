# ⚡ Le-Chargeur

**Le-Chargeur** est une application mobile Flutter conçue pour révolutionner la réservation de billets de transport interurbain au Cameroun. Elle permet aux utilisateurs de rechercher des trajets, réserver des places, payer via Mobile Money, et recevoir un billet numérique sécurisé — le tout en quelques clics.

---

## 📱 Téléchargement

👉 [Télécharger l'APK](./app-release.apk)

> Compatible avec Android 8.0 et versions ultérieures.

---

## 🚀 Fonctionnalités principales

- 🔍 **Recherche de trajets** : filtre par ville, date et heure
- 💳 **Paiement Mobile Money** : intégration avec MTN et Orange via CinetPay
- 🎟️ **Billet numérique** : QR code unique pour embarquement
- 🔔 **Notifications** : rappels de départ et mises à jour en temps réel
- 🧾 **Historique** : accès aux trajets passés et billets archivés

---

## 🛠️ Technologies utilisées

| Composant        | Stack technique                     |
|------------------|-------------------------------------|
| Frontend mobile  | Flutter (Dart)                      |
| Backend API      | Node.js + Express                   |
| Base de données  | MongoDB Atlas                       |
| Paiement         | CinetPay API (Mobile Money)         |
| Authentification | JWT + bcrypt                        |
| QR Code          | `qr_flutter`                        |

---

## 📸 Aperçu de l'application

Ajoutez vos captures d’écran dans le dossier `/assets` pour illustrer :
<p align="center">
  <img src="assets/banner.png" alt="Le-Chargeur Banner" width="100%" />
</p>
- Écran de recherche
- Paiement Mobile Money
- Billet avec QR code

---

## 🧪 Tests

- ✅ Tests unitaires backend avec Jest
- ✅ Tests d’intégration API
- ✅ Tests Flutter avec `flutter test` et `integration_test`
- 🔐 Sécurité des données assurée par chiffrement et authentification JWT

---

## 📦 Déploiement

- Backend hébergé sur DigitalOcean (Docker + CI/CD GitHub Actions)
- Base MongoDB sécurisée sur MongoDB Atlas
- APK distribué via GitHub Releases et Google Drive

---

## 📬 Contact

Développé par **Vaurice**  
📧 libertketch@gmail.com 
🌍 Basé à Bucarest, Roumanie

---

## 📄 Licence

Ce projet est sous licence MIT.  
Libre d’utilisation, de modification et de distribution.

---

## 💡 À venir

- Version iOS via TestFlight  
- Suivi en temps réel des véhicules  
- Intégration d’un système de fidélité  
- Tableau de bord pour les transporteurs

---

> Ce projet est en constante évolution. N’hésitez pas à proposer des améliorations ou à contribuer via pull request.flutter build apk --release
