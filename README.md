# Repositório de Análise de Dados para Relacionamentos Abertos

Este repositório contém notebooks do Google Colab desenvolvidos para auxiliar na análise de dados quantitativos relacionados a relacionamentos abertos, com foco em conceitos como paresia e compersão.  Os notebooks utilizam a linguagem Python e bibliotecas como Pandas, NumPy e Google Charts para gerar visualizações e análises estatísticas.

## Notebooks Incluídos:

* **`grafico_dispersao_compersao_satisfacao.ipynb`**: Este notebook demonstra como criar um gráfico de dispersão interativo usando o Google Charts diretamente no Google Colab. O gráfico visualiza a relação entre compersão e satisfação relacional, permitindo a diferenciação por tipo de relacionamento (e.g., swing, poliamor, aberto) através de cores.  O código inclui a conversão de dados do formato Pandas DataFrame para o formato exigido pelo Google Charts e a geração dinâmica do código HTML/JavaScript para exibição no Colab.  A legenda do gráfico é posicionada de forma otimizada e o tamanho dos pontos é ajustado para melhor visualização.

## Bibliotecas Utilizadas:

* **Pandas:** Para manipulação e análise de dados em formato tabular.
* **NumPy:** Para operações numéricas e geração de dados aleatórios.
* **Google Charts:** Para criação de gráficos interativos.
* **`google.colab.output`:** Para exibir o HTML/JavaScript do Google Charts diretamente no Colab.

## Recursos Adicionais:

* O código inclui comentários explicativos para facilitar a compreensão e adaptação.
* A geração do código HTML/JavaScript para o Google Charts é feita de forma dinâmica usando f-strings, o que melhora a legibilidade e a manutenção do código.
* O notebook demonstra boas práticas de visualização de dados, como o ajuste do tamanho dos pontos e o posicionamento otimizado da legenda.

## Como Usar:

1. Abra o notebook desejado no Google Colab.
2. Execute todas as células.
3. Os gráficos interativos serão exibidos diretamente na saída das células correspondentes.

## Observações:

* Certifique-se de ter as bibliotecas necessárias instaladas.  Você pode instalá-las usando `!pip install pandas numpy`.  Geralmente, o Colab já vem com essas bibliotecas pré-instaladas.
* O código foi desenvolvido e testado no Google Colab.  O comportamento em outros ambientes pode variar.


Este repositório fornece um ponto de partida para a análise de dados quantitativos em relacionamentos abertos.  Os notebooks podem ser adaptados e expandidos para explorar outras variáveis e gerar análises mais complexas.
