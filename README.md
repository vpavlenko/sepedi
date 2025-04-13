Starting from Autshumato bilingual corpus, rearrange all Sepedi sentences in the order of reading that simplifies learning of new words.

The idea:
- stem all words
- assign each word the number of sentences that its stem is in
- use min(counts) for word in sentence as ordering number
- if two words give equal number: sort by pair (count, stem itself) to group one stem together 


# Stemming

idea: stem out all productive verb affixes
