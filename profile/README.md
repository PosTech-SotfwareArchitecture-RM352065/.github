# POS TECH FIAP - SOFTWARE ARCHITECTURE
<img width="200" height="200" alt="Awesome GitHub Profile Readme" src="https://github.com/PosTech-SotfwareArchitecture-RM352065/.github/blob/79249f3afa76352cd1f954d841d8a5042254679e/docs/assets/sandduda-logo.png"> </img>

Projeto criado para as entregas relativas ao Tech Challenge para o curso de POS TECH

## Videos Youtube
[Video Youtube Módulo 2](https://www.youtube.com/watch?v=GzHLmtYgzV0)

[Video Youtube Módulo 3](https://www.youtube.com/watch?v=SvFZTCRB8gU)

[Video Youtube Módulo 4](https://www.youtube.com/watch?v=SnTAKJhcXwQ)

[Video Youtube Módulo 5](https://www.youtube.com/watch?v=SnTAKJhcXwaQ)

## Estrutura dos repositórios

> [!Note]
> 
> Algumas das configurações que fiz estão concentradas na minha página de "atalhos" [TLDR](https://github.com/cangelosilima/TLDR). Estou usando o [Windows Developer Environment](https://github.com/cangelosilima/TLDR/tree/main/win-developer-env/README.md)

### Documentação
A documentação deste projeto é estruturada de maneira organizada para garantir uma experiência intuitiva aos visitantes. Cada contexto, como Docker, Kubernetes e APIs, possui seu próprio conjunto de informações contido em um README específico, localizado dentro da pasta `docs`. A única exceção é o README do repositório principal, mantido fora dessa pasta para simplificar o acesso aos visitantes.

### Customer API

API desenvolvida em .net 8 para Azure Functions, utilizando banco de dados SQL Server para criação de novos logins assim como auteticação de clientes cadastrados e anônimos:

[![Code Test & Analysis](https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-api-customer/actions/workflows/code-analysis.yml/badge.svg?branch=main)](https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-api-customer/actions/workflows/code-analysis.yml) [![API Test & Analysis](https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-api-customer/actions/workflows/api-analysis.yml/badge.svg?branch=main)](https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-api-customer/actions/workflows/api-analysis.yml) [![Push to Docker & Azure](https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-api-customer/actions/workflows/docker-push.yml/badge.svg?branch=main)](https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-api-customer/actions/workflows/docker-push.yml) [![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=PosTech-SotfwareArchitecture-RM352065_tech-challenge-fiap-api-customer&metric=alert_status)](https://sonarcloud.io/summary/overall?id=PosTech-SotfwareArchitecture-RM352065_tech-challenge-fiap-api-customer) 

https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-api-customer

Terrafrom para criação da infraestrutura dentro da Azure para a api de clientes:

[![Terraform Apply](https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-api-customer-terraform/actions/workflows/terraform-apply.yml/badge.svg?branch=main)](https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-api-customer-terraform/actions/workflows/terraform-apply.yml)
[![Terraform Destroy](https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-api-customer-terraform/actions/workflows/terraform-destroy.yml/badge.svg?branch=main)](https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-api-customer-terraform/actions/workflows/terraform-destroy.yml)

https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-api-customer-terraform

### Order API

API desenvolvida em .net 8 para ASP.NET Core para criação de pedidos e carrinho, utilizando banco de dados SQL Server e REDIS, além de Service Bus para notificação em tópicos:

[![Code Test & Analysis](https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-api-order/actions/workflows/code-analysis.yml/badge.svg?branch=main)](https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-api-order/actions/workflows/code-analysis.yml) [![API Test & Analysis](https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-api-order/actions/workflows/api-analysis.yml/badge.svg?branch=main)](https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-api-order/actions/workflows/api-analysis.yml) [![Push to Docker & Azure](https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-api-order/actions/workflows/docker-push.yml/badge.svg?branch=main)](https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-api-order/actions/workflows/docker-push.yml) [![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=PosTech-SotfwareArchitecture-RM352065_tech-challenge-fiap-api-order&metric=alert_status)](https://sonarcloud.io/summary/overall?id=PosTech-SotfwareArchitecture-RM352065_tech-challenge-fiap-api-order) 

https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-api-order

Terrafrom para criação da infraestrutura dentro da Azure para a api de pagamentos:

[![Terraform Apply](https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-api-order-terraform/actions/workflows/terraform-apply.yml/badge.svg?branch=main)](https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-api-order-terraform/actions/workflows/terraform-apply.yml)
[![Terraform Destroy](https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-api-order-terraform/actions/workflows/terraform-destroy.yml/badge.svg?branch=main)](https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-api-order-terraform/actions/workflows/terraform-destroy.yml)

https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-api-customer-terraform

### Payment API

API desenvolvida em .net 8 para Azure Functions, utilizando banco de dados MongoDB e integrando com o Mercago Pago para geração de QR Code para PIX:

[![Code Tests & Analysis](https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-api-payment/actions/workflows/code-analysis.yml/badge.svg?branch=main)](https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-api-payment/actions/workflows/code-analysis.yml) [![API Tests & Analysis](https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-api-payment/actions/workflows/api-analysis.yml/badge.svg?branch=main)](https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-api-payment/actions/workflows/api-analysis.yml) [![Push to Docker & Azure](https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-api-payment/actions/workflows/docker-push.yml/badge.svg?branch=main)](https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-api-payment/actions/workflows/docker-push.yml) [![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=PosTech-SotfwareArchitecture-RM352065_tech-challenge-fiap-api-payment&metric=alert_status)](https://sonarcloud.io/summary/overall?id=PosTech-SotfwareArchitecture-RM352065_tech-challenge-fiap-api-payment) 

https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-api-payment

Terrafrom para criação da infraestrutura dentro da Azure para a api de pagamentos:

[![Terraform Apply](https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-api-payment-terraform/actions/workflows/terraform-apply.yml/badge.svg?branch=main)](https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-api-payment-terraform/actions/workflows/terraform-apply.yml)
[![Terraform Destroy](https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-api-payment-terraform/actions/workflows/terraform-destroy.yml/badge.svg?branch=main)](https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-api-payment-terraform/actions/workflows/terraform-destroy.yml)

https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-api-payment-terraform

### Admin API

API desenvolvida em .net 8 para ASP.NET Core, utilizando banco de dados SQL Server para criação de pedidos e carrinho:

[![Code Test & Analysis](https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-api-admin/actions/workflows/code-analysis.yml/badge.svg?branch=main)](https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-api-admin/actions/workflows/code-analysis.yml) [![API Test & Analysis](https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-api-admin/actions/workflows/api-analysis.yml/badge.svg?branch=main)](https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-api-admin/actions/workflows/api-analysis.yml) [![Push to Docker & Azure](https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-api-admin/actions/workflows/docker-push.yml/badge.svg?branch=main)](https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-api-admin/actions/workflows/docker-push.yml) [![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=PosTech-SotfwareArchitecture-RM352065_tech-challenge-fiap-api-admin&metric=alert_status)](https://sonarcloud.io/summary/overall?id=PosTech-SotfwareArchitecture-RM352065_tech-challenge-fiap-api-admin) 

https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-api-admin

Terrafrom para criação da infraestrutura dentro da Azure para a api de pagamentos:

[![Terraform Apply](https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-api-admin-terraform/actions/workflows/terraform-apply.yml/badge.svg?branch=main)](https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-api-admin-terraform/actions/workflows/terraform-apply.yml)
[![Terraform Destroy](https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-api-admin-terraform/actions/workflows/terraform-destroy.yml/badge.svg?branch=main)](https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-api-admin-terraform/actions/workflows/terraform-destroy.yml)

https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-api-admin-terraform

### Commons, Observability e Application Gateway

[![Terraform Apply](https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-azure-terraform/actions/workflows/terraform-apply.yml/badge.svg?branch=main)](https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-azure-terraform/actions/workflows/terraform-apply.yml)
[![Terraform Plan](https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-azure-terraform/actions/workflows/terraform-plan.yml/badge.svg?branch=main)](https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-azure-terraform/actions/workflows/terraform-plan.yml)

https://github.com/PosTech-SotfwareArchitecture-RM352065/tech-challenge-fiap-azure-terraform

### SAGA Pattern

Para o projeto da fase 5, optei por adotar o Saga Pattern utilizando a abordagem de orquestração no fluxo de criação de pedido, pagamento e envio para a cozinha na aplicação. Durante a análise, identifiquei que o domínio do Pedido e o entendimento integral do fluxo estavam concentrados dentro da Order API Isso a torna uma candidata ideal para orquestrar cada etapa do processo, garantindo que todos os passos sejam executados de maneira coordenada e com consistência.

Além disso, centralizar a orquestração na Order API permite manter uma visão unificada do estado do pedido, o que é crucial para responder prontamente a quaisquer falhas ou inconsistências que possam surgir durante a execução do fluxo. Essa centralização também facilita a disponibilização de informações atualizadas para o cliente, promovendo transparência e uma melhor experiência do usuário.

Outra vantagem significativa da orquestração é a possibilidade de implementar compensações de maneira mais controlada e eficiente. Em casos de falha em qualquer etapa, a Order API pode executar de forma coordenada as ações necessárias para reverter o processo, minimizando impactos negativos.

#### Fluxo de Criação, pagamento e inicio preparo
<img alt="Fluxo Saga 1" src="https://github.com/PosTech-SotfwareArchitecture-RM352065/.github/blob/5a554167f3df54122dde4513d6e4d0c5ee3cb832/docs/assets/saga-1.png"></img>

#### Fluxo de compensação em caso de falha
<img alt="Fluxo Saga 2" src="https://github.com/PosTech-SotfwareArchitecture-RM352065/.github/blob/5a554167f3df54122dde4513d6e4d0c5ee3cb832/docs/assets/saga-2.png"></img>


### LGPD 

O Relatório de Impacto à Proteção de Dados Pessoais (RIPD) é um documento fundamental na conformidade com a Lei Geral de Proteção de Dados (LGPD). Ele tem como objetivo analisar e documentar os riscos e impactos relacionados ao tratamento de dados pessoais em determinada atividade ou processo de uma organização. O RIPD deve descrever as medidas adotadas para mitigar os riscos e garantir a proteção dos dados pessoais.

[Relatório de Impacto à Proteção de Dados Pessoais - Restaurante Sanduba](https://github.com/PosTech-SotfwareArchitecture-RM352065/.github/blob/994933c361ef1fbc917389d8e3ce1d32925ea752/docs/assets/RIPD.md)

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
