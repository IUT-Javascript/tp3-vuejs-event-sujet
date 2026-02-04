# TP Vue.js - Gestion d'Articles

## 📋 Objectifs

Dans ce TP, vous allez implémenter les fonctionnalités de création et suppression d'articles avec une API externe.

---

## 🎯 Fonctionnalités à implémenter

### 1️⃣ Ajouter un article
- **Formulaire** : À la validation du formulaire, émettre un événement pour faire remonter l'article au composant parent
- **Liste** : Ajouter l'article au début de la liste (côté client)
- **API** : Ajouter l'article sur l'API https://jsonplaceholder.typicode.com/posts
  - ⚠️ **Note** : L'ID est auto-généré par l'API

### 2️⃣ Supprimer un article
- **Bouton** : Ajouter un lien ou bouton "supprimer" sur l'affichage de chaque article
- **Événement** : Au clic sur le bouton supprimer, émettre un événement au composant parent (la liste)
- **Liste** : Supprimer l'article de la liste (côté client)
- **API** : Supprimer l'article sur l'API https://jsonplaceholder.typicode.com/posts

---

## 📚 Ressources utiles

| Sujet | Lien |
|-------|------|
| **Event Handling** | [Event Handling - Vue.js](https://vuejs.org/guide/essentials/event-handling) |
| **Events between Components** | [Component Events - Vue.js](https://vuejs.org/guide/components/events.html) |

---

## 💡 Conseils

- Utilisez `emit()` pour communiquer entre composants
- Testez vos appels API avec les outils de développement
- Vérifiez les appels dans l'onglet Network du navigateur
