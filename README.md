# castle-swimmer-chatbot
A basic chatbot using Python and NLTK (Natural Language Toolkit) for answering simple questions about "Castle Swimmer Chapter 83-89: Unveiling New Prophecy." The chatbot will look for keywords in the user's input and provide predefined responses based on those keywords.

# Explanation
Response Mapping: We map specific questions (or keywords) to predefined responses. These responses provide answers about the plot, characters, and events in chapters 83-89 of Castle Swimmer.

Tokenization: We tokenize (split) the user input and the questions into individual words using NLTK's word_tokenize. This allows us to match keywords regardless of word order.

Simple Keyword Matching: We use a basic approach where we check if all the words in a predefined question are found in the user's input. If they match, we return the corresponding response.

Loop for Interaction: The chatbot runs in a loop, waiting for user input. It responds to questions until the user types "exit", "quit", or "bye".
