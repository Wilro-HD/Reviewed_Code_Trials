# Notes for review 537374 on 2023-05-10

string="you can have data without information,but you cannot have information without data"
letters=list( "abcdefghijklmnopqrsvwxyz")
 
letters_frequency={letter: 0 for letter in letters}
 
# Here I changed the name of the temporary variable in the for loop so that it does not it is not the same as the variable name for our list of letters
for char in string:
    # We now want to check if that new temp variable is found in our frequency dictionary (specifically in the keys)
    if char in letters_frequency.keys():
        letters_frequency[char] += 1
    # I removed the else, since if the char is not in the frequency dict, we dont want to do anything

# Here we are using the key value pairs of the dictionary and not the list of alphabet letters
for key,value in letters_frequency.items():
    # Lastly we only want to print the frequencies of letters > 0
    if value > 0:
        # If you use f-string syntax we need to specify that the quoted text is a f-string (f"text {variable}")
        print(f"{key} : {value} ")
