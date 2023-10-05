# dex_case_pbi

Escopo do projeto

Os dados estão em anexo que contém uma série de informações e que você tem liberdade para nos apresentar novos indicadores, mas queremos ver ao menos:

Total Vendido;
Total Vendido por Ano/Semestre/Trimestre/Mês;
Quantidade de Vendas por Tipo de Promoção;
Total Faturado por País;  - Conceito de faturamento 
Ticket Médio, considerando que é o Total Vendido divido pela quantidade distinta de pedidos.
Ticket Médio por Categoria de Produto/Subcategoria e Produto.
Top 10 empregados pelo Total Vendido;
Preço Unitário Médio por Linha de Produto (ProductLine) das Lojas;
 

Quanto à exibição de gráficos e layout fique à vontade em explorar da melhor forma, bem como utilizar um layout moderno e clean.


--------------------------------------------------------------------------------------------------------------------------------------------------------------------

Porjeto dashboad "DEX BICYCLE FACTORY"


ETAPAS DO PROJETO

Estudo e manipulação das fontes de dados
Criação do "shell" com os requisitos mínimos solicitados
Definição e criação do layout do painel
Identificação de insights e indicadores extras


1. Estudo e manipulação das fontes de dados:

Realizei um estudo das fontes disponíveis e criei um dicionário de dados para entender o significado de cada campo e o tipo de dado.
Importei os dados para o Power BI Desktop e efetuei tratamentos, como a alteração do tipo de dado das colunas e a remoção de linhas e colunas em branco ou desnecessárias.

2.Criação do "shell" com os requisitos mínimos solicitados:

Nesta etapa, contrui a dimensão calendário e estabeleci relacionamentos entre as tabelas usando a metodologia Star Schema, com relacionamentos 1 para muitos, unidirecionais, ligando as tabelas dimensão à tabela fato.
Desenvolvi fórmulas DAX, como as da tabela DIM_CALENDARIO e as relácionadas aos requisitos mínimos do escopo.

3.Definição e criação do layout do painel:

Considerando o contexto das fontes de dados (uma fábrica que vende materiais de ciclismo), criei o design do painel com a persona "DEX Bicycle Factory" em mente.
Utilizei as cores principais cinza e vermelho, destacando o vermelho em pontos de relevância.
Os backgrounds foram criados no Figma.

4.Identificação de insights e indicadores extras:

Nesta fase, incorporamos insights identificados durante a análise exploratória dos dados, que não eram obrigatórios para o projeto original.
