<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
  <h1>Análise de Vendas com Python e Plotly</h1>

  <p>Este projeto realiza uma análise de dados de vendas a partir de um arquivo Excel e gera um gráfico interativo para visualizar as vendas por vendedor e produto.</p>

  <h2>Funcionalidades</h2>
  <ul>
    <li>Lê dados de vendas de um arquivo Excel (<code>dados_vendas.xlsx</code>).</li>
    <li>Limpa e processa os dados, convertendo valores monetários para o formato numérico correto.</li>
    <li>Agrupa as vendas por vendedor e produto, calculando a quantidade total vendida e o valor total das vendas para cada combinação.</li>
    <li>Gera um gráfico interativo de barras agrupadas usando a biblioteca Plotly Express, mostrando:
      <ul>
        <li>Vendedores no eixo x.</li>
        <li>Quantidade vendida e valor total no eixo y, representados por barras agrupadas.</li>
        <li>Produtos diferenciados por cores.</li>
      </ul>
    </li>
    <li>O gráfico permite interações como passar o mouse sobre as barras para ver os valores, clicar na legenda para mostrar/ocultar produtos, etc.</li>
  </ul>

  <h2>Arquivos</h2>
  <ul>
    <li><code>dados_vendas.xlsx</code>: Arquivo Excel contendo os dados de vendas.</li>
    <li><code>analise_vendas.py</code>: Script Python que realiza a análise de dados e gera o gráfico.</li>
  </ul>

  <h2>Bibliotecas Utilizadas</h2>
  <ul>
    <li><code>pandas</code>: Para manipulação e análise de dados.</li>
    <li><code>plotly.express</code>: Para criação de gráficos interativos.</li>
  </ul>

  <h2>Como Executar</h2>
  <ol>
    <li>Certifique-se de ter o Python instalado em seu sistema.</li>
    <li>Instale as bibliotecas necessárias: <code>pip install pandas plotly</code>.</li>
    <li>Coloque o arquivo <code>dados_vendas.xlsx</code> na mesma pasta do script <code>analise_vendas.py</code>.</li>
    <li>Execute o script: <code>python analise_vendas.py</code>.</li>
    <li>O gráfico interativo será exibido em seu navegador padrão.</li>
  </ol>

  <h2>Observações</h2>
  <ul>
    <li>O arquivo <code>dados_vendas.xlsx</code> deve seguir o formato especificado no script (colunas "Vendedor", "Produto", "Quantidade", "Total").</li>
    <li>Você pode personalizar o gráfico alterando os parâmetros da função <code>px.bar</code> e do método <code>update_layout</code>.</li>
  </ul>

  <h2>Autor</h2>
  <p>[Seu Nome]</p>

  <h2>Licença</h2>
  <p>[Escolha uma licença, por exemplo, MIT]</p>
</body>
</html>
