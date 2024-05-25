# Radio Grid Run principles

## 1. Goals

Radio Grid Run is played from a [base](definitions.md#Base) where an [operator](definitions.md#Operator) is listening in. Teams of 2-3 people ([teams](definitions.md#Team)) compete against each other.

Each team uses its walkie-talkie to establish [contact](definitions.md#Contact) with the base through its transmissions. Each successful transmission earns the team an [activated location](definitions.md#Location) and extends its [territory](definitions.md#Terrain). The team with the largest territory wins the round. The game is played over several rounds.

The territory is a polygon delimited by the locations activated by a team. Certain locations can be imposed on the team, or offer special bonuses. The game is played in generally 2 rounds. Territories are not kept between rounds.

The exercise is spiced up by the fact that the time windows (hereafter [rendezvous](definitions.md#Rendezvous)) during which the base validates contacts are limited. These strict time constraints mean that teams have to make tactical choices about their path through the field. In addition, it is imperative to maintain contact with the base to be able to transmit its position when the time comes.

## 2. Principles

### Equipment

The devices used for transmissions are consumer walkie-talkies (PMR446) with a maximum transmitting power of 0.5W.

### Teams

To play, you need at least 3 teams of 2 players and an operator for the *base* and a log manager.

### Set-up

The base is manned by an operator. Teams start each round from the base, one after the other, according to a pre-determined schedule.

### Game progress

The round is made up of a certain number of rendezvous time windows specifically assigned to each team. Between each of these moments, the team is free to move as it wishes in order to maximize its territory. After the last rendezvous, teams have a limited time to return to base. The game ends after a formal debriefing led by a referee.

Team territories are calculated and visually compared. The python script [rgrHelper](https://github.com/radio-grid-run/rgrHelper) is designed specifically for this purpose.

![Sample territories of two teams](images/googleEarthPro_displayResults.png)
