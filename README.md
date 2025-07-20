# Exceller
Site dédiée à la formation sur le recrutement dans l'humanitaire et les institutions internationales
🌍 InnovaScope Academy - Site Web
Site web responsive et bilingue (FR/EN) pour la formation "Préparer sa candidature ONG / Nations Unies" d'InnovaScope Group.
✨ Fonctionnalités
Design responsive : Compatible mobile, tablette et desktop
Bilingue : Français et Anglais avec changement de langue en temps réel
Système de design : Couleurs et typographie InnovaScope
Sections complètes :
Hero avec appel à l'action
Présentation des avantages
Sessions de formation avec inscription
Programme détaillé
Témoignages
Footer avec informations de contact
Modal d'inscription : Formulaire complet avec options de paiement
Animations : Transitions fluides et effets visuels
🎨 Design System
Élément
Valeur
Couleur primaire
#005F73 (Bleu profond ONG)
Couleur accent
#F4A261 (Orange chaleur humanitaire)
Couleur succès
#2A9D8F
Arrière-plan
#FAFAFA
Typographie
Inter (Google Fonts)

🚀 Installation et démarrage
Prérequis
Node.js 18+
pnpm (ou npm)
Installation
# Cloner le projet

git clone <repository-url>

cd innovascope-academy

# Installer les dépendances

pnpm install

# Démarrer le serveur de développement

pnpm run dev

# Construire pour la production

pnpm run build

# Prévisualiser la version de production

pnpm run preview
📁 Structure du projet
innovascope-academy/

├── public/                 # Fichiers statiques

├── src/

│   ├── assets/            # Images et ressources

│   │   └── innovascope-logo.jpg

│   ├── components/        # Composants React

│   │   ├── ui/           # Composants UI (shadcn/ui)

│   │   ├── LanguageSwitcher.jsx

│   │   └── PaymentModal.jsx

│   ├── App.jsx           # Composant principal

│   ├── App.css           # Styles personnalisés

│   ├── i18n.js           # Configuration internationalisation

│   └── main.jsx          # Point d'entrée

├── dist/                 # Build de production

├── package.json

└── README.md
🌐 Internationalisation
Le site supporte le français et l'anglais. Les traductions sont gérées via react-i18next.
Ajouter une nouvelle traduction
Modifier le fichier src/i18n.js
Ajouter les clés dans les objets fr et en
Utiliser t('cle.traduction') dans les composants
💳 Système de paiement
Le modal de paiement inclut :

Formulaire d'informations personnelles
Options de paiement (1 ou 2 tranches)
Méthodes de paiement (Carte bancaire, Mobile Money)
Résumé de commande

Note : L'intégration avec Paystack ou Orange Money doit être configurée en production.
📱 Responsive Design
Le site est optimisé pour :

Mobile : 320px - 768px
Tablette : 768px - 1024px
Desktop : 1024px+
🔧 Technologies utilisées
React 19 - Framework frontend
Vite - Build tool et serveur de développement
Tailwind CSS - Framework CSS utilitaire
shadcn/ui - Composants UI
Lucide React - Icônes
react-i18next - Internationalisation
Framer Motion - Animations (pré-installé)
🚀 Déploiement
Option 1: Netlify (Recommandé)
Connecter le repository GitHub à Netlify
Configurer la commande de build : pnpm run build
Dossier de publication : dist
Option 2: Vercel
Importer le projet sur Vercel
La configuration est automatique pour Vite
Option 3: Serveur traditionnel
Exécuter pnpm run build
Copier le contenu du dossier dist/ sur le serveur
Configurer le serveur pour servir index.html pour toutes les routes
📞 Support
Pour toute question ou modification :

Email : academy@innovascope.group
Téléphone : +226 XX XX XX XX
📄 Licence
© 2025 InnovaScope Group. Tous droits réservés.



Développé avec ❤️ pour InnovaScope Academy

