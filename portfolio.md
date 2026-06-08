# Juan Henrique Evaristo CUrsino

[Insira sua foto aqui]

## Introdução

Este portfólio acadêmico foi construído com projetos reais desenvolvidos ao longo da minha formação no curso superior de tecnologia em Banco de Dados pela Faculdade de Tecnologia de São José dos Campos - Prof. Jessen Vidal. 

Durante a graduação, vivenciei a metodologia de Aprendizado por Projeto Integrador, trabalhando em equipes multifuncionais estruturadas sob o framework Scrum. Esse modelo de ensino me permitiu aplicar conceitos teóricos diretamente na resolução de dores reais de empresas parceiras do mercado de tecnologia.

Como futuro tecnólogo em Banco de Dados, especializei-me no ciclo de vida completo do dado: desde o levantamento de requisitos, modelagem conceitual e lógica, escolha entre paradigmas relacionais e não relacionais, até a otimização de consultas complexas, engenharia de dados (ETL) e a disponibilização de estruturas analíticas em nuvem. Os tópicos a seguir detalham essa trajetória de evolução técnica e profissional.

## Meus Projetos

## Em 2023-2 (1º Semestre)

### Parceiro Acadêmico
[PBLTeX](URL_DA_EMPRESA_AQUI)

### Descrição do Projeto
A PBLTeX é uma instituição educacional focada no ensino prático por meio do método de aprendizado baseado em problemas. No encerramento de cada ciclo letivo, a coordenação sofria com a falta de centralização e histórico para computar o Fator de Ensino Evolutivo dos alunos. O desafio consistiu em desenhar um fluxo seguro de informações para o monitoramento e consolidação das notas parciais (scores) acumuladas pelos estudantes.

### Solução Desenvolvida: [CoderHood API](https://github.com/CoderHood-Fatec/ProjetoCoderHood)
A equipe CoderHood projetou e implementou um sistema web de gestão de scores internos. A solução automatizou o cálculo do Fator de Ensino Evolutivo através de regras de negócio bem definidas no servidor. O sistema centralizou registros que antes ficavam dispersos, mitigou o risco de inconsistência de dados, ofereceu interfaces amigáveis para professores lançarem as notas e forneceu painéis de acompanhamento do progresso acadêmico dos alunos em tempo real.

<p align="center">
        <img src="lab/assets/03_Check-consistency-using-logbuffers.png" alt="Img 03 - Check consistency using logbuffers, node01"/><br>
        <em>Img 03 - Check consistency using logbuffers, node01</em>
    </p>

### Tecnologias Utilizadas e Justificativas

- **Python**: Linguagem utilizada no ecossistema de desenvolvimento backend para garantir agilidade na escrita das regras de negócio e fácil manipulação de estruturas de dados.
- **Flask**: Micro-framework web escolhido por sua leveza e flexibilidade, ideal para estruturar rotas de API robustas sem adicionar complexidades desnecessárias à arquitetura inicial.
- **HTML5 e CSS3**: Tecnologias estruturais de frontend aplicadas na criação das interfaces de usuário, garantindo acessibilidade, semântica e estilização responsiva.
- **JavaScript**: Utilizado no lado do cliente para prover dinamismo às telas, manipulação do DOM e requisições assíncronas para a API backend.
- **Git e GitHub**: Ferramentas fundamentais de controle de versão distribuído, utilizadas para garantir o histórico de alterações do código e gerenciar o fluxo de trabalho do time.

### Contribuições Pessoais
Fui responsável pelo desenvolvimento da lógica de backend, codificando os controladores e as rotas dentro do framework Flask para o processamento das avaliações e scores. Atuei ativamente no mapeamento inicial do fluxo de informações dos alunos e apoiei na padronização das mensagens de commits e na organização das branches do repositório no GitHub para manter a integridade do código.

### Hard Skills
- **Desenvolvimento Web Backend (Flask/Python)**: Entendimento e aplicação de rotas HTTP, tratamento de requisições e estruturação de regras de negócio lógicas no servidor. *Nível de autonomia: Parcialmente autônomo.*
- **Controle de Versão (Git/GitHub)**: Criação de branches, resolução de conflitos básicos e submissão de Pull Requests no fluxo de trabalho do time. *Nível de autonomia: Autônomo.*
- **Integração Básica de Dados**: Manipulação de estruturas de dicionários e listas em Python para simular a persistência e transporte temporário de notas e scores acadêmicos. *Nível de autonomia: Autônomo.*

### Soft Skills
- **Trabalho em Equipe e Colaboração**: Sendo o primeiro projeto integrado, exigiu grande effort para alinhar o desenvolvimento de backend com as interfaces visuais desenvolvidas pelos colegas, garantindo que o fluxo de dados dos scores funcionasse corretamente.
- **Adaptabilidade**: Necessidade de se adaptar rapidamente ao fluxo de trabalho do framework Scrum e à rotina de entregas segmentadas (sprints), comuns no desenvolvimento de software comercial.

---

## Em 2024-1 (2º Semestre)

### Parceiro Acadêmico
[Parceiro do Projeto Zeus](URL_DA_EMPRESA_AQUI)

### Descrição do Projeto
O desafio exigiu o desenvolvimento de um sistema nativo focado no controle rigoroso de dados transacionais e fluxos operacionais administrativos internos. O cenário demandava restrições de integridade estritas, alta disponibilidade local e agilidade na recuperação de grandes volumes de registros administrativos e cadastros, onde erros de concorrência ou perda de dados inviabilizariam a operação.

### Solução Desenvolvida: [Projeto Zeus](https://github.com/FatecCoderHood/Coderhood)
Conduzimos o design e o desenvolvimento do Projeto Zeus, uma aplicação desktop corporativa conectada a um servidor de banco de dados relacional robusto. A engineering do software focou na normalização de tabelas e na criação de índices eficientes. A solução viabilizou transações seguras (propriedades ACID), impedindo duplicidade de registros, além de fornecer uma interface rica para manipulação, busca avançada e persistência de dados de maneira performática.

<p align="center">
        <img src="lab/assets/03_Check-consistency-using-logbuffers.png" alt="Img 03 - Check consistency using logbuffers, node01"/><br>
        <em>Img 03 - Check consistency using logbuffers, node01</em>
    </p>

### Tecnologias Utilizadas e Justificativas

- **Java 17**: Versão de suporte de longo prazo (LTS) da linguagem, adotada para prover tipagem forte, orientação a objetos madura e estabilidade no backend e na lógica de negócios desktop.
- **JavaFX 22**: Framework gráfico avançado para construção de interfaces ricas voltadas a sistemas operacionais desktop, provendo componentes visuais modernos e bindings de dados eficientes.
- **PostgreSQL 16.2**: Sistema de Gerenciamento de Banco de Dados Relacional (SGBD) de nível corporativo escolhido devido ao seu suporte estrito ao padrão SQL, confiabilidade em transações e extensibilidade para queries complexas.
- **JDBC PostgreSQL**: Driver de conectividade essencial para permitir que a aplicação Java envie instruções SQL nativas diretamente ao banco de dados e trate os conjuntos de resultados de forma otimizada.
- **Git**: Sistema utilizado para rastrear o histórico de modificações e garantir a sincronia e segurança do código-fonte entre os desenvolvedores.

### Contribuições Pessoais
Minha atuação concentrou-se na camada de dados e persistência. Desenhei os esquemas de tabelas no PostgreSQL e escrevi as consultas SQL nativas integradas via JDBC. Trabalhei no desenvolvimento dos controladores de interface para garantir que a entrada de dados do usuário em JavaFX fosse corretamente tratada, validadada e persistida, além de codificar rotinas de teste para blindar o sistema contra falhas de persistência.

### Hard Skills
- **Manipulação de SGBD Relacional (PostgreSQL)**: Criação de esquemas físicos (DDL), aplicação de chaves primárias/estrangeiras e escrita de queries DML para inserções e atualizações estruturadas. *Nível de autonomia: Autônomo.*
- **Conectividade de Dados (JDBC)**: Integração de aplicações com bancos de dados relacionais via drivers nativos, gerenciando abertura, execução de statements e fechamento de conexões. *Nível de autonomia: Autônomo.*
- **Programação Orientada a Objetos (Java)**: Criação de classes controladoras e modelos estruturados para mapear os dados da interface gráfica em tipos compatíveis com o banco de dados. *Nível de autonomia: Parcialmente autônomo.*

### Soft Skills
- **Raciocínio Lógico e Resolução de Problemas**: Aplicados no mapeamento de restrições de integridade estritas e chaves estrangeiras no PostgreSQL, garantindo que as regras de negócio fossem validadas na própria camada do banco de dados.
- **Comunicação Assertiva**: Essencial no alinhamento com a equipe para mapear o fluxo de persistência de dados (CRUD) a partir das ações tomadas pelos usuários na interface gráfica em JavaFX.

---

## Em 2024-2 (3º Semestre)

### Parceiro Acadêmico
[GSW](URL_DA_EMPRESA_AQUI)

### Descrição do Projeto
A GSW demandava uma modernização em seus processos operacionais de controle interno e atendimento. O gargalo se encontrava na falta de rastreabilidade das interações corporativas e na lentidão para auditar modificações em registros de clientes e serviços. Havia a necessidade de migrar fluxos manuais para um ambiente web escalável que seguisse padrões rigorosos de segurança e auditoria de dados.

### Solução Desenvolvida: [GSW API](https://github.com/FatecCoderHood/GSW_API)
Implementamos uma arquitetura multicamadas (decoupled) composta por uma API robusta no ecossistema Java e um frontend SPA (Single Page Application). O sistema garantiu total rastreabilidade das operações através de um esquema de banco de dados relacional estruturado com chaves estrangeiras bem delimitadas. A solução contou ainda com o desenvolvimento de um manual técnico e de usuário completo, permitindo que a equipe de TI da GSW fizesse a implantação local e a manutenção de forma autônoma.

<p align="center">
        <img src="lab/assets/03_Check-consistency-using-logbuffers.png" alt="Img 03 - Check consistency using logbuffers, node01"/><br>
        <em>Img 03 - Check consistency using logbuffers, node01</em>
    </p>

### Tecnologias Utilizadas e Justificativas

- **Java**: Plataforma robusta utilizada para estruturar a lógica corporativa pesada do ecossistema de serviços da aplicação.
- **Spring Boot**: Framework de mercado adotado para simplificar a configuração de microsserviços ou APIs RESTful, fornecendo injeção de dependência e integração transparente com o banco de dados via ORM.
- **Vue.js**: Framework progressivo de JavaScript focado na camada visual, escolhido para criar uma aplicação web reativa, rápida e de fácil manutenção para o usuário final.
- **HTML5**: Estruturação semântica das páginas web, crucial para garantir a acessibilidade e a organização dos elementos na tela.
- **MySQL**: SGBD relacional amplamente consolidado no mercado, selecionado para gerenciar de forma estável, segura e veloz o armazenamento dos dados de negócios da empresa.
- **Visual Studio Code e IntelliJ IDEA**: Ambientes de Desenvolvimento Integrados (IDEs) especializados, otimizados respectivamente para o desenvolvimento frontend em Vue e backend in Java.

### Contribuições Pessoais
Liderei a modelagem do banco de dados MySQL, aplicando as três primeiras formas normais para eliminar redundâncias de tabelas. No backend, utilizei o Spring Data JPA para mapear as entidades do banco em classes Java, otimizando o carregamento de relacionamentos carregados sob demanda (Lazy Loading) para evitar problemas clássicos de performance em consultas.

### Hard Skills
- **Modelagem Relacional e Normalização**: Aplicação prática de técnicas de normalização (1FN, 2FN e 3FN) para desenhar diagramas entidade-relacionamento escaláveis e livres de anomalias. *Nível de autonomia: Autônomo.*
- **Mapeamento Objeto-Relacional (ORM / JPA)**: Vinculação de entidades Java com tabelas físicas no MySQL utilizando Spring Data JPA, abstraindo queries e gerenciando ciclos de vida de dados. *Nível de autonomia: Autônomo.*
- **Desenvolvimento de APIs RESTful**: Criação de endpoints estruturados com retornos baseados em códigos de status HTTP e payloads limpos em formato JSON. *Nível de autonomia: Parcialmente autônomo.*

### Soft Skills
- **Organização e Atenção aos Detalhes**: Fundamentais durante o processo de normalização do modelo conceitual e lógico de dados, assegurando que nenhuma dependência transitiva gerasse anomalias de atualização no MySQL.
- **Orientação a Resultados**: Foco no cumprimento rigoroso do escopo exigido pelo cliente corporativo (GSW), estruturando o mapeamento objeto-relacional para entregar telas de consulta fluidas e integradas.

---

## Em 2025-1 (4º Semestre)

### Parceiro Acadêmico
[Parceiro do Projeto Geohood](URL_DA_EMPRESA_AQUI)

### Descrição do Projeto
O desafio envolveu o tratamento e processamento de informações cartográficas e geográficas para fins gerenciais. Sistemas tradicionais falham ao tentar lidar com coordenadas de latitude e longitude sem as extensões corretas, degradando o tempo de resposta em consultas espaciais. A meta era criar um sistema capaz de capturar e tratar dados geográficos, permitindo análises baseadas na localização de ativos territoriais.

### Solução Desenvolvida: [Projeto Geohood](https://github.com/FatecCoderHood/4_GeoHood)
Desenvolvemos uma aplicação de geoprocessamento capaz de plotar, criar e editar geometrias (como pontos, linhas e polígonos) diretamente sobre mapas em tempo real. Estruturamos o backend para validar a integridade dos dados espaciais submetidos, evitando sobreposições de áreas e erros de projeção. A solução serviu como uma plataforma de suporte à tomada de decisão para os gestores da empresa parceira visualizarem a distribuição geográfica de seus ativos de forma analítica.

<p align="center">
        <img src="lab/assets/03_Check-consistency-using-logbuffers.png" alt="Img 03 - Check consistency using logbuffers, node01"/><br>
        <em>Img 03 - Check consistency using logbuffers, node01</em>
    </p>

### Tecnologias Utilizadas e Justificativas

- **Java**: Utilizado no backend para dar robustez à orquestração dos dados de negócios e controle de acessos da API.
- **Spring Boot**: Empregado para levantar rapidamente os endpoints de serviços REST, facilitando a exposição de dados geográficos limpos para o cliente web.
- **Vue.js**: Utilizado no frontend para renderizar mapas dinâmicos e componentes interativos de desenho de polígonos sem engargalar o navegador do usuário.
- **HTML5**: Utilizado na marcação e integração de elementos gráficos avançados na página web.
- **MySQL**: Utilizado como repositório de persistência de dados cadastrais e espaciais associados às entidades geográficas mapeadas.
- **Ferramentas de Geoprocessamento**: Bibliotecas e extensões específicas integradas para decodificar formatos geográficos estruturados e realizar cálculos de distância e perímetro diretamente na camada de software.

### Contribuições Pessoais
Atuei na integração de tipos de dados geométricos e espaciais no banco de dados, configurando a indexação necessária para buscas por proximidade. Desenvolvi no ecossistema Spring Boot os endpoints da API encarregados de receber objetos JSON no padrão GeoJSON do frontend Vue.js, parseá-los e gravá-los de forma íntegra no banco de dados relacional.

### Hard Skills
- **Manipulação de Dados Espaciais**: Armazenamento e consumo de geometrias complexas utilizando padrões geográficos e funções nativas de SGBD. *Nível de autonomia: Parcialmente autônomo.*
- **Integração de Padrões GIS (GeoJSON)**: Parser, validação e manipulação de objetos geográficos estruturados no padrão internacional GeoJSON trafegados entre o cliente e o servidor. *Nível de autonomia: Autônomo.*
- **Desenvolvimento Full-Stack Integrado**: Criação de endpoints Spring Boot assíncronos capazes de alimentar em tempo real componentes reativos do ecossistema Vue.js. *Nível de autonomia: Parcialmente autônomo.*

### Soft Skills
- **Pensamento Crítico**: Necessário para analisar e traduzir requisitos espaciais complexos em coordenadas e coleções de geometrias estruturadas que pudessem ser salvas e validadas de forma limpa.
- **Resiliência**: Capacidade de lidar e superar os desafios de compatibilidade entre bibliotecas de geoprocessamento do backend e os componentes de renderização visual em mapa do frontend.

---

## Em 2025-2 (5º Semestre)

### Parceiro Acadêmico
[Necto](URL_DA_EMPRESA_AQUI)

### Descrição do Projeto
O gerenciamento manual de projetos na Necto gerava descentralização de informações, falta de previsibilidade de custos e dificuldades em metrificar a produtividade real dos desenvolvedores. Os dados existiam de maneira bruta e fragmentada dentro de uma API operacional externa. O problema exigia uma abordagem de Engenharia de Dados: coletar esses dados operacionais, limpá-los, consolidá-los em uma estrutura propícia para análise e gerar inteligência de negócios.

### Solução Desenvolvida: [Athos Insight](https://github.com/AthosFatecSjc/Athos_Insight)
Concebemos o Athos Insight, uma solução analítica hospedada na nuvem da Microsoft Azure. O ecossistema consome os dados operacionais da API de origem e executa um pipeline de dados estruturado para alimentar um Data Warehouse modelado especificamente para consultas analíticas complexas. A plataforma web disponibiliza visões consolidadas de custos previstos versus realizados por projeto, calcula taxas de eficiência por desenvolvedor, e possui um gerador de relatórios executivos em formato PDF, facilitando auditorias internas da alta liderança da Necto.

<p align="center">
        <img src="lab/assets/03_Check-consistency-using-logbuffers.png" alt="Img 03 - Check consistency using logbuffers, node01"/><br>
        <em>Img 03 - Check consistency using logbuffers, node01</em>
    </p>

### Tecnologias Utilizadas e Justificativas

- **Java e Spring Boot**: Utilizados para construir a engine da aplicação backend, gerenciando as chamadas periódicas à API de origem e orquestrando o tratamento dos dados brutos.
- **Vue.js**: Framework frontend aplicado na construção de dashboards modernos com gráficos dinâmicos para a visualização intuitiva dos KPIs financeiros e operacionais.
- **PostgreSQL**: Adotado como o banco de dados centralizado do projeto, servindo como o repositório físico do Data Warehouse graças ao seu ótimo desempenho em consultas agregadas.
- **Microsoft Azure**: Nuvem pública utilizada para hospedar toda a solução (banco de dados e aplicação), provendo escalabilidade, segurança de rede e alta disponibilidade.
- **SonarQube**: Ferramenta de segurança e qualidade de código integrada à esteira de desenvolvimento para executar análises estáticas do código, garantindo a prevenção de bugs e vulnerabilidades.

### Contribuições Pessoais
Foquei na arquitetura de dados do projeto. Fui responsável por desenhar a modelagem dimensional (Tabelas Fato e Dimensão) do Data Warehouse no PostgreSQL. Criei os scripts e rotinas de ingestão que extraíam os payloads JSON da API externa, realizavam o mapeamento de tipos, o tratamento de registros nulos e a carga incremental no Data Warehouse, garantindo relatórios sempre atualizados e consultas rápidas.

### Hard Skills
- **Modelagem de Data Warehouse (Mapeamento Dimensional)**: Arquitetura de bancos de dados analíticos utilizando esquemas estrela (Star Schema), estruturando e separando Tabelas Fato (métricas) de Tabelas Dimensão (contextos). *Nível de autonomia: Autônomo.*
- **Engenharia de Dados (ETL / Ingestão)**: Desenvolvimento de rotinas automatizadas para extração de APIs em formato JSON, higienização de nulos, transformação e carga incremental no banco analítico. *Nível de autonomia: Autônomo.*
- **Cloud Computing (Microsoft Azure)**: Implantação de instâncias de servidores e provisionamento de bancos de dados relacionais gerenciados em ambiente de nuvem corporativo. *Nível de autonomia: Parcialmente autônomo.*

### Soft Skills
- **Visão Sistêmica e de Negócio**: Essencial para entender as dores financeiras da Necto e projetar um Data Warehouse capaz de responder perguntas estratégicas sobre o custo e a lucratividade das operações.
- **Liderança Técnica de Dados**: Assumindo a responsabilidade pela integridade da modelagem em estrela (Star Schema), orientando a equipe sobre como as chaves substitutas (surrogate keys) mantêm o histórico correto dos projetos.

---

## Em 2026-1 (6º Semestre)

### Parceiro Acadêmico
[TECSYS Brasil](URL_DA_EMPRESA_AQUI)

### Descrição do Projeto
Concessionárias de distribuição de energia operam sob severas regras da ANEEL, onde falhas na continuidade do fornecimento geram multas pesadas medidas por indicadores técnicos complexos (DEC e FEC). A TECSYS sofria com a dispersão crônica desses indicadores em múltiplos arquivos de dados abertos governamentais, o que tornava o processo de análise mercadológica puramente manual, lento e passível de falhas de processamento devido ao gigantismo dos arquivos.

### Solução Desenvolvida: [EnerSight](https://github.com/FatecCoderHood/EnerSight)
Entregamos a EnerSight, uma plataforma web analítica de Big Data para o setor elétrico. A aplicação automatiza a varredura e o download dos grandes datasets públicos da ANEEL, orquestrando fluxos de ETL por meio de microsserviços conteinerizados em Docker. O sistema padroniza e armazena os registros históricos de bilhões de ocorrências de interrupções, disponibilizando uma interface analítica avançada na qual usuários podem filtrar, comparar e rastrear a qualidade do serviço por distribuidora, região geográfica e conjuntos elétricos específicos.

<p align="center">
        <img src="lab/assets/03_Check-consistency-using-logbuffers.png" alt="Img 03 - Check consistency using logbuffers, node01"/><br>
        <em>Img 03 - Check consistency using logbuffers, node01</em>
    </p>

### Tecnologias Utilizadas e Justificativas

- **Python e Flask**: Tecnologias empregadas na criação dos scripts de automação e na construção do microsserviço de ETL, aproveitando a vasta gama de ecossistemas matemáticos e de manipulação de dados que o Python oferece.
- **PostgreSQL**: SGBD relacional escalável escolhido para suportar o massivo volume de registros das distribuidoras de energia do país, com foco em segurança de dados e criação de visões materializadas.
- **Docker e Docker Compose**: Tecnologia de virtualização a nível de sistema operacional (conteinerização), crucial para empacotar o banco de dados e as aplicações de forma idêntica, isolando dependências e simplificando o deploy em qualquer ambiente.
- **Node.js e TypeScript**: Plataforma backend de alta concorrência assíncrona utilizada junto com a tipagem estática do TypeScript para construir a API principal de consumo da aplicação com segurança e performance.
- **TailWind CSS**: Framework CSS baseado em utilitários adotado para acelerar o design de interfaces altamente customizadas, limpas e responsivas para o painel analítico.

### Contribuições Pessoais
Atuei na Engenharia de Dados pesada da aplicação. Desenvolvi todo o pipeline automatizado em Python que realiza o download dos grandes datasets da ANEEL, faz a limpeza de strings, trata inconsistências e insere os dados via bulk insert no PostgreSQL. Modelei a infraestrutura utilizando Docker Compose para criar clusters isolados e configurei índices de árvore B (B-Tree) e partições de tabelas por ano para que as agregações de KPIs nacionais retornassem respostas em menos de dois segundos.

### Hard Skills
- **Otimização de Performance e Tuning de Consultas**: Implementação de índices complexos estruturados em árvores B (B-Tree), análise de planos de execução (EXPLAIN ANALYZE) e aplicação de particionamento físico de tabelas para volumes massivos de Big Data. *Nível de autonomia: Autônomo.*
- **DevOps e Conteinerização (Docker/Docker Compose)**: Criação de Dockerfiles e arquivos Compose para isolar, orquestrar e automatizar a inicialização do ecossistema de banco de dados e microsserviços de ETL. *Nível de autonomia: Autônomo.*
- **Pipelines de Big Data (Python/Bulk Operations)**: Desenvolvimento de rotinas robustas voltadas à inserção maciça de dados (Bulk Inserts), otimizando a taxa de escrita por segundo e evitando gargalos de I/O em discos rígidos locais ou na nuvem. *Nível de autonomia: Autônomo.*

### Soft Skills
- **Gerenciamento de Crise e Resolução de Problemas Complexos**: Postos em prática ao otimizar consultas analíticas lentas que travavam o banco devido ao volume massivo de dados da ANEEL, exigindo estratégias de particionamento físico sob alta pressão.
- **Negociação e Alinhamento Técnico**: Importante na tomada de decisões arquiteturais com o time, defendendo o uso de Docker e particionamento de tabelas para garantir a escalabilidade horizontal exigida pela TECSYS Brasil.

---

## Meus Principais Conhecimentos

* **SGBDs Relacionais**: Experiência avançada em PostgreSQL e MySQL (Modelagem, Escrita de Queries complexas, Restrições de Integridade e Normalização).
* **Engenharia de Dados**: Construção de pipelines de ETL operacionais e analíticos, manipulação de arquivos de larga escala (JSON, CSV) e carga de dados otimizada (Bulk).
* **Modelagem de Dados**: Domínio em Modelagem Relacional (OLTP) e Modelagem Dimensional (OLAP / Star Schema / Tabelas Fato e Dimensão).

## Contatos

- GitHub: [Insira o link do seu perfil]
- LinkedIn: [Insira o link do seu perfil]
- E-mail: [Insira seu e-mail de contato]
