# Text-Generation---Markov-Chains
Markov Chains are a mathematical way of representing how systems change over time. Markov chains can be used for basic text generation. Think about every word in a corpus as a state. We can make a simple assumption that the next word is only dependent on the previous word - which is the basic assumption of a Markov chain.  

To create a Markov Chain , we create a dictionary for a corpus where the keys are the current state and the values are the options for the nest state. We then write a function to randomly generate next terms.  

Markov chains don't generate text as well as deep learning (LSTMs), but it's a good (and fun!) start.
