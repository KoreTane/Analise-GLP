<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="utf-8">
 
</head>
<body>

<h1>Análise-GLP</h1>
<p>O objetivo desta análise é responder três perguntas principais: Os preços do GLP variam no Brasil? Quem está pagando mais? Quem está pagando menos?
</strong></p>

<h2>O que iremos trabalhar?</h2>
<p>Dada a complexidade e o grande volume de dados envolvidos, utilizaremos <strong>Big Data</strong> com <strong>PySpark</strong>. Transformei os arquivos em <strong>Parquet</strong> para otimizar o armazenamento e melhorar a eficiência na leitura e processamento dos dados.</p>

<p>Integraremos os dados do governo com informações de localização do IBGE para realizar uma análise geoespacial. Através de técnicas estatísticas, como análise de séries temporais e modelagem preditiva, buscaremos identificar correlações significativas entre eventos climáticos extremos e as flutuações nos preços do GLP. Utilizaremos também visualizações dinâmicas para facilitar a interpretação dos resultados, permitindo uma compreensão mais clara das tendências.</p>



<h2>Os Preços do GLP Variam no Brasil?</h2>
<p>Na nossa análise, de um ano para o outro, não. Olhando geograficamente, sim, os preços do GLP variam significativamente no Brasil. O valor pago em média é de R$ 106,51, o desvio padrão está em 12,59 (essa será a referência de distância para valores abaixo e acima da média), ou seja, na maioria das vezes os valores pagos estão na faixa dos R$ 93,92 a R$ 119,10.</p>
<p>No valor final do gás, 8 em 10 consumidores estão pagando dentro da média, cerca de 1 em 10 pessoas pagam mais ou menos. Podemos notar que os maiores valores estão concentrados nas regiões Norte e Centro-Oeste, devido principalmente à distância das refinarias que estão localizadas na região Sudeste. Além disso, a infraestrutura de transporte e distribuição nessas regiões é menos desenvolvida, dentre outros fatores.</p>
<p>Curiosamente, preços entre R$ 101,00 e R$ 104,00 são raros, representando menos de 2% da nossa amostra, o que indica o uso de estratégias de precificação no mercado, incluindo a possibilidade de estratégias de preço psicologicamente atraentes.</p>

<h2>Quem Está Pagando Mais?</h2>
<p>É na região Norte onde encontramos os preços mais elevados; lá, quase metade dos consumidores pagam acima da média nacional, com valores variando de R$ 85,00 a R$ 155,00. O estado do Amazonas é onde se concentram os maiores preços da região e do país. Em Manaus (AM), cerca de 13,20% das pessoas pagam um valor acima de 15% em relação à média e, em Tefé (AM), encontramos o maior valor pago no Brasil: R$ 155,00.</p>
<p>O Centro-Oeste também possui preços elevados, com 1 em cada 5 pessoas pagando um valor superior a R$ 123,80.</p>

<h2>Quem Está Pagando Menos?</h2>
<p>A região Sudeste é a que está pagando o menor valor no Brasil; lá, 1 em 4 consumidores pagam um valor abaixo da média, com o preço girando em torno de R$ 100,37. No Nordeste, 1 em 7 pessoas pagam um valor médio em torno de R$ 102,06.</p>
<p>As maiores oscilações no preço ocorrem no terceiro trimestre do ano, possivelmente devido ao inverno, que aumenta a demanda por gás para geração de energia e aquecimento. Nos demais períodos do ano, o preço segue uma constante próxima à média. Vale salientar que, aparentemente, os valores no preço final do gás no Sul não sofreram alterações iminentes com os eventos climáticos extremos recentes.</p>
<p>O valor médio de venda do gás diminuiu em 2024 em relação a 2023, cerca de R$ 2,17, o que acompanha a baixa da inflação, que foi de 5,79% em 2023 e reduziu para cerca de 4,5% em 2024.</p>

<h2>A Bandeira Branca</h2>
<p>A bandeira branca é a mais comercializada, responsável por cerca de 1/4 do consumo de gás do brasileiro. Ela apresenta os menores valores, principalmente por não estar associada a grandes marcas, evitando custos operacionais adicionais, menos gastos com marketing e estrutura.</p>

<h2>Distribuição Média do Preço Final:</h2>
<ul>
  <li>Petrobras: 32,6%</li>
  <li>ICMS: 17,3%</li>
  <li>Distribuição e revenda: 50,2%</li>
</ul>
<p>O produto é livre de impostos federais.</p>

<h2>Fontes de Dados:</h2>
<ul>
  <li>IBGE (Cadastro de Localidades) <a href="https://agenciadenoticias.ibge.gov.br/agencia-sala-de-imprensa/2013-agencia-de-noticias/releases/14126-asi-ibge-disponibiliza-coordenadas-e-altitudes-para-21304-localidades-brasileiras">https://agenciadenoticias.ibge.gov.br/agencia-sala-de-imprensa/2013-agencia-de-noticias/releases/14126-asi-ibge-disponibiliza-coordenadas-e-altitudes-para-21304-localidades-brasileiras</a></li>
  <li>ANP (Preços do GLP) <a href="https://dados.gov.br/dados/conjuntos-dados/serie-historica-de-precos-de-combustiveis-e-de-glp">https://dados.gov.br/dados/conjuntos-dados/serie-historica-de-precos-de-combustiveis-e-de-glp</a></li>
  <li>Reportagem sobre o preço do gás em Tefé (2023) <a href="https://www.viomundo.com.br/voce-escreve/preco-do-gas-de-cozinha-supera-a-media-historica-em-71-cidades-tefe-no-am-botijao-custa-r-152.html">https://www.viomundo.com.br/voce-escreve/preco-do-gas-de-cozinha-supera-a-media-historica-em-71-cidades-tefe-no-am-botijao-custa-r-152.html</a></li>
</ul>

