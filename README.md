# Práticas de HTML e CSS | #01 - Currículo

## Introdução

Esse repositório pertence a uma série de práticas criadas para fixarmos nosso conhecimento sobre **HTML** e **CSS**. Como é uma prática com foco em **HTML e CSS**, pularemos algumas etapas do processo como um todo, mas - idealmente - recomenda-se **planejar muito bem o projeto antes de sairmos codando**. Isso inclui, no mínimo, busca por referências, definição do conteúdo, definição da hierarquia das informações e criação de um layout (ou ao menos um protótipo).

**Objetivo**

Basicamente criaremos um currículo básico para entendermos as principais **tags e atributos do HTML**, bem como a **semântica do HTML**. Em seguida aplicaremos estilo a esse currículo através do **CSS**, para conhecermos os principais **seletores** e **propriedades/valores**.

**Changelog**

Também será criado um **Changelog** explicando o que foi feito em cada branch do repositório, para que fique clara a ordem do passo a passo desse projeto.

**GitFlow e Padrões de Nomenclatura**

> **Importante:** como já conhecemos o **fluxo de trabalho com git (gitFlow)**, seguiremos as boas práticas de criarmos uma **branch** por atividade/feature e quebrarmos as atualizações de cada branch em **commits** que façam sentido - sempre incluindo a mensagem que descreve cada commit.

Como padrão, podemos considerar os prefixos `feature` (para novas funcionalidades ou recursos), `bugfix` para ajuste de erros, `hotfix` para ajustes urgentes e `documentation` para atualizações relacionadas a documentação do projeto.

**Branch**

Para nomearmos as _branches_, usaremos o seguinte modelo: `prefixo/00-titulo` , sendo o número a ordem de cada _branch_ e o título um título breve que descreva de forma sucinta o que está sendo feito na _branch_.

**Commit**

Para nomearmos os _commits_, usaremos o seguinte padrão: `prefixo: descrição breve [nome-da-branch]` - assim, ao olharmos a lista dos arquivos no repositório, veremos facilmente quando e para que ocorreu a última atualização de cada arquivo.

___

## Changelog

_Changelog basicamente é um log, um histórico das atualizações do projeto. Perceba que está organizado em ordem cronológica decrescente, ou seja, o que está acima é mais recente e o que está abaixo é mais antigo. É extremamente útil criarmos um changelog de nossos projetos para mantermos um histórico de fácil leitura e permitirmos outros devs entenderem rapidamente a evolução do projeto (não precisa ser tão detalhado quanto esse, que tem propósito didático)._

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

* Feature: inclusão da tags de texto, como `<b></b>` (bold/negrito), `<i></i>` (itálico) e `<mark></mark>` (grifado)

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

* Feature: inclusão das principais tags (`<header></header>`,    `<aside></aside>`,    `<main></main>`,    `<footer></footer>`)

* Feature: atualização dos meta dados ( `lang` e `title` )

* Feature: inclusão da estrutura inicial do HTML

* Documentação: inclusão da introdução sobre o projeto
