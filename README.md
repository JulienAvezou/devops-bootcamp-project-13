# devops-bootcamp-project-13
Prometheus

### 1. Setup

#### 1.1 create cluster in EKS using eksctl

![Capture d’écran 2023-03-11 à 12 37 45](https://user-images.githubusercontent.com/62488871/224486693-e2027ab8-2922-426f-ae94-3b5be6b63f7b.png)

![Capture d’écran 2023-03-11 à 12 55 43](https://user-images.githubusercontent.com/62488871/224486707-aa8ed4df-9ebe-4dd0-afea-1596ee339aec.png)

#### 1.2 deploy micro-service application

![Capture d’écran 2023-03-11 à 13 28 12](https://user-images.githubusercontent.com/62488871/224486734-ccf955da-e80a-45fc-ad04-48fa268e15d5.png)

#### 1.3 deploy prometheus monitoring stack using helm inside its own namespace - monitoring

![Capture d’écran 2023-03-11 à 13 42 41](https://user-images.githubusercontent.com/62488871/224486742-8e0566b3-0b6d-4d51-ba82-d092cde1bb78.png)

#### 1.4 check components of prometheus stack

![Capture d’écran 2023-03-11 à 13 45 48](https://user-images.githubusercontent.com/62488871/224486758-39d42e6f-252f-4391-8d64-5691523f030c.png)

#### 1.5 check Prometheus UI for monitoring

![Capture d’écran 2023-03-11 à 14 06 02](https://user-images.githubusercontent.com/62488871/224486785-2e1a91ee-4bf5-4c9f-9968-e038b2785ffa.png)

<img width="524" alt="Capture d’écran 2023-03-11 à 14 06 37" src="https://user-images.githubusercontent.com/62488871/224486786-ad92a55c-7a68-474a-8c7a-5812ace3ef9a.png">

#### 1.6 check Grafana UI for data visualisation

![Capture d’écran 2023-03-11 à 14 21 31](https://user-images.githubusercontent.com/62488871/224489207-6f4a7019-8775-4e72-98eb-d943e3ba0a2d.png)

![Capture d’écran 2023-03-11 à 14 23 55](https://user-images.githubusercontent.com/62488871/224489208-6a525033-1fa8-4b4f-983f-f29aeb9f166d.png)

### 2. Alert Rules - create new alert rules

![Capture d’écran 2023-03-11 à 15 42 11](https://user-images.githubusercontent.com/62488871/224491881-83bf08c9-baf8-4a4f-a6d0-127988f98c2e.png)

![Capture d’écran 2023-03-11 à 15 42 03](https://user-images.githubusercontent.com/62488871/224491886-56196442-9778-48c3-8735-f9fda36aaf3e.png)

![Capture d’écran 2023-03-11 à 15 51 48](https://user-images.githubusercontent.com/62488871/224491891-b64e724e-a1b2-4b71-9160-e52a12bdd224.png)

### 3. Alert Manager - create routes & receiver for email notification setup

#### 3.1 Create config files for alert manager config & secret for storing email password

![Capture d’écran 2023-03-11 à 16 48 17](https://user-images.githubusercontent.com/62488871/224495720-c9677b6b-aca4-4778-b663-3cbc98f2f950.png)

![Capture d’écran 2023-03-11 à 17 22 48](https://user-images.githubusercontent.com/62488871/224495746-869442fb-3aac-4c29-b5d4-8d88ae23becb.png)

#### 3.2 Deploy K8s resources

![Capture d’écran 2023-03-11 à 16 53 10](https://user-images.githubusercontent.com/62488871/224495831-308fe736-4e31-4467-a12a-8528ad93c968.png)

![Capture d’écran 2023-03-11 à 16 53 40](https://user-images.githubusercontent.com/62488871/224495832-a186e537-7bc4-4c37-b642-cf2910182c4d.png)

![Capture d’écran 2023-03-11 à 16 55 05](https://user-images.githubusercontent.com/62488871/224495843-4a1077ce-377a-4148-b232-a9087381903b.png)

#### 3.3 Deploy container that will simulate high CPU load

![Capture d’écran 2023-03-11 à 17 03 06](https://user-images.githubusercontent.com/62488871/224495886-eec68361-18ca-448c-b26e-17d8ad99c922.png)

#### 3.4 Verify that monitoring and alerting kicked in, you should have received an email

![Capture d’écran 2023-03-11 à 17 11 05](https://user-images.githubusercontent.com/62488871/224495920-a4fec356-532d-44b6-a2d7-6ccbef7d5c64.png)

<img width="1105" alt="Capture d’écran 2023-03-11 à 17 11 16" src="https://user-images.githubusercontent.com/62488871/224495921-dc690c16-190c-42d0-b017-380d0101160d.png">





