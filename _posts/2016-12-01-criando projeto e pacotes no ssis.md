---
layout: post
title:  Criando projeto e pacotes no SSIS
tags:
- SSIS
- Business Intelligence
- Visual Studio
---

<p>Neste tutorial construiremos um novo projeto no SSIS (SQL Server Integration Service) e manipularemos alguns pacotes de exemplo.</p>

<h3 id="heading3">Criando um novo projeto</h3>

<p>1. Abra o SQL Server Data Tools for Visual Studio, caso não o tenha instalado em seu computador, veja este post sobre como fazer <a href="http://mateusblopes.com.br/Download-e-Instalacao-SQL-Server-Integration-Service-SSIS.html" target="_blank">Download e Instalação do SQL Server Integration Service - SSIS</a>.</p>

<p>2. Na tela inicial/Start Page acesso a opção "File -> New -> Project". </p>

<p><img src="https://raw.githubusercontent.com/mateusblopes/mateusblopes.github.io/master/_posts/img/ProjectSSIS1.png" alt="SSIS - Criando um novo projeto" /></p>

<p>3. Na tela de criação do projeto selecione o "Template - Business Intelligence", o "Projeto - Integration Services Project", dê um nome para o seu projeto, no meu caso criei o projeto "<strong>CriandoProjetoPacoteSSIS</strong>", selecione a pasta onde seu projeto será salvo e dê um nome para a sua Solution, no meu caso coloquei o mesmo nome do projeto "<strong>CriandoProjetoPacoteSSIS</strong>". Clique em "Ok".</p>

<p><img src="https://raw.githubusercontent.com/mateusblopes/mateusblopes.github.io/master/_posts/img/ProjectSSIS2.png" alt="SSIS - Definindo um novo projeto" /></p>

<p>4. Temos então, nosso projeto SSIS criado com sucesso.</p>

<p><img src="https://raw.githubusercontent.com/mateusblopes/mateusblopes.github.io/master/_posts/img/ProjectSSIS3.png" alt="SSIS - Novo projeto criado" /></p>

<hr/>

<h3 id="heading3">Criando um novo pacote</h3>

<p>1. Dentro da Solution e do projeto que criamos a pouco, temos uma pasta denominada "SSIS Packages", por padrão o SSIS já cria o primeiro pacote pra gente denominado "Package".
<br/>Mas vamos criar outro pacote clicando com botão direito do mouse sobre a pasta "SSIS Packages" e selecionando a opção "New SISS Package".</p>

<p><img src="https://raw.githubusercontent.com/mateusblopes/mateusblopes.github.io/master/_posts/img/ProjectSSIS4.png" alt="SSIS - Criando um novo pacote" /></p>

<hr/>

<h3 id="heading3">Renomeando um novo pacote</h3>

<p>1. Clique com botão direito do mouse sobre o pacote que desejamos renomear e selecionando a opção "Rename", digite o nome desejado para o pacote, mas <strong>Atenção</strong>, cuidado para não retirar a extensão do pacote que deve ser <strong>".dtsx"</strong>.</p>

<p><img src="https://raw.githubusercontent.com/mateusblopes/mateusblopes.github.io/master/_posts/img/ProjectSSIS5.png" alt="SSIS - Renomeando um pacote" /></p>

<p>Nos próximos posts explicarei um pouco mais sobre como acrescentar componentes aos pacotes do SSIS, até lá =)</p>

<p>Acesse meu <a href="https://github.com/mateusblopes" target="_blank">GitHub</a>, faça download ou fork do meu repositório <a href="https://github.com/mateusblopes/trabalhando-com-ssis" target="_blank">Trabalhando com SSIS</a> e tenha acesso a este e outros arquivos de posts sobre o SSIS.</p>
