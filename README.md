# Jenkins CI/CD Pipeline — Maven + Nexus + Tomcat  
This project demonstrates a complete CI/CD pipeline using:

- **Jenkins**
- **Maven**
- **Nexus Repository (Artifact Upload)**
- **Tomcat 9 (Deployment)**
- **GitHub (Source Code)**

---

## 🚀 Pipeline Overview

### **1. Code Checkout**
Pulls source code from GitHub:
https://github.com/sivam792/one.git

powershell
Copy code

### **2. Build**
Builds the project using Maven:
mvn clean package

yaml
Copy code

### **3. Artifact Upload (Nexus)**
Uploads the generated `.war` file to a Nexus Repository.

### **4. Deploy to Tomcat**
Deploys the WAR file to a remote Tomcat server using Jenkins Deploy Plugin.

---

## 🧩 Jenkins Pipeline Stages

```mermaid
flowchart LR
A[Git Checkout] --> B[Maven Build]
B --> C[Nexus Upload]
C --> D[Tomcat Deployment]
 Tools Used
Jenkins

Maven

Nexus3

Tomcat9

GitHub

Groovy DSL (Pipeline)

📂 Jenkinsfile Included
The repository contains a full Jenkinsfile that:

✔ Checks out code
✔ Builds with Maven
✔ Uploads WAR to Nexus
✔ Deploys to Tomcat

⭐ Good for DevOps Practice
This is perfect for:

DevOps learning

Mini-projects

GitHub portfolio

LinkedIn posts

Interview preparation







