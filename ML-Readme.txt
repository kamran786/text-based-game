"TERRORIST STRIKE: CONDITION ZERO BEGINS!!

About:
TERRORIST STRIKE focuses on a battle between two teams; the terrorists and the Anti-terrorist Squad. Player objective is to kill all the terrorists hiding in the building and safely escape all the hostages. Terrorists are  hiding at different floors icluding lifts  and restrroms so navigate accordingly. The bullets are limited and you do not know how many terrorists are inside the building so be watchful and don't waste the bullets. Just follow the commands displayed on screen to move the player and perform action.

Win Condition:
In the limited  bullets assigned to the player, you have to kill all the terrorists.

Lose Condition:
If you run out of the bullets or selected to run out of the game, you lose.

Test Cases to check functions:
1. To verify that, the bullet count is reduced by 1 when a player types any invalid input(i.e. except 'Fire')
2. To verify that, the bullet count is reduced by 1 when a player types any valid input('Fire')
3. To verify that, terrorist count is reduced by 1 when a player types 'Fire'.
4. To verify that, step count is increased by 1 when a player navigates from one position to another.
5. To verify that, message 'Invalid characters entered!' is displayed when a player types any invalid option.
6. To verify that, win condition is met when all the terrorists are dead.
7. To verify that, game ends when a player selects to run out of the game.
8. To verify that, stat report is getting exported.
9. To verify that, all the steps taken by the player in the game are stored and at displayed at the end of the game when a player reaches a winning condition.
10. To verify that, game finishes when a player selects to exit the game.

Note: Imported packages import.time and import matplotlib.pyplot