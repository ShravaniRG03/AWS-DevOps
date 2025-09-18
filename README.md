# AWS-DevOps

This repository serves as a centralized location for documentation related to my DevOps projects. It includes guides, project overviews, and technical details for various tasks and automations. Check back for future updates and new project documentation!

---

### **1. AWS Continuous Deployment Pipeline**

This document outlines the process of building a continuous deployment pipeline using AWS CodePipeline to automatically deploy a static website game from a GitHub repository to an S3 bucket.

* **Project Goal:** To set up an automated CI/CD pipeline for a simple web game.
* **Technologies Used:**
    * **Version Control:** GitHub
    * **CI/CD:** AWS CodePipeline
    * **Storage:** AWS S3 (for static website hosting)
    * **Web Technologies:** HTML, CSS, JavaScript
* **Key Concepts:** The document covers the step-by-step configuration of CodePipeline, including connecting to a GitHub repository, skipping the build stage for a static site, and configuring the deploy stage to an S3 bucket. It also addresses the common `Access Denied` error and its solution, which involves setting the correct public read access policy on the S3 bucket.

---

### **2. Set Up a Web App - AWS & VS Code**

This project provides a guide on launching and setting up a web application on an EC2 instance, demonstrating foundational DevOps skills.

* **Project Goal:** To launch an EC2 instance, connect to it securely via VS Code, and generate a basic web application using Maven and Java.
* **Technologies Used:**
    * **Cloud Services:** AWS EC2
    * **Code Editor:** VS Code
    * **Build Tool:** Apache Maven
    * **Programming Language:** Java
* **Key Concepts:** The documentation explains the purpose of launching a virtual server in the cloud, the importance of key pairs for secure SSH access, and the role of Maven and Java in automating project setup and managing dependencies. It details the process of using the VS Code Remote - SSH extension to manage files and run commands on the EC2 instance remotely.
