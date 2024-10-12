<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="utf-8">
 
</head>
<body>

<h1>Análise-GLP</h1>
<p>Este projeto analisa a variação dos preços do gás liquefeito de petróleo (GLP) no Brasil entre janeiro de 2023 e agosto de 2024, levantando uma curiosidade: <strong>será que os eventos climáticos extremos realmente impactaram as vendas e preços?</strong></p>

<h2>O que iremos trabalhar?</h2>
<p>Dada a complexidade e o grande volume de dados envolvidos, utilizaremos <strong>Big Data</strong> com <strong>PySpark</strong>. Transformei os arquivos em <strong>Parquet</strong> para otimizar o armazenamento e melhorar a eficiência na leitura e processamento dos dados.</p>

<p>Integraremos os dados do governo com informações de localização do IBGE para realizar uma análise geoespacial. Através de técnicas estatísticas, como análise de séries temporais e modelagem preditiva, buscaremos identificar correlações significativas entre eventos climáticos extremos e as flutuações nos preços do GLP. Utilizaremos também visualizações dinâmicas para facilitar a interpretação dos resultados, permitindo uma compreensão mais clara das tendências.</p>

<h2>Fontes</h2>
<ul>
    <li><strong>Cadastro Localidades:</strong> O Cadastro de Localidades Brasileiras Selecionadas fornece informações detalhadas sobre 21.304 localidades, incluindo coordenadas geográficas e altitudes médias.</li>
    [[https://dados.gov.br/dados/conjuntos-dados/serie-historica-de-precos-de-combustiveis-e-de-glp](https://agenciadenoticias.ibge.gov.br/agencia-sala-de-imprensa/2013-agencia-de-noticias/releases/14126-asi-ibge-disponibiliza-coordenadas-e-altitudes-para-21304-localidades-brasileiras)](https://agenciadenoticias.ibge.gov.br/agencia-sala-de-imprensa/2013-agencia-de-noticias/releases/14126-asi-ibge-disponibiliza-coordenadas-e-altitudes-para-21304-localidades-brasileiras)
    <li><strong>Preço Combustíveis:</strong> A ANP monitora os preços do GLP por meio de uma pesquisa semanal, conforme estabelecido pela Lei do Petróleo (Lei nº 9478/1997).</li>
</ul>
https://dados.gov.br/dados/conjuntos-dados/serie-historica-de-precos-de-combustiveis-e-de-glp

</body>
</html>
