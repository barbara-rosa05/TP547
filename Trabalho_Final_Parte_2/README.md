# Análise dos Efeitos do Ruído de Fase em Sistemas OFDM

Este repositório contém o notebook desenvolvido para a simulação e análise dos efeitos do **ruído de fase** em sistemas OFDM, baseado no artigo científico _“Phase Noise and Sub-Carrier Spacing Effects on the Performance of an OFDM Communication System”_ (IEEE Communications Letters, 1998), de García Armada e Calvo. A atividade foi realizada como parte da disciplina **TP547 - Princípios de Simulação de Sistemas de Comunicação**, no contexto de pós-graduação, com nível de excelência esperado para alunas destaque.

## 🎯 Objetivos do Trabalho

- Compreender e demonstrar computacionalmente os efeitos do **ruído de fase (phase noise)** e da perda de ortogonalidade entre subportadoras.
- Simular diferentes configurações de sistemas OFDM com 128, 2048 e 8192 subportadoras.
- Analisar a influência da razão \( T_\phi / T_{OFDM} \) na SER (Symbol Error Rate).
- Reproduzir os gráficos apresentados no artigo (Figuras 2 e 3) e comparar com os resultados obtidos.
- Produzir um relatório técnico com estrutura acadêmica sólida, interpretação crítica e validação dos achados.

## 🧠 Conteúdo do Projeto

O notebook `main.ipynb` está dividido em seções comentadas e explicadas com Markdown, Latex e docstrings para facilitar o entendimento:

1. **Introdução**  
   Contextualização teórica do problema: OFDM, ruído de fase, CPE e ICI.

2. **Resumo Técnico do Artigo**  
   Síntese detalhada da metodologia empregada no artigo.

3. **Análise Crítica**  
   Avaliação das limitações, qualidades e impacto do estudo.

4. **Simulação Computacional**  
   Implementação em Python com geração de sinais QPSK, adição de ruído de fase e cálculo da SER.

5. **Validação e Comparação com o Artigo**  
   Análise comparativa dos gráficos gerados com as Figuras 2 e 3 do artigo original.

6. **Conclusão**  
   Discussão aprofundada dos resultados, destacando o impacto da escolha do espaçamento de subportadoras e do perfil do ruído.

## Tecnologias e Bibliotecas Utilizadas

- Python 3.x
- NumPy
- Matplotlib
- SciPy (IFFT/FFT)

## Estrutura do Repositório

`main.ipynb` # Notebook principal com simulações e análises

## Destaques Acadêmicos

- Trabalho conduzido com rigor analítico e simulações coerentes com o estado da arte.
- Apresentação clara e articulada, com visualizações gráficas alinhadas à fundamentação teórica.
- Validação dos resultados do artigo com **interpretação crítica e expansão do escopo**, incluindo subportadoras não exploradas no artigo original (N=128 e N=8192).

## Autoras

- Barbara Cássia Florentino Rosa
- Beatriz Bastos Assis