# 🚀 **Projet DevOps - Application Spring Backend avec Minikube, ArgoCD, Prometheus et Grafana**  

Bienvenue dans le projet backend basé sur **Spring Boot** ! Ce backend fait partie d'une application complète avec un frontend, un backend, et une base de données. Ce document explique comment configurer, construire, déployer, surveiller et orchestrer cette application avec des outils DevOps comme **Minikube**, **ArgoCD**, **Docker**, **Jenkins**, **Prometheus**, **Grafana**, et bien d'autres.

---

## **📋 Prérequis**  

Avant de commencer, assurez-vous d'avoir les outils suivants installés et configurés sur votre machine :  

- ☕ **Java JDK** (version 11 ou supérieure)  
- 🛠️ **Maven** (version 3.6 ou supérieure)  
- 🐳 **Docker** (version 20.x ou supérieure)  
- ⚙️ **Docker Compose**  
- 🧑‍💻 **Jenkins** (avec des pipelines configurés)  
- 🌐 **Ngrok** (pour les webhooks Jenkins)  
- 🔍 Accès à **SonarQube** et **Nexus** (avec vos identifiants)  
- 🖥️ **Minikube** (pour la création d'un cluster Kubernetes local)  
- 🌲 **ArgoCD** (pour l'orchestration et la gestion des déploiements Kubernetes via CI/CD)  
- 📊 **Prometheus** et **Grafana** pour la surveillance de Jenkins et de l'application Spring.  

---

## **📂 Étapes pour exécuter le projet**

### 1️⃣ **Cloner le projet**  
Clonez le repository backend depuis GitHub :  

```bash
git clone -b oumaima https://github.com/oumaimakhlifi/projet-DevOps.git
cd projet-DevOps
