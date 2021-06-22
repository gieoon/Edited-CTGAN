I am rewriting/copying the CTGAN framework (Link to come soon) and in the process adding comments and trying to understand how it works.

I've constantly been reading open source models and doing machine learning courses but still find it incredulous to create one on my own, so I think I need to go through a model step by step to understand it, dissect it, and see how it works to be able to reproduce it and modify it at will.

I will be writing questions and what I think the answers are down as I go through.

# Questions & Answers:

--------------------------------

- What is LeakyReLU?
- What are activation functions?
- What are embedding_dimensions?
- What are the different depths of the layers
- How is gradient descent calculated?
- How does varying the generator and discriminator learning_rates change the output?
- How is loss calculated?
- Is it possible to add extra layers in between?
- What happens if dropout amount is changed?
- How are non-gaussian, long-tail, modal distributions modelled, does the data pick this up?
- How are the conditions read?