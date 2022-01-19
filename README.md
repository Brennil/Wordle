# Wordle Helper
A little helper to narrow down your next word guess based on the clues unveiled in previous guesses.

To play one round, use the `play()` function. This function takes in two arguments:
* `guess`: the 5-word you just guessed
* `result`: a 5-character string that describes the colour of the letters in your guess. A green letter is depicted by 'g', a yellow letter is depicted by 'y', and a grey/black letter is depicted with a 'b'.

E.g. If I guess "world" and get the result of "black, green, yellow, yellow, black", I will enter the code:
`play('world','bgyyb')`

When you have selected a word from the resulting list (sorted from highest frequency to lowest) and played it for the next result, you can call the `play()` function again.

Credits: Inspired by [this post](http://estebanmoro.org/post/2022-01-10-wordle/).
