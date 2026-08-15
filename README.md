# Static-Website-Hosting-using-Amazon-S3
Static website hosted using Amazon S3 with hands-on experience in AWS cloud storage, website deployment, bucket configuration, and permissions.
# Project Overview
This project demonstrates how to host a static website using Amazon S3(Simple Storage Service). The website files were uploaded permissions were applied to make the website accessible through the web.
# Objectives
- Learn the fundamentals of Amazon S3
- Create and configure an S3 bucket
- Upload static website files to S3
- Enable static website hosting
- Configure bucket permissions
- Deploy a website using AWS
- Understand basic cloud deployment concept
# Technologies Used
- Amazon Web Services(AWS)
- Amazon S3
- HTML
- CSS
- Web Browser
# Project Architecture
User --> Web Browser --> S3 Bucket --> Website Files --> Hosted Website --> User
Components:
- user: Requests the website.
- Web Browser: Sends the request to the static website file.
- Amazon S3: Stores and serves the static website files.
- index.html: Main webpage.
- style.css: Website styling.
- S3 Website Hosting: Makes the static website accessible over the web.
# Implementation Steps
## 1. Create an S3 Bucket
Created an S3 bucket from the AWS Management Console. The bucket was configured for storing the static website files.
## 2. Upload Website Files
Upload the required website files to the S3 bucket:
- index.html
- style.css
- Other required static files
## 3. Enable Static Website Hosting
Enable the Static Website Hosting option in the S3 bucket properties.
configured:
Index Document: index.html
## 4. Configured Permissions
Configured the required bucket permissions/policy to allow visitors to access the website file.
## 5. Access the Website
Used the S3 website endpoint to open the hosted website in a web browser.
# Project Screenshots
## 1. S3 Bucket Created
<img width="1917" height="1017" alt="S3 Bucket" src="https://github.com/user-attachments/assets/77408460-5d51-446c-a880-aa2cac7984ca" />

## 2. Website File Uploaded
<img width="1917" height="1016" alt="Objects" src="https://github.com/user-attachments/assets/31a1d09b-303c-47b0-81e7-96fa77f99772" />

## 3. Static Website Hosting Configuration
<img width="1917" height="1016" alt="Static webhosting enable" src="https://github.com/user-attachments/assets/707f3cd9-5f8c-4353-8f18-1d37328377aa" />

## 4. Bucket Policy 
<img width="1916" height="1015" alt="Bucket Policy" src="https://github.com/user-attachments/assets/91c8d52d-d228-4e7d-a01e-5f1bb261daa0" />

## 5. Live Website
<img width="1917" height="1077" alt="Website Output" src="https://github.com/user-attachments/assets/1acb7887-63ce-4389-9473-7dbcfbffe20a" />
