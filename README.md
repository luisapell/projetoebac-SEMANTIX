# Diagnóstico Precoce de Doenças Cardíacas com Machine Learning

Este projeto foi feito com base no curso da EBAC em Ciência de Dados, em parceria com a empresa SEMANTIX utilizado para aplicar os conhecimentos adquiridos durante o aprendizado do curso. 

### Objetivo do Projeto

<ul>
 <li> 
 Encontrar uma problemática da vida real que possa ser resolvido com o Machine Learning
</li>
<li> Expor algum problema e seus pontos </li> 
<li> Justificar o porquê dos dados serem usados para o resolvimento desse problema. </li>
</ul>

### Premissas do Projeto 

<li> Levantar os dados públicos em busca de alguma informação relevante </li> 
<li> Efetuar a análise exploratória dos dados e levantar principais pontos </li>
<li> Construir um aprendizado de máquina/modelo estatístico através de técnicas de modelagem </li> 
<li> Apresentar uma boa visualização dos dados com os resultados obtidos.</li>
<li>Você pode encontrar os dados em: https://catalog.data.gov/dataset/rates-and-trends-in-heart-disease-and-stroke-mortality-among-us-adults-35-by-county-a-2000-45659</li>

### Variáveis
O DataSet possui 20 variáveis/atributos, sendo: 

<li>Year: Ano dos dados, útil para analisar tendências temporais.</li>
<li>LocationDesc: Descrição da localização (ex.: nome do condado ou cidade).</li>
<li>DataSource: Fonte dos dados, pode ser útil para entender a origem dos dados.</li>
<li>Class: Classe das doenças (doenças cardiovasculares).</li>
<li>Topic: Tópico específico das doenças (ex.: doenças cardíacas).</li>
<li>Data_Value: Valor dos dados (taxa de doenças cardíacas), a variável-alvo.</li>
<li>Confidence_limit_Low: Limite inferior do intervalo de confiança, útil para entender a precisão dos dados.</li>
<li>Confidence_limit_High: Limite superior do intervalo de confiança.</li>
<li>StratificationCategory1: Categoria de estratificação (ex.: grupo etário).</li>
<li>Stratification1: Estratificação específica (ex.: idades 35-64 anos).</li>
<li>StratificationCategory2: Categoria de estratificação adicional (ex.: raça).</li>
<li>Stratification2: Estratificação específica adicional (ex.: indígena americano/nativo do Alasca).</li>
<li>StratificationCategory3: Categoria de estratificação adicional (ex.: sexo).</li>
<li>Stratification3: Estratificação específica adicional (ex.: geral).</li>
<li>LocationID: ID da localização, útil para indexação e agrupamento.</li>
<li>GeographicLevel: Nível geográfico (ex.: condado, estado), pode ser derivado de LocationDesc.</li>
<li>Data_Value_Unit: Unidade do valor dos dados (ex.: por 100.000), pode ser útil se houver diferentes unidades.</li>
<li>Data_Value_Type: Tipo de valor dos dados (ex.: taxa ajustada por idade), pode ser útil para entender o tipo de medida.</li>
<li>Data_Value_Footnote_Symbol: Símbolo de nota de rodapé do valor dos dados, pode ser descartado se não for relevante.</li>
<li>Data_Value_Footnote: Nota de rodapé do valor dos dados, pode ser descartado se não for relevante.</li>

### Considerações Finais

Fiz a escolha de estudar estes dados pois Doenças Cardíacas é uma das principais causas de morte no mundo atualmente. Estudando os dados obtidos e retirando um bom insight deles, haverá um apoio relacionado a redução significativa das mortes além de um tratamento médico mais eficaz para as vítimas. Ou seja, a utilização dessa análise de dados e machine learning para o diagnóstico precoce de doenças cardíacas pode contribuir para melhorar a gestão de saúde e permitir intervenções preventivas.

Para mais informações sobre o desenvolvimento do modelo, basta acessar o desenvolvimento do projeto junto com o pdf explicando os resultados finais. 



