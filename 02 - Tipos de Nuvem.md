# 📘 Aula 02 — Tipos de Nuvem (Modelos de Implantação)

## 🎯 Objetivos da Aula
- Compreender os diferentes tipos de nuvem  
- Diferenciar nuvem pública, privada e híbrida  
- Identificar vantagens e desvantagens de cada modelo  
- Relacionar os tipos de nuvem com cenários reais  

---

## ☁️ 1. Introdução

Os **tipos de nuvem**, também chamados de **modelos de implantação**, definem **como a infraestrutura de computação em nuvem é disponibilizada e utilizada**.

➡️ Eles determinam:
- Quem pode acessar os recursos  
- Onde a infraestrutura está localizada  
- Como os recursos são compartilhados  

---

## 🧩 2. Classificação dos Tipos de Nuvem

Os principais modelos são:

- Nuvem Pública  
- Nuvem Privada  
- Nuvem Híbrida  

---

## 🌐 3. Nuvem Pública

### 📌 Definição
A **nuvem pública** é disponibilizada ao público em geral ou a múltiplas organizações, sendo operada por um provedor externo.

### 🔧 Características
- Infraestrutura compartilhada (multi-tenant)
- Acesso via internet
- Cobrança sob demanda (pay-per-use)
- Alta escalabilidade

### ✅ Vantagens
- Baixo custo inicial
- Alta elasticidade
- Facilidade de uso
- Rápida implantação

### ⚠️ Desvantagens
- Menor controle sobre a infraestrutura
- Dependência do provedor
- Possíveis preocupações com segurança

### 💡 Exemplos
- AWS (Amazon Web Services)
- Microsoft Azure
- Google Cloud Platform

---

## 🏢 4. Nuvem Privada

### 📌 Definição
A **nuvem privada** é utilizada exclusivamente por uma única organização.

### 🔧 Características
- Infraestrutura dedicada
- Pode ser interna (on-premises) ou externa (terceirizada)
- Maior controle e personalização

### ✅ Vantagens
- Maior segurança e controle
- Personalização de recursos
- Melhor adequação a requisitos legais

### ⚠️ Desvantagens
- Alto custo de implementação
- Necessidade de gestão interna
- Menor escalabilidade comparada à pública

---

## 🔗 5. Nuvem Híbrida

### 📌 Definição
A **nuvem híbrida** combina **nuvem pública e privada**, permitindo o compartilhamento de dados e aplicações entre elas.

### 🔧 Características
- Integração entre ambientes
- Flexibilidade operacional
- Balanceamento de cargas

### ✅ Vantagens
- Maior flexibilidade
- Otimização de custos
- Melhor controle de dados sensíveis

### ⚠️ Desvantagens
- Complexidade de gerenciamento
- Integração mais difícil
- Dependência de conectividade

---

## 🧠 6. Comparação entre os Tipos de Nuvem

| Característica        | Pública           | Privada            | Híbrida                |
|----------------------|------------------|--------------------|------------------------|
| Acesso               | Público          | Restrito           | Misto                  |
| Controle             | Baixo            | Alto               | Médio                  |
| Custo Inicial        | Baixo            | Alto               | Médio                  |
| Escalabilidade       | Alta             | Média              | Alta                   |
| Segurança            | Média            | Alta               | Alta (dependente)      |
| Complexidade         | Baixa            | Média              | Alta                   |


### 🌐 Nuvem Pública — Casos Reais


#### 🏢 Netflix (AWS)
- Utiliza **nuvem pública da AWS**
- Toda a plataforma de streaming roda na nuvem
- Usa elasticidade para lidar com picos de acesso

➡️ **Uso prático:**
- Escala automaticamente quando milhões de usuários assistem simultaneamente  
- Distribui conteúdo globalmente com alta disponibilidade  

---

#### 🛒 Mercado Livre (AWS / GCP)
- Utiliza múltiplas nuvens públicas
- Processa milhões de transações diariamente

➡️ **Uso prático:**
- Infraestrutura escalável para datas como Black Friday  
- Serviços distribuídos para reduzir latência  

---

#### 📱 Spotify (Google Cloud)
- Migrou sua infraestrutura para nuvem pública

➡️ **Uso prático:**
- Processamento de dados de usuários  
- Recomendação de músicas com machine learning  

---

### 🏢 Nuvem Privada — Casos Reais



#### 🏦 Bancos (ex: Itaú, Bradesco)
- Utilizam **nuvens privadas internas**
- Dados altamente sensíveis (financeiros)

➡️ **Uso prático:**
- Controle total sobre segurança e compliance  
- Processamento de transações bancárias  

---

#### 🏛️ Governo
- Órgãos públicos utilizam nuvem privada

➡️ **Uso prático:**
- Armazenamento de dados de cidadãos  
- Sistemas críticos (ex: saúde, impostos)

---

#### 🏭 Grandes indústrias
- Ambientes próprios para sistemas críticos

➡️ **Uso prático:**
- Sistemas de produção (ERP, MES)  
- Baixa latência e alta confiabilidade  

---

### 🔗 Nuvem Híbrida — Casos Reais



#### 🛍️ Magazine Luiza
- Usa modelo híbrido (on-premises + nuvem)

➡️ **Uso prático:**
- Sistemas críticos internos  
- Escalabilidade na nuvem em picos de vendas  

---

#### 🏦 Bancos modernos
- Misturam nuvem privada + pública

➡️ **Uso prático:**
- Dados sensíveis → nuvem privada  
- Aplicações digitais → nuvem pública  

---

#### 🏢 Empresas corporativas (ERP + Web)
- ERP interno + aplicações web na nuvem

➡️ **Uso prático:**
- Sistemas internos protegidos  
- Sites e apps escaláveis na nuvem  

---

### 🌐 Multi-Cloud — Casos Reais

#### 🛒 Amazon
- Usa múltiplos serviços internos e externos

#### 🏢 Empresas globais (ex: Uber)
- Utilizam mais de um provedor (AWS + GCP)

➡️ **Uso prático:**
- Evitar dependência de um único fornecedor  
- Melhor desempenho por região  

---

## 🧠 12. Resumo Prático (Visão de Mercado)

| Tipo de Nuvem | Exemplo Real        | Uso Principal                          |
|---------------|--------------------|----------------------------------------|
| Pública       | Netflix, Spotify   | Escalabilidade e distribuição global   |
| Privada       | Bancos, Governo    | Segurança e controle                   |
| Híbrida       | Magazine Luiza     | Equilíbrio entre custo e controle      |
| Multi-cloud   | Uber, Mercado Livre| Alta disponibilidade e flexibilidade   |

---

## 🎯 Insight Importante

➡️ **Na prática, poucas empresas usam apenas um tipo de nuvem.**

A tendência atual é:
- **Híbrida + Multi-cloud**
- Foco em **flexibilidade, custo e segurança**


---

## 🏗️ 7. Outros Modelos (Extensões)

Além dos modelos principais, existem variações:

### 🌍 Nuvem Comunitária
- Compartilhada por organizações com interesses comuns
- Ex: instituições governamentais ou educacionais

### 🌐 Multi-Cloud
- Uso de múltiplos provedores de nuvem pública
- Evita dependência de um único fornecedor (lock-in)

---

## ⚙️ 8. Critérios para Escolha do Tipo de Nuvem

A escolha depende de fatores como:

- Segurança da informação
- Regulamentações e compliance
- Orçamento disponível
- Necessidade de escalabilidade
- Capacidade técnica da equipe

---

## 🔄 9. Síntese da Aula

- A escolha do tipo de nuvem impacta diretamente a arquitetura de TI  
- Cada modelo possui vantagens e limitações  
- A tendência atual é o uso de **ambientes híbridos e multi-cloud**  

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
