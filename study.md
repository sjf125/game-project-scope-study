# Game Project Scope Study

## Required Readings

-   [Game Project](https://github.com/ga-wdi-boston/game-project)
-   [Game API](https://github.com/ga-wdi-boston/game-project-api)
-   [What is a User Story](http://searchsoftwarequality.techtarget.com/definition/user-story)

## Deliverables

After reading the `game-project` prompt and the `game-project-api` documentation
please do the following and be prepared to share and discuss on Monday morning.

Submit detailed answers to these in this file via a pull request.

-   A wireframe of what your game project will look like.
-   The data structure you plan to use.
  - How you will take the markup of the game board and represent it in JS
-   How you plan to approach this project.
-   4-8 user stories for your game project.
-   How you plan to keep your code moodular.
-   What creative spin will you add to your project.
-   How you will use version control to backup / track your project.
-   Do you plan to attempt any of the bonuses.


[Wireframe](https://app.moqups.com/sjf125/woZADwAU/edit/page/a16b2c2a4)
Data structure
  -Each TTT cell will have unique ID (A to I?)
  -Cell states will be mapped to an array - changes made with jQuery
  -Cells can either be null, 'x', or 'o'

Approach
  -Set up login and game pages
  -Integrate login and records functionality with API
  -Set up game logic
  -Set up reach goals of
    -Keep track of multiple game rounds with a win counter
    -Allow players to customize their tokens (X, O, name, picture, etc)
    -Get inventive with your styling, e.g. use hover effects or animations to
      spiff things up
  -Look into online multiplayer support
  -Look into setting up an AI player

User Stories
  -As a user, I'd like to be able to have an account to track my games
  -As a user, I'd like to be able to see the games won by each player to be able
   to tell who is winning
  -As a user, I'd like to be able to play against an AI in case I don't have
  anyone to play with
  -As a user, I'd like to be able to play online with other people in case no
  one is around to play on the same machine as me.
  -As someone concerned with privacy, I'd like to be able to play a game of TTT
  without having to sign up/register/submit my email.

Modularity - separate files
  -JS game logic
  -JA+jQUery game state/display manipulation
  -JS+Ajax API interaction
  -Moodularity - Barry White

Creative Spin
  -AI?
  -customizable player pieces?

I will git commit each time I create a new file, or get a section of code working

I'd like to attempt the reach goals of
  -online multiplayer
  -wins-counter
  -customizable tokens
  -AI/auto random placement of tokens
