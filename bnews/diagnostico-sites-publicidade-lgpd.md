# Diagnóstico rápido: publicidade e LGPD nos sites BNews

> Verificação feita em 10/11/2026, por amostragem, nas páginas públicas dos sites. Não substitui uma auditoria completa.

| Site | Status da verificação |
|---|---|
| bnewssaopaulo.com.br | Lido |
| bnewsrn.com.br (o antigo bnewsnatal.com.br redireciona para cá) | Lido |
| bnews.com.br (Bahia) | Página inicial lida; páginas internas bloqueadas por proteção anti-robô |
| bnewsal.com.br (Alagoas) | Fora do ar no momento (erro 502) |
| Instagram (@bnews.sp, @bnews.rn, @bnews_oficial) | Não analisado: o Instagram exige login para mostrar os posts |

---

## Achado 1: links de afiliado sem aviso (seção "Ofertas")

- **O que vi:** SP, RN e Bahia têm a seção **"Ofertas"** no menu, com textos como "Oferta do dia: 52% de desconto na caixa de som...". No texto de SP que abri, o link do produto leva à Amazon com o código de afiliado `tag=bnews_sp-20`. Ou seja, **o BNews ganha comissão em cada venda.**
- **O problema:** a matéria é assinada por "Redação" e **em nenhum lugar diz que o BNews ganha comissão.** Para o leitor, parece notícia.
- **Risco:**
  - **CDC (art. 36) e CONAR:** publicidade precisa ser identificada.
  - **Contrato de afiliados da Amazon:** o programa exige um aviso de que o site ganha comissão. Sem esse aviso, a conta pode ser encerrada, e **a receita acaba.**
- **Correção (custo zero):** colocar no topo de cada oferta: *"O BNews pode receber comissão por compras feitas pelos links desta página."*

## Achado 2: conteúdo de empresas sem rótulo (seção "Negócios")

- **O que vi:** no BNews RN, matérias como "Unimed Natal promove evento inédito..." e "Honda domina mercado de motocicletas no RN..." usam foto de divulgação ou da assessoria e não têm nenhum rótulo.
- **O que não dá para saber de fora:** se foram pagas.
- **Pergunta interna:** se foram pagas, precisam do aviso "Conteúdo patrocinado". Se vieram de press release gratuito, tudo bem, mas é bom ter uma regra escrita para separar os dois casos.

## Achado 3: não existe seção de publieditorial

- Nos três sites não encontrei nenhuma seção ou rótulo de "Publieditorial", "Patrocinado" ou "Informe publicitário".
- Há duas leituras:
  - **(a)** o BNews não vende esse produto, o que é uma **oportunidade de receita**;
  - **(b)** vende, mas sem rótulo, o que é um **risco**.
- Vale descobrir qual das duas é a verdadeira.

## Achado 4: aviso de cookies em desacordo com o que o site faz

- **O que o aviso diz:** *"Utilizamos cookies essenciais e tecnologias semelhantes..."*, com **um único botão: "OK"**, sem opção de recusar.
- **O que o site carrega de fato:**
  - anúncios do Google (DoubleClick / Google Ad Manager);
  - **Taboola**;
  - notificações **OneSignal**;
  - em SP e RN, o **pixel do TikTok**.
- Esses rastreadores são de publicidade, não são essenciais. A própria política de privacidade de SP lista cookies de publicidade e marketing, diz que a base legal é o consentimento e admite o compartilhamento com agências.
- **Risco:** pela LGPD, cookie de publicidade depende de consentimento real, e "OK" sem opção de recusa não é consentimento válido. O guia de cookies da ANPD segue nessa linha.
- **Correção:** um banner com as opções "Aceitar", "Recusar" e "Configurar", em que os rastreadores de anúncio só carregam depois do aceite. Existem ferramentas prontas e baratas para isso.

## Achado 5: política de privacidade de SP com erros visíveis

1. **Link de contato quebrado:** está escrito `https://www.BNEWS SÃO PAULO.com.br/contato/`. É resultado de um "localizar e substituir" malfeito em um modelo copiado. **O leitor não tem como exercer os direitos dele pela LGPD.**
2. **Empresa titular identificada como "ALVES QUATRO ASSESSORIA DE COMUNICAÇÃO EIRELI"**, com sede em Salvador. A EIRELI deixou de existir (Lei 14.195/2021). Os dados cadastrais devem estar desatualizados.
3. **Não localizei o nome ou o contato do encarregado (DPO)** nem um canal específico para o titular dos dados.
4. A política da Bahia não pôde ser lida (bloqueio anti-robô).

## Achado 6, estratégico: a assessoria é a dona do jornal

- A política de SP informa que o BNews SP é de titularidade de uma **assessoria de comunicação**.
- Isso torna concreto o ponto do conflito de interesses: **se a assessoria atende clientes que viram notícia no BNews, sem regra de separação e de transparência, a credibilidade do veículo fica exposta.**
- Não é uma acusação. É o primeiro tema que uma política de compliance precisa cobrir.

---

## Prioridades sugeridas

| Prioridade | Ação | Custo | Ganho |
|---|---|---|---|
| 1 | Aviso de comissão nas "Ofertas" | Zero | Protege a receita de afiliados |
| 2 | Corrigir o link de contato e os dados da empresa na política | Zero | Tira um erro visível e o risco de LGPD |
| 3 | Banner de cookies com opção de recusar | Baixo | Adequação à LGPD/ANPD |
| 4 | Regra escrita "pago × press release × notícia" | Zero | Protege a credibilidade |
| 5 | Criar o produto "Publieditorial BNews" com contrato-padrão | Baixo | **Receita nova** |
