# Data driven insights


## Dados de amostra de vendas

    Esse dataset é sobre as vendas de uma empresa usado para estudo de caso para análise de dados com o intuito para aprimorar o aprendizado utizando as bibliotecas: pandas,numpy e matplotlib em conjunto com alguns recursos nativos do pyhton.



## Observações

    Foi criado uma variavel chamada vendas e chamei a biblioteca pandas e usei a função .read_csv( ) e entre passei o arquivo csv chamado dados-vendas para ser lido o dataset de amostra de vendas ,ao chamar a função .head(), foi mostrado as 5 primeiras linhas e as 25 colunas e alguns dados contidos no dataset, verifiquei com a função .shape o total de linhas e colunas, que retornou 25 linhas e 2823 colunas. Para ver quantas dimensões esse dataset possui usei a função .ndim que retornou duas dimensões, para saber os tipos de dados presença chamei a função .dtypes que retornou uma lista com os nomes das colunas e o tipo de dado correspondente que em quantidade são 7 int, 16 objet(string) e 2 float somando da 25. Com a função .describe( ) obtive uma descrição geral sobre a distribuição dos dados, mostrando valor minimo e máximo, a média, desvio padrão, e a porcentagem.
     Uma lista criada a partir de uma coluna chamada 'LINHA DE PRODUTOS' do dataset e usei a função .value_count para contar quantas vezes os nomes de certos paises aparecem na lista , essa coluna possui os nomes dos paises que fizeram pedidos e os nomes que mais aparecem no top 3 são: USA,Espanha e França. Um dicionario a partir das colunas ' CIDADE ' e ' ESTADO ', mostrando o nome da cidade e do estado e aparecem valores NaN(nulos). Foi utilizado uma tupla com base no dataframe usando a função .iloc()para localizar por indice a linha e coluna, as colunas usadas na tupla foi: ' CODIGO DE PRODUTO ',' LINHA DE PRODUTOS ',' QUANTIDADE PEDIDA '. Que retornou o código de um determinado produto, o nome do produto e quantidade pedida. Utilizando estruturas condicionais e de repetição, foi mostrado que a quantidade pedida de produtos é intermédiaria e o valor de quantidade somado deu 199, e em um intervalo até 30 o maior valor foi 34.  Calculado o total de vendas, e com as colunas ' VENDAS ' e 'PREÇO UNITARIO ' e uma nova coluna foi adicionada, e também foi calculado o desconto de 10% utilizando a coluna ' TOTAL DE VENDAS ' e uma nova coluna chamada ' DESCONTO ' foi criada. A finalidade da criação dessas colunas são mostrar o desconto de 10% aplicado em cada venda e mostrar o total de vendas.

    

