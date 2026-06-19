# CLAUDE.md — oracle-diagnostic-lite

## O que é este repo

Uma skill do Claude distribuída como repositório público no GitHub. A única
fonte de verdade do comportamento é `skills/oracle-diagnostic-lite/SKILL.md`.
Toda mudança de comportamento começa por lá.

A skill é a **leitura de superfície do Creative Oracle™** — a porta de entrada
gratuita. Roda 3–5 perguntas e devolve onde a tensão se concentra (uma de
quatro frentes), sem prescrever. Termina fazendo o handoff para o Diagnóstico
Oracle completo. O repo é uma vitrine: o README é uma landing page, não só
documentação.

## O que editar

| Arquivo | O que controla |
|---------|----------------|
| `skills/oracle-diagnostic-lite/SKILL.md` | Comportamento — triggers, roteiro, leitura, handoff. PT-BR, canônico. |
| `skills/oracle-diagnostic-lite/README.md` | Resumo por-skill voltado pra humano. |
| `README.md` (raiz) | Porta de entrada do produto. Funil isca → Diagnóstico Oracle completo. |
| `assets/social-preview.html` | Instância do gabarito DS V3.0 (motivo quadrant) do social card. |
| `page/index.html` | Página-vitrine interativa publicada na Vercel. |

## O que NÃO editar

- Não edite a skill canônica no monorepo privado `mscs-skills` a partir daqui —
  este repo é um espelho publicado. Mudanças de comportamento fluem pelo `skills-sync`.
- Mantenha o frontmatter do SKILL.md (`name`, `description`, `metadata`) intacto.
- **Nunca publique pricing.** Esta é a entrada grátis do funil. Sem valores,
  sem tabela de preço, nem no README nem na página. Só leitura de superfície +
  handoff pro diagnóstico completo.
- Não reproduza a lógica do diagnóstico completo (leitura cruzada das quatro
  frentes, ordem de ataque, "como" resolver). Isso é o motor pago.
- Nunca commite `.env`, tokens ou credenciais.

## Convenções

- Idioma: README/skill em PT-BR; voz Tradutor, frases curtas, voz ativa, zero floreio.
  Sem léxico inflado, sem paralelismo negativo. Termo proprietário aterrissa na 1ª menção
  (Creative Oracle™ na primeira vez que aparecer).
- O Oracle nunca é "ferramenta" nem "assistente" — é árbitro estratégico.
- Commits: Conventional Commits. Push só com SHA verificado (local = remote).

## Licença

MIT. Creative Oracle™ e MSCREATIVE.SYSTEMS™ são marcas do método. A leitura é
direcional — localiza a tensão, não promete resultado. Contribuições bem-vindas
— ver CONTRIBUTING.md.
