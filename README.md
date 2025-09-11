Project I – Kubernetes WordPress Deployment on AWS

This project uses Kubernetes to deploy a WordPress website with a MySQL database on AWS.  
The infrastructure leverages EBS for persistent storage and Secrets & ConfigMaps for secure configuration.

---

🔧 Technologies Used
- Kubernetes (Deployments, Services, PVC, StorageClass, RBAC)
- AWS EBS & EFS
- WordPress & MySQL
- ConfigMaps & Secrets
- MongoDB & Mongo-Express (optional part)
- RBAC & ServiceAccounts

---

🚀 Project Structure
- deployment/ – WordPress & MySQL deployments  
- storage/ – PersistentVolumeClaims and StorageClasses  
- secrets/ – Secrets for database credentials  
- mongo/ – Optional MongoDB + Mongo Express setup

---

📦 How to Deploy
1. Apply all Kubernetes YAML files using:
   
   kubectl apply -f .
   
2. Wait for LoadBalancer IP, then access the WordPress site.
