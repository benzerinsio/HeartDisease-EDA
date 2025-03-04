# ❤️ Investigação de Fatores Cardíacos  
*Projeto de Análise Exploratória de Dados (EDA) - Felipe V. Sousa*

Bem-vindo(a)! Este repositório apresenta uma **Análise Exploratória de Dados (EDA)** no conjunto de dados Heart Disease UCI, investigando fatores clínicos e sua relação com a presença de doença cardíaca.

🔗 [Visualizar o Notebook](https://github.com/benzerinsio/HeartDisease-EDA/blob/main/EDA-BreastCancer.ipynb)

## 🎯 Objetivo da Análise

Explorar variáveis clínicas (como `age`, `cholestoral`, `oldpeak` e `chest_pain_type`) e o diagnóstico (`target`), para entender distribuições, identificar padrões e avaliar o impacto de duplicatas (>70%) nas associações com doença cardíaca, gerando insights acionáveis e preparando o terreno para modelos preditivos.

## 📊 Fonte de Dados

Os dados vêm do arquivo Heart Disease UCI, contendo 1025 registros de pacientes (UCI Machine Learning Repository).

## 🛠️ Bibliotecas Utilizadas

- **Pandas**: Manipulação e análise de dados.  
- **NumPy**: Cálculos numéricos e operações matemáticas.  
- **Seaborn**: Visualizações estatísticas como heatmaps e countplots.  
- **Matplotlib**: Criação de gráficos comparativos e pairplots.

## 💬 Conclusão

Esta EDA revelou padrões sutis no dataset cardíaco: `oldpeak` baixo associa-se a maior prevalência de doença (`target=1`), enquanto `typical angina` é 3 vezes mais inofensiva e `non-anginal pain` tem mais de 3 vezes maior chance de indicar doença. Duplicatas (>70%) são proporcionais, com impacto mínimo nas análises (variações ~0.02). A baixa correlação entre variáveis e a mistura nos dados sugerem que modelos de Machine Learning, combinando múltiplas features, têm potencial para alta precisão na classificação de doenças cardíacas.