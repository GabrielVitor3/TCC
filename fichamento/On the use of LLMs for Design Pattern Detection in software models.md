# Fichamento: On the use of LLMs for Design Pattern Detection in software models

**Referência:**  
Abdeljalil, Y.; Radermacher, A.; Didonet del Fabro, M.; Mraidha, C. "On the use of LLMs for Design Pattern Detection in software models." In: *LLM4SE 2025 - First Large Language Models for Software Engineering Workshop*, Jun 2025, Coblence, Germany. HAL Id: cea-05121589.

---

## 1. Fichamento de Conteúdo

O artigo investiga o uso de Large Language Models (LLMs) para detecção de padrões de projeto GoF a partir de modelos UML. Os autores propõem um fluxo de trabalho que integra Engenharia Dirigida por Modelos (MDE) e LLMs para extrair e processar representações UML de código-fonte, usando a ferramenta PlantUML. O estudo avalia a capacidade de LLMs (como Llama3.3, DeepSeek-R1 e Qwen2.5-Coder) em identificar padrões isolados e combinados, com e sem comentários. Os resultados mostram que os LLMs são capazes de detectar padrões com certa precisão, mas o desempenho diminui com a complexidade e combinações de padrões. Comentários melhoram ligeiramente a detecção, mas a precisão geral não é alta, sugerindo a necessidade de abordagens híbridas.

---

## 2. Fichamento Bibliográfico

- **LLMs (Large Language Models):** Modelos de linguagem de grande escala usados para análise textual e de código, aplicados na detecção de padrões de projeto a partir de representações UML (p. 2).
- **PlantUML:** Linguagem textual para geração de diagramas UML, usada como formato de entrada para os LLMs (p. 4).
- **P-MART:** Repositório de projetos Java com anotações de padrões de projeto GoF, usado como base para geração de modelos UML (p. 4).

---

## 3. Fichamento de Citações

> "Integrating design pattern detection with inference through Large Language Models (LLMs) and MDE techniques may overcome some of these limits by producing abstractions of large code bases." (p. 2)

> "According to our findings, LLMs are able to identify a variety of Gang of Four (GoF) design patterns using UML models as input, but with limits, particularly when combining multiple patterns." (p. 3)

> "Adding brief comments led to a slight improvement in performance, and LLMs were able to detect multiple coexisting patterns to some extent." (p. 11)