# Análise de Cadeia de Markov com Estados Absorventes

Este repositório contém o notebook desenvolvido para a simulação e análise de uma Cadeia de Markov com dois estados absorventes (aranhas), conforme proposto em atividade prática da disciplina TP547. O trabalho inclui a modelagem do sistema, construção da matriz de transição, visualização em grafo, cálculo da probabilidade de absorção e número médio de passos até a absorção.

## Objetivos do Trabalho

- Representar o problema de movimentação da mosca entre compartimentos usando uma cadeia de Markov.
- Criar o grafo de transição com destaque para os estados absorventes.
- Calcular a matriz de transição \( P \), a matriz fundamental \( N \) e a matriz de absorção \( B \).
- Obter a probabilidade da mosca ser absorvida no 3º minuto.
- Calcular o número médio de passos até a absorção.
- Implementar o código de forma modular, didática e com visualização gráfica.

## Tecnologias e Bibliotecas

- Python 3.x
- NumPy
- Pandas
- Matplotlib
- NetworkX

## Conteúdo do Código

O notebook `Trabalho_Markov.ipynb` está organizado da seguinte forma:

1. **Descrição do problema e definição da matriz de transição.**
2. **Visualização do diagrama de transição de estados com NetworkX.**
3. **Cálculo da matriz \( P^3 \) e distribuição da mosca no 3º minuto.**
4. **Construção da matriz Q e cálculo da matriz fundamental \( N \).**
5. **Estimativa do tempo médio até absorção.**
6. **Cálculo das probabilidades de absorção para cada estado inicial.**
7. **Código estruturado em funções com docstrings e explicações teóricas.**

## Estrutura do Repositório

- `Trabalho_Markov.ipynb` → Notebook principal com todo o desenvolvimento teórico e prático da atividade.
- `Exercicios_Sala.ipynb` → Exercícios complementares resolvidos em sala de aula.

## Autora

- Bárbara Cássia Florentino Rosa