# American English Dictionary
The purpose of this repository is to store all information for the American English Dictionary used by the[NLP ENGINE](https://github.com/VisualText/nlp-engine) including analyzers that create dictionary knowledge and an anlyzer to generate the KB for the entire dictionary (not yet implemented).

There are two main folders in the repository:
1. **Analyzers:** a repository for all analyzers that are related to this dictionary including the main analyzer that generates the final dictionary kb
2. **Data:** the location of all the dictionary knowledge in simple text formats
 
## History
The current dictionary what is used in the NLP Engine and by VisualText comes from [WordNet from Princeton](https://wordnet.princeton.edu/). It hasn't been updated since 2012 or there about.

## Short Term Goals
Short term goals for the English US dictionary:
- update and enhance the vocabulary
- number values
- gender
- other syntactic features like count etc.

## Text Repository
The purpose of the text repository is to store all the dictionary information in the simplest manner from which the KB will be generated with a special KB generator analyzer.

## Long Term Goals
- create a dictionary where each meaning for each word is deliniated
- create a faster dictionary lookup in the [NLP ENGINE](https://github.com/VisualText/nlp-engine)
