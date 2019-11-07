# ImageResizerService

Application responsible for resizing product images to predefined
sizes. Resized images are stored in CloudStorage and retrieved 
directly from there.   

Owner|Tier|Status|Contexts
---|---|---|---
CatalogTeam|Tier2|Prod|Web,Catalog

##### Environments

Production:

- URL: https://...
- AWS account: 1234567890
- Logs: https://...
- Dashboard: https://...

There is no staging environment. 

##### Tech

- Python: implementation
- AWS Lambda: execution env 
- Serverless: deployment
- AWS SQS: transport medium

## Deployment

    AWS_PROFILE=... ENV=prod VERSION=... make deploy
    
