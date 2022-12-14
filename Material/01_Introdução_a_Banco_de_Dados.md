# PRÉ REQUISITOS:

 - Lógica e Pensamento Computacional
 - Noções de arquitetura de computadores
 - noções de sistemas operacionais
 - noções de matemática básica (teoria de conjuntos em especial)

# APRESENTAÇÃO INICIAL

 - Iinformações da instrutora

![Objetivo desse modulo](../img/apre_01.jpg)

# Cenário de dados

 - Tudo são dados
 - Persistencia e confiança nos dados
 - Acesso a conta - dados relacionados a conta
 - No inicio -> tipo de dados -> numericos e textuais
 - Maior capacidade dos computadores
 - Paradigma do BigData - Velocidade, variedade e volume.

# O que são banco de dados

 - Dados são "fatos"
 - Dados relacionados -> Database
 - Conjunto de dados q transmite informação
 - "coleção de palavras, que dentre elas há relacionamentos entre dados, constituindo então um banco de dados" -> definição Geral
 - **uso + restrito**
   - contexto - representação do mundo real
   - coerência
   - propósito
 - Acesso
   - Fontes distintas persistinto dados
   - Api (acesso a banco de dados é geralmente feito por API)
   - Ações implicam em mudança de estado
   - Mudança de um estado válido para outro estado válido
     - confiável/acurado
   - o que muda é o tamanho
 - para gerenciar grandes quantidades de dados é necessario um sistema
 - Banco de dados é o conjunto de dados
 - SGBD / DBMS é o sistema q gerencia o banco de dados de um estado válido para outro

# Sistemas de Gerenciamento de Banco de dados - SGBDs

 - Software de propósito geral
   - gerenciamento de banco de dados
 - Etapas
   - Definição
     - Tipo, estrutura e regras
     - o que quero representar
   - Construção
     - Inserção de dados
     - persistencia - mapeamento
   - Manipulação
     - Recuperação
     - Relatórios
       - Query
   - Compartilhamento
     - Simultaneidade
     - Acesso
 - Ações agregadas
   - Transações
     - Retorno de dados
 - Ciclo de vida Longo
 - Proteção
   - Malfuncionamento
   - Acesso
![SGBD](../img/sgbd-01.jpg)
 - Definição
Componentes de um banco de dados
![SGBD](../img/sgbd-02.jpg)
![SGBD](../img/sgbd-02-1.jpg)
   - Metadados
     - informações que fornecem uma descrição dos dados
 - Construção
   - determina como é feito o acesso aos dados
![SGBD](../img/sgbd-03.jpg)
 - Manipulação
   - manutenção de banco
   - updates
![SGBD](../img/sgbd-04.jpg)
 - Compartilhamento
   - exige bloqueio para liberação das tabelas
   - bloqueia acesso de todos até a efetivação da modificção
![SGBD](../img/sgbd-05.jpg)
# Breve histórico de SGBDs

 - 60/70 Diminuir custos com pessoal
 - Modelos baseados em sistemas de arquivos
 - Modelo Hierarquico
 - Modelo em rede
 - modelo Relaciona
   - 1970 Artigo sobre teoria de conjuntos e Algebra Relacional
   - SQL
   - 76 1ºSGBD
   - 80 Oracle 2 SGBD
   - 83 Oracle 3 SGBD
 - Conce 

![Historico](../img/hist-01.jpg)

![Historico](../img/hist-02.jpg)

  
## Modelo Hierarquico
 
![Historico](../img/hist-03.jpg)
 - Organizado por dintância 
 - Registro: links e dados
 - TAD tree - com raiz

## Modelo em Rede

![Historico](../img/hist-04.jpg)
 
 - Conhecer a estrutura física da estrutura de dados
 - não existe definição da forma de relacionar

# Modelo de Banco de Dados Relacional

![Historico](../img/Slide68.jpg)

 - Abstração matemática da relação
 - Algebra relacional

![Historico](../img/Slide69.jpg)

  - Definido pelo Administrador de banco de dados

![Historico](../img/Slide70.jpg)

 - manutenção

![Historico](../img/Slide71.jpg)


![Historico](../img/Slide74.jpg)

usuario comum

![Historico](../img/Slide76.jpg)







![Historico](../img/Slide78.jpg)
tratado pelo sitema operacional

![Historico](../img/Slide80.jpg)
integrar diversas tecnologias de sgdbs

![Historico](../img/Slide81.jpg)
![Historico](../img/Slide82.jpg)
fontes diversas isendo integradas para ter um resultado



# SGBDs mais utilizados pelo mercado

![Historico](../img/Slide84.jpg)

![Historico](../img/Slide85.jpg)

![Historico](../img/Slide86.jpg)



# A era dos dados e o futuro da modelagem - Parte 1

![Historico](../img/Slide88.jpg)

![Historico](../img/Slide89.jpg)

 - independente do tamanho da empresa, em mais de 90% dos casos é necessario pelo menos um sistema básico relacional
 - 80% das situações estão nos casos acima.

![Historico](../img/Slide90.jpg)

 - Ambiente de pesquisa - estudos

![Historico](../img/Slide91.jpg)

![Historico](../img/Slide92.jpg)

![Historico](../img/Slide93.jpg)

![Historico](../img/Slide94.jpg)

![Historico](../img/Slide95.jpg)

 - 
![Historico](../img/Slide96.jpg)

 - Paralelismo
   - Múltiplos processadores operando concorrentemente
   - HPC - High performance computint
 - Big Data
   - Processamento paralelo de dados persistentes e particionados
 - Cloud
   - Recursos de terceiros - Soluções de tecnologia como serviço

![Historico](../img/Slide97.jpg)

 - nós de processamento paralelo
 - arquivos paralelos sem persistencia de dados

![Historico](../img/Slide98.jpg)

 - nós de processamento paralelos
 - arquivos paralelos com persistencia de dados


HPC | Big data 
---------|----------
 sem percistencia | com perssistencia 

![Historico](../img/Slide99.jpg)

[proxima aula](https://web.dio.me/course/contextualizacao-do-cenario-na-area-de-banco-de-dados-1/learning/5bedd5d3-3b7b-44a9-b551-e50793da444f?back=/track/database-experience&tab=undefined)




# Novo cenário e novas tecnologias - E agora?CENÁRIO DE DADOS


