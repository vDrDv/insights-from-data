# Projetos de Data Science

Este repositório é focado em projetos e notebooks de Data Science. Aqui você encontrará análises, visualizações e modelos de machine learning em diferentes áreas e conjuntos de dados.

## Checklist de Limpeza de Dados

| Passo                                   | Descrição                                                                      | Concluído |
|-----------------------------------------|--------------------------------------------------------------------------------|------------|
| 1. Entendimento dos dados              | Entender a estrutura, tipos de variáveis, valores ausentes e padrões nos dados  | [ ]        |
| 2. Tratamento de valores ausentes      | Identificar e lidar com valores ausentes na base de dados                       | [ ]        |
| 3. Lidar com valores duplicados        | Remover linhas duplicadas, se aplicável                                         | [ ]        |
| 4. Padronização de nomes de variáveis  | Padronizar nomes de variáveis para consistência                                 | [ ]        |
| 5. Verificação de consistência de dados | Verificar se os dados seguem regras de negócio ou restrições conhecidas        | [ ]        |
| 6. Tratamento de outliers              | Identificar e lidar com valores extremos que possam distorcer a análise         | [ ]        |
| 7. Normalização ou transformação       | Normalizar ou transformar variáveis conforme necessário                         | [ ]        |
| 8. Codificação de variáveis categóricas| Codificar variáveis categóricas para análise quantitativa                       | [ ]        |
| 9. Análise exploratória de dados       | Conduzir uma análise exploratória para entender melhor os dados                 | [ ]        |
| 10. Documentação                        | Documentar todas as etapas de limpeza de dados e decisões tomadas              | [ ]        |

Marque os passos à medida que os completa, preenchendo os campos na coluna "Concluído".

# Métricas Comuns em Análise de Dados

## Métricas de Desempenho de Modelos de Machine Learning:
- Precisão (Accuracy)
- Precisão Balanceada (Balanced Accuracy)
- Sensibilidade (Recall)
- Especificidade (Specificity)
- Pontuação F1 (F1 Score)
- Área sob a Curva ROC (ROC-AUC)
- Matriz de Confusão (Confusion Matrix)

## Métricas de Regressão:
- Erro Quadrático Médio (Mean Squared Error - MSE)
- Raiz do Erro Quadrático Médio (Root Mean Squared Error - RMSE)
- Erro Absoluto Médio (Mean Absolute Error - MAE)
- Coeficiente de Determinação (R-squared)

## Métricas de Classificação Binária:
- Precisão (Precision)
- Recall (Sensibilidade)
- Pontuação F1 (F1 Score)
- Área sob a Curva ROC (ROC-AUC)
- Taxa de Falsos Positivos (False Positive Rate - FPR)

## Métricas de Clusterização:
- Índice de Silhueta (Silhouette Score)
- Coeficiente de Davies-Bouldin (Davies-Bouldin Index)
- Índice de Calinski-Harabasz (Calinski-Harabasz Index)

## Métricas de Análise de Séries Temporais:
- Erro Médio Absoluto Percentual (Mean Absolute Percentage Error - MAPE)
- Raiz do Erro Médio Quadrático Percentual (Root Mean Squared Percentage Error - RMSPE)
- Erro Absoluto Médio (Mean Absolute Error - MAE)
- Erro Quadrático Médio (Mean Squared Error - MSE)
- Coeficiente de Correlação de Pearson


# Comandos Principais do Pandas e Numpy

## Pandas
### Leitura e Escrita de Dados
- `pd.read_csv()`: Leitura de arquivos CSV.
- `pd.read_excel()`: Leitura de arquivos Excel.
- `df.to_csv()`: Escrita de DataFrame em arquivo CSV.
- `df.to_excel()`: Escrita de DataFrame em arquivo Excel.

### Manipulação de Dados
- `df.head()`: Visualiza as primeiras linhas do DataFrame.
- `df.tail()`: Visualiza as últimas linhas do DataFrame.
- `df.info()`: Sumário das informações do DataFrame.
- `df.describe()`: Estatísticas descritivas do DataFrame.
- `df.shape`: Retorna a forma (número de linhas e colunas) do DataFrame.
- `df.columns`: Retorna os nomes das colunas do DataFrame.
- `df.index`: Retorna os rótulos das linhas do DataFrame.
- `df.drop()`: Remove linhas ou colunas do DataFrame.
- `df.rename()`: Renomeia colunas do DataFrame.
- `df.groupby()`: Agrupa dados por uma ou mais variáveis.
- `df.merge()`: Une dois DataFrames usando uma chave de junção.

### Seleção e Filtragem de Dados
- `df['coluna']`: Seleciona uma coluna específica.
- `df.loc[]`: Acesso baseado em rótulos.
- `df.iloc[]`: Acesso baseado em índices inteiros.
- `df.query()`: Filtra linhas com uma expressão booleana.
- `df[(condição)]`: Filtra linhas com uma condição booleana.

### Operações com Dados
- `df.apply()`: Aplica uma função ao longo de um eixo do DataFrame.
- `df.drop_duplicates()`: Remove linhas duplicadas.
- `df.fillna()`: Preenche valores ausentes com um valor específico.
- `df.sort_values()`: Ordena os valores do DataFrame.
- `df.pivot_table()`: Cria uma tabela dinâmica a partir dos dados.
- `df.merge()`: Combina dois DataFrames usando uma chave de junção.

## Numpy
### Criação de Arrays
- `np.array()`: Cria um array numpy a partir de uma lista ou tupla.
- `np.zeros()`: Cria um array de zeros com a forma especificada.
- `np.ones()`: Cria um array de uns com a forma especificada.
- `np.arange()`: Cria um array com valores espaçados uniformemente dentro de um intervalo.

### Operações com Arrays
- `np.sum()`: Calcula a soma dos elementos do array.
- `np.mean()`: Calcula a média dos elementos do array.
- `np.median()`: Calcula a mediana dos elementos do array.
- `np.std()`: Calcula o desvio padrão dos elementos do array.
- `np.max()`: Encontra o valor máximo do array.
- `np.min()`: Encontra o valor mínimo do array.
- `np.argmax()`: Retorna o índice do valor máximo do array.
- `np.argmin()`: Retorna o índice do valor mínimo do array.

### Manipulação de Arrays
- `np.reshape()`: Redimensiona o array.
- `np.concatenate()`: Concatena arrays ao longo de um eixo.
- `np.vstack()`: Empilha arrays verticalmente.
- `np.hstack()`: Empilha arrays horizontalmente.
- `np.split()`: Divide o array em sub-arrays.
- `np.copy()`: Cria uma cópia do array.

