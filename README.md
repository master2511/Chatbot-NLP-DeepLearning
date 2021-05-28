# Chatbot-NLP-DeepLearning
In this project I have used some simple tokenization and stemming and bag of works concept to train my DeepLearning model.

There are 4 python files.
1) Chatbot_helper_functions : This includes the tokenize, stem and bag_of_words function, which is used to create the dataset.
2) Chatbot_model : The model I have used is a simple Neural Network with two hidden layers.
3) Chatbot_train : I am using the intents.json file to train my model
                   loss function : Cross Entropy loss
                   weight update : Adam optimizer
                   I have achieved a loss of 0.001, at the end of training.

4) Chatbot_chat : The trained model is saved in the data.pth file, which is used to implement the chat.

I have also included the trained model and intents.json file in the repository.
                  
