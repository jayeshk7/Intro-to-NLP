# Word level langugage modelling

This repository contains code for word level language modelling using PyTorch. I used all of shakespeare's sonnets as the dataset. The model was trained for 15 epochs with just randomly initialised vectors for word embeddings.

### Architecture 
Randomly initialised (learnable) 200 dim vectors were used as word representation.
Embedding vector was fed into a 2-layer LSTM cell with 1024 hidden size and 0.5 dropout on output of first LSTM layer. Output of this LSTM is used as input to the final linear layer which predicts the next word. 

### Results : 

morning it self to my love <br/>
you as the sun and make war <br/>
with me and beauty ’ s own <br/>
in thy love and this huge <br/>
we desire of thee my self thy beauty <br/>
of thy beauty still weep that is <br/>
so thou art so should look in <br/>
the time that thou art twice in <br/>
love is the day and in your <br/>
own hand takes from you should my<br/> 
self thy self with his beauty and <br/>
in my mind that which steals a <br/>
little of my mind and in thy <br/>
sweet semblance to be a woman<br/>

 I was honestly really impressed with these results, given I trained only for 15 epochs. I think it captured some important relationships between words. 