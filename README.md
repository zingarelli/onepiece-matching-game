# One Piece | Matching Game

A matching game themed with One Piece characters, created using only HTML, CSS and Javascript. 

| :placard: Vitrine.Dev |     |
| -------------  | --- |
| :sparkles: Nome        | **One Piece Matching Game**
| :label: Tecnologias | javascript, css, html
| :rocket: URL         | https://zingarelli.github.io/onepiece-matching-game/
| :fire: Desafio     | Bootcamp TQI - DIO

![](https://user-images.githubusercontent.com/19349339/190666882-6779776b-3521-4a50-baf6-642ef06f09dd.png#vitrinedev)

## Project Details
This project is one of several challenges proposed as part of a technology bootcamp promoted by [DIO](https://www.dio.me) and sponsored by [TQI](https://www.tqi.com.br). You can [click here](https://github.com/zingarelli/desafios-bootcamp-TQI-DIO) to view the repo with all the projects (in Portuguese).

The instructor in this challenge was [Gabriela Pinheiro](https://www.linkedin.com/in/gabrielapinheiro129/).

## About the challenge
We were challenged to create a matching game using only HTML, CSS and JavaScript (no frameworks allowed). The project was developed step by step by Gabriela, theming the game with Mario characters. The game was composed of a 4 x 3 board, with 6 pairs of cards portraying different Mario characters. 

Every new game the cards were randomly scrambled, with their faces being revealed for a few seconds and then flipped. The flipping action was animated using CSS. Using javascript, we added some controls to prevent flipping more than 2 cards per round and to keep the faces of cards already matched revealed.

## Developing my own matching game
Learning from the tutorials and code developed by Gabriela, I created my own matching game, theming it with One Piece characters ("Most Wanted" posters of the Straw Hat Pirates). My game was composed of 10 pairs of cards, placed in a 4 x 5 board. 

In addition, I created a side panel with a scoreboard, dinamically showing the number of attempts made by the player in the current game (considering it as the "score"), and the best score of all games. If the player wins the game with less attempts than the best score, the scoreboard is updated. 

I also added a "New Game" button, so the player can play another round and try to beat the best score. The button is deactivated while the face of the cards are being shown. Data is not stored in the browser, so if the page is reloaded, the best score is is set to zero.

Here's a GIF file of the game, where we can see the cards being revealed, the player making some attempts and then clicking on the New Game button.

![gif file showing the game in action](https://user-images.githubusercontent.com/19349339/177368271-c072195e-53bc-4c90-bf97-b8cfbd594e54.gif)

### Credits
Images for the cards are from [One Piece Wiki](https://onepiece.fandom.com/wiki/Bounties/Gallery).

Background image is from [Wallpapers House](https://wallpaper-house.com/data/out/5/wallpaper2you_62356.jpg)

Gabriela is a great instructor and an excellent Front End Engineer! You should contact her on her [LinkedIn Page](https://www.linkedin.com/in/gabrielapinheiro129/). 

## TODO
Here's a list of features to develop in future versions:

- Responsiveness: the game was designed for big screens, with the board being 640x640 pixels + the scoreboard. On mobile devices, the layout breaks and the cards are very small, becoming impossible to play;

- Congratulations panel: create a modal with an animated gif and a congratulations message when the player finishes the game (maybe a gif with Sanji, since the game was a "total match" 🤡);

- Show the name of the player with the best score and add a modal with an input for the player to enter his/her name when beating the best score.

- Use local storage to store data in the browser, so the best score is not set to zero if the page reloads.