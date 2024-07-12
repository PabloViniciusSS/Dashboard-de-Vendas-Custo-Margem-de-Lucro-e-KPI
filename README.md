
# Projeto Dashboard Analítico de Vendas, Custos, Margem de Lucro e KPI

No segundo projeto do curso da Data Science Academy focado em Power BI, estamos explorando a modelagem de dados, DAX e o relacionamento entre dados. Para esse capitulo vamos esta respondendo as seguintes perguntas:

1.  Qual foi o total de valor venda considerando cada modo de envio dos pedidos? Use um gráfico de cascata.

2.  Quais mercados tiveram o maior custo médio de envio dos produtos vendidos? Use um gráfico treemap.

3. A empresa tem como objetivo (meta) manter uma média de 350 para o valor de venda todos os meses. Mostre um indicador (KPI–Key Performance Indicator) com o valor médio de venda. A empresa ficou abaixo ou acima da meta no mês de Abril/2014?

4. Considere que o lucro é equivalente a:valor venda -custo envio. Qual categoria de produto apresentou maior lucro médio.

5. Qual foi o comportamento da margem de lucro ao longo do tempo? Considere amargem de lucro como o lucro dividido pelo valor venda

# Temas Explorados

O principal objetivo da modelagem de dados no Power BI é integrar informações provenientes de diferentes fontes. Isso é feito principalmente através de identificadores (IDs), que são chaves primárias. Ao estabelecer relacionamentos entre tabelas usando esses IDs, podemos garantir que os dados da Tabela X sejam corretamente relacionados e utilizados com os dados da Tabela Y. Essa etapa é crucial para evitar que o Power BI incorra em erros ao gerar análises, já que ele depende dessas conexões para realizar junções precisas entre os conjuntos de dados.

## Modelagem de Dados

A modelagem de dados é uma etapa em que o analista define a estrutura e as relações dos dados dentro das ferramentas de análise. Seu objetivo é organizar, armazenar e manipular os dados para atender aos requisitos específicos de análise e relatórios.

### Principais Aspectos:

- **Estrutura de Dados:** Define quais dados serão utilizados e como serão armazenados.

- **Relacionamentos:** Estabelece os relacionamentos usando chaves primárias e estrangeiras para garantir que os dados possam ser analisados em conjunto.

- **Otimização para Análise:** Organiza os dados de modo que consultas e análises sejam rápidas e eficientes, evitando redundâncias.

- **Adaptação aos Requisitos de Negócio:** Os dados são estruturados de acordo com as necessidades definidas na fase de definição do projeto.

O objetivo final é permitir que as ferramentas de análise de dados explorem os dados de forma eficaz e precisa, fornecendo insights valiosos para a empresa.

## Cardinalidade

Durante essa etapa também foi explicado sobre cardinalidade, que é como a relação entre as tabelas irá ser. Ela especifica a quantidade de relações entre as tabelas. Existem três tipos:

**Um para Um (1:1)**: Apenas um elemento de cada tabela se relaciona entre si, sendo exclusivo. Exemplo: Pessoa e CPF.

**Um para Muitos (1:N)**: Um elemento está associado a vários elementos de outra tabela. Exemplo: Produto e vendas.

**Muitos para Muitos (N:N)**: Nesse caso, diferentes do primeiro, todos os elementos de uma tabela podem estar relacionados a outra tabela e vice-versa, não havendo exclusividade.

No Power BI, não é recomendado utilizar a relação muitos para muitos, mesmo que em alguns casos ele permita. É recomendado criar uma tabela secundária para ser a tabela central e, depois, ramificar a partir dela.

Entender a cardinalidade é importante para estabelecer a relação dos itens de forma correta e, assim, evitar problemas na criação dos gráficos.


## Autores

- [@PabloVinicius](https://www.github.com/PabloViniciusSS)

Meu nome é Pablo Vinícius, venho estudando analise de dados, Ciencia de Dados , Aprendizado de Máquinas e deep learning, para buscar meu objetivo que é entrar na área de dados.
## Stack utilizada

**Análise de Dados:** Power BI
## Aprendizados

Nesse projeto, foi demonstrado como realizar uma análise superficial dos dados, incluindo a verificação e remoção de dados duplicados, além de identificar problemas na detecção dos cabeçalhos. Foi discutida a importância de compreender a modelagem de dados para manipular diferentes bases de dados e estabelecer o relacionamento entre os dados. Utilizamos o DAX para criar duas novas tabelas: a tabela Lucro e a tabela Margem de Lucro.

Principais Destaques:

- **Análise de Vendas**: Utilizei gráficos de cascata para visualizar o valor total de vendas por modo de envio.
- **Custo de Envio**: Identifiquei os mercados com maior custo médio de envio usando gráficos treemap.
- **Indicadores de Desempenho**: Criei KPIs para monitorar se a empresa atingiu suas metas de vendas mensais.
- **Margem de Lucro**: Analisei o comportamento da margem de lucro ao longo do tempo.

## Licença

[MIT](https://choosealicense.com/licenses/mit/)


## Etiquetas

Adicione etiquetas de algum lugar, como: [shields.io](https://shields.io/)

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)
[![GPLv3 License](https://img.shields.io/badge/License-GPL%20v3-yellow.svg)](https://opensource.org/licenses/)
[![AGPL License](https://img.shields.io/badge/license-AGPL-blue.svg)](http://www.gnu.org/licenses/agpl-3.0)

