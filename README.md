# ToM_coding
Create a machine learning model that automatically categorise text for the presence of Theory of Mind elements.

* **T5 (Jago)** \
....

* **model_distilbert (Eli)** \
Predict values based on a NN with the DistilBERT language model. This NN tokenizes and transcribes the answered questions and feeds it into a neural network to predict the no. of ToM attributes per question. \

Network Architecture:
* Tokenized input -> DistilBERT (input -> 768)
* TanH (768 -> 768)
* ReLU (768 -> 768)
* FCN (768 -> 6)
* Dropout (0.1)

Contact for weights .pt file


