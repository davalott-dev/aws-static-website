# AWS: Static Website Hosting

[![AWS](https://img.shields.io/badge/AWS-Cloud-orange)](https://aws.amazon.com/)
[![HTML5](https://img.shields.io/badge/HTML5-%23E34F26.svg?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-%231572B6.svg?logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)

---

## Project Overview
This is a **static website** that I built, hosted on **Amazon S3**, and delivered via **AWS CloudFront**.
The project demonstrates my ability to deploy a website using AWS services and manage basic cloud hosting configurations.

---

## Technologies Used
- **AWS S3** — static website hosting
- **AWS CloudFront** — content delivery network for global access
- **HTML & CSS** — front-end design

---

## What I Did
- Created an S3 bucket and uploaded the website files (`index.html` and `styles.css`).
- Enabled **static website hosting** on the bucket.
- Configured the **bucket policy** to allow CloudFront access.
- Set up a **CloudFront distribution**:
- Origin pointing to the S3 bucket
- Default root object: `index.html`
- Viewer protocol policy: HTTP → HTTPS
- Tested both the S3 website endpoint and CloudFront URL to confirm the site loads correctly.

---

## Result
The website is live and accessible globally via CloudFront:
https://dava-static-website.s3.us-east-1.amazonaws.com/index.html

It displays a clean landing page with my name, showing my ability to deploy a static website using AWS.


