Convert Ballots
===============
This Utility allows automatic scanning and analysis of ballots for Schulze Voting. It takes the output of SDAPS and converts it for processing with schulze-simple. 

Usage
===============
Scan the ballots and analyse them using SDAPS. Pass the csv export as argument to convert_ballots. The utility will output a ballots.txt which can be used as input to the schulze-tools by the public software group: http://www.public-software-group.org/preftools.

Note: candidate.txt needs to be created manually

Disclaimer
===============
There is not guarantee for the correctness of the result. As with any elecrontic vote counting system, the ballots have to be counted by hand as well. 
