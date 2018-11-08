# NumberWizard-UnityConsole, guessing game

Developed on Windows 10 with Unity Version 2018.2.6.f1
Game played in the Unity Editor, Output on Console, Input Arrow-Keys UP, DOWN and ENTER

Desc: A player chooses a number (secret) between 1 and 1000. 
The system guesses a number (min+max)/2.
As long as the guess isn't equal to the secret number the player confirms with with the Arrow-Keys UP, DOWN and the ENTER-Key. 
After each system's guess, the player confirms with arrow key UP when his/her number is higher as the guessed one with
arrow key DOWN when the number is lower is the guessed one.
If the player's number is equal to the guessed one, the player hits the ENTER key. 
The game ends, when no more guesses are possible or the system guesses the player's number. 
----------------------
GameMechanics: 

guess = ( min + max ) / 2

if secret number < guess --> max = guess

if secret nubmer > guess --> min = guess

![Image game mech Number wizard](./Screenshots/gameMech-nbrw.jpg)

------------------------
