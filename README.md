## Matheus Beneti

**Full stack — TypeScript, Go e Java · Arquitetura de sistemas distribuídos · IA aplicada ao desenvolvimento de software**

Trabalho onde o erro custa dinheiro: pagamento, risco e compliance. Não começo escrevendo — começo desenhando: fronteira, contrato entre serviços e comportamento sob falha definidos antes do código.

### 🟠 Portfólio

**[matheusbeneti.github.io/myPortfolio](https://matheusbeneti.github.io/myPortfolio/)**

Uma sala de agentes de IA em 3D, em tempo real e 100 % procedural — sem asset externo, sem vídeo, sem requisição a terceiros. Prova de trabalho, arquitetura e o CV em PDF estão lá.

### O que eu faço

**Arquitetura** — projeto para o dia ruim: escala horizontal em vez de máquina maior, falha contida onde nasceu, e segurança como restrição de projeto e não revisão no fim. Padrão consagrado em vez de invenção: outbox, idempotência, orientação a eventos, tempo-limite com repetição, fila-morta, invariante garantida no banco.

**IA aplicada** — o gargalo não é mais o modelo, é a infraestrutura em volta dele. Construí um sistema de **26 agentes** com servidor **MCP** próprio e **RAG** que audita segurança, compliance, performance e arquitetura a cada PR — com escopo de ferramenta declarado, teto de custo e resposta que cita arquivo e linha. Uso nas duas frentes: no código que eu escrevo e em software que já está rodando.

**As três pontas** — infraestrutura como código, o serviço que decide e a tela que a pessoa usa. Full stack não é a lista de tecnologias: é ter respondido pelas quatro camadas do mesmo sistema quando quebrou.

### Onde fiz

**Linka** · gateway de pagamentos regulado · dez/2025 – ago/2026
Sob **PCI DSS** e sob a régua do BACEN, onde a pergunta não é se o código funciona — é se você consegue provar que funciona, para um auditor, meses depois. Autor da API core em TypeScript, do serviço de PIX em Go, do ledger, do repositório de infraestrutura e das duas aplicações React. Operei produção: deploy, runbook e um incidente de severidade alta com post-mortem escrito. Medindo onde estava o teto real, derrubei a **CPU do banco de 87 % para 12 %** e o erro 503 de **82,6 % para 10,4 %**.

**CI&T** · setor de seguros · mar/2025 – atual
10 microsserviços Java com Spring Boot e Kafka, e referência técnica de IA do time. Um pipeline de LLM documentou um legado inteiro em uma semana.

### Stack

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)
![Python](https://img.shields.io/badge/Python-3670A0?style=flat-square&logo=python&logoColor=white)

![Node.js](https://img.shields.io/badge/Node.js-6DA55F?style=flat-square&logo=node.js&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white)
![Spring](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white)

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![DynamoDB](https://img.shields.io/badge/DynamoDB-4053D6?style=flat-square&logo=amazondynamodb&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Three.js](https://img.shields.io/badge/Three.js-000000?style=flat-square&logo=three.js&logoColor=white)

### Contato

[![Portfólio](https://img.shields.io/badge/Portfólio-8F5432?style=flat-square&logo=googlechrome&logoColor=white)](https://matheusbeneti.github.io/myPortfolio/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/matheusbeneti/)
[![E-mail](https://img.shields.io/badge/E--mail-111111?style=flat-square&logo=gmail&logoColor=white)](mailto:matheusbeneti3@gmail.com)

Último ano de Sistemas de Informação na **UFU**. Monte Carmelo – MG, remoto — **aberto a mudança de cidade e a trabalho presencial**.

---

<details>
<summary><b>English</b></summary>

**Full stack — TypeScript, Go and Java · Distributed systems architecture · AI applied to software development**

I work where mistakes cost money: payments, risk and compliance. I don't start by writing — I start by designing: boundaries, contracts between services and failure behaviour defined before the code.

**Portfolio:** [matheusbeneti.github.io/myPortfolio](https://matheusbeneti.github.io/myPortfolio/) — a real-time 3D room of AI agents, fully procedural, no external assets and no third-party requests.

**Architecture** — designed for the bad day: horizontal scale instead of a bigger machine, failures contained where they start, security as a design constraint rather than a review at the end.

**Applied AI** — the bottleneck is no longer the model, it's the infrastructure around it. I built a **26-agent** system with a custom **MCP** server and **RAG** that audits security, compliance, performance and architecture on every PR — declared tool scope, cost ceiling, and answers that cite file and line.

**Linka** · regulated payment gateway · Dec 2025 – Aug 2026 — under **PCI DSS** and Brazilian central bank rules. Author of the core API in TypeScript, the PIX service in Go, the ledger, the infrastructure repository and both React applications. Ran production: deploys, runbooks and a high-severity incident with a written post-mortem. Measuring where the real ceiling was, I took **database CPU from 87 % to 12 %** and 503 errors from **82.6 % to 10.4 %**.

**CI&T** · insurance sector · Mar 2025 – present — 10 Java microservices with Spring Boot and Kafka, and the team's technical reference for AI.

Final year of Information Systems at **UFU**. Open to relocation and on-site work.

</details>
