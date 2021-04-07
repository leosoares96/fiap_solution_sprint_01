## PIPELINE DE DADOS NO FRAMEWORK HADOOP

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
