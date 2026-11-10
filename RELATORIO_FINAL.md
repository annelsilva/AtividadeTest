# Relatório Final de Testes e Qualidade

## 1. Resumo dos Indicadores (Google Lighthouse)

| Categoria | Pontuação Inicial (Antes) | Meta / Pós-Correção (Depois) |
| :--- | :---: | :---: |
| **Performance** | 55 | 90+ |
| **Acessibilidade** | 65 | 95+ |
| **Boas Práticas** | 78 | 100 |
| **SEO** | 70 | 90+ |

---

## 2. Matriz de Bugs Identificados

| ID da Issue | Título do Bug / Falha | Tipo | Severidade | Status |
| :---: | :--- | :---: | :---: | :---: |
| **#1** | [Performance] Script bloqueante causa lentidão na página | Performance | Alta | Aberto |
| **#2** | [UX/Acessibilidade] Menu superior fixo sobrepõe o conteúdo | Usabilidade / Design | Média | Aberto |

---

## 3. Recomendações Técnicas
1. **Performance:** Remover o loop síncrono do arquivo `script.js` ou utilizar o atributo `defer`/`async` no carregamento dos scripts.
2. **Acessibilidade & UX:** Ajustar o `padding-top` do contêiner de conteúdo principal para evitar que o menu fixo cubra os textos, e aplicar cores de fundo/fonte conforme os critérios de contraste do WCAG.
