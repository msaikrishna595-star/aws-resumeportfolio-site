# aws-resumeportfolio-site
Learning cloud engineering by building real projects on AWS. This is my first project — a portfolio site hosted on S3 and served through CloudFront.

# Portfolio Site — AWS S3 + CloudFront

🔗 Live URL: https://d2wdsjs7efqq8s.cloudfront.net

## What I Built
A personal portfolio website designed in Google AI Studio, 
exported as static HTML, and deployed on AWS infrastructure.

## Architecture
Browser → CloudFront (CDN + HTTPS) → S3 (private bucket)

## AWS Services Used
- **S3** — stores and hosts the static HTML/CSS files
- **CloudFront** — CDN that serves the site globally over HTTPS
- **IAM** — created admin user with least-privilege access, 
  root account secured with MFA

## What I Learned
- How to host a static website on S3
- Why CloudFront is used in front of S3 (CDN + security)
- How HTTPS works with SSL certificates
- Why S3 public access should be blocked when using CloudFront
- IAM best practices — never use root for daily work

## Live Site
![Live Site](https://github.com/msaikrishna595-star/aws-resumeportfolio-site/blob/c2a413b565f071ae0963ca0a7ebb36a82590a848/Screenshot%202026-05-28%20162054.png)

## AWS Console
![CloudFront Setup](https://github.com/msaikrishna595-star/aws-resumeportfolio-site/blob/ae6496fd7bfd6a0034e96d7cb3c75bac8a3855bc/Screenshot%202026-05-28%20162907.png)
