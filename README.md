<h1>Engenharia de Dados - Rox Partner</h1>

<h4>O PRESENTE PROBLEMA SE REFERE AOS DADOS DE UMA EMPRESA QUE PRODUZ BICICLETAS.</h4>

<ol>
<li>Fazer a modelagem conceitual dos dados;</li>
<li>Criação da infraestrutura necessária;</li>
<li>Criação de todos os artefatos necessários para carregar os arquivos para o banco criado;</li>
<li>Desenvolvimento de SCRIPT para análise de dados;</li>
<li>Criar um relatório em qualquer ferramenta de visualização de dados.</li>
</ol>

<br>

<p>Os seguintes <a href="https://github.com/BYTE-JoseLucas/TesteRoxPartner/tree/main/arquivosBrutosCSV"> arquivos</a> devem ser importados (ETL) para o banco de dados de sua escolha:</p>
<li>Sales.SpecialOfferProduct.csv</li>
<li>Production.Product.csv</li>
<li>Sales.SalesOrderHeader.csv</li>
<li>Sales.Customer.csv</li>
<li>Person.Person.csv</li>
<li>Sales.SalesOrderDetail.csv</li>

<br>

<h4>RESOLUÇÃO</h4>
<p>
Para a realização deste teste, você deve utilizar alguma das principais nuvens públicas (Azure, AWS, GCP). Pedimos também que compartilhe conosco o código fonte (preferencialmente através de um repositório git público). 
A nossa expectativa é um processo de ingestão de dados utilizando os serviços da nuvem escolhida.
Além disso, inclua um arquivo README.md onde você deve compartilhar as decisões de arquitetura, implementação e instruções sobre como executar o software. Caso tenha criado um relatório em alguma ferramenta de visualização de dados, inclua um screenshot do mesmo no arquivo.
</p>

<br>

<h4>ANÁLISE DE DADOS</h4>
<p>Com base na solução implantada responda aos seguintes questionamentos:</p>
<ol>
<li>Escreva uma query que retorna a quantidade de linhas na tabela Sales.SalesOrderDetail pelo campo SalesOrderID, desde que tenham pelo menos três linhas de detalhes.</li>
<li>Escreva uma query que ligue as tabelas Sales.SalesOrderDetail, Sales.SpecialOfferProduct e Production.Product e retorne os 3 produtos (Name) mais vendidos (pela soma de OrderQty), agrupados pelo número de dias para manufatura (DaysToManufacture).</li>
<li>Escreva uma query ligando as tabelas Person.Person, Sales.Customer e Sales.SalesOrderHeader de forma a obter uma lista de nomes de clientes e uma contagem de pedidos efetuados.</li>
<li>Escreva uma query usando as tabelas Sales.SalesOrderHeader, Sales.SalesOrderDetail e Production.Product, de forma a obter a soma total de produtos (OrderQty) por ProductID e OrderDate.</li>
<li>Escreva uma query mostrando os campos SalesOrderID, OrderDate e TotalDue da tabela Sales.SalesOrderHeader. Obtenha apenas as linhas onde a ordem tenha sido feita durante o mês de setembro/2011 e o total devido esteja acima de 1.000. Ordene pelo total devido decrescente.</li>
</ol>
