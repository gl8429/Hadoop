# Text Analyzer
In this project, we implement a text analyzer using Hadoop, which is a programming model and software framework for developing applications that concurrently process large scale data (Big Data) on distributed systems. The analyzer has to build a table that shows the occurrences of the words that appear together in the given text. The data set for this problem is the novel Pride and Prejudice. 

## Here is an example for calculating the occurrences:
* Text: “Mr. Bingley was good-looking and gentlemanlike; he had a pleasant countenance, and easy, unaffected manners.”
* Occurrences: For the word Bingley, “and” appears twice and “gentlemanlike” appears once. In this calculation, we say Bingley is a ‘contextword’; “and” and “gentlemanlike” are ‘query- words’. The other example: for the contextword and, “pleasant” appears once, “and” appears once (not zero times or twice).

## Output format
contextword1 <br />
\<queryword1, occurrence\> <br />
\<queryword2, occurrence\> <br />

contextword2 <br />
\<queryword1, occurrence\> <br />
\<queryword2, occurrence\><br />
