# ê°Å¸Â¦Â¾ GrokBot 7 Agentes

<div align="center">
  <img src="capa/logo.svg" alt="Arckhé AI" height="48" />
  <p><strong>Arckhé AI</strong></p>
</div>


**ê°Å¸â¡Â§ê°Å¸â¡Â· [PortuguêÂªs](README.md) êÂ· ê°Å¸â¡Âºê°Å¸â¡Â¸ [English](README.en.md) êÂ· ê°Å¸â¡Âªê°Å¸â¡Â¸ [EspaêÂ±ol](README.es.md)**

[![GrokBot 7 Agentes](guia/assets/banner.jpg)](https://linnoff88-dev.github.io/

## O que êÂ©

êâ° um kit com sete agentes prontos para quem usa o GrokBot, o assistente de agentes da xAI. Cada agente vem numa ficha: um texto para colar no GrokBot, o que ele pode e nêÂ£o pode fazer sozinho, trêÂªs testes para fazer antes de confiar e uma rotina curta de acompanhamento. Juntos, eles vigiam seu e-mail, checam contratos, cuidam das redes, pedem orêÂ§amentos, olham suas finanêÂ§as, guardam a memêÂ³ria da equipe e coordenam tudo. Para usar, basta ter o GrokBot e conectar os aplicativos que cada ficha indica.

## ê°Å¸ââ Guia de uso

Guia completo (landing + passo a passo + instruêÂ§êÂµes para copiar): **https://linnoff88-dev.github.io/

## Os 7 agentes

| # | Agente | O que faz | NêÂ­vel | Quando roda |
|---|---|---|---|---|
| 1 | [ê°Å¸âºÂ¡ê¯Â¸Â Escudo](agentes/01-escudo.md) | Resgata e-mail bom do spam, sinaliza golpe, acha seu telefone em sites de busca de pessoas | N2 êÂ· prepara, vocêÂª aprova | todo dia 7h |
| 2 | [ê°Å¸âÂ Checagem](agentes/02-checagem.md) | Checa pessoa/empresa em 4 lugares e lêÂª as letras miêÂºdas antes de vocêÂª assinar | N1 êÂ· pesquisa e prepara | todo dia + sob pedido |
| 3 | [ê°Å¸âÂ± Redes](agentes/03-redes.md) | TendêÂªncias no X, posts na sua voz, DM automêÂ¡tica por palavra-chave | N2 êÂ· prepara, vocêÂª aprova | toda manhêÂ£ + sob pedido |
| 4 | [ê°Å¸âÂ¸ Negociador](agentes/04-negociador.md) | Pede 3+ orêÂ§amentos por e-mail prêÂ³prio, compara e pechincha | N2 êÂ· prepara, vocêÂª aprova | sob pedido |
| 5 | [ê°Å¸âÅ  Financeiro](agentes/05-financeiro.md) | Acha assinatura duplicada, gasto êÂ  toa, dinheiro esquecido e o custo de cada bot | N0 êÂ· sêÂ³ olha | todo dia, painel na segunda |
| 6 | [ê°Å¸Â§Â  CêÂ©rebro](agentes/06-cerebro.md) | MemêÂ³ria compartilhada da equipe num banco de dados; os outros sêÂ³ acrescentam relatêÂ³rios, ele organiza | N3 êÂ· executa | sob pedido |
| 7 | [ê°Å¸Â¤Â Chefe de Gabinete](agentes/07-chefe-de-gabinete.md) | Coordena os outros e te entrega o resumo das 8h | N3 êÂ· executa | todo dia 8h |

Cada ficha segue o formato **Ficha do Agente** do ARCKHê ([7 princêÂ­pios](https://linnoff88-dev.github.io/ missêÂ£o, contexto, dados, critêÂ©rio de sucesso, autonomia, observaêÂ§êÂ£o e supervisêÂ£o, mais a **instruêÂ§êÂ£o pronta** para colar, **3 testes** e o **checklist de supervisêÂ£o**.

## O processo, do inêÂ­cio ao fim

Quem faz: ê°Å¸Â§â vocêÂª êÂ· ê¢Å¡â¢ê¯Â¸Â o GrokBot sozinho, no horêÂ¡rio êÂ· ê°Å¸Â¤â o agente, quando vocêÂª pede.

1. ê°Å¸Â§â **Escolha o trabalho que mais toma a sua semana** (e-mail, contratos, redes, orêÂ§amentos ou gastos) e abra a ficha dele em `agentes/`.
2. ê°Å¸Â§â **Copie a "InstruêÂ§êÂ£o pronta"** da ficha (ou pelo botêÂ£o copiar no [guia](https://linnoff88-dev.github.io/
3. ê°Å¸Â§â **Cole numa conversa nova no GrokBot** e troque o que estêÂ¡ entre `[colchetes]` pelos seus dados. O GrokBot confirma em 3 linhas o que entendeu.
4. ê°Å¸Â§â **Conecte os aplicativos** que a ficha pede (`"Quero conectar ao [serviêÂ§o]. O que vocêÂª precisa?"`). Chave de API vai no campo seguro do GrokBot.
5. ê°Å¸Â§â **Rode os 3 testes** da ficha (informaêÂ§êÂ£o faltando, pedido proibido, alarme). Errou? Ajuste a regra e teste de novo.
6. ê¢Å¡â¢ê¯Â¸Â **O agente roda no horêÂ¡rio** da ficha (Escudo 7h, Chefe 8h, Financeiro com painel na segunda) e ê°Å¸Â¤â sob pedido.
7. ê°Å¸Â§â **2 minutos por dia:** leia o relatêÂ³rio e aprove o que espera seu OK. **10 minutos por semana:** ajuste uma regra sêÂ³ (na conversa do bot: *"Mude uma regra: ..."*) e anote o que quebrou numa planilha sua, copiando a tabela "Registro de falhas" da ficha.
8. ê°Å¸Â§â **Repita do passo 1** com o prêÂ³ximo agente, uma semana depois.
9. ê°Å¸Â§â **Com 2+ agentes rodando, monte o CêÂ©rebro** (um banco de dados que vira a memêÂ³ria comum) e **conecte o mesmo banco em cada bot**: as instruêÂ§êÂµes jêÂ¡ mandam cada um guardar ali o prêÂ³prio relatêÂ³rio. Depois monte **o Chefe de Gabinete**, que lêÂª esses relatêÂ³rios e te resume êÂ s 8h.
10. ê°Å¸Â§â **Todo mêÂªs:** confira se o nêÂ­vel de cada agente ainda êÂ© o certo; suba sêÂ³ quando a ficha disser que pode.

## Regra dos 3 motivos

Crie um bot separado sêÂ³ se ele precisar de **memêÂ³ria prêÂ³pria**, **permissêÂ£o diferente** ou **relêÂ³gio prêÂ³prio**. SenêÂ£o, peêÂ§a direto ao Chefe de Gabinete. Seis bots sêÂ£o seis conversas para acompanhar.

## Avisos

- As fichas sêÂ£o um kit do ARCKHê.
- NêÂ£o foram testadas por nêÂ³s em todas as contas e planos do GrokBot: **rode os 3 testes no seu antes de confiar**.
- Ferramentas citadas nas fichas (agendador de posts, carteira, banco de dados) sêÂ£o exemplos, nêÂ£o exigêÂªncia. Nenhuma tem vêÂ­nculo com o ARCKHê.
- Tudo que mexe com dinheiro ou fala com gente de fora comeêÂ§a no nêÂ­vel N2: **nada sai sem o seu OK**.

## Para quem mantêÂ©m o kit

As instruêÂ§êÂµes da pêÂ¡gina saem das fichas. Editou uma ficha (PT em `agentes/`, EN em `agentes/en/`, ES em `agentes/es/`) ou a pêÂ¡gina (`guia/_src/<idioma>.html`)? Rode:

```bash
python3 guia/build.py   # gera guia/index.html, guia/en/ e guia/es/
```

---

Kit aberto e gratuito êÂ· [ARCKHê AI](https://ARCKHê AI)

---

<div align="center">
  <img src="capa/logo.svg" alt="Arckhé AI" height="32" />
  <p><strong>Arckhé AI</strong></p>
</div>