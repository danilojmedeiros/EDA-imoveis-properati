# Análise exploratória de um conjunto de dados de preços de imóveis

A imobiliária Properati publica periodicamente informações sobre ofertas de imóveis para venda e aluguel. Deve aconselhar o agente imobiliário a desenvolver um modelo de regressão que permita prever o preço por metro quadrado de um imóvel. O objetivo final é que o modelo desenvolvido por eles seja utilizado como avaliador automático a ser aplicado nos próximos imóveis que forem comercializados pela empresa. Para isso, a empresa disponibiliza um conjunto de dados correspondente ao primeiro semestre de 2017.

O conjunto de dados é de tamanho pequeno a médio, mas tem duas complexidades às quais você precisa prestar atenção:

- Peso de dados faltantes em algumas variáveis relevantes.
- Será importante ter em conta o problema da influência espacial nos preços por metro quadrado. De fato, é provável que existam diferenças importantes nas diferentes geografias, bairros e áreas analisadas.

## Objetivos:

- Executar uma limpeza do conjunto de dados fornecido. Em particular, você precisará elaborar estratégias para lidar com dados ausentes em determinadas variáveis.
- Realizar uma análise descritiva das principais variáveis.
- Criar novas colunas de determinados recursos que podem ter valor preditivo.
