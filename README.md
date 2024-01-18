# Análise de Qualidade de Frutas



## Objetivo


Bem-vindo ao projeto "Análise de Qualidade de Frutas". O principal objetivo deste projeto é realizar uma análise exploratória de dados em um conjunto de dados sobre frutas, identificando padrões e características que possam estar relacionadas à qualidade das frutas.


## 1. Preparação do Ambiente

### 2. Carregamento e Pré-processamento dos Dados

Nesta etapa, realizamos o carregamento dos dados e aplicamos o pré-processamento necessário para preparar os dados para análise. Eliminamos dados ausentes, convertemos tipos de colunas e exploramos estatísticas básicas das variáveis.

### 3. Exploração Visual das Relações entre Variáveis

Utilizamos gráficos de dispersão e histogramas para visualizar as distribuições e relações entre variáveis como tamanho, peso, doçura e crocância.

### 4. Distribuição da Qualidade das Frutas

Um gráfico de barras é utilizado para mostrar a distribuição de frutas por qualidade. Observamos uma distribuição quase igualitária entre as categorias de boa e má qualidade.

### 5. Identificação de Correlações entre Variáveis

A matriz de correlação revela correlações relativamente baixas entre as variáveis. Destacamos as variáveis que têm as maiores correlações com a qualidade.

### 6. Análise da Relação entre Maturação e Qualidade

Discretizamos a variável de maturação e utilizamos gráficos de barras e boxplot para analisar a relação entre a maturação e a qualidade.

## Exemplo de Uso

```python
# Exemplo de código para análise específica
import pandas as pd
import seaborn as sns
import matplotlib.pyplot as plt

# ... (código relevante)

# Visualizar a relação entre tamanho e peso
sns.scatterplot(x=df['Size'], y=df['Weight'], hue=df['Quality'])
plt.title('Relação entre Tamanho e Peso com Qualidade')
plt.show()
```

## Conclusão e Contribuições

Neste projeto, explorei detalhadamente a qualidade das frutas, identificando padrões e relações entre variáveis. Contribuições e feedback são sempre bem-vindos. Se tiver dúvidas ou sugestões, entre em contato:

- E-mail: miguelsilvafreire@hotmail.com
- LinkedIn: (https://www.linkedin.com/in/miguel-freire99/)
