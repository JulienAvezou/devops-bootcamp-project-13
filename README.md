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


