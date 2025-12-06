 ##Projeto:Modelando um Dashboard de E-commerce com Power BI Utilizando Fórmulas DAX.

 Neste desafio de projeto, meu objetivo foi transformar a tabela única Financial Sample em um modelo dimensional completo baseado em star schema. Para isso, comecei criando uma cópia da tabela original, chamada Financials_origem, que deixei oculta apenas como backup e referência. A partir dela, iniciei o processo de separar e reorganizar os dados em tabelas fato e dimensão, garantindo uma estrutura mais limpa, analítica e otimizada para consultas.

Em seguida, passei a construir as dimensões. Criei a D_Produtos, selecionando apenas as informações essenciais sobre os produtos e adicionando métricas derivadas, como média de unidades vendidas, média e mediana do valor de vendas, além dos valores máximo e mínimo. Depois, desenvolvi a D_Produtos_Detalhes, onde inclui informações mais detalhadas, como Discount Band, Sale Price, Units Sold e Manufactoring Price. Para complementar essas informações, também construí a dimensão D_Descontos, agrupando dados de desconto e faixas de desconto por produto.

Outra etapa importante foi criar a D_Detalhes, onde concentrei informações que não foram contempladas nas dimensões anteriores, mas que ainda assim agregam contexto relevante sobre vendas. Além disso, construí a D_Calendário utilizando a função DAX CALENDAR(), permitindo trabalhar com análises baseadas em tempo e facilitando relacionamentos com a tabela fato.

Com as dimensões definidas, avancei para a construção da tabela fato F_Vendas, onde reuni os dados principais relacionados às transações: chaves substitutas, produto, unidades vendidas, preço, desconto, país, segmento, vendedor, lucro e datas. Também criei novas colunas derivadas a partir de condicionais, como o Índice de Produtos, exemplificando o uso de funções DAX para enriquecer a modelagem.

Após organizar e revisar todas as tabelas, finalizei a estrutura reposicionando colunas, garantindo consistência e um layout mais limpo para o esquema em estrela. Por fim, salvei o projeto .pbix e capturei a imagem do diagrama dimensional para adicionar ao meu repositório no GitHub. No README, descrevi todo o processo de construção, detalhei as etapas, as funcionalidades utilizadas e as funções DAX aplicadas. Dessa forma, transformei esse desafio em um projeto bem documentado e útil tanto para estudos quanto para demonstrar minhas habilidades a outros profissionais e recrutadores.
 
 
