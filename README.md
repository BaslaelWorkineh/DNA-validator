Documentaion for the DNA validator

1 Command-Line Usage Check: Checks if the script is being used correctly from the command line. It expects two arguments: the path to a CSV file containing DNA data and the path to a text file containing a DNA sequence.

2 Reading Database File: Reads the CSV database file into a variable. The database file contains information about DNA sequences and their corresponding profiles.

3 Reading DNA Sequence File: Reads the DNA sequence file into a variable. This file contains the DNA sequence that needs to be analyzed.

4 Finding Longest Match of Each STR in DNA Sequence: Compares the DNA sequence against each Short Tandem Repeat (STR) specified in the database and finds the longest match for each STR.

5 Checking Database for Matching Profiles: Compares the results of the analysis with the profiles in the database. If there's a match, it prints the name associated with the matching profile.

6 Longest Match Function: Defines a function called longest_match that calculates the length of the longest run of a subsequence (STR) in a given sequence.

7 Main Function: Calls the main function to execute the script.
