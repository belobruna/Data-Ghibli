# Studio Ghibli

​O objetivo deste projeto é construir uma página web para visualizar um conjunto de dados que se adapte às necessidades do usuário. Essa página possibilita tanto visualizar como filtrar, ordenar os dados e mostrar informações relevantes através de cálculos agregados.

## Índice

- [1. Introdução ao Projeto](#1.-introdução-ao-projeto)
- [2. Histórias de Usuários](#2.-histórias-de-usuários)
- [3. Desenvolvimento da Interface](#3.-desenvolvimento-da-interface)
- [4. Testes de Usabilidade](#4.-testes-de-usabilidade)
- [5. Conteúdos implementados no projeto](#5.-conteúdos-implementados-no-projeto)


## 1. Introdução ao Projeto

A escolha do tema para o projeto foi o Studio Ghibli.

Studio Ghibli é um estúdio japonês de animação, muito conhecido por seus filmes como Meu Amigo Totoro, A Viagem de Chihiro, O Castelo Animado, entre outros grandes sucessos. As animações são bem recebidas em todo o mundo e algumas receberam várias nomeações e prêmios. De todo esse fandom há um grupo que deseja interagir e ver as informações das animações e seus personagens.

A partir dessa proposta definimos que o site seria dividido em 4 páginas:

Página Inicial - Traz um menu responsivio em dispositivos móveis, e uma apresetação de imagens de filmes mais conhecidos.

Página de filmes - Possibilita a visualização de todos os filmes do estúdio em formato de cards e no verso detalhes sobre cada um. Os filmes podem ser ordenados por ordem alfabética, A-Z e Z-A.

Página de Personagens - Apresenta cards com todos os personagens no verso algumas informações de genêro, idade e filme que participa. Podem ser ordenados por ordem alfabética, A-Z e Z-A.

Página de Dados - Em formato de cards, possibilita ao usuário ter acesso à informações sobre o tema e médias. (Em construção)

## 2. Histórias de Usuários

Uma História de Usuário representa em linguagem simples o que o usuário faz, do que ele precisa e por que, de maneira concisa. As histórias para esse projeto foram escritas pensando nas necessidades de nosso usuário final. A medida que o projeto avançava, algumas histórias foram subdivididas, tendo como objetivo organizar melhor as tarefas e atender aos requisitos da aplicação.

![images](./src/images/Historias_usuario.png) 

## 3. Desenvolvimento da Interface

Após a primeira análise dos dados disponíveis, percebemos que o site contaria com com cards de filmes e personagens que seriam filtrados e ordenados. A partir desta primeira ideia foi definido o protótipo de baixa fidelidade:

(Protótipo de baixa fidelidade)

Desenvolvemos o prototótipo de alta fidelidade no figma, onde posteriormente fizemos algumas alterações.

![images](./src/images/Sample_Wireframe.png)

Escolhemos a Flat UI Pallate em https://flatcolors.net/palette/182-flat-ui-pallate# como referência do site https://ghiblicollection.com/

![Alt text](Flat_UI_Pallate.gif)

## 5. Conteúdos implementados no projeto
Para construir a interface desta aplicação, em que é possível visualizar e manipular dados, os conhecimentos abordados foram:

HTML e CSS
Uso de HTML semântico.
Uso de seletores de CSS.
Construir sua aplicação respeitando o desenho realizado (protótipo).
Uso de flexbox em CSS.
DOM e Web APIs
Uso de seletores de DOM.
Gerenciamento de eventos de DOM.
Manipulação dinâmica de DOM. (appendChild |createElement | createTextNode| innerHTML | textContent | etc.)
JavaScript
Uso de condicionais (if-else | switch | operador ternário)
Uso de laços (for | for..in | for..of | while)
Uso de funções (parâmetros | argumentos | valor de retorno)
Manipular arrays (filter | map | sort | reduce)
Manipular objects (key | value)
Uso ES modules (import | export)
Diferenciar entre expression e statements.
Diferenciar entre tipos de dados atômicos e estruturados.
Testing
Teste unitário.
Estrutura do código e guia de estilo
Organizar e dividir o código em módulos (Modularização)
Uso de identificadores descritivos (Nomenclatura | Semântica)
Uso de linter (ESLINT)
Git e GitHub
Uso de comandos de git (add | commit | pull | status | push)
Gerenciar repositórios de GitHub (clone | fork | gh-pages)
Colaboração no Github (branches | pull requests | |tags)



