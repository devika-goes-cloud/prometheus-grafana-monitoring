
# Prometheus and Grafana Monitoring Setup

This project shows the steps to set up **Prometheus** for monitoring and **Grafana** for visualization.

---

## 🛠️ Prometheus Setup

1. Installed Prometheus using Docker / Kubernetes / manual setup (whichever you used).  
2. Configured Prometheus `prometheus.yml` to scrape metrics from targets.  
3. Verified Prometheus is running on port `9090`.

Screenshot of Prometheus dashboard:


---

## 📊 Grafana Setup

1. Installed Grafana (Docker/Kubernetes/manual).  
2. Added Prometheus as a data source in Grafana.  
3. Created dashboards to visualize metrics.

Screenshot of Grafana dashboard:



---

## 🔧 Useful Commands

```bash
# Start Prometheus container
docker run -d -p 9090:9090 prom/prometheus

# Start Grafana container
docker run -d -p 3000:3000 grafana/grafana
