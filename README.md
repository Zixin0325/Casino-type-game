# Casino-type-game

design a casino-type game using the random number generator on the Basys 3 board using Vivado.

A sample play of the game is as follows:

1) The player starts to generate the random numbers on two of the digits.
 
2) The player then taps the Roll button. If the current two hex numbers are equal then "UI" is displayed, if not, then "LO" is displayed (on the other remaining two digits). The "UI" or "LO" is still displayed until the next tap of the Roll button. The two hex numbers are still changing throughout this entire process.

3) The player can then tap the Roll button again and the (new) current two hex numbers are compared again to see if the other two digits should display "UI" or "LO".

For simplicity "LO" can be displayed before the first tap of the roll button.

Of course, the player can always see the value of the hex digits, and thus tap the Roll button at the right time in order to win or lose the game, but this is done for debugging purposes.
