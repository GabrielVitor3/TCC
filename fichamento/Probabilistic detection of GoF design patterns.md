# Fichamento: Probabilistic detection of GoF design patterns

**Referência:**  
Bozorgvar, N.; Rasoolzadegan, A.; Harati, A. "Probabilistic detection of GoF design patterns." In: *The Journal of Supercomputing*, vol. 79, pp. 1654–1682, 2023. doi: 10.1007/s11227-022-04718-7

---

## 1. Fichamento de Conteúdo

O artigo propõe uma abordagem probabilística para detecção de padrões de projeto GoF em código-fonte. O método utiliza uma rede neural MLP para regressão e um modelo gráfico probabilístico (rede bayesiana) para inferência. Os autores representam padrões como conjuntos de características extraídas de assinaturas e medem a similaridade entre classes e papéis dos padrões. A avaliação em projetos de código aberto (como JHotDraw e JUnit) mostra que a abordagem cobre variantes de padrões e oferece resultados em uma escala de probabilidade, superando métodos determinísticos em termos de cobertura e flexibilidade.

---

## 2. Fichamento Bibliográfico

- **Abordagem probabilística:** Método que atribui uma probabilidade à presença de um padrão de projeto no código, em vez de uma detecção binária (p. 1).
- **MLP (Multilayer Perceptron):** Rede neural usada para regressão e estimativa da similaridade entre classes e papéis de padrões (p. 9).
- **Rede Bayesiana:** Modelo gráfico probabilístico usado para inferência da probabilidade de um padrão com base nos papéis detectados (p. 17).

---

## 3. Fichamento de Citações

> "Detecting design patterns from source code of software systems can help to understand the structure and the behavior of the software systems." (p. 1)

> "The purpose of this paper is to provide a way for identifying design patterns in source code probabilistically." (p. 3)

> "The results of the proposed method show the similarity of each code to the design patterns in the range between 0 and 1." (p. 1)