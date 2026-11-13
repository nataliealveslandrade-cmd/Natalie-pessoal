# Revisão LGPD dos sites BNews: versão simples

**Data:** 13/11/2026 · **Sites verificados:** BNews São Paulo, BNews RN e BNews Bahia.
O site de Alagoas estava fora do ar. Algumas páginas do site da Bahia bloqueiam a leitura automática.

---

## Primeiro, o básico: o que é a LGPD?
A **LGPD** (Lei Geral de Proteção de Dados) diz que, quando uma empresa coleta informações de uma pessoa (nome, e-mail, telefone, o que ela clica no site), precisa:
1. **avisar** o que vai fazer com essas informações;
2. em alguns casos, **pedir permissão** antes;
3. **cuidar** delas para não vazarem;
4. ter **alguém responsável** com quem o leitor possa falar.

> O jornalismo em si (as matérias) tem proteção especial e fica fora dessas regras. Mas a **parte comercial** do site (anúncios, cadastros, formulários, grupos) **precisa seguir a lei**.

---

## Resumo em uma tabela

| # | Problema | Urgência |
|---|---|---|
| 1 | O aviso de cookies diz que o leitor "concorda" só por continuar navegando | 🔴 Alta |
| 2 | Os anúncios começam a "seguir" o leitor antes de ele autorizar | 🔴 Alta |
| 3 | Não existe um responsável pelos dados indicado no site | 🔴 Alta |
| 4 | As políticas de privacidade de SP e RN mandam o leitor para links que não funcionam | 🔴 Alta |
| 5 | O grupo de WhatsApp do RN mostra o telefone dos leitores para todo mundo | 🔴 Alta |
| 6 | As Ofertas não avisam que o BNews ganha comissão | 🔴 Alta |
| 7 | O formulário "Fale Conosco" não explica para que os dados servem | 🟡 Média |
| 8 | A política não conta que os dados vão para empresas de fora do Brasil | 🟡 Média |
| 9 | O RN tem duas políticas de privacidade diferentes no ar | 🟡 Média |
| 10 | As políticas estão em PDF, sem data e com letras faltando | 🟡 Média |
| 11 | Os termos de uso dizem que podem mudar "sem aviso" | 🟡 Média |
| 12 | Newsletter e notificações da Bahia precisam ser conferidas | 🟡 Verificar |

---

## Explicando cada ponto

### 1. O aviso de cookies 🔴
**O que são cookies?** São pequenos arquivos que o site guarda no celular ou no computador do leitor. Alguns fazem o site funcionar; outros servem para **mostrar anúncios** e **contar a audiência**.

**O que o site diz hoje:** *"ao continuar navegando, você concorda"*. Só existe um botão, de aceitar.

**Por que é um problema:** é como dizer "se você entrou na loja, concordou em ser filmado e ter seus dados vendidos". A lei exige que o leitor **possa dizer não**. Ficar no site não é dizer sim.

**Como resolver:** trocar a barrinha por uma com três botões: **Aceitar · Recusar · Personalizar**. Os botões de aceitar e recusar devem ter o mesmo tamanho.

<small>Base: LGPD, art. 5º, XII (consentimento) · Guia de Cookies da ANPD</small>

### 2. Anúncios que "seguem" o leitor antes da autorização 🔴
**O que acontece:** assim que a página abre, já carregam ferramentas do Google (anúncios e métricas), do comScore (audiência) e, na Bahia, do Taboola e do OneSignal (notificações). **O leitor ainda nem clicou em nada.**

**Por que é um problema:** essas ferramentas só podem ser ligadas **depois** que o leitor autorizar. Hoje é como cobrar antes de o cliente aceitar o serviço.

**Como resolver:** contratar uma **ferramenta de consentimento** (existem opções gratuitas ou baratas) que só liga os anúncios depois do "Aceitar". O Google tem um modo próprio para isso que **preserva parte da receita** mesmo quando o leitor recusa.

<small>Base: LGPD, art. 7º, I</small>

### 3. Falta um responsável pelos dados 🔴
**O que é:** a lei pede que a empresa indique uma pessoa (chamada de **encarregado** ou **DPO**) para atender os leitores e a autoridade de proteção de dados (ANPD).

**O que vimos:** não há nome nem e-mail dessa pessoa em nenhum site.

**Por que é um problema:** se um leitor quiser saber o que o BNews tem sobre ele, ou pedir para apagar o cadastro, não sabe com quem falar.

**Como resolver:** nomear o encarregado (pode ser você) e colocar no rodapé do site, por exemplo: *"Privacidade: privacidade@bnews..."*.

<small>Base: LGPD, art. 41 · Resolução ANPD nº 18/2024</small>

### 4. As políticas de privacidade mandam o leitor para links que não funcionam 🔴
**O que vimos:** os sites **têm** uma página "Fale Conosco" que funciona. O problema é que as políticas **não mandam o leitor para lá**, e sim para endereços quebrados:

| Site | Link na política | Funciona? |
|---|---|---|
| SP | `www.BNEWS SÃO PAULO.com.br/contato/` | ❌ Escrito errado, e a página `/contato/` não existe |
| SP e RN | `.../meu_cadastro` | ❌ A página não existe |
| RN | `www.bnewsrnl.com.br/fale-conosco.html` | ❌ Erro de digitação ("rn**l**") |
| RN | `www.bnewsrn.com.br/fale-conosco.html` (aparece em outro trecho) | ✅ Este funciona |

Além disso, a política de SP diz que a empresa é **"EIRELI"**, um tipo de empresa que deixou de existir em 2021. As políticas do RN dizem "LTDA".

**Por que é um problema:** é justamente no trecho em que a política explica **como o leitor pede para ver ou apagar seus dados** que os links estão quebrados. Na prática, o leitor fica sem caminho.

**Como resolver:** trocar todos os links pelo **"Fale Conosco" correto** de cada site (ou pelo e-mail do responsável pelos dados), apagar a menção a "meu_cadastro" e corrigir o nome da empresa conforme o cartão CNPJ.

<small>Base: LGPD, arts. 9º e 18</small>

### 5. O grupo de WhatsApp do RN 🔴
**O que vimos:** o site convida o leitor a entrar num **grupo** de WhatsApp.

**Por que é um problema:** num grupo, **todo mundo vê o número de todo mundo**. Qualquer participante, inclusive golpistas, pode copiar os telefones dos leitores. Quem expôs os números foi o BNews.

**Como resolver:** trocar o grupo por um **Canal do WhatsApp**: só o BNews publica e os números ficam escondidos. Custo zero.

<small>Base: LGPD, arts. 6º e 46 (segurança)</small>

### 6. As Ofertas não avisam da comissão 🔴 (regra de publicidade, não de LGPD)
**O que vimos:** os textos de "Ofertas" levam para a Amazon com um código do BNews. Quando o leitor compra, **o BNews ganha comissão**, mas o texto não avisa.

**Por que é um problema:** o leitor acha que é notícia, mas é publicidade. Além disso, a própria **Amazon exige esse aviso** e pode cancelar o programa, e o BNews **perde essa receita**.

**Como resolver:** escrever no topo de cada oferta: *"Link de afiliado: o BNews pode ganhar comissão se você comprar por aqui."*

<small>Base: Código de Defesa do Consumidor, art. 36 · CONAR</small>

### 7. O formulário "Fale Conosco" 🟡
**O que vimos:** o formulário pede e-mail, telefone, cidade e mensagem, mas **não diz para que** esses dados vão ser usados.

**Como resolver:** colocar uma frase embaixo do botão: *"Usaremos seus dados só para responder sua mensagem. Veja nossa Política de Privacidade."* E pensar se o telefone e a cidade são realmente necessários.

<small>Base: LGPD, art. 9º</small>

### 8. Dados que vão para fora do Brasil 🟡
**O que acontece:** Google, Taboola, comScore e OneSignal são empresas estrangeiras, e os dados dos leitores vão para servidores **fora do país**.

**Por que é um problema:** a lei permite isso, desde que exista um **contrato com garantias** e que o leitor **seja avisado**. A política atual não diz nada sobre isso.

**Como resolver:** conferir os contratos desses fornecedores e incluir na política: *"usamos os serviços de [empresas], que podem armazenar dados fora do Brasil."*

<small>Base: LGPD, arts. 33 a 36 · Resolução ANPD nº 19/2024</small>

### 9. Duas políticas diferentes no RN 🟡
**O que vimos:** o site do RN tem duas políticas no ar ("BNews Natal" e "BNews RN").

**Como resolver:** fazer **uma política só para todo o grupo BNews**, válida para todos os sites.

### 10. Políticas em PDF, sem data 🟡
**O que vimos:** as políticas estão em PDF, sem data de atualização, e o PDF de SP tem letras faltando.

**Como resolver:** publicar a política como uma **página normal do site**, com *"Última atualização: [data]"* no topo.

### 11. Termos de uso que mudam "sem aviso" 🟡
**O que vimos:** os termos do RN dizem que podem ser alterados *"a qualquer momento sem qualquer aviso prévio"*.

**Como resolver:** trocar por *"Os termos podem ser atualizados. A data da última versão fica no topo e mudanças importantes serão avisadas no site."*

### 12. Newsletter e notificações (Bahia) 🟡 Verificar
**O que conferir:**
- [ ] O cadastro da newsletter explica para que o e-mail será usado?
- [ ] Cada e-mail enviado tem o link **"Descadastrar"**?
- [ ] Existe contrato com a plataforma de envio?

---

## Por onde começar

| Quando | O que fazer | Custo |
|---|---|---|
| **Semana 1** | Corrigir os links e o nome da empresa nas políticas (4) · trocar o grupo pelo Canal de WhatsApp (5) · aviso nas Ofertas (6) | Zero |
| **Semanas 2 e 3** | Nomear o responsável pelos dados (3) · fazer uma política única com data, aviso no formulário e termos corrigidos (7, 9, 10, 11) | Zero |
| **Semanas 2 a 4** | Nova barrinha de cookies com "Recusar" e anúncios só depois do aceite (1, 2) | Baixo (equipe de tecnologia) |
| **Mês 2** | Fornecedores de fora do Brasil e newsletter (8, 12) | Zero |
