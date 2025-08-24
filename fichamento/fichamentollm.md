# Fichamento: NPCs Orientados por LLM: Sistema de Diálogo Multiplataforma para Jogos e Plataformas Sociais

**Autor:** Li Song  
**Fonte:** Artigo acadêmico, 2024. Disponível em: [link não informado]. Acesso em: [data não informada].

---

## 1. Fichamento de Conteúdo

Este artigo propõe um sistema inovador que utiliza Large Language Models (LLMs) para criar NPCs (Personagens Não-Jogáveis) com diálogos dinâmicos e persistentes, capazes de interagir com jogadores tanto dentro de um ambiente de jogo (Unity) quanto em uma plataforma social externa (Discord). O sistema armazena os registros de diálogo em um banco de dados em nuvem (LeanCloud), permitindo sincronização de memória entre plataformas e mantendo a coerência das conversas. Os autores identificam a limitação dos NPCs tradicionais, que dependem de árvores de diálogo estáticas e estão restritos a um único ambiente. Por meio de experimentos iniciais, demonstram a viabilidade técnica da interação multiplataforma e sugerem a base para desenvolvimentos futuros, como modelagem emocional e suporte a memória persistente. O estudo conclui que a integração de LLMs pode transformar NPCs em companheiros sociais contínuos, ampliando os limites do storytelling interativo.

---

## 2. Fichamento Bibliográfico

- **Large Language Models (LLMs):** Modelos de linguagem de grande escala capazes de compreender contexto e gerar respostas naturais, usados para dar vida a NPCs com diálogos fluidos e adaptativos (p. 1–2).
- **Sistema de Favorabilidade:** Mecanismo simples que ajusta o tom e o conteúdo das respostas do NPC com base no histórico de interações com o jogador (p. 2–3).
- **Fluxo de Dados Multiplataforma:** Arquitetura que salva e recupera diálogos de um banco de dados em nuvem para manter a consistência contextual entre o jogo (Unity) e o Discord (p. 3–4).
- **Memória de Curto Prazo:** Recuperação das últimas interações (ex.: 6 turnos) para contextualizar respostas, mas com limitação em diálogos muito longos (p. 4–5).

---

## 3. Fichamento de Citações

- "NPCs in traditional games are often limited by static dialogue trees and a single platform for interaction." (p. 1)
- "Large Language Models (LLMs), with their strong contextual understanding and ability to generate natural-sounding responses, offer a promising alternative." (p. 1)
- "Building an NPC system that allows consistent interaction across both games and social platforms could meaningfully enhance the player experience and sense of continuity." (p. 1)
- "The system also includes a basic favorability mechanism to shape how the NPC responds based on prior interaction history." (p. 1)
- "The LLM is capable of maintaining coherent conversations across different platforms." (p. 5)
- "Introducing a vector database or retrieval-augmented generation (RAG) mechanism could help the system retain essential memories over longer time spans." (p. 5)
- "NPCs can become not just game elements, but persistent social companions that exist across platforms." (p. 6)