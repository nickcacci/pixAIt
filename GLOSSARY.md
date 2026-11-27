# pixAIt

A multiplayer storytelling and social-deduction card game played on a shared screen (the Board) with each Participant's phone as a private controller. Humans and AI Bots play together.

## Language

### Places and time

**Room**:
The shared space identified by a 4-letter code that Players join. It outlives a single play-through, and its lobby phase is where a Match is configured before it starts.
_Avoid_: Lobby (as a separate thing), session, game room

**Match**:
One complete play-through inside a Room, from start to game over.
_Avoid_: Game, game session

**Round**:
One Storyteller's turn within a Match.
_Avoid_: Turn

### Match modes

**Classic**:
A Match mode that ends at the end of the first Round in which a Participant reaches 30 points.

**Quick Match**:
A Match mode that ends after a fixed number of Rounds chosen in advance.

### People

**Participant**:
Anyone taking part in a Match: a Player or a Bot.
_Avoid_: Player (when Bots are included)

**Player**:
A human Participant, playing from a phone.
_Avoid_: User

**Bot**:
An AI-controlled Participant. "PixAI" is only the default display name of a Bot, never the name of the concept.
_Avoid_: AI player, AI bot, PixAI

**Host**:
The Player who configures the Match and starts it.
_Avoid_: Owner, admin

**Board**:
The shared display screen of a Room. It shows the Room code and the Match progress, and is never a Participant.
_Avoid_: Table, main screen

### Roles within a Round

**Storyteller**:
The Participant whose Card the others must try to identify in a Round.
_Avoid_: Narrator

**Guesser**:
Any Participant in a Round other than the Storyteller.
_Avoid_: Listener, non-storyteller

**Decoy**:
A Card submitted by a Guesser to hide among the options for the Storyteller's Card.
_Avoid_: Fake card, bluff

### Cards

**Card**:
An image together with a required text description of it.
_Avoid_: Picture, tile

**Hand**:
The Cards a Participant holds privately.
_Avoid_: Deck (a Hand is never a Deck)
