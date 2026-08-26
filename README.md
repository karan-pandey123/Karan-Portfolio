# Portfolio Website – CI/CD Deployment on AWS

## Project Overview

Built and deployed a responsive personal portfolio website using a CI/CD pipeline with GitHub Actions and AWS.

The website is hosted using Amazon S3 and delivered globally through Amazon CloudFront. Any changes made to the website code are automatically processed and deployed through the CI/CD pipeline.

## Technologies Used

- HTML
- CSS
- JavaScript
- Git & GitHub
- GitHub Actions
- CI/CD
- Amazon S3
- Amazon CloudFront

## Deployment Architecture

Developer → GitHub → GitHub Actions → Build → Amazon S3 → CloudFront → Users

## CI/CD Workflow

The deployment process was automated using GitHub Actions.

1. Developed the portfolio website using HTML, CSS and JavaScript.
2. Pushed the project source code to a GitHub repository.
3. Configured GitHub Actions to automatically trigger the deployment workflow whenever changes are pushed to the repository.
4. Made multiple changes and updates to the HTML/CSS/JavaScript files during development.
5. Each code change pushed to GitHub automatically triggered the GitHub Actions workflow.
6. GitHub Actions checked out the latest source code and executed the configured build/deployment steps.
7. After a successful build, the updated website files were deployed to the Amazon S3 bucket.
8. Amazon CloudFront then delivered the updated content globally through its edge locations.
9. This eliminated the need to manually upload website files to S3 after every change.

## Continuous Deployment

During development, I made multiple changes to the portfolio website and pushed them to GitHub.

For every update:

Git Push → GitHub Actions Triggered → Build/Process → Deploy to S3 → CloudFront Delivery

This demonstrated automated continuous deployment, where website updates could be delivered to the cloud environment without manually deploying each change.

## AWS Services Used

### Amazon S3

- Used to store the static website files.
- Acts as the origin for the website deployment.
- Receives updated files automatically through the CI/CD workflow.

### Amazon CloudFront

- Used as a Content Delivery Network (CDN).
- Provides fast global content delivery.
- Enables HTTPS-based access.
- Caches website content at edge locations.

## Key Features

- Responsive personal portfolio website
- Automated CI/CD deployment
- GitHub Actions workflow
- Automatic deployment after code changes
- Static website hosted on Amazon S3
- Amazon CloudFront CDN integration
- HTTPS-enabled content delivery
- Global content distribution through CloudFront
- Reduced manual deployment effort

## Project Outcome

Successfully implemented a CI/CD-based deployment workflow for a personal portfolio website.

The project demonstrates practical experience with Git, GitHub, GitHub Actions, CI/CD automation, Amazon S3 and Amazon CloudFront, including automatically deploying website updates after code changes.
