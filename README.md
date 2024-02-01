# <h1>dio-desafio-git-github</h1>
Desafio Projeto Git-Github 
<br>

Para que server o Git e Git Hub?
<br>

Git e o GitHub formam uma combinação poderosa que auxilia as equipes de desenvolvimento a controlar o versionamento de código, rastrear mudanças, colaborar de forma eficiente e garantir que o trabalho em equipe flua sem problemas. Eles são fundamentais para muitos fluxos de trabalho de desenvolvimento de software modernos.<br>
<br>
<br>

Imagens referências utilizando a versão: <strong>Windows 11</strong>.

{c:red}Primeiro passo{/c}: Crie uma pasta para o repositório em sua maquína com o nome que você deseja, pode ser tanto na area de trabalho ou em meus documentos, aonde você preferir, segue a explicação e imagens abaixo:

Pressione o botão direito do mouse aonde você desejar criar sua pasta e selecione New/Novo, em seguida  Folder/Pasta: 

![image](https://github.com/AscensionismSS/dio-desafio-github/assets/156155614/9f35bfba-364c-4114-b056-1704b3274155)<br>

após isso de um nome a sua pasta:<br>

![image](https://github.com/AscensionismSS/dio-desafio-github/assets/156155614/87c57abe-2f1f-4d6a-973f-d1a25cd24a99)<br>
<br>




<strong>Segundo passo</strong>: Instalando o Git, acesse o link https://git-scm.com/downloads e escolhe a versão correta para qual sistema operacional você esta utilizando.<br>

Agora vamos descobrir a versão do  Windows que você utiliza, se é 32bits ou 64 bits: <br>

Vá ao menu iniciar do Windows e pressione o botão direito em cima dele e selecione a opção System/Sistema:<br>

![image](https://github.com/AscensionismSS/dio-desafio-github/assets/156155614/b960b6dc-8966-480f-a809-a4cd4e1b6bea)<br>

na sequência irá aparecer uma tela para você com informações sobre computaor e a versão do seu sistema:<br>

![image](https://github.com/AscensionismSS/dio-desafio-github/assets/156155614/37fb9cc5-dfc0-440f-af15-de922b44f5b6)<br>


Pronto, agora é só escolher a versão que é mais compatível com seu windows e instalar.<br>


Abrindo o site https://git-scm.com/download e escolhendo seus sistema operacional, no meu caso Windows 11:

![image](https://github.com/AscensionismSS/dio-desafio-github/assets/156155614/8f092021-a885-47d0-97cd-b7184528e1ea)<br>


versão desejada, no meu caso 64 bits:<br>

![image](https://github.com/AscensionismSS/dio-desafio-github/assets/156155614/2313e8ba-e5a3-409d-be67-e5bd9c982f60) 

finalizando o download, é só concluir com a instalação.
<br>
<br>



<strong>Terceiro Passo</strong>: Agora que a instalação já foi concluída, vamos ver como utilizar o Git e Git Hub e algumas de suas funcionalidades básicas.
<br>
<br>



Agora sim, primeiros passos com Git e Github. Vamos acessar nossa conta do github em https://github.com e dar sequência criando nosso primeiro repositório.<br>

Imagino que você já tenha feito seu login, agora para criar seu primeiro repositório veremos no canto superior direito  um sinal de mais com uma seta, vamos clicar nele e em seguida New Repository/Novo Repositório:<br>

![image](https://github.com/AscensionismSS/dio-desafio-github/assets/156155614/25b2cb7f-9af1-459b-9d72-6039cab27923)<br>


Agora estamos na nossa tela para criar o repositório, aqui temos algumas opções:<br>
<br>
Repository name/Nome do repositório: Aqui daremos um nome para nosso repositório.<br>
<br>
Description/Descrição: Uma breve descrição sobre o repositório.<br>
<br>
Public/Publíco ou Private/Privado: vamos escolher se ele será público ou não, no caso escolhi público para todo mundo pode ver, mas apenas eu ou quem eu escolher pode alterá-lo.<br>
<br>
Readme File/Arquivo Leia-me, aqui que você pode escrever uma longa descrição para o seu repositório com detalhes e tudo mais.
Esse arquivo possue a extensão md(markdown), que é uma linguagem de marcação de texto<br>
Segue o Link para saber mais: [Markdown Guides/Guias de Markdown](https://www.markdownguide.org/basic-syntax)
<br>
Agora finalizamos clicando em Create repository/Criar Repositório:<br>
<br>

![image](https://github.com/AscensionismSS/dio-desafio-github/assets/156155614/6c465db5-e955-46da-8059-421d149f1fe7)<br>
<br>


Chegamos, finalmente a vez do Git:<br>
<br>



Lembra da pasta que criamos lá no começo? Então, agora vamos abrir ela,  quando estivermos dentro dela nós iremos clicar com o botão direito e selecionhar a opção Git Bash Here/Git Bash Aqui:<br>


![image](https://github.com/AscensionismSS/dio-desafio-github/assets/156155614/29338d0c-1818-4fd6-bc74-25f094f8de2c)<br>


caso não esteja aparecendo, ainda com o botão direito dentro desta pasta seleciona a opção Show More Options/Mostrar mais opções, ai sim você pode seguir o passo anterior:<br>

![image](https://github.com/AscensionismSS/dio-desafio-github/assets/156155614/5017fb82-e99a-4785-9b91-b5cc310bb5b4)<br>

Agora que estamos com o terminal aberto, vamos voltar rapidamente ao nosso github. Dentro do github vamos acessar nosso repositório, e nele vamos clicar na opção code, que esta em verde, depois ir em local e em seguidaclicar  na opção https, e vamos copiar a URL. Esse será o método que vamos usar para clonar nossa repositório para nossa máquina local.<br>

![image](https://github.com/AscensionismSS/dio-desafio-github/assets/156155614/1dae7df8-a5fe-4e04-8f6b-b5c502e69742)<br>
<br>

Utilizando o terminal para nosso primeiro clone: com o terminal aberto do git vamos digitar o seguinte comando: git clone, clicar com o seguinda botão do mouse e clicar em paste/colar, que é a URL que nós copianos anteriormente do nosso repositório do github na parte de https como mostra na imagens aterior, meu link no caso é este https://github.com/AscensionismSS/dio-desafio-github.git , você irá usar o do seu repositório.<br>

![image](https://github.com/AscensionismSS/dio-desafio-github/assets/156155614/19f770bd-e128-4f0a-b335-dc849cc5f9d9)<br>

Pronto, agora você fez o clone na sua máquina de forma local, aqui esta ele de forma concluída:<br>
![image](https://github.com/AscensionismSS/dio-desafio-github/assets/156155614/0fc79091-8dad-4b37-af16-047a927ece43)<br>

Agora você vai abrir e fechar ou dar uma f5 na pasta escolhida anteriormente, na qual você executou o Guit Bash, e verá que foi criado uma pasta com tudo que você já colocou no seu repositório. Aqui vai a minha =). <br>

![image](https://github.com/AscensionismSS/dio-desafio-github/assets/156155614/dee6076d-9598-4ec5-a9ec-6a0d3f9c95fd)<br>

Caso não consiga fazer o ultímo passo e pedir alguma autenticação, aqui está a documentação para fazer de maneira correta, basta seguir os passos:<br>

[Aprenda a autenticar o https clone](https://docs.github.com/pt/get-started/getting-started-with-git/about-remote-repositories#cloning-with-https-urls)

Link para comandos de Git e explicações mais detalhadas: <br>
[Git Comandos](https://comandosgit.github.io/)
 





























