# HashCracker

The algorithm for HashCracker is relatively simple, and is pictured below.
![HashCracker algorithm for generating password guesses](https://i.imgur.com/qy10SWJ.png)

It is necessary to be familiar with a few terms in order to understand this algorithm.

----

Guess Password: A password generated by the program that is then hashed and compared
to the hash the user is trying to crack.

Root Password: A combination of one or more words either randomly generated or
socially engineered. The root password serves as the base for all of the alterations
that will be applied to it.

Alteration: Any change to the root password, which may be adding characters, removing
characters, or changing characters.

Number Alteration: Any change to the root password that involves appending numbers
to the beginning or ending of the root password.

Symbol Alteration: Any change to the root password that involves appending symbols
to the beginning or ending of the root password, or replacing letters with symbols.
This also includes adding hyphens and underscores to the spaces between letters of
the root password.

Letter Alteration: Checking capitalization (most often the first character of the
password).

----

