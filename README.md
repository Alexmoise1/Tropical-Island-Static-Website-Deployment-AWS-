🌴 Tropical Island Restaurant – AWS Static Website Deployment

This project demonstrates how I deployed a fully functional static website using Amazon S3 and Amazon CloudFront under the AWS Free Tier. The website showcases a restaurant concept called Tropical Island, and the deployment process reflects real-world cloud engineering practices, including hosting configuration, CDN distribution, and secure HTTPS delivery.

🚀 Project Overview

This project walks through the complete process of deploying a static website using AWS services. It includes:

Setting up an Amazon S3 bucket for public static website hosting

Uploading HTML, images, and assets

Applying a bucket policy for public read access

Enabling static hosting in S3

Deploying a CloudFront distribution to serve the website globally with HTTPS

Configuring CloudFront to use the correct S3 website endpoint

Setting index.html as the default root object

Performing invalidations to refresh the CloudFront cache

The result is a fully deployed, publicly accessible restaurant website with professional-grade architecture.


🌐 Live Website URL (CloudFront)

👉 https://d2clyxacvq8ee5.cloudfront.net

(Served securely with AWS CloudFront)

📁 Project Structure
tropical-island-website/
│── index.html
│── tropical-island-logo.png
│── images/
│── assets/
│── README.md

🛠 AWS Services Used
Amazon S3

Hosts the static website

Stores HTML, images, CSS, and assets

Static website hosting enabled

Bucket website endpoint configured

Amazon CloudFront

Acts as a global CDN

Provides HTTPS encryption by default

Uses S3 website endpoint as the origin

Configured with “Redirect HTTP to HTTPS”

Default root object: index.html

AWS IAM Policies

Public Read policy for S3 (GetObject)

Secure access configuration

📘 Skills Demonstrated

✔ Cloud Architecture

Understanding how S3 + CloudFront work together to host static sites via global CDN.

✔ Static Website Hosting

Configuring S3 for public access and static hosting.

✔ CDN Optimization

Using CloudFront to improve global performance, caching, and security.

✔ Security + Permissions

Applying correct bucket policies, handling public access, and configuring HTTPS.

✔ Debugging Cloud Deployments

Resolved issues such as:

404 Not Found (root object missing)

Origin misconfiguration

Cache invalidation

Using the correct S3 website endpoint (not the API endpoint)

✔ Version Control & GitHub Documentation

Organizing files, writing a professional README, and publishing the project.
