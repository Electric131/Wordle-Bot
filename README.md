# Wordle Bot
 A very simple wordle bot, nothing fancy.
 Note: This obviously ruins the point of wordle so if you want to play the game the correct way,
 do not use this. This script will reveal the word for that day.

 ## To use, either copy from main.js or below
 ```js
 if (window.localStorage['nyt-wordle-state']) alert("Today's word is '" + JSON.parse(window.localStorage['nyt-wordle-state']).solution + "'.");
 ```
