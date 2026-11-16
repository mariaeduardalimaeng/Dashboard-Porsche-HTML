# Dashboard-Porsche-HTML
Dashboard de vendas de modelos da porsche
# Quais perguntas de negócio você escolheu, e por quê?

Escolhi três perguntas de negócio principais para orientar o desenvolvimento da dashboard:

**1. Quais modelos apresentam maior variação de preço?**

Escolhi essa pergunta para identificar as diferenças de valores entre os modelos Porsche e compreender quais veículos apresentam maior variação de preço. Essa análise ajuda a entender o posicionamento dos modelos e as diferenças de valor dentro do portfólio.

**2. Existe uma família de veículos com crescimento de participação?**

Essa pergunta foi escolhida para identificar quais famílias de veículos estão ganhando maior participação nas vendas. O objetivo é observar o comportamento das vendas ao longo do tempo e identificar possíveis mudanças nas preferências dos consumidores.

**3. Quais modelos possuem maior procura em diferentes cidades?**

Escolhi essa pergunta para entender como a procura pelos modelos Porsche varia de acordo com a localização. Essa análise permite identificar diferenças de preferência entre cidades e compreender melhor o comportamento regional dos clientes.

Além dessas perguntas, defini indicadores principais para facilitar a análise, como total de vendas e receita, e filtros por modelo, cidade, ano e método de pagamento. Assim, a dashboard permite explorar os dados por diferentes perspectivas.

# O prompt que gerou a dashboard, e o que mudou até a versão final

O desenvolvimento começou com um prompt solicitando a criação de uma dashboard interativa em HTML, utilizando uma base de dados de vendas da Porsche.

A primeira orientação foi construir um painel que apresentasse informações comerciais de maneira organizada, com indicadores, gráficos e análises que ajudassem a responder perguntas de negócio.

**Exemplo do prompt consolidado utilizado como referência para o desenvolvimento:**

"Crie uma dashboard interativa em HTML para análise de vendas da Porsche, utilizando a base de dados fornecida. O painel deve apresentar indicadores de desempenho, como total de vendas e receita, além de gráficos que permitam analisar os modelos mais vendidos, variação de preços, participação das famílias de veículos e procura por cidade.

Adicione filtros interativos por modelo, cidade, ano e método de pagamento, permitindo que os dados sejam atualizados conforme a seleção do usuário.

Utilize um design elegante, moderno e sofisticado, inspirado na identidade visual da Porsche Brasil. A dashboard deve ter uma aparência profissional, ser responsiva e apresentar informações de maneira clara e intuitiva."

**O que mudou durante o desenvolvimento:**

- Ampliei as perguntas de negócio para tornar as análises mais estratégicas.
- Acrescentei filtros para permitir diferentes recortes dos dados.
- Incluí indicadores de topo, como total de vendas e receita.
- Ampliei a quantidade de gráficos e análises, incluindo informações sobre famílias de veículos, cidades, modelos e formas de pagamento.
- Aprimorei a identidade visual, buscando uma aparência mais sofisticada e alinhada à marca Porsche.
- Ajustei a organização dos elementos para melhorar a leitura e a experiência de navegação.

A versão final ficou mais completa, interativa e orientada à tomada de decisão, em vez de apresentar apenas gráficos e números.

# Que tratamento a base precisou antes de ir para a IA?

A base utilizada continha 100 registros de vendas. Durante a análise, foi identificada uma questão importante relacionada às datas: apenas 76 registros apresentavam datas válidas, enquanto outros continham datas inválidas ou futuras.

Por isso, foi necessário considerar a qualidade dos dados antes de realizar as análises temporais.

Os principais cuidados foram:

- Verificação da consistência das informações.
- Identificação de datas inválidas e datas futuras.
- Separação dos registros com datas válidas para análises temporais.
- Utilização dos campos tratados nas análises gerais e nos indicadores.
- Atenção para não considerar informações inconsistentes como se fossem dados confiáveis.

Dessa forma, foi possível reduzir o risco de interpretações incorretas e tornar os resultados da dashboard mais confiáveis.

# Você usou o ChatGPT com Canvas, um agente com skill, ou os dois?

Utilizei o ChatGPT com Canvas para desenvolver e aprimorar a dashboard em HTML.

O processo foi realizado de forma iterativa: comecei com uma estrutura inicial e, conforme analisava o resultado, solicitava alterações nos indicadores, gráficos, filtros, organização visual e funcionalidades.

O Canvas facilitou a edição e a evolução do código, permitindo trabalhar na construção da dashboard até chegar à versão final.

Não tenho registro de utilização de um agente com skill específico nesse projeto. Portanto, a ferramenta identificada no processo foi o ChatGPT com Canvas.

<img width="1220" height="873" alt="image" src="https://github.com/user-attachments/assets/23317fad-764c-4362-ae70-e46af732cb2d" />
<img width="1211" height="690" alt="{B6997592-B9E0-413B-AB33-BE1E13B5F4D1}" src="https://github.com/user-attachments/assets/ef30088e-f12c-4925-ba54-bb7530dca03b" />
<img width="1206" height="440" alt="{4E3F9563-B69D-40A1-91F2-51C43B56A984}" src="https://github.com/user-attachments/assets/d5b3985a-05bc-4c36-844a-4de406726a99" />
<img width="920" height="662" alt="{24F7A622-7A03-40E2-96DF-8F6783A2AB2D}" src="https://github.com/user-attachments/assets/7433f9d1-0962-42b2-9920-d24f37cb421f" />
<img width="909" height="510" alt="{3CFF9532-4718-4BB6-98EB-CEE865EA2860}" src="https://github.com/user-attachments/assets/01c70841-c2aa-4af5-ae15-453c4a934898" />

