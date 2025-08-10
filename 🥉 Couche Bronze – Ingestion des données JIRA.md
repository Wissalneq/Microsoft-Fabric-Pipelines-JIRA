## 📋 Objectif
La **couche Bronze** contient les **données brutes** extraites depuis l’API REST de JIRA, sans transformation majeure, afin de préserver l’intégrité des données sources.

---

## 📤 Sources de données
- **API REST JIRA** :
  - Extraction des données via endpoints `/rest/api/2/issue`, `/rest/api/2/component`, `/rest/api/2/backlog`
  - Authentification par clé API
  - Récupération au format JSON

---

