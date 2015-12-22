# ANOTHER HANGMAN BOT FOR TELEGRAM
Yep! Another one...

Start with
> npm install

##THIS DOC NEED A ENGLISH REVISION!!!

## Sub-projects (progress)
* Commands
	* [ ] "/open" and "/abrir" to open a new game room in the 'Telegram Room/Group'.
	* [ ] "/start" and "/começar" to start the game (availble only for the game room owner).
	* [ ] "/end" and "/encerrar" to cancel a running game (availble only for the game room owner).
	* [ ] "/join" and "/entrar" to register participacion in a game.
	* [ ] "/guess" and "/chutar" to guess a letter.
	* [ ] "/gamble" and "/apostar" to guess a word.
	* [ ] "/suggest" and "/sugerir" to suggest a tuple <word>;<hint>
	* [ ] "/rank" and "/placar" to see the all time rank for the 'Telegram Room/Group'.
	* [ ] "/hint" and "/dica" to see the hint from a running game.
	* [ ] "/letters" and "/letras" to see all the already guessed letters.


## Rules
* Any wrong letter guess spends a life.
* Any wrong word guess spends remove that player from the game.
* Any right letter guess reveals the guessed letter in the secret word.
* The first player to right guess the secret word, wins the game.
* Inactivity will be punished with player losing his turn.

## Score
* The player who guess a letter correctly, receives 5 points for each of that letter in the secret word.
* The player who guess a word correctly, receives 25 points.
* The player who guess a letter incorrectly, lose 5 points.
* The player who guess a word incorrectly, lose 25 points.
* The player who lose your turn for inactivity lose 1 point.