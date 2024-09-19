# Lab-Dio-AzureEssentials

# Meu Resumo Módulo Git, GitHub e Introdução ao Azure

Olá, sou grato pelos ensinamentos passados até aqui.
Nessas aulas do Bootcamp Azure Essentials pude aprender como instalar o Git, criar e configurar uma conta no GitHub, criar um repositório, colaborar com um repositório Open Source, utilizar comandos para manipular os arquivos do repositório localmente, como os comando git clone, pull request, commit. Também já foi feito uma introdução no Azure, criando uma conta gratuita e explorando os diversos recursos que o Azure pode fornecer. Está sendo um desafio bastante inovador e válido nos dias de hoje, espero seguir com os aprendizados e poder evoluir profissionalmente. Muito Obrigado.


# Meu Resumo Módulo Benefícios na Nuvem

## Alta Disponibilidade

Significa o quanto as aplicações ou recursos de nuvem estão disponíveis sempre que necessário e a garantia de SLA de acordo com o contrato que ele se propõe a atender.

A alta disponibilidade deve garantir a disponibilidade máxima independete de interrupções ou eventos que possam ocorrer.

## Escalabilidade

Refere-se à capacidade de ajustar ou adicionar recursos para atender a demanda. É uma escala vertical. Exemplo: Aumentar a capacidade de discos rígidos devido ao crescimento natural de um banco de dados.

## Elasticidade

É quando você automatiza, ou mão, a criação de recursos para atender uma demanda por meio de expansão, e quando essa demanda cai automaticamente os recursos são desalocados e reduzidos horizontalmente. É possível configurar a expansão de recursos de acordo com um indicador, por exemplo: Quando tivermos X acessos ao nosso site, aumente 1 servidor.

## Confiabilidade

Resiliência em criar recursos em diversos lugares do mundo, tornando nossas aplicações seguras, decentralizadas para se recuperar de desastres facilmente.

## Precisibilidade

Influencido pelo Microsoft Azure Architected Framework, um recurso do Azure que nos mostra os cases de sucesso.

## Segurança

O Azure fornece diversos recursos de segurança, porém a responsabiidade da Configuração é de responsabilidade do cliente, então é necessário criar regras e modelos de segurança para se previnir de possíveis ataques, como por exemplo atualização de hotfix e patches do Windows.

## Governança

Quais são os padrões de gerenciamento da computação em nuvem que serão implementados no ambiente, está associado a segurança e politicas que estejam em conformidade com o negócio e a padrões corporativos que a empresa\cliente deve atender.

## Gerenciabilidade

São as formas e as ferramentas disponíveis para gerenciar o ambiente em nuvem, exemplo:
    
    Navegador\Portal
    Linha de Comando
    API
    Power Shell
    Terraform

É possível escalar automaticamente a implantação de recursos com base na necessidade.

É possível implantar recursos com base em um modelo pré-configurado, ermovendo a necessidade de configuração manual.

# TIPOS DE SERVIÇO DE NUVEM

## IaaS (Infraestrutura como serviço)

    Serviços de Nuvem mais flexível.
    Você configura e gerencia o hardware para o seu aplicativo.
    Necessita de configuração e personalização dos recursos, exemplos de recursos:
    Servidores e Armazenamento
    Firewalls\Segurança de rede
    Planta física\edifício do datacenter

## PaaS (PLataforma como serviço)

    Focado no desenvolvimento de aplicativos.
    O gerenciamento de plataforma é de responsabilidade do provedor de nuvem.
    Além dos recursos acima, o PaaS também engloba Sistemas Operacionais, ferramentas para desenvolvedores, análise de negócios de gerenciamento de database.
    Um exemplo, é um banco de dados hospedado em nuvem, onde usamos apenas a plataforma de database e não me preocupo com o servidor onde ele está hospedado.

## SaaS (Software como serviço)

    Modelo de preço de pagamento conforme uso.
    Os usuários pagam pelo software que utilizam em um modelo de assinatura.
    São os aplicativos e apps hospedados na nuvem, são aplicativos licenciados, exemplo: Office 365, email, calendários, Netflix, Spofify.

# MODELO DE RESPONSABILIDADE COMPARTILHADA

![alt text](image.png)

# COMPONENTES DE ARQUITETURA DO AZURE

Os componentes de arquitetura do Azurereferir-se

## Computação
   
    Máquinas Virtuais (VMs)
    Serviços de aplicativos
    Serviço Azure Kubernetes (AKS)
    Funções do Azure

## Rede
    Rede Virtual (VNet)
    Balanceador de Carga do Azure
    Gateway VPN

## Armazenamento
    Armazenamento de Blobs do Azure
    Arquivos do Azure
    Armazenamento em disco do Azure

## Bancos de Dados
    Banco de Dados SQL do Azure: Banco
    Cosmos DB
    PostgreSQL

## Monitoramento e Gerenciamento
    Monitor do Azure
    Central de Segurança do Azure
    Automação do Azure

## Identidade e Acesso
    Diretório Ativo do Azure (Azure AD)
    Controle de acesso baseado em função (RBAC)

## Ferramentas de Integração
    Aplicativos lógicos do Azure
    Ônibus de serviço
    Grade de eventos

## Segurança
    Cofre de Chaves do Azure
    Firewall do Azure
    Proteção DDoS

## Aprendizado de Máquina e IA
    Aprendizado de máquina do Azure
    Serviços Cognitivos

## DevOps e Desenvolvimento
    Azure DevOps
    Pipelines do Azure
    
Esses componentes são combinados para formar soluções robustas e escaláveis ​​na nuvem, cada uma atendendo a diferentes necessidades.

# Pares de Região (Region Pairs)

Pares de Região garantem alta disponibilidade e resiliência, proporcionando replicação geográfica de dados e continuidade dos serviços em caso de falhas.

Características principais:

    Alta Disponibilidade
    Replicação de Dados
    Distância Física
    Atualizações Planejadas

## Exemplo de Pares

    Leste dos EUA eOeste dos EUA
    Leste da Austrália e Sudeste da Austrália
    Norte da Europa e Oeste da Europa
    
Esses pares garantem que, em caso de falha de uma região inteira (como desastres naturais ou problemas técnicos significativos), a região emparelhada pode continuar funcionando com seus dados e serviços replicados.

# Grupos de Recursos (Resource Groups)

Grupos de Recursos permitem organização eficiente e gerenciamento centralizado de recursos, facilitando a administração de soluções no Azure.

Características:
    
    Organização
    Gerenciamento Coletivo
    Controle de Acesso
    Tags
    Ciclo de Vida dos Recursos
