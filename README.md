## Previsão de Vendas Rede de Farmácias

**Sobre**

Este projeto visa desenvolver modelo preditivo de vendas da rede de farmácias Rossmann

Contexto: A presidência da rede de farmácia nos contratou para auxiliá-los prever o comportamento das vendas com base nas informações sazonais das lojas para contribuir no planejamento de investimentos do ano seguinte.

Nossa abordagem incluiu a Análise Exploratória dos Dados para melhor entender os dados e fornecer insights relevantes por meio da elaboração de hipóteses de negócio. Posteriormente, desenvolvemos um modelo de machine learning para identificar padrões das diversas lojas e capturar o movimento sazonal de cada uma delas.

**Principais Insights da EDA:**

- Lojas com mais variedade de produtos tende a vender menos (Veja EDA - H1)
- **Atenção:** Lojas com promoções ativas por longos períodos de tempo, ou com promoções consecutivas, perdem o atrativo e passam a vender menos. (Veja EDA - H3 e H5)

**Resultado do modelo preditivo:**

Elaborado modelo de Regressão para encontrar o padrão dos dados. Na média, nos testes o modelo obteve margem de erro percentual de 9.5%. O que representa um bom resultado a julgar pela complexidade do caso e a finalidade do projeto.

O modelo não foi capaz de capturar o padrão de vendas das lojas 297 e 915, apresentando erro percentual superior a 50%. Por esse motivo, recomendamos que desprezem a previsão do modelo adotem a média simples da sazonalidade sobre estas duas lojas.


**Notebooks Jupyter:**

* Dois notebooks fazem parte do projeto: "EDA", "Modeling", cada um dedicado a diferentes fases do desenvolvimento.

**Requisitos:**

* Um arquivo requirements.txt lista todas as ferramentas necessárias para reproduzir o projeto.

**Estrutura do Projeto:**

* Dois subdiretórios compõem o projeto: "encoders", visando uma futura implementação de api, e o diretório de dados fonte, chamado "data" e o diretório de imagens, chamado de "img"
