
# O papel dos Bancos de Dados SQL e NoSQL na Engenharia de Dados

Projeto realizado durante o Bootcamp Database Experience da Digital Innovation One (DIO).

## Desafio
Neste desafio, você terá a missão de compreender o papel dos Bancos de Dados Relacionais (SQL) e Não Relacionais (NoSQL) no contexto de um Engenheiro de Dados. Para isso, anote todos os conceitos, definições e insights que julgar relevantes em um novo repositório Git, aumentando assim seu portfolio de conhecimentos.

### Contexto geral - atualidade
Com a produção crescente de dados em vários formatos é necessário que haja uma gestão desses dados conforme seu contexo.

### SQL x NoSQL
#### O que é um Banco de Dados Relacional (SQL)
É um tipo de banco onde armazenamos informações que se relacionam. Temos um esquema de dados rígido. 

#### O que é um Banco de Dados Não Relacional (NoSQL)
Not Only Structured Query Language.
Necessidade de armazenar dados não estruturados, por conta da grande escabilidade dos tipos de dados.
O NoSQL não foi criado para substituir o SQL.

#### Exemplos de modelos de banco de dados NoSQL
Chave-valor (key-value) - Dynamo

Banco de Dados Orientado a Documento - MongoDB

Orientado a Coluna (column family) - Cassandra

Orientado a Grafos - Neo4j

### Consultando um dado armazenado no NoSQL
As chaves de consultas são importantes. Apesar de não ter um esquema rígido, é importante ter alguns cuidados básicos.
A forma como pretendemos realizar as consultas também deve ser pensada desde o inicio pensando nas características do banco.

### É necessário conhecer todos os tipos de SGBDs?
É importante conhecer os contextos e para qual finalidade os bancos de dados estão sendo utilizados. Cada um tem sua particularidade, porém o propósito é o mesmo.

### Flexibilidade do NoSQL
Os bancos NoSQL podem ser utilizados em aplicações com dados de diferentes formatos e que não necessariamente tenham um relacionamento. 
Dessa forma, essa flexibilidade também se estende para as opções de manipulação e processamento dos dados armazenados. 

### Datalake e Databricks
Um data lake é um local central que contém uma grande quantidade de dados em seu formato bruto que podem ser ou não estruturados, usando uma arquitetura simples. 
É necessário que seja consistente para consumirmos as informações, e que não se torne um "pântano de dados".

### Desafios ao realizar ETL
Extract - Transform - Load (processo de transformação dos dados).
Desafio na manipulação dos dados em diversas rotinas, utilizando ferramentas para administrar essas manipulações.

### Engenheiro e Cientista de Dados
Perfis complementares.
O papel do engenheiro está mais relacionado a preparação da informação para que posteriormente os cientistas possam utilizá-las.
O cientista também trabalha com as aplicações, Machine Learning e insights para tomadas de decisões.


### Conclusão
O NoSQL tem muitas vantagens para ser utilizado. Mas não é por isso que devemos utilizá-lo em todas as situações. Em muitos sistemas, você pode (e até deve) usar o modelo relacional. O NoSQL é mais indicado para aqueles sistemas que tenham necessidades maiores de armazenamento e desempenho.

O banco de dados relacional sempre irá fornecer dados íntegros e imutáveis, garantindo um controle transacional consistente. Além disso, seu esquema é rígido, sendo possível atribuir campos e estabelecer se o dado de uma coluna é nulo ou não nulo.

Já o banco de dados não relacional, que representa diversos tipos de bancos de dados, não exige a rigidez de esquemas para armazenar os dados, ou seja, ele não limita os campos, diferente das colunas do SQL. Além disso, é possível adicionar novas propriedades, sem a preocupação com o impacto nas demais informações já armazenadas.

O NoSQL não veio para substituir o SQL, mas sim para oferecer mais uma alternativa de um banco de dados mais flexível no suporte de dados. Sendo assim, pode-se usar ambas as soluções para diferentes casos de uso. Por isso, o mais comum em soluções escalares de sucesso é a utilização de uma arquitetura híbrida, aproveitando o melhor dois dois modelos.

Não existe um modelo que seja melhor do que o outro, pois cada um tem seu ponto forte. Tudo dependerá do contexto e da necessidade do projeto.

## Referências complementares

 - [SQL vs NoSQL, qual usar?](https://www.treinaweb.com.br/blog/sql-vs-nosql-qual-usar)
 - [Os principais SGBDs NoSQL](https://www.treinaweb.com.br/blog/os-principais-sgbds-nosql/)
 - [Os principais SGBDs relacionais](https://bulldogjob.com/news/449-how-to-write-a-good-readme-for-your-github-project)
- [Banco de dados: entenda o que é um banco de dados relacional e não relacional](https://www.digitalhouse.com/br/blog/banco-de-dados-relacional-e-nao-relacional/)

