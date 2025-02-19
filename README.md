# 🚀 Browser JS

## 🌟 Description
Ce projet est un script Node.js permettant d'envoyer des requêtes HTTP via un proxy et d'extraire des informations essentielles des réponses, telles que le titre de la page et la présence de challenges JavaScript.

## 📌 Fonctionnalités
- 📡 **Requêtes HTTP via Proxy**
- 🔎 **Extraction automatique du titre de la page**
- 🛡️ **Détection des challenges JavaScript**
- 🍪 **Récupération des cookies**
- ⚡ **Exécution automatique d'un script en fonction des résultats**
- ⏳ **Limitation du temps d'exécution**
- 🔥 **Gestion des erreurs et logs colorés**

## 🛠️ Prérequis
- **Node.js** (version 14+ recommandée)
- **npm** ou **yarn**
- **Fichier de proxies et APIs**

## 📦 Installation
```bash
# Cloner le dépôt
git clone https://github.com/MedusaSH/BrowserV1.git
cd BROWSERJS

# Installer les dépendances
npm install
``` 

## 🚀 Utilisation
```bash
node script.js --host <URL_CIBLE> --list_proxies proxies.txt --list_apis apis.txt --time-limit 60 --rate-limit 5 --limit-resolver 10
```
### 🔧 Paramètres
| Paramètre          | Description                           | Obligatoire |
|--------------------|-------------------------------------|-------------|
| `--host`          | URL de la cible                     | ✅          |
| `--list_proxies`  | Fichier contenant la liste des proxies | ✅          |
| `--list_apis`     | Fichier contenant les APIs          | ✅          |
| `--time-limit`    | Temps limite d'exécution (sec)      | ❌ (default: 60) |
| `--rate-limit`    | Nombre de requêtes/sec              | ❌ (default: 5) |
| `--limit-resolver`| Nombre maximum d'APIs utilisées    | ❌ (default: illimité) |

## ⚠️ Avertissement
Ce script est à utiliser uniquement à des fins éducatives et légales. L'utilisation abusive ou illégale de ce script est strictement interdite.

## 📜 Licence
Ce projet est sous licence **MIT**. Voir le fichier `LICENSE` pour plus d'informations.

## 💡 Contribuer
Les contributions sont les bienvenues ! N'hésitez pas à ouvrir une **issue** ou une **pull request**.

---

✨ *Happy coding!* 🚀
