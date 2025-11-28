# Modelagem-de-Banco-de-Dados #

🗄️ Repositório: Fundamentos e Prática de Modelagem de Dados
"Dados são o combustível essencial para a inovação na era digital."

Repositório dedicado a Modelagem de Banco de Dados, com foco em transformar requisitos de negócio em estruturas de dados eficientes, íntegras e escaláveis. Este projeto demonstra a jornada completa do design conceitual à implementação física.

📖 Sobre Este Conteúdo
Este material oferece uma visão abrangente sobre o ciclo de vida da modelagem, equipando o estudante com as habilidades para projetar sistemas de informação robustos. O estudo está organizado em uma progressão lógica de quatro fases:

Análise e Contextualização: Entendimento da diferença crucial entre dado e informação, considerações éticas (LGPD) e introdução aos diversos tipos de Sistemas Gerenciadores de Banco de Dados (SGBDs).

Design Conceitual: Desenvolvimento da estrutura visual do negócio utilizando o Modelo Entidade-Relacionamento (MER) e seus respectivos Diagramas Entidade-Relacionamento (DER).

Projeto Lógico e Otimização: Aplicação das técnicas de Normalização para remover redundâncias e assegurar a integridade referencial da estrutura.

Implementação Prática (SQL): Tradução do modelo lógico para o ambiente físico, incluindo a manipulação de dados e a criação de objetos no SGBD utilizando comandos SQL.

🎯 Resultados de Aprendizagem
Ao longo deste projeto, foram consolidadas as competências para:

✅ Traduzir requisitos de negócio em um modelo formal, identificando corretamente entidades, atributos e seus relacionamentos. ✅ Aplicar e justificar as Formas Normais (1FN, 2FN, 3FN) para garantir a consistência e evitar anomalias de atualização. ✅ Utilizar ferramentas de design para criar e manter modelos de dados (ex: BRModelo, MySQL Workbench, PgAdmin). ✅ Desenvolver e executar scripts SQL para criar a estrutura (DDL) e manipular os dados (DML) de forma otimizada.

🛠️ Tecnologias PrincipaisCategoriaFerramenta / LinguagemModelagem[Ferramenta usada, ex: BRModelo ]SGBD[Banco usado, ex: MySQL / PostgreSQL ]LinguagemSQL (Structured Query Language)Ambiente/IDE[BRmodelo/Pgadmin]
📂 Estrutura do RepositórioPastaDescrição01-modelagem-conceitualContém os Diagramas ER (DER) resultantes dos estudos de caso e análises de requisitos.02-normalizacaoDemonstração e exercícios da aplicação da 1ª, 2ª e 3ª Formas Normais (FN).03-sql-scriptsArquivos contendo os comandos DDL (criação de tabelas) e DML (queries de manipulação) testados no SGBD.
🚀 Como Explorar os Projetos
Obtenha o Conteúdo: git clone https://github.com/seu-usuario/modelagem-bd.git

Visualizar Modelos: Os diagramas conceituais podem ser vistos abrindo os arquivos .png ou .brM3 na pasta 01-modelagem-conceitual.

Executar Estruturas: Os scripts SQL (.sql) na pasta 03-sql-scripts podem ser importados e executados no seu SGBD de preferência.

📝 Detalhamento de Tópicos
Este repositório é um guia prático que navega desde as regras de negócio (modelo conceitual) até a criação física no banco de dados (SQL), focando em integridade e alta performance.

📚 Conteúdo Detalhado
🔹 1. Contexto e Fundamentos A distinção fundamental entre Dados e Informação.

Diretrizes de Ética e Privacidade no tratamento de dados, com base na LGPD.

🔹 2. Design Conceitual (MER/DER) Metodologias de identificação de Entidades, Atributos e a Cardinalidade dos Relacionamentos.

Uso de ferramentas para a representação visual (Ex: BRModelo, PGadmin, etc.).

🔹 3. Projeto Lógico e Normalização Estruturação do modelo através da aplicação de 1FN, 2FN e 3FN.

Definição correta de Chaves Primárias (PK) e Chaves Estrangeiras (FK) para garantir a ligação dos dados.

Estratégias para a eliminação eficiente de redundâncias.

Implementação (SQL) Comandos DDL (Data Definition Language) essenciais: CREATE TABLE, ALTER TABLE, DROP TABLE.
Comandos DML (Data Manipulation Language) para interação com os dados: INSERT, UPDATE, DELETE, e SELECT.
