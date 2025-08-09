
# Prometheus and Grafana Monitoring Setup to monitor system and website metrics

This project shows the steps to set up **Prometheus** for monitoring and **Grafana** for visualization.

---

## 🛠️ Prometheus Setup

1. Installed Prometheus.
2. Installed and configured **Node Exporter** to collect system-level metrics (CPU, memory, disk, etc.) on the target machines.
3. Installed and configured **Blackbox Exporter** to monitor website and service availability by probing endpoints.
4. Configured Prometheus `prometheus.yml` to scrape metrics from targets.
5. Verified Prometheus is running on port `9090`.

Screenshot of Prometheus dashboard:

<img width="1907" height="977" alt="prometheus_monitor" src="https://github.com/user-attachments/assets/3dc67ce1-0e5b-4af6-a04f-814195058d49" />

---

## 📊 Grafana Setup

1. Installed Grafana.  
2. Added Prometheus as a data source in Grafana.
3. Imported and customized dynamic, full-featured dashboards to visualize system and website metrics effectively.
4. Created dashboards for CPU, memory, disk usage, network stats (via Node Exporter), and HTTP probe results (via Blackbox Exporter). 


Screenshot of Grafana dashboard for Node exporter:

<img width="1916" height="982" alt="Grafana_node_exporter" src="https://github.com/user-attachments/assets/d8cf8501-8a84-42a9-963c-4e79401cbe6d" />

Screenshot of Grafana dashboard for Blackbox exporter:

<img width="1915" height="980" alt="blackbox_github_grafana" src="https://github.com/user-attachments/assets/9e4430bb-adbf-4377-8a70-837517f17920" />

<br>

<img width="1916" height="988" alt="blackbox_grafana" src="https://github.com/user-attachments/assets/91000598-2346-45ca-9b75-353e52dc35fd" />

---

## Access Prometheus UI
http://localhost:9090

## Access Grafana UI
http://localhost:3000



---
⚠️ Notes

Ensure ports 9100 (Node Exporter), 9115 (Blackbox Exporter), 9090 (Prometheus), and 3000 (Grafana) are accessible.
