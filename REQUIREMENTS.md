# Requirements

These are the requirements for different milestones of wargames.

## MVP

### Data Integrity Epic

These requirements are focused around providing identity and integrity for the
actions that happen in games. Securely identifying gamers and confirming the
actions they take as part of games are the driver for this phase of development.

This epic will be done first as it is foundational to implementing any game.

#### Implement User Registration

Effectively the stories here will all be implemented by the same code.

1. As a platform operator, I want self-service registration so that my workload
is minimal.

1. As a gamer, I want to self-register to the platform so that I can play
games.

1. As a gamer, I want the gaming platform to verify the integrity of player
moves so that there is fairness in the games played.

1. As a developer, I want gamers to have action signing keys so that I can
confirm they have authorised in-game actions.

1. As a developer, I want the registration function to capture username and
email address so that future profile rescue could be performed.

1. As a developer, I want the registration function to capture a Ed25519 key
pair so that gamers can be identified and their game actions verified.

### Tic Tac Toe Epic

#### Parent Requirement

1. As a gamer, I want to play Tic Tac Toe (TTT) so that I can have fun.

##### Implementation Cards

1. As a developer, I want to validate TTT moves so that gamer expectations
are met.

1. As a gamer, I want to be automatically matched with another player so that I
can play TTT.

## Enhancements 1

1. As a platform operator, I want self-service profile resets / rescures so that my
workload is minimal.

1. As a gamer, I want to be able to rescue my profile in case of lost credentials
so that I can retain my profile and history.
