#  Tópicos avançados de Bancos Relacionais ( SQL ) para Bancos não relacionais ( NoSQL )

## ![Captura de tela 2023-03-29 123613](https://user-images.githubusercontent.com/106993667/228523647-afa5e629-dd61-4f2f-8371-f8a349b8b699.png) x  ![Captura de tela 2023-03-29 123232](https://user-images.githubusercontent.com/106993667/228522957-b0c1c950-c9c1-47a2-8b50-464a53759873.png)

Com o SQL, você pode executar vários comandos para criar, alterar, gerenciar, consultar, dentre outras informações no seu banco de dados. Já o NoSQL foi criado para ter uma performance melhor e uma escalabilidade mais horizontal para suprir necessidades onde os bancos relacionais não são eficazes.
 
 ## Vantagens de um banco de dados SQL
  - Escalabilidade - A facilidade de manipulação dos dados no banco tornam o SQL uma ótima escolha para bancos de dados de grande porte ou com previsão de alta escalabilidade.
  -  Manutenção - O SQL conta com recursos nativos de automação de processos de reparo, manutenção e controle do banco de dados. 
  - Velocidade - A performance dos bancos de dados SQL é de alta eficiência, com mínimo uso de memória RAM, menor carga da CPU e um menor custo de armazenamento.
  - Flexibilidade - Bancos de dados SQL permitem que o administrador faça alterações no banco sem interromper suas opções, isto é, torná-lo temporariamente indisponível.
 
 ## Vantagens de um Banco de Dados NoSQL
 - Mais liberdade - BDs NoSQL permitem que se armazene informação estruturada, semiestruturada e não estruturada. Além da flexibilidade, bancos de dados NoSQL permitem que a informação seja armazenada no formato apropriado ou necessário para que outras aplicações façam uso dela.
 - Esquema dinâmico - Num BD NoSQL, é possível e bastante fácil alterar a estrutura da informação já armazenada. Isso aumenta suas possibilidades de uso e o valor agregado do banco de dados.
 - O NoSQL foi criado para ter uma performance melhor e uma escalabilidade mais horizontal para suprir necessidades onde os bancos relacionais não são eficazes. No geral, temos 5 tipos de bancos de dados NoSQL:
 
   - Documento:
     - Os dados são armazenados como documentos. Os documentos podem ser descritos como dados no formato de chave-valor, como por exemplo, o padrão JSON.
 Um exemplo de banco de dados neste formato é o MongoDB.
   - Colunas:
     - Os dados são armazenados em linhas particulares de tabela no disco, podendo suportar várias linhas e colunas, além de permitir sub-colunas.
 Um banco de dados dessa família, por exemplo, é o Cassandra.
   - Grafos:
     - Os dados são armazenados na forma de grafos (vértices e arestas).
 O Neo4j é um banco que utiliza grafos.
   - Chave-valor:
     - Essa família de bancos NoSQL é a que aguenta a maior carga de dados, pois o conceito dela é que um determinado valor seja acessado através de uma chave identificadora  única.
 Um exemplo é o banco de dados Riak.
 
 ![Captura de tela 2023-03-29 115916](https://user-images.githubusercontent.com/106993667/228515002-34151061-f904-4e5e-bd89-5829e347737d.png)

 ## Diferenças entre Bancos de Dados SQL e NoSQL
 Modelos de dados - Nos bancos de dados SQL ou relacionais, as informações são necessariamente armazenadas em forma de linhas e colunas.
 Nos bancos NoSQL (não-relacionais), os dados podem ser armazenados em documentos, colunas, key values e gráficos.
 Escalabilidade - Bancos de dados relacionais lidam com a escalabilidade de forma vertical, aumentando a carga do servidor.
 Enquanto isso, os BDs não-relacionais escalam de maneira horizontal, fragmentando a carga entre diferentes instâncias de servidor.
 
