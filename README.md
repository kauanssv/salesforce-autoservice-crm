# AutoService CRM

Projeto de portfólio desenvolvido na plataforma Salesforce com o objetivo de criar um sistema completo para gerenciamento de serviços automotivos.

A proposta do projeto é simular uma solução real de CRM para oficinas e centros automotivos, permitindo o gerenciamento de clientes, veículos, ordens de serviço, diagnósticos, orçamentos, técnicos e acompanhamento dos serviços.

O projeto será desenvolvido de forma evolutiva, aplicando recursos administrativos e de desenvolvimento da plataforma Salesforce.

## Objetivo

O objetivo principal do AutoService CRM é colocar em prática conhecimentos de Salesforce em um projeto completo, aproximando o desenvolvimento de um cenário real de mercado.

Ao longo do projeto serão aplicados conceitos de:

- Salesforce Administration
- Modelagem de dados
- Flow Builder
- Apex
- SOQL
- Lightning Web Components
- Integrações REST
- Segurança e permissões
- Reports e Dashboards
- Salesforce CLI
- Git e GitHub
- Agentforce

## Fluxo principal do sistema

O processo principal do AutoService será baseado no seguinte fluxo:

```text
Cliente
   ↓
Veículo
   ↓
Ordem de Serviço
   ↓
Diagnóstico
   ↓
Orçamento
   ↓
Aprovação
   ↓
Reparo
   ↓
Entrega
```

## Funcionalidades planejadas

Entre as principais funcionalidades previstas estão:

- Cadastro de clientes
- Cadastro e gerenciamento de veículos
- Criação de ordens de serviço
- Registro de diagnósticos
- Criação e aprovação de orçamentos
- Acompanhamento do status do serviço
- Distribuição de serviços entre técnicos
- Automação de processos com Flow Builder
- Regras de validação
- Controle de acesso com Permission Sets
- Desenvolvimento de regras de negócio em Apex
- Testes automatizados em Apex
- Componentes personalizados com Lightning Web Components
- Integrações com APIs externas
- Relatórios e dashboards
- Automação e atendimento utilizando Agentforce

## Arquitetura inicial

A estrutura inicial de dados será baseada em objetos padrão e personalizados da Salesforce.

```text
Account
   ↓
Contact
   ↓
Vehicle__c
   ↓
Service_Order__c
   ├── Diagnosis
   ├── Budget
   └── Service
```

A modelagem poderá ser alterada durante o desenvolvimento conforme novos requisitos forem adicionados ao projeto.

## Tecnologias

- Salesforce Platform
- Salesforce Lightning Experience
- Flow Builder
- Apex
- SOQL
- Lightning Web Components
- Salesforce CLI
- REST APIs
- Git
- GitHub
- Agentforce

## Estrutura do projeto

```text
salesforce-autoservice-crm/
│
├── force-app/
│   └── main/
│       └── default/
│
├── config/
├── scripts/
├── .forceignore
├── .gitignore
├── README.md
└── sfdx-project.json
```

Conforme o projeto evoluir, a pasta `force-app/main/default` armazenará metadados como:

```text
classes/
triggers/
lwc/
flows/
objects/
permissionsets/
applications/
```

## Etapas de desenvolvimento

O projeto será desenvolvido seguindo aproximadamente esta ordem:

1. Planejamento e modelagem
2. Configuração administrativa
3. Estrutura dos processos de negócio
4. Automações com Flow Builder
5. Configuração do ambiente com Salesforce CLI
6. Desenvolvimento Apex
7. Testes Apex
8. Lightning Web Components
9. Integrações REST
10. Processamento assíncrono
11. Reports e Dashboards
12. Agentforce
13. Documentação final

## Status do projeto

🚧 **Em desenvolvimento**

Atualmente o projeto está em sua fase inicial de estruturação e configuração do ambiente de desenvolvimento.

## Sobre o projeto

Este projeto foi criado como parte do meu desenvolvimento profissional na plataforma Salesforce e será utilizado como portfólio para demonstrar conhecimentos de administração, automação e desenvolvimento Salesforce.

O objetivo não é apenas implementar funcionalidades, mas também aplicar boas práticas de organização, versionamento, segurança, automação e desenvolvimento.

## Autor

**Kauan de Souza dos Santos Vieira**

Estudante de Análise e Desenvolvimento de Sistemas e profissional em formação na plataforma Salesforce.