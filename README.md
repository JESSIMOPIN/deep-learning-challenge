# deep-learning-challenge

Model report:

The main purpose was to create a binary classifier using a neural network to predict the success of funding applicants for Alphabet Soup.

What was done in the code.
1. Data prep. 

The less useful identification column were "EIN" and "Name" so were taken out of the data.
After that, it was critical to work on the categorical variables, the main ones used being "Application type" and "Classification" which were both one-hot encoded using pd.get dummies.
Last but not least the dataset was split into training and testing to, then, applied the standard scaling.

2. Model architecture
The most successful model used three hidden layers; first with 20 neurons, second and third with 10. Additional layers and additional neurons were tested but were not as successful as the optimized model. 

This model was compiled using binary-cross entropy loss and the Adam optimizer.

3. Results.
The model achieved an accuracy of 60% on the test set


Resources used
https://www.tensorflow.org/model_optimization/guide?hl=es-419
https://www.geeksforgeeks.org/python-pandas-get_dummies-method/
https://www.tensorflow.org/api_docs/python/tf/keras/Model
https://www.tensorflow.org/guide/keras/training_with_built_in_methods
https://www.codificandobits.com/blog/funcion-de-activacion/
Stack overflow.
