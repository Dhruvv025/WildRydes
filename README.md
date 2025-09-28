# 🦄 WildRydes: A Serverless Ride Booking Application 

Traditional ride-booking applications rely on servers, making them **costly to maintain, complex to scale, and harder to secure**.  

**WildRydes** is a **serverless ride-booking application** built on **AWS Cloud**, designed to solve these challenges.  
Inspired by the AWS educational project, this implementation demonstrates how to design, deploy, and scale modern **cloud-native applications** without managing servers.


---

## 🚀 Features :

- 🌍 **Frontend Hosting** with AWS Amplify (CI/CD + Global CDN)  
- 🔐 **User Authentication** via Amazon Cognito  
- 🌐 **API Management** using Amazon API Gateway  
- ⚡ **Business Logic** with AWS Lambda  
- 🗄️ **Database** using Amazon DynamoDB  
- 📊 **Monitoring & Logging** via Amazon CloudWatch  
- 🛡️ **Secure Access Control** through AWS IAM  
- 📈 Fully **scalable**, **cost-efficient**, and **serverless**

---

## 🛠️ Tech Stack :

- 🎨 **Frontend** → HTML, CSS, JavaScript ![Amplify](https://img.shields.io/badge/AWS-Amplify-orange?logo=awsamplify)  
- 🔐 **Authentication** → Amazon Cognito ![Cognito](https://img.shields.io/badge/AWS-Cognito-FF4F8B?logo=amazoncognito)  
- 🌐 **API** → Amazon API Gateway ![API Gateway](https://img.shields.io/badge/AWS-API%20Gateway-FF9900?logo=amazonapigateway)  
- ⚡ **Backend** → AWS Lambda (Node.js/Python) ![Lambda](https://img.shields.io/badge/AWS-Lambda-orange?logo=awslambda)  
- 🗄️ **Database** → Amazon DynamoDB (NoSQL) ![DynamoDB](https://img.shields.io/badge/AWS-DynamoDB-4053D6?logo=amazondynamodb)  
- 📊 **Monitoring** → Amazon CloudWatch ![CloudWatch](https://img.shields.io/badge/AWS-CloudWatch-FF4F8B?logo=amazoncloudwatch)  
- 🛡️ **Security** → AWS IAM ![IAM](https://img.shields.io/badge/AWS-IAM-232F3E?logo=amazonaws)  
 

---

## 📐 System Architecture :

![WhatsApp Image 2025-09-24 at 21 38 23_8edcf3f7](https://github.com/user-attachments/assets/4efc16e4-16ea-4936-ac35-b18daf07a6aa)

**Architecture Flow**:
1. 🌍 **Frontend (Amplify)** → Static website hosted globally with CI/CD.  
2. 🔐 **Authentication (Cognito)** → Manages user sign-up, login, and tokens.  
3. 🌐 **API Gateway** → Handles RESTful requests from the frontend.  
4. ⚡ **Lambda Functions** → Business logic (ride requests, unicorn assignment).  
5. 🗄️ **DynamoDB** → Stores ride details (UserID, Pickup, Drop, Status).  
6. 📊 **CloudWatch** → Logging & monitoring for performance and debugging.  
7. 🛡️ **IAM** → Secure role-based access control for all resources.  
---

## ⚙️ Implementation Steps :

1. **Frontend Deployment**  
   - Build static site using HTML, CSS, JS  
   - Deploy on AWS Amplify (connected to GitHub for CI/CD)
     
     <img width="624" height="169" alt="image" src="https://github.com/user-attachments/assets/259a526f-ea6e-4dab-8760-6d0793b07dc0" />


2. **Authentication**  
   - Setup Cognito User Pools for signup/sign-in  
   - Integrate Cognito tokens for API authorization
     
    <img width="624" height="348" alt="image" src="https://github.com/user-attachments/assets/b3894306-476e-4fa5-a869-a3c09922ed6d" />


3. **API Development**  
   - Create RESTful endpoints in API Gateway  
   - Secure endpoints with Cognito Authorizers
     

4. **Backend Logic**  
   - Implement AWS Lambda functions for ride requests, unicorn assignment, and data validation
     
     <img width="624" height="108" alt="image" src="https://github.com/user-attachments/assets/d01b765d-e8f9-4631-a7d4-cc95d791933d" />


5. **Database Configuration**  
   - Create DynamoDB table to store ride data (UserID, Pickup, Drop, Status)
     
     <img width="624" height="285" alt="image" src="https://github.com/user-attachments/assets/c77d85d0-3e7d-423d-af62-7cab8857c2ae" />


6. **Monitoring & Security**  
   - Enable CloudWatch for logs & dashboards  
   - Configure IAM policies (principle of least privilege)  

7. **Deployment**  
   - Final hosting on AWS Amplify with GitHub CI/CD  
   - Application accessible globally via Amplify domain  
   - Test end-to-end ride booking workflow
     
---

## 📊 Results

| Feature | Outcome |
|---------|---------|
| 🔐 Authentication | Secure sign-up/login using Cognito |
| ⚡ Backend | Scalable business logic with Lambda functions |
| 🗄️ Data Storage | Fast & reliable NoSQL data handling via DynamoDB |
| 📊 Monitoring | Real-time logging and dashboards with CloudWatch |
| 🌍 Serverless | Fully serverless application, no server management needed |

---

## 🖼️ Screenshots:


**Home Screen** – Users can see available unicorn rides
      <img width="975" height="490" alt="image" src="https://github.com/user-attachments/assets/a4d6409e-852c-497c-8500-e24b664915dc" />
 
  **Login / Signup Screen** – Secure authentication with Cognito
    <img width="975" height="483" alt="image" src="https://github.com/user-attachments/assets/aff2e8a1-36f8-4931-84b2-3ad27cbe0a76" />

  **DynamoDB Ride Entries** – Stores all ride data with status
    <img width="975" height="469" alt="image" src="https://github.com/user-attachments/assets/a048ff6d-4986-43c5-83ff-f963098aaf92" />

  **API Gateway** – RESTful endpoints for ride management
      <img width="975" height="465" alt="image" src="https://github.com/user-attachments/assets/23bdeb19-62e0-4b94-bc8d-1ccff35e3270" />
 
 
- Entire Website :  
   [![GitHub](https://img.shields.io/badge/View%20Website-181717?logo=github&logoColor=white)](https://drive.google.com/file/d/1v_qDdYTgFkvDeopQlrGwJH4s1VyJ6SyP/view?usp=sharing)

- Video :  
  [![Watch Video](https://img.shields.io/badge/Watch-Video-red?logo=youtube&logoColor=white)](https://drive.google.com/file/d/1iT7Najuux7olpx9Oz3OXy9w1nO_yQ7mq/view?usp=sharing)

  
---

## ⚡ Challenges Faced

- Integrating Cognito authentication with frontend  
- Configuring IAM roles with least privilege  
- Debugging Lambda functions via CloudWatch logs  
- Designing efficient NoSQL schema for DynamoDB  

---

## 🔮 Future Enhancements

**Scalability & Performance**  
- Multi-region deployment with CloudFront  
- Location-based ride matching (Amazon Location Service)  

**User Experience**  
- Mobile app support (Flutter/React Native)  
- Real-time notifications (SNS/SQS)  

**Security & Payments**  
- Advanced security (MFA, WAF, encryption)  
- Payment gateway integration (Stripe/PayPal)  

**Analytics & Insights**  
- Analytics dashboards with Amazon QuickSight

