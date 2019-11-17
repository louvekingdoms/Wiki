<!-- TITLE: Relation -->
<!-- SUBTITLE: A quick summary of Relation -->

# Description
Each character has a relation value with each other character, given they ever interacted. This values ranges from -100 to 100 and describe the attitude of the traveller towards the ruler.
This number can be affected by Communication (*see Communication*). 

| Hostile | Opposed ||| Neutral | Friendly ||| Loyal |
| -------- | -------- | -------- | -------- | -------- |-------- | -------- |-------- | -------- |
| -100| -75  | -50 | -25| 0  | 25| 50 | 75 | 100|

This relation value expresses the relation **from** a character **to** another. This means two characters will have to distinct relation values to one another.
The relation *between them* is sum of both, except negative points count **double** in this addition.

| -------- | -------- |
| What A thinks of B   | 50 |
| What B thinks of A |  -20 |
| Relation between them | **10** |

## Relation between a player and an AI
In the relation between a PC and a NPC, only the NPC has a relation value *towards* the player. The player's relation value towards everyone is considered to be 0;
## Relation between two players
There is no relation value between two players.
# Communication
The primary way to influence someone is to have a direct interaction with them, by the form of messages. There are three types of comunication.

* **CONVERSATION** 
* **PROPOSITION**
* **REQUEST**

Constructive communication is mainly only possible between a Ruler and a Traveler, but not between two Rulers.
## Conversation
A conversation is a typical discussion between two characters. Conversing is done by choosing one of the many subjects, and expressing an opinion on the matter : that opinion can be either **Neutral**, **Disapproving** or **Approving**.
### Conversation subjects

| Name | Technical | Description |
| -------- | -------- | -------- |
| Martial     | `martial`     | Personal combat, military, swordsmanship |
| Magic     | `magic`     | Magicians, wizardry |
| History     | `history`     | Past events, nationwide acheivements |
| Emotions     | `emotions`     | Feelings, sensations |
| Economy     | `economy`     | Management, economy, luxury |
| Art     | `art`     | Ballads, poems, paintings |
| Religion     | `religion`     | Faith, gods, sacred mission |
| Politics     | `politics`     | Internal affairs, rumors, legitimacy |
| Occult arts     | `occults`     | Resurrection, ghosts, curses |
| Nature     | `nature`     | Communion with nature, animals, beasts |

### Stance
When conversing, the character adopts a stance on those subjects, one at a time. The other character then answers positively, negatively or neutrally on the subject depending on their own opinions.
* If the reaction is positive, the relation gains **5** points
* If the reaction is negative, the relation loses **5** points
* If the reaction is neutral, the relation value doesn't change

The stance of the character on a subject or another **stays** through switching conversations, unlesss they have the Manipulative trait. ( See [Traits](/kingdoms-game/character/traits) )

### Streak
When conversing multiple subjects one after another with a character, consecutive reactions of the same kind (positive or negative) multiplies their effect. 
For example, if a character answers positively 3 times in a row, the relation value will increase by 5, then by 10, then by 15, for a total of **30**.

### Language barrier
If the two characters are not speaking the same [Language](/kingdoms-game/realms/language), the opinion expressed will be altered.

| Language barrier | Effect | 
| -------- | -------- | -------- |
| Different alphabet | The relation value doesn't change no matter what |
| Different root |  The relation value doesn't change no matter what  |
| Different form | There is no streaking, and **one out of five** messages will have the wrong opinion expressed on the subject |
| No language barrier | The relation value changes as intended, and the conversation works fully |


## Proposition

## Request
