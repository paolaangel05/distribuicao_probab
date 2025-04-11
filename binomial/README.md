[![author](https://img.shields.io/badge/author-Paola_Silva-red.svg)]([https://www.linkedin.com/in/paolaufsj/]([https://www.linkedin.com/in/paolaufsj/](https://www.linkedin.com/in/paolaufsj/))) [![](https://img.shields.io/badge/python-3.11+-blue.svg)](https://www.python.org/downloads/release/python-365/) 

<p align="center">
  <img src="https://images.unsplash.com/photo-1454165804606-c3d57bc86b40?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=1050&q=80" alt="imagem maneira relacionada ao projeto"height=400px >
</p>

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
