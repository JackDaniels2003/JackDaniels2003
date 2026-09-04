<!-- ╔══════════════════════════════════════════════════════════════╗ -->
<!-- ║  Daniel Teodoro · Perfil README · design dark / azul           ║ -->
<!-- ╚══════════════════════════════════════════════════════════════╝ -->

<p align="center">
  <img src="./assets/banner.svg" alt="Daniel Teodoro, Software Engineer" width="100%"/>
</p>

<p align="center">
  <a href="./README.md">English</a>
  &nbsp;·&nbsp;
  <a href="./README_pt.md"><b>Português</b></a>
</p>

<p align="center">
  <code>Engenheiro de Software</code> &nbsp;•&nbsp;
  <code>Sistemas de Negócio</code> &nbsp;•&nbsp;
  <code>Tecnologia Financeira</code> &nbsp;•&nbsp;
  <code>Automação</code>
</p>

<img src="./assets/divider.svg" width="100%"/>

## &nbsp; O engenheiro por trás dos sistemas

Construo software interno usado diariamente pelas equipes de financeiro, logística, comercial e gestão: plataformas financeiras, dashboards operacionais e ferramentas de automação que sustentam decisões reais. Escrever o código vem depois. Entender o problema de negócio o suficiente pra saber o que vale a pena construir vem primeiro, moldado por uma formação dividida entre Engenharia de Software e Administração.

<br/>

<p align="center">
  <img src="./assets/impact.svg" alt="4 plataformas em produção, 6 departamentos atendidos, uso interno diário, fluxo assistido por IA" width="100%"/>
</p>

<img src="./assets/divider.svg" width="100%"/>

## &nbsp; O que eu faço

<table>
<tr>
<td width="50%" valign="top">

**Gestão Financeira**
DRE projetado, fluxo de caixa, contas a receber e os indicadores que a liderança acompanha.

**Business Intelligence**
Dashboards e KPIs que substituem planilhas frágeis por dados vivos e consultáveis.

**Automação**
Extração de documentos, pipelines de ETL e rotinas que eliminam trabalho manual e repetitivo.

</td>
<td width="50%" valign="top">

**Plataformas Internas**
Sistemas operacionais usados diariamente entre setores, com autenticação e controle de acesso por cargo.

**Integração de Dados**
Ponte entre dados de ERP legado (DBF / TOTVS) e aplicações modernas com PostgreSQL.

**Análise de Negócio**
Entender um processo manual ou quebrado, conversar com quem convive com ele no dia a dia, e decidir o que vale a pena construir antes de escrever qualquer código.

</td>
</tr>
</table>

<img src="./assets/divider.svg" width="100%"/>

## &nbsp; Missão atual

> **Construo os sistemas que a empresa usa para tomar decisões, e participo das decisões que eles geram.**
>
> Substituir planilhas por aplicações web.
> Transformar exportações brutas do ERP em decisões confiáveis.
> Entregar à gestão números reais, em tempo real, em vez de relatórios de uma semana atrás.

<br/>

## &nbsp; Como eu trabalho

<p align="center">
  <img src="./assets/workflow.svg" alt="Fluxo de engenharia" width="100%"/>
</p>

<p align="center">
  <sub>
    Problema de Negócio → Requisitos → Arquitetura → Desenvolvimento com IA → Testes → Deploy → Melhoria Contínua
  </sub>
</p>

<img src="./assets/divider.svg" width="100%"/>

## &nbsp; Plataformas em destaque

<sub>Construídas para uso em produção. Os repositórios são mantidos **privados** porque o código contém informações confidenciais da empresa.</sub>

<br/>

<table>
<tr>
<td colspan="2" valign="top">

### ▣ &nbsp;Plataforma de Gestão Integrada &nbsp;<sub>· principal</sub>

O que começou como um DRE financeiro virou o hub de operações interno da empresa. Uma plataforma, vários setores, todos rodando sobre os mesmos dados ao vivo.

| Módulo | O que faz |
|--------|-----------|
| **Financeiro** | DRE projetado e realizado com back-testing, calendário de fluxo de caixa, contas a receber, indicadores |
| **RH** | Folha de ponto digital, controle de banco de horas, resumo da folha |
| **Compras** | Pedidos, orçamento de compras e o impacto deles no financeiro |
| **Logística** | Endereçamento de estoque e centro de distribuição, movimentação de pallets e controle de inventário, reconstruído dentro da plataforma depois de começar como sistema separado |
| **Comercial** | Indicadores de vendas, desempenho de vendedores e análise de clientes |
| **Dados** | ETL automatizado importando dados do ERP legado (DBF / TOTVS) para o PostgreSQL a cada poucos minutos |

`Node.js` · `Express` · `PostgreSQL` · `Python ETL` · `Docker` · `Nginx`

<sub>Privado · produção · usado entre setores todos os dias</sub>

</td>
</tr>
<tr>
<td width="50%" valign="top">

### ◆ &nbsp;Plataforma de Captação em Campo

Transforma a equipe de vendas em uma rede de prospecção em campo.

- Consultores registram obras e prospects no local
- Mais de 200 obras captadas até hoje
- Fotos (comprimidas automaticamente) e geolocalização GPS por lead
- Mapa interativo de cada oportunidade captada
- Distribuição de leads e acompanhamento de follow-up
- Single sign-on com a plataforma principal (HMAC)

`Python` · `Flask` · `SQLite` · `Pandas`

<sub>Privado · produção · uso diário</sub>

</td>
<td width="50%" valign="top">

### ◇ &nbsp;Plataforma de Processamento de Notas

Tira a digitação manual da rotina financeira.

- Extração de PDF · leitura de XML (NF-e)
- Conciliação automatizada direto no banco

`Python` · `Automação` · `PostgreSQL`

<sub>Privado · produção</sub>

</td>
</tr>
<tr>
<td colspan="2" valign="top">

### ◷ &nbsp;Plataforma de Solicitação de Estoque

Coordena o fluxo entre vendas e o centro de distribuição.

- Confirmação de estoque e fluxo estruturado de solicitação
- Acompanhamento de status e comunicação interna

`Node.js` · `PostgreSQL` · `EJS`

<sub>Privado · produção</sub>

</td>
</tr>
</table>

<img src="./assets/divider.svg" width="100%"/>

## &nbsp; Projeto pessoal

<sub>Não é trabalho da empresa. Construído no meu tempo livre pra aprender o que a stack interna não cobre: front-end moderno, tempo real, OAuth.</sub>

<br/>

<table>
<tr>
<td colspan="2" valign="top">

### ▲ &nbsp;Spotter &nbsp;<sub>· app pra encontrar parceiro de treino</sub>

Conecta pessoas que treinam sozinhas com parceiros de treino na mesma academia e horário.

- Onboarding em várias etapas: academia, horário, objetivos, interesses
- Feed com posts de fotos, comentários e combinação de perfis
- Chat em tempo real (individual e em grupo) via Socket.IO
- Eventos com mapa, álbum de fotos compartilhado e chat do evento
- Google OAuth, sessões JWT, API com rate limiting

`React Native` · `Expo` · `Express` · `PostgreSQL` · `Socket.IO`

<sub>Pessoal · em desenvolvimento</sub>

</td>
</tr>
</table>

<img src="./assets/divider.svg" width="100%"/>

## &nbsp; Stack

<table>
<tr>
<td align="center" width="16.6%"><img src="./assets/icons/backend.svg" width="92"/></td>
<td align="center" width="16.6%"><img src="./assets/icons/frontend.svg" width="92"/></td>
<td align="center" width="16.6%"><img src="./assets/icons/database.svg" width="92"/></td>
<td align="center" width="16.6%"><img src="./assets/icons/business.svg" width="92"/></td>
<td align="center" width="16.6%"><img src="./assets/icons/infra.svg" width="92"/></td>
<td align="center" width="16.6%"><img src="./assets/icons/ai.svg" width="92"/></td>
</tr>
<tr>
<td align="center"><sub>Python · Flask<br/>Node.js · Express</sub></td>
<td align="center"><sub>JavaScript · React Native<br/>HTML · CSS</sub></td>
<td align="center"><sub>PostgreSQL<br/>SQLite · SQL</sub></td>
<td align="center"><sub>Power BI<br/>Power Apps</sub></td>
<td align="center"><sub>Docker · Nginx<br/>Git</sub></td>
<td align="center"><sub>Engenharia<br/>assistida por IA</sub></td>
</tr>
</table>

<img src="./assets/divider.svg" width="100%"/>

## &nbsp; IA no meu fluxo de engenharia

<table>
<tr>
<td width="62%" valign="top">

A IA faz parte de como eu construo. Não é enfeite e não substitui engenharia.

Eu uso para avançar mais rápido na implementação: scaffolding, código repetitivo, refatorações, descoberta de casos de borda e documentação. Ela encurta a distância entre uma decisão e o código funcionando.

**As decisões continuam minhas.** Arquitetura, modelagem de dados, fronteiras de segurança, trade-offs e o que significa *correto* para o negócio: isso vem de entender o problema, não de um prompt. A IA acelera a digitação. O pensamento continua sendo meu.

</td>
<td width="38%" valign="top">

<img src="./assets/terminal.svg" alt="terminal" width="100%"/>

</td>
</tr>
</table>

<img src="./assets/divider.svg" width="100%"/>

## &nbsp; Atividade no GitHub

<div align="center">

<table>
<tr>
<td align="center" valign="top">
  <img height="195" src="https://github-readme-stats-gamma-plum-69.vercel.app/api/top-langs/?username=JackDaniels2003&layout=compact&hide_border=true&langs_count=8&bg_color=020617&title_color=60A5FA&text_color=94A3B8" alt="top languages"/>
</td>
<td align="center" valign="top">
  <img height="195" src="https://streak-stats.demolab.com?user=JackDaniels2003&hide_border=true&background=020617&stroke=1E3A8A&ring=2563EB&fire=60A5FA&currStreakLabel=60A5FA&sideLabels=94A3B8&dates=475569&currStreakNum=E2E8F0&sideNums=E2E8F0" alt="streak"/>
</td>
</tr>
</table>

<br/>

<img width="92%" src="https://github-readme-activity-graph.vercel.app/graph?username=JackDaniels2003&bg_color=020617&color=60A5FA&line=2563EB&point=FFFFFF&area=true&area_color=1E3A8A&hide_border=true&custom_title=Grafico%20de%20Contribuicoes" alt="activity graph"/>

<br/><br/>

<img width="92%" src="https://raw.githubusercontent.com/JackDaniels2003/JackDaniels2003/output/github-snake-dark.svg" alt="contribution snake"/>

</div>

<img src="./assets/divider.svg" width="100%"/>

## &nbsp; Contato

<p align="center">
  <a href="https://www.linkedin.com/in/daniel-vitor-da-silva-teodoro-31a01a273">
    <img src="https://img.shields.io/badge/LinkedIn-Daniel%20Vitor%20Teodoro-020617?style=for-the-badge&logo=linkedin&logoColor=60A5FA&labelColor=0F172A" alt="linkedin"/>
  </a>
  &nbsp;
  <a href="https://wa.me/5524999261431">
    <img src="https://img.shields.io/badge/WhatsApp-(24)%2099926--1431-020617?style=for-the-badge&logo=whatsapp&logoColor=60A5FA&labelColor=0F172A" alt="whatsapp"/>
  </a>
  &nbsp;
  <a href="mailto:danielteodoro1003@gmail.com">
    <img src="https://img.shields.io/badge/Email-danielteodoro1003@gmail.com-020617?style=for-the-badge&logo=gmail&logoColor=60A5FA&labelColor=0F172A" alt="email"/>
  </a>
</p>

<p align="center">
  <sub>Brasil · construindo software de produção que resolve problemas reais de negócio.</sub>
</p>

<img src="./assets/divider.svg" width="100%"/>
