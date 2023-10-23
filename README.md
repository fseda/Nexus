# Passeio Carioca - README

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
- Buscar Novidade:
  
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


- Visualizar feed:

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


- Saber Mais:

| Campo                       | Descrição                                                               |
|-----------------------------|-------------------------------------------------------------------------|
| **Descrição**               | O usuário clicar em saiba mais e terá acesso à novidade em sua completude. |
| **Ator**                    | Usuario do sistema                                                      |
| **Fluxo principal**         | Usuário será levado para uma página sobre a novidade fora do aplicativo. |
| **Fluxos alternativos**    | Usuário será levado para uma página sobre a novidade (dentro do aplicativo, como um outro site). |
| **Pré-condições**          | A novidade deve ter mais a apresentar do que só o que está presente no feed de notícias. |
| **Pós-condições**          | Nenhum                                                                  |
| **Exceções**               | Nenhum                                                                  |
| **Requisitos não funcionais** | - Transição rápida e agradável. |


- Curtir Novidade:

| Campo                       | Descrição                                                               |
|-----------------------------|-------------------------------------------------------------------------|
| **Descrição**               | O usuário deve poder curtir qualquer novidade. Essa novidade será armazenada em uma pasta ‘favoritos’. |
| **Ator**                    | Usuário do sistema (CADASTRADO)                                         |
| **Fluxo principal**         | Apertar em um botão que representa essa ação.                           |
| **Fluxos alternativos**    | Nenhum                                                                  |
| **Pré-condições**          | Usuário estar cadastrado.                                               |
| **Pós-condições**          | ID da novidade deve ser armazenada em um banco de dados para que o usuário possa voltar a ela com facilidade. |
| **Exceções**               | Se o usuário não for cadastrado, ele deverá receber um popup que o avisa para se cadastrar para que ele possa curtir notícias. |
| **Requisitos não funcionais** | - Fácil acesso. |


- Compartilhar Novidade:

| Campo                       | Descrição                                                               |
|-----------------------------|-------------------------------------------------------------------------|
| **Descrição**               | O usuário deverá poder compartilhar a novidade com Não Usuários.        |
| **Ator**                    | Usuário do sistema                                                      |
| **Fluxo principal**         | O usuário clicará em um botão que o permitirá compartilhar por uma série de formas, o link da novidade. |
| **Fluxos alternativos**    | Nenhum                                                                  |
| **Pré-condições**          | A página de cada novidade deve ter seu próprio link.                    |
| **Pós-condições**          | Nenhum                                                                  |
| **Exceções**               | Nenhum                                                                  |
| **Requisitos não funcionais** | - Fácil acesso. |


- Acessar Menu do Feed:

| Campo                       | Descrição                                                               |
|-----------------------------|-------------------------------------------------------------------------|
| **Descrição**               | Usuário poderá acessar um menu dentro do feed que lhe possibilitará: Filtrar o Feed e Acessar pasta de novidades favoritadas. |
| **Ator**                    | Usuário do sistema                                                      |
| **Fluxo principal**         | O usuário clica no ícone de menu e acessa os elementos descritos.       |
| **Fluxos alternativos**    | Possíveis caminhos alternativos que o usuário pode seguir, normalmente quando ocorrem situações excepcionais. |
| **Pré-condições**          | Nenhuma                                                                 |
| **Pós-condições**          | Nenhum                                                                  |
| **Exceções**               | Usuário que não está cadastrado não pode ter pasta de favoritos.        |
| **Requisitos não funcionais** | - Fácil acesso. |


- Comentar:

| Campo                       | Descrição                                                               |
|-----------------------------|-------------------------------------------------------------------------|
| **Descrição**               | O usuário deve poder comentar em novidades do seu interesse.            |
| **Ator**                    | Usuário do sistema (CADASTRADO)                                         |
| **Fluxo principal**         | Clicar em um botão que o permite escrever um comentário em uma caixinha de texto e depois enviá-la. |
| **Fluxos alternativos**    | Nenhum                                                                  |
| **Pré-condições**          | Usuário estar cadastrado.                                               |
| **Pós-condições**          | Comentário salvo.                                                       |
| **Exceções**               | Se o usuário não for cadastrado, ele deverá receber um popup que o avisa para se cadastrar para que ele possa comentar. |
| **Requisitos não funcionais** | - Fácil acesso. |


- Filtrar o Feed:

| Campo                       | Descrição                                                               |
|-----------------------------|-------------------------------------------------------------------------|
| **Descrição**               | O usuário deve poder escolher qualquer filtro dentre os presentes: Localização (“Perto de Você”), Ordem Padrão, …histórico , arquitetura… (“interesse”). |
| **Ator**                    | Usuário do sistema                                                      |
| **Fluxo principal**         | Acessar o menu e filtrar o que deseja.                                  |
| **Fluxos alternativos**    | Nenhum                                                                  |
| **Pré-condições**          | Nenhum Ainda                                                            |
| **Pós-condições**          | Feed filtrado à pedido do usuário.                                      |
| **Exceções**               | Não ter acesso à localização do usuário.                                |
| **Requisitos não funcionais** | - Velocidade de carregamento da página. |


- Acessar pasta de novidades favoritas:

| Campo                       | Descrição                                                               |
|-----------------------------|-------------------------------------------------------------------------|
| **Descrição**               | O usuário terá acesso às novidades que favoritou.                       |
| **Ator**                    | Usuário do sistema (CADASTRADO)                                         |
| **Fluxo principal**         | Acesse o menu e selecione o ícone de favoritos.                         |
| **Fluxos alternativos**    | Nenhum                                                                  |
| **Pré-condições**          | Usuário estar cadastrado.                                               |
| **Pós-condições**          | Nenhum                                                                  |
| **Exceções**               | 1. Se o usuário não for cadastrado, ele deverá receber um popup que o avisa para se cadastrar para que ele possa curtir novidades.<br>2. Se o usuário não tiver favoritado nada,  deverá aparecer uma mensagem que diz “ Parece que você ainda não tem nenhuma novidade favorita ainda.” |
| **Requisitos não funcionais** | - Velocidade de carregamento da página. |




**Equipe Nexus**

Felipe Seda

Isabella Vieira

Victor Furtado

Emilly Fernandes

Beatriz Babinski


