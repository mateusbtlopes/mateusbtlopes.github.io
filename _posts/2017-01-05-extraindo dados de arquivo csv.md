---
layout: post
title:  Extraindo dados de arquivo CSV
tags:
- '#SSIS'
- '#BusinessIntelligence'
- '#VisualStudio'
category: [<i class="fa fa-github"></i>]
---

<div style="text-align:center">
<p><img src="https://raw.githubusercontent.com/mateusbtlopes/mateusbtlopes.github.io/master/_posts/img/ExtraindoDadosCSV13.png" alt="Extraindo Dados CSV - Adicionando Data Flow Control" height="200" width="400"/></p>
</div>

<p>Neste tutorial criaremos um novo projeto no SSIS (SQL Server Integration Service) capaz de extrair dados de uma fonte de dados csv para outro arquivo csv.</p>

<p>1. Abra o SQL Server Data Tools for Visual Studio, caso não o tenha instalado em seu computador, veja este post sobre como fazer <a href="http://mateusbtlopes.github.io/download-e-instalacao-sql-server-integration-service-ssis" target="_blank">Download e Instalação do SQL Server Integration Service - SSIS</a>, em seguida crie um projeto, caso nunca tenha feito isso, veja este post sobre <a href="http://mateusbtlopes.github.io/criando-projeto-e-pacotes-no-ssis" target="_blank">Como criar um projeto e pacotes no SSIS</a>.</p>

<p>Neste tutorial executaremos um teste utilizando o Selenium IDE no navegador Mozilla Firefox, conforme prometido no post anterior sobre <a href="http://mateusbtlopes.github.io/instalando-selenium-ide-no-firefox" target="_blank">como instalar o Selenium IDE no Firefox</a>.</p>

<h3 id="heading3">Criando conexão com arquivo CSV</h3>

<p>1. Para criar uma conexão com arquivo CSV, veja este post sobre <a href="http://mateusbtlopes.github.io/criando-conexoes-no-ssis" target="_blank">Como criar conexões no SSIS</a>.</p>

<h3 id="heading3">Extraindo dados de um arquivo CSV para outro arquivo CSV</h3>

<p>1. Na janela principal do SQL Server Data Tools for Visual Studio, "Control Flow", adicione uma task "Data Flow Task", em seguida abra esta task clicando duas vezes nela.</p>

<p><img src="https://raw.githubusercontent.com/mateusbtlopes/mateusbtlopes.github.io/master/_posts/img/ExtraindoDadosCSV1.png" alt="Extraindo Dados CSV - Adicionando Data Flow Control" /></p>

<p>2. Na aba "Data Flow" adicione uma task "Flat File Source", em seguida abra esta task, clicando duas vezes nela.</p>

<p><img src="https://raw.githubusercontent.com/mateusbtlopes/mateusbtlopes.github.io/master/_posts/img/ExtraindoDadosCSV2.png" alt="Extraindo Dados CSV - Adicionando Flat File Source" /></p>

<p>3. Configure a conexão criada inicialmente nesta task "Flat File Source".</p>

<p><img src="https://raw.githubusercontent.com/mateusbtlopes/mateusbtlopes.github.io/master/_posts/img/ExtraindoDadosCSV3.png" alt="Extraindo Dados CSV - Configurando Flat File Source" /></p>

<p>4. Confira o mapeamento dos dados.</p>

<p><img src="https://raw.githubusercontent.com/mateusbtlopes/mateusbtlopes.github.io/master/_posts/img/ExtraindoDadosCSV4.png" alt="Extraindo Dados CSV - Configurando Flat File Source" /></p>

<p>5. Na aba "Data Flow" adicione uma task "Flat File Destination".</p>

<p><img src="https://raw.githubusercontent.com/mateusbtlopes/mateusbtlopes.github.io/master/_posts/img/ExtraindoDadosCSV5.png" alt="Extraindo Dados CSV - Adicionando Flat File Destination" /></p>

<p>6. Link a task "Flat File Source" na task "Flat File Destination".</p>

<p><img src="https://raw.githubusercontent.com/mateusbtlopes/mateusbtlopes.github.io/master/_posts/img/ExtraindoDadosCSV6.png" alt="Extraindo Dados CSV - Lincando Flat File Destination" /></p>

<p>7. Abra a task "Flat File Destination" clicando duas vezes nela.</p>

<p><img src="https://raw.githubusercontent.com/mateusbtlopes/mateusbtlopes.github.io/master/_posts/img/ExtraindoDadosCSV7.png" alt="Extraindo Dados CSV - Configurando Flat File Destination" /></p>

<p>8. Clique no botão "New" para criar uma nova conexão para um arquivo CSV Delimitado.</p>

<p><img src="https://raw.githubusercontent.com/mateusbtlopes/mateusbtlopes.github.io/master/_posts/img/ExtraindoDadosCSV8.png" alt="Extraindo Dados CSV - Criando uma nova conexão para o Flat File Destination" /></p>

<p>9. Configure a nova conexão e informe o endereço do arquivo de destino.</p>

<p><img src="https://raw.githubusercontent.com/mateusbtlopes/mateusbtlopes.github.io/master/_posts/img/ExtraindoDadosCSV9.png" alt="Extraindo Dados CSV - Configurando a nova conexão" /></p>

<p>10. Realize o mapeamento do arquivo CSV de origem para o arquivo CSV de destino e clique em "Ok".</p>

<p><img src="https://raw.githubusercontent.com/mateusbtlopes/mateusbtlopes.github.io/master/_posts/img/ExtraindoDadosCSV10.png" alt="Extraindo Dados CSV - Mapeando a extração dos dados" /></p>

<p>11. Execute o pacote clicando em "Run".</p>

<p><img src="https://raw.githubusercontent.com/mateusbtlopes/mateusbtlopes.github.io/master/_posts/img/ExtraindoDadosCSV11.png" alt="Extraindo Dados CSV - Mapeando a extração dos dados" /></p>

<p>12. Temos então os dois arquivos origem e destino processados.</p>

<p><img src="https://raw.githubusercontent.com/mateusbtlopes/mateusbtlopes.github.io/master/_posts/img/ExtraindoDadosCSV12.png" alt="Extraindo Dados CSV - Mapeando a extração dos dados" /></p>

<p>Acesse meu <a href="https://github.com/mateusbtlopes" target="_blank">GitHub</a>, faça download ou fork do meu repositório <a href="https://github.com/mateusbtlopes/trabalhando-com-ssis" target="_blank">Trabalhando com SSIS</a> e tenha acesso a este e outros arquivos de posts sobre o SSIS.</p>
