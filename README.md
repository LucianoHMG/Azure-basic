# Azure-basic
# Arquitetura Microsoft Azure

## Descrição
Este projeto foi criado para demonstrar o entendimento dos componentes principais da arquitetura da **Microsoft Azure** e como eles podem ser utilizados para construir soluções em nuvem escaláveis e seguras. O objetivo é proporcionar uma visão geral dos recursos do Azure aplicados em uma solução prática.

## Componentes Utilizados

### 1. **Serviços de Computação**
   - **Azure Virtual Machines**: Implementação de VMs para hospedar a aplicação.
   - **Azure App Services**: Hospedagem de APIs e serviços web.
   - **Azure Kubernetes Service (AKS)**: Gerenciamento de contêineres com Kubernetes para orquestração.

### 2. **Armazenamento**
   - **Azure Blob Storage**: Armazenamento de arquivos estáticos, como logs e imagens.
   - **Azure Files**: Sistema de arquivos compartilhado.
   - **Discos Gerenciados**: Utilizados para armazenamento persistente das VMs.

### 3. **Rede**
   - **Azure Virtual Network (VNet)**: Criação de uma rede privada para isolar os recursos.
   - **Azure Load Balancer**: Balanceamento de carga entre múltiplas instâncias de VMs.
   - **Azure VPN Gateway**: Configuração de uma VPN para comunicação segura entre a rede local e a nuvem.

### 4. **Banco de Dados**
   - **Azure SQL Database**: Banco de dados relacional gerenciado para a aplicação principal.
   - **Azure Cosmos DB**: Armazenamento de dados não relacionais e distribuídos.

### 5. **Segurança e Identidade**
   - **Azure Active Directory (AAD)**: Gerenciamento de usuários e permissões de acesso.
   - **Azure Key Vault**: Armazenamento seguro de chaves de criptografia e segredos.
   - **Azure Security Center**: Monitoramento e avaliação de segurança.

### 6. **Gerenciamento e Monitoramento**
   - **Azure Monitor**: Coleta de métricas de performance e logs de eventos para monitorar os serviços em tempo real.
   - **Azure Resource Manager (ARM)**: Criação e gerenciamento dos recursos da infraestrutura.
   - **Azure Policy**: Aplicação de políticas de governança para garantir a conformidade das implementações.

## Estrutura do Projeto

- **Infraestrutura como Código (IaC)**: Foi utilizado **Azure Resource Manager (ARM)** templates para automatizar a criação e configuração dos recursos.
- **Monitoramento e Logs**: Configurado o **Azure Monitor** e **Application Insights** para acompanhar métricas e diagnósticos de performance em tempo real.
- **Escalabilidade**: Implementada uma arquitetura escalável utilizando **Load Balancer** para distribuir o tráfego entre as instâncias de VMs.
- **Segurança**: Todas as credenciais e segredos são armazenados no **Azure Key Vault**, com autenticação gerenciada pelo **Azure Active Directory**.


📌 Nota: Este projeto está em constante evolução para incorporar novos recursos da plataforma Azure e explorar mais profundamente as melhores práticas de arquitetura na nuvem.
az login
