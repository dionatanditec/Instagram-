# Skills e plugins de terceiros avaliados

Pesquisa automática feita em **2026-10-29**. **Nada foi instalado.**
Status possíveis: 🔍 avaliado · ⏳ aguardando aprovação do Dionatan · ✅ aprovado · ❌ recusado.

## Pacotes de skills no GitHub (código lido)

### 1. Jakeschincariol/instagram-agent-skill — ⏳
- **Link:** https://github.com/Jakeschincariol/instagram-agent-skill · Licença MIT · atualizado em set/2026.
- **O que é:** 13 skills (`/ig-reel`, `/ig-caption`, `/ig-carousel`, `/ig-story`, `/ig-profile`, `/ig-plan`,
  `/ig-viral`, `/ig-audit`, `/ig-human`, `/ig-comment`, `/ig-reply`, `/ig-dm`, `/ig-repurpose`).
- **Código lido:** 6 scripts Python (`caption.py`, `hookscore.py`, `beats.py`, `swipe.py`, `detect.py`,
  `humanize.py`). Só leem texto local e escrevem arquivos; **não usam internet, não pedem chave de API**,
  sem `subprocess`/`eval`.
- **Pontos fortes:** pontuação de ganchos (26 fórmulas), linha do tempo do Reel, "múltiplo sobre a
  mediana" para achar posts fora da curva, nota de perfil de 0 a 100.
- **Limites:** tudo em inglês (o detector de "texto de IA" usa vocabulário em inglês e não serve para
  português); nada sobre ética em saúde mental.
- **O que já aproveitamos (só ideias, sem copiar código):** múltiplo sobre a mediana, nota de perfil,
  ganchos por fórmula, legenda de 125 caracteres.

### 2. sergebulaev/instagram-skills — ⏳ (só modo rascunho)
- **Link:** https://github.com/sergebulaev/instagram-skills · MIT · atualizado em out/2026.
  (Há uma cópia: catiacreator/instagram-skills.)
- **O que é:** 9 skills (legenda, carrossel, extrator de gancho, hashtags, humanizador, calendário,
  reaproveitamento, perfil, insights de audiência).
- **Código lido:** `requirements.txt` pede `requests` e `python-dotenv`. A publicação usa a API paga
  **Publora** e a leitura de dados usa **Apify** — ambos exigem chave de API e conta. Sem chave, funciona
  só em modo rascunho.
- **Risco:** conectar a agendador externo com acesso à conta da Taína. Não recomendo a parte de publicação.

### 3. coreyhaines31/marketingskills — 🔍
- **Link:** https://github.com/coreyhaines31/marketingskills · MIT · atualizado em out/2026.
- **O que é:** pacote grande de marketing (copy, SEO, e-mail, PR) com uma skill `social` geral.
  Útil para copy, mas pouco específico de Instagram.

### 4. guyaga/claude-code-social-media-skill — ❌ (não recomendado agora)
- **Link:** https://github.com/guyaga/claude-code-social-media-skill · MIT.
- **O que é:** um único SKILL.md para **publicar** em várias redes via API paga Upload Post (pede chave em `.env`).
- **Motivo:** publicação automática vai contra a regra "o Dionatan aprova e publica".

## Plugins do catálogo do Claude (claude.ai)

| Plugin | Quem publica | O que faz | Recomendação |
|---|---|---|---|
| **Marketing** | Anthropic (oficial) | Criar conteúdo, planejar campanhas, voz de marca, concorrentes, relatórios | ⏳ melhor candidato — oficial, sem chave de API |
| **Social Media Skills** (106 skills) | Comunidade (Frank Heijdenrijk) | Estratégia, escrita, vídeo, design, crescimento, analytics | 🔍 ler antes; muito amplo |
| Posty / Ayrshare | Comunidade | Agendar e publicar em várias redes | ❌ por enquanto (publicação automática, pede conta) |
| Windsor.ai | Parceiro | Dados de anúncios Meta/Instagram | 🔍 só se a Taína fizer anúncios pagos |

## Próximo passo

Para instalar qualquer item ⏳, o Dionatan precisa aprovar por escrito. Sugestão de ordem:
1. Plugin oficial **Marketing** (Anthropic).
2. Copiar para `.claude/skills/` só as skills de `Jakeschincariol/instagram-agent-skill`
   que não temos (`ig-comment`, `ig-reply`, `ig-dm`, `ig-story`), traduzindo e adaptando à ética.
