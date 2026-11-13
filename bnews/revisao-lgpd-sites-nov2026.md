# Revisão LGPD dos sites BNews

**Data da verificação:** 13/11/2026 · **Sites:** BNews SP, BNews RN e BNews BA (página inicial). O BNews AL estava fora do ar. As páginas internas do BNews BA bloqueiam acesso automatizado e não puderam ser lidas.
**Escopo:** o que um visitante vê e o que o site carrega. Não inclui sistemas internos (CRM, RH, assessoria).

> **Correções em relação à revisão anterior (10/11):**
> (1) os sites **têm** formulário "Fale Conosco". O problema é que a política de privacidade aponta para um endereço `/contato/` que não existe;
> (2) as menções ao TikTok são **links para o perfil** do BNews, **não** um pixel de rastreamento.

---

## Quadro-resumo

| # | O que adequar | Onde | Prioridade |
|---|---|---|---|
| 1 | Aviso de cookies com "consentimento por continuar navegando" | SP, RN, BA | 🔴 Alta |
| 2 | Rastreadores de publicidade carregados sem consentimento | SP, RN, BA | 🔴 Alta |
| 3 | Encarregado (DPO) não identificado | SP, RN, BA | 🔴 Alta |
| 4 | Política de SP com link de contato quebrado e empresa como "EIRELI" | SP | 🔴 Alta |
| 5 | Grupo de WhatsApp expõe o telefone dos leitores | RN | 🔴 Alta |
| 6 | Formulário "Fale Conosco" sem informação sobre o uso dos dados | SP, RN | 🟡 Média |
| 7 | Política não trata da transferência de dados ao exterior | SP, RN | 🟡 Média |
| 8 | Duas políticas diferentes no ar no RN; dados da empresa divergentes entre os sites | RN, SP | 🟡 Média |
| 9 | Políticas em PDF, sem data de atualização | SP, RN | 🟡 Média |
| 10 | Termos de uso "alteráveis sem qualquer aviso prévio" | RN | 🟡 Média |
| 11 | Newsletter e notificações sem verificação do cadastro | BA | 🟡 A verificar |
| 12 | Ofertas com link de afiliado sem aviso de comissão (CDC/CONAR, não LGPD) | SP, RN | 🔴 Alta |

---

## Detalhamento

### 1. Aviso de cookies com consentimento tácito 🔴
- **O que está lá:** *"Utilizamos cookies essenciais e tecnologias semelhantes [...] e, **ao continuar navegando, você concorda** com essas condições."* Há um único botão, de aceite.
- **Por que adequar:** a LGPD define consentimento como manifestação **livre, informada e inequívoca** (art. 5º, XII). "Continuar navegando" não é manifestação inequívoca, e o Guia de Cookies da ANPD rejeita esse modelo e exige a opção de recusar. O texto também diz "essenciais", mas o site usa cookies de publicidade e de medição (item 2), o que torna a informação **inexata** (art. 6º, VI, transparência).
- **O que fazer:** banner com **Aceitar · Recusar · Personalizar**, com o mesmo destaque para aceitar e recusar, e o link "Preferências de cookies" no rodapé.

### 2. Rastreadores carregados sem consentimento 🔴
- **O que está lá:** Google Ad Manager (DoubleClick), Google Analytics e comScore nos três sites. Taboola e OneSignal (notificações) no BA. Taboola também aparece em SP e RN. Não há nenhuma ferramenta de gestão de consentimento nem o "Modo de Consentimento" do Google.
- **Por que adequar:** cookies de publicidade e de medição de terceiros dependem de **consentimento prévio** (LGPD, art. 7º, I, e Guia de Cookies da ANPD). Hoje eles carregam **antes** de qualquer escolha do leitor.
- **O que fazer:** usar uma ferramenta de consentimento (CMP) que só carregue anúncios e métricas depois do aceite, e ativar o Modo de Consentimento do Google para preservar parte da receita de anúncios.

### 3. Encarregado (DPO) não identificado 🔴
- **O que está lá:** nenhum dos sites nem das políticas informa o nome ou o contato do encarregado.
- **Por que adequar:** a identidade e o contato do encarregado devem ser divulgados de forma clara, preferencialmente no site (LGPD, art. 41, §1º, e Resolução CD/ANPD nº 18/2024). A dispensa para agentes de pequeno porte (Resolução CD/ANPD nº 2/2022) é discutível aqui, pelo uso intenso de rastreamento para publicidade, e mesmo com a dispensa é obrigatório manter um **canal de comunicação** com o titular.
- **O que fazer:** nomear formalmente o encarregado e publicar o nome e o e-mail (por exemplo, privacidade@...) na política e no rodapé.

### 4. Política de SP com erros 🔴
- **O que está lá:** o contato para exercer direitos aparece como `https://www.BNEWS SÃO PAULO.com.br/contato/` (endereço inválido, e o `/contato/` real dá erro 404). A titular aparece como **"EIRELI"**, enquanto as políticas do RN, do mesmo grupo, dizem **"LTDA"**.
- **Por que adequar:** o titular precisa de um meio efetivo para exercer seus direitos (art. 18) e de informação correta sobre o controlador (art. 9º, III). A EIRELI foi extinta pela Lei 14.195/2021.
- **O que fazer:** apontar para o formulário "Fale Conosco" existente ou para o e-mail do encarregado, e corrigir a razão social conforme o cartão CNPJ.

### 5. Grupo de WhatsApp (RN) 🔴
- **O que está lá:** convite para um **grupo** (`chat.whatsapp.com/...`).
- **Por que adequar:** num grupo, todos os participantes veem o número de todos. O BNews acaba **compartilhando dados pessoais com terceiros** sem base legal e sem medidas de segurança (arts. 6º, VII, e 46).
- **O que fazer:** migrar para um **Canal do WhatsApp**, em que os números ficam ocultos, ou deixar o grupo só com administradores enviando mensagens e informar as regras na entrada.

### 6. Formulário "Fale Conosco" 🟡
- **O que está lá:** coleta e-mail, assunto, telefone, cidade e mensagem, com reCAPTCHA do Google. Não há aviso sobre o uso dos dados nem link para a política.
- **Por que adequar:** o titular deve ser informado, no momento da coleta, sobre a finalidade e o uso dos dados (art. 9º). O reCAPTCHA envia dados ao Google.
- **O que fazer:** incluir abaixo do botão: *"Seus dados serão usados apenas para responder a esta mensagem. Saiba mais na Política de Privacidade."* Avaliar se o telefone e a cidade são necessários (princípio da necessidade, art. 6º, III).

### 7. Transferência internacional 🟡
- **O que está lá:** as políticas não mencionam que os dados vão para fornecedores no exterior (Google, Taboola, comScore, OneSignal).
- **Por que adequar:** a transferência internacional exige um mecanismo válido, como as cláusulas-padrão (LGPD, arts. 33 a 36, e Resolução CD/ANPD nº 19/2024), e deve ser informada ao titular.
- **O que fazer:** verificar se os contratos ou termos desses fornecedores trazem as cláusulas-padrão e incluir na política: quais fornecedores, quais países e com qual base.

### 8. Políticas duplicadas e dados divergentes 🟡
- **O que está lá:** o RN tem **duas políticas no ar** ("BNews Natal" e "BNews RN"), quase idênticas. SP usa "EIRELI" e RN usa "LTDA".
- **Por que adequar:** o leitor não sabe qual documento vale (transparência, art. 6º, VI).
- **O que fazer:** uma **Política única do Grupo BNews**, válida para todos os portais.

### 9. Formato e data 🟡
- **O que está lá:** políticas em PDF, sem data de atualização. O PDF de SP tem caracteres corrompidos.
- **Por que adequar:** a informação deve ser clara e acessível (arts. 6º, VI, e 9º).
- **O que fazer:** publicar como página do site, com *"Última atualização: [data]"*.

### 10. Termos de uso do RN 🟡
- **O que está lá:** *"Estes Termos podem ser alterados a qualquer momento sem qualquer aviso prévio."*
- **Por que adequar:** mudanças sem aviso prejudicam a transparência (LGPD, art. 9º, §2º, que exige informar as mudanças de finalidade) e tendem a ser vistas como abusivas pelo CDC.
- **O que fazer:** *"Os Termos podem ser atualizados. A data da última versão ficará no topo e mudanças relevantes serão informadas no site."*

### 11. Newsletter (BA) e notificações 🟡 A verificar
- **O que está lá:** cadastro de newsletter "Beta" em domínio externo (`newsletterbnews.com.br`) e notificações por navegador (OneSignal) no BA.
- **Por que verificar:** é preciso informar a finalidade na coleta (art. 9º), ter um descadastro fácil (art. 18, IX, revogação do consentimento) e um contrato com o fornecedor (art. 39).
- **O que fazer:** conferir o formulário, o link "Descadastrar" em cada e-mail e o contrato com a plataforma.

### 12. Ofertas com link de afiliado 🔴 (publicidade, não LGPD)
- **O que está lá:** as ofertas trazem link da Amazon com o código de afiliado do BNews (`tag=bnews_sp-20`) e **não informam a comissão**.
- **Por que adequar:** a publicidade deve ser identificada como tal (CDC, art. 36, e CONAR), e o programa de afiliados da Amazon exige esse aviso, sob pena de encerramento da conta.
- **O que fazer:** selo "Link de afiliado" + aviso de comissão no topo de cada oferta.

---

## Ordem de execução sugerida
| Prazo | Itens | Quem |
|---|---|---|
| **Semana 1** | 4, 5, 12 (custo zero) | Jurídico + Redação |
| **Semanas 2–3** | 3, 6, 8, 9, 10 (nova Política única + encarregado) | Jurídico |
| **Semanas 2–4** | 1, 2 (ferramenta de consentimento) | Tecnologia + Jurídico |
| **Mês 2** | 7, 11 (fornecedores e newsletter) | Jurídico + Tecnologia |
