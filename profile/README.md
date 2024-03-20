# POS TECH FIAP - SOFTWARE ARCHITECTURE

<img alt="Awesome GitHub Profile Readme" src="https://github.com/PosTech-SotfwareArchitecture-RM352065/.github/tree/main/docs/assets/sandduda-logo.png"> </img>

Projeto criado para as entregas relativas ao Tech Challenge para o curso de POS TECH

## Video Youtube Módulo 2
[![YouTube Link](https://img.youtube.com/vi/GzHLmtYgzV0/0.jpg)](https://www.youtube.com/watch?v=GzHLmtYgzV0)

## Video Youtube Módulo 3
[![YouTube Link](https://img.youtube.com/vi/SvFZTCRB8gU/0.jpg)](https://www.youtube.com/watch?v=SvFZTCRB8gU)

> [!Note]
> 
> Algumas das configurações que fiz estão concentradas na minha página de "atalhos" [TLDR](https://github.com/cangelosilima/TLDR). Estou usando o [Windows Developer Environment](https://github.com/cangelosilima/TLDR/tree/main/win-developer-env/README.md)

## Estrutura dos repositórios

### Documentação
A documentação deste projeto é estruturada de maneira organizada para garantir uma experiência intuitiva aos visitantes. Cada contexto, como Docker, Kubernetes e APIs, possui seu próprio conjunto de informações contido em um README específico, localizado dentro da pasta `docs`. A única exceção é o README do repositório principal, mantido fora dessa pasta para simplificar o acesso aos visitantes.

#### API do restaurante em ASP.Net core, contendo as collections do postman para testes da API
https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-api

[![Code Test & Analysis | Push to DockerHub](https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-api/actions/workflows/code-test-analysis.yml/badge.svg?branch=main)](https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-api/actions/workflows/code-test-analysis.yml)

#### Terrafrom para criação da infraestrutura de kubernetes para a api acima:
https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-kubernetes-terraform

[![Terraform Apply](https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-kubernetes-terraform/actions/workflows/terraform-apply.yml/badge.svg?branch=main)](https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-kubernetes-terraform/actions/workflows/terraform-apply.yml)
[![Terraform Destroy](https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-kubernetes-terraform/actions/workflows/terraform-destroy.yml/badge.svg?branch=main)](https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-kubernetes-terraform/actions/workflows/terraform-destroy.yml)

#### API de autenticação em .net core e Azure function
https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-auth-api

[![Push to DockerHub](https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-auth-api/actions/workflows/docker-push.yml/badge.svg?branch=main)](https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-auth-api/actions/workflows/docker-push.yml)

#### Terrafrom para criação da infraestrutura de serverless para a api acima:
https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-auth-terraform

[![Terraform Apply](https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-auth-terraform/actions/workflows/terraform-apply.yml/badge.svg?branch=main)](https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-auth-terraform/actions/workflows/terraform-apply.yml)
[![Terraform Destroy](https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-auth-terraform/actions/workflows/terraform-destroy.yml/badge.svg?branch=main)](https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-auth-terraform/actions/workflows/terraform-destroy.yml)

#### Terrafrom para criação da infraestrutura de observabilidade:
https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-observability-terraform

[![Terraform Apply](https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-observability-terraform/actions/workflows/terraform-apply.yml/badge.svg?branch=main)](https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-observability-terraform/actions/workflows/terraform-apply.yml)
[![Terraform Destroy](https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-observability-terraform/actions/workflows/terraform-destroy.yml/badge.svg?branch=main)](https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-observability-terraform/actions/workflows/terraform-destroy.yml)

#### Terrafrom para criação da infraestrutura de banco de dados (SQL Server e REDIS), assim como scripts para deployment:
https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-database-terraform

[![Terraform Apply](https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-database-terraform/actions/workflows/terraform-apply.yml/badge.svg)](https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-database-terraform/actions/workflows/terraform-apply.yml)
[![Terraform Destroy](https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-database-terraform/actions/workflows/terraform-destroy.yml/badge.svg)](https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-database-terraform/actions/workflows/terraform-destroy.yml)

#### Terrafrom para criação da infraestrutura de Application Gateway:
https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-api-gateway-terraform

[![Terraform Apply](https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-api-gateway-terraform/actions/workflows/terraform-apply.yml/badge.svg?branch=main)](https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-api-gateway-terraform/actions/workflows/terraform-apply.yml)
[![Terraform Destroy](https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-api-gateway-terraform/actions/workflows/terraform-destroy.yml/badge.svg?branch=main)](https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-api-gateway-terraform/actions/workflows/terraform-destroy.yml)


#### Terraform para criacão do storage account onde será armazenado o terraform state, assim como Virtual Network e subnets:
https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-azure-terraform

### C4 Model
Para criação dos digramas usando o modelo C4, utilizei o site [IcePanel](https://app.icepanel.io/) que facilita a criação e navegação entre os digramas previstos nessa modelagem. Para uma navegação dentro dos sistemas e suas interações acesso o [Sanduba - C4 Model](https://s.icepanel.io/3NzMSG0BWa6nvY/CH0k).

#### Diagrama de Contexto
Tem como objectivo demonstrar como os atores, no nosso caso usuário, interagem com nosso sistema e onde podemos agregar valor ao cliente:

<img alt="Diagrama de Contexto" src="https://github.com/PosTech-SotfwareArchitecture-RM352065/.github/tree/main/docs/assets/contextDiagram.png"></img>

#### Diagrama de Container
Aplicações e bases dentro de um sistema usado pelo usuário:

<img alt="Diagrama de Contexto" src="https://github.com/PosTech-SotfwareArchitecture-RM352065/.github/tree/main/docs/assets/containerDiagram.png"></img>

#### Diagrama de Componentes
Componentes dentro da aplicação:

<img alt="Diagrama de Contexto" src="https://github.com/PosTech-SotfwareArchitecture-RM352065/.github/tree/main/docs/assets/componentsDiagram.png"></img>
