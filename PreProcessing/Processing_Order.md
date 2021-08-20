# Take input in lines or words
***

## 1.Accented Character:
### `accent_rm_data_Singleline(line)`
    Takes a string as input an return a string removing accented character.
    // doing this first may improve speed.
### `accent_rm_data_Multiline(lines_list)`
    Applies accent_rm_data_Singleline(line) for a list of string. 
    Input: structure: List, type: String
    Output: structure: List, type: String
***

## 2.Removing Twitter Handel
### `Remove_Mention_Singleline(line, replacer = 'user')`
    Takes a string as input an return a string replacing twitter handel mentions with the given replacer string.

    like, 
        input: @xyz having a wonderfulday!
        output: user having a wonderfullday!


## Tokanization:
	if input is in Lines:
		// tokanize a line and feed it into a List "DATA_LIST"
		    returns a LIST
	else make every word a list


## HashTag Segmentation:
    // A function will go through a list of words "DATA_LIST"
        returns a LIST
    
## Emojis & Emoticons to text:
    // A function will go through a list of words "DATA_LIST"
        returns a LIST

## URL Identification Expansion/Normalization:
    // A function will go through a list of words "DATA_LIST"
        returns a LIST
    // things to take in consideration -- 
            // "DATA_LIST" is valid in this Section if Tokenaization done using
                Tweettokenizer

## Special Character Removal
    // A function will go through a list of words "DATA_LIST"
        returns a LIST

## Lexical Normalization
    // A function will go through a list of words "DATA_LIST"
        returns a LIST
        
        // Keep a process to add extra word as list

## Stemming
    A function will go through a list of words "DATA_LIST"
        returns a LIST 
        
        // Build Stemmer in Function and return it as an object to keep flaxibility
        
        // Make another function to run the process
        
        {Whole process can be wrapped in a class} (try it)
        
## Stop-Word Removal
    // A function will go through a list of words "DATA_LIST"
        returns a LIST
