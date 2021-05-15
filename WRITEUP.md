# Azure VMs vs App Services

## Analyze, choose, and justify the appropriate resource option for deploying the app

### **Analyze costs, scalability, availability, and workflow**

- In contrast to Azure App Service, Azure VMs are more costly to run.
- In contrast to Azure App Service, Azure VMs are more scalable. As a result, Azure VMs are favored when there is a possibility of future expansion.
- In contrast to Azure App Service, managing Azure VMs necessitates more effort.
- When using Azure Software Service, app creation is much quicker and easier.
- In contrast to App Service, Azure VMs have more control over the underlying infrastructure. We can't choose which underlying OS we want in an App Service.

### **Choose the appropriate solution (VM or App Service) for deploying the app**

- The following factors influenced my decision to use an App Service rather than Azure VMs:
  1. The requirement for a low-cost alternative
  2. There isn't much of a need for scaling.
  3. There is no requirement to choose the underlying infrastructure.

## Assess app changes that would change your decision

*Detail how the app and any other needs would have to change for you to change your decision in the last section.*

- If successful, my app's size and compute resources could skyrocket. This demonstrates the importance of scaling.
- Also, since some products are a huge success and others aren't, there's no way to foresee how much resources will be required, necessitating the use of AUTO SCALING.
These updates to my app will have an impact on the decision I made in the previous section.
