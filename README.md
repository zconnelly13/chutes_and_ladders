Chutes And Ladders
==================

Grabbing breakfast one morning, Greg and I started playing Chutes and Ladders.
Pleasantly amused by the simplicity of the game I realized that there was a
pile of interesting questions to ask. In fact, this could make for a great
set of interview questions.

![](http://i.imgur.com/N6m4ZQ9.jpg)

# The Rules

Both players start on square `0` (not present on the board) then they take 
turns spinning a spinner (1-6) and moving that many squares. If that square
is the bottom of a ladder they move up to the square at the top of the
ladder. If that square is a slide they move to the bottom of the slide.

You must land exactly on square 100 to win (i.e. if you are on square 99
you must roll a `1` to win, else you pass the turn)

# Questions

The more I thought about it the more opportunity I saw for questions...

Initially one could imagine how you'd model such a game and how you'd use
that model to implement a command-line version of the game.

To add some complexity you might ask questions like... 
1. Given a representation of a random board, how would you compute the shortest
   number of rolls to win?
   - how would your algorithm detect an unsolvable board?
2. Given a representation of a random board, how much of an advantage does a player
   get for going first?

Or some questions about generating a board
1. Given dimensions `M x N` as well as a number of chutes and number of ladders how
   would you generate a random "playable" board?
   - how would this algorithm detect if the constraints made it unsolvable?

Or, my favorite (and one where as of writing this I cannot think of a solution)
1. Given a representation of a random board, if you were allowed to weight your 
   di (or spinner), how would you compute the optimal weights to finish the game
   the fastest on average?
