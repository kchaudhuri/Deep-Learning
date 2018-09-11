Emoji Predictor

- We are going to use word vector representations to build an Emoji predictor. 

- Scenario - Have you ever wanted to make your text messages more expressive? Your Emoji predictor will help you do that. So rather than writing "Congratulations on the promotion! Lets get coffee and talk. Love you!" the Emoji predictor can automatically turn this into "Congratulations on the promotion! 👍 Lets get coffee and talk. ☕️ Love you! ❤️"

- This will be a model which inputs a sentence (such as "Let's go see the baseball game tonight!") and finds the most appropriate emoji to be used with this sentence (⚾️). In many emoji interfaces, the need to remember that ❤️ is the "heart" symbol rather than the "love" symbol. But using word vectors, we will see that even if the training set explicitly relates only a few words to a particular emoji, the algorithm will be able to generalize and associate words in the test set to the same emoji even if those words don't even appear in the training set. This allows us to have an accurate classifier mapping from sentences to emojis, even using a small training set. 

- In this project, I'll start with a baseline model (v0) using word embeddings, then build a more sophisticated model (v1) that further incorporates an LSTM. 

- This project is part of Coursera's Deep Learning Specialization. Run the 'Emoji predictor.ipynb' file to see the project. 