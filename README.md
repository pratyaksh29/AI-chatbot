# AI-chatbot


- The program first iterates through the patterns and responses in the intents.json file.
- It tokenises each word from the input data, stems it and makes a list.
- Then we create a bag of words and one hot encode the words to check if it exists and then train the model.
- We get prediction from the model and find the most probable intent in the intensts.json file.
- It picks the most appropriate response from that intent/tag and outputs them.
