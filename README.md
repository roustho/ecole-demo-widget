# Site Client de Démonstration - Widget IA Scolaire

## 🎯 Objectif

Ce site de démonstration simule un site client d'école qui intègre le widget IA scolaire avec les **améliorations de la branche `correctifs_safe`**.

## 🚀 Fonctionnalités

- Site web d'école fictive avec design moderne
- Intégration du widget chat avec les **dernières améliorations**
- Configuration pour pointer vers la branche `correctifs_safe`
- Badge visuel indiquant la version améliorée
- Prêt pour déploiement Vercel

## 🔧 Configuration

Le widget est configuré pour utiliser :
- **URL API**: `https://api.school.axonovia.com/staging` (pour la branche correctifs_safe)
- **Widget Source**: URL Vercel pointant vers la branche `correctifs_safe`
- **Établissement**: `demo-school`

## 🌐 Déploiement

### Déploiement Vercel

1. Pusher le code sur GitHub
2. Connecter le dossier `demo-client-site` à Vercel
3. Déployer avec les paramètres par défaut

### Configuration des branches

- **Production** : Branche `main` → Widget production
- **Preview** : Branche `correctifs_safe` → Widget avec améliorations

## 🧪 Test local

```bash
cd demo-client-site
python3 -m http.server 3000
```

Puis ouvrir http://localhost:3000

## ✨ Améliorations incluses

Cette version utilise la branche `correctifs_safe` qui inclut :
- ✅ Correction du centrage vertical du bouton d'envoi
- ✅ Utilisation de Flexbox au lieu de transform
- ✅ Positionnement plus précis et fiable

## 📝 Notes

- Le site charge automatiquement le CSS du widget
- Le script du widget est chargé à la demande (lors du clic sur le bouton)
- Configuration flexible via `window.AbiChatConfig`