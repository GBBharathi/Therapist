# Therapist
This code is a Python implementation of a simple chatbot using regular expressions and NLTK library. The chatbot responds to various user inputs by matching them with the predefined patterns and corresponding responses. It also uses reflections to map first and second person expressions to create a more natural conversation.

The chatbot has a set of predefined pairs, where each pair consists of a regular expression pattern and a list of possible responses. When a user input is received, the chatbot checks each pattern to see if it matches the input. If a pattern matches, the chatbot picks a random response from the list of possible responses and substitutes any wildcards in the response with the appropriate parts of the user input.

The chatbot also has a method to handle sentiment analysis using the SentimentIntensityAnalyzer class from NLTK. However, this method is not used in the current implementation.

The converse() method of the Chat class runs the chatbot in a loop until the user enters the quit command. The user input is stripped of any trailing exclamation marks or periods, and is passed to the respond() method of the Chat class. The chatbot's response is printed to the console, and the loop continues until the user enters the quit command.
