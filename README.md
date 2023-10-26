# Multi-Document-Summarization
Abstractive Summarize multiple Vietnamese news using ViT5 using 3 methods:
- Rank-Concat: Extract k important sentences in each documents in cluster, merge all sentences and use that as an input for ViT5 Summarization
- Rank-Concat: Concat all documents in cluster, Extract k important sentences, and use that as an input for ViT5 Summarization
- Clustering: Clustering sentences in cluster into k clusters, extract sentence that have the nearest distance from centroid, and use that as an input for ViT5 Summarization