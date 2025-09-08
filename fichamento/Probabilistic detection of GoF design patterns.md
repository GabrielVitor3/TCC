# Probabilistic detection of GoF design patterns

Bozorgvar, N., Rasoolzadegan, A., & Harati, A. (2023). *Probabilistic detection of GoF design patterns*. The Journal of Supercomputing, 79, 1654–1682. https://doi.org/10.1007/s11227-022-04718-7

---

## 1. Fichamento de Conteúdo

Este artigo propõe um método probabilístico para detecção de padrões de projeto *Gang of Four* (*GoF*) em código-fonte, superando as limitações das abordagens determinísticas tradicionais. O método é dividido em duas fases: *Fase de Aprendizado*: os padrões são representados como um conjunto de 10 características (*features*) extraídas de suas assinaturas estruturais e comportamentais (ex.: associação, herança, delegação, métodos sobrescritos); um modelo de *Multilayer Perceptron* (*MLP*) é treinado via regressão para estimar a similaridade entre classes do código e os 19 papéis que compõem seis padrões *GoF* (*Singleton*, *Factory Method*, *Composite*, *Adapter*, *Observer*, *State/Strategy*); *Fase de Detecção*: o código é convertido em diagramas de classe e grafos enriquecidos; instâncias candidatas são extraídas; um modelo gráfico probabilístico (rede bayesiana com modelo linear generalizado) infere a probabilidade final de cada padrão com base nas similaridades dos papéis e suas relações causais. O método foi avaliado em cinco sistemas *open-source* (*JHotDraw 5.1*, *JRefactory 2.6.24*, *JUnit 3.7*, *QuickUML 2001*, *MapperXML 1.9.7*) e comparado com ferramentas consolidadas (*DEMiMA*, *Sempatrec*, *GTM*, *SSA*). Os resultados mostram que a abordagem cobre variantes de implementação e oferece resultados em uma escala contínua de probabilidade (0 a 1), sendo que instâncias detectadas por métodos determinísticos foram corretamente identificadas com probabilidade entre 98% e 100%. O método alcançou *Mean Squared Error* (*MSE*) de 0.0027 no treinamento do *MLP*, indicando alta precisão na regressão.

---

## 2. Fichamento Bibliográfico

- ***Abordagem Probabilística***: Método que atribui uma probabilidade (entre 0 e 1) à presença de um padrão de projeto no código, em vez de uma detecção binária, permitindo capturar variantes e implementações incompletas (p. 1–2).  
- ***Assinaturas de Padrões***: Definições de baixo nível que capturam aspectos estruturais e comportamentais dos padrões, usadas para extrair características estáveis frente a variações de implementação (p. 9).  
- ***Multilayer Perceptron (MLP)***: Rede neural artificial com uma camada oculta de 12 neurônios, treinada com algoritmo de *backpropagation* e funções de ativação *Log-Sigmoid* e *Tan-Sigmoid* para regressão das similaridades entre classes e papéis (p. 10–13).  
- ***Modelo Gráfico Probabilístico***: Rede bayesiana que modela relações causais entre os papéis de um padrão, usando funções lineares generalizadas e operadores *Min* e *Addition* para inferir a probabilidade final do padrão (p. 17–19).  
- ***Avaliação com MSE***: *Mean Squared Error* (fórmula 2) usado para medir o erro da regressão, com valor de 0.0027 indicando alta precisão do modelo (p. 20).  
- ***Projetos de Avaliação***: *JHotDraw 5.1*, *JRefactory 2.6.24*, *JUnit 3.7*, *QuickUML 2001*, *MapperXML 1.9.7* — sistemas *open-source* amplamente usados em literatura para comparação de métodos de detecção (p. 21).  

---

## 3. Fichamento de Citações

- "Detecting design patterns from source code of software systems can help to understand the structure and the behavior of the software systems." (p. 1)  
- "The purpose of this paper is to provide a way for identifying design patterns in source code probabilistically." (p. 3)  
- "The results of the proposed method show the similarity of each code to the design patterns in the range between 0 and 1." (p. 1)  
- "Using regression as one of the machine learning techniques allows us to cover design patterns variants." (p. 25)  
- "In all cases where each of the proposed methods identified a specific pattern instance, the proposed method estimated the pattern as 98% to 100% probable." (p. 23)  
- "The MSE value for the training model in this study is 0.0027, which is close to zero, indicating a good performance in the regression." (p. 20)  

---