# ðŸ¦¾ GrokBot 7 Agentes

<div align="center">
  <img src="capa/logo.svg" alt="Arckhé AI" height="48" />
  <p><strong>Arckhé AI</strong></p>
</div>


**ðŸ‡§ðŸ‡· [PortuguÃªs](README.md) Â· ðŸ‡ºðŸ‡¸ [English](README.en.md) Â· ðŸ‡ªðŸ‡¸ [EspaÃ±ol](README.es.md)**

[![GrokBot 7 Agentes](guia/assets/banner.jpg)](https://inematds.github.io/grokbot-7-agentes/guia/)

## O que Ã©

Ã‰ um kit com sete agentes prontos para quem usa o GrokBot, o assistente de agentes da xAI. Cada agente vem numa ficha: um texto para colar no GrokBot, o que ele pode e nÃ£o pode fazer sozinho, trÃªs testes para fazer antes de confiar e uma rotina curta de acompanhamento. Juntos, eles vigiam seu e-mail, checam contratos, cuidam das redes, pedem orÃ§amentos, olham suas finanÃ§as, guardam a memÃ³ria da equipe e coordenam tudo. Para usar, basta ter o GrokBot e conectar os aplicativos que cada ficha indica.

## ðŸ“– Guia de uso

Guia completo (landing + passo a passo + instruÃ§Ãµes para copiar): **https://inematds.github.io/grokbot-7-agentes/guia/**

## Os 7 agentes

| # | Agente | O que faz | NÃ­vel | Quando roda |
|---|---|---|---|---|
| 1 | [ðŸ›¡ï¸ Escudo](agentes/01-escudo.md) | Resgata e-mail bom do spam, sinaliza golpe, acha seu telefone em sites de busca de pessoas | N2 Â· prepara, vocÃª aprova | todo dia 7h |
| 2 | [ðŸ” Checagem](agentes/02-checagem.md) | Checa pessoa/empresa em 4 lugares e lÃª as letras miÃºdas antes de vocÃª assinar | N1 Â· pesquisa e prepara | todo dia + sob pedido |
| 3 | [ðŸ“± Redes](agentes/03-redes.md) | TendÃªncias no X, posts na sua voz, DM automÃ¡tica por palavra-chave | N2 Â· prepara, vocÃª aprova | toda manhÃ£ + sob pedido |
| 4 | [ðŸ’¸ Negociador](agentes/04-negociador.md) | Pede 3+ orÃ§amentos por e-mail prÃ³prio, compara e pechincha | N2 Â· prepara, vocÃª aprova | sob pedido |
| 5 | [ðŸ“Š Financeiro](agentes/05-financeiro.md) | Acha assinatura duplicada, gasto Ã  toa, dinheiro esquecido e o custo de cada bot | N0 Â· sÃ³ olha | todo dia, painel na segunda |
| 6 | [ðŸ§  CÃ©rebro](agentes/06-cerebro.md) | MemÃ³ria compartilhada da equipe num banco de dados; os outros sÃ³ acrescentam relatÃ³rios, ele organiza | N3 Â· executa | sob pedido |
| 7 | [ðŸ¤ Chefe de Gabinete](agentes/07-chefe-de-gabinete.md) | Coordena os outros e te entrega o resumo das 8h | N3 Â· executa | todo dia 8h |

Cada ficha segue o formato **Ficha do Agente** do INEMA ([7 princÃ­pios](https://inematds.github.io/7pa/)): missÃ£o, contexto, dados, critÃ©rio de sucesso, autonomia, observaÃ§Ã£o e supervisÃ£o, mais a **instruÃ§Ã£o pronta** para colar, **3 testes** e o **checklist de supervisÃ£o**.

## O processo, do inÃ­cio ao fim

Quem faz: ðŸ§‘ vocÃª Â· âš™ï¸ o GrokBot sozinho, no horÃ¡rio Â· ðŸ¤– o agente, quando vocÃª pede.

1. ðŸ§‘ **Escolha o trabalho que mais toma a sua semana** (e-mail, contratos, redes, orÃ§amentos ou gastos) e abra a ficha dele em `agentes/`.
2. ðŸ§‘ **Copie a "InstruÃ§Ã£o pronta"** da ficha (ou pelo botÃ£o copiar no [guia](https://inematds.github.io/grokbot-7-agentes/guia/#agentes)).
3. ðŸ§‘ **Cole numa conversa nova no GrokBot** e troque o que estÃ¡ entre `[colchetes]` pelos seus dados. O GrokBot confirma em 3 linhas o que entendeu.
4. ðŸ§‘ **Conecte os aplicativos** que a ficha pede (`"Quero conectar ao [serviÃ§o]. O que vocÃª precisa?"`). Chave de API vai no campo seguro do GrokBot.
5. ðŸ§‘ **Rode os 3 testes** da ficha (informaÃ§Ã£o faltando, pedido proibido, alarme). Errou? Ajuste a regra e teste de novo.
6. âš™ï¸ **O agente roda no horÃ¡rio** da ficha (Escudo 7h, Chefe 8h, Financeiro com painel na segunda) e ðŸ¤– sob pedido.
7. ðŸ§‘ **2 minutos por dia:** leia o relatÃ³rio e aprove o que espera seu OK. **10 minutos por semana:** ajuste uma regra sÃ³ (na conversa do bot: *"Mude uma regra: ..."*) e anote o que quebrou numa planilha sua, copiando a tabela "Registro de falhas" da ficha.
8. ðŸ§‘ **Repita do passo 1** com o prÃ³ximo agente, uma semana depois.
9. ðŸ§‘ **Com 2+ agentes rodando, monte o CÃ©rebro** (um banco de dados que vira a memÃ³ria comum) e **conecte o mesmo banco em cada bot**: as instruÃ§Ãµes jÃ¡ mandam cada um guardar ali o prÃ³prio relatÃ³rio. Depois monte **o Chefe de Gabinete**, que lÃª esses relatÃ³rios e te resume Ã s 8h.
10. ðŸ§‘ **Todo mÃªs:** confira se o nÃ­vel de cada agente ainda Ã© o certo; suba sÃ³ quando a ficha disser que pode.

## Regra dos 3 motivos

Crie um bot separado sÃ³ se ele precisar de **memÃ³ria prÃ³pria**, **permissÃ£o diferente** ou **relÃ³gio prÃ³prio**. SenÃ£o, peÃ§a direto ao Chefe de Gabinete. Seis bots sÃ£o seis conversas para acompanhar.

## Avisos

- As fichas sÃ£o um kit do INEMA.
- NÃ£o foram testadas por nÃ³s em todas as contas e planos do GrokBot: **rode os 3 testes no seu antes de confiar**.
- Ferramentas citadas nas fichas (agendador de posts, carteira, banco de dados) sÃ£o exemplos, nÃ£o exigÃªncia. Nenhuma tem vÃ­nculo com o INEMA.
- Tudo que mexe com dinheiro ou fala com gente de fora comeÃ§a no nÃ­vel N2: **nada sai sem o seu OK**.

## Para quem mantÃ©m o kit

As instruÃ§Ãµes da pÃ¡gina saem das fichas. Editou uma ficha (PT em `agentes/`, EN em `agentes/en/`, ES em `agentes/es/`) ou a pÃ¡gina (`guia/_src/<idioma>.html`)? Rode:

```bash
python3 guia/build.py   # gera guia/index.html, guia/en/ e guia/es/
```

---

Kit aberto e gratuito Â· [INEMA.CLUB](https://inema.club)

---

<div align="center">
  <img src="capa/logo.svg" alt="Arckhé AI" height="32" />
  <p><strong>Arckhé AI</strong></p>
</div>