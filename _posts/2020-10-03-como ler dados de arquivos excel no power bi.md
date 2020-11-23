---
layout: post
title: Como ler dados de arquivos Excel no Power BI
tags:
- '#Excel'
- '#xls'
- '#xlsx'
- '#xlsm'
- '#lendoexcelnopowerbi'
- '#PowerBI'
- '#DataVisualization'
category: [<i class="fa fa-github"></i>]
---

<div style="text-align:center">
<p><img src="https://raw.githubusercontent.com/mateusbtlopes/mateusbtlopes.github.io/master/_posts/img/LendoExcel1.png" alt="Como ler dados de arquivos Excel no Power BI" height="240" width="480"/></p>
</div>

<div style="text-align:center">
<p><i>Como ler dados de arquivos Excel no Power BI</i>.</p>
</div>

<p>O Power BI é uma ferramenta de visualização de dados que possibilita aos seus usuários utilizarem de <a href="https://mateusbtlopes.github.io/descubra-quanto-custa-o-power-bi-para-voc%C3%AA-ou-sua-empresa" target="_blank">forma gratuita</a> a <a href="https://mateusbtlopes.github.io/conheca-as-plataformas-do-power-bi" target="_blank">plataforma do Power BI Desktop</a>. Ela ainda permite acesso a mais de 100 fontes de dados que abrangem serviços online, banco de dados, arquivos simples e muitas outras fontes. </p>

<p>Neste post iremos aprender como ler dados de arquivos do MS Excel, nos formatos ".xls", ".xlsx" e ".xlsm" utilizando o Power BI Desktop.</p>

<h3 id="heading3">Arquivos de Exemplo</h3>

<ul>
<li><strong><i>EstadosBrasileiros.xls</i>:</strong> Arquivo em formato "xls" utilizado por padrão ao salvar arquivos nas versões mais antigas do Excel (97 à 2003).</li>
<li><strong><i>Exportação de Carros.xlsx</i>:</strong> Arquivo em formato "xlsx" utilizado por padrão ao salvar arquivos nas versões mais recentes do Excel (Superiores á 2003).</li>
<li><strong><i>ListadePilotosF12020.xlsm</i>:</strong> Arquivo em formato "xlsm" utilizado ao salvar arquivos com macro em VBA (Visual Basic).</li>
</ul>

<p>Estes arquivos estão disponíveis para download gratuitamente no meu repositório "<a href="https://github.com/mateusbtlopes/ArquivosParaPowerBI" target="_blank">ArquivosParaPowerBI</a>" do GitHub.</p>

<p>Basta acessar o repositório, fazer o download destes arquivos para o seu computador e começar a praticar!</p>

<h3 id="heading3">Lendo arquivos do Excel</h3>

<p>1. Abra a plataforma <i>Power BI Desktop</i>;</p>

<p>2. Acesse o menu <i>"Página Inicial"</i>, clique no botão <i>"Excel"</i> diretamente ou clique no botão <i>"Obter dados"</i> e acesse a opção <i>"Excel"</i>;</p>

<p><img src="https://raw.githubusercontent.com/mateusbtlopes/mateusbtlopes.github.io/master/_posts/img/LendoExcel2.png" alt="Acessando a fonte de dados" /></p>

<p>3. Uma janela para seleção do arquivo a ser importado será exibida;</p>

<p>4. Devemos escolher qual arquivo desejamos ler ou carregar, neste exemplo, vamos selecionar o arquivo <i><strong>EstadosBrasileiros.xls</strong></i></p>

<p><img src="https://raw.githubusercontent.com/mateusbtlopes/mateusbtlopes.github.io/master/_posts/img/LendoExcel3.png"/></p>

<p>5. A tela de "Navegação" será exibida;</p>

<p>6. Devemos selecionar a "EstadosBrasileiros" e em seguida clicar em "Transformar Dados";</p>

<p><img src="https://raw.githubusercontent.com/mateusbtlopes/mateusbtlopes.github.io/master/_posts/img/LendoExcel4.png"/></p>

<p>7. A tela do "Power Query Editor" será exibida;</p>

<p>8. No menu "Página Inicial" dentro do item "Transformar", selecione a opção "Usar a Primeira Linha como Cabeçalho";</p>

<p><img src="https://raw.githubusercontent.com/mateusbtlopes/mateusbtlopes.github.io/master/_posts/img/LendoExcel5.png"/></p>

<p>9. Ainda no menu "Página Inicial" clique no botão "Fechar e Aplicar"</p>

<p>10. O seu arquivo será carregado para o Power BI Desktop e os campos da "EstadosBrasileiros" poderão ser visualizados na sessão "Campos".</p>

<p><img src="https://raw.githubusercontent.com/mateusbtlopes/mateusbtlopes.github.io/master/_posts/img/LendoExcel6.png"/></p>

<p>Prontinho! Seu primeiro arquivo excel foi carregado e os dados estão disponíveis para serem utilizados :)</p>

<p><img src="https://raw.githubusercontent.com/mateusbtlopes/mateusbtlopes.github.io/master/_posts/img/LendoExcel7.png"/></p>

<p>Repita do passo 2 ao 10 e carregue os demais ou quantos mais arquivos nos formatos "xls", ".xlsx" e ".xlsm" para o Power BI que você quiser.</p>

<p>Estes arquivos estão disponíveis para download gratuitamente no meu repositório "<a href="https://github.com/mateusbtlopes/ArquivosParaPowerBI" target="_blank">ArquivosParaPowerBI</a>" do GitHub.</p>