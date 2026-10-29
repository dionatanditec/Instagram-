# Registro de decisões

Formato: data — decisão — motivo. Mais recentes no topo.

## 2026-10-29 — Plugin Marketing (Anthropic) instalado
- **Decisão:** instalar o plugin oficial Marketing no escopo do projeto (`.claude/settings.json`).
  Código lido por inteiro antes; nenhum conector externo (Gmail, Slack, Canva…) foi conectado.
- **Regra nova:** as regras de `memoria/` e as skills próprias têm prioridade sobre o plugin
  (ele sugere urgência, depoimentos e hashtags em bloco, o que não serve para a Taína).
- **Motivo:** aprovação do Dionatan. Detalhes e riscos em `plugins-avaliados.md`.

## 2026-10-29 — Skills próprias em vez de instalar as de terceiros
- **Decisão:** criar 6 skills próprias em português (`.claude/skills/`), inspiradas nas boas ideias
  dos pacotes pesquisados, em vez de instalar pacotes de terceiros.
- **Motivo:** regra do CLAUDE.md (nada de terceiros sem aprovação); os pacotes encontrados são em inglês
  e genéricos, sem as regras de ética da área de saúde mental. Avaliação completa em `plugins-avaliados.md`.
- **Atualização:** o Dionatan aprovou só o plugin Marketing (Anthropic); os pacotes do GitHub continuam não instalados.

## 2026-10-29 — Coordenador + agente
- **Decisão:** a sessão principal age como coordenador (`.claude/agents/coordenador-instagram.md`) e delega
  a produção ao subagente `agente-instagram`.
- **Motivo:** pedido do Dionatan. Separar planejamento/revisão de produção melhora a qualidade:
  o coordenador revisa com checklist tudo o que o agente entrega.

## 2026-10-29 — Criação do repositório de Instagram
- **Decisão:** usar o repositório `Instagram-` para estratégia e conteúdo; `Edi-o-videos` continua com a edição.
- **Motivo:** pedido do Dionatan para ter um social media/analista sênior de Instagram com memória própria.

## 2026-10-29 — Regras herdadas do repositório de vídeos
- **Decisão:** mesmas regras de segurança (nada de terceiros sem aprovação, ler o código antes,
  sem senhas nos arquivos, sem vídeos no GitHub) e mais duas: nunca publicar sozinho e não inventar métricas.
- **Motivo:** manter um padrão único entre os repositórios.
