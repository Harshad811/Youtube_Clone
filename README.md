
PROJECT TITLE:
YouTube Clone – CI/CD Automation using Azure DevOps Pipeline Artifacts


PROJECT OVERVIEW:
This project demonstrates a complete CI/CD implementation for a frontend YouTube Clone application using Azure DevOps and Microsoft Azure. 
The frontend code is used as a sample application, while the primary focus of the project is on CI/CD pipeline automation, pipeline artifacts, testing integration, and cloud deployment.


PROJECT OBJECTIVE:
The objective of this project is to implement Continuous Integration and Continuous Deployment using Azure DevOps pipelines, focusing on build automation, pipeline artifacts, testing stages, and deployment to Azure App Service.


NOTE ON CODE OWNERSHIP:
The frontend YouTube Clone code is used only for deployment and CI/CD demonstration purposes.
The main contribution in this project is designing and implementing CI/CD pipelines, artifact handling, testing integration, and Azure deployment.


TECHNOLOGIES USED:

Frontend (Sample Application):
- HTML
- CSS
- JavaScript

DevOps & Cloud:
- Azure DevOps Pipelines
- Pipeline Artifacts (Normal Artifacts)
- Azure Test features (Pipeline testing / validations)
- Azure App Service (Linux)
- Node.js
- Git & GitHub


ARCHITECTURE FLOW:

Developer Code Repository
        |
        v
Azure DevOps CI Pipeline
        |
        v
Install Dependencies
        |
        v
Build Frontend Application
        |
        v
Run Tests (Validation / Test Stage)
        |
        v
Pipeline Artifact Published
        |
        v
CD Pipeline Downloads Artifact
        |
        v
Deployment to Azure App Service
        |
        v
Live Web Application


CONTINUOUS INTEGRATION (CI):
- Automatically triggered on every code push
- Installs dependencies
- Builds the frontend application
- Executes test steps for validation
- Publishes build output as a Pipeline Artifact


TESTING FEATURES USED:
- Pipeline-based testing and validation steps
- Ensures build quality before deployment
- Prevents faulty builds from moving to deployment stage


CONTINUOUS DEPLOYMENT (CD):
- Downloads the pipeline artifact generated during CI
- Deploys the artifact without rebuilding
- Ensures consistency between tested and deployed code
- Fully automated deployment to Azure App Service (Linux)


ARTIFACT MANAGEMENT:
- Uses Azure DevOps Pipeline Artifacts (Normal Artifacts)
- Artifacts are scoped to pipeline runs
- Used for transferring build output from CI to CD
- Ensures clean separation between build and deployment stages


DEPLOYMENT DETAILS:
- Hosted on Azure App Service (Linux)
- Automated deployment using CI/CD pipeline
- Publicly accessible application

LIVE APPLICATION URL:
https://youtubeclone123-eyc0bjb4f6beb6gw.centralindia-01.azurewebsites.net


KEY DEVOPS LEARNINGSINGS:
- CI/CD pipeline design using Azure DevOps
- Difference between Pipeline Artifacts and Centralized Artifact Feeds
- Integration of testing in CI pipelines
- Automated deployment using pipeline artifacts
- Clear separation of CI and CD responsibilities


INTERVIEW EXPLANATION (SAFE & PROFESSIONAL):
This project focuses on implementing CI/CD pipelines using Azure DevOps where a sample YouTube Clone frontend application is built, tested, packaged as a pipeline artifact, and deployed to Azure App Service. The main contribution is DevOps automation, artifact handling, and testing integration rather than frontend development.


DIFFERENCE FROM NIKE PROJECT:
- Uses Pipeline Artifacts instead of Centralized Artifact Feed
- Includes testing stages in the CI pipeline
- Artifacts are scoped per pipeline run
- Simpler artifact lifecycle compared to centralized feeds


POSSIBLE FUTURE ENHANCEMENTS:
- Add approval gates for deployment
- Add multi-environment pipelines (Dev / QA / Prod)
- Integrate advanced automated testing
- Migrate to Azure Static Web Apps
