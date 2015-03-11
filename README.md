# novel_generator

Main scripts:

-	generate_Doyle.m and generate_Austen.m are the main scripts.

Functions:

	get_row_data.m reads the .txt novels.
	seperate_special_characters.m seperates words from special charachters.
	seperate_special_characters.m seperates words from special characters and creates the history of words(unigrams).
	create_bigram_history.m creates the history of bigrams.
	create_trigram_history.m creates the history of trigrams.
	create_dictionary.m creates a dictionary given a certain vector of words that can be repeated.
	generate_MM1.m creates a probability transition matrix M where M(i,j) is the transition probability from the word i to the word j.
	generate_MM2.m creates a probability transition matrix M where M(i,j) is the transition probability from the bigram i to the word j.
	generate_MM3.m creates a probability transition matrix M where M(i,j) is the transition probability from the trigram i to the word j.
generate_novel3.m generates a pseudo novel of a given author using 3rd, 2nd, and 1st MM predictions.
