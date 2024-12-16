# FaaS (Lambda) with TIBCO Flogo Enterprise

## Scenario

The architecture diagram isn't updated for AWS Lambda so it shows HTTP Trigger but in application it uses receive lambda invocation trigger


![image](https://github.com/user-attachments/assets/5a24d8a4-9f77-48c9-b085-082d9139ccc5)

## Deployment
- AWS Lambda

## Prerequisites
- We are using TIBCO Cloud Platform APIs to build the app binary. You need to prepare  accessToken to access the platform apis.
- Similarly you will need to get your aws credentials for final deployment
- jenkins server should have http request plugin installed we are using it for calling TIBCO Cloud PAPI


Hopefully, it will give you quick peek of how easy it is to build automation around TIBCO Flogo for FaaS deployment!!!
