<img src="Images/UMBC_Graduate_School.jpg" width="150"> 

# Music_Generation
Read in Funk basslines Midi files and generate music based on 10 note sequences by using the 10 note sequences to predict the next 10 note sequences

# Conclusion
LSTM and GRU models should be trained for 350 epochs to allow for learning room as around 390 model accuracy falls.

# Example Song
https://soundcloud.com/vintagegold123/bass-11-robot-notes-sample

# Model Parameters

LSTM: batch_size = 256, epochs = 350, n = 1024, num_layers = 2, dropout = 0.3, learning_rate = 0.8, loss_func = nn.CrossEntropyLoss())

GRU:  batch_size = 256, epochs =390, n = 1024, num_layers = 2 ,dropout = 0.3, learning_rate = 0.8, loss_func = nn.CrossEntropyLoss())
