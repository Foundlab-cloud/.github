<div align="center">
  <h1 style="font-size: 3em; font-weight: bold;">FoundLab</h1>
  <h2>Infraestrutura de Confiança Computacional Auditável</h2>
  <p><em>Uma startup do <strong>Google for Startups Cloud Program</strong>, operando com uma stack de alta performance para o setor financeiro.</em></p>

  <div>
    <img src="https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white" alt="Google Cloud" />
    <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white" alt="Kubernetes" />
    <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
    <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React" />
    <img src="https://img.shields.io/badge/NVIDIA-76B900?style=for-the-badge&logo=nvidia&logoColor=white" alt="NVIDIA" />
  </div>
</div>

<div align="center">  
  <a href="https://ibb.co/ccj8Mdky"><img src="https://i.ibb.co/ccj8Mdky/LOGO-OK1.png" alt="LOGO-OK1" border="0"></a>
</div>  

---

## Plataforma Umbrella: Análise de Portfólio com IA

A **Plataforma IA** em questão, denominada Umbrella — Plataforma de Análise de Portfólio com IA**), é uma **plataforma inteligente de análise de documentos** projetada para transformar documentos não estruturados em *insights* acionáveis e confiáveis. Sua missão é capacitar analistas financeiros a se dedicarem à tomada de decisões estratégicas, enquanto a tecnologia gerencia a tarefa de dados com precisão e confiabilidade sem precedentes.

### Visão e Proposta de Valor

A visão da FoundLab reside na **agilidade e exatidão** no cenário financeiro, onde analistas despendem muitas horas na extração e validação manual de dados de documentos complexos, como DREs e balanços. A plataforma aborda essa questão com um motor de análise inteligente, robusto e auto-verificável. Sua **proposta de valor** otimiza a análise de documentos com inovação e segurança, oferecendo:

* Um **pipeline multietapas** que transforma dados brutos em decisões informadas, desde o *parser* avançado até a síntese executiva, resultando em um veredito claro e próximos passos objetivos.
* **Privacidade por Design**, garantindo a proteção de informações sensíveis através da **zero persistência de documentos sensíveis**, processando dados exclusivamente em memória e descartando-os após o uso. A retenção é limitada a metadados não sensíveis para rastreabilidade e transparência.
* **Resiliência Antifrágil**, com uma arquitetura que não apenas resiste a falhas, mas se torna mais robusta sob estresse, utilizando mecanismos como *throttling*, *healthchecks* contínuos e *retries* automáticos. Há também um *fallback* de modelo/infra, incluindo uso de GPU para cargas pesadas.
* **Auditabilidade Total**, rastreando e verificando cada etapa do processo através de um **DecisionID** exclusivo para cada análise, logs detalhados e pacotes de auditoria com carimbo de tempo.
* **Integração Simples** via API robusta (REST e GraphQL), exportação em formatos como CSV, PDF e JSON, e opções *white-label* para personalização.

### Como Funciona: Pipeline de Processamento de Documentos

A FoundLab opera através de um pipeline institucional robusto e altamente eficiente para o processamento de documentos digitais. Esse pipeline é composto por estágios multifacetados:

1. **Ingestão:** Recebimento e incorporação de documentos de diversas proveniências, com controle de qualidade para garantir a fidelidade dos dados.
2. **Parsing:** Decomposição da estrutura do documento, identificando e categorizando elementos como parágrafos, títulos, listas e tabelas. Para documentos não estruturados, pode envolver reconhecimento de padrões e IA para inferir a estrutura lógica.
3. **Extração:** Identificação e isolamento de informações-chave e entidades relevantes, utilizando técnicas como Reconhecimento Óptico de Caracteres (OCR) para imagens/documentos digitalizados, Processamento de Linguagem Natural (PLN) e algoritmos de aprendizado de máquina.
4. **Validação:** Verificação rigorosa da qualidade e conformidade dos dados extraídos com regras de negócios predefinidas e critérios de integridade.
5. **Pontuação (Score):** Atribuição de um valor ou nível de relevância a cada documento e às informações extraídas, com base em critérios como completude, consistência e conformidade.
6. **Geração de Evidências (Veritas):** Criação de um registro imutável de cada etapa do processo (ingestão, *parsing*, extração, validação) com carimbos de tempo e *hashes* criptográficos, garantindo rastreabilidade e transparência.
7. **Identidade Reputacional (SDID):** Geração de um perfil abrangente para cada documento, refletindo sua origem, histórico de processamento e confiabilidade intrínseca, atuando como um selo de qualidade dinâmico.

A plataforma lida com **documentos em PDF** (extração de texto e metadados), **imagens** (com OCR avançado) e **arquivos HTML** (extraindo informações estruturadas). A força da FoundLab reside na sua capacidade de **integrar e normalizar dados** de diversas fontes, padronizando-os para análise, otimizando fluxos de trabalho e aprimorando a tomada de decisões.

### Lógica de IA Avançada e Motores de IA

A **Inteligência Artificial (IA Ops)** é o coração da FoundLab, impulsionada pelo **modelo Gemini** do Google. Ela é totalmente integrada a todos os módulos da plataforma e permite personalização profunda para atender às necessidades específicas de cada cliente. As funções essenciais da IA incluem:

* **Coleta e Análise de Dados Automatizada e Inteligente:** Automatiza a coleta de informações de diversas fontes, identifica padrões complexos, detecta anomalias e revela oportunidades ocultas em tempo real.
* **Painéis de Controle Interativos e Acionáveis:** Transforma *insights* da IA em representações visuais claras e personalizáveis, permitindo explorar dados em diferentes granularidades.
* **Geração de Relatórios Personalizados e Sob Demanda:** Cria automaticamente diversos tipos de relatórios (operacionais, estratégicos, de conformidade, desempenho).
* **Automatização de Fluxos de Trabalho Inteligente:** Identifica gargalos e otimiza processos de negócios, automatizando tarefas repetitivas.
* **Alertas e Notificações Inteligentes e Proativas:** Monitora continuamente os dados e envia alertas contextuais e acionáveis sobre eventos significativos, desvios ou riscos potenciais.

A IA da FoundLab é construída sobre quatro pilares tecnológicos:

* **Processamento de Linguagem Natural (PNL):** Decifra e interpreta vastos volumes de dados textuais para extrair *insights* valiosos, automatizando análises complexas.
* **Machine Learning (ML):** Modelos que aprendem e aprimoram continuamente, fornecendo recomendações personalizadas e otimizando processos de forma autônoma.
* **Visão Computacional (VC):** Analisa imagens/vídeos para identificação automática de padrões, objetos e anomalias visuais.
* **Análise Preditiva e Prescritiva:** Prevê cenários futuros e prescreve ações específicas para alcançar os melhores resultados.

Seus **motores de IA (Core Engines)** incluem:

* **Cognitive Orchestrator:** Gerencia a orquestração de *prompts* e agentes de IA, com um *critic-loop* para validação sintática e semântica, e *guardrails* éticos e regulatórios.
* **Parser de Precisão:** Extrai informações robustamente de tabelas e indicadores de documentos PDF (nacionais e internacionais), convertendo-os em JSON canônico.
* **Analista Granular (CFA Persona):** Emula um analista financeiro, realizando avaliações detalhadas por ativo, considerando risco, volatilidade, liquidez, *rating* e eventos.
* **Estratega Chefe:** Consolida informações para oferecer recomendações táticas e estratégicas, analisando concentração de portfólio, exposição cambial, cenários macroeconômicos, entre outros.
* **Compliance Shield (Zero-Persistence):** Garante conformidade e segurança dos dados com processamento em memória e descarte automático de dados sensíveis, mantendo uma trilha de decisão auditável.
* **SRE Antifrágil:** Projeta-se para prosperar sob estresse, com mecanismos como *throttling*, *healthchecks*, *retries* automáticos e *fallback* de modelo/infra (incluindo GPU).

### Arquitetura e Infraestrutura Tecnológica

A FoundLab é construída sobre a **infraestrutura robusta e escalável do Google Cloud**, aproveitando uma gama de serviços gerenciados para garantir alta disponibilidade, segurança e desempenho. Sua arquitetura é **modular e baseada em microsserviços**, permitindo flexibilidade, escalabilidade (horizontal e vertical), manutenção simplificada e agilidade no desenvolvimento.

**Serviços GCP utilizados:**

* **Cloud Run:** Para implantação e escalabilidade de contêineres sem servidor, ajustando-se dinamicamente à demanda.
* **Document AI:** Para extração inteligente de dados e *insights* de documentos não estruturados.
* **BigQuery:** *Data warehouse* corporativo para análise de grandes volumes de dados, relatórios, armazenamento de longo prazo e ETL.
* **Pub/Sub:** Serviço de mensagens assíncronas para comunicação desacoplada entre componentes e processamento assíncrono.
* **Cloud SQL (PostgreSQL):** Banco de dados relacional gerenciado para armazenamento de dados estruturados e transacionais.
* **Secret Manager:** Gerenciamento seguro de segredos e credenciais.
* **Cloud Armor:** Proteção contra ataques DDoS e WAF (Web Application Firewall) na borda da rede.
* **VPC Service Controls (VPC-SC):** Criação de perímetros de segurança em torno dos serviços do Google Cloud.
* **Vertex AI:** Plataforma unificada de MLOps para orquestrar e gerenciar o ciclo de vida dos fluxos de trabalho de IA/ML, integrando Document AI e aplicando lógica de pontuação/conformidade.
* **Cloud Storage (GCS):** Para *buckets* de *upload* de documentos e *logs* de auditoria.
* **Memorystore (Redis):** Cache de alta velocidade para otimização de desempenho e redução de latência.

**Tecnologias de Frontend e Backend:**

* **Frontend:** Desenvolvido com **React com TypeScript**, visando uma interface fluida, reativa e robusta. Utiliza também **Vite, TailwindCSS** e **Recharts** para gráficos. O *hosting* é feito via Vercel ou Firebase Hosting.
* **Backend:** Implementado em **Python com Flask**, com a inteligência central residindo no motor de extração com o modelo **Gemini 1.5-flash** do Google, utilizando um *responseSchema* JSON detalhado para previsibilidade e precisão. Inclui um módulo **seal_decision.py** para auditoria automática e validação, e uma **fallback_logic.py** inteligente para re-tentativas com diferentes *prompts*, modelos ou OCR em caso de falha.

**Outros aspectos arquiteturais:**

* **Contêineres (Docker):** Encapsulamento de aplicações e dependências para consistência em qualquer ambiente.
* **Orquestração (Kubernetes):** Gerencia a complexidade e a escala de contêineres, garantindo alta disponibilidade, escalabilidade elástica e implantação contínua.
* **Aceleração de Hardware (NVIDIA):** Uso de GPUs e NVIDIA Inference Microservices (NIM) para processamento intensivo de dados e execução de algoritmos complexos de IA, garantindo rapidez e precisão.

### Performance e Segurança

A FoundLab estabeleceu metas rigorosas de latência: **inferior a 520 milissegundos (ms)** para requisições síncronas (pré-análise) e **menos de 3 minutos por documento** para processamento assíncrono completo. A arquitetura de segurança é um pilar fundamental, permeando todas as camadas. Inclui:

* **Criptografia de dados em trânsito e em repouso** (TLS 1.3 e AES-256).
* **Autenticação Multifator (MFA)** e **Controle de Acesso Baseado em Funções (RBAC)** com granularidade por cliente e perfil.
* **Monitoramento contínuo** para detectar e responder a atividades suspeitas.
* **Auditorias de segurança regulares** e testes de penetração.
* **Policy-as-Code com OPA (Open Policy Agent)** para definir políticas de segurança de forma centralizada e automatizada.
* **Gerenciamento de Segredos e Chaves** (Secret Manager e KMS) com rotação periódica de chaves.
* **Prevenção de Perda de Dados (DLP) opcional** para inspecionar e bloquear vazamento de informações sensíveis.

### Filosofia "by-design" e Conformidade

A FoundLab adota uma cultura "**by-design**" visando transformar a confiança em um componente inerente, programável e auditável da infraestrutura financeira. Isso elimina o "custo invisível da desconfiança". Os elementos-chave dessa filosofia são:

* **Confiança como Infraestrutura Programável e Auditável**.
* **Arquitetura Modular Plug-and-Play e Não-Custodial**, atuando como um "*middleware* neutro" e "Suíça da infraestrutura reputacional".
* **Veritas Protocol para Auditabilidade Criptográfica**, garantindo ações e decisões criptograficamente auditáveis com logs imutáveis.
* **Governança Transparente e Ética Algorítmica**, incluindo um Conselho de Ética Algorítmica (CEA) e um Defensor Público Algorítmico (DPA).
* **Guardian AI e o Flywheel Reputacional Antifrágil**, fortalecendo-se a cada interação e antecipando ameaças.
* **Burn Engine** para prevenção ativa e execução proativa de riscos, realizando ações irreversíveis no ponto de risco.
* **Signed Digital Identity (SDID)** como um artefato de identidade digital portátil e verificável.
* **Camada de Integridade Silenciosa** que preenche a lacuna entre TradFi e Web3.
* **Filosofia Open Source** para transparência e inovação.

A plataforma possui **conformidade regulatória abrangente** com LGPD, BACEN/CVM e FATF/AML (quando aplicável), garantindo governança corporativa, segurança da informação e trilhas de auditoria detalhadas.

Em suma, a Umbrella é uma *operação completa com IA** sofisticada, estratégica e robusta, que se posiciona no mercado de Venture Capital como uma empresa de "**Infraestrutura Confiável como Serviço**", entregando confiança computacional auditável e mitigando os riscos de alucinação e conformidade.

---

## 🚀 Execução Local

### Pré-requisitos

* [Node.js](https://nodejs.org/en/) (versão 20.x ou superior)

* [NPM](https://www.npmjs.com/) ou [Yarn](https://yarnpkg.com/)

### Passos

1. **Clone o repositório:**

    ```bash
    git clone <URL_DO_REPOSITORIO>
    cd studio-main
    ```

2. **Instale as dependências:**

    ```bash
    npm install
    ```

3. **Configure as Variáveis de Ambiente:**
    * Renomeie o arquivo `.env.local.example` para `.env.local`.
    * Preencha as variáveis de ambiente com suas chaves de API e configurações do Firebase/GCP.

4. **Execute o servidor de desenvolvimento:**

    ```bash
    npm run dev
    ```

5. Abra [http://localhost:3000](http://localhost:3000) no seu navegador para ver a aplicação.

---

<div align="center">
  <p><strong>FoundLab</strong> | Transforming documents into dynamic, trustworthy assets.</p>
</div>
