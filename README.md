# bubble-selection-sort
# Exercício Prático – Bubble Sort vs Selection Sort

## Objetivo

Implementar os algoritmos Bubble Sort e Selection Sort em C e comparar:

- Tempo de execução (ms)
- Número de comparações
- Número de movimentações

Os testes foram realizados com vetores preenchidos em ordem decrescente (pior caso), nos tamanhos:

- 100
- 1000
- 10000

---

## Metodologia

- O tempo foi medido utilizando a função `clock()`.
- Comparações e movimentações foram contabilizadas manualmente dentro dos algoritmos.
- Cada troca foi considerada como 3 movimentações.

---

## Análise

- Ambos os algoritmos apresentaram complexidade O(n²) em relação ao número de comparações.
- O Selection Sort apresentou número significativamente menor de movimentações.
- O tempo de execução foi menor no Selection Sort, principalmente para vetores maiores.

---

## Conclusão

O Selection Sort apresentou melhor desempenho geral devido ao menor número de trocas realizadas.
