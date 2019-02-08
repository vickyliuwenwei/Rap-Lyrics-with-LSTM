# Rap-Lyrics-with-LSTM
Generate Rap Lyrics with RNN
Feed artist specific rap lyrics into LSTM and generate artist specific songs character by character.

## Data:
380,000+ lyrics from MetroLyrics, it contains around 380,000 songs for different artists and genre from 1960 to 2016. The artists of our choice are Drake, Eminem, and Tupac because they have created raps that have strong personal style are successful both artistically and commercially.

### Pre-processing:
Transform the text into vectors with numerical values. We use a vector of length 63 with 62 0’s and one 1 to represent the character.

## Model Tuning:
Using LSTM model and feeding the model with 40 characters. Adding different layers, and different parameters for the learning rate, diveristy, and epoch. With the size of data, AWS is used to train LSTM models and tune using grid search appraoch.
