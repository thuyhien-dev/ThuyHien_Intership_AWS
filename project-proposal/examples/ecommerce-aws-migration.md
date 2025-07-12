# Project Proposal Example

**Project Title:** Hotel Management System on AWS

**Objective:**  
Build a cloud-native hotel management platform that enables small and medium-sized hotels to streamline operations, improve customer experience, and scale easily. The system should support room management, customer booking, authentication, reporting, and optional integration with payment gateways, all deployed using AWS services.

**Technologies Used:**

- **Frontend:** ReactJS + Chakra UI (SPA, responsive UI)
- **Backend:** NodeJS + AWS Lambda (serverless)
- **Database:** Amazon DynamoDB (NoSQL, scalable)
- **Authentication:** AWS Cognito (OTP, roles, session management)
- **Storage & Delivery:** Amazon S3 (images) + CloudFront (CDN)
- **Monitoring:** AWS CloudWatch
- **CI/CD:** GitHub + AWS CodePipeline

**Features:**

- User registration, login, password reset, OTP verification
- Room and service management with image uploads
- Booking and checkout tracking with real-time status
- Revenue reports by room type, status, and month
- Mobile-friendly UI, customizable themes
- Admin/staff/user roles and permission system

**Timeline:**

- **Week 1:** Requirement analysis & architecture design
- **Week 2-3:** Frontend development + authentication integration
- **Week 4:** Backend logic (CRUD, booking, image upload, DynamoDB)
- **Week 5:** Testing (unit, integration, performance)
- **Week 6:** Deployment to AWS (S3, CloudFront, CI/CD), UAT

**System Architecture:**  
A full cloud-native stack: SPA frontend → AWS Lambda backend → DynamoDB + S3 storage → Cognito for auth → CloudFront for performance → CloudWatch for logs → Optional OTA integrations in future.

**Expected Outcome:**

- Fully functional hotel management app on AWS with secure login, room control, and reporting features
- Minimal monthly cost (< $10 with AWS Free Tier)
- Potential to extend into a SaaS product
- 99.5% uptime, <500ms response time, scalable infrastructure

**Team:**  
1 Developer (student intern) with mentor support  
Project supervised by Mr. Văn Hoàng Kha
