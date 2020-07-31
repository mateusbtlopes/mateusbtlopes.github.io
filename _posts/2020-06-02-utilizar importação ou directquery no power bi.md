---
layout: post
title:  Utilizar Importação ou DirectQuery no Power BI?
tags:
- '#directquerypbi'
- '#importpbi'
- '#powerbi'
- '#pbidesktop'
- '#datavisualization'
category: [<i class="fa fa-linkedin"></i>]
---

<div style="text-align:center">
<p><img src="https://raw.githubusercontent.com/mateusbtlopes/mateusbtlopes.github.io/master/_posts/img/ImportDirectQueryPowerBI0.png" alt="Utilizar Importação ou DirectQuery no Power BI?" height="280" width="600"/></p>
</div>

<div style="text-align:center">
<p><i>Import ou DirectQuery de dados no Power BI</i>.</p>
</div>

<p>O <i>Power BI</i> é uma ferramenta de visualização de dados que possibilita aos seus usuários utilizarem de <a href="https://mateusbtlopes.github.io/descubra-quanto-custa-o-power-bi-para-voc%C3%AA-ou-sua-empresa" target="_blank">forma gratuita</a> a plataforma do <i>Power BI Desktop</i>. Ela ainda permite acesso a mais de 100 fontes de dados que abrangem serviços online, banco de dados, arquivos simples entre outras fontes.</p>

<p>Para essas fontes, é possível importar os dados diretamente para o <i>Power BI</i>, para algumas delas, também é possível conectar-se utilizando o <i>DirectQuery</i>, vejamos abaixo as principais características de cada um destes modos de conectividade disponíveis na ferramenta.</p>

<h3 id="heading3">Importação</h3>

<p>Utilizando este modo de conectividade, as tabelas e as colunas selecionadas serão importadas da origem para o <i><a href="https://mateusbtlopes.github.io/conheca-as-plataformas-do-power-bi" target="_blank">Power BI Desktop</a></i>, desta forma quando você criar ou interagir com uma visualização/gráfico, a plataforma usará os dados importados, sendo assim, a consulta será rápida e todas as alterações no visual serão refletidas imediatamente.</p>

<p>Para visualizar quaisquer alterações de dados ocorridas na origem das informações desde a importação inicial ou após a atualização mais recente, será necessário atualizar os dados, e assim, todo o conjunto de dados será importado novamente.</p>

<p>Ao salvar o arquivo do <i><a href="https://mateusbtlopes.github.io/conheca-as-plataformas-do-power-bi" target="_blank">Power BI Desktop</a></i> em sua máquina e compartilhá-lo com alguém, aquele que o receber poderá consultar completamente os dados, garantindo a interatividade de seu relatório ou painel.</p>

<p>Ao publicar um relatório no <i><a href="https://mateusbtlopes.github.io/conheca-as-plataformas-do-power-bi" target="_blank">Power BI Serviço</a></i> os dados importados serão incluídos no conjunto de dados e dada a configuração do serviço estas informações podem ser compartilhadas entre os usuários, porém, dependendo da localização da fonte de dados original, poderá ser necessário configurar um gateway de dados local.</p>

<p>Fique atento! O <i>Power BI</i> possui um limite padrão de importação, não permitindo que a importação aconteça de fontes de dados que possuem mais de 10 Gigabytes de dados.</p>

<h3 id="heading3">DirectQuery</h3>

<p>Utilizando este modo de conectividade, nenhum dado é importado ou copiado para o <i><a href="https://mateusbtlopes.github.io/conheca-as-plataformas-do-power-bi" target="_blank">Power BI Desktop</a></i>. Desta forma, conforme você cria uma visualização ou interage com ela, as consultas são enviadas à fonte de dados de origem para recuperar os dados atualizados.</p>

<p>Para visualizar a qualquer tempo as alterações de dados ocorridas na origem das informações, basta fazer a atualização dos dados - clicando no botão <i>“Atualizar”</i> da ferramenta - o tempo para atualizar o painel ou relatório depende do desempenho da fonte de dados de origem.</p>

<p>Após utilizar o DirectQuery e salvar o arquivo do <i><a href="https://mateusbtlopes.github.io/conheca-as-plataformas-do-power-bi" target="_blank">Power BI Desktop</a></i> e, ao compartilhar este arquivo com alguém, aquele que receber só conseguirá utilizar e acessar os dados, caso tenha permissão de acesso na base de dados de origem.</p>

<p>Ao publicar um relatório no <i><a href="https://mateusbtlopes.github.io/conheca-as-plataformas-do-power-bi" target="_blank">Power BI Serviço</a></i> os dados utilizados na consulta e a atualização dos visuais não serão incluídos no conjunto de dados do serviço. Dependendo da localização da fonte de dados original, poderá ser necessário configurar um gateway de dados local que se conecte à base de dados.</p>

<p>Para garantir que a abertura de um dashboard seja rápida, agendamentos podem ser feitos de forma a atualizar os dados frequentemente, refletindo a frequência com que os dados são alterados e o nível de relevância de ter os dados mais recentes em seus relatórios ou painéis.</p>

<p>E você, como tem feito suas conexões às bases de dados no <i>Power BI</i>? Tem utilizado <i>Import</i> ou <i>DirectQuery</i>?</p>