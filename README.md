# 🚀 Docker Monitoring Stack – Prometheus + Grafana + Node Exporter + cAdvisor

Cette stack vous permet de monitorer facilement vos ressources système et conteneurs Docker avec Prometheus, Grafana, Node Exporter et cAdvisor.

---

## 📦 Services inclus

- **Prometheus** : collecte des métriques de vos systèmes et conteneurs.
- **Grafana** : visualisation des métriques Prometheus avec de superbes dashboards.
- **Node Exporter** : expose les métriques de la machine hôte (CPU, mémoire, etc.).
- **cAdvisor** : exporte les métriques des conteneurs Docker.

---

## 🧰 Démarrage rapide

```bash
git clone https://github.com/votre-repo/monitoring-stack.git
cd monitoring-stack
docker-compose up -d
