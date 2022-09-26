# Projeto Final Database Experience
## O PAPEL DOS BANCOS DE DADOS SQL E NOSQL NO CONTEXTO DA ENGENHARIA DE DADOS 

### **Bancos SQL** 

Structured Query Language ou SQL é a linguagem mais conhecida do mundo e também a mais popular. É utilizada para executar comandos em Banco de Dados Relacionais, ou seja, baseado em tabelas. É por meio dela que criamos databases, tabelas, colunas, índices, garantimos e revogamos privilégios a usuários e consultamos os dados armazenados no banco de dados. SQL é uma linguagem declarativa dividida em conjuntos de comandos:                                                      
Data Definition Language (DDL) - comandos que permitem ao usuário definir as novas tabelas e os elementos que serão associados a elas;                                  Data Manipulation Language (DML) - comandos utilizados para a recuperação, inclusão, remoção e modificação de informações em bancos de dados;                
Data Control Language (DCL) - comandos utilizados para controlar o acesso e gerenciar permissões de usuários no banco de dados;                             Transactional Control Language (TCL) - são comandos utilizados para gerenciar as mudanças feitas por instruções DML;                                                    Data Query Language (DQL) - utiliza-se do comando SELECT para consulta dos dados.
A nova demanda de flexibilidade e escalabilidade das aplicações por conta do volume de dados, velocidade de processamento e/ou falta de estrutura fixa dos dados, em muitos casos emerge o uso de sistemas gerenciados de banco de dados não relacionais, também  conhecidos  como SGBDs  NoSQL.

 
### **Bancos NoSQL**

Os bancos de dados NoSQL (não-relacionais) utilizam um padrão diferente de armazenamento em relação aos bancos SQL e são  classificados  de  acordo  com  a forma  em que  os dados  são  persistidos. Eles podem, ainda,  processar grandes volumes de dados não estruturados e que estão mudando constantemente.
Entre os principais tipos de SGBD NoSQL temos:

Chave-valor;  Colunar;  Grafo; e  Documento.
Tipo  Chave-valor:  todos  os  registros  compõem  a mesma coleção (Tabela) e a única característica em comum entre os registros é uma chave única (Hash), sendo o modelo mais simples e fácil de implementar. Exemplo, Riak;

Tipo Coluna:  todos os registros fazem parte da mesma tabela, sendo que as colunas variam de acordo com os registros. Esse tipo de banco é otimizado para colunas de leitura e gravação, ao contrário dos SGBDs relacionais que são linhas de dados. Exemplo, Cassandra;

  Tipo Grafo:  os registros são representados como nós e os relacionamentos como arestas, formando um grafo. Exemplo, Neo4j8
Tipo  Documento:  cada  registro  fica  armazenado  em um arquivo específico, geralmente em formato JSON (JavaScript Object Notation) ou XML (eXtensible  Markup  Language),  dentro  de  uma  coleção.  Diferente  dos  SGBDs relacionais, o esquema dos documentos pode variar, permitindo maior flexibilidade e o tamanho do documento torna-se variável.  Exemplo, MongoDB

Atualmente as empresas sofrem um crescente volume de dados, onde as aplicações devem ser preparadas para suportar esta grande demanda, focando em um tempo de resposta satisfatório,  visto  que há uma grande quantidade de  usuários,  o  que culmina em mudanças na engenharia de dados e software.
Nos últimos anos os avanços da tecnologia e a demanda por soluções cada vez mais robustas, tornaram obsoletas as soluções de banco de dados tradicionais, que em sua natureza  permitiam  o  armazenamento  e  manipulação  de  dados  apenas  em  formato alfanumérico. Essa nova demanda exige o armazenamento de imagens, streams de áudio e vídeo, dados de informações geográficas entre outras formas.

 Big data é uma realidade para muitas empresas, culminando em um desafio. O mercado demanda profissionais que estejam atualizados e saibam lidar com esse novo cenário. Big Data não é simplesmente trabalhar com grande volume de dados, mas saber tratá-los e manipulá-los em diversos formatos diferentes. Exemplos que podem ser citados são dados econômicos e de saúde, muitas vezes encontrados em arquivos de Excel, CSV (Comma-separated values) ou texto. Essa diversidade de dados é algo crescente e até mesmo soluções simples podem se tornar interessantes para o uso de um SGBD NoSQL. Nesse contexto é imprescindível que o engenheiro de dados esteja munido de conhecimento plausível acerca dos principais SGBDs NoSQL, suas funcionalidades e aplicações. 

