## Project Parts-of-Speech Tagging (Viterbi algorithm) 

This project is devoted to assigning a part-of-speech tag (Noun, Verb, Adjective...) to each word in an input text. Tagging is difficult because some words can represent more than one part of speech at different times. They are **Ambiguous**. Let's look at the following example:

- The whole team played **well**. [adverb]
- You are doing **well** for yourself. [adjective]
- **Well**, this assignment took me forever to complete. [interjection]
- The **well** is dry. [noun]
- Tears were beginning to **well** in her eyes. [verb]

The structure of the project is as follows:

- Computing the transition matrix A in a Hidden Markov Model
- Computing the emission matrix B in a Hidden Markov Model
- Computing the Viterbi algorithm
- Computing the accuracy of the model

