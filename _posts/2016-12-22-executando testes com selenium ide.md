---
layout: post
title:  Executando Testes com Selenium IDE
tags:
- '#TestesAutomatizados'
- '#Selenium IDE'
- '#Firefox'
---

<p>Neste tutorial executaremos um teste utilizando o Selenium IDE no navegador Mozilla Firefox, conforme prometido no post anterior sobre <a href="http://mateusblopes.github.io/instalando-selenium-ide-no-firefox" target="_blank">como instalar o Selenium IDE no Firefox</a>.</p>

<h3 id="heading3">Gravando um teste no Selenium IDE</h3>

<p>1. Clique no menu "Ferramentas" e selecione a opção "Selenium IDE".</p>

<p><img src="https://raw.githubusercontent.com/mateusblopes/mateusblopes.github.io/master/_posts/img/ExecutandoSeleniumIDE1.png" alt="Selenium IDE - Reiniciar o navegador" /></p>

<p>2. Na janela principal do Selenium IDE, repare que a opção de "record" já vem como se estivesse pressionada. Caso não esteja, clique nela.</p>

<p><img src="https://raw.githubusercontent.com/mateusblopes/mateusblopes.github.io/master/_posts/img/ExecutandoSeleniumIDE2.png" alt="Selenium IDE - Tela principal do Selenium IDE" /></p>

<p>3. Volte ao Firefox e acesse o site que deseja testar, por exemplo <a href="http://mateusblopes.github.io/" target="_blank">http://mateusblopes.github.io/</a>.</p>

<p>4. Ainda no Firefox, agora com o site já aberto, vamos clicar com o botão direito do mouse sobre qualquer parte "branca" do site e em seguida selecionar a opção "<strong>waitForTitle Mateus Bruno T. Lopes</strong>".</p>

<p><img src="https://raw.githubusercontent.com/mateusblopes/mateusblopes.github.io/master/_posts/img/ExecutandoSeleniumIDE3.png" alt="Selenium IDE - Aguardando título do site" /></p>

<p>5. Agora vamos clicar com o botão direito do mouse sobre o item de menu "Blog" e em seguida selecionar a opção "<strong>verifyElementPresent link=BLOG</strong>". Com esta ação, estamos pedindo para o selenium que verifique se existe um link com nome de "BLOG".</p>

<p><img src="https://raw.githubusercontent.com/mateusblopes/mateusblopes.github.io/master/_posts/img/ExecutandoSeleniumIDE4.png" alt="Selenium IDE - Verificando item Blog" /></p>

<p>6. Agora vamos clicar novamente com o botão direito do mouse sobre o item de menu "Blog" e em seguida selecionar a opção "Exibir todos os comandos disponíveis -> <strong>assertText link=BLOG</strong>". Com esta ação, estamos pedindo ao selenium que confirme se o link que nós clicamos é o link do BLOG.</p>

<p><img src="https://raw.githubusercontent.com/mateusblopes/mateusblopes.github.io/master/_posts/img/ExecutandoSeleniumIDE5.png" alt="Selenium IDE - Assert item Blog" /></p>

<p>7. Agora vamos voltar a tela do Selenium, podemos reparar que ele gravou sequencialmente tudo que fizemos no site.</p>

<p><img src="https://raw.githubusercontent.com/mateusblopes/mateusblopes.github.io/master/_posts/img/ExecutandoSeleniumIDE6.png" alt="Selenium IDE - Teste gravado com sucesso" /></p>

<h3 id="heading3">Executando um teste no Selenium IDE</h3>

<p>1. Para executar o teste que acabamos de gravar, basta clicar no botão "<strong>Play</strong>".</p>

<p><img src="https://raw.githubusercontent.com/mateusblopes/mateusblopes.github.io/master/_posts/img/ExecutandoSeleniumIDE7.png" alt="Selenium IDE - Executar teste" /></p>

<p>2. Durante a execução será possível ver as ações gravadas sendo executadas no browser e também na tela do Selenium IDE, a medida que as ações vão sendo executadas com sucesso elas vão ficando verde e ao final, todo o processo deve ficar verde.</p>

<p><img src="https://raw.githubusercontent.com/mateusblopes/mateusblopes.github.io/master/_posts/img/ExecutandoSeleniumIDE8.png" alt="Selenium IDE - Teste executado com sucesso" /></p>

<p>3. Caso durante a execução um erro acontecer, a linha do processo ficará vermelha.</p>

<p><img src="https://raw.githubusercontent.com/mateusblopes/mateusblopes.github.io/master/_posts/img/ExecutandoSeleniumIDE9.png" alt="Selenium IDE - Teste executado com falha" /></p>

<h3 id="heading3">Salvando um teste do Selenium IDE</h3>

<p>1. Para salvar o teste seu teste e executá-lo novamenteo depois, clique no menu "Arquivo -> Salvar Teste", selecione a pasta que deseja salvar e pronto, seu teste está salvo para ser executado novamente em outro momento.</p>

<p><img src="https://raw.githubusercontent.com/mateusblopes/mateusblopes.github.io/master/_posts/img/ExecutandoSeleniumIDE10.png" alt="Selenium IDE - Salvando teste" /></p>
