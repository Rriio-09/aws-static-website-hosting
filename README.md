# 🚀 AWS Static Website Hosting using Amazon S3 & CloudFront

![AWS](https://img.shields.io/badge/AWS-S3%20%7C%20CloudFront-orange?logo=amazonaws)
![HTML](https://img.shields.io/badge/HTML-5-orange?logo=html5)
![CSS](https://img.shields.io/badge/CSS-3-blue?logo=css3)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6-yellow?logo=javascript)
![Status](https://img.shields.io/badge/Status-Completed-success)

## 📖 Project Overview

This project demonstrates how to deploy a **static website** on **Amazon Web Services (AWS)** using **Amazon S3** and **Amazon CloudFront**.

The website files were uploaded to an Amazon S3 bucket configured for static website hosting. Amazon CloudFront was then used as a Content Delivery Network (CDN) to improve website performance and provide secure global content delivery.

This project was completed as part of the **Udacity AWS Cloud Foundations** program.

---

## 🏗️ Architecture

```text
                User
                  │
                  ▼
      Amazon CloudFront (CDN)
                  │
                  ▼
 Amazon S3 Static Website Hosting
                  │
                  ▼
      HTML • CSS • JavaScript
```

---

## 🛠️ Technologies Used

- Amazon S3
- Amazon CloudFront
- HTML5
- CSS3
- JavaScript
- AWS Management Console

---

## 📂 Project Structure

```text
aws-static-website-hosting/
│
├── index.html
├── css/
├── img/
├── vendor/
├── screenshots/
└── README.md
```

---

## 📋 Project Workflow

- Created an Amazon S3 bucket
- Uploaded website files
- Disabled Block Public Access
- Configured Bucket Policy
- Enabled Static Website Hosting
- Configured `index.html` as the default document
- Created an Amazon CloudFront Distribution
- Connected CloudFront to the S3 Website Endpoint
- Successfully deployed the website

---

## 📸 Project Screenshots

### S3 Bucket

> Add your screenshot here

```
screenshots/s3-bucket.png
```

---

### Website Files Uploaded

> Add your screenshot here

```
screenshots/files-uploaded.png
```

---

### Static Website Hosting

> Add your screenshot here

```
screenshots/static-hosting.png
```

---

### Bucket Policy

> Add your screenshot here

```
screenshots/bucket-policy.png
```

---

### CloudFront Distribution

> Add your screenshot here

```
screenshots/cloudfront.png
```

---

### Website Output

> Add your screenshot here

```
screenshots/website-output.png
```

---

## 🎯 Learning Outcomes

Through this project I learned how to:

- Host static websites using Amazon S3
- Configure Static Website Hosting
- Configure Bucket Policies
- Manage Public Access settings
- Create and configure CloudFront Distributions
- Use AWS CDN services
- Troubleshoot deployment issues such as CloudFront 504 Gateway Timeout errors

---

## ⚠️ Note

This project was deployed using **AWS Academy lab resources**.

As required by the course, the Amazon S3 bucket and CloudFront distribution were deleted after successful project completion to avoid unnecessary cloud resource usage.

Therefore, the live website is no longer available.

The source code and deployment screenshots are preserved in this repository.

---

## 📚 Project Reference

This project was completed as part of the **Udacity AWS Cloud Foundations** course.

---

## 👩‍💻 Author

**Rehana Banu**

- B.Tech – Artificial Intelligence & Machine Learning
- Python Full Stack Learner
- AWS Cloud Foundations Learner

---

⭐ If you found this repository helpful, feel free to star it!
