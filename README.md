# engenharia-analytics-fiap

# Limpeza e Normalização de Dados em Python

Este repositório apresenta um guia prático para limpeza e normalização de dados em Python, abordando tratamento de valores ausentes missing values e de outliers que são dados fora de padrão.

## 📌 Tecnologias Utilizadas
- 🐍 Python
- 📊 Pandas
- 🔢 NumPy
- 📊 Matplotlib

## 🚀 Funcionalidades Implementadas
- **Tratamento de Valores Ausentes**: Substitui valores `NaN` pela mediana da coluna correspondente.
- **Remoção de Outliers**: Identifica outliers utilizando o método IQR (Interquartile Range) e os substitui pela mediana da coluna.
- **Normalização dos Dados**: Aplica a técnica Min-Max Scaling para padronizar os valores entre 0 e 1.
- **Preparação para Machine Learning**: Os dados limpos e normalizados podem ser utilizados para alimentar modelos de aprendizado de máquina, melhorando a eficiência dos algoritmos.


## 📊 Exemplo de Uso
O script cria um DataFrame com valores ausentes e outliers e aplica os seguintes passos:
1. Substitui valores ausentes pela mediana.
2. Remove outliers com base no método IQR.
3. Normaliza os dados entre 0 e 1.
4. Os dados processados podem ser utilizados para modelos de Machine Learning, como regressão e classificação.

## 🤖 Machine Learning
Após a limpeza e normalização dos dados, é possível utilizá-los em modelos de aprendizado de máquina, como:
- **Regressão Linear e Logística**
- **Árvores de Decisão**
- **Redes Neurais**
- **K-Means e outras técnicas de clusterização**

A normalização e a remoção de outliers são passos essenciais para melhorar a precisão e a generalização dos modelos.

## 🤝 Contribuição
Sinta-se à vontade para abrir issues e pull requests para melhorias neste projeto.

## 📜 Licença
Este projeto está licenciado sob a MIT License - veja o arquivo [LICENSE](LICENSE) para mais detalhes.

