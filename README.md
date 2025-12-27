# Metamob TCS - Assistant Archimonstres

Un assistant moderne pour gérer votre inventaire d'archimonstres sur Metamob. Optimisé pour la rapidité et le confort d'utilisation.

![App Screenshot](icon.png)

## 🚀 Fonctionnalités

- **Inventaire Fluide** : Gérez vos captures avec des boutons +/- rapides et une synchronisation bidirectionnelle.
- **Import Massif Intelligent** : Copiez-collez vos listes de captures (depuis le jeu ou un tableur).
    - **Fuzzy Matching** : Reconnaît les noms même avec des fautes ou des formats différents.
    - **Filtrage Anti-Doublon** : Ne coche par défaut que les monstres que vous n'avez pas encore.
- **Gestion des Échanges** : Visualisez instantanément vos doubles et vos monstres manquants.
- **Performance** : Interface ultra-réactive grâce à une base de données locale (Dexie) et des composants optimisés.
- **Design Sombre** : Interface premium et reposante pour les longues sessions de jeu.

## ⚙️ Configuration

Pour utiliser l'application, vous devez configurer vos accès Metamob dans l'onglet **Configuration**.

### 1. Obtenir vos clés API
1. Connectez-vous sur [Metamob.fr](https://www.metamob.fr/).
2. Allez dans votre **Profil** > **Profil**.
3. En bas de page, vous trouverez votre **Clé API** et votre **Identifiant unique** (User Key).
4. Notez également votre **Pseudo** exact.

### 2. Remplir les champs
- **Pseudo** : Votre nom d'utilisateur Metamob.
- **Clé API** : Votre clé `api_key` (nécessaire pour lire vos données).
- **Identifiant unique** : Votre clé `user_key` (nécessaire pour envoyer vos modifications vers Metamob).


## 📝 Technologies
- **Frontend** : React 19, Lucide Icons, Framer Motion.
- **Stockage** : Dexie.js (IndexedDB).
- **Matching** : Fuse.js.
- **Backend** : Electron (Main process gérant les appels API via Axios pour éviter les problèmes de CORS).

---
*Développé pour simplifier la quête de l'Éternelle Moisson.*


