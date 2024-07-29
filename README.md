## Instruções gerais
- O presente repositório e seu conteúdo é de caráter pessoal e privado, não podendo ser compartilhado pelo candidato por quaisquer meios.
- A solução do exercício deverá ser elaborada única e exclusivamente pelo candidato, sem ajuda **pessoal** externa. Obviamente, não há problemas em caso de consultas em livros ou meios eletrônicos (não é permitida a submissão das questões deste teste em fóruns e comunidades online).
- O exercício em questão é fictício e não é parte de qualquer projeto real desenvolvido ou em desenvolvimento pela Kognita Lab.
- O exercício tem caráter classificatório, e não eliminatório. Portanto, caso tenha algum problema e não consiga resolver todo o exercício, envie a solução até onde conseguiu evoluir.
- A solução deverá ser entregue num repositório à parte, criado pelo candidato.
- Linguagem: Python.
- O prazo para entrega do exercício é de 1 semana. 

<br></br>
## Dados disponibilizados:

- "_data/pontos_interesse_geograficos.parquet": pontos de interesse (estabelecimentos comerciais e afins) geolocalizados.
- "_data/unidades_faturamento.parquet": dataset contendo as unidades geolocalizadas e o faturamento mensal das mesmas.



<br></br>
## Contexto de negócio do exercício

Os dados disponibilizados em "_data/unidades_faturamento.parquet" se referem a uma rede de varejo do segmento alimentício (doces e chocolates). Tal rede, que carece de um departamento de expansão e de análise geoespacial, deseja ter uma visão mais aprofundada de seu posicionamento geográfico no estado de São Paulo.



<br></br>
## Questões

1. Determinar os pontos de interesse geográficos (POIs) localizados dentro de cada município, e mapear as categorias relacionadas a potenciais concorrentes. (Tempo estimado: 2h)

2. Plotar, usando uma escala de cores adequada, um mapa da quantidade total de POIs por município. (Tempo estimado: 2h)

3. Para cada uma das top 5 categorias de POIs (em termos de quantidade), fazer o mesmo que o item 2. (Tempo estimado: 1h)

4. Para as categorias de POIs que foram identificadas como possíveis concorrentes, fazer o mesmo que o item 2. Considere as categorias agrupadas para gerar apenas 1 mapa. (Tempo estimado: 1h)

5. Para os dados utilizados para gerar os 7 mapas acima, determinar a correlação espacial (coeficiente I de Moran global) da quantidade de POIs no nível de município. (Tempo estimado: 4h)

6. Plotar os dados de faturamento (considere a mediana do faturamento no período disponibilizado) exibindo informações de lat long e o faturamento no "hover" do mouse sobre o ponto. (Tempo estimado: 1h)

7. Baseado no faturamento histórico, determinar programaticamente quais unidades estão com tendência de alta ou de baixa no faturamento. Adicionar essa informação de alta ou baixa no gráfico do item 6. (Tempo estimado: 5h)

8. Plotar o faturamento médio por município usando alguma escala de cores que julgue razoável.
(Tempo estimado: 1h)

9. Idem para o faturamento médio por 100 mil habitantes. (Tempo estimado: 1h)

10. Dada a tabela de faturamentos fictícios, determinar a correlação espacial (coeficiente I de Moran global) do faturamento total no nível de município. (Tempo estimado: 2h)

11. Dadas as análises elaboradas, que conclusões consegue extrair do estudo? Caso seja útil, fique à vontade para explorar outros tipos de análises adicionais. (Tempo estimado: 5h)




<br></br>
## Informações adicionais
- Tempo total estimado para a realização do teste: 25h
- Bibliotecas suficientes para a realização do teste: plotly, pysal, geobr, geopandas, pandas, numpy e scikit-learn.
- A entrega pode ser feita em 1 ou mais notebooks, e as questões precisam estar claramente identificadas.
