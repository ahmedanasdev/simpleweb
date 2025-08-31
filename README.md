# 🚀 SimpleWeb - CI/CD on AWS Elastic Beanstalk

This project is a **simple web application** deployed using **AWS Elastic Beanstalk** with a **CI/CD pipeline powered by GitHub Actions**.  

---

## 📌 Features
- ✅ Containerized app with **Docker**  
- ✅ Automated build & test using **GitHub Actions**  
- ✅ Deployment to **AWS Elastic Beanstalk**  
- ✅ Versioned releases with commit SHA  

---

## 🛠️ Tech Stack
- **Language/Runtime**: Node.js  
- **Containerization**: Docker  
- **CI/CD**: GitHub Actions  
- **Hosting**: AWS Elastic Beanstalk  

---

## ⚙️ CI/CD Workflow
The pipeline runs on every push to `main`:

1. **Build Stage**
   - Install dependencies
   - Run tests
   - Build Docker image
   - Run container for testing

2. **Deploy Stage**
   - Create deployment package
   - Deploy to Elastic Beanstalk (`simpleweb` → `Simpleweb-env`)

---

## 📂 Project Structure
.
├── .github/workflows/cicd.yml # CI/CD pipeline
├── Dockerfile # Docker build file
├── app/ # Source code
├── package.json # Node.js dependencies
└── README.md


🔑 Secrets

Make sure you configure the following secrets in your GitHub repo:
AWS_ACCESS_KEY_ID
AWS_SECRET_ACCESS_KEY

<img width="816" height="219" alt="image" src="https://github.com/user-attachments/assets/a11c3f74-6f96-4237-9128-5f60a27ce5ff" />
<img width="1883" height="867" alt="image" src="https://github.com/user-attachments/assets/bfa73c73-2a0d-468d-bb54-5ee9a9283d9d" />
<img width="1859" height="957" alt="image" src="https://github.com/user-attachments/assets/f23ee1d2-c4dd-473f-ba99-127a4f184614" />


