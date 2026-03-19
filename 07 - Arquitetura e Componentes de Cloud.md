# 📘 Aula 07 — Arquitetura e Componentes de Cloud Computing

## 🎯 Objetivos da Aula
- Compreender a arquitetura da computação em nuvem  
- Identificar os principais componentes da nuvem  
- Entender a organização de datacenters e serviços  
- Relacionar arquitetura com escalabilidade e desempenho  

---

## ☁️ 1. Introdução

A **arquitetura de computação em nuvem** define como os recursos são organizados, distribuídos e disponibilizados aos usuários.

➡️ Ela é responsável por:
- Garantir escalabilidade  
- Assegurar disponibilidade  
- Permitir flexibilidade  

---

## 🧩 2. Visão Geral da Arquitetura

A arquitetura de nuvem é composta por dois grandes blocos:

### 🖥️ Front-end
- Interface com o usuário  
- Aplicações cliente  
- Navegadores e APIs  

---

### 🏗️ Back-end
- Infraestrutura de nuvem  
- Servidores  
- Armazenamento  
- Redes  

---

## 🏗️ 3. Componentes Principais

---

### 🖥️ 3.1 Datacenter

### 📌 Definição
Local físico onde estão os servidores e equipamentos.

### 🔧 Características
- Alta disponibilidade  
- Redundância  
- Controle de temperatura e energia  

---

### 💻 3.2 Servidores

- Responsáveis pelo processamento  
- Podem ser físicos ou virtuais  

---

### 📦 3.3 Armazenamento

### 📌 Tipos
- **Bloco** → discos virtuais  
- **Arquivo** → sistemas de arquivos  
- **Objeto** → armazenamento escalável (ex: S3)  

---

### 🌐 3.4 Rede

- Conectividade entre recursos  
- Balanceamento de carga  
- Segurança de tráfego  

---

### 🧠 3.5 Virtualização

- Abstração de hardware  
- Criação de máquinas virtuais  

---

### ⚙️ 3.6 Containers e Orquestração

- Containers (ex: Docker)  
- Orquestradores (ex: Kubernetes)  

➡️ Permitem:
- Escalabilidade  
- Deploy automatizado  

---

### 🔐 3.7 Segurança

- Controle de acesso (IAM)  
- Criptografia  
- Firewalls  

---

## 🌍 4. Camadas da Arquitetura de Nuvem

---

### 🏗️ Infraestrutura (IaaS)
- Servidores  
- Redes  
- Armazenamento  

---

### ⚙️ Plataforma (PaaS)
- Ambiente de desenvolvimento  
- Middleware  
- Banco de dados  

---

### 🖥️ Aplicação (SaaS)
- Software final para o usuário  

---

## 🔄 5. Alta Disponibilidade e Redundância

### 📌 Conceitos
- Regiões (Regions)  
- Zonas de disponibilidade (AZs)  

➡️ Objetivo:
- Evitar falhas  
- Garantir continuidade do serviço  

---

## ⚖️ 6. Balanceamento de Carga

### 📌 Definição
Distribuição de tráfego entre múltiplos servidores.

### 🎯 Benefícios
- Melhor desempenho  
- Evita sobrecarga  
- Alta disponibilidade  

---

## 📊 7. Escalabilidade

### 📌 Tipos
- **Vertical** → aumentar recursos de um servidor  
- **Horizontal** → adicionar mais servidores  

---

## 🌐 8. Arquitetura Distribuída

- Recursos distribuídos geograficamente  
- Uso de CDNs (Content Delivery Networks)  

➡️ Benefícios:
- Redução de latência  
- Melhor experiência do usuário  

---

## 🌍 9. Exemplos Reais

---

### ☁️ AWS
- Regiões globais  
- Serviços como EC2, S3, VPC  

---

### 🌐 Google Cloud
- Forte uso de containers (Kubernetes)  

---

### 🏢 Microsoft Azure
- Integração com ambientes corporativos  

---

## ⚙️ 10. Boas Práticas de Arquitetura

- Uso de múltiplas zonas de disponibilidade  
- Implementação de backup  
- Monitoramento contínuo  
- Automação de recursos  
- Arquitetura resiliente  

---

## 🔄 11. Síntese da Aula

- A arquitetura de nuvem é composta por múltiplos componentes integrados  
- Front-end e back-end estruturam o sistema  
- Datacenters, rede, armazenamento e virtualização são fundamentais  
- Escalabilidade e disponibilidade são objetivos centrais  

---

## 📚 12. Referências

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