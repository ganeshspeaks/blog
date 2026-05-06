---
layout: post
title: "I Hate Back Propagation in ML"
tags: ["experience", "ml"]
---

I have learned about backpropagation, neural networks, and several activation functions. To be honest, I hate this approach. I am not an AI expert, but fundamentally this is the wrong way to train a machine learning model. Why let the model predict garbage values, then punish it until it reaches an accurate answer?

Since this is supervised learning, why not teach the model before letting it guess? Same as how a child learns. They know nothing, so they guess nothing. We tell them, this is a cat, that is a dog, then they start speaking.
This is why I am doing research in metric spaces, topology, and probability theory. I have created a metric that measures similarity between two sets of information without using cosine similarity or embeddings, and it works pretty well. It outperforms embedding-based semantic similarity on small datasets. It will probably struggle on large datasets, but I am working on that. Eventually I want to make it GPU-friendly.
