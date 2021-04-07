## FIRST STEP DATA ENGINEER

### SOLUTION SPRINT

### Integrantes:

- Leonardo Soares Pereira
- Rodrigo Erasmo Vasconcellos
- Samuel Arcanjo de Oliveira Rodrigues

## 1.1 NOSSO CONSULTOR

Leandro Moraes Mendes é Data Engineering Manager na Accenture e será nosso consultor neste desafio. Compartilhará toda a sua experiência e conhecimento sobre o universo de dados.

Podemos conhecê-lo mais em:

<https://www.linkedin.com/in/leandrommendes>.

## 1.2 DESAFIO

Todo o conteúdo apresentado na 1ª fase Firsts Step Data Engineer – ecossistema big data, data governance e agile database project – será colocado em prática neste desafio.

Para isso, nosso consultor Leandro Moraes Mendes nos traz o mundo do Campeonato Brasileiro de Futebol, mais especificamente o Cartola FC, criado e mantido pela Globo.com e promovido pelo canal de TV por assinatura Sportv.

Os scouts e as partidas podem ser visualizados em Scouts e Estatísticas do Cartola FC. Nesse estilo de jogo de futebol virtual, o torcedor administra um time com base no desempenho real dos atletas. A cada rodada, o usuário escolhe 11 jogadores e um técnico, os quais vão compor o seu time. Para isso, utiliza quantias em cartoleta (C$), a moeda virtual do jogo. Todos começam a temporada com C$ 100.

Na primeira rodada do Campeonato Brasileiro de 2016, o jogo de abertura registrou a sua melhor marca entre times escalados em uma única rodada em 12 anos de história: 2.723.915 usuários montaram as suas equipes.

Nosso objetivo será elaborar e preparar um ambiente big data para analisar os resultados de partidas de futebol e os scouts dos jogadores no Campeonato Brasileiro desde 2014.

## 1.3 PIPELINE DE DADOS NO FRAMEWORK HADOOP

Vamos construir um ecossistema big data simples com HDFS e Hive. No caso, recorremos a Gomide e Gualberto (2021), autores que criaram o “Cartola FC: Ciência de Dados e Futebol”, disponibilizando dados e modelos analíticos sobre a mania nacional desde 2014; e a Vicente Neto (2021), que criou a Python Cartola FC API.

Realizaremos os seguintes passos:

Elaborar uma arquitetura para obtenção e tratamento dos dados.
Importar os arquivos para o HDFS.
Criar tabela(s) no Hive para realizar consultas analíticas.
Construir consultas SQL para responder às questões:

-        Quantos registros há na tabela por ano?

-        Quantas equipes únicas mandantes existem?

-        Quantas vezes as equipes mandantes saíram vitoriosas?

-        Quantas vezes as equipes visitantes saíram vitoriosas?

-        Quantas partidas resultaram em empate?

-        Quais jogadores detêm os melhores scouts gerais e por ano?

-        Qual é o time ideal?

-        Será que podemos preparar a ingestão para o campeonato de 2021?

-        Como capturar os dados direto do Cartola FC?

**Entregável 1**

1. O diagrama da arquitetura de dados proposta.
2. Evidências da importação dos arquivos no HDFS – Print do ls (hdfs.jpeg).
3. Os scripts com os comandos para a criação da tabela no Hive.
4. Um documento denominado resposta.doc com as
   queries e as respostas das questões propostas.
5. Exemplo de uso da API.

## 1.4 PESQUISAR, DETALHAR E COMPARAR FERRAMENTAS PARA GOVERNANÇA DE DADOS

Elaborar uma visão sobre as principais ferramentas (mínimo três) para governança de dados existentes no mercado. Esse documento deve conter:

Breve descrição de cada ferramenta pesquisada e analisada.
Quadro comparativo entre as ferramentas pesquisadas com no mínimo cinco características destacadas.
Recomendação sobre o uso da ferramenta associado às boas práticas de governança.

Sugestão: Veja os Quadrantes Mágicos do Gartner para Qualidade de Dados, Master Data Management e Metadata Management Solutions.

**Entregável 2**

1. Um documento com os itens descritos acima.

## 1.5 PROPOR UM PROJETO PARA CONSTRUÇÃO MDM

Uma organização decidiu seguir as boas práticas sugeridas pela Governança de Dados e investir em Master Data Management. Assim precisamos detalhar as seguintes atividades:

Elaborar Scrum Product Backlog.
Propor planejamento do Product Backlog.
Propor planejamento do Sprint.

**Entregável 3**

1. Um documento com as atividades propostas acima.

O documento final deverá conter os entregáveis destacados para cada item do desafio.
