## Spelling Bee

**Project description:** 
The project aims at learning a model that can take in the pronunciation of a word as a list of phonemes, and try to spell it. One difficulty is this model will be evaluated on how well it can spell words that it has never seen before

### 1. Architecture Details

The model consists of Gated Recurrent Units, Long Short Term Memory and MultiRNN cells. These are used they preserve information that the model has learnt over different durations, which is necessary to predict the correct spelling of the phonemes.

<img src="images/spelling/gru.png?raw=true"/>
<img src="images/spelling/LSTM.jpg?raw=true"/>

### 2. Features

    <ul> Created model from scratch including the batch iterator and feed funtions.</ul>
    <ul> Acheived the accuracy of 96.2%.</ul>
    <ul> Subimtted as my semester project in Third year of college.

