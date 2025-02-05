![CI Pipeline](https://github.com/SalmanShamsKhan/DevOps-CI-jenkins/blob/main/Continuous%20Integration%20Using%20Jenkins,Nexus,Sonarqube&%20Slack.png)


# Continuous Integration (CI) Pipeline using Jenkins, Nexus, SonarQube & Slack Integration

## 📌 Project Overview
This project sets up a **Continuous Integration (CI) pipeline** using **Jenkins**, **Nexus Repository**, **SonarQube**, and **Slack notifications** to streamline the software development lifecycle (SDLC). The objective is to automate code compilation, security scanning, unit testing, and artifact management, ensuring high-quality code deployment.

## 🏗️ Project Architecture
The CI pipeline consists of the following components:
- **Developers** push code to a **GitHub repository**.
- **Jenkins** fetches the source code and triggers a build process.
- **SonarQube** performs **static code analysis** and ensures code quality.
- **Nexus Repository** stores versioned build artifacts for future deployments.
- **Slack Webhook** provides real-time notifications to the development team.

The entire pipeline runs on **AWS EC2 instances**, leveraging security groups, IAM roles, and automation scripts.

---

## 🔄 Project Workflow
### ✅ **Infrastructure Setup on AWS**
- Launch AWS **EC2 instances** for Jenkins, Nexus, and SonarQube.
- Configure **Security Groups** for secure access to services.
- Use **User Data scripts** for automated instance configuration.

### ✅ **Jenkins Installation & Configuration**
- Install Jenkins and configure plugins.
- Set up **Jenkins Pipeline** for automated CI.

### ✅ **Nexus Repository Setup**
- Install and configure **Nexus Artifact Repository** for storing build artifacts.
- Secure repository access with credentials.

### ✅ **SonarQube Integration**
- Install **SonarQube** for **static code analysis**.
- Connect Jenkins with SonarQube for automated **code quality checks**.

### ✅ **GitHub Webhook Integration**
- Set up **GitHub Webhook** to trigger Jenkins builds on code commits.

### ✅ **Jenkins Pipeline Execution**
- Fetches the latest source code from GitHub.
- Runs **Maven or Gradle build** commands.
- **Performs unit testing** using JUnit.
- Scans code quality via **SonarQube**.
- Pushes built artifacts to **Nexus Repository**.

### ✅ **Slack Notifications**
- Configure **Slack Webhook** in Jenkins.
- Send notifications for **successful or failed builds**.

---

## ⚙️ Technology Stack
- **CI/CD Tool**: Jenkins
- **Artifact Repository**: Nexus
- **Static Code Analysis**: SonarQube
- **Source Code Management**: GitHub
- **Infrastructure**: AWS (EC2, IAM, Security Groups)
- **Notifications**: Slack Webhook
- **Build Tool**: Maven/Gradle
- **Scripting**: Shell & Groovy

---

## 🎯 Benefits of this Project
✔ **Automated Build Process** - No manual intervention needed for building and testing.  
✔ **Code Quality Assurance** - SonarQube ensures clean, optimized, and secure code.  
✔ **Centralized Artifact Storage** - Nexus maintains version-controlled builds.  
✔ **Real-time Notifications** - Slack alerts keep teams informed about build status.  
✔ **Improved Collaboration** - GitHub Webhook triggers immediate feedback loops.

---

## 🚀 Conclusion
This project successfully implements a **CI pipeline** to enhance **developer productivity** and **code quality**. With **automated builds, testing, and notifications**, teams can deliver **error-free, production-ready software** in a streamlined manner.

# Prerequisites
#
- JDK 17 or 21
- Maven 3.9
- MySQL 8

# Technologies 
- Spring MVC
- Spring Security
- Spring Data JPA
- Maven
- JSP
- Tomcat
- MySQL
- Memcached
- Rabbitmq
- ElasticSearch
# Database
Here,we used Mysql DB 
sql dump file:
- /src/main/resources/db_backup.sql
- db_backup.sql file is a mysql dump file.we have to import this dump to mysql db server
- > mysql -u <user_name> -p accounts < db_backup.sql


