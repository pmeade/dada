# dada

A four person game of Euchre, played by friends. Created by pmeade for the Status.im hackathon found at https://hackathon.status.im/

**Game Design**

Euchre is a four player trump game played with the cards Nine through Ace. Rules can be found at https://en.wikipedia.org/wiki/Euchre

This dapp is meant to be lightweight and played by friends. It will not enforce the rules of the game, but will maintain a flow of cards that conform to the rules.

If possible the game will notify players of who has won each hand, but scoring itself will probably be manual.

**Technical Design**

The trickiest part of playing a card game on Ethereum is maintaining the secrecy of each players hand. I plan to accomplish this by having each player take a turn encrypting each card with a per card secret and shuffling the deck. Each card will have four layers of encryption. When a card is dealt to a player, the other players will provide their secret for that specific card. This will leave the card encrypted but visible to the player who holds the card. Once a player plays a card they provide their secret for the card thus rendering it visible to all.

**Visual Design**

TBD

**About the name dada**

It has no meaning