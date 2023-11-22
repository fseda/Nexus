# Passeio Carioca - README

[Repositóro do aplicativo](https://github.com/fseda/nexus-app)

## Tabela de Conteúdos
- [5W2H - Sistema](#5w2h---sistema)
  - [O que?](#o-que)
  - [Como?](#como)
  - [Quem?](#quem)
  - [Por que?](#por-que)
  - [Onde?](#onde)
  - [Quando?](#quando)
  - [Quanto?](#quanto)
- [Requisitos Funcionais](#requisitos-funcionais)
- [Requisitos Não-Funcionais](#requisitos-não-funcionais)
- [Propósito](#propósito)
- [Casos de uso](#casos-de-uso)
  - [Buscar Novidade](#buscar-novidade)
  - [Visualizar feed](#visualizar-feed)
  - [Saber Mais](#saber-mais)
  - [Curtir Novidade](#curtir-novidade)
  - [Compartilhar Novidade](#compartilhar-novidade)
  - [Acessar Menu do Feed](#acessar-menu-do-feed)
  - [Comentar](#comentar)
  - [Filtrar o Feed](#filtrar-o-feed)
  - [Acessar pasta de novidades favoritas](#acessar-pasta-de-novidades-favoritas)
- [Equipe Nexus](#equipe-nexus)

## 5W2H - Sistema
## O que?

• Prototipagem e desenvolvimento de um sistema dentro de um aplicativo web (Passeio Carioca). O que será prototipado e desenvolvido é um feed que contém informações sobre locais, estátuas e imóveis históricos da cidade do Rio de Janeiro.

• As informações que serão apresentadas sobre os locais: 
  - 📖 História
  - 📷 Fotos
  - 🗺 Endereço
  - 📞 Contato

## Como? 

• O sistema funcionará como um feed de notícias, então o usuário poderá arrastar para cima e para baixo.

• O sistema será desenvolvido com **React**, uma biblioteca javascript, e prototipado no **Figma**.

• Será utilizado um repositório hospedado do GitHub para versionar o código e facilitar a colaboração entre os membros da equipe para que o sistema seja formado da melhor forma possível.

## Quem?

• O sistema poderá ser utilizado e acessado pelos usuários do aplicativo Passeio Carioca.

## Por que?

• Busca criar uma plataforma de distribuição de conteúdo, por meio de um feed, para difundir informações sobre, e aproximar pessoas de imóveis históricos.

## Onde?

• 🗺️ O sistema poderá ser utilizado no aplicativo Passeio Carioca.

• 📱 O aplicativo poderá ser acessado por dispositivos que possuem um navegador web e uma conexão à internet, e o sistema que criaremos estará dentro do APP Passeio Carioca.

## Quando? 

• 🕰 O sistema será acessado quando o usuário clicar em um botão dentro do aplicativo Passeio Carioca.

## Quanto?

• O sistema em si não custará nenhum valor em dinheiro, apenas tempo para sua produção.


## Requisitos Funcionais:
  - O sistema deve possuir um feed de pontos de interesse
  - O sistema deve exibir os pontos de interesse ordenados por data de edição.
  - O sistema deve ter pontos de interesse, com fotos, história, endereço, contato.
  - O sistema deve exibir anúncios de empresas parceiras.
  - O sistema deve permitir que qualquer usuário possa ver o feed.
  - O sistema deve permitir que qualquer usuário possa ver os detalhes de um ponto de interesse, ao clicar nele.
  - O sistema deve permitir o compartilhamento de um ponto de interesse, por meio de um link.
  - O sistema deve poder exibir anúncios, no feed, de imóveis parceiros do Passeio Carioca.
  - O sistema deve permitir a busca por pontos de interesse, através de palavras chaves.
  - O sistema deve permitir que usuários possam comentar em pontos de interesse.
  - O sistema deve exibir apenas comentários aprovados por administradores.
  - O sistema deve permitir que usuários favoritem pontos de interesse.

## Requisitos Não-Funcionais:
  - O sistema deve ser desenvolvido em React.
  - O sistema deve ser prototipado pelo Figma.
  - O sistema de possuir código fonte e documentação hospedados no Github.

##  Propósito:
Exibir um feed de notícias com os pontos de interesse do usuário. Além disso, o sistema mostrará anúncios de empresas parceiras no feed e possibilitará o compartilhamento dos pontos de interesse do usuário

## Casos de uso:
  #### Buscar Novidade:

  | Campo                       | Descrição                                                               |
  |-----------------------------|-------------------------------------------------------------------------|
  | **Descrição**               | O usuário irá poder buscar (em uma barra de busca) por algo específico (que esteja presente no sistema). |
  | **Ator**                    | Usuario do sistema                                                      |
  | **Fluxo principal**         | 1. Usuário acessa a barra de busca.<br>2. Usuário digita palavras chave, um grupo delas, datas ou locais.<br>3. O sistema exibe as novidades correspondentes à pesquisa do usuário. |
  | **Fluxos alternativos**    | 1. Usuário acessa a barra de busca.<br>2. Usuário digita palavras chave, um grupo delas, datas ou locais.<br>3. O sistema exibe a informação: “ nenhuma novidade correspondente a pesquisa foi encontrada”. |
  | **Pré-condições**          | Nenhuma                                                                 |
  | **Pós-condições**          | Nenhuma                                                                 |
  | **Exceções**               | - Palavras com erro linguístico / case sensitive.<br>- Nenhuma novidade correspondente a pesquisa.<br>- Má conexão. |
  | **Requisitos não funcionais** | - Função de fácil acesso e visibilidade.<br>- Busca deve ser o mais rápido possível.<br>- Exibir “barra” ou algo que demonstre que os dados estão sendo carregados pelo sistema. |

  #### Visualizar feed:

  | Campo                       | Descrição                                                               |
  |-----------------------------|-------------------------------------------------------------------------|
  | **Descrição**               | O usuário poderá visualizar quaisquer notícias desejadas por meio desse sistema. |
  | **Ator**                    | Usuario do sistema                                                      |
  | **Fluxo principal**         | 1. O feed estará disponível no menu do aplicativo.<br>2. O usuário poderá deslizar a tela. |
  | **Fluxos alternativos**    | Nenhum                                                                  |
  | **Pré-condições**          | Nenhum                                                                  |
  | **Pós-condições**          | Nenhum                                                                  |
  | **Exceções**               | Nenhum                                                                  |
  | **Requisitos não funcionais** | - Deslizar suavemente.<br>- Esteticamente agradável.<br>- Fácil acesso. |



  #### Ver detalhes:

  | Campo                       | Descrição                                                               |
  |-----------------------------|-------------------------------------------------------------------------|
  | **Descrição**               | O usuário clicar em ver detalhes e terá acesso à novidade em sua completude. |
  | **Ator**                    | Usuario do sistema                                                      |
  | **Fluxo principal**         | Usuário terá acesso a mais informações e fotos sobre o local. |
  | **Fluxos alternativos**    | Usuário será levado para uma página sobre a novidade (dentro do aplicativo, como um outro site). |
  | **Pré-condições**          | A novidade deve ter mais a apresentar do que só o que está presente no post principal. |
  | **Pós-condições**          | Nenhum                                                                  |
  | **Exceções**               | Nenhum                                                                  |
  | **Requisitos não funcionais** | - Transição rápida e agradável. |



  #### Filtrar o Feed:
  
  | Campo                       | Descrição                                                               |
  |-----------------------------|-------------------------------------------------------------------------|
  | **Descrição**               | O usuário deve poder escolher qualquer filtro dentre os presentes: Localização, Nome, palavras relacionadas |
  | **Ator**                    | Usuário do sistema                                                      |
  | **Fluxo principal**         | Acessar o menu e filtrar o que deseja.                                  |
  | **Fluxos alternativos**    | Nenhum                                                                  |
  | **Pré-condições**          | Nenhum Ainda                                                            |
  | **Pós-condições**          | Feed filtrado à pedido do usuário.                                      |
  | **Exceções**               | Não ter acesso à localização do usuário.                                |
  | **Requisitos não funcionais** | - Velocidade de carregamento da página. |
  
                                  
## Protótipo Figma 
[Protótipo Passeio Carioca](https://www.figma.com/file/iAdXW9OlZqI7b2lDzNd5mX/Untitled?type=design&node-id=0%3A1&mode=design&t=sXibb1qPX1T7P6l4-1)


### **Equipe Nexus**

[Felipe Seda](github.com/fseda)

[Isabella Vieira](github.com/isabellavieira)

[Victor Furtado](github.com/VicMouEstFur)

[Emilly Fernandes](github.com/emi-fernandes)

[Beatriz Babinski](https://github.com/BiaKzl)

## Entrosamento
O grupo decidiu se encontrar uma vez por semana em uma cafeteria para melhorar o entrosamento.

