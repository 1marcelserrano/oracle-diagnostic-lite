# oracle-diagnostic-lite

**Onde o seu negócio trava — de verdade. A leitura de superfície do Creative Oracle™.**

Uma skill do Claude que roda 3–5 perguntas curtas sobre o seu negócio e devolve uma leitura honesta de *onde* a tensão se concentra: posicionamento, presença, conversão ou operação. Não prescreve. Localiza. É a porta de entrada gratuita do Creative Oracle™ — o árbitro estratégico que lê um negócio por quatro frentes ao mesmo tempo. Um arquivo markdown. Sem servidor, sem dependência.

[Instalar](#instalar) · [O que ela faz](#o-que-ela-faz--e-o-que-não-faz) · [Quando usar](#quando-usar) · [As quatro frentes](#as-quatro-frentes) · [Exemplo](#exemplo) · [FAQ](#faq) · [Página](https://oracle-diagnostic-lite-page.vercel.app)

---

Pense num médico que olha você por dois minutos no corredor e diz "isso é respiratório, vale investigar". Útil, honesto, e claramente não é a consulta. É exatamente esse o contrato aqui.

O **Creative Oracle™** é o árbitro estratégico do MSCREATIVE.SYSTEMS™ que lê um negócio por quatro frentes ao mesmo tempo e diz onde a coisa está desalinhada. Esta versão lite faz só a primeira parte: aponta o cômodo onde está o incêndio. Apagar o fogo é o trabalho do Diagnóstico Oracle completo.

## O problema

Você sente que algo trava, mas não sabe nomear o quê. Mexe no Instagram quando o nó está na oferta. Refaz a oferta quando o problema é que ninguém entende pra quem você existe. Energia gasta no cômodo errado enquanto o incêndio segue no outro.

Antes de resolver, é preciso localizar. A maioria dos diagnósticos grátis pula essa etapa e já entrega um "plano" genérico — que não cola, porque foi feito sem olhar. Esta skill faz o oposto: escuta primeiro, localiza com honestidade, e só então mostra onde fica a porta do diagnóstico completo.

## O que ela faz — e o que não faz

**Faz:** roda 3–5 perguntas em ritmo de conversa, escuta de verdade, e devolve uma leitura curta de ONDE a tensão se concentra — uma frente só, a que puxa as outras.

**Não faz:** não prescreve, não monta plano, não reescreve posicionamento, não dá o "como". A leitura cruzada das quatro frentes — qual tensão puxa as outras, em que ordem mexer, o que destravar primeiro — é o Diagnóstico Oracle completo.

Esse limite não é mesquinhez. É o que mantém a leitura honesta: ela sinaliza, não resolve. Quem promete resolver de graça em três perguntas está mentindo, e você sente.

## Quando usar

**Use quando:**
- Você sente que algo trava no negócio e quer um norte antes de agir
- Quer um raio-x rápido de onde está o gargalo estratégico
- Quer experimentar como o Creative Oracle™ enxerga, antes do diagnóstico completo

**Não use quando:**
- Você já sabe o problema e quer o plano de ação → isso é o Diagnóstico Oracle completo
- Você quer que ela reescreva posicionamento, oferta ou voz → ela localiza, não executa
- O objetivo é um diagnóstico profundo das quatro frentes cruzadas → é o motor pago

## As quatro frentes

O negócio é lido por quatro frentes. A leitura aponta a que concentra a tensão — uma só.

| Frente | O que ela mede |
|--------|----------------|
| **Quem você é, pra quem** | Clareza de posicionamento e público |
| **Como você soa e aparece** | Voz, estética, presença |
| **Por que compram de você** | Oferta, persuasão, conversão |
| **Como você entrega e sustenta** | Operação, monetização, dependência de você |

Cada pergunta do roteiro abre uma dessas frentes. A última deixa você apontar onde dói mais.

## Exemplo

**O que o usuário trouxe:** "o tráfego chega, mas trava na hora de comprar — e eu mesmo titubeio quando me perguntam pra quem eu existo."

**A leitura que ela devolve:**

> Pelo que você trouxe: o tráfego chega, mas trava na hora de comprar — e você mesmo disse que titubeia na frase de "pra quem eu existo". Isso aponta pra uma só coisa: o nó está em **por que compram de você**. A oferta e a razão de escolher você não estão claras o bastante pra mover quem já apareceu. Onde isso vem de — se é a oferta, o público errado, ou a voz — é o que a leitura completa separa.

Note o que a leitura faz e não faz: nomeia a frente, conecta às palavras do usuário, e para na fronteira do diagnóstico. Não diz como arrumar a oferta. Localizou; desatar é o próximo trabalho.

Método completo em [`skills/oracle-diagnostic-lite/SKILL.md`](./skills/oracle-diagnostic-lite/SKILL.md).

## Instalar

```bash
# Via skills CLI (recomendado)
npx skills add 1marcelserrano/oracle-diagnostic-lite

# Ou manualmente — faça backup antes se a pasta já existir:
# mv ~/.claude/skills/oracle-diagnostic-lite ~/.claude/skills/oracle-diagnostic-lite.backup
git clone https://github.com/1marcelserrano/oracle-diagnostic-lite.git
cp -r oracle-diagnostic-lite/skills/oracle-diagnostic-lite ~/.claude/skills/
```

**Verifique:** abra uma sessão nova do Claude e rode `/skills` (ou pergunte "que skills você tem?"). `oracle-diagnostic-lite` deve aparecer. Se não, confira que `~/.claude/skills/oracle-diagnostic-lite/SKILL.md` existe e reinicie a sessão.

**Sem terminal?** Baixe [`oracle-diagnostic-lite.skill`](./oracle-diagnostic-lite.skill) e suba no Claude (Cowork / claude.ai → Skills).

**Testar sem instalar:** abra [`SKILL.md`](./skills/oracle-diagnostic-lite/SKILL.md), copie o conteúdo inteiro, cole numa conversa nova e em seguida descreva seu negócio.

## FAQ

**É um diagnóstico de verdade?** É a leitura de superfície — localiza a frente onde a tensão se concentra. Honesta sobre o que é: aponta o cômodo do incêndio, não apaga o fogo. O diagnóstico que cruza as quatro frentes e diz a ordem de ataque é o Diagnóstico Oracle completo.

**Funciona pra qualquer negócio?** Sim. As quatro frentes são genéricas o bastante pra ler qualquer marca, serviço ou produto. A leitura calibra pelas suas respostas, não por um nicho fixo.

**Por que não dá logo o plano?** Porque um plano feito sem olhar de verdade é genérico, e genérico não cola. Localizar primeiro é o que torna o passo seguinte preciso. Resolver é outro trabalho — e exige olhar as quatro frentes cruzadas.

**Precisa de API key, conta paga ou servidor?** Não. É um arquivo markdown que o Claude carrega. Roda onde o Claude roda.

**O que é o Creative Oracle™?** O árbitro estratégico do MSCREATIVE.SYSTEMS™ que lê um negócio por quatro frentes ao mesmo tempo. Esta skill é a amostra grátis dele — a primeira leitura.

---

Uma skill do **[MSCREATIVE.SYSTEMS™](https://fronteirista.substack.com)** — a porta de entrada do Creative Oracle™. Licença MIT — use, modifique, redistribua. Mantenha os créditos.
