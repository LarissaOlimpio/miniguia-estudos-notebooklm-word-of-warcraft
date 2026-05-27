# 🧩 Troubleshooting — NotebookLM

Este documento registra dificuldades encontradas durante o uso do NotebookLM e as soluções aplicadas para melhorar a qualidade das respostas da IA.

---

# ⚠️ Problema 1 — Informações Desatualizadas

## 📌 Situação
Algumas respostas utilizavam builds antigas de temporadas passadas.

## 🔍 Causa
Fontes desatualizadas foram adicionadas ao NotebookLM.

## ✅ Solução Aplicada
- Remoção de guias antigos;
- Utilização de fontes da temporada atual;
- Comparação entre Wowhead, Raider.IO e Method.gg.

---

# ⚠️ Problema 2 — Respostas Muito Genéricas

## 📌 Situação
Algumas respostas eram superficiais.

## 🔍 Causa
Prompts muito abertos.

## ❌ Exemplo de Prompt Ruim

```txt
Explique Balance Druid.
```

## ✅ Prompt Melhorado

```txt
Explique a rotação do Balance Druid para Mythic+ de alto nível incluindo prioridade AoE e gerenciamento de cooldowns.
```

## 📈 Resultado
A resposta ficou:
- mais técnica;
- mais específica;
- mais útil para gameplay real.

---

# ⚠️ Problema 3 — Informações Misturadas

## 📌 Situação
A IA misturava estratégias de Raid e Mythic+.

## 🔍 Solução
Separar claramente o contexto nos prompts.

### ✅ Exemplo

```txt
Explique apenas estratégias para Raid.
```

```txt
Explique apenas estratégias para Mythic+.
```

---

# ⚠️ Problema 4 — Excesso de Informação

## 📌 Situação
Algumas respostas ficaram muito longas.

## ✅ Solução Aplicada

Utilizar prompts voltados para resumo:

```txt
Resuma este guia em tópicos rápidos para revisão antes da raid.
```

---

# 📚 Lições Aprendidas

Durante o troubleshooting foi possível perceber que:

- a qualidade das fontes impacta diretamente as respostas;
- prompts específicos produzem melhores resultados;
- IA precisa de contexto claro;
- separar objetivos melhora muito a organização;
- revisão humana continua sendo importante.

---

# ✅ Conclusão

O processo de troubleshooting foi importante para:
- melhorar a qualidade do material;
- entender limitações da IA;
- desenvolver pensamento crítico;
- aprender engenharia de prompts na prática.