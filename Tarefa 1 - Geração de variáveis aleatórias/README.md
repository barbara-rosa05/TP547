# TP547 — Lista de Exercícios 1

Este repositório contém a resolução da **Lista de Exercícios 1** da disciplina de **Modelagem e Simulação (TP547)** do curso de Mestrado, ministrada pela professora **Bárbara Cássia Florentino Rosa**.

As resoluções foram realizadas em **Python 3** com auxílio das bibliotecas `NumPy`, `SciPy` e `Matplotlib`, e organizadas em um **notebook Jupyter** com visualizações e explicações passo a passo.

---

## Objetivos

- Aplicar conceitos de geração de variáveis aleatórias usando métodos como:
  - Gerador Linear Congruente (GLC)
  - Distribuições: Poisson, Binomial, Exponencial, Geométrica
  - Métodos de simulação: Inversa e Aceitação-Rejeição
- Calcular probabilidades, médias, desvios padrão e plotar histogramas comparando com a PDF teórica.
- Compreender e implementar a simulação de variáveis aleatórias discretas e contínuas.

---

## Estrutura

- `lista_resolvida.ipynb`: Notebook Jupyter com a resolução completa da lista.
- `Lista de exercícios_1_2025_1.pdf`: Arquivo original com o enunciado das questões.

---

## Exercícios Resolvidos

| Questão | Tema Principal                                | Técnicas Aplicadas                                       |
|--------:|-----------------------------------------------|----------------------------------------------------------|
| 1       | Gerador Linear Congruente (GLC)               | Cálculo iterativo e análise de período                   |
| 2       | Distribuição de Poisson                       | `poisson.pmf`, `poisson.cdf`                             |
| 3       | Distribuição Binomial                         | `binom.pmf`, `binom.cdf`, média e desvio padrão          |
| 4       | Poisson + Simulação Histograma                | `poisson.rvs` + `matplotlib`                             |
| 5       | Distribuição Exponencial                      | `λ = 1/μ`, probabilidades teóricas                       |
| 6       | Distribuição Geométrica                       | PMF manual + média e desvio padrão                       |
| 7       | Geração por Método da Inversa                 | `np.random.rand()` + `-ln(1-U)/λ`                        |
| 8       | Geração por Aceitação-Rejeição                | Comparação `f(x)/cg(x)` + histograma e PDF analítica     |

---

## Tecnologias Utilizadas

- **Python 3.10+**
- [Jupyter Notebook](https://jupyter.org/)
- [NumPy](https://numpy.org/)
- [SciPy](https://scipy.org/)
- [Matplotlib](https://matplotlib.org/)

---

## Observações

- Os resultados são reproduzíveis com `np.random.seed(42)` para garantir consistência estatística.
- Todos os exercícios estão comentados com explicações teóricas e práticas.
- A solução segue o estilo acadêmico sugerido pela docente.

---