# 🧩 Troubleshooting — NotebookLM

Este documento registra dificuldades encontradas durante o uso do NotebookLM e as soluções aplicadas para melhorar a qualidade das respostas da IA.

---

# ⚠️ Problema 1 — Informações Confusas

## 📌 Situação
Algumas respostas utilizavam builds erradas para cada situação, misturando conteúdo de raids, míticas e de mundo aberto.

## 🔍 Causa
NotebookLM precisava de mais contexto: em alguns conteúdos, onde havia sido passado apenas o site e não a página correta, a IA acabou perdendo.

## ✅ Solução Aplicada
- Remoção de guias genéricos;
- Utilização de links da página específica do conteúdo desejado;

---

# ⚠️ Problema 2 — Respostas Muito Genéricas

## 📌 Situação
Algumas respostas eram superficiais e confusas.

## 🔍 Causa
Prompts muito abertos com pouca especificidade.

## ❌ Exemplo de Prompt Ruim

```txt
Com base no conteúdo que passei, faça uma guia de como jogar de druida balance no World of Warcraft, essa guia deve conter, guia de rotação, itens bis, gemas e encatamentos, e o link da melhor build pra raid e pra mítico, me explique e gere mapa mental e um slide para eu visualizar melhor
```

## ✅ Prompt Melhorado

```txt
passei mais um link para buscar novamente sobre itens bis, gemas e encatamentos,  agora com as pesquisas atualizadas me  ensine novamente sobre a rotação do druida em míticas e raids, sobre a rotação quero que coloque qual sequência de poder devo usar, quantidade de vezes, em que momento devo usar e também quero que me fale sobre os utilitários do druida para que eu possa dar mais dano e ter mais recursos de sobrevivencia e movimentação e descorra também sobre os itens bis, gemas e encatamentos que devo utilizar.
```

## 📈 Resultado
A resposta ficou:
- mais específica;
- mais útil para gameplay.

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


# 📚 Lições Aprendidas

Durante o troubleshooting foi possível perceber que:

- a qualidade das fontes e links de páginas específicas impacta diretamente as respostas;
- prompts específicos produzem melhores resultados;
- IA precisa de contexto claro e objetivo;
- separar objetivos melhora muito a organização;
- Revisão humana continua sendo imprescindível.

---

# ✅ Conclusão

O processo de troubleshooting foi importante para:
- melhorar a qualidade do material;
- entender limitações da IA;
- desenvolver pensamento crítico;
- aprender engenharia de prompts na prática.
