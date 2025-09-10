# Documentation Prompt2Prod

Cette documentation complète présente **Prompt2Prod**, un système DevOps moderne qui transforme des idées en langage naturel en code de production déployé.

## 📚 Structure de la documentation

### Documents sources (Markdown)
- [`architecture/architecture.md`](architecture/architecture.md) - Architecture technique et DevOps
- [`api/api-reference.md`](api/api-reference.md) - Référence complète des APIs
- [`functional/user-guide.md`](functional/user-guide.md) - Guide utilisateur fonctionnel

### Documentation HTML générée
- **[📖 Page d'accueil](html/index.html)** - Interface d'accueil avec navigation
- **[🏗️ Architecture](html/architecture.html)** - Documentation technique DevOps
- **[🔌 API Reference](html/api-reference.html)** - Référence des endpoints
- **[👤 Guide Utilisateur](html/user-guide.html)** - Guide fonctionnel et cas d'usage
- **[📋 Documentation Complète](html/documentation-complete.html)** - Document unifié

## 🚀 Accès rapide

**Pour consulter la documentation :**
```bash
open docs/html/index.html
```

**Pour régénérer la documentation :**
```bash
cd docs/assets
./generate-html.sh
```

## 📋 Contenu par document

### 🏗️ Architecture Technique
- Vue d'ensemble du POC et objectifs DevOps
- Arborescence complète du projet
- Architecture cloud-native avec Kubernetes
- Pipeline CI/CD avec GitHub Actions
- Instructions de déploiement étape par étape
- Monitoring et observabilité
- Bonnes pratiques DevOps

### 🔌 Référence API
- Documentation détaillée des endpoints
- Modèles de données avec validation
- Codes d'erreur et gestion des exceptions
- Exemples pratiques avec curl et clients
- SDK Python et JavaScript
- Interface Swagger interactive

### 👤 Guide Utilisateur
- Introduction et cas d'usage
- Guide de démarrage rapide
- Exemples concrets de génération
- Bonnes pratiques pour les prompts
- Dépannage et FAQ
- Support et contribution

## 🛠️ Outils utilisés

- **[Pandoc](https://pandoc.org/)** - Conversion Markdown vers HTML
- **CSS personnalisé** - Styles professionnels
- **Highlighting** - Coloration syntaxique du code
- **Navigation** - Table des matières automatique

## 📈 Statistiques

- **3 documents** techniques complets
- **Plus de 500 lignes** de documentation technique
- **Dizaines d'exemples** de code et configurations
- **Interface web** moderne et responsive
- **Navigation intuitive** avec tables des matières

---

## À propos du POC

**Prompt2Prod** démontre une pipeline DevOps complète permettant de transformer une idée exprimée en langage naturel en un projet GitHub déployé et prêt pour la production.

**Technologies showcasées :**
- OpenHands pour l'orchestration AI
- KGateway (CNCF) pour le routage intelligent
- Multi-LLM (Ollama local + OpenRouter cloud)
- Kubernetes avec K3s
- GitHub Actions CI/CD
- FastAPI avec documentation automatique

**Valeur ajoutée :**
- Automatisation complète de la chaîne de valeur
- Patterns cloud-native modernes
- GitOps et Infrastructure as Code
- Monitoring et observabilité intégrés

*Documentation générée automatiquement - Septembre 2025*