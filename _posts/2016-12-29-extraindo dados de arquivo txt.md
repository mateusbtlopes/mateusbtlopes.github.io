---
layout: post
title:  Extraindo dados de arquivo TXT
tags:
- SSIS
- Business Intelligence
- Visual Studio
---

<p>Neste tutorial criaremos um novo projeto no SSIS (SQL Server Integration Service) capaz de extrair dados de uma fonte de dados txt para outro arquivo txt.</p>

<p>1. Abra o SQL Server Data Tools for Visual Studio, caso não o tenha instalado em seu computador, veja este post sobre como fazer <a href="http://mateusblopes.com.br/Download-e-Instalacao-SQL-Server-Integration-Service-SSIS.html" target="_blank">Download e Instalação do SQL Server Integration Service - SSIS</a>, em seguida crie um projeto, caso nunca tenha feito isso, veja este post sobre <a href="http://mateusblopes.com.br/Criando-projeto-e-pacotes-no-SSIS.html" target="_blank">Como criar um projeto e pacotes no SSIS</a>.</p>

<p>Neste tutorial executaremos um teste utilizando o Selenium IDE no navegador Mozilla Firefox, conforme prometido no post anterior sobre <a href="http://mateusblopes.com.br/instalando-selenium-ide-no-firefox.html" target="_blank">como instalar o Selenium IDE no Firefox</a>.</p>

<h3 id="heading3">Criando conexão com arquivo TXT</h3>

<p>1. Para criar uma conexão com arquivo TXT, veja este post sobre <a href="http://mateusblopes.com.br/criando-conexoes-no-ssis.html" target="_blank">Como criar conexões no SSIS</a>.</p>

<h3 id="heading3">Extraindo dados de um arquivo TXT para outro arquivo TXT</h3>

<p>1. Na janela principal do SQL Server Data Tools for Visual Studio, "Control Flow", adicione uma task "Data Flow Task", em seguida abra esta task clicando duas vezes nela.</p>

<p><img src="https://raw.githubusercontent.com/mateusblopes/mateusblopes.github.io/master/_posts/img/ExtraindoDadosTXT1.png" alt="Extraindo Dados TXT - Adicionando Data Flow Control" /></p>

<p>2. Na aba "Data Flow" adicione uma task "Flat File Source", em seguida abra esta task, clicando duas vezes nela.</p>

<p><img src="https://raw.githubusercontent.com/mateusblopes/mateusblopes.github.io/master/_posts/img/ExtraindoDadosTXT2.png" alt="Extraindo Dados TXT - Adicionando Flat File Source" /></p>

<p>3. Configure a conexão criada inicialmente nesta task "Flat File Source".</p>

<p><img src="https://raw.githubusercontent.com/mateusblopes/mateusblopes.github.io/master/_posts/img/ExtraindoDadosTXT3.png" alt="Extraindo Dados TXT - Configurando Flat File Source" /></p>

<p>4. Confira o mapeamento dos dados.</p>

<p><img src="https://raw.githubusercontent.com/mateusblopes/mateusblopes.github.io/master/_posts/img/ExtraindoDadosTXT4.png" alt="Extraindo Dados TXT - Configurando Flat File Source" /></p>

<p>5. Na aba "Data Flow" adicione uma task "Flat File Destination".</p>

<p><img src="https://raw.githubusercontent.com/mateusblopes/mateusblopes.github.io/master/_posts/img/ExtraindoDadosTXT5.png" alt="Extraindo Dados TXT - Adicionando Flat File Destination" /></p>

<p>6. Link a task "Flat File Source" na task "Flat File Destination".</p>

<p><img src="https://raw.githubusercontent.com/mateusblopes/mateusblopes.github.io/master/_posts/img/ExtraindoDadosTXT6.png" alt="Extraindo Dados TXT - Lincando Flat File Destination" /></p>

<p>7. Abra a task "Flat File Destination" clicando duas vezes nela.</p>

<p><img src="https://raw.githubusercontent.com/mateusblopes/mateusblopes.github.io/master/_posts/img/ExtraindoDadosTXT7.png" alt="Extraindo Dados TXT - Configurando Flat File Destination" /></p>

<p>8. Clique no botão "New" para criar uma nova conexão para um arquivo TXT Delimitado.</p>

<p><img src="https://raw.githubusercontent.com/mateusblopes/mateusblopes.github.io/master/_posts/img/ExtraindoDadosTXT8.png" alt="Extraindo Dados TXT - Criando uma nova conexão para o Flat File Destination" /></p>

<p>9. Configure a nova conexão e informe o endereço do arquivo de destino.</p>

<p><img src="https://raw.githubusercontent.com/mateusblopes/mateusblopes.github.io/master/_posts/img/ExtraindoDadosTXT9.png" alt="Extraindo Dados TXT - Configurando a nova conexão" /></p>

<p>10. Realize o mapeamento do arquivo TXT de origem para o arquivo TXT de destino e clique em "Ok".</p>

<p><img src="https://raw.githubusercontent.com/mateusblopes/mateusblopes.github.io/master/_posts/img/ExtraindoDadosTXT10.png" alt="Extraindo Dados TXT - Mapeando a extração dos dados" /></p>

<p>11. Execute o pacote clicando em "Run".</p>

<p><img src="https://raw.githubusercontent.com/mateusblopes/mateusblopes.github.io/master/_posts/img/ExtraindoDadosTXT11.png" alt="Extraindo Dados TXT - Mapeando a extração dos dados" /></p>

<p>12. Temos então os dois arquivos origem e destino processados.</p>

<p><img src="https://raw.githubusercontent.com/mateusblopes/mateusblopes.github.io/master/_posts/img/ExtraindoDadosTXT12.png" alt="Extraindo Dados TXT - Mapeando a extração dos dados" /></p>

<p>Acesse meu <a href="https://github.com/mateusblopes" target="_blank">GitHub</a>, faça download ou fork do meu repositório <a href="https://github.com/mateusblopes/trabalhando-com-ssis" target="_blank">Trabalhando com SSIS</a> e tenha acesso a este e outros arquivos de posts sobre o SSIS.</p>