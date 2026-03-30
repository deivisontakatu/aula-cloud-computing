# 📘 Introdução à Computação em Nuvem

---

## ☁️ 1. Conceito de Computação em Nuvem

A **computação em nuvem (Cloud Computing)** é um modelo de entrega de recursos computacionais (como servidores, armazenamento, redes e software) por meio da internet.

➡️ Em vez de possuir infraestrutura física própria, as organizações utilizam recursos sob demanda, fornecidos por provedores.

### 📌 Definição (síntese conceitual)
Segundo a literatura (Veras, Taurion), computação em nuvem é:

> Um modelo que permite acesso sob demanda, via rede, a um conjunto compartilhado de recursos computacionais configuráveis, que podem ser rapidamente provisionados e liberados com mínimo esforço de gerenciamento.

---

## 🧠 2. Evolução da Computação em Nuvem

A nuvem não surgiu do nada — ela é resultado da evolução da computação:

### 🕰️ Linha evolutiva
- Mainframes (décadas de 60–70)
- Computação cliente-servidor
- Virtualização
- Computação distribuída
- Grid Computing
- Cloud Computing

### 💡 Ponto-chave:
A **virtualização** (VERAS, 2016) é a tecnologia central que possibilita a nuvem, permitindo múltiplos sistemas operacionais em um único hardware físico.

---

## 🧩 3. Características Essenciais da Computação em Nuvem

Segundo o NIST, essas características definem o funcionamento e os benefícios da computação em nuvem moderna.

---

### ⚙️ Autoatendimento sob demanda
O usuário pode provisionar recursos computacionais automaticamente, como servidores e armazenamento, sem interação com o provedor, usando painéis web ou APIs.

#### Exemplos
AWS EC2, Azure Virtual Machines, Google Compute Engine permitem criação instantânea de recursos sob demanda.

---

### 🌐 Amplo acesso à rede
Os serviços são acessíveis pela internet, utilizando dispositivos diversos como computadores, smartphones e tablets, garantindo mobilidade, padronização e interoperabilidade entre plataformas.

#### Exemplos
Acesso via navegador, apps mobile, APIs REST, integração com sistemas web corporativos.

---

### 🧱 Pool de recursos (Resource Pooling)
Os recursos do provedor são compartilhados entre múltiplos clientes (multi-tenant), com alocação dinâmica conforme demanda, garantindo eficiência e otimização da infraestrutura.

#### Exemplos
Data centers AWS, Google Cloud e Azure atendendo milhares de clientes simultaneamente.

---

### 📈 Elasticidade rápida
Capacidade de aumentar ou reduzir recursos automaticamente, conforme a demanda, muitas vezes de forma quase instantânea, garantindo desempenho e economia.

#### Exemplos
Auto Scaling AWS, Azure Scale Sets, Google Autoscaler ajustando servidores em tempo real.

---

### 📊 Serviço mensurável
O uso dos recursos é monitorado, controlado e cobrado conforme consumo, permitindo transparência, controle de custos e modelo pay-per-use eficiente.

#### Exemplos
Cobrança por hora de uso, armazenamento consumido, tráfego de dados ou requisições realizadas.

---

## 🏗️ 4. Arquitetura Conceitual da Nuvem

A nuvem é baseada em uma arquitetura que separa:

- **Front-end** → Interface do usuário  
- **Back-end** → Infraestrutura (servidores, armazenamento, rede)  

### Componentes principais:
- Datacenters
- Máquinas virtuais
- Sistemas de armazenamento distribuído
- Redes de alta disponibilidade

---

## 🧪 5. Virtualização: Base da Nuvem

A virtualização permite:

- Criar múltiplas máquinas virtuais (VMs)
- Otimizar uso de hardware
- Isolar ambientes

### 📌 Tipos principais:
- Virtualização de servidores
- Virtualização de armazenamento
- Virtualização de rede

➡️ Segundo VERAS (2016), ela é o elemento central do datacenter moderno.

---

## 🌐 6. Modelos de Implantação em Nuvem

### ☁️ Nuvem Pública
Infraestrutura compartilhada, acessível via internet, fornecida por terceiros, com alta disponibilidade global, escalabilidade dinâmica e modelo de pagamento sob demanda.

#### Empresas
AWS, Microsoft Azure, Google Cloud, IBM Cloud oferecem serviços amplos, como computação, armazenamento, inteligência artificial, redes e bancos de dados gerenciados.

#### Ferramentas
Docker para containers, Kubernetes para orquestração, Terraform para infraestrutura como código, além de serviços nativos como EC2, S3 e BigQuery.

#### Vantagens
Baixo custo inicial, rápida implementação, escalabilidade automática, acesso global facilitado, manutenção sob responsabilidade do provedor, ideal para startups e aplicações web.

---

### 🔒 Nuvem Privada
Infraestrutura dedicada a uma organização, podendo ser local ou hospedada, com alto controle, segurança reforçada e maior personalização dos recursos.

#### Empresas
VMware, Red Hat (OpenStack), Oracle Cloud oferecem soluções privadas robustas para empresas que exigem controle, compliance e alta proteção de dados.

#### Ferramentas
OpenStack para gerenciamento, VMware vSphere para virtualização, Ansible para automação, além de soluções de monitoramento e segurança avançadas corporativas.

#### Vantagens
Maior controle sobre dados, alta segurança, personalização completa, melhor adequação a normas regulatórias, ideal para bancos, governo e grandes empresas.

---

### 🔀 Nuvem Híbrida
Combinação de nuvem pública e privada, permitindo integração entre ambientes, balanceamento de cargas e maior flexibilidade operacional e estratégica.

#### Empresas
Microsoft Azure Arc, AWS Outposts, Google Anthos, IBM Hybrid Cloud permitem integração eficiente entre ambientes locais e serviços em nuvem pública.

#### Ferramentas
Kubernetes para multi-cloud, APIs para integração, VPN e conexões dedicadas, pipelines CI/CD para automação e gerenciamento distribuído de aplicações.

#### Vantagens
Flexibilidade, otimização de custos, segurança para dados sensíveis, escalabilidade combinada, ideal para empresas em transformação digital e migração gradual.

---

## ⚙️ 7. Benefícios da Computação em Nuvem

### ✔️ Técnicos
- Escalabilidade
- Alta disponibilidade
- Flexibilidade

### ✔️ Econômicos
- Redução de custos iniciais (CapEx → OpEx)
- Pagamento por uso

### ✔️ Operacionais
- Rapidez na implantação
- Foco no negócio (menos gestão de infraestrutura)

---

## ⚠️ 8. Desafios e Limitações

Apesar das vantagens, há desafios importantes:

- Segurança e privacidade
- Dependência de internet
- Lock-in de fornecedor
- Governança e compliance

---

## 🔄 9. Impacto na Área de TI

A computação em nuvem transforma o papel da TI:

### Antes:
- Foco em infraestrutura física  
- Alto custo de aquisição  

### Depois:
- Foco em serviços  
- TI como facilitadora do negócio  

➡️ Surge o conceito de:
- **TI como serviço (ITaaS)**  
- **DevOps e automação**

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
