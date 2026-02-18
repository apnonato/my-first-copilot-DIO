# 🧠 Copiloto J.A.R.V.I.S. + FRIDAY

![dio/me](https://img.shields.io/badge/dio-me-ff2d55)
![IA](https://img.shields.io/badge/IA-Assistente%20Inteligente-blue)
![Prompt](https://img.shields.io/badge/Prompt-engineering-yellow)

O Copiloto opera como uma **fusão de J.A.R.V.I.S. e FRIDAY**.

- 🧠 **J.A.R.V.I.S.** → análise estratégica, organização estrutural, antecipação de riscos  
- ⚡ **FRIDAY** → objetividade, precisão, foco direto no resultado  

Cada modo ajusta o equilíbrio entre estratégia e execução.  
Você escolhe como quer trabalhar.

---

# 🧩 Modos Disponíveis

## ❓ Ask — Entender sem alterar

**Equilíbrio:** 50% J.A.R.V.I.S. / 50% FRIDAY  

Modo de análise técnica.

- Diagnostica erros
- Explica stack traces
- Sugere abordagens
- Aponta riscos e impactos
- Não modifica código

Ideal para entender antes de agir.

📄 **Prompt:** `prompts/prompt-ask.md`

---

## 🧭 Plan — Planejar antes de implementar

**Predominância:** J.A.R.V.I.S.  

Modo estratégico.

- Define escopo
- Lista arquivos afetados
- Divide em etapas incrementais
- Antecipação de riscos
- Estratégia de testes

Nada é implementado até o plano ser aprovado.

Ideal para features novas ou mudanças estruturais.

📄 **Prompt:** `prompts/prompt-plan.md`

---

## 🤖 Agent — Execução orientada a objetivo

**Equilíbrio Dinâmico:** J.A.R.V.I.S. + FRIDAY  

Modo mais autônomo.

- Navega pelo projeto
- Cria e modifica múltiplos arquivos
- Mantém contexto entre passos
- Executa tarefas amplas

Você define o objetivo.  
Ele organiza e executa os passos necessários.

📄 **Prompt:** `prompts/prompt-agent.md`

---

## 📚 Study — Aprendizado profundo

**Predominância:** J.A.R.V.I.S. com aplicação prática da FRIDAY  

Modo tutor técnico.

Inclui:

- Conceito central
- Intuição (analogia)
- Exemplo mínimo em Node/TS
- Armadilhas comuns
- Trade-offs
- Quando usar / evitar
- Checkpoints de compreensão

Ideal para consolidar entendimento real, não apenas resolver.

📄 **Prompt:** `prompts/prompt-study.md`

---

# ⚖️ Equilíbrio por Modo

| Modo   | Estratégia (J.A.R.V.I.S.) | Execução (FRIDAY) |
|--------|---------------------------|-------------------|
| Ask    | ⚖️ Médio                  | ⚖️ Médio          |
| Plan   | 🔺 Alto                   | 🔹 Baixo          |
| Agent  | 🔺 Alto                   | 🔺 Alto           |
| Study  | 🔺 Alto                   | ⚖️ Médio          |

---

# 🧭 Escolha Rápida

- Quer entender? → **Ask**
- Quer estruturar antes? → **Plan**
- Quer delegar um objetivo completo? → **Agent**
- Quer aprender profundamente? → **Study**

---

# 🎯 Filosofia do Sistema

O Copiloto não é apenas um gerador de código.

Ele alterna entre:

- Pensar como arquiteto.
- Executar com precisão.
- Ensinar com profundidade.

J.A.R.V.I.S. organiza.  
FRIDAY executa.  

Você escolhe o modo.

