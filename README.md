<p align="center" style="margin-bottom:10px;">
  <a href="https://www.clickqi.com.br/" target="_blank" rel="noopener noreferrer">
    <img width="100" src="https://raw.githubusercontent.com/ClickQi/hello-young-padawan/master/img/Q.png" alt="Click Qi logo">
  </a>
  <h1 align="center" style="color: #24292e;">Click Qi</h1>
</p>

<p align="center" style="margin-bottom:10px;margin-top:10px;">
   <img width="400" src="https://media.makeameme.org/created/hello-young-padawan.jpg" alt="Hello Young Padawan">
</p>

## Agora vc faz parte do nosso time. 🥳

Sabemos que os primeiros dias no trampo novo é meio zuado, mas muita calma, vamos te da umas _call_ maneiras pra te ajudar a começar.
Bora?

Vamos começar pelo mais importante para desenvolvedores...

### Café! ☕️
É grátis e fica lá na cozinha vc pode tomar o quanto quiser ;)

Agora que temos combustivel vamo enfrente. 👉🏻

![much to learn you still have](https://media.giphy.com/media/3ohuAxV0DfcLTxVh6w/giphy.gif)


# Click Qi Tools 🤘
O [Teamwork](https://www.teamwork.com/) é o nosso CRM. Através dele organizamos nosso fluxo de informação e interações com o cliente.<br />
Vc pode acessar por [aqui](http://teamwork.clickqi.com.br/) e pode baixar o _Chat_ por [aqui](https://www.teamwork.com/chat/apps/#for_windows).

<br />

# Devs Things 🖥️

Bora falar um pouco do nosso _workflow_ e das ferramentas que usamos aqui no desenvolvimento ?<br/>
<img width="300" src="https://raw.githubusercontent.com/ClickQi/hello-young-padawan/master/img/jedi-weapon.gif" alt="Click Qi Tools">
<br/>

### Editor de código  👩🏻‍💻
Aqui na Click a maioria dos _Devs_ utilizam o [Visual Studio Code](https://code.visualstudio.com/) ou **VSCode** para os íntimos 🥰, como editor de código, porém não tem nenhuma regra não, pode usar o que vc preferir.

### Ferramenta de UI 🦄
Nossos queridos Designers escolheram o [Figma](https://www.figma.com) como ferramenta de UI para esbanjarem toda sua criatividade, vc pode fazer o download dele clicando [aqui](https://www.figma.com/downloads/)

### Ferramenta de proxy 🌐
Para evitar umas 💩 em produção, nosso ambiente de desenvolvimento é mapeado para o _localhost_ (nada como nossa casa 😆). E para nos auxiliar nessa função, utilizamos um carinha chamado [Charles](https://www.charlesproxy.com/), ele é uma ferramenta de proxy que nos permite interceptar requisições HTTP/HTTPS e mapea-las.

### Ferramenta de versionamento 🔥
Versionamos toda nossa "arte" com [GIT](https://git-scm.com/) e flertamos com o [Git Flow](http://danielkummer.github.io/git-flow-cheatsheet/index.pt_BR.html) e armazenamos nossos projetos no [Bitbucket](https://bitbucket.org/)<br/>
E nunca se esqueça:

<p align="left" style="margin-bottom:10px;margin-top:10px;">
   <img width="200" src="https://raw.githubusercontent.com/milaniromulo/hello-young-padawan/master/img/git-fire.png" alt="Git Fire">
</p>

##### Dicas 💡
* <a href="https://www.hostinger.com.br/tutoriais/tutorial-do-git-basics-introducao/" target="_blank">GIT</a>
* <a href="https://medium.com/trainingcenter/utilizando-o-fluxo-git-flow-e63d5e0d5e04" target="_blank">GIT Flow</a>


## Code 💻
Abaixo um pouco das tecnologias que a gente gosta: 😍

* Todo nosso _workflow_ roda em cima do [Node JS](https://nodejs.org/en/) essa coisa maravilhosa que mudou o mundo Javascript.
* Aquele HTMLzinho filé, bem escrito, semântico e acessivel que aquece o coração.
* No CSS a gente da show, mas da uma puta preguiça de escrever, ai _nóis_ usa um [SASS](https://sass-lang.com/guide) pra pré-processar que o trem "avua"; 
* A gente escreve javascript ES6. E sim tem [jQuery](https://jquery.com/) no meio.
* [React JS](https://pt-br.reactjs.org/) ~~Hype~~ para algumas aplicaçãoe especificas.
* E o [Webpack](https://webpack.js.org/) orquestrando essa bagunça, organizada, é claro 😉


E se vc estudar isso tudo com muito empenho...

<p align="left" style="margin-bottom:10px;margin-top:10px;">
   <img   src="https://raw.githubusercontent.com/ClickQi/hello-young-padawan/master/img/you-will-become-a-jedi.gif" alt="you will become a jedi">
</p>

### Plataformas de e-commerce 🛒
Nós somos uma agência digital especializada em e-commerce e trabalhamos com plataformas no modelo SaaS (Software as a Service). Atualmente [VTEX](https://www.vtex.com/) e [Tray Corp](https://www.traycorp.com.br/) são nossas parceiras.

## VTEX
* [Mini Curso Sobre](https://www.udemy.com/course/vtex-um-guia-completo-sobre-a-plataforma/)
* [Documentação](https://help.vtex.com/developer-docs)
* [Controles para templates](https://help.vtex.com/tutorial/lista-de-controles-para-templates?locale=pt)
* [Controles para prateleira](https://help.vtex.com/tutorial/controles-do-template-de-prateleira?locale=pt)
* [VTEX IO](https://help.vtex.com/tracks/vtex-io-getting-started?locale=pt)

Para acessar as plataformas da VTEX basta utilizar o modelo de URL `[Nome da Loja].myvtex.com/` e `[Nome da Loja].myvtex.com/admin` para o painel de administração.

Para sua tranquilidade (e a nossa 😅), criamos um ambiente seguro todinho para vc começar a treinar e desenvolver suas habilidades.

# Aqui vai os primeiros passos com cada ferramenta 🤘

### Git Flow
Depois de você ter pesquisado sobre o git e git flow, resumindo, o git flow é uma forma organizada de fazermos o versionamento dos nossos projetos. 

São alguns comandos básicos que você vai usar:

* git flow init (para iniciar o git flow)
* git flow feature start NomeBranch (para criar uma nova branch, que irá ser uma cópia da Develop)
* git flow feature finish NomeBranch (para finalizar a branch e fazer o merge com a Develop)

Temos a master que é a branch principal, ao dar o "git flow init", ele irá criar a branch Develop que é uma cópia da Master, para podermos trabalhar nela com mais tranquilidade caso ocorra algum erro. Ao dar o comando "git flow feature start NomeBranch", este irá criar uma cópia da Develop e nesta branch você irá fazendo por etapas, como por exemplo o header de algum projeto, ao terminar este header você finaliza essa branch, e ele irá juntar ela com a Develop, depois é só inicar outra branch de outra parte do projeto que irá fazer. E assim vai até terminar todo o projeto e subir tudo para a Develop, nós fazemos a junção da Develop com a Master que é a principal, lançando uma reelise (versão).

### Charles
O Charles é uma ferramenta que usamos para mapear os aquivos que estão no nosso pc para a URL do projeto, já que não fazemos o CSS e JS na plataforma (apenas o HTML é feito na plataforma). Então para juntar este HTML com o CSS e JS precisamos mapear os aquivos para podermos visualizar como está ficando o projeto.

Para fazer o mapeamento da pasta com os arquivos siga esses comandos:

* Primeiro você vai fazer a instalação do certificado de segurança, no menu em **Help - SSL Proxing - Install Charles Root Certificate - Instalar Certificado - Usuário Atual - Procurar - Autoridades de certificação raiz confiável**.
* Com a página para o mapeamento aberta no navegador, clique com o direito no link desejado no charles (lembrando que é gerado mais de uma URL, é necessário fazer para todas), selecione a opção **Map local** e preencha o formulário de acordo com as imagens:

**VTEX:**(para VTEX com todas as URLs, fazer com o Path: /files/ e depois com /arquivos/)
<p align="left" style="margin-bottom:10px;margin-top:10px;">
   <img width="200" src="https://raw.githubusercontent.com/milaniromulo/hello-young-padawan/master/img/git-fire.png" alt="Git Fire">
</p>

**TRAY:**
<p align="left" style="margin-bottom:10px;margin-top:10px;">
   <img width="200" src="https://raw.githubusercontent.com/milaniromulo/hello-young-padawan/master/img/git-fire.png" alt="Git Fire">
</p>

## [Sand Box do Padawan](https://sandboxpadawan.myvtex.com/)

<p align="left" style="margin-bottom:10px;margin-top:10px;">
   <img   src="https://raw.githubusercontent.com/ClickQi/hello-young-padawan/master/img/may-the-force.gif" alt="May the force be with us">
</p>
