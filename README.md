# Personal Code Auto-Completion Model

A character-level LSTM model used to learn your own personal coding style based on the code that you wrote in the past and provide a code auto-completion function. 

For example, if the user is a ML developer, then given "from torc", the model will be able to predict "from torch.nn.functional as F" which is very likely what the user is going to enter. 

Note that the training data (your past code) needs to be preprocessed and the comments has to be removed before it is passed into the training file.  
