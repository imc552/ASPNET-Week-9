# Azure App Deployment Plan

## Application Workflow
Local development environment > Push code to Github repository > Commit is pushed to build server > Deploy build to Azure App Service > Run Azure App Service

## App Service Setup
- Runtime Stack: .NET 9.0
- App Name: [Your app name]
- Region: US East

## Branches
- **Development Branch**: All code will be pushed here and will be deployed to the staging slot
- **Production Branch**: Code will be deployed to the production slot

## Configuration
- App settings for development and production environment
- Logging for both development and productin environment
