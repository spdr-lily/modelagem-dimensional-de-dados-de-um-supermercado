# **Projeto de Cubo de Dados para Análise de Supermercado**

## **1\. Introdução**

Este relatório detalha o projeto de construção de um cubo de dados tridimensional para análise de dados de um supermercado hipotético. O projeto utiliza a biblioteca Pandas em Python para manipular e analisar os dados, visando fornecer insights sobre as vendas e outras métricas relevantes do supermercado.

## **2\. Objetivos**

O principal objetivo deste projeto é construir um cubo de dados que permita a análise multidimensional das vendas do supermercado. Os objetivos específicos incluem:

* Manipular e estruturar os dados de vendas utilizando Pandas.  
* Visualizar as relações entre diferentes variáveis, como preço unitário, quantidade e linha de produto.  
* Preparar os dados para análises mais aprofundadas, como a identificação de tendências de vendas e a avaliação do desempenho de diferentes produtos e filiais.

## **3\. Metodologia**

O projeto foi desenvolvido seguindo os passos descritos abaixo:

1. **Importação de Bibliotecas**: As bibliotecas Pandas, Numpy e Matplotlib foram importadas para manipulação de dados, cálculos numéricos e visualização, respectivamente.  
2. **Simulação de Dados**: Foi criado um conjunto de dados simulado de vendas de supermercado, contendo informações como:  
   * `id_fatura`: Identificador da fatura.  
   * `filial`: Identificador da filial do supermercado.  
   * `tipo_cliente`: Tipo de cliente (Membro ou Normal).  
   * `genero`: Gênero do cliente.  
   * `linha_produto`: Categoria do produto.  
   * `preco_unitario`: Preço de cada unidade do produto.  
   * `quantidade`: Número de unidades vendidas.  
   * `total`: Valor total da venda.  
   * `custo_produtos_vendidos`: Custo total dos produtos vendidos.  
   * `margem_bruta`: Margem bruta da venda.  
3. **Criação do DataFrame**: Os dados simulados foram utilizados para criar um DataFrame do Pandas, que é a estrutura de dados principal para a manipulação e análise.  
4. **Mapeamento de Linhas de Produtos**: As linhas de produtos (Alimentos, Higiene, Limpeza e Eletrônicos) foram mapeadas para valores numéricos para facilitar a análise quantitativa.  
5. **Visualização dos Dados**: Foi criado um scatter plot para visualizar a relação entre o preço unitário, a quantidade vendida e a linha de produto. Este gráfico ajuda a identificar padrões e possíveis correlações entre essas variáveis.

## **4\. Resultados**

Os principais resultados do projeto incluem:

* Um DataFrame contendo os dados de vendas do supermercado, estruturado e pronto para análise.  
* Um mapeamento das linhas de produtos para valores numéricos, permitindo a inclusão dessas categorias em análises quantitativas.  
* Um scatter plot que visualiza a relação entre preço unitário, quantidade e linha de produto, oferecendo insights sobre como esses fatores se relacionam.

## **5\. Análise do Scatter Plot**

O scatter plot gerado mostra a relação entre preço unitário, quantidade e linha de produto. A cor dos pontos representa as diferentes linhas de produtos, permitindo visualizar como cada categoria se distribui em relação ao preço e à quantidade.

* **Preço Unitário vs. Quantidade**: O gráfico permite observar se há alguma correlação entre o preço dos produtos e a quantidade vendida. Por exemplo, pode-se identificar se produtos mais caros tendem a ser vendidos em menor quantidade ou vice-versa.  
* **Linha de Produto**: A diferenciação por cores ajuda a identificar se certas categorias de produtos têm faixas de preço ou volumes de venda específicos.  
* **Padrões e Outliers**: O gráfico também pode revelar padrões gerais nos dados, como clusters de produtos com características semelhantes, e a presença de outliers, que são pontos de dados que se desviam significativamente do padrão geral.

## **6\. Conclusões**

Este projeto demonstrou a construção de um cubo de dados básico para análise de vendas de supermercado utilizando Pandas. A manipulação e visualização dos dados permitem obter insights iniciais sobre as relações entre diferentes variáveis.
