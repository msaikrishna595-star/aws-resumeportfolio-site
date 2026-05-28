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
![Live Site](site-screenshot.png)

## AWS Console
![CloudFront Setup](cloudfront-screenshot.png)
