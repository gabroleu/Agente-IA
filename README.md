# Lança Leads AI | AGENTE IA

Lança Leads AI é uma plataforma de prospecção inteligente que identifica automaticamente empresas com baixa presença digital, qualifica oportunidades de negócio e auxilia no processo comercial de venda de sites e serviços digitais.

O sistema utiliza inteligência artificial para analisar empresas encontradas em plataformas públicas, identificar potenciais clientes e gerar abordagens personalizadas para aumentar a eficiência da prospecção.

## Objetivo

Ajudar agências, freelancers e empresas de tecnologia a encontrar negócios que necessitam de melhorias em sua presença digital, reduzindo o tempo gasto com pesquisa manual e aumentando a geração de oportunidades comerciais.

## Funcionalidades

### Descoberta de Leads

* Busca automática de empresas por região e segmento.
* Identificação de empresas sem site.
* Identificação de empresas com presença digital limitada.
* Coleta de informações públicas relevantes.
* Organização automática dos resultados.

### Análise Inteligente

* Classificação de oportunidades por potencial de conversão.
* Avaliação da presença digital da empresa.
* Geração de score de oportunidade.
* Análise de concorrência local.
* Sugestões de serviços adequados para cada negócio.

### Geração de Abordagens

* Criação automática de mensagens personalizadas.
* Adaptação da comunicação ao segmento da empresa.
* Sugestões de argumentos comerciais.
* Follow-up assistido por IA.

### CRM Integrado

* Gestão de leads.
* Pipeline de vendas.
* Histórico de contatos.
* Controle de status da negociação.
* Dashboard de métricas.

## Casos de Uso

### Freelancer

Encontrar empresas que ainda não possuem site e oferecer serviços de desenvolvimento web.

### Agência Digital

Construir uma base contínua de potenciais clientes para prospecção ativa.

### Consultoria de Marketing

Identificar empresas com oportunidades de melhoria em SEO local, presença digital e geração de leads.

## Tecnologias

### Frontend

* React
* TypeScript
* Vite
* Tailwind CSS

### Backend

* Node.js
* Express
* TypeScript
* Prisma ORM

### Banco de Dados

* PostgreSQL

### Inteligência Artificial

* OpenAI API

### Infraestrutura

* Vercel
* Render
* Supabase

## Arquitetura

```text
+----------------------+
|   Fontes Públicas    |
+----------+-----------+
           |
           v
+----------------------+
| Coleta de Empresas   |
+----------+-----------+
           |
           v
+----------------------+
| Motor de Análise IA  |
+----------+-----------+
           |
           v
+----------------------+
| Classificação Leads  |
+----------+-----------+
           |
           v
+----------------------+
| CRM e Dashboard      |
+----------+-----------+
           |
           v
+----------------------+
| Prospecção Comercial |
+----------------------+
```

## Roadmap

### Fase 1

* Estrutura inicial do projeto.
* Banco de dados.
* Cadastro de leads.
* Dashboard inicial.

### Fase 2

* Integração com fontes de dados.
* Identificação de empresas sem site.
* Sistema de classificação de oportunidades.

### Fase 3

* Integração com IA.
* Geração automática de mensagens.
* Relatórios de análise.
* Download em PDF dos relatórios

### Fase 4

* CRM completo.
* Pipeline de vendas.
* Histórico de interações.

### Fase 5

* Automações de prospecção.
* Follow-up inteligente.
* Métricas avançadas.

## Estrutura do Projeto

```text
src/
├── app/
├── modules/
│   ├── dashboard/
│   ├── leads/
│   ├── crm/
│   ├── ai/
│   └── settings/
├── services/
├── shared/
│   ├── components/
│   ├── hooks/
│   ├── types/
│   └── utils/
└── styles/
```

## Visão de Longo Prazo

Transformar a prospecção comercial em um processo orientado por dados e inteligência artificial, permitindo que profissionais e empresas encontrem oportunidades de negócio de forma mais rápida, eficiente e escalável.

## Licença

Este projeto está licenciado sob a licença MIT.
