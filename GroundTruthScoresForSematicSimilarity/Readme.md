# Semantic Similarity
The data for semantic similarity has 5 different files in it where each file represents the model used.
For each of the section there are csv files that have the following list of columns with description to it:
1. Score -> Model generated score for a given pair of policy extract and template for the associated verb (score range from -1.0 - 1.0 depending on the model)
2. Decision -> Human evaluation for the generated score to make the score either 0 or 1.

# Model descriptions
1. chat.csv -> end-to-end ChatGPT
2. chatph2.csv -> GPT 3.5-Turbo
3. davin -> GPT-Davinci  
4. Lm12.csv -> Sentence BERT (Microsoft all-MiniLM-L12-v2)
5. mpnet.csv - Sentence BERT (Microsoft all-mpnet-base-v2)
