# Distribuição Binomial

Esta pasta contém materiais e exemplos práticos sobre a Distribuição Binomial.

## O Que é a Distribuição Binomial?

A Distribuição Binomial modela o número de sucessos em uma sequência de \( n \) ensaios independentes, onde cada ensaio resulta em sucesso com probabilidade \( p \). É definida pelos seguintes parâmetros:

- **\( n \):** Número de ensaios.
- **\( p \):** Probabilidade de sucesso em cada ensaio.

A função massa de probabilidade (PMF) da distribuição é a probabilidade exata de ocorrer um determinado número de sucessos.

Além da PMF, a Distribuição Binomial também possui a função de distribuição acumulada (CDF), que é a probabilidade acumulada até um determinado valor.  

## Conteúdo Desta Pasta

- **Notebook `binomial.ipynb`:**  
  Contém implementações usando Python e a biblioteca SciPy para:
  - Calcular a PMF (`binom.pmf`)
  - Calcular a CDF (`binom.cdf`)
  
- **Exemplos Gráficos:**  
  Visualizações que demonstram a forma da PMF (barras discretas) e da CDF (escada) da distribuição.

## Como Utilizar

1. **Abra o notebook:**  
   Utilize o Jupyter Notebook ou o JupyterLab para abrir e executar o `binomial.ipynb`.
2. **Estude os exemplos:**  
   Siga as células interativas para entender como calcular e visualizar as principais funções da distribuição binomial.
3. **Experimente:**  
   Modifique os parâmetros \( n \) e \( p \) para ver como a forma da distribuição se altera.

## Requisitos

- Python 3.x
- Bibliotecas: NumPy, SciPy, Matplotlib
