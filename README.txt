1) Short Bio:

Intro: As a AWS DevOps Engineer designing CI/CD pipelines for applications or web applications and prividing the infrusructure via AWS IaC.

Skills: AWS (EC2, EKS, ECS, Lambda, IAM, VPC, CloudWatch, S3), Terraform, CloudFormation, GitHub Actions/CodePipeline, Docker, Linux, Python/Bash.

Experience: Desining CI/CD pipelines via Infra-as-Code(IaC) and combining apps with API integration

Certifications: AWS Technical Essentials Certificate

2) Projects:

A CI/CD pipeline that automates PR testing, Docker image builds and pushes to GHCR, automatic staging deployments, and production deployments with manual approval. All for deploying a web application.  
   1.) Skills Demonstrated: CI/CD, Docker, GitHub Actions and environments (dev, staging, prod)
   
3) Architecture:

   GitHub Push
    │
    ▼
GitHub Actions
    ├── Run tests (Jest/Pytest)
    ├── Build Docker image
    ├── Push to ghcr.io
    ├── Deploy to staging (automatic)
    └── Deploy to production (manual approval gate)

 Testing is automatical done on the staging environment. The goal is to upload a web app in GitHub repo, build docker image
 push to hube GitHub container registery then eventually lands and deploys on the staging environment. When everything is good to go eventually we manually deploy. 

   



   
    
