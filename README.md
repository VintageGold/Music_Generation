<img src="Images/UMBC_Graduate_School.jpg" width="150"> 

# Music_Generation
Read in Midi files and generate music based on 10 note sequences of Funk basslines and piano.

Conclusion: LSTM and GRU models should be trained for 350 epochs to allow for learning room as around 390 model accuracy falls.

Model Parameters

LSTM: batch_size = 256, epochs = 350, n = 1024, num_layers = 2, dropout = 0.3, learning_rate = 0.8, loss_func = nn.CrossEntropyLoss())

GRU:  batch_size = 256, epochs =390, n = 1024, num_layers = 2 ,dropout = 0.3, learning_rate = 0.8, loss_func = nn.CrossEntropyLoss())
