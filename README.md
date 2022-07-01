# samplewebapp
ASP.NET Web application deployment on Azure Kubernetes Services

Azure Kubernetes Services:

Agenda:
	- ASP.NET Web application deployment on Azure Kubernetes Services
		through Azure DevOps CI/CD

Flow:

- ASP.NET Web application creation
	- DockerFile creation
- Push changes in Azure Repos (Along with DockerFile)
- Build and Push Image (ACR Repository)
- Deploy (AKS)
	- Creation of deployment.yml and service.yml files

