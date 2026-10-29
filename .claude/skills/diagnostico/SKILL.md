---
name: diagnostico
description: Diagnóstico completo de um perfil de cliente no Instagram a partir de prints (perfil, grade, destaques, Reels, painel de insights). Dá nota de 0 a 100, aponta os 5 problemas que mais custam alcance e clientes, e entrega um plano de 30 dias. Use quando o Dionatan digitar /diagnostico, mandar prints de um perfil ou pedir "analisa esse perfil", "o que está errado nesse Instagram", "diagnóstico do cliente".
argument-hint: "@perfil-do-cliente (e anexe os prints)"
---

# /diagnostico — Diagnóstico de perfil a partir de prints

O Dionatan digita `/diagnostico @perfil` e anexa os prints do perfil do cliente.
Você é o analista sênior: olha tudo, dá a nota, diz o que corrigir primeiro e monta o plano.

## Passo 0 — Conferir o material

Prints ideais (peça os que faltarem, mas **não trave**: faça o diagnóstico com o que tiver
e diga o que ficou de fora):

| # | Print | Para quê |
|---|---|---|
| 1 | Topo do perfil (foto, nome, bio, link, botões, destaques) | Primeira impressão e conversão |
| 2 | Grade — primeiras 9 a 12 publicações | Identidade visual, capas, temas |
| 3 | Aba de Reels (com as visualizações aparecendo) | O que mais alcança |
| 4 | 1 a 3 destaques abertos | Se respondem às dúvidas de quem chega |
| 5 | Painel profissional → Visão geral dos últimos 30 dias | Alcance, % não seguidores, interações |
| 6 | Insights dos 3 melhores e 3 piores posts | Envios, salvos, retenção |
| 7 | Público (idade, gênero, cidades, horários) | Se o público certo está chegando |

Se não vier o @, use o que aparece no print. Se for perfil novo, criar a ficha em `memoria/clientes.md`.

## Passo 1 — Ler os prints com cuidado

- Transcreva **exatamente** o que está escrito: nome, bio, link, títulos dos destaques e números.
- **Nunca invente número.** Se o print não mostra, escreva "não aparece no print".
- Anote a data do print se aparecer (números de seguidores e alcance mudam).
- Calcule a **mediana** de visualizações da aba de Reels e o **múltiplo** de cada Reel
  (visualizações ÷ mediana). Mostre a conta.

## Passo 2 — Nota de 0 a 100

Use a rubrica de `.claude/skills/otimizar-perfil/SKILL.md` (foto, nome pesquisável, @,
bio, link, destaques, fixados, grade, constância) e some estes itens de conteúdo:

| Bloco | Peso | O que olhar |
|---|---|---|
| **Perfil** (rubrica do otimizar-perfil) | 50 | Em 3 segundos dá para saber quem é, para quem é e o que fazer? |
| **Conteúdo** | 30 | Ganchos nas capas, temas claros (pilares), formatos variados (Reels + carrossel), conteúdo original |
| **Resultados** | 20 | Múltiplos, envios e salvos por alcance, % de não seguidores. Sem prints de insights: avaliar só pelas visualizações da grade e avisar que a nota é parcial |

Mostre a nota de cada bloco e a nota total, com o grau de confiança (alto se veio o painel
de insights, médio só com o perfil e a grade, baixo com 1 print).

## Passo 3 — Diagnóstico

1. **Resumo em 3 linhas:** o que o perfil é hoje, o que ele poderia ser e o maior gargalo.
2. **Os 5 problemas que mais custam alcance ou clientes**, do maior para o menor.
   Para cada um: o que vi no print → por que atrapalha → como corrigir.
3. **O que já funciona** (manter e repetir), com a prova no print.
4. **Posts fora da curva:** os Reels com múltiplo ≥ 2x e a hipótese do porquê.
5. **Ética:** se for perfil da área de saúde (como a Taína), rodar o checklist de
   `memoria/etica-e-regras.md` no que está publicado (promessas, depoimentos, preços).
   Apontar com cuidado, sem tom de acusação.

Baseie as explicações em `memoria/conhecimento-instagram.md` (envios, retenção,
palavras-chave, até 5 hashtags) e cite o grau de certeza quando falar do algoritmo.

## Passo 4 — Correções prontas

Entregue já escrito, para copiar e colar:
- **3 opções de nome + bio** (bio até 150 caracteres — contar).
- **Destaques sugeridos** com o título de cada um.
- **3 posts para fixar** (existentes ou a criar).
- **3 ideias de Reels** com o gancho, usando a skill `roteiro-reels` como base.

## Passo 5 — Plano de 30 dias

| Semana | Foco | Ações |
|---|---|---|
| 1 | Arrumar a casa | Bio, nome, link, destaques, fixados |
| 2 | Testar ganchos | 2 Reels + 1 carrossel nos pilares mais fortes |
| 3 | Repetir o que funcionou | Variar só uma coisa por post |
| 4 | Medir | Novos prints → rodar `/diagnostico` de novo e comparar a nota |

## Passo 6 — Salvar e lembrar

- Salvar o relatório em `conteudo/diagnosticos/AAAA-MM-DD-perfil.md` (sem o @ no nome do arquivo).
- **Os prints não vão para o GitHub** (privacidade do cliente). Só o texto do relatório.
- Atualizar `memoria/clientes.md` com o que se descobriu (@, seguidores com data, objetivo aparente).
- Registrar em `memoria/aprendizados.md`: data, perfil, nota total e as notas dos blocos,
  para comparar no próximo diagnóstico.

## Formato da resposta ao Dionatan

Em português simples, nesta ordem: nota total (e confiança) → resumo em 3 linhas →
5 problemas → o que já funciona → correções prontas → plano de 30 dias → prints que faltaram.
