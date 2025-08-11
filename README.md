# Flask DevOps Demo  
Цель: CI/CD пайплайн с Docker, Terraform и Kubernetes.  
## 🛠️ Стек:  
- Python (Flask)  
- Docker + GitHub Actions  
- Terraform 
- Kubernete
- Prometheus + Grafana  
## 🚀 Запуск:  
1. Собрать Docker: `docker build -t my-flask-app .`  
2. Развернуть инфраструктуру: `terraform apply`  
3. Деплой: `kubectl apply -f kubernetes/`  
