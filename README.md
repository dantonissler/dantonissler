# 👨💻 Danton Issler Rodrigues  
**Tech Lead Pleno | Multicloud AWS & GCP | Produtos IA & Integrações | Pós-graduado em ML | Legal Tech**

💼 **Tech Lead Pleno** no [Ernesto Borges Advogados](https://www.ernestoborges.com.br/)  
🎓 Pós-graduado em Estatística, Analytics/IA, Modelagem Preditiva e Machine Learning  
🎓 Bacharel em Engenharia da Computação    
🎓 Técnico em Informática    
🚀 **7+ anos** construindo sistemas críticos para contencioso em massa  
🔧 **Stack atual:** Python/FastAPI · Angular/React · Supabase · AWS · GCP · **Terraform** · **GitHub Actions** / **Azure Pipelines**  

---

## 🔍 **Sobre Mim**
Líder técnico especializado em transformar complexidade jurídica em plataformas escaláveis em **arquitetura multicloud**:
- Frontends com **Angular**, **React.js**, Next.js e TypeScript
- Backend principal: **Python + FastAPI** (APIs, Lambdas, IA e automações) + Supabase
- **AWS (uso diário):** Lambda, SQS, S3, API Gateway, EventBridge, Step Functions, ECS, ECR, EC2, VPC, ALB, Target Groups, DocumentDB, Secrets Manager, IAM, CloudWatch
- **IaC & CI/CD:** infraestrutura com **Terraform** (AWS/GCP) · pipelines **GitHub Actions** e **Azure Pipelines**
- IA generativa, **RAG**, **MCP** e **Tabular Review** aplicados a produtos jurídicos em produção

📂 Repositórios da pós: [Pos-Machine-Learning](https://github.com/dantonissler/Pos-Machine-Learning) · [Pos-Analytics-IA](https://github.com/dantonissler/Pos-Analytics-IA) · [Lang-Graph-Examples](https://github.com/dantonissler/Lang-Graph-Examples) · [Pydantic-AI-Examples](https://github.com/dantonissler/Pydantic-AI-Examples)

---
## 🏆 **Destaques**  

### ☁️ **Multicloud & Arquitetura (2025–2026)**  
- **Tech Lead Pleno** liderando produtos em **AWS + GCP** no Ernesto Borges Advogados  
- **Centralizador de Cadastro**: React + Supabase + 10+ Lambdas + SQS + S3 + LLM (Gemini/Bedrock) — automação end-to-end de cadastro processual  
- **Migração ElawIO → MAX**: orquestrador **ECS Fargate** para **569k+ processos** — checkpoint, anti-duplicação SQS, Lambdas e modo incremental diário  
- **Plataforma Aderência**: API Gateway + WAF + VPC Link + ALB + **ECS** (Terraform, Azure Pipelines)  
- **ECS Terraform**: IaC do cluster **ECS Fargate** com ALB interno servindo dezenas de APIs jurídicas em produção  
- **AWS em produção:** Lambda, SQS, S3, API Gateway, EventBridge, Step Functions, ECS, ECR, EC2, VPC, ALB, Target Groups, DocumentDB, Secrets Manager, IAM, CloudWatch  
- **GCP em produção**: Cloud Run, Cloud SQL, Load Balancer, GCS, Pub/Sub, Secret Manager, KMS  
- **Gestão de Ativos Orion**: plataforma multi-tenant em **GCP** (Terraform) com **Clerk** (auth JWT/convites), Next.js 16, Fastify, Drizzle ORM e PostgreSQL  
- **IaC:** infraestrutura provisionada com **Terraform** (homolog/prod — AWS e GCP)  
- **CI/CD:** pipelines **GitHub Actions** e **Azure Pipelines** (build, testes, SonarQube, deploy ECS/Lambda)  

### 🚀 **Liderança & Estratégia**  
- Estruturei a área de Dados & IA do zero: padrões, governança e documentação integrada  
- Capacitei equipes para CI/CD e observabilidade (redução de 40% em incidentes pós-deploy)  
- Mentoria de 5+ desenvolvedores em 100+ projetos  

### 🤖 **Produtos de IA Generativa (RAG · MCP · Tabular Review)**  
- **Ernesto AI Platform**: produto completo de extração documental com **IA generativa** (Vertex AI/Gemini), **Tabular Review** para validação humana campo a campo, workflows multi-etapa e webhooks pós-revisão  
- **RAG** e **grounding**: extrações ligadas à fonte no documento; consulta contextual a PDFs e peças jurídicas  
- **MCP** (Model Context Protocol): integração de agentes com ferramentas e sistemas externos de forma padronizada  
- **Centralizador de Cadastro**: LLM + pipeline serverless (Lambda/SQS) com etapa de revisão antes do cadastro no MAX  
- Bot **Teams + GLPI** (Copilot Studio) — −40% consultas internas repetitivas  
- NLP para classificação automática de processos (Python + Transformers)  

### 📄 **Extração Documental com IA em Escala**  
- **100k+ documentos** processados com **RAG**, **Tabular Review** e **IA generativa** — extração estruturada de campos com validação humana  
- Pré-processamento em lote: split de PDFs (500 pág.), compressão Ghostscript (limite 50 MB), merge ordenado e **HTML→PDF** (Chrome headless)  
- **Pipeline JusBrasil → S3 → Ernesto AI**: webhook assíncrono (API Gateway + Lambda), download de anexos, junção de PDFs e extração via API com polling  
- **API Escavador V2**: atualização e classificação de processos arquivados/encerrados em lote (ThreadPool + polling)  
- Integração com **JusBrasil** (Digesto) e **Escavador** para enriquecer cadastro; **Google Drive** e **SharePoint** (Microsoft Graph) como fontes documentais  

### 🏢 **Gestão de Ativos Orion — GCP + Clerk**  
- Plataforma **multi-tenant** de desimobilização de ativos: jornada do cadastro à venda, catálogo público e RBAC por organização/regional  
- **Frontend:** Next.js 16, TypeScript, shadcn/ui, Tailwind CSS  
- **API:** Node.js, **Fastify**, **Drizzle ORM**, PostgreSQL 15  
- **Autenticação:** **Clerk** (JWT/JWKS, convites, webhooks; autorização e RBAC no backend)  
- **GCP (Terraform):** Cloud Run (API + frontend), Cloud SQL privado na VPC, Load Balancer HTTPS, GCS (URLs assinadas), Secret Manager, KMS, Pub/Sub, Cloud Functions  
- **CI/CD:** GitHub Actions + Workload Identity Federation → Artifact Registry → deploy Terraform  

### ⚖️ **Legal Ops, Integrações & Analytics**  
- **Atas JusBrasil**: arquitetura serverless (**EventBridge** → Lambda ingestão → **SQS** → Lambda processamento) com sumarização **NLP/OpenAI** e Supabase  
- **Classificação de publicações**: pipeline **MAX** + IA Tela + rastreabilidade em **Azure Blob** (Parquet) e MongoDB  
- **Validação de encerramento**: cruzamento **Escavador** × pauta **MAX** com justificativa automática de prazos e auditoria  

### 🔧 **DevOps & Entrega**  
- **CI/CD:** GitHub Actions + Azure Pipelines (build, testes, cobertura, SonarQube, deploy ECS/ECR/Lambda)  
- **IaC:** Terraform para AWS (Lambda, SQS, API Gateway, ECS) e GCP (Cloud Run, VPC, Cloud SQL)  
- Observabilidade: CloudWatch, Grafana + Prometheus  

---


## 📫 **Vamos Conversar?**  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/danton-issler-rodrigues-8ba01a115/)
[![Email](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:danton.issler18@gmail.com)
[![WhatsApp](https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](https://wa.me/556792466935)

<hr>

## 🛠 **Tecnologias Principais**  

### 🖥️ **Frontend**  
![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat&logo=angular&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=next.js&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind-06B6D4?style=flat&logo=tailwindcss&logoColor=white)

### ☁️ **Multicloud**  
![AWS](https://img.shields.io/badge/AWS-FF9900?style=flat&logo=amazon-aws&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=flat&logo=google-cloud&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat&logo=supabase&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=flat&logo=terraform&logoColor=white)

### ⚡ **AWS (uso diário)**  

**Compute:** Lambda · EC2 · ECS · ECR  

**Integração:** SQS · EventBridge · Step Functions · API Gateway  

**Rede:** VPC · ALB · Target Groups  

**Dados:** S3 · DocumentDB  

**Segurança & ops:** IAM · Secrets Manager · CloudWatch · Bedrock  

### 🌐 **GCP (produção)**  
Cloud Run · Cloud SQL · Load Balancer · GCS · Pub/Sub · Cloud Functions · Secret Manager

### ⚙️ **Backend (foco atual)**  
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=flat&logo=pydantic&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=node.js&logoColor=white)

### 🧠 **IA & Agentes**  
![Gemini](https://img.shields.io/badge/Vertex_AI-4285F4?style=flat&logo=google-cloud&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat&logo=langchain&logoColor=white)
![RAG](https://img.shields.io/badge/RAG-412991?style=flat&logo=openai&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-000000?style=flat&logo=protocol&logoColor=white)

**IA Generativa** · **RAG** · **MCP** · **Tabular Review** · LangGraph · Pydantic AI · Bedrock · Gemini

### 🐳 **DevOps & IaC**  
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=github-actions&logoColor=white)
![Azure DevOps](https://img.shields.io/badge/Azure_Pipelines-0078D7?style=flat&logo=azure-devops&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=flat&logo=terraform&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)

---

## Minhas Habilidades 🛠

> **🟢 Stack atual** = foco nos últimos 12 meses · **📜 Histórico** = experiência anterior mantida no perfil

### 🟢 Front-End · atual

<p>
    <img alt="Angular" src="https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white"/>
    <img alt="React" src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black"/>
    <img alt="Next.js" src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white"/>
    <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white"/>
    <img alt="TailwindCSS" src="https://img.shields.io/badge/Tailwind-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white"/>
    <img alt="Vite" src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white"/>
</p>

#### 📜 Histórico:

<p>
    <img alt="Bootstrap" src="https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white"/>
    <img alt="HTML5" src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white"/>
    <img alt="CSS" src="https://img.shields.io/badge/CSS-239120?style=for-the-badge&logo=css3&logoColor=white"/>
    <img alt="Sass" src="https://img.shields.io/badge/Sass-CC6699?style=for-the-badge&logo=sass&logoColor=white"/>
    <img alt="jQuery" src="https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white"/>
</p>

<hr/>

### 🟢 Back-End · atual

<p>
    <img alt="Python" src="https://img.shields.io/badge/Python-14354C?style=for-the-badge&logo=python&logoColor=white"/>
    <img alt="FastAPI" src="https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi"/>
    <img alt="Pydantic" src="https://img.shields.io/badge/Pydantic-E92063?style=for-the-badge&logo=pydantic&logoColor=white"/>
    <img alt="Node.js" src="https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white"/>
</p>

#### 📜 Histórico:

<p>
    <img alt="Java" src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white"/>
    <img alt="PHP" src="https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white"/>
    <img alt="C#" src="https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white"/>
    <img alt="Ruby" src="https://img.shields.io/badge/Ruby-CC342D?style=for-the-badge&logo=ruby&logoColor=white"/>
    <img alt="JavaScript" src="https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E"/>
    <img alt="BashScript" src="https://img.shields.io/badge/bash%20script-0101?style=flat&logo=gnubash&logoColor=%23FFFFFF&labelColor=%23000000"/>
</p>

<hr/>

### 🟢 Frameworks & IA · atual

<p>
    <img alt="FastAPI" src="https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi"/>
    <img alt="Angular" src="https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white"/>
    <img alt="React" src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black"/>
    <img alt="LangChain" src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white"/>
    <img alt="Vertex AI" src="https://img.shields.io/badge/Vertex_AI-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white"/>
    <img alt="Gemini" src="https://img.shields.io/badge/Gemini-8E75B2?style=for-the-badge&logo=google-gemini&logoColor=white"/>
    <img alt="Bedrock" src="https://img.shields.io/badge/AWS_Bedrock-FF9900?style=for-the-badge&logo=amazon-aws&logoColor=white"/>
</p>

<p>
    <img alt="RAG" src="https://img.shields.io/badge/RAG-412991?style=for-the-badge&logo=openai&logoColor=white"/>
    <img alt="MCP" src="https://img.shields.io/badge/MCP-000000?style=for-the-badge&logo=protocol&logoColor=white"/>
    <img alt="Tabular Review" src="https://img.shields.io/badge/Tabular_Review-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
    <img alt="LangGraph" src="https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white"/>
    <img alt="Pydantic AI" src="https://img.shields.io/badge/Pydantic_AI-E92063?style=for-the-badge&logo=pydantic&logoColor=white"/>
</p>

#### 📜 Histórico:

<p>
    <img alt="Spring" src="https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white"/>
    <img alt="Flask" src="https://img.shields.io/badge/flask-%23000.svg?style=for-the-badge&logo=flask&logoColor=white"/>
    <img alt="Django" src="https://img.shields.io/badge/django-%23092E20.svg?style=for-the-badge&logo=django&logoColor=white"/>
    <img alt="Laravel" src="https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white"/>
</p>

<hr/>

### 🟢 Banco de Dados · atual

<p>
    <img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white"/>
    <img alt="Supabase" src="https://img.shields.io/badge/Supabase-3FCF8E?style=for-the-badge&logo=supabase&logoColor=white"/>
    <img alt="DocumentDB" src="https://img.shields.io/badge/DocumentDB-4053D6?style=for-the-badge&logo=mongodb&logoColor=white"/>
    <img alt="MongoDB" src="https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white"/>
</p>

#### 📜 Histórico:

<p>
    <img alt="MySQL" src="https://img.shields.io/badge/MySQL-00000F?style=for-the-badge&logo=mysql&logoColor=white"/>
    <img alt="SQL Server" src="https://img.shields.io/badge/Microsoft_SQL_Server-CC2927?style=for-the-badge&logo=microsoft-sql-server&logoColor=white"/>
    <img alt="MariaDB" src="https://img.shields.io/badge/MariaDB-01529E?style=for-the-badge&logo=mariadb&logoColor=white"/>
    <img alt="Firebase" src="https://img.shields.io/badge/Firebase-F29D0C?style=for-the-badge&logo=firebase&logoColor=white"/>
    <img alt="Redis" src="https://img.shields.io/badge/redis-%23DD0031.svg?style=for-the-badge&logo=redis&logoColor=white"/>
</p>

<hr/>

### 🟢 Cloud · atual

<p>
    <img alt="AWS" src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white"/>
    <img alt="GCP" src="https://img.shields.io/badge/GCP-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white"/>
    <img alt="Azure" src="https://img.shields.io/badge/Azure-0089D6?style=for-the-badge&logo=microsoft-azure&logoColor=white"/>
    <img alt="Supabase" src="https://img.shields.io/badge/Supabase-3FCF8E?style=for-the-badge&logo=supabase&logoColor=white"/>
    <img alt="Terraform" src="https://img.shields.io/badge/Terraform-844FBA?style=for-the-badge&logo=terraform&logoColor=white"/>
</p>

<p>
    <img alt="Lambda" src="https://img.shields.io/badge/AWS_Lambda-FF9900?style=flat&logo=aws-lambda&logoColor=white"/>
    <img alt="SQS" src="https://img.shields.io/badge/Amazon_SQS-FF9900?style=flat&logo=amazon-aws&logoColor=white"/>
    <img alt="S3" src="https://img.shields.io/badge/Amazon_S3-569A31?style=flat&logo=amazon-s3&logoColor=white"/>
    <img alt="ECS" src="https://img.shields.io/badge/Amazon_ECS-FF9900?style=flat&logo=amazon-ecs&logoColor=white"/>
    <img alt="EC2" src="https://img.shields.io/badge/Amazon_EC2-FF9900?style=flat&logo=amazon-ec2&logoColor=white"/>
    <img alt="API Gateway" src="https://img.shields.io/badge/API_Gateway-FF9900?style=flat&logo=amazon-api-gateway&logoColor=white"/>
    <img alt="EventBridge" src="https://img.shields.io/badge/EventBridge-FF9900?style=flat&logo=amazon-eventbridge&logoColor=white"/>
    <img alt="Step Functions" src="https://img.shields.io/badge/Step_Functions-FF9900?style=flat&logo=aws-step-functions&logoColor=white"/>
    <img alt="VPC" src="https://img.shields.io/badge/Amazon_VPC-FF9900?style=flat&logo=amazon-vpc&logoColor=white"/>
    <img alt="ALB" src="https://img.shields.io/badge/ALB-FF9900?style=flat&logo=amazon-aws&logoColor=white"/>
    <img alt="CloudWatch" src="https://img.shields.io/badge/CloudWatch-FF9900?style=flat&logo=amazon-cloudwatch&logoColor=white"/>
    <img alt="Cloud Run" src="https://img.shields.io/badge/Cloud_Run-4285F4?style=flat&logo=google-cloud&logoColor=white"/>
    <img alt="Cloud SQL" src="https://img.shields.io/badge/Cloud_SQL-4285F4?style=flat&logo=google-cloud&logoColor=white"/>
</p>

#### 📜 Histórico:

<p>
    <img alt="Heroku" src="https://img.shields.io/badge/Heroku-430098?style=for-the-badge&logo=heroku&logoColor=white"/>
    <img alt="Locaweb" src="https://img.shields.io/badge/Locaweb-2E3192?style=for-the-badge&logo=cloudflare&logoColor=white"/>
</p>

<hr/>

### 🟢 DevOps & IaC · atual

<p>
    <img alt="GitHub Actions" src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white"/>
    <img alt="Azure Pipelines" src="https://img.shields.io/badge/Azure_Pipelines-0078D7?style=for-the-badge&logo=azure-devops&logoColor=white"/>
    <img alt="Terraform" src="https://img.shields.io/badge/Terraform-844FBA?style=for-the-badge&logo=terraform&logoColor=white"/>
    <img alt="Docker" src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
    <img alt="Kubernetes" src="https://img.shields.io/badge/Kubernetes-326DE6?style=for-the-badge&logo=kubernetes&logoColor=white"/>
    <img alt="SonarQube" src="https://img.shields.io/badge/SonarQube-4E9BCD?style=for-the-badge&logo=sonarqube&logoColor=white"/>
    <img alt="Git" src="https://img.shields.io/badge/Git-E34F26?style=for-the-badge&logo=git&logoColor=white"/>
</p>

#### 📜 Histórico:

<p>
    <img alt="Jenkins" src="https://img.shields.io/badge/Jenkins-D33833?style=for-the-badge&logo=jenkins&logoColor=white"/>
    <img alt="Apache" src="https://img.shields.io/badge/Apache-CA2136?style=for-the-badge&logo=apache&logoColor=white"/>
    <img alt="Nginx" src="https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white"/>
    <img alt="Grafana" src="https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white"/>
    <img alt="Prometheus" src="https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white"/>
</p>

<hr/>

### 📜 Sistemas Operacionais · histórico e atual

<p>
    <img alt="Linux" src="https://img.shields.io/badge/Linux-E34F26?style=for-the-badge&logo=linux&logoColor=black"/>
    <img alt="Ubuntu" src="https://img.shields.io/badge/Ubuntu-35495E?style=for-the-badge&logo=ubuntu&logoColor=2CA5E0"/>
    <img alt="Debian" src="https://img.shields.io/badge/Debian-D70A53?style=for-the-badge&logo=debian&logoColor=white"/>
    <img alt="Windows" src="https://img.shields.io/badge/Windows-017AD7?style=for-the-badge&logo=windows&logoColor=white"/>
</p>
