# Letterpressing
Find playable words in a game of Letterpress. Test at http://themize.github.io/Letterpressing/

Type in the letters of the board (or honestly, any string of letters) and it will check them against the dictionary. It will produce a list of all the words in the Letterpress dictionary that can be made using those letters, ordered by length.

It's pretty slow, since it's all done in client-side javascript; might take 30+ seconds to produce the list of allowed words.


Letterpress is an iOS game by Loren Brichter http://www.atebits.com/letterpress/
For the dictionary of playable words, I used the official word list available at https://github.com/atebits/Words