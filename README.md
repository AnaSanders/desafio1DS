# Análise de Dados das Lojas

Este repositório contém um notebook do Google Colab (`AluraChallenge1DS.ipynb`) que realiza uma análise exploratória de dados de quatro lojas. O objetivo principal desta análise é fornecer insights valiosos sobre o desempenho de cada loja para auxiliar na tomada de decisões estratégicas de negócios.

## Propósito da Análise

A análise realizada busca responder a perguntas-chave sobre o desempenho das lojas, incluindo:

* Qual o faturamento total de cada loja?
* Quais categorias de produtos são mais e menos vendidas?
* Qual a média de avaliação dos clientes por loja?
* Quais produtos são os mais e menos vendidos em cada loja?
* Qual o custo médio de frete para cada loja?

Essas informações são cruciais para identificar pontos fortes e fracos de cada loja, otimizar a alocação de recursos e embasar decisões sobre o futuro das unidades.

## Estrutura do Projeto e Organização dos Arquivos

O projeto está organizado da seguinte forma:

* `AluraChallenge1DS.ipynb`: Este é o notebook do Google Colab que contém todo o código Python para a análise dos dados. Ele inclui a importação dos dados, limpeza, análise exploratória e visualização dos resultados.
* `data/`: Este diretório (que você deve criar, se necessário) deve conter os arquivos CSV com os dados de cada loja.
    * `loja_1.csv`: Dados da Loja 1.
    * `loja_2.csv`: Dados da Loja 2.
    * `loja_3.csv`: Dados da Loja 3.
    * `loja_4.csv`: Dados da Loja 4.

    **Observação:** Certifique-se de que os arquivos CSV estejam localizados no diretório `data/` ou ajuste os caminhos no notebook para que apontem para o local correto dos arquivos.

## Exemplos de Gráficos e Insights Obtidos

A análise gera diversos gráficos e fornece insights valiosos. Alguns exemplos incluem:

* **Gráfico de Pizza de Diferença de Faturamento:**

    * Este gráfico visualiza a diferença no faturamento entre as lojas, tomando a loja com o menor faturamento como base.
    * **Insight:** Permite identificar rapidamente quais lojas estão performando acima ou abaixo da média em termos de receita. Por exemplo, a análise revelou que a Loja 1 possui o maior faturamento, enquanto a Loja 4 apresenta o menor.

* **Análise de Avaliação da Compra:**

    * Gráficos de barras mostram a distribuição das avaliações dos clientes para cada loja.
    * **Insight:** Ajuda a entender o nível de satisfação dos clientes em cada unidade. Lojas com avaliações consistentemente altas indicam uma experiência positiva do cliente.

* **Análise de Categorias de Produtos:**

    * Gráficos de barras comparam o desempenho de diferentes categorias de produtos entre as lojas.
    * **Insight:** Permite identificar quais categorias são mais lucrativas em cada loja e quais podem precisar de mais atenção ou investimento.

* **Análise de Frete Médio:**

    * Valores de frete médio são calculados e comparados entre as lojas.
    * **Insight:** Lojas com custos de frete muito altos podem ter margens de lucro menores ou enfrentar dificuldades em atrair clientes.

## Instruções para Executar o Notebook

* Para executar a análise, siga as instruções abaixo:

    * Você precisará de uma conta no Google para usar o Google Colab.
    * Certifique-se de ter os arquivos CSV (`loja_1.csv`, `loja_2.csv`, `loja_3.csv` e `loja_4.csv`) disponíveis.
    * Faça o upload do notebook `AluraChallenge1DS.ipynb` para o seu Google Colab.
    * Execute as células do notebook sequencialmente. O Colab irá executar o código Python e exibir os resultados, tabelas e gráficos diretamente no notebook.
    * Após a execução completa do notebook, revise os resultados e gráficos gerados para obter insights sobre o desempenho de cada loja.
    * O notebook fornece análises detalhadas sobre faturamento, categorias de produtos, avaliações de clientes, produtos vendidos e custos de frete.
    * Use essas informações para tomar decisões informadas sobre as lojas.
