# OPUS ACADEMICA — RULEBOOK

**A modular-building eurogame for 2–4 players | ~2 hours**

Each player leads a guild of builders competing to erect the most prestigious academy of magic. You will send Apprentices and your Magister to work in the campus buildings, build new ones, and compete for the Prestige Points that will lead you to victory.

For the exact text of every card, see [opusacademica_catalog.md](opusacademica_catalog.md).

---

## Background

The small town of **Sileatus** has grown enormously over the last few decades: the discovery of new mines, improved roads, and the recent opening of its river port have spiked its population and footprint. Amid this boom, the King has decided the time has come to found a new academy of magic. The Count has prepared the grounds and raised the basic structure of the academy upon a natural source of Aether discovered in the region. As distinguished *Magisters* of your magical schools, you have been charged with collaborating to complete this great work. And yet, even as you raise its walls together, each of you contends for the prestige of being its greatest architect. Whom will history remember as the most accomplished founder?

---

## Components

**Per player:**

- 1 player board (with the Private Archive)
- 1 Magister
- 3 Apprentices
- Ownership markers

**Resources** (unlimited general bank):

| Resource | Symbol | Description |
|---|---|---|
| Mundane | M | Basic materials, the most abundant |
| Gold | G | Trade currency |
| Aether | A | Magical energy, scarce |
| Insight | I | Academic knowledge, the rarest |

**Cards:**

- 78 building cards that form the deck
- 6 neutral cards that form the starting board
- 30 objective cards, corresponding to 23 distinct objectives

**General:**

- 1 First Player marker
- Landmark Building token

---

## The building cards

The 78 cards of the deck are the buildings you construct and work on. They all read the same way.

### How to read a card

```text
  TRADE CARAVAN   ·   Courtyard   ·   3 PP
  ───────────────────────────────────────────────
  Cost (to build)   :  2M + 2G
  Entry (to work)   :  1G
  Track             :  one-round
  Production        :  Gain 3 Mundane · Draw 1 card
```

Each card shows its **name** and **type** (Academy or Courtyard), its **Prestige Points (PP)**, the **Cost** to build it, the **Entry** cost to work on it (`No entry` = free), its **Track** —when it produces: immediate, one-round or two-round (see *Time tracks*)— and its **Production** effect, which you receive when your meeple reaches the end of the track.

In addition, some cards carry:

- **On enter:** an effect resolved the moment you place the meeple, not on production.
- **Magister Only:** only your Magister may work on them (for example, the Chancellery).

The exact text of every card is in the [catalog](opusacademica_catalog.md).

### Academies and Courtyards

Every building is one of two types, printed under its name:

- **Academy** — the great halls and works of the academy. They tend to be worth more PP and to produce knowledge (Insight, cards, resource conversions).
- **Courtyard** — the grounds and plots of the campus. They tend to be worth less PP and to produce raw materials (Mundane, Gold, Aether).

The type does nothing on its own, but many **objectives** and **card effects** look at it (for example, "for each adjacent Academy" or "have 3 connected Courtyards"). The 6 neutral starting cards are neither Academy nor Courtyard.

### Building Prestige Points

The number in the corner is the **Prestige Points (PP)** the building adds to your tally.

- A building starts counting its PP **the moment you build it** and place your ownership marker, even before it is inaugurated, and keeps counting as long as it stays on the board with your marker.
- A building's PP always belongs to its **owner** (whoever built it). Working on someone else's card gives you its production, but not its PP.
- These PP, together with those from your completed objectives, are what count toward the **35 PP** threshold that triggers the end of the game (checked at the end of each round) and toward final scoring.
- Neutral cards and the Private Archive give no PP.

---

## Setup

### Starting board

Place the 6 neutral cards in two rows of 3. These are neutral, unowned buildings: you can work on them and they count for adjacency, but they give no PP and are neither Academy nor Courtyard.

```text
[Village Market] - [The Great Gate] - [Alchemy Workshop]
       |                  |                    |
[Provisional Library] - [Well of Souls] - [Chancellery]
```

### Starting resources

Each player receives:

- 4 Mundane
- 3 Gold
- 2 Aether
- 1 Insight

### Deck, discard, and hand

1. Shuffle the 78 cards of the deck.
2. Set aside space for the common discard pile, face up.
3. Deal 7 cards to each player.
4. Each player keeps 5 for their hand and discards the remaining 2 to the common discard.

### Meeples and turn order

Each player places their Magister and their 3 Apprentices in their personal supply. Choose the First Player at random; from there, turn order proceeds clockwise.

### Objective draft

1. Shuffle the objective cards and place N+1 face up (N = number of players). This is the Objective Market.
2. In reverse turn order, each player picks 1 objective from the market.
3. Refill the market up to N+1 cards from the objective deck.

---

## Round structure

The game is played in rounds. Each round has two phases.

### Phase 1: Actions

Players take one action at a time in turn order. The available actions are:

- Work
- Build
- Supervise
- Pass

In addition, you may take objective free actions at any moment of your turn (see the Objectives section).

The phase ends when all players Pass consecutively. Passing does not remove you from the phase: if another player does something afterwards, you will get a turn again.

### Phase 2: Maintenance

Resolved in this order:

**1. Production.** Every meeple already at the end of its track triggers the card's effect and returns to its owner's supply. Resolved in turn order.

**2. Inauguration.** Meeples that are on a card via Supervision or Construction return to their owner's supply. Cards marked Under Construction are inaugurated and become available.

**3. Time advancement.** Every meeple still on a track advances one space toward the end. Meeples that reach the end during this step will produce next round, not this one.

**4. End of round.** If any player has 35 or more PP (buildings + objectives), the game ends. Otherwise, the First Player marker passes to the player on the left (the next in turn order) and a new round begins.

---

## General rules

- **Under Construction blocks everything.** A card Under Construction admits no action.
- **If you cannot pay, you cannot act.** All costs must be paid in full.
- **One meeple per track.** Only one meeple may be on a card's track at a time.
- **Partial resolution.** If an effect cannot be fully resolved, resolve as much as possible. If no part is possible, the result is null.
- **"Up to" effects.** You may choose 0. This may be used to occupy a space without using its effect.

---

## Actions

### Work

Place a meeple from your supply on the track of an inaugurated card on the board. You may work on any card, yours or someone else's — there is no mechanical difference.

1. Choose an inaugurated card whose track is free.
2. If the card is Magister Only, you may only use your Magister.
3. If you work with the Magister, discard 1 card from your hand.
4. Pay the card's entry cost, if any.
5. Place the meeple on the starting space of the track. If the card has an "On enter" effect, resolve it now.

The meeple will advance one space per round until it reaches the end, where it produces.

### Private Archive

Each player has a personal action space on their board called the **Private Archive**. It works like a Work space, but it is not a card: it is not built, has no owner, is not on the communal board, gives no PP, and does not count for objectives.

- Only that player may use it.
- Only the Magister may use it.
- It has no entry cost.
- It has no extra cost beyond the Magister's: because it is a Magister Work action, it only requires discarding 1 card for using the Magister to work.
- It is an immediate track: it produces in Phase 2 of the current round.
- Capacity: a single meeple; if the Magister is already there, it is locked until it produces.
- Production: draw 1 card.

### Build

An Apprentice from your supply builds a card from your hand and places it on the board.

1. Choose a card from your hand and pay its full build cost.
2. Place the card on an empty space orthogonally adjacent to at least one existing card (orthogonal = up, down, left, or right; never diagonally).
3. Place your ownership marker on it.
4. Place an Apprentice from your supply on the card.

The card stays Under Construction until Phase 2 of this round. Only Apprentices may build. The Magister cannot.

### Supervise

Your Magister accelerates one of your Apprentices that is on a track.

1. Choose a card where you have an Apprentice on the track that is not already at the last space.
2. There must not already be a Magister on that card.
3. Place your Magister on that card.
4. Your Apprentice advances one space toward the end of the track.

If the Apprentice reaches the end thanks to this acceleration, it will produce in Phase 2 of this same round. The Magister returns to your supply in Phase 2, step 2.

### Pass

You do nothing. It does not remove you from the phase.

---

## The Magister

The Magister only has a cost when it Works: discard 1 card from your hand, in addition to paying the card's entry cost if any. Supervising with the Magister has no cost.

The Magister can:

- Work
- Supervise

The Magister cannot:

- Build

Certain cards are Magister Only: only the Magister may work on them.

---

## Time tracks

Each card has a track that determines how long a meeple takes to produce. There are three types:

- **Immediate track:** the meeple enters directly at the end of the track and produces in Phase 2 of this round.
- **One-round track:** the meeple enters one space before the end. It advances to the end in Phase 2 and produces next round.
- **Two-round track:** the meeple enters two spaces before the end. It takes two rounds to reach the end and produce.

Supervision and certain card effects can advance meeples on tracks, accelerating production.

---

## Production

When a meeple reaches the end of its track and produces, the card's effect resolves and the meeple returns to its owner's supply.

### Resources deposited on cards

Some effects deposit resources on other cards (Archmage's Chamber, Pantheon, Supply Office, etc.). When a player produces successfully on a card that has resources deposited on it, they pick them up automatically along with the card's normal production, regardless of who placed them or of what type they are.

> **Exception — Necromancer's Crypt:** the resources on the Crypt are not collected on production; they form its exchange pool. They only move when a producer trades them 1:1 for their own resources using its production effect.

---

## Example round

A sample round with two players, **Ana** (First Player) and **Beto**. Both start with 4M, 3G, 2A, 1I.

**Phase 1**

1. **Ana — Work.** She places an Apprentice on the *Alchemy Workshop* (neutral, one-round track, entry 1A). She pays 1A. Her Apprentice enters one space before the end: on its own it would produce next round.
2. **Beto — Work.** He places an Apprentice on the *Village Market* (neutral, one-round track, entry 1G). He pays 1G.
3. **Ana — Supervise.** Her Magister accelerates her Apprentice at the Workshop: it advances one space and **reaches the end**. It will now produce in Phase 2 of **this** round. The Magister stays on the Workshop.
4. **Beto — Build.** He builds *Moneychanger's Square* (Courtyard, 3 PP) from his hand: he pays its cost (3M+1G), places it adjacent to the board, sets his marker and an Apprentice on it. It is **Under Construction** — but its **3 PP already count** for Beto.
5. **Ana — Pass.**
6. **Beto — Pass.**

Two consecutive passes: Phase 1 ends.

**Phase 2**

1. **Production.** Ana's Apprentice is at the end of its track: the Workshop produces, Ana gains **2 Gold and 2 Mundane**, and the Apprentice returns to her supply. Beto's Apprentice is not at the end yet, so it does not produce.
2. **Inauguration.** Ana's Magister (which was supervising) returns to her supply. Beto's *Moneychanger's Square* is inaugurated and becomes available; his building Apprentice returns to his supply.
3. **Time advancement.** Beto's Apprentice at the Market advances one space and reaches the end: it will produce in **round 2**.
4. **End of round.** No one reaches 35 PP. The First Player marker passes from Ana to Beto, and round 2 begins.

---

## Deck and cards

### Drawing cards

When an effect says "draw X cards", draw X cards from the deck.

### Empty deck

If the deck runs out of cards, shuffle the common discard to form a new deck. If even then there are not enough cards, resolve with what is available.

### Common discard

Every discarded card goes to the common discard, face up. Any player may examine it at any moment.

---

## Objectives

Objectives give each player their own strategic direction. When completed, they award PP immediately.

### General objective rules

- Each player can have at most **2 active objectives** at a time.
- At the start of the game, each player picks 1 objective from the market (initial draft).
- To get more objectives, send your Magister to the **Chancellery** during the game (requires having fewer than 2 active).
- Every time a player takes 1 objective from the market, the slot is refilled immediately from the objective deck, so that the market keeps showing `players + 1` objectives whenever possible.
- If the objective deck runs out, the market stops refilling. Discards and completed objectives are not reshuffled to create new ones.
- A completed objective stops being active: its PP add to your total and a slot is freed.
- If an objective requires a payment or deposit on acquisition, you may only pick it if you can pay at that moment.
- Objective PP count toward the 35 PP end-of-game threshold.
- **Private building** = any card with an owner. Neutral cards are not private buildings.
- Objectives complete at the exact moment their condition is met.
- **An objective cannot come pre-fulfilled.** What you already had at the moment of acquiring the objective (cards, positions, resources, board configurations) does not count toward satisfying its condition: something new after acquisition must satisfy it (a card built afterwards, a later trigger, a pivot or configuration different from the one you had at that moment). For example, if upon acquiring *Landmark Building* you already have one of your Academies with 4 occupied sides and ≥1 adjacent Courtyard, that Academy is excluded: you will need ANOTHER Academy to qualify. Same logic applies to clusters, straight lines, and similar configurations.

### Objective types

- **Solo:** depends only on your actions (supervising, building, spending resources, the position of your cards on the board).
- **Interactive:** requires interaction with other players (they work on your buildings, you on theirs, free actions between players).
- **Mixed:** combines solo conditions with board position.

### Objective free actions

Some objectives unlock free actions you can take on your turn without consuming your main action. The available free actions are:

**Reprimand** (Reprimand objective active): Advance one of a rival's Apprentices that is not on a production space by 1 space toward production. Apprentices only, never the Magister. Once per turn.

**Take Loan** (rival's Loan objective): Take the Gold deposited on another player's Loan objective. This completes their objective.

**Collaborate** (rival's Institutional Collaboration objective): Pay 1 Insight and deposit it on another player's Institutional Collaboration. You draw 2 cards.

**Take from Fixer** (rival's Fixer objective): Take 1 available resource from another player's Fixer. You may not take resources from your own Fixer. Once per turn.

**Build Idea** (rival's Inspired Idea objective): Build the card another player placed on their Inspired Idea. You pay the normal build cost and need a free Apprentice. This completes their objective.

**Village Workers** (rival's Village Workers objective): Deposit 1 Gold on the card and receive 2 Mundane. You may not deposit on your own objective. Once per turn per player. When 3 Gold are accumulated, the objective completes.

For the exact text of each objective, consult the catalog.

---

## End of game and scoring

The game ends at the end of a round in which any player has 35 or more PP (buildings + objectives).

**Final Prestige Points = PP from your buildings + PP from completed objectives**

Tiebreakers:

1. more Insight
2. more Aether
3. more Gold
4. more Mundane
5. if still tied, shared victory

---

## Quick reference

| Concept | Value |
|---|---|
| Starting resources | 4M, 3G, 2A, 1I |
| Starting hand | 5 cards chosen out of 7 |
| Objective Market | players + 1 objectives |
| Meeples | 1 Magister + 3 Apprentices |
| Max active objectives | 2 |
| End of game | 35 PP (buildings + objectives) |
| Magister cost | Work: discard 1 card. Supervise: free |

| Action | Who | Summary |
|---|---|---|
| Work | Apprentice or Magister | Place meeple on track and pay entry |
| Build | Apprentice | Pay cost, place card, leave Under Construction |
| Supervise | Magister | Advance one of your Apprentices by 1 space |
| Pass | Anyone | Do nothing |

| Free action (objective) | Effect |
|---|---|
| Reprimand | Advance a rival's Apprentice by 1 space (1/turn) |
| Take Loan | Take Gold from a rival's Loan |
| Take from Fixer | Take 1 resource from a rival's Fixer (1/turn) |
| Collaborate | Pay 1I to a rival, draw 2 cards |
| Build Idea | Build a rival's Inspired Idea card |
| Village Workers | Deposit 1G on a rival's objective and receive 2M |
