---

layout: col-sidebar
title: OWASP Top Ten Card Game
tags: example-tag
level: 2
type: documentation
pitch: A very brief, one-line description of your project

---

OWASP Top Ten Card Game
Background and Rules

The OWASP Top 10 Card Game is an educational card game designed to help novice students learn about web application security, specifically by using the OWASP Top 10 — a widely recognized list of the top ten most critical web application security risks published by the Open Web Application Security Project (OWASP).

The game is easy to learn and designed to introduce risk concepts of the OWASP Top Ten and the best practices control concepts of the OWASP Top Ten Proactive Controls at a novice level in an environment that reflects a sense of realism and excitement. 

The game’s play grid was based on the attack path flow diagram provided with OWASP’s Top Ten publication. It is designed to help the student understand that attackers can potentially use many different paths through your application to do harm to your business or organization. 

The OWASP Top 10 focuses on identifying the most serious web application security risks for a broad array of organizations. The primary aim of the OWASP Top 10 is to educate developers, designers, architects, managers, and organizations about the consequences of the most common and most important web application security weaknesses. 

The OWASP Top 10 Proactive Controls are like the OWASP Top 10 but are focused on defensive techniques and controls as opposed to risks. The OWASP Top 10 Proactive Control techniques map to the threats in the OWASP Top 10. 

Game Objectives:

Simulate real-world cyberattack and defense scenarios using card-based mechanics. Player’s attack using the OWASP Top 10 threats (TA cards Ace through 10) and defend using the OWASP Proactive Controls (DC cards Ace through 10). The game provides opportunities to learn about vulnerabilities, cyber defenses, and resource tradeoffs through interactive play.

Each player must defend their assigned cyber assets from a series of attacks. The goal is to successfully counter incoming threats using Defense Control (DC) cards before losing key cyber assets.

Deck Composition:

* Standard poker deck: The game is based on the standard poker deck and modified playing cards (as described below) are not required for game play. Depending on the game mode, each player may need one or two decks.

* 20 Threat Agent (TA) cards (Hearts and Diamonds Ace to 10): Depending on the game mode, the TA deck may contain 40 TA cards (Hearts and Diamonds Ace to 10).

* 20 Defense Control (DC) cards (Spades and Clubs Ace to 10): Depending on the game mode, the DC deck may contain 40 cards (Spades and Clubs Ace to 10).

* Face Cards (Jacks, Queens, Kings): Face cards represent the player's key cyber assets. TA (Spades and Clubs) and DC (hearts and diamonds).

* Joker Wildcards: The black Joker card represents TA Black Hat malicious activities, and the red Joker card represents DC White Hat defense processes and tools. The number of Jokers depends on the selected game mode.

* OWASP modified playing cards: OWASP provides modified poker cards to enhance game play and learning experience. These cards are about the same size as the standard poker card (2.5 x 3.5 inches) and the card backs show the OWASP logo. In addition, the card faces carry OWASP copyrighted images designed to enhance game play. Similar to a standard poker card deck, the numbered cards (Ace through 10) are printed with the card suit and number in the upper left corner with a mirror image in the bottom right corner. The suit images found within the body of a standard poker card are replaced with a brief description of the Top 10 risk (Heart and Diamond cards) and the Top 10 Proactive Control (Spade and Club cards). The OWASP modified decks can be used for standard poker card play. 
 
Steps for Game Setup:

1. Remove the face cards and jokers from the card decks.

2. Place the Joker cards into the appropriate TA attack and DC proactive control decks or set aside depending on game mode.

3. Shuffle the TA and DC cards separately.

4. Each player randomly selects 6 Face Cards (Jack, Queen, King). Three (Clubs or Spades) represent their TA cyber assets and three (Hearts or Diamonds) represent their DC cyber assets. The three TA Face Cards are place face down on the players’ left side and the three DC Face Cards are place face down on the players’ right side.

5. The TA attack card draw stack is positioned face down on the players left behind the 3 TA Face Cards and the DC defense card draw stack is positioned face down on the players right behind the 3 DC Face Cards.

6. Each player self-deals 5 TA attack cards and 5 DC defense cards. Depending on game mode, the number of cards may be increased to 7.

6. The TA attack hand is positioned face down behind the player’s TA draw card stack and the DC defense hand is place face down positioned behind the player’s DC draw stack.

7. The TA card discard pile is on the far-left side of the game board and the DC card discard pile is on the far right of the game board.

8. Start game. 

Gameplay Overview:

* Coin flip determines which player starts the game with the first attack round.

* If the attack is successful, the TA player discards the attacking TA card and the defending player discards their failed defensive card, and the TA player moves to the next phase as described in the Attack Progression section. 

* If the attack is not successful, the TA player discards the attacking TA card and the defending player discards their successful defensive DC card and the attack round ends. The attack role now switches player. 
 
Card Draw Rules:

At the start of each attack round:

* The attacking player draws TA cards (if available) until they have 5 (or 7) TA cards in their hand.

* The attacking player must discard TA cards of their choosing if holding more than 5 (or 7).

* The defending player draws DC cards (if available) until they have 5 (or 7) cards in their hand.

* The defense player must discard DC cards of their choosing if holding more than 5 (or 7). 

* If there are insufficient cards in the attacking player’s TA draw deck, they may elect to “reboot” their TA deck by combining the TA discard pile with their hand, shuffle and deal themselves 5 (or 7) cards placing the remaining cards in the TA draw card stack position. The cost of performing a “reboot” is to add one damage count to any TA face card of their choice.

* If there are insufficient cards in the defending player’s DC draw deck, they may elect to “reboot” their DC deck by combining the DC discard pile with their hand, shuffle and deal themselves 5 (or 7) cards placing the remaining cards in the DC draw card stack position. The cost of performing a “reboot” is to add one damage count to any DC face card of their choice.
 
Attack Progression:

* Observation: The first attack on a face-card DC asset. If the exploit is successful, the card is turned face up.

* Weaponization phase: If the Observation exploit is successful, the TA moves to the Weaponization phase. The TA player may continue any appropriate attack on any DC asset of their choosing or draw 2 cards, end turn (stop additional attacks and end round without penalty) and permit the other player to commence their attack.

* Assessment: The second attack on a DC face card that has fallen victim to an Observation exploit and is now face-up. If successful, the card is rotated 90 degrees.

* Site Evaluation phase: If the Assessment attack is successful, the TA moves to the Site Evaluation phase. The TA player may continue any appropriate attack on any DC asset of their choosing or draw 2 cards, end turn (stop additional attacks and end round without penalty) and permit the other player to commence their attack.

* PWN: The third attack on a DC face card that has fallen victim to an Assessment attack and has been rotated 90 degrees. If the PWN attack is successful, the DC card is decommissioned and removed from play. A successful PWN attack ends the TA player’s attack round.

DC Bonus Card Draw:

If the TA attack fails, the DC defender may draw 2 additional DC cards and place them in their DC hand.

Face Card Damage Progression:

DC card damage must follow this sequence:

1. **Observation** – Card is turned face up.
2. **Assessment** – Card is rotated 90 degrees.
3. **PWN** – Card is decommissioned and removed from play.

If the TA attack fails, the TA player must select one of their 3 TA face cards and record damage following the face-up, rotation and decommission sequence.

Note: You cannot skip steps in this sequence — e.g., a face-down card must first be revealed before it can be rotated, and it must be rotated before it can be decommissioned.

Winning the Game:

A player wins by:

* TA Successfully breaching 2 of the defender’s 3 assets, which requires 6 successful attacks (Observation, Assessment, or PWN steps applied in sequence).

* DC: Successfully defending against 6 attack sequences resulting in 2 decommissioned TA face card assets. 

* Generally, the starting player has either won or lost the match by the time they are holding the 15th drawn card. For example, player #1 has won the coin flip and commences their attack. They successfully complete the Observation attack exploit and choose to skip the Assessment phase card draw and launch their Assessment attack which is successful. Player #1 now only has 3 (or 5) cards in their TA hand and (skipping the Site Evaluation phase card draw) launches the PWN attack on Player #2 which is successful. Player #1 now has only 2 (or 4) cards in their TA hand. However, since the attack round is over and before Player #2 commences their attack, each player completes the “card draw” as described above.

Card Matching Logic:

* TA cards (Clubs and Spades) are numbered (Ace through 10) and correspond to OWASP Top Ten Risk categories. About every 3 to 5 years, OWASP updates the Top 10 risks. The Ace card represents the Top 10 risk number 1.

* DC cards (Hearts and Diamonds) are similarly numbered (Ace through 10) and represent the OWASP Proactive Controls. About every 3 to 5 years, OWASP updates the Top 10 Proactive Controls. The Ace card represents the Top 10 Proactive Control number 1.

* Successful defense typically requires DC# = TA#.

* Jokers may override match requirements as wildcards.

Game Time: About 15–30 minutes per match.

Educational Use: Ideal for workshops, classroom training, and security awareness programs. Feel free to expand mechanics for longer sessions or multiple teams.
 

### Road Map
Project start* > preliminary coordination with the OWASP Education Committee* > complete working model of game* > coordination with the OWASP Top Ten team and OWASP Top Ten Proactive Controls team > refine working model of game > determine desired license > partner with a Game Manufacturer/Fulfillment Vendor > explore Educational Distribution Channels > launch with Minimal Risk via Print-on-Demand Platforms > pilot via Kickstarter or OWASP Chapters.

* - Completed

![image](https://github.com/user-attachments/assets/c958c63f-e0f6-480c-8998-d76bf1a8e87c)
