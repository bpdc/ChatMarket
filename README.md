# ChatMarket
Se gostou do projeto, deixe uma ⭐️<strong> [pt_br] </strong> <br>
If you enjoyed the project, leave a ⭐️<strong> [en] </strong>

<h2> Descrição Geral / General Description 🌐 </h2>

O ChatMarket é uma solução conversacional orientada a dados (data-driven) desenvolvida para a exploração analítica de hábitos de consumo no comércio eletrônico alimentar (*e-grocery*). Integrando a API do Google Gemini e o framework Chainlit, a aplicação consome registros transacionais consolidados da Instacart, permitindo que analistas e gestores obtenham respostas assertivas e contextuais sobre comportamento de recompra, fluxos de carrinho e padrões temporais de compra sem a necessidade de escrita manual de consultas SQL. <strong> [pt_br] </strong>
<br>
<br>
ChatMarket is a data-driven conversational solution developed for the analytical exploration of consumer habits in online grocery retail (e-grocery). Integrating the Google Gemini API and the Chainlit framework, the application queries consolidated transactional records from Instacart, allowing analysts and decision-makers to retrieve contextual insights regarding repeat purchase behavior, cart dynamics, and temporal order patterns without manually writing SQL queries. <strong> [en] </strong>

<h2> Sobre o Dataset / About the Dataset 📊 </h2>

O projeto utiliza como base o conjunto oficial **"The Instacart Online Grocery Shopping Dataset"**, disponibilizado publicamente pela empresa no Kaggle. Os dados foram tratados e agregados via Python (Pandas) gerando uma visão transacional analítica única e anonimizada. <strong> [pt_br] </strong>

* **Fonte oficial / Official Source:** [Instacart Market Basket Analysis (Kaggle)](https://www.kaggle.com/c/instacart-market-basket-analysis/data)
* **Arquivos do repositório / Repository Files:**
  * `instacart_consolidado.csv`: Base analítica unificada resultante do pré-processamento relacional.
  * `instacart_1000.csv`: Amostra controlada de 1.000 registros para otimização de latência e limites de contexto do LLM.
* **Principais atributos / Key Features:**
  * `order_id`: Identificador exclusivo da compra / Unique order identifier.
  * `product_name`: Nome comercial do item / Commercial product name.
  * `department`: Departamento do supermercado (ex.: *produce*, *dairy eggs*) / Supermarket department.
  * `aisle`: Corredor ou gôndola específica / Specific supermarket aisle.
  * `order_dow`: Dia da semana da compra (0 a 6) / Day of week (0 to 6).
  * `order_hour_of_day`: Horário da transação (0 a 23h) / Purchase hour (0 to 23h).
  * `days_since_prior_order`: Intervalo em dias desde o último pedido / Days elapsed since prior order.
  * `reordered`: Indicador binário de recompra (1 = recorrente, 0 = novo) / Repeat purchase indicator (1 = recurrent, 0 = first-time).

<h2> Tecnologias Utilizadas / Technologies Used 💻 </h2>

* [Python](https://www.python.org/): Linguagem principal para análise de dados e backend da aplicação [pt_br]
* [Python](https://www.python.org/): Core language used for data analysis and backend logic [en]
* [Pandas](https://pandas.pydata.org/): Utilizado para extração, limpeza, engenharia de atributos e junção relacional dos dados [pt_br]
* [Pandas](https://pandas.pydata.org/): Used for extraction, cleaning, feature engineering, and relational merges [en]
* [Chainlit](https://docs.chainlit.io/): *Framework* web para construção da interface de chat interativa [pt_br]
* [Chainlit](https://docs.chainlit.io/): Web framework used to build the interactive conversational interface [en]
* [Google Gemini API](https://ai.google.dev/): Modelo de linguagem multimodal aplicado à inferência e contextualização analítica [pt_br]
* [Google Gemini API](https://ai.google.dev/): Multimodal large language model applied for business data inference and reasoning [en]
* [Jupyter Notebook](https://jupyter.org/): Ambiente empregado na execução da Análise Exploratória de Dados (EDA) [pt_br]
* [Jupyter Notebook](https://jupyter.org/): Environment used for running the Exploratory Data Analysis (EDA) [en]

## 📌 ChatMarket - Informações importantes sobre a aplicação / ChatMarket - Important Information 📌

<p>Projeto acadêmico desenvolvido durante o curso de Bacharelado em Sistemas de Informação na Universidade Presbiteriana Mackenzie, como parte da disciplina de Inteligência Artificial, integrando técnicas de Ciência de Dados, Análise Exploratória e Inteligência Artificial Generativa para suporte à decisão corporativa. <strong>[pt_br]</strong></p>
<p>Academic project developed during the Bachelor's degree in Information Systems at Mackenzie Presbyterian University, as part of the Artificial Intelligence course, integrating Data Science techniques, Exploratory Data Analysis, and Generative Artificial Intelligence for enterprise decision support. <strong>[en]</strong></p>

<h2> Integrantes 🔽 </h2>
<ul>
  <li> Beatriz Pimenta de Camargo </li>
  <li> Daniela Pereira da Silva </li>
  <li> Ricardo Lins Pires </li>
  <li> Valéria Oliveira de Almeida </li>
</ul>

<p>If you have any questions or suggestions about this project, feel free to contact me via email at <a href="mailto:beatriz_de_camargo@hotmail.com">beatriz_de_camargo@hotmail.com</a>. <strong> [en] </strong></p>
