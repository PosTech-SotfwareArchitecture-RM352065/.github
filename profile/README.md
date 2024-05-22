# POS TECH FIAP - SOFTWARE ARCHITECTURE
<img width="200" height="200" alt="Awesome GitHub Profile Readme" src="https://github.com/PosTech-SotfwareArchitecture-RM352065/.github/blob/79249f3afa76352cd1f954d841d8a5042254679e/docs/assets/sandduda-logo.png"> </img>

Projeto criado para as entregas relativas ao Tech Challenge para o curso de POS TECH

## Videos Youtube
[Video Youtube Módulo 2](https://www.youtube.com/watch?v=GzHLmtYgzV0)

[Video Youtube Módulo 3](https://www.youtube.com/watch?v=SvFZTCRB8gU)

## Estrutura dos repositórios

> [!Note]
> 
> Algumas das configurações que fiz estão concentradas na minha página de "atalhos" [TLDR](https://github.com/cangelosilima/TLDR). Estou usando o [Windows Developer Environment](https://github.com/cangelosilima/TLDR/tree/main/win-developer-env/README.md)

### Documentação
A documentação deste projeto é estruturada de maneira organizada para garantir uma experiência intuitiva aos visitantes. Cada contexto, como Docker, Kubernetes e APIs, possui seu próprio conjunto de informações contido em um README específico, localizado dentro da pasta `docs`. A única exceção é o README do repositório principal, mantido fora dessa pasta para simplificar o acesso aos visitantes.

### Payment API

API desenvolvida em .net 8 para Azure Functions, utilizando banco de dados MongoDB e integrando com o Mercago Pago para geração de QR Code para PIX:

https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-api-payment

[![Code Analysis & Push to DockerHub](https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-api-payment/actions/workflows/code-analysis.yml/badge.svg?branch=main)](https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-api-payment/actions/workflows/code-analysis.yml) [![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=PosTech-SotfwareArchitecture-RM352065_tech-challenge-fiap-api-payment&metric=alert_status)](https://sonarcloud.io/summary/overall?id=PosTech-SotfwareArchitecture-RM352065_tech-challenge-fiap-api-payment) [![Coverage](https://sonarcloud.io/api/project_badges/measure?project=PosTech-SotfwareArchitecture-RM352065_tech-challenge-fiap-api-payment&metric=coverage)](https://sonarcloud.io/summary/overall?id=PosTech-SotfwareArchitecture-RM352065_tech-challenge-fiap-api-payment) 

Terrafrom para criação da infraestrutura dentro da Azure para a api de pagamentos:

https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-api-payment-terraform

[![Terraform Apply](https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-api-payment-terraform/actions/workflows/terraform-apply.yml/badge.svg?branch=main)](https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-api-payment-terraform/actions/workflows/terraform-apply.yml)
[![Terraform Destroy](https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-api-payment-terraform/actions/workflows/terraform-destroy.yml/badge.svg?branch=main)](https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-api-payment-terraform/actions/workflows/terraform-destroy.yml)

### Costumer API

API desenvolvida em .net 8 para Azure Functions, utilizando banco de dados SQL Server para criação de novos logins assim como auteticação de clientes cadastrados e anônimos:

https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-api-costumer

[![Code Analysis & Push to DockerHub](https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-api-costumer/actions/workflows/code-analysis.yml/badge.svg?branch=main)](https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-api-costumer/actions/workflows/code-analysis.yml) [![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=PosTech-SotfwareArchitecture-RM352065_tech-challenge-fiap-api-costumer&metric=alert_status)](https://sonarcloud.io/summary/overall?id=PosTech-SotfwareArchitecture-RM352065_tech-challenge-fiap-api-costumer) [![Coverage](https://sonarcloud.io/api/project_badges/measure?project=PosTech-SotfwareArchitecture-RM352065_tech-challenge-fiap-api-costumer&metric=coverage)](https://sonarcloud.io/summary/overall?id=PosTech-SotfwareArchitecture-RM352065_tech-challenge-fiap-api-costumer) 

Terrafrom para criação da infraestrutura dentro da Azure para a api de clientes:

https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-api-costumer-terraform

[![Terraform Apply](https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-api-costumer-terraform/actions/workflows/terraform-apply.yml/badge.svg?branch=main)](https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-api-costumer-terraform/actions/workflows/terraform-apply.yml)
[![Terraform Destroy](https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-api-costumer-terraform/actions/workflows/terraform-destroy.yml/badge.svg?branch=main)](https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-api-costumer-terraform/actions/workflows/terraform-destroy.yml)

### Order API

API desenvolvida em .net 8 para ASP.NET Core para criação de pedidos e carrinho, utilizando banco de dados SQL Server e REDIS, além de Service Bus para notificação em tópicos:

https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-api-costumer

[![Code Analysis & Push to DockerHub](https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-api-order/actions/workflows/code-analysis.yml/badge.svg?branch=main)](https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-api-order/actions/workflows/code-analysis.yml) [![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=PosTech-SotfwareArchitecture-RM352065_tech-challenge-fiap-api-order&metric=alert_status)](https://sonarcloud.io/summary/overall?id=PosTech-SotfwareArchitecture-RM352065_tech-challenge-fiap-api-order) [![Coverage](https://sonarcloud.io/api/project_badges/measure?project=PosTech-SotfwareArchitecture-RM352065_tech-challenge-fiap-api-order&metric=coverage)](https://sonarcloud.io/summary/overall?id=PosTech-SotfwareArchitecture-RM352065_tech-challenge-fiap-api-order) 

Terrafrom para criação da infraestrutura dentro da Azure para a api de pagamentos:

https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-api-costumer-terraform

[![Terraform Apply](https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-api-order-terraform/actions/workflows/terraform-apply.yml/badge.svg?branch=main)](https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-api-order-terraform/actions/workflows/terraform-apply.yml)
[![Terraform Destroy](https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-api-order-terraform/actions/workflows/terraform-destroy.yml/badge.svg?branch=main)](https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-api-order-terraform/actions/workflows/terraform-destroy.yml)

### Admin API

API desenvolvida em .net 8 para ASP.NET Core, utilizando banco de dados SQL Server para criação de pedidos e carrinho:

https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-api-costumer

[![Code Analysis & Push to DockerHub](https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-api-admin/actions/workflows/code-analysis.yml/badge.svg?branch=main)](https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-api-admin/actions/workflows/code-analysis.yml) [![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=PosTech-SotfwareArchitecture-RM352065_tech-challenge-fiap-api-admin&metric=alert_status)](https://sonarcloud.io/summary/overall?id=PosTech-SotfwareArchitecture-RM352065_tech-challenge-fiap-api-admin) [![Coverage](https://sonarcloud.io/api/project_badges/measure?project=PosTech-SotfwareArchitecture-RM352065_tech-challenge-fiap-api-admin&metric=coverage)](https://sonarcloud.io/summary/overall?id=PosTech-SotfwareArchitecture-RM352065_tech-challenge-fiap-api-admin) 

Terrafrom para criação da infraestrutura dentro da Azure para a api de pagamentos:

https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-api-admin-terraform

[![Terraform Apply](https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-api-admin-terraform/actions/workflows/terraform-apply.yml/badge.svg?branch=main)](https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-api-admin-terraform/actions/workflows/terraform-apply.yml)
[![Terraform Destroy](https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-api-admin-terraform/actions/workflows/terraform-destroy.yml/badge.svg?branch=main)](https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-api-admin-terraform/actions/workflows/terraform-destroy.yml)

### Commons, Observability e Application Gateway

https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-api-gateway-terraform
https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-azure-terraform
https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-observability-terraform

[![Terraform Apply](https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-observability-terraform/actions/workflows/terraform-apply.yml/badge.svg?branch=main)](https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-observability-terraform/actions/workflows/terraform-apply.yml)
[![Terraform Destroy](https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-observability-terraform/actions/workflows/terraform-destroy.yml/badge.svg?branch=main)](https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-observability-terraform/actions/workflows/terraform-destroy.yml)

[![Terraform Apply](https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-api-gateway-terraform/actions/workflows/terraform-apply.yml/badge.svg?branch=main)](https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-api-gateway-terraform/actions/workflows/terraform-apply.yml)
[![Terraform Destroy](https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-api-gateway-terraform/actions/workflows/terraform-destroy.yml/badge.svg?branch=main)](https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-api-gateway-terraform/actions/workflows/terraform-destroy.yml)

### C4 Model
Para criação dos digramas usando o modelo C4, utilizei o site [IcePanel](https://app.icepanel.io/) que facilita a criação e navegação entre os digramas previstos nessa modelagem. Para uma navegação dentro dos sistemas e suas interações acesso o [Sanduba - C4 Model](https://s.icepanel.io/3NzMSG0BWa6nvY/CH0k).

#### Diagrama de Contexto
Tem como objectivo demonstrar como os atores, no nosso caso usuário, interagem com nosso sistema e onde podemos agregar valor ao cliente:

<img alt="Diagrama de Contexto" src="https://github.com/PosTech-SotfwareArchitecture-RM352065/.github/blob/105726af71c66ceeb59197ee74cce4c13989f3dc/docs/assets/componentsDiagram.png"></img>

#### Diagrama de Container
Aplicações e bases dentro de um sistema usado pelo usuário:

<img alt="Diagrama de Contexto" src="https://github.com/PosTech-SotfwareArchitecture-RM352065/.github/blob/105726af71c66ceeb59197ee74cce4c13989f3dc/docs/assets/containerDiagram.png"></img>

#### Diagrama de Componentes
Componentes dentro da aplicação:

<img alt="Diagrama de Contexto" src="https://github.com/PosTech-SotfwareArchitecture-RM352065/.github/blob/105726af71c66ceeb59197ee74cce4c13989f3dc/docs/assets/componentsDiagram.png"></img>
