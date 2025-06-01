# WordSearch
Hello. This is a command line utility that allows a user to input an arbitrary amount
of words in sequence. Run `python3 wordsearch.py {name_of_wordsearch_grid}.txt` in the
working directory after extracting the zip file to there, and there will be created in that directory a text file for each word entered.
Each file will display the solution to that word (the word will be capitalized and in quotes to distinguish it).
There is contained in the zip file an example word search grid called puzzle1.txt, so you can 
run `python3 wordsearch.py puzzle1.txt` to see how the utility works. If you create a different word search grid file
in the same working directory, make sure to run the command with that file name instead. Run `rm results_of*.txt` to 
get rid of these files. If a word you entered is not in the grid you have in your command, then it will say so in the 
appropriate file
