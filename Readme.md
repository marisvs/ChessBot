### Overview

Imagine that you, as a chess player, can ask the computer about chess: to understand a position, why a move is good, to hear what the refutation is of a bad move, to learn with guided hints, to learn positional and strategic features, to learn about plans. To have a program that can explain why a move was played, in human understandable terms. Why is this not yet possible?

In 1997 Deep Blue settled the question whether computers could play chess strong enough to beat the world champion. Since then the chess battle between men and computer is over and the strongest engines are too strong to leave the world champion any hope for a win.
Continued development on hardware and software has made chess engines unbeatable for humans but less progress has been made in transfering this superior playing skills to human players.

Of course, computers play chess in a different way, but why are they not able to communicate more about a position than just the evaluation: a single numeric value.

Hence the goal of this project to add human *Cognitive skills* to computer chess:
*Develop programs that help human players improve their skills, that can communicate in human understandable terms about chess*


### Chess Bot
Chess engines are capable to calculate a million positions per second so the searchtree explodes very quickly. A human player cannot absorb all this information but is only interested in good moves or bad moves (from the opponent). For good moves he would like to understand why a move is good. For a bad move, he wants to know the refutation.
All this information is contained in the searchtree. What if we extract this information from the tree data, condensing it enormously and use it for communication with a chess player?
Let's build a chess chatbot or **ChessBot** to be used by humans to improve their chess skills through chatting about a game or position.

The ChessBot uses [Stockfish] (https://github.com/official-stockfish/Stockfish) as its core of a [Chess Engine] (https://github.com/marisvs/Stockfish) that has been modified to output the searchtree and other relevant information.


### Terms of use

