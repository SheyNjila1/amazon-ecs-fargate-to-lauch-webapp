# amazon-ecs-fargate-to-launch-webapp

## Launch Web App using Amazon ECS Fargate
## Prerequisites
###  In order to complete this tutorial you must have an AWS Account  with IAM   user having ECS full access or full administrator access
### 1. From the amazon ECS console, select Get started. Here a Container definition and Task definition
![image](https://user-images.githubusercontent.com/96470430/213062325-11042e9c-0150-4248-94d7-4a33dd9fe414.png)

![image](https://user-images.githubusercontent.com/96470430/213062615-8be8d6fa-55a4-42d5-be71-9fd9624a5273.png)

### 2. Define the service. In this demo, no load balancer is used.
![image](https://user-images.githubusercontent.com/96470430/213063278-77608276-0a4b-4b4e-8b2d-4bc0470af2d0.png)
### 3. Configure the cluster. 
![image](https://user-images.githubusercontent.com/96470430/213063880-ca69f0e6-306f-43ab-b337-178c72ae5732.png)
![image](https://user-images.githubusercontent.com/96470430/213064173-71d8694d-a65b-4929-98bb-c3652a97369e.png)

#### Cluster Created: Cluster created with additional features as shown below
![image](https://user-images.githubusercontent.com/96470430/213064700-8dc0a7d0-896a-42d9-acdf-f35ce12f6781.png)

#### Service: Service is up and running with details as below
![image](https://user-images.githubusercontent.com/96470430/213064993-e50b23df-ebe3-4e27-b7a4-7da85310dc4e.png)

#### Tasks shows a ruunig status
![image](https://user-images.githubusercontent.com/96470430/213065154-d4126631-8c6e-4997-8513-c351685dab2b.png)

#### Events
![image](https://user-images.githubusercontent.com/96470430/213065348-efa2a367-6014-4af8-84bb-c2e0ae2ed736.png)

#### Deployments
![image](https://user-images.githubusercontent.com/96470430/213065476-e8d2030f-ce71-479a-900a-6ba9d8c0f70b.png)

#### Logs
![image](https://user-images.githubusercontent.com/96470430/213065683-cd3e5112-50b5-47fc-8b59-f815126d073b.png)

#### Cluster Details shows an active status with the sample app servicee  in active status also
![image](https://user-images.githubusercontent.com/96470430/213066247-5efdd281-be32-4444-8ff2-351ec1323d3d.png)

### 3. Verify if App can be desplayed in browser. This is done using Public IP ( 54.175.51.243) in this case  
![image](https://user-images.githubusercontent.com/96470430/213066677-e021f5fd-1a87-4aed-aec6-be25ea792b28.png)

## App is up and running!!!!!!
![image](https://user-images.githubusercontent.com/96470430/213066914-ebc9dbbb-5a4e-43cc-9343-0fcd1f41a180.png)











