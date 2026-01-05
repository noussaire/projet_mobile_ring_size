# projet_mobile_ring_size
# 🔷 Ring Sizer

Ring Sizer est une application mobile complète conçue pour faciliter le calcul des tailles de bagues, bracelets et la gestion de produits en or.  
Elle permet également de suivre les prix de l'or en temps réel et d'estimer la valeur des bijoux.

---

## 2. Écran d'Inscription

**Description :**  
Interface d'inscription permettant la création d'un nouveau compte utilisateur.

**Éléments clés :**
- Champ **Name** pour le nom complet
- Champ **Email** pour l'adresse électronique
- Champ **Password** pour le mot de passe
- Champ **Confirm Password** pour la vérification du mot de passe
- Bouton **REGISTER** pour soumettre le formulaire
- Lien **Already have an account? Login** pour rediriger vers la connexion

**Design :**  
En-tête doré avec fond blanc, design épuré et professionnel

---

## 3. Écran de Connexion

**Description :**  
Page de connexion sécurisée pour accéder à l'application.

**Éléments clés :**
- Logo avec icône d'image
- Titre **Ring Sizer**
- Sous-titre *Calculate ring sizes and track gold prices*
- Champ **Email**
- Champ **Password** avec icône œil pour afficher/masquer le mot de passe
- Bouton **LOGIN**
- Lien **Don't have an account? Register**

**Fonctionnalité :**  
Authentification sécurisée avec toggle de visibilité du mot de passe

---

## 4. Page d'Accueil

**Description :**  
Dashboard principal affichant les prix de l'or en temps réel et les actions rapides.

### Prix de l'Or (MAD)
- 24k : د.م. 1.429,25/g
- 22k : د.م. 1.310,19/g
- 18k : د.م. 1.071,94/g
- 14k : د.م. 833,68/g

### Quick Actions
- 👁️ Ring Calculator - Measure ring size
- 🕐 Bracelet Calculator - Calculate bracelet size
- ⚖️ Gold Calculator - Calculate gold value
- 🖼️ Products - Browse catalog

**Navigation :**  
Barre de navigation inférieure avec icônes (Home, Products, Admin, Profile)

---

## 5. Calculateur de Bague

**Description :**  
Outil interactif pour calculer la taille de bague avec visualisation graphique.

**Éléments clés :**
- Représentation visuelle circulaire du diamètre (35.7 mm)
- Boutons **−** et **+** pour ajuster la mesure
- Affichage : **35.7 mm**

### Conversions automatiques
- Circonférence : 112.2 mm
- US : 30
- UK : 29.5
- EU : 44

- Zone **Notes (optional)**
- Bouton **SAVE MEASUREMENT**

---

## 6. Calculateur de Bracelet

**Description :**  
Outil de calcul basé sur la circonférence du poignet.

**Instructions :**  
Measure your wrist circumference using a flexible measuring tape or string.

**Champs :**
- Wrist Circumference (cm) : 14

**Fit Type :**
- Snug
- Comfortable
- Loose (sélectionné)

**Résultat :**
- Wrist : 14.0 cm
- Bracelet : 16.5 cm
- Fit : Loose

- Notes (optional)
- Bouton **SAVE MEASUREMENT**

---

## 7. Catalogue de Produits

**Description :**  
Affichage en grille des produits disponibles.

### Produits
**teeeeeest**
- 18k
- 10.5g
- MAD 1000.00

**Tesst 2**
- 22k
- 18.0g
- MAD 12799.00

**dream ring**
- 24k
- 12.0g
- MAD 9999.00

**Design :**  
Cartes produits avec fond doré

---

## 8. Calculateur de Valeur d'Or (Partie 1)

**Description :**  
Interface de calcul de la valeur estimée.

### Current Gold Prices (MAD)
- 24k : د.م. 1.429,25/g
- 22k : د.م. 1.310,19/g
- 18k : د.م. 1.071,94/g
- 14k : د.م. 833,68/g

### Formulaire
- Item Type : Ring / Bracelet / Other
- Weight : 4g
- Size (US) : 7
- Gold Purity : 24k / 22k / 18k / 14k
- Making Charges : 0%
- Bouton **CALCULATE VALUE**

---

## 9. Calculateur de Valeur d'Or (Résultat)

**Estimated Value :**
- د.م. 5.717,00

**Détails :**
- Gold Value : د.م. 5.717,00
- Making Charges : د.م. 0,00
- Price/Gram : د.م. 1.429,25

**Formule :**  
(Poids × Prix au gramme × Pureté) + Frais + Supplément taille

---

## 10. Détail du Produit

- Nom : teeeeeest
- Description : Test description
- Type : Ring
- Purity : 18k
- Weight : 10.5g
- Size : 10
- Condition : New
- Prix : MAD 1000.00

**Owner Information**
- Phone : 0600000000
- City : Casablanca

Bouton **CALL OWNER**

---

## 11. Gestion des Produits (Admin)

Fonctionnalités :
- TOGGLE : Activer/Désactiver
- EDIT : Modifier
- DELETE : Supprimer
- Bouton **+** pour ajouter

---

## 12. Ajouter un Produit

### Champs
- Product Name *
- Description
- Product Type
- Gold Purity
- Weight
- Size
- Currency : MAD
- Estimated Price
- Owner Phone
- Owner City
- Condition : New
- Images (max 5)
- Published
- Bouton **SAVE PRODUCT**

---

## 13. Profil Utilisateur

- Avatar
- Nom
- Email
- Badge Admin
- Historique des mesures
- Bouton **LOGOUT**

---

## 🎨 Design System

### Couleurs
- Or : #D4AF37
- Blanc : #FFFFFF
- Gris foncé
- Vert pour actions positives

### Composants
- Cartes avec ombres
- Boutons arrondis
- Champs dorés
- Icônes minimalistes

---

## 📋 Technologies Utilisées

- Framework mobile : React Native / Flutter
- Backend : Node.js / Firebase / Laravel
- Base de données : MongoDB / PostgreSQL / Firebase
- API : Gold Price API

---

## 🛠️ Installation

```bash
git clone https://github.com/noussaire/ring-sizer.git
cd ring-sizer
npm install
npm start
