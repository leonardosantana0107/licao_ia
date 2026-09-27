# Atividade: Site de Festival com IA

> 🎯 **Objetivo:** em duplas ou trios, construir um site completo de **5 páginas** para um festival de música inventado por vocês, usando **Inteligência Artificial do começo ao fim**. Aqui a IA é permitida e incentivada. O importante não é só o site pronto, mas **como vocês conduziram a IA** até chegar num design com personalidade, e se vocês **entendem o código** que ela escreveu.
> 

🎪 O tema: Festival de Música

Toda a turma tem o mesmo tema, mas **cada dupla inventa o seu próprio festival**. Vocês decidem:

- O **nome** do festival
- O **estilo musical** (rock, sertanejo, gospel, eletrônica, K-pop, jazz, trap, música clássica, o que quiserem)
- A **cidade** e o **local** onde acontece
- As **datas** (2 ou 3 dias)
- Os **artistas** (podem ser reais ou inventados)

Um festival de jazz num casarão antigo não pode ter a mesma cara de um festival de trap num galpão industrial. É justamente isso que vai diferenciar o site de vocês do site das outras duplas.

⚠️ Regras obrigatórias

- O site precisa ter as **5 páginas** descritas na Parte 4, todas acessíveis pelo menu
- O site precisa estar **publicado e funcionando na Vercel** no dia da entrega
- O arquivo `README.md` precisa estar completo (modelo na Parte 7)

---

## Meu site de exemplo:

Claude Artifact

## Parte 1: Preparando o projeto

> A dupla trabalha no **mesmo computador**. Combinem de revezar: enquanto um conversa com a IA, o outro cola o código no VS Code e testa no navegador. Troquem de função de vez em quando.
> 
- [ ]  Crie uma pasta em Documentos com o nome `festival-` seguido do nome do festival de vocês (exemplo: `festival-noite-do-jazz`)
- [ ]  Abra essa pasta no VS Code (menu **Arquivo → Abrir Pasta**)
- [ ]  Dentro da pasta, crie estes arquivos **vazios**: `index.html`, `lineup.html`, `ingressos.html`, `informacoes.html`, `faq.html`, `style.css` e `README.md`
- [ ]  Crie também uma pasta chamada `img` (todas as imagens do site vão ficar aqui)
- [ ]  Abra o site da IA que vocês vão usar no navegador (ChatGPT, Claude ou Gemini)

## Parte 2: Como trabalhar com a IA no navegador

> A IA fica numa aba do navegador e o código fica no VS Code. O caminho do código é sempre: **IA → copiar → colar no arquivo certo → salvar → testar no navegador**.
> 
- [ ]  **Sempre diga o nome do arquivo** no pedido. Exemplo: "escreva o arquivo `lineup.html` completo"
- [ ]  **Peça o arquivo inteiro**, não pedaços. Assim vocês apagam tudo o que estava no arquivo e colam o novo, sem risco de colar no lugar errado
- [ ]  **Um arquivo por vez.** Se uma mudança mexe no HTML e no CSS, peça primeiro um e depois o outro
- [ ]  Depois de colar, **salve** (**Ctrl + S**) e **atualize** o navegador para ver o resultado
- [ ]  Deu erro ou ficou estranho? Tire um **print** da tela e mande para a IA junto com a explicação do problema
- [ ]  O `header`, o menu e o `footer` são iguais nas 5 páginas. Peçam para a IA escrever **uma vez**, testem na `index.html` e depois copiem para as outras páginas
- [ ]  Se a conversa ficar muito comprida e a IA começar a se confundir, abram **uma conversa nova** e colem nela o **briefing** e o conteúdo atual do `style.css` antes do novo pedido

## Parte 3: O briefing (antes de pedir qualquer código)

> Briefing é o documento que diz **como o site deve ser** antes de ele existir. Designers profissionais sempre começam por aqui. Usem a IA para ajudar a pensar, mas quem decide são vocês. Escrevam tudo no `README.md`.
> 
- [ ]  **README.md:** escreva quem é o **público** do festival (idade, gostos, o que essas pessoas esperam)
- [ ]  **README.md:** escreva o **clima** do festival em 3 palavras (exemplo: "elegante, noturno, intimista" ou "barulhento, colorido, caótico")
- [ ]  **README.md:** defina a **paleta de cores**: no mínimo 4 cores, com o código hexadecimal de cada uma e onde ela será usada
- [ ]  **README.md:** defina **2 fontes** do Google Fonts: uma para títulos e uma para textos, e explique em uma frase por que escolheram
- [ ]  **README.md:** coloque os links de **3 sites reais** que serviram de inspiração visual e diga o que vocês gostaram em cada um

## Parte 4: As 5 páginas obrigatórias

> Cada página precisa ter um **propósito próprio**. Não vale fazer 5 páginas iguais com títulos diferentes.
> 
- [ ]  **index.html (Início):** nome do festival, datas, local, uma frase de chamada e o destaque de 3 atrações principais
- [ ]  **lineup.html (Line-up):** no mínimo **8 artistas**, cada um com nome, imagem, dia, horário e palco
- [ ]  **ingressos.html (Ingressos):** no mínimo **3 tipos** de ingresso, cada um com preço e o que está incluído
- [ ]  **informacoes.html (Informações):** endereço, como chegar, um mapa (imagem ou mapa incorporado) e as regras do festival (o que pode e o que não pode levar)
- [ ]  **faq.html (Dúvidas e contato):** no mínimo **6 perguntas** com resposta e um formulário de contato (só visual, não precisa enviar de verdade)

## Parte 5: Estrutura que toda página precisa ter

- [ ]  O mesmo **header** em todas as páginas, com o nome ou logo do festival e o menu
- [ ]  O **menu** com link para as 5 páginas, **funcionando** em todas elas (cliquem em todos os links de todas as páginas para testar)
- [ ]  O mesmo **footer** em todas as páginas, com o nome do festival, o ano e os nomes da dupla
- [ ]  Um **único** arquivo `style.css` ligado em todas as páginas
- [ ]  Todas as imagens dentro da pasta `img`

## Parte 6: Refinando o design com a IA

> A primeira versão que a IA entrega quase sempre tem "cara de IA": parece com todos os outros sites. O trabalho de vocês é **conversar com a IA** até o site ficar com a cara do briefing.
> 
- [ ]  Peçam para a IA gerar a **primeira versão** da página inicial, colem no VS Code e abram no navegador
- [ ]  Tirem um **print** dessa primeira versão antes de mudar qualquer coisa e salvem como `img/antes.png`
- [ ]  Vão refinando com novos prompts. Em vez de "deixa mais bonito", digam **exatamente** o que querem mudar (vejam as dicas abaixo)
- [ ]  Quando a página inicial estiver pronta, tirem outro print e salvem como `img/depois.png`
- [ ]  **README.md:** copiem os **4 prompts** que mais fizeram diferença no resultado
- 💡 Dicas para escrever prompts melhores
    
    **Prompt fraco:**
    
    > Faz um site de festival bonito.
    > 
    
    **Prompt forte:**
    
    > Estou fazendo o site de um festival de jazz chamado Noite do Jazz, para um público adulto que gosta de ambientes elegantes. Use estas cores: fundo #1B1A17, dourado #C9A45C, creme #EFE6D2 e vinho #6B1F2A. A fonte dos títulos é Playfair Display e a dos textos é Lato. Escreva o arquivo index.html completo, com o header tendo o nome do festival à esquerda e o menu à direita, usando display flex. O CSS vai ficar no arquivo style.css. Não use gradientes nem emojis.
    > 
    
    **Mais truques:**
    
    - Sempre colem o **briefing** no começo da conversa, para a IA saber o contexto
    - Peçam **uma mudança por vez** ("aumente o espaço entre os artistas do line-up" funciona melhor do que 10 pedidos juntos)
    - Mandem um **print** do site para a IA e digam o que está incomodando
    - Peçam para a IA **explicar** o código que ela escreveu ("explique linha por linha o CSS do header")
- 🚫 Lista "cara de IA" (evitem tudo isto)
    - Fundo com gradiente roxo e azul ou roxo e rosa
    - Emojis usados no lugar de ícones ou imagens
    - Todas as seções feitas com cards iguais, cantos arredondados e sombra
    - Textos genéricos como "Bem-vindo ao nosso site" ou "Lorem ipsum"
    - Imagens de placeholder (quadrados cinza com o tamanho escrito)
    - Cores ou fontes diferentes das que foram definidas no briefing

## Parte 7: O README completo

- [ ]  Confiram se o `README.md` segue esta estrutura:

```markdown
# Nome do Festival

**Dupla:** Nome 1 e Nome 2
**Site publicado:** link da Vercel

## Briefing
Público, clima em 3 palavras, paleta, fontes e sites de inspiração.

## Antes e depois
!Antes
!Depois

## Os 4 prompts que mais fizeram diferença
1. ...
2. ...
3. ...
4. ...
```

## Parte 8: Entendendo o código de vocês

> A IA escreveu o código, mas o site é de vocês. Na aula de entrega, o professor vai escolher algumas duplas e pedir uma alteração simples no próprio site (exemplo: "coloque esses artistas em coluna", "aumente o espaço interno desse botão"), para ser feita **sem IA**.
> 
- [ ]  Peçam para a IA explicar o CSS de cada página e leiam com atenção
- [ ]  Os **dois** integrantes precisam saber onde fica cada parte do código
- [ ]  Treinem juntos: um pede uma alteração, o outro faz sem IA

## Parte 9: Publicando e entregando

- [ ]  Subam a pasta do projeto para o GitHub pelo GitHub Desktop, na conta de um dos integrantes (passo a passo no toggle **Conexão com o GitHub Desktop**, na página da turma)
- [ ]  Publiquem o repositório na **Vercel** (passo a passo no toggle **Adicionar projetos a Vercel**, na página da turma)
- [ ]  Abram o site publicado e cliquem em **todos os links de todas as páginas**
- [ ]  Colem o link da Vercel no `README.md` e subam essa alteração
- [ ]  Entreguem na plataforma o **link do site na Vercel**

---

- 🚀 Desafios extras (para quem terminar antes)
    - [ ]  Deixem o site funcionando bem no celular
    - [ ]  Criem uma sexta página com a **programação completa** por dia e horário
    - [ ]  Destaquem no menu a página em que o usuário está (exemplo: o link da página atual com outra cor)
    - [ ]  Criem um logo para o festival e usem também como ícone da aba do navegador (favicon)