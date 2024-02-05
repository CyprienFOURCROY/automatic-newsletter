# automatic-newsletter
From a dataset of articles, create an automatic newsletter using clusterisation over semantic embeddings and summarizing clusters with a powerful LLM.
# Dataset
A base of 589 articles from French newspapers, with thoses fields: URL, title, summary and date.
# Embedding
Vectorize summary using an embedder (SIM-CSE) in order to keep semantic meaning of articles 
# Clusterization
Regroup articles by theme using an algorithm  based on K-Means to get the articles of same meaning together
# Filter clusters
Keep only big clusters supposing many articles from a same subject means it constitutes a news. 
# Write NewsLetter 
Summarize the clusters using GPT-4. The context window is sufficiently large to have all the summaries in input.

