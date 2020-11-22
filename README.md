![Imagem de Capa](https://github.com/Marcelo-Diament/pratica-HTML-CSS-01-Curriculo/blob/main/assets/img/cover.png)

# Práticas de HTML e CSS | #01 - Currículo

Para visualizar o projeto, acesse a [página no GitHubPages](https://marcelo-diament.github.io/pratica-HTML-CSS-01-Curriculo/index).
___

## Índice

[Introdução](#introdução)

* [Objetivo](#objetivo)

* [Tecnologias](#tecnologias)

* [Links Úteis](#links-úteis)

[Como Usar o Repositório?](#como-usar-o-repositório?)

* [Pré Requisitos](#pré-requisitos)

* [Baixando o Repositório](#baixando-o-repositório)

* [Baixando Atualizações](#baixando-atualizações)

* [Criando sua Própria Branch](#criando-sua-própria-branch)

* [Atualizando sua Branch](#atualizando-sua-branch)

[Como Colaborar?](#como-colaborar?)

* [Atualizando o Changelog](#atualizando-o-changelog)

* [GitFlow e Padrões de Nomenclatura](#gitflow-e-padrões-de-nomenclatura)

* [Observações](#observações)

[Changelog](#changelog)

[Contato](#obrigado-pela-visita!)

___

## Introdução

Esse repositório é o primeiro de uma série de práticas criadas para fixarmos nosso conhecimento sobre **HTML** e **CSS**. Como é uma prática com foco em **HTML e CSS**, pularemos algumas etapas do processo de desenvolvimento de uma aplicação como um todo, mas - idealmente - recomenda-se **planejar muito bem o projeto antes de sairmos codando**. Isso inclui, no mínimo, busca por referências, definição do conteúdo, definição da hierarquia das informações e criação de um layout (ou ao menos um protótipo).

Ainda, como é a primeira aula sobre **HTML** e **CSS**, tenha em mente que há uma série de 'melhores maneiras' de atingirmos o mesmo resultado (ou mesmo resultados melhores), como uso do _flexbox_, o desenvolvimento _mobile first_ e o uso de uma série de outras propriedades e recursos, como _media queries_. Mas não se preocupe, chegaremos lá! Por enquanto, vamos focar no básico e garantirmos que todo o conhecimento será devidamente absorvido.

### Objetivo

Basicamente criaremos um currículo básico para entendermos as principais **tags e atributos do HTML**, bem como a **semântica do HTML**. Em seguida aplicaremos estilo a esse currículo através do **CSS**, para conhecermos os principais **seletores** e **propriedades/valores**.

### Tecnologias

Por se tratar da primeira prática do módulo de HTML e CSS, trabalharemos apenas com **HTML** (_Hyper Text Markup Language_) e **CSS** (_Cascading Style Sheet_), sem o uso de bibliotecas, pacotes, _frameworks_ nem _plugins_ externos. Exceto pela importação de fontes através do [Google Fonts](https://fonts.google.com/).

### Links Úteis

| Tema | Link |
| ----- | ----- |
| Git | https://thewebdev.com.br/git.php |
| HTML | https://www.w3schools.com/html/ |
| Elementos HTML | https://www.w3schools.com/html/html_elements.asp |
| Atributos HTML | https://www.w3schools.com/html/html_attributes.asp |
| Tabelas HTML | https://www.w3schools.com/html/html_tables.asp |
| Links HTML | https://www.w3schools.com/html/html_links.asp |
| Imagens HTLM | https://www.w3schools.com/html/html_images.asp |
| Símbolos HTML (unicode) | https://www.w3schools.com/charsets/ref_utf_symbols.asp |
| Lista de HTML Entities | https://dev.w3.org/html5/html-author/charref |
| Semântica em HTML | https://www.w3schools.com/html/html5_semantic_elements.asp |
| Atributo `rel` HTML | https://www.digitalocean.com/community/tutorials/html-rel-attribute-anchor-tags |
| CSS | https://www.w3schools.com/css/css_intro.asp |
| Sintaxe CSS | https://www.w3schools.com/css/css_syntax.asp |
| Seletores CSS | https://www.w3schools.com/css/css_selectors.asp |
| Listas CSS | https://www.w3schools.com/css/css_list.asp |
| Fontes CSS | https://www.w3schools.com/css/css_font.asp |
| Pseudo elementos CSS | https://www.w3schools.com/css/css_pseudo_elements.asp |
| Pseudo seletores ou classes CSS | https://www.w3schools.com/css/css_pseudo_classes.asp |
| Transition CSS | https://www.w3schools.com/css/css3_transitions.asp |
| Cubic Bezier (timing transições visual) | https://cubic-bezier.com/#.17,.67,.83,.67 |
| Animações CSS | https://www.w3schools.com/css/css3_animations.asp |

___

## Como Usar o Repositório?

Esss é um repositório público para fins didáticos (com conteúdo fictício, apenas para ilustração). Sinta-se à vontade para cloná-lo. No entanto, a ideia é que faça o seu próprio currículo, com dados reais e layout bem planejado, visando apresentá-lo a recrutadores e possíveis clientes (então capriche!).

### Pré Requisitos

Para poder manipular os arquivos desse repositório deve possuir, ao menos:

* IDE ou Software para Desenvolvimento, como o [VS Code](https://code.visualstudio.com/download)

* Terminal para executar comandos _git_, como o [GitBash](https://git-scm.com/downloads), por exemplo.

### Baixando o Repositório

Há mais de uma forma de 'baixar' um repositório, por exemplo, fazendo o download do projeto zipado. Mostraremos como **clonar** um repositório. Basta seguir os passos a seguir:

1. Abra o terminal de sua preferência e acesse o local (pasta do seu computador) onde o clone do projeto deverá ser criado:

``` sh
$ cd ../../C/User/Seu-Usuario/Desktop
```

_O local e o caminho para acessar tal local dependerá de cada máquina. Digite `ls` para listar os arquivos da pasta onde está para confirmar se é lá mesmo onde quer criar o clone do projeto. **Dica: o cifrão indica que trata-se de um código no terminal, ele não deve ser digitado.**_

2. Clique no botão botão verde no topo desse repositório ('_Code_') e selecione a opção de copiar o link para clonar o repositório, conforme imagem a seguir:

![Code](https://github.com/Marcelo-Diament/pratica-HTML-CSS-01-Curriculo/blob/main/assets/img/code.png)

_Antes de copiar o link, certifique-se de que está na branch main, branch principal do repositório._

3. Voltando para o terminal, execute o seguinte comando:

``` sh
$ git clone https://github.com/Marcelo-Diament/pratica-HTML-CSS-01-Curriculo.git
```

4. Por fim, acesse a pasta do repositório clonado com o comando:

``` sh
$ cd pratica-HTML-CSS-01-Curriculo
```

Prontinho! Você já possui o repositório clonado em sua máquina! =)

> **Dica Extra** | Vale a pena autenticar seu usuário GitHub com sua máquina, para facilitar o fluxo de trabalho. Para saber mais, acesse [esse link](https://thewebdev.com.br/git-autenticacao.php) que preparei para te ajudar.

### Baixando Atualizações

_E se passar um tempo e o projeto sofrer atualizações por parte do autor? Como consigo manter meu repositório atualizado? Preciso apagar e clonar o repositório novamente?_

A resposta é... Não! Você pode simplesmente baixar as atualizações através do terminal. Para isso, basta acessar o repositório via terminal e executar o comando `git pull` . Simples assim!

### Criando sua Própria Branch

Para criar uma branch, siga o [padrão de nomenclatura definido no repositório](#gitflow-e-padrões-de-nomenclatura). Basta executar o seguinte comando:

``` sh
$ git checkout -b feature/99-incluindo-x-recurso
```

### Atualizando sua Branch

Basta adicionar suas alterações ( `git add .` - você pode substituir o `.` por um arquivo ou pasta específicos), e realizar o _commit_ (sempre identificando as atualizações agrupadas no _commit_). Você deve agrupar os _commits_ de forma que faça sentido (exemplo: um _commit_ para atualizar as fontes, outro para atualizar posicionamento dos elementos, e assim por diante). Veja o comando para adicionar alterações e realizar um _commit_:

``` sh
$ git add . && git commit -m 'prefixo: alterando tamanhos de fontes [prefixo/00-nome-da-branch]'
```

Após finalizar todos os _commits_ execute um _push_ direcionado para sua branch. Então abra uma PR, complete os campos e aguarde o _Code Review_ (com a aprovação ou solicitação de ajustes):

``` sh
$ git push origin prefixo/00-nome-da-branch
```

Para abrir a PR, acesse o repositório e clique em '_Open Pull Request_' ou pressione a tecla _Control_ e clique no link sugerido pelo terminal.

> Saiba mais sobre git e gitflow acessando esse [tutorial](https://thewebdev.com.br/git.php) que criei para te ajudar!

___

## Como Colaborar?

Essa sessão destina-se a explicar como colaborar com nosso projeto - ou seja, quais os padrões definidos e que devem ser respeitados.

### Atualizando o Changelog

**Changelog** basicamente é um log, um histórico das atualizações do projeto. Perceba que está organizado em ordem cronológica decrescente, ou seja, o que está acima é mais recente e o que está abaixo é mais antigo. Portanto cada nova _feature_, _bugfix_ ou qualquer outra alteração deve ser documentada no _changelog_.

É extremamente útil criarmos um changelog de nossos projetos para mantermos um histórico de fácil leitura e permitirmos outros devs entenderem rapidamente a evolução do projeto (não precisa ser tão detalhado quanto esse, que tem propósito didático).

### GitFlow e Padrões de Nomenclatura

> **Importante:** como já conhecemos o **fluxo de trabalho com git (gitFlow)**, seguiremos as boas práticas de criarmos uma **branch** por atividade/feature e quebrarmos as atualizações de cada branch em **commits** que façam sentido - sempre incluindo a mensagem que descreve cada commit.

Como padrão, podemos considerar os prefixos `feature` (para novas funcionalidades ou recursos), `bugfix` para ajuste de erros, `hotfix` para ajustes urgentes e `documentation` para atualizações relacionadas a documentação do projeto.

**Branch**

Para nomearmos as _branches_, usaremos o seguinte modelo: `prefixo/00-titulo` , sendo o número a ordem de cada _branch_ e o título um título breve que descreva de forma sucinta o que está sendo feito na _branch_.

**Commit**

Para nomearmos os _commits_, usaremos o seguinte padrão: `prefixo: descrição breve [prefixo-branch/nome-da-branch]` - assim, ao olharmos a lista dos arquivos no repositório, veremos facilmente quando e para que ocorreu a última atualização de cada arquivo.

**Pull Request**

Ao abrir uma PR (_Pull Request_), lembre-se sempre de preencher, no mínimo, o responsável (_Assignees_), o(s) rótulos (_Labels_) e a descrição, contendo as seguintes informações:

* **Nome da Branch**

* **Objetivo:** numa sentença curta, descreva o objetivo da sua branch/feature.

* **Solução:** como você solucionou o problema? Como funciona sua proposta?

* **Dependências:** é necessário instalar alguma biblioteca, pacote ou usar algum CDN?

* **QA:** Como eu devo testar sua feature? Que cenários de uso você imaginou?

**Nota importante:** quanto mais específico você for, mais chances da sua **PR** ser aprovada.

### Observações

Sempre mantenha seu código limpo, bem indentado e escrito de forma clara.

Mantenha as propriedades de estilo em ordem alfabética dentro de cada seletor e respeite a hierarquia dos seletores (seletores mais genéricos acima e seletores mais específicos abaixo, de modo que as especificidades sobrescrevam as generalidades).

Lembre-se sempre de testar em seu ambiente local (_localhost_) antes de abrir uma PR (_Pull Request_).

___

## Changelog

### Versão 1.0.0

**Release v1.0.0** _22/11/2020_

**feature/15-documentation-review**

* Documentação: inclusão de outros tópicos e revisão geral

* Documentação: inclusão de imagem de apoio (como clonar o repositório)

* Documentação: inclusão de 'Índice'

* Documentação: inclusão de 'Como Colaborar?'

* Documentação: revisão geral do arquivo README.md

* Documentação: inclusão de imagem de capa

**feature/14-seletores-avancados-css**

_Novos seletores: por atributo ( `[attr="valor"]` ), pseudoseletores ( `:` ) e pseudoelementos ( `::` )_

* Documentação: atualização do que foi feito no projeto até o momento

* Feature: animação com `@keyframes`

* Feature: pseudo-classes `first-of-type`

* Feature: adição formação acadêmica para destacar uso das pseudo-classes

* Feature: pseudo-classes `first-child` e `nth-child`

* Feature: pseudo-seletor com transform e transition

* Feature: pseudo-elemento com unicode (códigos HTML que trazem símbolos)

* Feature: aplicação de estilo por seletor genérico de atributos

**feature/13-mais-seletores-css**

_Novos seletores: por ID ( `#` ) e por classe ( `.` )_

* Documentação: atualização do que foi feito no projeto até o momento

* Feature: aplicação de estilo por seletores de classe

* Feature: inclusão de atributos classe

* Feature: aplicação de estilo por seletores de ID

* Feature: inclusão de atributos ID

**feature/12-estilo-inicial**

_Apenas seletores simples e aninhados através de tags HTML_

* Documentação: atualização do que foi feito no projeto até o momento

* Feature: estilizando table

* Feature: estilizando header e footer

* Feature: estilizando imagem de perfil (incluindo sombra)

* Feature: centralizando conteúdo do footer com `display: block; margin: auto; width: fit-content;`

* Feature: definindo margens e alinhamento de textos

* Feature: definindo margem de elementos containeres (`header`,           `aside`,           `main`,           `footer`,           `section`,           `article`,           `div`)

* Feature: definindo estilo de fontes

* Feature: importando fontes através do [GoogleFonts](https://fonts.google.com/specimen/Anton?sidebar.open=true&selection.family=Anton|Montserrat)

* Feature: definindo resets no estilo (propriedades iniciais)

* Feature: adicionando o arquivo CSS ao HTML pela tag `<link rel="stylesheet" href="./assets/stylesheets/style.css">` (caminho relativo)

* Feature: criando arquivo CSS - `./assets/stylesheets/style.css`

**feature/11-tags-semanticas-de-texto**

* Documentação: atualização do que foi feito no projeto até o momento

* Feature: uso da tag `<strong></strong>` (importância) e `<em></em>` (ênfase na leitura do texto por _screen readers_)

**feature/10-inclusao-atributos-html**

* Documentação: atualização do que foi feito no projeto até o momento

* Feature: definição de título, cópia, cópia oculta e corpo do email definido no link do tipo '_mailto_'

* Feature: inclusão de atributos complementares da tag `<a></a>` (`rel` e `referrerpolicy` além do `href`)

* Feature: inclusão de atributos básicos da tag `<a></a>` (`title` e `target` além do `href`)

* Feature: inclusão de atributos da tag `<img/>` (`height` e `width` além do `alt`)

**bugfix/09-refatoracao-aside**

* Documentação: atualização do que foi feito no projeto até o momento

* Bugfix: inclusão de títulos

**feature/08-recomendacoes**

* Documentação: atualização do que foi feito no projeto até o momento

* Feature: inclusão da tag `<caption></caption>`

* Feature: adicionando atributo `scope`

* Feature: adicionando tag `<table></table>` (e demais tags de tabela) para inclusão de contatos para recomendação

**feature/07-estrutura-semantica**

* Documentação: atualização do que foi feito no projeto até o momento

* Feature: agrupando elementos do header com tag neutra `<div></div>`

* Feature: substituindo algumas listas por outras tags mais adequadas

* Feature: agrupando conteúdo com tag semântica `<article></article>` ('micro') no lugar de algumas listas

* Feature: agrupando conteúdo com tag semântica `<section></section>` ('macro') no lugar de algumas listas

**feature/06-main**

* Documentação: atualização do que foi feito no projeto até o momento

* Bugfix: ajuste de conteúdo (data na formação acadêmica)

* Feature: inclusão de tags de títulos (_headings), como `<h2></h2>` e `<h3></h3>`

* Feature: criação de listas aninhadas (listas dentro de outras)

* Feature: criação de lista ordenada com a tag `<ol></ol>` (_ordered list_) e `<li></li>` (_list item_)

* Feature: criação de lista não ordenada com a tag `<ul></ul>` (_unordered list_) e `<li></li>` (_list item_)

**feature/05-aside**

* Documentação: atualização do que foi feito no projeto até o momento

* Feature: inclusão da tags de texto, como `<b></b>` (bold/negrito),           `<i></i>` (itálico) e `<mark></mark>` (grifado)

* Feature: inclusão da tag `<p></p>` em cada parágrafo

**feature/04-footer**

* Documentação: atualização do que foi feito no projeto até o momento

* Feature: inclusão da tag `<b></b>` para deixar rodapé em negrito

* Feature: inclusão do atributo de link `href` (tag `<a></a>`) no telefone e email do footer

**hotfix: atualização da documentação 3**

**feature/03-header**

* Documentação: atualização do que foi feito no projeto até o momento

* Feature: inclusão do atributo de link `href` (tag `<a></a>`) no telefone e email do header

* Feature: inclusão da imagem de perfil

* Feature: reordenação das informações do _header_

* Feature: inclusão de tags HTML no _header_

**feature/02-conteudo-inicial**

* Documentação: atualização do que foi feito no projeto até o momento

* Feature: inclusão de textos iniciais

* Feature: inclusão de imagem de perfil no projeto

**hotfix: atualização da documentação 2**

**hotfix: atualização da documentação**

**feature/01-estrutura-inicial**

* Documentação: atualização do que foi feito no projeto até o momento

* Feature: inclusão das principais tags (`<header></header>`,              `<aside></aside>`,              `<main></main>`,              `<footer></footer>`)

* Feature: atualização dos meta dados ( `lang` e `title` )

* Feature: inclusão da estrutura inicial do HTML

* Documentação: inclusão da introdução sobre o projeto

___

![cheers](https://github.githubassets.com/images/icons/emoji/unicode/1f942.png?v8)

 _And that's all folks!_

Se você leu esse documento até o final, está de parabéns! Programação é isso mesmo, muito estudo, prática, pesquisa, documentação... Mas vale todo o esforço!

Ficou com alguma dúvida? Não hestite em entrar em contato - estarei à disposição para te ajudar!

## Obrigado pela visita!

___

**Vamos nos conectar?**

Se quiser trocar idéias, experiências e figurinhas, entre em contato comigo!

**Marcelo Diament** | Desenvolvedor Front End Pleno e Instrutor

[Github][Github] | [LinkedIn][LinkedIn]

[//]: # 

[Github]: <https://github.com/Marcelo-Diament>
[LinkedIn]: <https://linkedin.com/in/marcelodiament>
