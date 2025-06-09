# Ratslap clone

## Foreword

Hi! Welcome to my silly little card game! If you happen to play it, please open an issue on this repo or send me a message with any feedback you may have! I'd love to hear your thoughts, and also rather selfishly, I love hearing when people play my games! 

Alright that's all, enjoy the game! 

## Goal

The goal is to get the most cards. Once you posess the whole deck, you win.

## Setup

You can play with any number of players greater than or equal to 2. Deal the whole deck out to everyone evenly. Each player should set their cards face down in front of them. Shuffle well and often!

## Play

This game is split into two phases. The main phase and the bluff phase. When in doubt, return to the main phase.

### The main phase

This phase mirrors that of egyptian rat slap.

In the main phase, everyone goes in a circle clockwise placing their top card face up in the center, piling on top of previously placed cards. If a predefined pattern of cards occur, the first player to slap the pile wins those cards. If a player slaps but there is no pattern, they must burn one card from the top of their pile to the center.

#### Patterns

You can choose any combination of card patterns you wish. here are a few examples:

- Pair: two cards of the same value.
- Sandwitch: two cards of the same value, separated by one miscellaneous card.
- Flush: three cards of the same suit.
- Straight: three cards of ascending or descending value.
- Add to 10: any pair of cards that adds to a total value of 10.
- 10: any 10.

## Bluff Phase

If at any time during the main phase, a face card is drawn, the bluff phase is triggered.

The next player in order, after the person who drew the face card, draws any number of cards from their deck, one by one, into their hand, hiding them from other players.

When drawing, each player gets a certain number of cards for free, but all cards after that number require them to burn one card from their deck before drawing. To determine the number of free cards any given player gets, check the last visible face card and consult the following graph:

|Last visible face card | Free cards |
|---|---|
|King | up to 4 |
|Queen | up to 3 |
|Jack | up to 2 |

When they're finished, they play their hand face down into the center, claiming one of the following:

- Their face down cards contain a face card.
- Their face down cards do not contain a face card.

Other players now have the option to call their bluff by slapping the face down cards and wagering any number of their cards on it. If correct, the caller may take their bluff back along with an equal number of cards from the central pile. If incorrect, the called player gets both the wagered cards and the matched cards from the center.

if not called, the cards are treated as claimed. (If the player claimed "face card", they are treated as a face card, otherwise they're treated as a non-face card)

If the played cards are a face card, the next player in turn order must now bluff in the same way.

If the played cards are not a face card, the last person who did play a face card takes the full center pile, and play returns to the main phase.

## Winning cards

When a player wins cards from any source, they must place them beside their current deck in a second pile. Only once their active pile is fully depleted, can they shuffle the second pile and use that as their active pile.


## Rats

2's and Jokers are considered "Rats".

If a pile containing a rat is called and the player who played it lied, then the liar takes the whole pile as well as the wager, and the game returns to the main phase. This takes precedence over other rules.

Rats only trigger on lies. If the player playing the rat told the truth, their rats are treated as normal non-face cards.
