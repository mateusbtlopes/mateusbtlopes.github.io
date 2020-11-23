---
layout: post
title: Como ler dados do Google Sheet no Power BI
tags:
- '#Google'
- '#GoogleSheet'
- '#lendogooglesheetnopowerbi'
- '#PowerBI'
- '#DataVisualization'
category: [<i class="fa fa-github"></i>]
---

<div style="text-align:center">
<p><img src="https://raw.githubusercontent.com/mateusbtlopes/mateusbtlopes.github.io/master/_posts/img/LendoGoogleShets1.png" alt="Como ler dados de arquivos Excel no Power BI" height="240" width="480"/></p>
</div>

<div style="text-align:center">
<p><i>Como ler dados do Google Sheet no Power BI</i>.</p>
</div>

<p>O Power BI é uma ferramenta de visualização de dados que possibilita aos seus usuários utilizarem de <a href="https://mateusbtlopes.github.io/descubra-quanto-custa-o-power-bi-para-voc%C3%AA-ou-sua-empresa" target="_blank">forma gratuita</a> a <a href="https://mateusbtlopes.github.io/conheca-as-plataformas-do-power-bi" target="_blank">plataforma do Power BI Desktop</a>. Ela ainda permite acesso a mais de 100 fontes de dados que abrangem serviços online, banco de dados, arquivos simples e muitas outras fontes. </p>

<p>Neste post iremos aprender como ler dados do <a href="https://docs.google.com/spreadsheets/" target="_blank">Google Sheets</a> utilizando o Power BI Desktop.</p>

<h3 id="heading3">Google Sheet de Exemplo</h3>

<ul>
<li><strong><i>Times_SerieA_Brasileiro20/21</i>:</strong> Arquivo que contém a lista de times da Série A do Campeonato Brasileiro 2020/2021, disponível em dois link's abaixo</li>
<li><a href="https://github.com/mateusbtlopes/ArquivosParaPowerBI" target="_blank"><strong><i>Link para download</i></strong></a></li>
<li><a href="https://docs.google.com/spreadsheets/d/1XRQD4ypljtdaLH66yARIgPCrP_incjLUnqBdarumOf8/edit?usp=sharing" target="_blank"><strong><i>Link para acesso online</i></strong></a></li>
</ul>

<h3 id="heading3">Configurando as permissões para acesso ao Google Sheets</h3>

<p>1. Crie uma nova <i>Sheet do Google</i>;</p>

<p>2. Acesse o menu <i>"File/Arquivo"</i> e em seguida acesse <i>"Publish to the web/Publicar na web"</i>;</p>

<p>3. Selecione a forma de publicação desta planilha, selecionando a <i>"Sheet1"</i> e o formato do arquivo como <i>"Comma-separated values (.csv)"</i>... Após configurado, clique em <i>"Publish/Publicar"</i>;</p>

<p><img src="https://raw.githubusercontent.com/mateusbtlopes/mateusbtlopes.github.io/master/_posts/img/LendoGoogleShets2.png"/></p>

<p>4. Uma notificação será exibida perguntando se você tem certeza de que quer publicar a sheet, confirme.</p>

<p>5. O link da Sheet publicada, será gerado e disponibilizado para cópia/utilização.</p>

<p><img src="https://raw.githubusercontent.com/mateusbtlopes/mateusbtlopes.github.io/master/_posts/img/LendoGoogleShets3.png"/></p>

<h3 id="heading3">Lendo dados do Google Sheets no Power BI</h3>

<p>1. Abra a plataforma <i>Power BI Desktop</i>;</p>

<p>2. Acesse o menu <i>"Página Inicial"</i>, clique no botão <i>"Obter dados"</i> e acesse a opção <i>"Web"</i>;</p>

<p>3. Uma janela para inclusão do link a ser acessado será exibida, cole o endereço do <a href="https://github.com/mateusbtlopes/ArquivosParaPowerBI" target="_blank"><strong><i>link para download</i></strong></a> e clique em <i>"Ok"</i></p>

<p><img src="https://raw.githubusercontent.com/mateusbtlopes/mateusbtlopes.github.io/master/_posts/img/LendoGoogleShets4.png"/></p>

<p>4. A tela de <i>"Pré-visualização"</i> dos dados será exibida com uma amostra dos dados da Sheet;</p>

<p>5. Clique em <i>"Transformar Dados"</i>;</p>

<p><img src="https://raw.githubusercontent.com/mateusbtlopes/mateusbtlopes.github.io/master/_posts/img/LendoGoogleShets5.png"/></p>

<p>6. A tela do "Power Query Editor" será exibida;</p>

<p>7. No menu <i>"Página Inicial"</i> dentro do item <i>"Transformar"</i>, selecione a opção <i>"Usar a Primeira Linha como Cabeçalho"</i>;</p>

<p>8. Ainda no menu <i>"Página Inicial"</i> clique no botão <i>"Fechar e Aplicar"</i>;</p>

<p><img src="https://raw.githubusercontent.com/mateusbtlopes/mateusbtlopes.github.io/master/_posts/img/LendoGoogleShets6.png"/></p>

<p>9. O seu arquivo será carregado para o <i>Power BI Desktop</i> e os campos da Sheet poderão ser visualizados na sessão <i>"Campos"</i>. Para trocar o nome da base, clique com botão direito no mouse sobre ela e vá até a opção <i>"Renomear"</i></p>

<p><img src="https://raw.githubusercontent.com/mateusbtlopes/mateusbtlopes.github.io/master/_posts/img/LendoGoogleShets7.png"/></p>

<p>Prontinho! Seus dados foram carregados com sucesso do Google Sheets para Power BI Desktop :)</p>

<p><img src="https://raw.githubusercontent.com/mateusbtlopes/mateusbtlopes.github.io/master/_posts/img/LendoGoogleShets8.png"/></p>

<p>Estes arquivos estão disponíveis para download gratuitamente no meu repositório <a href="https://github.com/mateusbtlopes/ArquivosParaPowerBI" target="_blank">"ArquivosParaPowerBI"</a> do GitHub.</p>