# 📘 Aula 03 — Modelos de Serviços em Nuvem (IaaS, PaaS, SaaS)

## 🎯 Objetivos da Aula
- Compreender os modelos de serviço em nuvem  
- Diferenciar IaaS, PaaS e SaaS  
- Entender responsabilidades em cada modelo  
- Identificar aplicações reais no mercado  

---

## ☁️ 1. Introdução

Os **modelos de serviço em nuvem** definem **o nível de abstração e responsabilidade entre o cliente e o provedor**.

➡️ Em outras palavras:
- O que o provedor gerencia  
- O que o cliente precisa gerenciar  

---

## 🧩 2. Visão Geral dos Modelos

Os três principais modelos são:

- **IaaS (Infrastructure as a Service)**  
- **PaaS (Platform as a Service)**  
- **SaaS (Software as a Service)**  

---

## 🏗️ 3. IaaS — Infrastructure as a Service

### 📌 Definição
O provedor oferece **infraestrutura virtualizada**, como:
- Servidores
- Redes
- Armazenamento

➡️ O cliente gerencia:
- Sistema operacional  
- Aplicações  
- Dados  

---

### 🔧 Características
- Alto nível de controle  
- Flexibilidade total  
- Base para outros modelos  

---

### ✅ Vantagens
- Controle total do ambiente  
- Escalabilidade  
- Personalização  

### ⚠️ Desvantagens
- Maior complexidade  
- Necessidade de conhecimento técnico  
- Gestão de sistema operacional  

---

### 🌍 Exemplos Reais



#### 🏢 AWS EC2
- Empresas criam máquinas virtuais sob demanda  

#### 🛒 Mercado Livre
- Usa IaaS para suportar picos de acesso  

#### 🎮 Empresas de jogos
- Criam servidores sob demanda para partidas online  

---

## ⚙️ 4. PaaS — Platform as a Service

### 📌 Definição
O provedor fornece uma **plataforma pronta para desenvolvimento**, incluindo:
- Sistema operacional  
- Middleware  
- Banco de dados  
- Ambiente de execução  

➡️ O cliente gerencia apenas:
- Código da aplicação  
- Dados  

---

### 🔧 Características
- Foco no desenvolvimento  
- Abstração da infraestrutura  
- Integração com serviços  

---

### ✅ Vantagens
- Aumento da produtividade  
- Redução de complexidade  
- Implantação rápida  

### ⚠️ Desvantagens
- Menor controle  
- Dependência da plataforma  
- Possível lock-in  

---

### 🌍 Exemplos Reais



#### 💻 Heroku
- Desenvolvedores fazem deploy de aplicações rapidamente  

#### 🧠 Google App Engine
- Aplicações escaláveis automaticamente  

#### 🚀 Startups
- Usam PaaS para acelerar desenvolvimento de produtos  

---

## 🖥️ 5. SaaS — Software as a Service

### 📌 Definição
O provedor entrega **software pronto para uso**, acessado via internet.

➡️ O cliente:
- Apenas utiliza o sistema  
- Não gerencia infraestrutura nem plataforma  

---

### 🔧 Características
- Acesso via navegador  
- Sem instalação local  
- Atualizações automáticas  

---

### ✅ Vantagens
- Facilidade de uso  
- Baixo custo inicial  
- Acesso remoto  

### ⚠️ Desvantagens
- Menor personalização  
- Dependência do fornecedor  
- Questões de privacidade  

---

### 🌍 Exemplos Reais



#### 📄 Google Docs
- Edição de documentos online  

#### 📊 Salesforce
- CRM totalmente em nuvem  

#### 🎬 Netflix
- Usuário consome software como serviço  

---

## 🧠 6. Comparação entre IaaS, PaaS e SaaS

| Camada              | IaaS        | PaaS        | SaaS        |
|---------------------|------------|------------|------------|
| Aplicações          | Cliente    | Cliente    | Provedor   |
| Dados               | Cliente    | Cliente    | Provedor   |
| Runtime             | Cliente    | Provedor   | Provedor   |
| Middleware          | Cliente    | Provedor   | Provedor   |
| Sistema Operacional | Cliente    | Provedor   | Provedor   |
| Infraestrutura      | Provedor   | Provedor   | Provedor   |

---

## 🔄 7. Analogia Simples

📌 Comparando com alimentação:

- **IaaS** → Você cozinha (controle total)  
- **PaaS** → Restaurante self-service (estrutura pronta)  
- **SaaS** → Delivery (tudo pronto)  

---

## ⚙️ 8. Uso Combinado na Prática

Empresas utilizam os modelos juntos:

- IaaS → Infraestrutura base  
- PaaS → Desenvolvimento de aplicações  
- SaaS → Ferramentas de negócio  

➡️ Exemplo:
- Backend em IaaS  
- APIs em PaaS  
- CRM em SaaS  

---

## 🔄 9. Síntese da Aula

- Os modelos definem **quem gerencia o quê**  
- Quanto mais alto o nível (SaaS), menor o controle  
- Quanto mais baixo (IaaS), maior a flexibilidade  

---

## 📚 10. Referências

### Bibliografia Básica
- CHEE, J. S. B.; JUNIOR, Franklin C.  
  *Computação em Nuvem – Cloud Computing Tecnologias e Estratégias*. São Paulo: M. Books, 2013.

- VERAS, Manoel  
  *Cloud Computing: Nova Arquitetura de TI*. Rio de Janeiro: Brasport, 2012.

- VERAS, Manoel  
  *Virtualização: Tecnologia Central do Datacenter*. Rio de Janeiro: Brasport, 2016.

### Bibliografia Complementar
- ANTUNES, L. J.  
  *Amazon AWS: Descomplicando a computação na nuvem*. São Paulo: Casa do Código, 2016.

- ARUNDEL, J.; DOMINGUS, J.  
  *DevOps Nativo de Nuvem com Kubernetes*. São Paulo: Novatec, 2019.

- MOLINARI, L.  
  *Cloud Computing: A inteligência na nuvem e seu novo valor em TI*. São Paulo: Érica, 2017.

- TAURION, Cesar  
  *Cloud Computing*. Rio de Janeiro: Brasport, 2009.