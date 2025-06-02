# 📚🤖 Chatbot Inteligente para Livraria Online com LLM + Banco Vetorial

Este projeto tem como objetivo implementar um **chatbot baseado em LLM** que atua como assistente inteligente para uma **livraria online**, capaz de responder perguntas em **linguagem natural** sobre:

- 📘 Livros disponíveis
- 🧠 Recomendações baseadas no catálogo
- 📝 Conteúdos e curiosidades do blog da livraria

---

## 🎯 Objetivo

Ajudar clientes da livraria a obterem informações rápidas e contextuais sobre o catálogo e conteúdos editoriais, utilizando **modelos de linguagem** com acesso a **um banco vetorial enriquecido**.

---

## ⚙️ Tecnologias Utilizadas

| Tecnologia         | Finalidade                                                |
|--------------------|-----------------------------------------------------------|
| **Python 3.10+**   | Linguagem principal do projeto                            |
| **Groq API (LLM)** | Geração de respostas em linguagem natural                 |
| **LlamaIndex**     | Framework para conectar LLM a dados estruturados e textos |
| **FAISS / Chroma** | Banco de dados vetorial                                   |
| **Gradio**         | Interface web acessível para interação                    |
| **Pandas**         | Processamento dos dados do CSV                            |

---

## 🧠 Como Funciona

1. Os dados do **catálogo da livraria (CSV)** são transformados em **documentos vetoriais**.
2. Textos de **postagens do blog** também são inseridos no mesmo **índice vetorial**, ampliando o contexto.
3. O LLM, ao receber uma pergunta, busca contexto no índice e gera uma **resposta inteligente** com base em múltiplas fontes.
4. A resposta é entregue ao usuário final por meio de uma **interface amigável**.

---

## 💬 Exemplos de Perguntas

- “Quais são os livros mais vendidos sobre desenvolvimento pessoal?”
- “Me recomende um livro de ficção científica recente.”
- “Tem algum artigo do blog falando sobre hábitos de leitura?”
