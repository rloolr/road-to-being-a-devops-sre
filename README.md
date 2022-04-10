# Trilha básica para atuar como DevOps 2021

## Objetivos deste documento

A ideia desta página é descrever de forma **básica** ferramentas e conceitos para ser possível atuar como DevOps / SRE hoje no mercado de TI.

Todo o conteúdo que coloco aqui foram ferramentas, cursos, livros que estudei até hoje e o que vejo ser usado nas maiorias das Empresas. Existem muito mais ferramentas no mercado, mas as que menciono aqui já trará uma boa estrutura para boas oportunidades.

Para ter uma ideia de qual nível de conhecimento é necessário para participar de uma oportunidade de DevOps / SRE tenha em mente algo do tipo:

### Nível Júnior

Para uma oportunidade de **Júnior** ou mesmo **Pleno nível I**, entendo que tentar possuir o máximo de conhecimento indicado como **ideal** na tabela de classificação do **Bloco 1** informado abaixo lhe dará ampla vantagem ao nível de conhecimento técnico que é geralmente solicitado nas descrições das vagas e também será a sua principal base para todos os outros níveis.

| Etapa | Domínio |
| --------  | -------- |
| Bloco 1 - Etapa 1 | - Min: Domínio total de 50% dos itens mencionados </p> - Ideal: Domínio total de 80% dos itens mencionados |
| Bloco 1 - Etapa 2 | - Min: Domínio total de 30% dos itens mencionados </p> - Ideal: Domínio total de 60% dos itens mencionados |
| Bloco 1 - Etapa 3 | - **Nginx** Min: Domínio total de 50% de conhecimento na ferramenta </p> - **Nginx** Ideal: Domínio total de 80% de conhecimento na ferramenta </p> --- </p> - **Apache** Min: Domínio total de 30% de conhecimento na ferramenta </p> - **Apache** Ideal: Domínio total de 50% de conhecimento na ferramenta |
| Bloco 1 - Etapa 4 | - **AWS** Min: Curso AWS Practitioner </p> - **AWS** Ideal: Certificação AWS Practitioner </p> --- </p> - **Azure** Min: Curso AZ-900 </p> - **Azure** Ideal: Certificação AZ-900 </p> |
| Bloco 1 - Etapa 5 | - Min: Domínio Mínimo de 50% da ferramenta </p> - Ideal: Domínio Mínimo de 80% da ferramenta |
| Bloco 1 - Etapa 6 | - Min: Domínio total de 50% dos itens mencionados </p> - Ideal: Domínio total de 80% dos itens mencionados |

## Caminhos de desenvolvimento

### Bloco 1 - Etapa 1: Operating Systems & Linux Basics

- Comandos básicos de Shell
- Dominar ao máximo a ferramenta vi / vim
- Ferramentas para manipular textos (awk, sed, grep, egrep, fgrep, sort, uniq, cat, cut, echo, fmt, tr, nl, wc, Less, more, tac)
- Ferramentas para monitoramento de processos (ps, top, htop, atop, lsof)
- Ferramentas para thsoot de redes (nmap, tcpdump, ping, mtr, traceroute, dig, airmon, airodump, iptables, netstat)
- Ferramentas para analise de performance de sistemas (nmon, iostat, sar, vmstat)
- Outras ferramentas (find, tar, gz, zip, unzip, bz2, strace, dtrace, systemtap, uname, df)
- Criar e Entender Linux File System
- SSH Key Management

> **Recomendação para estudos:** Overview do conteúdo [Linux Essentials](https://www.lpi.org/our-certifications/linux-essentials-overview) e Curso [Linux Essetials](https://www.udemy.com/course/lpi-linux-essentials/) e de [Shell Script](https://www.udemy.com/course/shell-script-do-basico-ao-profissional/)

### Bloco 1 - Etapa 2: Networking & Security

- Configurações básicas de firewalls
- Conhecimento sobre Camada OSI
- Entender sobre IP addresses, CIDRs subnets, portas, protocolos e DNS
- Load Balancers
- Proxy Server
- Proxy Reversos
- HTTP/HTTPS
- SSL e TLS
- Port Forwarding

### Bloco 1 - Etapa 3: WebServers

- Nginx
- Apache
- IIS

> **Dica:** Focar em configuração de SSL TLS para cada WebServer acima, pois hoje tudo tem que ter certificado nem que seja Let's Encrypt. Tente dominar instalações, configurações e alguns tshoots da ferramenta e de certificados.

### Bloco 1 - Etapa 4: Public Cloud Provider

- AWS
- Azure
- GCP

> **Obs.:** Escolha como principal AWS ou Azure e aprenda ao máximo, e tenha conhecimento suficiente na segunda opção como backup técnico.

### Bloco 1 - Etapa 5: Ferramenta para controle de versão

- GIT

> **Obs.:** O seu nível de conhecimento nesta ferramenta deverá ser de no mínimo 50%, pois ela será a sua ferramenta principal para versionar tudo o que for código para as próximas etapas.

**Materiais de apoio:**

- [Pro Git (English Edition)](https://www.amazon.com.br/gp/product/B01ISNIKES)
- [Ry's Git Tutorial (English Edition)](https://www.amazon.com.br/gp/product/B00QFIA5OC)

> **Dica:** Após ter conhecimentos sólidos em Git, tente estudar sobre Git Flow.

### Bloco 1 - Etapa 6: Linguagens para estruturar Dados e informações

- Yaml
- Json
- XML
- Markdown

> **Obs.:** Focar no aprendizado de Yaml e Json para trabalhar com a maior quantidade de arquivos de configurações, XML para alguns cenários que ainda utilizam e entender bastante sobre Markdown para criações e sustentações de documentações.

### Etapa 7 - IaC e Gerência de Configurações

- Terraform
- Ansible
- Baseado na Etapa 4, estude CloudFormation ou Azure Resource Manager

### Etapa 8 - Containers

- [Docker](https://docs.docker.com/)
- [Containerd](https://containerd.io/docs/)
- [Crio](https://cri-o.io/)
- [Podman](https://podman.io/)

> **Obs.:** Focar no aprendizado de Containers será muito importante para a próxima Etapa.</p>
**Dica:** Dedique maior esforço no aprendizado de Docker e ao se sentir confortavel dedique um tempo ao Containerd. Com o passar do tempo vá conhecendo as outras opções de mercado.

### Etapa 9 - Orquestradores / Gerenciadores de containers

- Kubernetes
- Docker Swarm
- AWS ECS (Caso tenha escolhido AWS na Etapa 4)
- Rancher

> **Obs.:** Dedique mais estudos a Kubernetes pois é a ferramenta mais usada atualmente, mas tenha conhecimento em Swarm pois há casos de ambientes que ainda o utilizam como solução.</p>
> **Dica:** Utilizar material de CKAD no primeiro momento irá ajudar muito a entender e atuar com Kubernetes.

### Etapa 10 - Ferramentas de CICD

- Jenkins
- Gitlab CI
- Github Actions
- Bitbucket

> **Obs.:** Estas ferramentas são as mais presentes nas empresas atualmente

### Etapa 11 - Monitoramento de Infraestrutura

- Zabbix
- Prometheus
- AWS CloudWatch
- Grafana

### Etapa 12 - Monitoramento de Aplicações (APM)

- New Relic
- Jaeger

### Etapa 13 - Log Management

- ELK
- Graylog
- Splunk

### Etapa 14 - Scripting Language

- Python
- Golang
- Shell Script
- Powershell

### Etapa 15 - Aprender sobre Metodologias Ágeis e Cultura DevOps

- [EXIN Agile Scrum Foundation](https://academy.estabil.is/courses/exin-agile-scrum-foundation)
- [DevOps Foundation](https://academy.estabil.is/courses/devops-foundation)
- Para quem possui assinatura premium do Linkedin pode fazer o curso [Become a DevOps Engineer](https://www.linkedin.com/learning/paths/become-a-devops-engineer)

### Etapa 16 - Leituras complementares

> **Obs.:** Essa lista eu busquei em minha conta, se for adquirir algum deles, verifique se há alguma versão mais atualizada.

**Essenciais:**

- [O Projeto Fênix: Um romance sobre TI, DevOps e sobre ajudar o seu negócio a vencer](https://www.amazon.com.br/Projeto-F%C3%AAnix-romance-DevOps-neg%C3%B3cio-ebook/dp/B08FLDJJ7M/ref=sr_1_7)
- [Manual De DevOps: Como obter agilidade, confiabilidade e segurança em organizações tecnológicas](https://www.amazon.com.br/Manual-DevOps-confiabilidade-organiza%C3%A7%C3%B5es-tecnol%C3%B3gicas-ebook/dp/B08DR7861Y/ref=sr_1_1)
- [DevOps na prática: Entrega de software confiável e automatizada](https://www.amazon.com.br/DevOps-pr%C3%A1tica-software-confi%C3%A1vel-automatizada-ebook/dp/B00VRS7WRS/ref=sr_1_2)
- [Site Reliability Engineering: How Google Runs Production Systems (English Edition)](https://www.amazon.com.br/Site-Reliability-Engineering-Production-Systems-ebook/dp/B01DCPXKZ6/ref=sr_1_1)
- [Ansible for DevOps: Server and configuration management for humans (English Edition)](https://www.amazon.com.br/gp/product/B08FBLVVFG)

**Bom para complementar estudos e ter ideias:**

- [The Site Reliability Workbook: Practical Ways to Implement SRE (English Edition)](https://www.amazon.com.br/Site-Reliability-Workbook-Practical-Implement-ebook/dp/B07FWFPMYG/ref=sr_1_3)
- [97 Things Every SRE Should Know: Collective Wisdom from the Experts (English Edition)](https://www.amazon.com.br/Things-Every-SRE-Should-Know-ebook/dp/B08P2CP1FK)
- [DevOps and Site Reliability Engineering (SRE) Handbook : Non-Programmer’s Guide ( Second Edition) (English Edition)](https://www.amazon.com.br/DevOps-Site-Reliability-Engineering-Handbook-ebook/dp/B07KSK1GMK)
- [Lean Inception: Como Alinhar Pessoas e Construir o Produto Certo](https://www.amazon.com.br/gp/product/B07NBH3FHQ)
- [Scrum e Métodos Ágeis: Um Guia Prático](https://www.amazon.com.br/gp/product/B01LBSPIAG)
- [SCRUM em equipes de Infraestrutura: Relatos práticos de um gerente de TI Jonas Salengue](https://www.amazon.com.br/gp/product/B01M10DDR4)
- [O que é DevOps?: Colaboração como caminho para entregar valor ao negócio](https://www.amazon.com.br/gp/product/B01BXUKU7I)
- [DevOps & Microservices Handbook: Non-Programmer’s Guide to DevOps and Microservices (English Edition)](https://www.amazon.com.br/gp/product/B07CRJDL6C)
- [TimeDev - Muito mais do que código](https://www.amazon.com.br/gp/product/B096W4SJHM)

**Caso sua opção tenha sido AWS na Etapa 4 essa leitura é fundamental:**

- [AWS Well-Architected Framework (AWS Whitepaper) (English Edition)](https://www.amazon.com.br/gp/product/B08CFW9PXN)

### Etapa 17 - Entender conceitos sobre Software Development

- Conhecer os Git Workflows usados por desenvolvedores
- Tipo de ambientes usados atualmente em uso pelos desenvolvedores (Prod, Staging, Developer, etc)
- Ferramentas de testes mais utilizadas atualmente