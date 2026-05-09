# 💅 Nails by Anna

Une application web intuitive pour gérer une activité de prestation d'ongles (nail art, vernis semi-permanent, etc.). Designed pour les esthéticiens(nes) qui veulent suivre leurs prestations, gérer leurs clients et analyser leur activité en temps réel.

> **Built with:** HTML5 + Vanilla JavaScript + Firebase Firestore + PWA  
> **Status:** Fully functional single-file app  
> **License:** MIT

---

## 🎯 Features

### 📊 Dashboard
- **Vue d'ensemble en temps réel** : chiffre d'affaires du jour, semaine, mois
- **Graphiques interactifs** : tendances des prestations et revenus
- **Statistiques clés** : nombre de prestations, panier moyen, client favorit
- **Filtre par période** : accès rapide aux données de périodes antérieures

### 👥 Gestion Clients
- **Répertoire complet** : nom, téléphone, email, date de naissance
- **Historique de prestations** : toutes les interventions par client
- **Notes personnalisées** : allergies, préférences de design, rappels
- **Recherche rapide** : filtre en temps réel par nom
- **Export des données** : sauvegarde locale de tes contacts

### 💇 Prestations & Devis
- **Catalogue personnalisé** : crée ta liste de prestations avec prix
- **Devis interactifs** : calcule rapidement le prix d'une intervention
- **Formules flexibles** : combine plusieurs prestations dans un devis
- **Historique** : accès à tous tes devis antérieurs

### 📈 Dépenses & Suivi Financier
- **Enregistrement des charges** : fournitures, loyers, frais divers
- **Catégorisation** : organise tes dépenses par type
- **Analyse mensuelle** : vois le ratio dépenses/revenus
- **Tendances** : comprends tes coûts et optimise ta marge

### 📋 Bilan Mensuel
- **Résumé complet** : prestations réalisées, revenus nets, dépenses
- **Comparaisons mensuelles** : quel mois a été le plus rentable ?
- **Export PDF** : génère des rapports professionnels
- **Archivage** : consulte les données des mois antérieurs

### ⚙️ Paramètres
- **Personnalisation** : renomme l'app (ex : "Studio Nails Lara")
- **Gestion des données** : importe/exporte tes données complets
- **Synchronisation cloud** : connexion Firebase optionnelle
- **Thème** : interface sombre optimisée pour tous les appareils

---

## 🚀 Démarrage Rapide

### Installation
1. **Télécharge** le fichier `index.html`
2. **Ouvre-le** dans n'importe quel navigateur moderne
3. **C'est tout !** L'app fonctionne offline grâce au localStorage

### Mode PWA (optionnel)
Pour transformer l'app en app native sur ton téléphone :
- **iOS** : Safari → Partage → Ajouter à l'écran d'accueil
- **Android** : Chrome → Menu (⋮) → Installer l'application

### Synchronisation Cloud (optionnel)
Si tu veux syncer tes données sur plusieurs appareils :
1. Configure Firebase dans les paramètres
2. Tes données se synchro automatiquement
3. Accès depuis n'importe quel appareil

---

## 💾 Architecture Technique

### Stack
- **Frontend** : HTML5, CSS3, JavaScript vanilla (zéro dépendances)
- **Storage** : localStorage (par défaut) + Firebase Firestore (optionnel)
- **Charts** : Chart.js pour les graphiques
- **Responsive** : Mobile-first, optimisée tablet & desktop

### Structure
L'app est un **single-file HTML** pour faciliter le déploiement :
- 📱 100% responsive design
- 🔄 Synchronisation temps réel
- 💾 Offline-first avec fallback
- 🎨 Dark theme intégré

### Pages
```
📌 Dashboard     → Vue d'ensemble & KPIs
👥 Clients       → Répertoire complet
💇 Prestations   → Catalogue & devis
📉 Dépenses      → Suivi financier
📋 Bilan         → Rapports mensuels
⚙️  Paramètres   → Config & import/export
```

---

## 🎮 Utilisation

### Ajouter une prestations
1. Va sur l'onglet **Prestations**
2. Clique sur **+ Nouvelle prestation**
3. Remplis : nom, prix, durée (optionnel)
4. Sauvegarde automatique ✅

### Créer un devis
1. Va sur **Prestations** → **Nouveau devis**
2. Sélectionne le client
3. Ajoute les services
4. Le prix se calcule auto
5. Marque comme accepté/refusé

### Suivre tes revenus
1. Chaque prestation ajoutée = une ligne au Dashboard
2. Les graphiques se mettent à jour en temps réel
3. Filtre par période pour comparer

### Gérer tes dépenses
1. Va sur **Dépenses** → **+ Nouvelle dépense**
2. Renseigne : montant, catégorie, description
3. Tes dépenses se déduisent automatiquement de tes bénéfices

---

## 📱 Compatibilité

| Appareil | Navigateur | Support |
|----------|-----------|---------|
| 📱 iPhone | Safari 13+ | ✅ Excellent |
| 📱 Android | Chrome, Firefox | ✅ Excellent |
| 💻 Desktop | Chrome, Firefox, Safari, Edge | ✅ Excellent |
| ⌚ iPad | Safari | ✅ Excellent (optimisé) |

---

## 🔐 Sécurité & Vie Privée

- **Tes données restent chez toi** : stockées en local sur ton appareil
- **HTTPS recommandé** : utilise une connexion sécurisée
- **Pas de cookies de tracking** : aucune donnée envoyée à des tiers (sauf Firebase si activé)
- **Export datas** : télécharge une copie complète de tes données à tout moment

---

## 🔧 Maintenance & Troubleshooting

### L'app ne se synchronise pas
→ Vérifie la connexion Internet  
→ Réveille ton téléphone (peut être en mode veille)

### Les données ne s'affichent pas
→ Vide le cache du navigateur (Ctrl+Shift+Del)  
→ Vérifie que localStorage n'est pas désactivé

### Export/Import ne fonctionne pas
→ Essaie avec un autre navigateur  
→ Sur mobile : utilise Desktop pour les manipulations

---

## 🚀 Roadmap & Futures Features

- [ ] **Photos de designs** : galerie de tes créations
- [ ] **Rappels SMS/Email** : notifie automatiquement les clients
- [ ] **Factures PDF** : génère des devis/factures professionnels
- [ ] **Abonnements clients** : gère les abos (forfaits mensuels)
- [ ] **Intégration Stripe** : accepte les paiements en ligne
- [ ] **Planning/Calendrier** : gère les RDV en temps réel

---

## 💬 Support & Questions

Besoin d'aide ?
- **Bug report** : décris le problème + ton navigateur/OS
- **Feature request** : explique ce que tu aimerais
- **Questions** : contacte via les issues GitHub

---

## 📄 License

MIT License © 2025 Nails by Anna  
Tu es libre d'utiliser, copier, modifier cette app à titre personnel ou commercial.

---

## 🙏 Merci !

Merci d'utiliser Nails by Anna ! Si l'app t'aide dans ton business, n'hésite pas à laisser une ⭐ sur GitHub.

---

**Made with ❤️ for nail artists & esthetic professionals**
