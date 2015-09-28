# Welcome to the Python Workshop 

## Powered by RMK Coding Club

- Write a function translate() that will translate a text into "rövarspråket" (Swedish for "robber's language"). That is, double every consonant and place an occurrence of "o" in between. For example, translate("this is fun") should return the string "tothohisos isos fofunon".

- Define a procedure histogram() that takes a list of integers and prints a histogram to the screen. For example, histogram([4, 9, 7]) should print the following:

 ```
 ****
 *********
 *******
 ```

- Write a function find_longest_word() that takes a list of words and returns the length of the longest one.

- Write a function char_freq() that takes a string and builds a frequency listing of the characters contained in it. Represent the frequency listing as a Python dictionary. Try it with something like char_freq("abbabcbdbabdbdbabababcbcbab").

- Define a simple "spelling correction" function correct() that takes a string and sees to it that 1) two or more occurrences of the space character is compressed into one, and 2) inserts an extra space after a period if the period is directly followed by a letter. E.g. correct("This   is  very funny  and    cool.Indeed!") should return "This is very funny and cool. Indeed!" Tip: Use regular expressions!

- Define a function overlapping() that takes two lists and returns the common elements only once.

- Write a program that maps a list of words into a list of integers representing the lengths of the correponding words.

- A pangram is a sentence that contains all the letters of the English alphabet at least once, for example: The quick brown fox jumps over the lazy dog. Your task here is to write a function to check a sentence to see if it is a pangram or not.

- The third person singular verb form in English is distinguished by the suffix -s, which is added to the stem of the infinitive form: run -> runs. A simple set of rules can be given as follows:
 
 If the verb ends in y, remove it and add ies

 If the verb ends in o, ch, s, sh, x or z, add es

 By default just add s

 Your task in this exercise is to define a function make_3sg_form() which given a verb in infinitive form returns its third person singular form. Test your function with words like try, brush, run and fix. Note however that the rules must be regarded as heuristic, in the sense that you must not expect them to work for all cases. Tip: Check out the string method endswith().

- Make a two-player Rock-Paper-Scissors game. (Hint: Ask for player plays (using input), compare them, print out a message of congratulations to the winner, and ask if the players want to start a new game)

 Remember the rules:

 Rock beats scissors
 Scissors beats paper
 Paper beats rock

- Write a program (function!) that takes a list and returns a new list that contains all the elements of the first list minus all the duplicates.

- Represent a small bilingual lexicon as a Python dictionary in the following fashion {"God":"kadavul", "time":"neram", "sleep":"thookam", "food":"saapadu"} and use it to translate strings from English into Tamil/Telugu. That is, write a function translate() that takes a list of English words and returns a list of Tamil/Telugu words.

- Write a program (using functions!) that asks the user for a long string containing multiple words. Print back to the user the same string, except with the words in backwards order. For example:
I/p : My name is Michele
O/p :Michele is name My

- Write a function filter_long_words() that takes a list of words and an integer n and returns the list of words that are longer than n.

- In English, the present participle is formed by adding the suffix -ing to the infinite form: go -> going. A simple set of heuristic rules can be given as follows:

 If the verb ends in e, drop the e and add ing (if not exception: be, see, flee, knee, etc.)
 If the verb ends in ie, change ie to y and add ing
 For words consisting of consonant-vowel-consonant, double the final letter before adding ing
 By default just add ing
Your task in this exercise is to define a function make_ing_form() which given a verb in infinitive form returns its present participle form. Test your function with words such as lie, see, move and hug.

