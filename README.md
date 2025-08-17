# 🚀 DevOps CI/CD Project with AWS EKS, Jenkins, Docker & Maven  

✨ Successfully Completed My DevOps Project Setup & Deployment! ✨  

In this project, I built a **complete CI/CD pipeline** and deployed a web application on **AWS EKS (Elastic Kubernetes Service)** using **Maven, GitHub, Jenkins, Docker, and Kubernetes**.  

This was an amazing hands-on journey covering **automation, containerization, orchestration, and cloud-native deployment** 🚀  

---

## 🔧 Project Setup  

### Tools Used  
- ✅ Maven  
- ✅ GitHub  
- ✅ Jenkins  
- ✅ Docker  
- ✅ Kubernetes (EKS)  

---

## 📌 Step-by-Step Implementation  

### Step 1: Created 2 EC2 Instances  
- 🔹 Jenkins Server  
- 🔹 EKS Management Host  

### Step 2: Jenkins Server Setup  
- 🔹 Installed Jenkins  
- 🔹 Configured Maven as Global Tool  
- 🔹 Installed & Integrated Docker with Jenkins  

### Step 3: AWS Setup  
- 🔹 Created IAM roles for Jenkins & EKS Host  
- 🔹 Provisioned EKS Cluster using `eksctl`  

### Step 4: Jenkins Configurations  
- 🔹 Installed AWS CLI & kubectl on Jenkins Server  
- 🔹 Updated kubeconfig file for EKS cluster  

### Step 5: Jenkins CI/CD Pipeline  
1. Clone GitHub Repository  
2. Maven Build  
3. Build Docker Image  
4. Push Docker Image to Registry  
5. Deploy Application on Kubernetes (EKS)  

---

## 🌐 Application Deployment  

- Created a **Kubernetes LoadBalancer Service**  
- AWS automatically provisioned an **Elastic Load Balancer (ELB)**  
- Accessed the application through the **LoadBalancer DNS URL** 🎉  

👉 Example:  
http://af1d10c6c28644955968e5d31bec44ea-694572455.us-east-1.elb.amazonaws.com
<img width="1920" height="1080" alt="Screenshot (814)" src="https://github.com/user-attachments/assets/3130be34-631c-4cd6-981f-9be3a77c8579" />

<img width="1920" height="1080" alt="Screenshot (827)" src="https://github.com/user-attachments/assets/a6a77342-63d7-48a8-8e57-d888956aa672" />

<img width="1920" height="1080" alt="Screenshot (822)" src="https://github.com/user-attachments/assets/669e83c8-944c-475d-b215-7fee51f3c6f6" />

<img width="1920" height="1080" alt="devops-2" src="https://github.com/user-attachments/assets/522c3996-6e6b-477a-957b-63b40c5f39a0" />

<img width="1920" height="1080" alt="devops-1" src="https://github.com/user-attachments/assets/524f5f74-9a50-4719-8942-91413ea86bca" />


