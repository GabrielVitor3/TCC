# An Empirical Investigation of the Impact of Architectural Smells on Software Maintainability

Martini, A., Sharma, T., & Bianchini, E. (2018). *An Empirical Investigation of the Impact of Architectural Smells on Software Maintainability*. In 2018 IEEE International Conference on Software Architecture (ICSA), pp. 105–114. IEEE. doi:10.1109/ICSA.2018.00018

---

## 1. Fichamento de Conteúdo

O artigo investiga de forma empírica como *architectural smells* influenciam a manutenibilidade de sistemas de software. Os autores partem da observação de que a maioria das pesquisas sobre *code smells* foca em classes ou métodos, enquanto os problemas arquiteturais de maior escala recebem menos atenção, apesar de afetarem profundamente a evolução do sistema. Para isso, o estudo avalia projetos open source, analisando métricas de qualidade e evolução associadas a diferentes tipos de *architectural smells*. A metodologia combina análise de repositórios com técnicas de detecção automática de *smells*, relacionando-os com indicadores de esforço de manutenção. Os resultados sugerem que certos tipos de *smells*, como *cyclic dependencies* e *god components*, estão fortemente associados ao aumento da complexidade e ao maior esforço de manutenção. Além disso, os autores destacam que não apenas a presença, mas também a severidade e propagação desses *smells* influenciam negativamente a capacidade de evoluir o software. Assim, o artigo reforça a importância de ferramentas e práticas de monitoramento contínuo para prevenção e mitigação de problemas arquiteturais.

---

## 2. Fichamento Bibliográfico

- **Architectural smells** são sintomas de problemas de design em nível de arquitetura, que indicam potenciais dificuldades na manutenção e evolução do sistema (p. 106).  
- **Cyclic dependency** ocorre quando módulos dependem entre si em ciclos, o que aumenta o acoplamento e dificulta mudanças (p. 107).  
- **God component** é um módulo centralizado que concentra responsabilidades excessivas, tornando-se um gargalo de manutenção (p. 107).  
- O estudo adota uma análise empírica baseada em repositórios de projetos open source, relacionando a ocorrência de *smells* com métricas de manutenção (p. 108).  
- A presença e a severidade de *smells* estão fortemente correlacionadas com maior esforço de manutenção e menor qualidade de evolução (p. 112).  

---

## 3. Fichamento de Citações

- "Architectural smells are symptoms of poor design decisions at the architectural level that can hinder system maintainability and evolution." (p. 106)  
- "Cyclic dependencies among components significantly increase the maintenance effort due to higher coupling." (p. 107)  
- "God components act as central hubs in the architecture, accumulating responsibilities and limiting modularity." (p. 107)  
- "Our empirical results show that the presence and severity of architectural smells correlate with increased maintenance costs." (p. 112)  
- "Monitoring and refactoring architectural smells should be a priority to ensure long-term maintainability." (p. 113)  

