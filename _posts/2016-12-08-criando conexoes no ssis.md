---
layout: post
title:  Criando conexões no SSIS
tags:
- '#SSIS'
- '#BusinessIntelligence'
- '#VisualStudio'
category: [<i class="fa fa-github"></i>]
---

<div style="text-align:center">
<p><img src="https://raw.githubusercontent.com/mateusblopes/mateusblopes.github.io/master/_posts/img/ConnectionsSSIS14.png" alt="Criando conexões no SSIS" height="160" width="450"/></p>
</div>

<p>Neste tutorial criaremos um novo projeto no SSIS (SQL Server Integration Service) capaz de se conectar a diversas fontes de dados como bancos de dados, arquivos do tipo excel, csv e até txt.</p>

<h3 id="heading3">Criando uma conexão com banco de dados SQL Server</h3>

<p>1. Abra o SQL Server Data Tools for Visual Studio, caso não o tenha instalado em seu computador, veja este post sobre como fazer <a href="http:/mateusblopes.github.io/download-e-instalacao-sql-server-integration-service-ssis" target="_blank">Download e Instalação do SQL Server Integration Service - SSIS</a>, em seguida crie um projeto, caso nunca tenha feito isso, veja este post sobre <a href="http://mateusblopes.github.io/criando-projeto-e-pacotes-no-ssis" target="_blank">Como criar um projeto e pacotes no SSIS</a>.</p>

<p>2. Clique com botão direito do mouse sobre dentro da janela de "Connections Managers", em seguida selecione a opção "New OLE DB Connections".</p>

<p><img src="https://raw.githubusercontent.com/mateusblopes/mateusblopes.github.io/master/_posts/img/ConnectionsSSIS1.png" alt="SSIS - Criando conexão com banco de dados" /></p>

<p>3. Na tela de configuração clique no botão "New".</p>

<p><img src="https://raw.githubusercontent.com/mateusblopes/mateusblopes.github.io/master/_posts/img/ConnectionsSSIS2.png" alt="SSIS - Criando uma nova conexão com banco de dados" /></p>

<p>4. Preencha o campos "Server Name", "Log on to the server", "Connect to a database -> Select or enter a database name" e teste a conexão com o banco desejado. No meu caso, conectei a um banco de dados local denominado "BancoConexaoSSIS".</p>

<p><img src="https://raw.githubusercontent.com/mateusblopes/mateusblopes.github.io/master/_posts/img/ConnectionsSSIS3.png" alt="SSIS - Configurando uma conexão com banco de dados" /></p>

<p>5. Temos então uma nova conexão com o banco de dados criada.</p>

<p><img src="https://raw.githubusercontent.com/mateusblopes/mateusblopes.github.io/master/_posts/img/ConnectionsSSIS4.png" alt="SSIS - Conexão com banco de dados criada" /></p>

<hr/>

<h3 id="heading3">Criando uma conexão com arquivos excel</h3>

<p>1. Clique com botão direito do mouse sobre dentro da janela de "Connections Managers", em seguida selecione a opção "New Connections".</p>

<p><img src="https://raw.githubusercontent.com/mateusblopes/mateusblopes.github.io/master/_posts/img/ConnectionsSSIS5.png" alt="SSIS - Criando conexão com banco de dados" /></p>

<p>2. Selecione a opção "EXCEL" na tela de adição de conexões e clique no botão "Add...".</p>

<p><img src="https://raw.githubusercontent.com/mateusblopes/mateusblopes.github.io/master/_posts/img/ConnectionsSSIS6.png" alt="SSIS - Criando uma nova conexão com banco de dados" /></p>

<p>3. Preencha o campo "Excel file path".</p>

<p><img src="https://raw.githubusercontent.com/mateusblopes/mateusblopes.github.io/master/_posts/img/ConnectionsSSIS7.png" alt="SSIS - Configurando uma conexão com banco de dados" /></p>

<p>4. Temos então uma nova conexão com o excel criada.</p>

<p><img src="https://raw.githubusercontent.com/mateusblopes/mateusblopes.github.io/master/_posts/img/ConnectionsSSIS8.png" alt="SSIS - Conexão com excel criada" /></p>

<hr/>

<h3 id="heading3">Criando uma conexão com arquivos .csv</h3>

<p>1. Clique com botão direito do mouse sobre dentro da janela de "Connections Managers", em seguida selecione a opção "New Flat File Connections".</p>

<p><img src="https://raw.githubusercontent.com/mateusblopes/mateusblopes.github.io/master/_posts/img/ConnectionsSSIS9.png" alt="SSIS - Criando conexão com arquivo CSV"/></p>

<p>2. Preencha o campo "File name" selecionando um arquivo de extensão ".csv".</p>

<p><img src="https://raw.githubusercontent.com/mateusblopes/mateusblopes.github.io/master/_posts/img/ConnectionsSSIS10.png" alt="SSIS - Configurando uma conexão com arquivo CSV" /></p>

<p>3. Temos então uma nova conexão com o arquivo csv criada.</p>

<p><img src="https://raw.githubusercontent.com/mateusblopes/mateusblopes.github.io/master/_posts/img/ConnectionsSSIS11.png" alt="SSIS - Conexão com arquivo CSV craida" /></p>

<h3 id="heading3">Criando uma conexão com arquivos .txt</h3>

<p>1. Clique com botão direito do mouse sobre dentro da janela de "Connections Managers", em seguida selecione a opção "New Flat File Connections".</p>

<p><img src="https://raw.githubusercontent.com/mateusblopes/mateusblopes.github.io/master/_posts/img/ConnectionsSSIS9.png" alt="SSIS - Criando conexão com arquivo TXT"/></p>

<p>2. Preencha o campo "File name" selecionando um arquivo de extensão ".txt".</p>

<p><img src="https://raw.githubusercontent.com/mateusblopes/mateusblopes.github.io/master/_posts/img/ConnectionsSSIS12.png" alt="SSIS - Configurando uma conexão com arquivo TXT" /></p>

<p>3. Temos então uma nova conexão com o arquivo txt criada.</p>

<p><img src="https://raw.githubusercontent.com/mateusblopes/mateusblopes.github.io/master/_posts/img/ConnectionsSSIS13.png" alt="SSIS - Conexão com arquivo TXT craida" /></p>

<p>Acesse meu <a href="https://github.com/mateusblopes" target="_blank">GitHub</a>, faça download ou fork do meu repositório <a href="https://github.com/mateusblopes/trabalhando-com-ssis" target="_blank">Trabalhando com SSIS</a> e tenha acesso a este e outros arquivos de posts sobre o SSIS.</p>
