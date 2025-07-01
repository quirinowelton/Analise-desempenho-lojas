# Análise de Desempenho de Lojas – Projeto Oracle ONE | Alura

## Descrição do Projeto

Este projeto realiza uma análise comparativa do desempenho de quatro lojas distintas (Loja 01, Loja 02, Loja 03 e Loja 04) utilizando um conjunto de métricas estratégicas. O objetivo é identificar qual loja seria a mais indicada para venda, considerando fatores como faturamento, vendas por categoria de produto, avaliação dos clientes, produtos mais e menos vendidos e custo médio de frete.

## Dados

Os dados utilizados para esta análise são provenientes de quatro arquivos CSV, cada um representando as vendas de uma loja específica:

*   `loja_1.csv`
*   `loja_2.csv`
*   `loja_3.csv`
*   `loja_4.csv`

Estes arquivos contêm informações detalhadas sobre cada transação de venda, incluindo:

*   `Produto`: Nome do produto vendido.
*   `Categoria do Produto`: Categoria à qual o produto pertence.
*   `Preço`: Preço unitário do produto.
*   `Frete`: Custo do frete para a entrega.
*   `Data da Compra`: Data em que a compra foi realizada.
*   `Vendedor`: Nome do vendedor responsável pela venda.
*   `Local da compra`: Localização da compra.
*   `Avaliação da compra`: Avaliação do cliente sobre a compra.
*   `Tipo de pagamento`: Método de pagamento utilizado.
*   `Quantidade de parcelas`: Número de parcelas do pagamento.
*   `lat`: Latitude da localização da compra.
*   `lon`: Longitude da localização da compra.

## Análises Realizadas

As seguintes análises foram conduzidas para avaliar o desempenho de cada loja:

1.  **Faturamento Total por Loja:** Cálculo e visualização do faturamento total gerado por cada loja.
2.  **Quantidade de Produtos Vendidos por Categoria:** Análise da distribuição e quantidade de produtos vendidos por categoria em cada loja.
3.  **Média das Avaliações dos Clientes:** Cálculo e visualização da média das avaliações de compra para cada loja, indicando a satisfação do cliente.
4.  **Produtos Mais e Menos Vendidos:** Identificação dos produtos com maior e menor volume de vendas em cada loja.
5.  **Custo Médio de Frete:** Cálculo e visualização do custo médio de frete por loja, indicando a eficiência logística.

## Conclusão e Recomendação

Com base nas análises detalhadas acima, a **Loja 01** é a mais indicada para ser vendida. Embora apresente o maior faturamento, esta loja também demonstra o maior custo médio de frete e a menor média de avaliação dos clientes. Estes fatores sugerem possíveis ineficiências operacionais e menor satisfação do cliente em comparação com as outras lojas. A venda da Loja 01 permitiria focar recursos e esforços nas demais operações que apresentam melhor desempenho em termos de custos de frete e satisfação do cliente, com maior potencial de crescimento sustentável a longo prazo.

## Como Executar o Código

Para replicar as análises realizadas neste projeto, siga os passos abaixo:

1.  Clone este repositório para o seu ambiente local.
2.  Certifique-se de ter o Python instalado, juntamente com as bibliotecas `pandas`, `seaborn` e `matplotlib`. Você pode instalá-las usando pip:
