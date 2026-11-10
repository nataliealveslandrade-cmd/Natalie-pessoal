# Soluções prontas: os 3 pontos do diagnóstico

> Rascunho para revisão interna. Os trechos entre [colchetes] precisam ser preenchidos com dados do BNews.
> Fonte: diagnóstico de 10/11/2026 (`diagnostico-sites-publicidade-lgpd.md`).

---

## PONTO 1: aviso nas "Ofertas" (links de afiliado)

### O problema, em uma frase
O BNews ganha comissão quando o leitor compra pelos links das "Ofertas", e o leitor não é avisado.

### A solução

**a) Selo acima do título de cada oferta**
> **OFERTA · LINK DE AFILIADO**

**b) Aviso logo abaixo do título (texto pronto)**
> *Este conteúdo contém links de afiliado. Se você comprar por eles, o BNews pode receber uma comissão, sem nenhum custo extra para você. As ofertas são escolhidas pela nossa equipe, e preços e estoque podem mudar a qualquer momento.*

**c) Frase no final do texto, exigida pelo programa da Amazon**
> *Como Associado da Amazon, o BNews recebe por compras qualificadas.*

**d) Assinatura:** trocar "Redação" por **"Equipe de Ofertas BNews"**. Isso separa o conteúdo comercial do jornalismo.

**e) Data e preço:** sempre informar *"Preço consultado em [data e hora]"*.

**f) Redes sociais e WhatsApp:** quando uma oferta com link de afiliado for divulgada no Instagram, no WhatsApp ou no Telegram, incluir **#publi** ou **"link de afiliado"** na primeira linha do texto.

### Checklist para a equipe (colar no manual da redação)
- [ ] Tem o selo "Link de afiliado"?
- [ ] Tem o aviso de comissão no topo?
- [ ] Tem a frase da Amazon no final, se o link for da Amazon?
- [ ] A assinatura é "Equipe de Ofertas BNews", e não "Redação"?
- [ ] Tem a data em que o preço foi consultado?
- [ ] Nas redes, tem #publi ou "link de afiliado"?

### Por que isso importa
- **Lei:** o Código de Defesa do Consumidor (art. 36) e o CONAR exigem que o leitor saiba quando algo é publicidade.
- **Dinheiro:** o programa de afiliados da Amazon exige o aviso. Sem ele, a Amazon pode encerrar a conta e reter comissões, e **o BNews perde essa receita.**
- **Custo da solução:** zero.

---

## PONTO 2: aviso de cookies (a barrinha do site)

### O problema, em uma frase
O aviso só tem o botão "OK" e diz que o site usa apenas cookies "essenciais", mas o site usa rastreadores de anúncio (Google, Taboola, TikTok) e o leitor não pode recusar.

### A solução

**a) Novo texto da barrinha (pronto)**
> *Usamos cookies para o site funcionar e, com a sua permissão, para medir a audiência e mostrar anúncios mais relevantes. Você pode aceitar, recusar ou escolher o que permite. Saiba mais na nossa [Política de Privacidade].*
>
> **[ Aceitar todos ]  [ Recusar ]  [ Personalizar ]**

**b) Tela "Personalizar"**

| Categoria | Para que serve | Pode desligar? |
|---|---|---|
| **Necessários** | Fazem o site funcionar (segurança, carregamento da página) | Não: sempre ativos |
| **Estatística** | Contam quantas pessoas leem cada matéria | Sim |
| **Publicidade** | Mostram anúncios conforme o interesse do leitor (Google, Taboola, TikTok) | Sim |

**c) Regras para a equipe de tecnologia**
1. Os rastreadores de **anúncio e estatística só podem ser carregados depois que o leitor clicar em "Aceitar".** Esta é a regra mais importante.
2. O botão **"Recusar" deve ter o mesmo tamanho e o mesmo destaque** do "Aceitar", nada de esconder.
3. Colocar no **rodapé** do site um link **"Preferências de cookies"**, para o leitor mudar de ideia quando quiser.
4. **Guardar o registro** de cada escolha (data, hora e opção escolhida). Serve como prova se a ANPD perguntar.
5. Usar uma ferramenta pronta de gestão de consentimento (CMP). Existem opções gratuitas ou baratas que se integram ao Google, inclusive ao "Modo de Consentimento" do Google, que permite continuar exibindo anúncios mesmo quando o leitor recusa.

### Por que isso importa
- **Lei:** pela LGPD, cookie de publicidade exige consentimento real, e "OK" sem opção de recusa não vale como consentimento. O guia de cookies da ANPD vai na mesma linha.
- **Dinheiro:** feito do jeito certo, com o Modo de Consentimento do Google, o impacto na receita de anúncios é pequeno, e o BNews passa a ter uma base de leitores com consentimento válido, que vale mais para anunciantes.
- **Custo:** baixo (ferramenta gratuita ou mensalidade pequena, mais algumas horas de tecnologia).

---

## PONTO 3: correções na Política de Privacidade

### O problema, em uma frase
O texto do BNews SP foi copiado de um modelo e tem erros: o link de contato está quebrado, o tipo de empresa está desatualizado, não há contato do responsável pelos dados e a parte de cookies não bate com o site.

### Tabela de correções

| # | Como está | Como deve ficar |
|---|---|---|
| 1 | Link de contato `https://www.BNEWS SÃO PAULO.com.br/contato/` (quebrado) | `https://www.bnewssaopaulo.com.br/contato/` (ou um e-mail exclusivo, ver item 3) |
| 2 | "ALVES QUATRO ASSESSORIA DE COMUNICAÇÃO **EIRELI**" | Razão social **atual** conforme o cartão CNPJ (a EIRELI foi extinta pela Lei 14.195/2021; hoje deve ser **SLU** ou outro tipo). **Confirmar no cartão CNPJ.** |
| 3 | Não há contato do responsável pelos dados | Incluir a seção "Encarregado" (texto abaixo) |
| 4 | Cookies: diz que para revogar o consentimento o leitor "deverá apagar os cookies" no navegador | Incluir: *"ou clicar em 'Preferências de cookies', no rodapé do site"* (ligado ao Ponto 2) |
| 5 | Não lista com clareza com quem os dados são compartilhados | Listar os parceiros: Google (anúncios e métricas), Taboola, TikTok, OneSignal (notificações), Amazon (programa de afiliados) |
| 6 | Caracteres estranhos no PDF (letras faltando, como "pu licidad ") | Publicar a política como **página do site (HTML)**, não como PDF |
| 7 | Sem data de atualização visível | Incluir *"Última atualização: [data]"* no topo |

### Textos prontos para incluir

**a) Quem é o responsável (controlador)**
> *O BNews São Paulo é mantido por [RAZÃO SOCIAL ATUALIZADA], inscrita no CNPJ sob o nº [CNPJ], com sede em [ENDEREÇO COMPLETO] ("BNews"), que é a controladora dos dados pessoais tratados nesta Página.*

**b) Encarregado pelo tratamento de dados (DPO)**
> *Para exercer os seus direitos previstos na LGPD (acesso, correção, exclusão, revogação do consentimento, entre outros) ou para tirar dúvidas sobre esta Política, entre em contato com o nosso Encarregado pelo Tratamento de Dados Pessoais:*
> *Nome: [NOME DO ENCARREGADO ou "Comitê de Privacidade BNews"]*
> *E-mail: [privacidade@bnews...]*
> *Responderemos no menor prazo possível, observados os prazos legais.*

**c) Com quem compartilhamos dados**
> *Para exibir anúncios, medir a audiência e enviar notificações, o BNews pode compartilhar dados de navegação, como cookies e identificadores do dispositivo, com parceiros como Google, Taboola, TikTok e OneSignal, sempre conforme as suas escolhas no aviso de cookies. Quando você compra um produto por um link de afiliado, a loja parceira (por exemplo, a Amazon) recebe a informação de que você veio do BNews.*

### Observações para a sua análise
- **Agente de pequeno porte:** a ANPD dispensa algumas empresas pequenas de indicar um encarregado (Resolução CD/ANPD nº 2/2022), mas o canal de contato continua obrigatório. Como o BNews usa muitos rastreadores de publicidade, a dispensa pode não se aplicar. **Recomendação: indicar o encarregado.** Pode ser você.
- **Verificar também as políticas da Bahia, do RN e de Alagoas.** Provavelmente vieram do mesmo modelo e têm os mesmos erros. O ideal é **uma política única do grupo**, com a lista dos sites.

---

## Resumo

| Ponto | O que fazer | Quem faz | Custo | Prazo estimado |
|---|---|---|---|---|
| 1. Ofertas | Selo, aviso de comissão e assinatura nova | Redação | Zero | 1 semana |
| 2. Cookies | Nova barrinha com "Recusar" e bloqueio prévio dos rastreadores | Tecnologia + Jurídico | Baixo | 2 a 4 semanas |
| 3. Privacidade | Corrigir o texto e indicar o encarregado | Jurídico | Zero | 1 a 2 semanas |
