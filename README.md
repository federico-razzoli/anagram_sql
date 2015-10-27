anagram_sql
===========

Anagram game, implemented with MariaDB/MySQL Stored Procedures... without a particular reason :) 

Hot to play
===========

To start a game, type:

CALL new();

To try guessing the word, type:

CALL guess('word');

By default, anagrams are made from any English word (that is in my database).
I speak Italian, Spanish and German too.
To change the language and set a minimum/maximum length for the words:

CALL set_options('es', 4, 10);

Use NULL to avoid minimum or maximum bound.


