# 🦄 WildRydes: A Serverless Ride Booking Application 

Traditional ride-booking applications rely on servers, making them **costly to maintain, complex to scale, and harder to secure**.  

**WildRydes** is a **serverless ride-booking application** built on **AWS Cloud**, designed to solve these challenges.  
Inspired by the AWS educational project, this implementation demonstrates how to design, deploy, and scale modern **cloud-native applications** without managing servers.


---

## 🚀 Features :

- **Frontend Hosting** with AWS Amplify (CI/CD + Global CDN)
- **User Authentication** via Amazon Cognito
- **API Management** using Amazon API Gateway
- **Business Logic** with AWS Lambda
- **Database** using Amazon DynamoDB
- **Monitoring & Logging** via Amazon CloudWatch
- **Secure Access Control** through AWS IAM
- Fully **scalable**, **cost-efficient**, and **serverless**

---

## 🛠️ Tech Stack :

- **Frontend** → HTML, CSS, JavaScript (hosted on Amplify)  
- **Authentication** → Amazon Cognito  
- **API** → Amazon API Gateway  
- **Backend** → AWS Lambda (Node.js/Python)  
- **Database** → Amazon DynamoDB (NoSQL)  
- **Monitoring** → Amazon CloudWatch  
- **Security** → AWS IAM  

---

## 📐 System Architecture :

![WhatsApp Image 2025-09-24 at 21 38 23_8edcf3f7](https://github.com/user-attachments/assets/4efc16e4-16ea-4936-ac35-b18daf07a6aa)

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

---

## 📊 Results

-  Fully serverless application with no server management  
-  Secure user authentication using Cognito  
-  Scalable backend with Lambda functions  
-  Fast & reliable data handling via DynamoDB  
-  Real-time monitoring and debugging with CloudWatch  

---

## 🖼️ Screenshots:


- Home Screen :
      <img width="975" height="490" alt="image" src="https://github.com/user-attachments/assets/a4d6409e-852c-497c-8500-e24b664915dc" />
 
- Login / Signup Screen :
    <img width="975" height="483" alt="image" src="https://github.com/user-attachments/assets/aff2e8a1-36f8-4931-84b2-3ad27cbe0a76" />

- DynamoDB Ride Entries :
    <img width="975" height="469" alt="image" src="https://github.com/user-attachments/assets/a048ff6d-4986-43c5-83ff-f963098aaf92" />

- API Gateway :
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

- Location-based ride matching (Amazon Location Service)  
- Payment gateway integration (Stripe/PayPal)  
- Real-time notifications (SNS/SQS)  
- Analytics dashboards (QuickSight)  
- Mobile app support (Flutter/React Native)  
- Advanced security (MFA, WAF, encryption)  
- Multi-region deployment with CloudFront  

