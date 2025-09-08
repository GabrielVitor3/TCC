# On the use of LLMs for Design Pattern Detection in software models

Abdeljalil, Y., Radermacher, A., Didonet del Fabro, M., & Mraidha, C. (2025). *On the use of LLMs for Design Pattern Detection in software models*. In Proceedings of the First Large Language Models for Software Engineering Workshop (LLM4SE 2025). Coblence, Germany. HAL Id: cea-05121589.

---

## 1. Fichamento de Conteúdo

Este artigo investiga o uso de *Large Language Models* (*LLMs*) para detecção de padrões de projeto *Gang of Four* (*GoF*) a partir de modelos *UML*, integrando princípios de *Model-Driven Engineering* (*MDE*). Os autores propõem um fluxo de trabalho que inclui: (i) engenharia reversa de código-fonte Java do repositório *P-MART* para gerar modelos *UML*; (ii) conversão para *PlantUML* para representação textual; (iii) uso de *prompts* estruturados para orientar os *LLMs* na detecção; e (iv) avaliação quantitativa com métricas de precisão, *recall* e *F1-score*. Foram testados três modelos (*Llama3.3*, *DeepSeek-R1* e *Qwen2.5-Coder*) em dois cenários: detecção de padrões únicos (ex.: *Singleton*, *Observer*) e múltiplos (ex.: *Observer & Singleton*, *State & Strategy*), com e sem comentários nos modelos. Os resultados mostram que os *LLMs* são capazes de identificar padrões a partir de modelos *UML*, mesmo sem detalhes de implementação de métodos, porém com acurácia limitada (até 0.53 no melhor caso). A inclusão de comentários melhorou ligeiramente o desempenho, especialmente para o *Llama3.3*. A detecção de múltiplos padrões mostrou-se mais desafiadora, com desempenho inferior. O estudo conclui que *LLMs* sozinhos não são suficientes para detecção precisa de padrões complexos, sugerindo a necessidade de abordagens híbridas ou frameworks integrados de análise baseada em modelos.

---

## 2. Fichamento Bibliográfico

- ***Large Language Models (LLMs)***: Modelos de linguagem de grande escala (ex.: *Llama3.3*, *DeepSeek-R1*, *Qwen2.5-Coder*) usados para análise de código e modelos *UML* para detecção de padrões de projeto (p. 2–3).  
- ***Model-Driven Engineering (MDE)***: Abordagem que utiliza modelos como artefatos centrais no desenvolvimento de software, aqui aplicada para gerar abstrações de código-fonte em *UML* (p. 3).  
- ***PlantUML***: Linguagem textual para descrição de diagramas *UML*, usada como formato de entrada para os *LLMs* por sua clareza e compatibilidade (p. 4).  
- ***P-MART***: Repositório público de implementações Java de padrões *GoF*, usado como fonte para engenharia reversa e geração de modelos *UML* (p. 4).  
- ***Prompt Engineering***: Técnica de construção de *prompts* estruturados para guiar *LLMs* na detecção de padrões, incluindo instruções claras e exemplos (p. 4).  
- ***Métricas de Avaliação***: Precisão (*precision*), *recall*, *F1-score* e matriz de confusão usadas para avaliar o desempenho dos modelos (p. 5).  

---

## 3. Fichamento de Citações

- "Integrating design pattern detection with inference through Large Language Models (LLMs) and MDE techniques may overcome some of these limits by producing abstractions of large code bases." (p. 2)  
- "The LLM successfully identifies the Singleton pattern and justifies its answer based on the presence of a private constructor, a static instance captain within the Captain class, and the static method getCaptain()." (p. 6)  
- "Adding brief comments led to a slight improvement in performance, and LLMs were able to detect multiple coexisting patterns to some extent." (p. 11)  
- "Llama3.3 exhibits the most significant improvement when comments are provided, with accuracy increasing from 0.40 to 0.50 and the F1-score rising from 0.39 to 0.48." (p. 8)  
- "Our evaluation highlights the impact of comments on model performance and demonstrates that while all models show some improvement, Llama3.3 consistently outperforms the others." (p. 10)  
- "This suggests that relying solely on LLMs may not be sufficient for precise detection and opens up opportunities to explore additional techniques or hybrid approaches to improve performance." (p. 11)  

---