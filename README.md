# 🫐 nomyrtille-template

Template de base pour déployer une app sur **nomyrtille.com**.

## 🚀 Démarrage rapide

1. Clique sur **"Use this template"** → "Create a new repository"
2. Nomme ton repo (ce sera ton sous-domaine : `<nom>.nomyrtille.com`)
3. Push ton code → le déploiement est automatique

## 📦 Ce qui est inclus

- Pipeline CI/CD GitHub Actions (`.github/workflows/deploy.yml`)
- Déploiement automatique sur toutes les branches
- Preview URL sur chaque Pull Request

## 🌐 Sous-domaines

| Branche | URL |
|---|---|
| `main` | `<app>.nomyrtille.com` |
| `staging` | `<app>-staging.nomyrtille.com` |
| toute autre | `<app>-<branche>.nomyrtille.com` |

## 🛠️ Technologies supportées

Coolify détecte automatiquement via Nixpacks :
- Node.js / Bun
- Python
- PHP
- Go, Rust, Ruby...
- Docker (si `Dockerfile` présent)

## ⚙️ Variables d'environnement

Ajoute tes variables dans **Coolify** (pas dans le repo).  
Ne jamais committer de `.env` avec des secrets.

## 🆘 Problème de déploiement ?

Vérifie les logs dans :
- GitHub Actions → onglet **Actions** du repo
- Coolify → dashboard de ton app

Contact : Tounsi98(https://github.com/tounsi98)
