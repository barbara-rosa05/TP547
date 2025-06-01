# Trabalho Final - Simulação de Canais para RIS com Monte Carlo

Este repositório contém o código-fonte desenvolvido para o Trabalho Final Parte 1 da disciplina de Mestrado TP547.  
O projeto tem como objetivo reproduzir resultados de um artigo científico recente e realizar simulações utilizando o método de Monte Carlo.

## Artigo Utilizado

**Título:** [Rayleigh Fading Modeling and Channel Hardening for Reconfigurable Intelligent Surfaces](https://ieeexplore.ieee.org/document/9300189)  
**Autores:** Emil Björnson e Luca Sanguinetti  
**Fonte:** *IEEE Wireless Communications Letters*, Vol. 10, No. 4, Abril 2021.

## Objetivos do Trabalho

- Escolher um artigo relacionado à área de pesquisa.
- Fazer uma breve explicação sobre o tema e a metodologia do artigo.
- Reproduzir um dos resultados utilizando simulações de Monte Carlo.
- Gerar variáveis aleatórias para modelar o canal.

## Tecnologias e Bibliotecas

- Python 3.13
- NumPy
- Matplotlib
  
## Conteúdo do Código

O código está dividido em:

1. **Simulação da distribuição dos autovalores** da matriz de correlação espacial para diferentes espaçamentos dos elementos do RIS.
2. **Análise da energia cumulativa dos autovalores** (Rank Efetivo).
3. **Simulação do Hardening da SNR**, avaliando como o número de elementos influencia o comportamento do canal.
4. **Plotagem dos resultados** de forma gráfica para facilitar a análise.

## Estrutura do Repositório

- `main.ipynb` → Notebook completo com as simulações, geração de variáveis aleatórias e análise dos autovalores.
- `Apresentação Final.pptx` → Slides utilizados na apresentação oral do trabalho.
- `Trabalho Final de TP547.docx` → Documento em Word com a descrição técnica e teórica da atividade.

## Autoras

- Barbara Cássia Florentino Rosa
- Beatriz Bastos Assis
