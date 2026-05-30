# AWS Project 1 – Static Portfolio Website Hosting using Amazon S3

## Project Overview

This project demonstrates how to host a static website on Amazon S3 using AWS Static Website Hosting.

The website was developed using HTML and CSS, version-controlled using Git and GitHub, and deployed on AWS S3.

---

## Project Objectives

* Create a personal portfolio website.
* Learn Git and GitHub fundamentals.
* Deploy a static website using Amazon S3.
* Understand bucket policies and public access configuration.
* Gain hands-on AWS experience.

---

## Technologies Used

### Frontend

* HTML5
* CSS3

### Version Control

* Git
* GitHub

### AWS Services

* Amazon S3
* S3 Static Website Hosting

---

## Architecture

User Browser
↓
Amazon S3 Static Website Hosting
↓
HTML + CSS Files

---

## Project Folder Structure

AWS_Portfolio

├── index.html

├── styles.css

├── README.md

├── screenshots

└── project-documents

---

## Implementation Steps

### Step 1

Created portfolio website using HTML and CSS.

### Step 2

Tested the website locally using VS Code Live Server.

### Step 3

Initialized Git repository.

Commands used:

git init

git add .

git commit -m "Initial AWS Portfolio Website"

---

### Step 4

Created GitHub repository and pushed source code.

Commands used:

git remote add origin <repository-url>

git push -u origin main

---

### Step 5

Created Amazon S3 bucket.

---

### Step 6

Uploaded:

* index.html
* styles.css

---

### Step 7

Enabled Static Website Hosting.

Configuration:

Index Document:

index.html

---

### Step 8

Configured Bucket Policy for public access.

---

### Step 9

Verified website accessibility through S3 Website Endpoint.

---

## Challenges Faced

### CSS Not Loading

Issue:
CSS file was not linked correctly.

Resolution:
Verified file path and corrected stylesheet reference.

---

### Git Push Error

Issue:

error: src refspec main does not match any

Resolution:
Created initial commit and pushed code successfully.

---

### S3 Access Denied Error

Issue:

403 Access Denied

Resolution:
Configured bucket policy and enabled public access.

---

## Screenshots

Add screenshots here:

* Portfolio Homepage
* GitHub Repository
* S3 Bucket Created
* Files Uploaded
* Static Website Hosting Enabled
* Live Website

---

## Key Learnings

* Static website hosting on AWS
* Git and GitHub workflow
* Bucket policies and permissions
* S3 object storage
* Troubleshooting deployment issues

---

## Future Enhancements

* Add CloudFront CDN
* Add custom domain
* Add HTTPS support
* Make portfolio fully responsive
* Add project cards and architecture diagrams

---

## Outcome

Successfully developed and deployed a static portfolio website on AWS S3 and managed source code through GitHub.

This project provided practical experience in cloud deployment, source control, and AWS storage services.
