

# End-to-End CI/CD Pipeline using Jenkins, Docker & AWS EC2

📌 Overview

“This project simulates a production-level CI/CD pipeline used in real-world DevOps environments.”
This project demonstrates the design and implementation of a complete CI/CD pipeline to automate application deployment using Jenkins, Docker, and AWS EC2.
The pipeline automates the process from source code integration to application deployment, reducing manual effort and ensuring consistent and reliable releases.



🎯 Objectives

* Automate application deployment
* Implement Continuous Integration and Continuous Deployment (CI/CD)
* Use Docker for containerization
* Deploy application on AWS EC2
* Improve deployment speed and reliability



Technologies Used

* AWS EC2 (Ubuntu)
* Jenkins
* Docker
* GitHub
* Node.js
* Linux



⚙️ Architecture


GitHub → Jenkins → Docker → AWS EC2 → Browser




🔄 CI/CD Pipeline Workflow

#1️⃣ Clone Stage

* Jenkins fetches source code from GitHub repository

#2️⃣ Build Stage

* Docker image is built using the application's Dockerfile

#3️⃣ Run Stage

* Docker container is created and deployed
* Application is exposed on port 3000



 📂 Project Structure


ci-cd-project
│
├── README.md
├── Jenkinsfile
├── Dockerfile
├── 
│
├── app/
│   ├── 
│   ├── 
│
├── screenshots
│   ├── .png
│   ├── .png
│   ├── .png
│




🔐 Best Practices Followed

* Automated deployment using CI/CD
* Containerized application using Docker
* Secure access using AWS Security Groups
* Separation of build and deployment stages






## 📈 Future Improvements

* Push Docker image to DockerHub
* Add CI/CD using GitHub Actions
* Implement auto-scaling
* Add monitoring tools



👩‍💻 Author

Pranali Bhandare



⭐ Conclusion

This project demonstrates a real-world CI/CD pipeline that automates application deployment from source code to production using industry-standard DevOps tools.





 
