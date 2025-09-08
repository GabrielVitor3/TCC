# An Empirical Investigation of the Impact of Architectural Smells on Software Maintainability  

Jolak, R.; Karlsson, S.; Dobslaw, F. *An Empirical Investigation of the Impact of Architectural Smells on Software Maintainability*. The Journal of Systems & Software, vol. 225, 112382, 2025. doi:10.1016/j.jss.2025.112382  

---

## 1. Fichamento de Conteúdo  

O artigo investiga empiricamente o impacto de *architectural smells* na manutenibilidade de sistemas de software, avaliando duas subcaracterísticas específicas do padrão ISO/IEC 25010:2023: *modularity* e *testability*. Os autores partem da crítica de que grande parte das afirmações sobre o impacto negativo de *smells* arquiteturais é baseada em opinião de desenvolvedores ou pressupostos teóricos, sem validação empírica. Para preencher essa lacuna, conduziram um *multiple embedded case study* em oito projetos *open source* em Java, selecionados com critérios de relevância (≥10k LOC, ≥3 anos de atividade, presença de *smells* e builds consistentes). Foram analisadas 378 versões, cobrindo cerca de 29 anos de desenvolvimento. A coleta de dados utilizou a ferramenta ASAT (Architectural Smell Analysis Tool), que integra *Designite* (detecção de *smells*), *DV8* (cálculo de *Decoupling Level* e *Propagation Cost*) e *JaCoCo* (métrica de *code coverage* para testabilidade). O estudo avaliou sete *smells*: *Ambiguous Interface, Cyclic Dependency, Feature Concentration, God Component, Scattered Functionality, Unstable Dependency* e *Dense Structure*. A análise estatística foi feita com coeficiente de Spearman (ρ), devido à distribuição não normal dos dados, considerando significância em p<0,05. Os resultados mostram que, de modo geral, a maioria dos *smells* não apresentou correlação negativa consistente com modularidade no nível de projeto — com exceção de *Dense Structure*, que exibiu impacto negativo forte. Já em relação à *testability*, houve correlações negativas em nível de projeto, mas mais fortemente associadas ao tamanho do sistema do que aos *smells* em si. Em nível de pacotes, a maioria das correlações foi insignificante, embora *God Component* e *Scattered Functionality* tenham se destacado por prejudicar a *testability*. A conclusão central é que o tamanho do projeto é um fator confundidor dominante: ele influencia modularidade e testabilidade mais fortemente que os *smells*, embora alguns tipos específicos (como *Dense Structure*, *God Component* e *Scattered Functionality*) sejam de fato indicadores relevantes de risco para a manutenibilidade. O trabalho reforça que a análise de *smells* deve ser contextualizada, contínua e apoiada por ferramentas automatizadas para orientar refatorações estratégicas.  

---

## 2. Fichamento Bibliográfico  

- **Definição de *Architectural smells***: sintomas recorrentes de más decisões de design em nível arquitetural, que violam princípios como modularidade, hierarquia e dependências estáveis, e podem gerar *technical debt* (p. 1–2).  
- **Subcaracterísticas de manutenibilidade avaliadas**: *modularity* (grau de independência entre componentes) e *testability* (facilidade e eficiência para estabelecer critérios de teste e validar componentes) (p. 3–4).  
- **Projetos analisados**: 8 sistemas Java *open source*, totalizando 378 versões e cerca de 29 anos de desenvolvimento. Critérios: ≥10k LOC, ≥3 anos de atividade, presença de *smells*, builds consistentes (p. 6).  
- **Ferramentas**:  
  - *Designite*: detecção dos sete *smells* arquiteturais (p. 7–8).  
  - *DV8*: cálculo de *Decoupling Level (DL)* e *Propagation Cost (PC)* (p. 9).  
  - *JaCoCo*: métrica de *code coverage* (linhas e ramos) para testabilidade (p. 9–10).  
- **Resultados principais**:  
  - *Dense Structure*: forte correlação negativa com *modularity* em quase todos os projetos (p. 15).  
  - *God Component* e *Scattered Functionality*: impacto negativo mais consistente sobre *testability* em nível de projeto e pacotes (p. 17–18).  
  - *Ambiguous Interface* e *Cyclic Dependency*: mostraram alguma influência negativa sobre *modularity*, mas de forma menos consistente (p. 20).  
  - Tamanho do projeto (*LOC* e número de classes) foi fator mais fortemente correlacionado tanto com *modularity* quanto com *testability* (p. 18–19).  

---

## 3. Fichamento de Citações  

- “*Architectural smells are recurring, identifiable architectural design decisions that mainly impact the maintainability of a system*.” (p. 1)  
- “*We investigate modularity and testability because quantifiable means exist to assess them. Modularity is measured using Decoupling Level and Propagation Cost. Testability is estimated by code coverage of files impacted by architectural smells*.” (p. 4)  
- “*Eight open-source projects were selected, covering 378 versions and approximately 29 years of active development data*.” (p. 6)  
- “*Most projects studied did not exhibit negative correlations between architectural smells and modularity at the project level, with the Dense Structure smell as an exception*.” (p. 15)  
- “*At the project level, testability showed stronger negative correlations with project size than with architectural smells*.” (p. 17)  
- “*Our findings show that Ambiguous Interface, Cyclic Dependency, and Dense Structure negatively influence modularity, while God Component and Scattered Functionality impair testability at both project and package levels*.” (p. 22)  
