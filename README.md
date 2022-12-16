# One Piece | Matching Game

[Veja esta página em português](#detalhes-do-projeto)

A matching game themed with One Piece characters, created using only HTML, CSS and Javascript. 

| :placard: Vitrine.Dev |     |
| -------------  | --- |
| :sparkles: Nome        | **Jogo da Memória de One Piece**
| :label: Tecnologias | HTML, CSS, JavaScript
| :rocket: URL         | https://zingarelli.github.io/onepiece-matching-game/
| :fire: Desafio     | Bootcamp TQI - DIO

![](https://user-images.githubusercontent.com/19349339/190666882-6779776b-3521-4a50-baf6-642ef06f09dd.png#vitrinedev)

## Project Details
This project is one of several challenges proposed as part of a technology bootcamp promoted by [DIO](https://www.dio.me) and sponsored by [TQI](https://www.tqi.com.br). You can [click here](https://github.com/zingarelli/desafios-bootcamp-TQI-DIO) to view the repo with all the projects (in Portuguese).

The instructor in this challenge was [Gabriela Pinheiro](https://www.linkedin.com/in/gabrielapinheiro129/).

## Credits
Images for the cards are from [One Piece Wiki](https://onepiece.fandom.com/wiki/Bounties/Gallery).

Background image is from [Wallpapers House](https://wallpaper-house.com/data/out/5/wallpaper2you_62356.jpg)

Gabriela is a great instructor and an excellent Front End Engineer! You should contact her on her [LinkedIn Page](https://www.linkedin.com/in/gabrielapinheiro129/). 

## About the challenge
We were challenged to create a matching game using only HTML, CSS and JavaScript (no frameworks allowed). The project was developed step by step by Gabriela, theming the game with Mario characters. The game was composed of a 4 x 3 board, with 6 pairs of cards portraying different Mario characters. 

Every new game the cards were randomly scrambled, with their faces being revealed for a few seconds and then flipped. The flipping action was animated using CSS. Using JavaScript, we added some controls to prevent flipping more than 2 cards per round and to keep the faces of cards already matched revealed.

## Developing my own matching game
Learning from the tutorials and code developed by Gabriela, I created my own matching game, theming it with One Piece characters ("Most Wanted" posters of the Straw Hat Pirates). My game was composed of 10 pairs of cards, placed in a 4 x 5 board. 

In addition, I created a side panel with a scoreboard, dinamically showing the number of attempts made by the player in the current game (considering it as the "score"), and the best score of all games. If the player wins the game with less attempts than the best score, the scoreboard is updated. 

I also added a "New Game" button, so the player can play another round and try to beat the best score. The button is deactivated while the face of the cards are being shown. Data is not stored in the browser, so if the page is reloaded, the best score is is set to zero.

Here's a GIF file of the game, where we can see the cards being revealed, the player making some attempts (with the score being updated) and then clicking on the New Game button.

![gif file showing the game in action](https://user-images.githubusercontent.com/19349339/177368271-c072195e-53bc-4c90-bf97-b8cfbd594e54.gif)

## TODO
Here's a list of features to develop in future versions:

- Responsiveness: the game was designed for big screens, with the board being 640x640 pixels + the scoreboard. On mobile devices, the layout breaks and the cards are very small, becoming impossible to play;

- Congratulations panel: create a modal with an animated gif and a congratulations message when the player finishes the game (maybe a gif with Sanji, since the game was a "total match" 🤡);

- Show the name of the player with the best score and add a modal with an input for the player to enter his/her name when beating the best score.

- Use local storage to store data in the browser, so the best score is not set to zero if the page reloads.

---

## Detalhes do projeto

Este projeto é um dos diversos desafios propostos como parte do bootcamp de tecnologia promovido pela [DIO](https://www.dio.me) e patrocinado pela [TQI](https://www.tqi.com.br). Você pode [clicar aqui](https://github.com/zingarelli/desafios-bootcamp-TQI-DIO) para ver o repositório com todos os projetos do bootcamp.

A instrutora neste desafio foi a [**Gabriela Pinheiro**](https://www.linkedin.com/in/gabrielapinheiro129/).

## Créditos

As imagens para os cards foram copiadas da [Wiki de One Piece](https://onepiece.fandom.com/wiki/Bounties/Gallery).

A imagem de background foi copiada de [Wallpapers House](https://wallpaper-house.com/data/out/5/wallpaper2you_62356.jpg).

A Gabriela é uma ótima instrutora e excelente engenheira de Front End! Você pode contactá-la em sua [página do LinkedIn](https://www.linkedin.com/in/gabrielapinheiro129/). 

## Sobre o desafio

Fomos desafiados a criar um jogo da memória utilizando somente HTML, CSS e JavaScript (sem utilizar frameworks ou bibliotecas externas). O projeto foi feito passo a passo pela instrutora, que o tematizou com personagens do Mario. O jogo original era composto por um tabuleiro 4 x 3, com 6 pares de cards mostrando diferentes personagens do Mario.

A cada novo jogo, os cards eram misturados aleatoriamente e tinham suas faces reveladas por alguns segundos antes de serem viradas. A ação de virar foi animada utilizando CSS. Com o JavaScript, nós adicionamos alguns controles para prevenir que mais de 2 cards fossem virados em um mesmo round, e para manter reveladas as faces dos cards que já haviam sido descobertos.

## Desenvolvendo meu jogo da memória customizado

Baseado nos tutoriais e código desenvolvido pela instrutora, eu customizei meu próprio jogo, tematizado com personagens de One Piece (com imagens dos pôsteres "Most Wanted" dos Piratas do Chapéu de Palha). Meu jogo é composto por 10 pares de cartas, dispostos em um tabuleiro 4 x 5.

Além disso, eu criei um painel lateral à direita com um placar, mostrando de maneira dinâmica o número de tentativas que o jogador fez no jogo atual (que seria o "score") e também o melhor score de todos os jogos. No caso do jogador/jogadora ganhar com um número de tentativas menor que o melhor score, o placar é atualizado com esse novo score.

Eu também adicionei um botão de "New Game" no painel lateral, para que o jogador/jogadora possa jogar uma nova partida e tentar bater o melhor score. O botão é desativado enquanto as faces dos cards estão sendo mostrados. Os dados de score não são armazenados localmente, então o melhor score se torna zero caso a página seja recarregada.

Segue um GIF do jogo, em que pode ser visto todos os cards sendo revelados, o jogador fazendo algumas tentativas(com o score sendo atualizado) e então clicando no botão de New Game.

![gif mostrando o jogo em ação](https://user-images.githubusercontent.com/19349339/177368271-c072195e-53bc-4c90-bf97-b8cfbd594e54.gif)

## TODO

Segue uma lista de funcionalidades a serem desenvolvidas em futuras versões:

- Responsividade: o jogo foi projetado para telas grandes (o tabuleiro tem 640x640 pixels, fora o placar lateral). Em telas pequenas, o layout quebra e os cards ficam muito pequenos, sendo impossível de jogar; 

- Painel de felicitações: criar um modal com um gif animado e uma mensagem de felicitações quando o jogador/jogadora vence o jogo (talvez um gif do Sanji, já que a partida foi um "match total" 🤡);

- Mostrar o nome do jogador/jogadora com o melhor score e adicionar um modal para que ele/ela possa digitar seu nome quando bate o melhor score;

- Usar o local storage para armazenar os dados de score no navegador, evitando que o melhor score seja zerado quando a página é recarregada.