# 🛒 Algoritmo de Recomendação de Produtos com A\*

Este projeto implementa um aloritmo de recomendação de produtos utilizando o algoritmo A\* (A-Star). O objetivo é simular um sistema inteligente que sugere caminhos de navegação entre produtos com maior probabilidade de conversão.

---

## 🚀 Visão Geral

O algoritmo A\* é adaptado aqui para navegar por um "grafo de produtos", onde cada nó representa um produto e as arestas representam possíveis caminhos de navegação. A heurística utilizada é baseada na **probabilidade de conversão** de cada produto.

---

## 🧠 Estratégia de Busca

O A\* utiliza duas componentes principais:

- **g(n)**: custo acumulado até o nó atual (simulado como passos entre produtos).
- **h(n)**: heurística baseada na **probabilidade de conversão**. Quanto maior a probabilidade, menor o custo heurístico (`h = -probabilidade`).

A função de avaliação é: f(n) = g(n) + h(n)

📚 Requisitos
Python 3.8+

Nenhuma biblioteca externa necessária (apenas heapq da biblioteca padrão)


✅ Como executar
python .\recommendation-algorithm.py      
