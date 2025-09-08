# Modular Monolith: Is This the Trend in Software Architecture?

Su, R., & Li, X. (2024). *Modular Monolith: Is This the Trend in Software Architecture?* In Proceedings of the 2024 Conference on Software Architecture Patterns. University of Oulu, Finland.

---

## 1. Fichamento de Conteúdo

Este artigo investiga a arquitetura de *modular monolith* como uma tendência emergente no design de software, motivada pelo lançamento do framework *Service Weaver* pelo Google. Os autores realizam uma *Systematic Grey Literature Review* (SGLR) para compreender a definição, frameworks e casos de uso do *modular monolith* na indústria. A partir de 140 resultados iniciais, 64 estudos foram selecionados para análise. Os resultados mostram que o *modular monolith* é um padrão arquitetural que combina as vantagens do monolito tradicional (simplicidade de desenvolvimento e implantação) com os benefícios dos microsserviços (modularidade e baixo acoplamento). O sistema é organizado em módulos independentes com dependências bem definidas, podendo ser implantado como uma única unidade ou posteriormente migrado para microsserviços. Foram identificados três frameworks principais (*Service Weaver*, *Spring Modulith* e *Light-hybrid-4j*) e quatro casos de uso industriais (*Shopify*, *Appsmith*, *Gusto* e *PlayTech*) que adotaram essa abordagem. O estudo conclui que o *modular monolith* representa uma alternativa viável aos microsserviços, especialmente para projetos que buscam equilibrar velocidade de desenvolvimento e escalabilidade, podendo também servir como etapa intermediária em migrações futuras.

---

## 2. Fichamento Bibliográfico

- ***Modular Monolith***: Padrão arquitetural que organiza o sistema em módulos fracamente acoplados, com limites bem definidos e dependências explícitas, combinando a simplicidade de implantação monolítica com a modularidade de microsserviços (p. 3).  
- ***Service Weaver***: Framework open-source do Google que permite escrever aplicações como um monolito modular e implantá-las como microsserviços, usando chamadas de método nativas em Go (p. 4).  
- ***Spring Modulith***: Projeto experimental do Spring para aplicações monolíticas modulares, oferecendo convenções e APIs para declarar e validar módulos lógicos (p. 4).  
- ***Light-hybrid-4j***: Framework baseado em *light-4j* para arquitetura monolítica modular e serverless, focando em flexibilidade de implantação e redução de custos (p. 5).  
- ***Casos de Uso***: *Shopify*, *Appsmith*, *Gusto* e *PlayTech* adotaram *modular monolith* como alternativa a microsserviços, citando simplicidade, custo e manutenibilidade como fatores decisivos (p. 5).  
- ***Systematic Grey Literature Review (SGLR)***: Metodologia usada para buscar e analisar literatura cinzenta (blogs, documentação, artigos não acadêmicos) sobre o tópico, com *snowballing* para identificar estudos adicionais (p. 2).  

---

## 3. Fichamento de Citações

- "Modular Monolith is a software architecture pattern that strategically combines the simplicity of a monolithic structure with the advantages of microservices." (p. 3)  
- "Service Weaver allows people to write the application as a modular monolith and deploy it as a set of microservices." (p. 4)  
- "Shopify is a great example that has used this approach as an alternative to microservice decomposition." (p. 5)  
- "Modular monolith is an alternative way to microservices, and it also could be a previous step before systems migrate to microservices." (p. 6)  
- "The goal is to achieve independence and isolation for each module, allowing them to be worked on independently while still being deployed collectively as a single unit." (p. 3)  
- "They chose modular monolith because it allowed them to maintain one large codebase, deploy a single binary, and balance the interests of their end customers." (p. 5)  

---