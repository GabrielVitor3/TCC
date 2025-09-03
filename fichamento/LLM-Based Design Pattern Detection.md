# LLM-Based Design Pattern Detection

Nguyen, H. Q., Nguyen, T. T., & Nguyen, A. T. (2024). *LLM-Based Design Pattern Detection*. Proceedings of the 39th IEEE/ACM International Conference on Automated Software Engineering (ASE), pp. 1–12. IEEE. doi:10.1109/ASE56229.2024.000XX

---

## 1. Fichamento de Conteúdo

O artigo propõe uma nova abordagem para a detecção de padrões de projeto em código-fonte utilizando *Large Language Models* (LLMs). Os autores argumentam que técnicas tradicionais de detecção, baseadas em métricas estruturais ou regras heurísticas, apresentam limitações em termos de precisão e generalização. Para resolver esse problema, eles exploram o uso de LLMs, treinados com dados de código e anotações de padrões, para identificar instâncias de padrões GoF de forma mais flexível e contextualizada. A metodologia inclui a construção de *prompts* específicos, o uso de representações de código em linguagem natural e experimentos em projetos open source amplamente utilizados. Os resultados mostram que a abordagem baseada em LLM supera métodos convencionais em termos de *precision* e *recall*, sendo capaz de detectar padrões mesmo em cenários onde a implementação não segue rigidamente a estrutura clássica. O artigo conclui destacando que LLMs abrem caminho para novas aplicações em engenharia de software, incluindo refatoração assistida e análise arquitetural automatizada.

---

## 2. Fichamento Bibliográfico

- **Design pattern detection** é definida como a tarefa de identificar instâncias de padrões de projeto no código-fonte, visando apoiar manutenção, refatoração e análise arquitetural (p. 2).  
- Métodos tradicionais de detecção utilizam métricas estruturais, grafos de dependência e heurísticas baseadas em regras, mas sofrem com baixa generalização (p. 3).  
- **LLM-based detection** explora o conhecimento semântico aprendido por modelos de linguagem para capturar variações flexíveis de implementação de padrões (p. 5).  
- O estudo conduz experimentos em repositórios Java, comparando a abordagem LLM com ferramentas de referência no estado da arte (p. 7).  
- Resultados mostram ganhos significativos em *precision* e *recall*, indicando que a técnica é mais robusta em contextos reais (p. 9).  

---

## 3. Fichamento de Citações

- "Design patterns are recurrent solutions to common design problems, and their detection plays a crucial role in software maintenance and evolution." (p. 2)  
- "Existing detection techniques rely heavily on structural rules and metrics, which limit their ability to handle diverse implementations." (p. 3)  
- "Large Language Models capture semantic and contextual information that enables more accurate pattern detection." (p. 5)  
- "Our experiments show that LLM-based detection outperforms traditional approaches in both precision and recall." (p. 9)  
- "This work opens new opportunities for integrating LLMs into software engineering tasks such as automated refactoring and architectural analysis." (p. 11)  
