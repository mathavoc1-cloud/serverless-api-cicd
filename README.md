Serverless API with CI/CD (AWS + FastAPI)

This project demonstrates a complete CI/CD pipeline deploying a Python FastAPI application to AWS Lambda.

Features
- FastAPI backend
- AWS Lambda deployment
- GitHub Actions CI/CD
- Automated testing with pytest

Tech Stack
- Python
- FastAPI
- AWS Lambda
- API Gateway
- GitHub Actions

CI/CD Pipeline
Every push to `main` triggers:
- Dependency installation
- Automated tests
- Deployment to AWS Lambda

Endpoints
- `/` → Hello message
- `/health` → Health check

Setup

1. Configure AWS credentials in GitHub Secrets:
   - AWS_ACCESS_KEY_ID
   - AWS_SECRET_ACCESS_KEY

2. Update:
   - YOUR_FUNCTION_NAME in deploy.yml

Future Improvements
- Add Terraform
- Add staging environment
- Improve logging
