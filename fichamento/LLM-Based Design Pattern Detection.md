# LLM-Based Design Pattern Detection

Schindler, C., & Rausch, A. (2025). *LLM-Based Design Pattern Detection*. In Proceedings of PATTERNS 2025. Clausthal University of Technology, Germany.

---

## 1. Fichamento de Conteúdo

O artigo propõe uma abordagem inovadora para detecção de instâncias de padrões de projeto em código-fonte utilizando *Large Language Models* (*LLMs*), especificamente *ChatGPT-3.5* e *ChatGPT-4*. O estudo foca no padrão *Composite* e utiliza um conjunto de dados público do repositório *P-MART*, que inclui projetos como *JUnit v3.7*, *JHotDraw v5.1*, *PMD v1.8*, *QuickUML 2001* e *MapperXML v1.9.7*. A metodologia consiste em quatro etapas: preparação dos dados, incluindo filtragem de instâncias incompletas e limpeza de anotações em *XML*; construção de *prompts* estruturados em duas mensagens, contendo um exemplo anotado e um trecho de código alvo; execução dos modelos com limite de 128k *tokens*; e pós-processamento das saídas em *XML*. Os resultados mostram que o *ChatGPT-4* superou significativamente o *ChatGPT-3.5* em precisão, *recall*, *F1-score* e acurácia, além de não apresentar *hallucinations* (criação de classes ou papéis inexistentes). No entanto, a abordagem ainda enfrenta desafios como a limitação de contexto imposta pelo tamanho máximo de *tokens*, a variabilidade na implementação dos papéis entre diferentes instâncias do padrão e a dificuldade de generalização quando o exemplo fornecido não cobre todos os papéis presentes no código alvo. O artigo conclui que *LLMs* são promissores para tarefas de compreensão e manutenção de software, mas sugere que futuros trabalhos explorem técnicas de *pruning* de código e o uso de múltiplos exemplos para melhorar a robustez e a escalabilidade do método.

---

## 2. Fichamento Bibliográfico

- ***Design pattern detection***: Tarefa de identificar implementações concretas de padrões de projeto em bases de código, crucial para manutenção, refatoração e compreensão de sistemas legados (p. 1–2).  
- ***P-MART repository***: Repositório público de instâncias anotadas de padrões de projeto, utilizado como base de dados para experimentos, contendo projetos como *JUnit*, *JHotDraw* e *PMD* (p. 10, Tabela I).  
- ***Prompt engineering***: Estratégia de construção de *prompts* em duas etapas: a primeira define o contexto e fornece um exemplo anotado; a segunda apresenta o código a ser analisado (p. 11–12, Listing 1).  
- ***Hallucinations***: Fenômeno em que o *LLM* inventa classes ou papéis não presentes no código, observado apenas no *ChatGPT-3.5* e não no *ChatGPT-4* (p. 15).  
- ***Métricas de avaliação***: *Precision*, *Recall*, *F1-score*, *Accuracy* e matriz de confusão multi-classe para os papéis *Client*, *Component*, *Composite*, *Leaf* e *No Role* (p. 14–15, Tabelas II–V).  
- ***Token limit***: Restrição prática de *LLMs* que limita a quantidade de código e contexto que pode ser fornecido em um único *prompt*, impactando a escalabilidade do método (p. 18).  

---

## 3. Fichamento de Citações

- "Detecting design pattern instances in unfamiliar codebases remains a challenging yet essential task for improving software quality and maintainability." (p. 1)  
- "We focus on instances of the *Composite* design pattern collected from the *P-MART* repository." (p. 10)  
- "The actual prediction task is performed using *ChatGPT-3.5* and *4*, both with a limit of 128k *tokens*." (p. 12)  
- "Our experiments also exhibited *hallucinations*, where the model invented classes or roles not present in the source code snippets." (p. 15)  
- "*ChatGPT-4* performed better compared to *ChatGPT-3.5*, by finding more annotations and having more correct annotations." (p. 17)  
- "Providing multiple examples could help the model better generalize across varying instances of the design pattern." (p. 19)  

---