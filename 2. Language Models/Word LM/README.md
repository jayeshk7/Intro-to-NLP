# Word level langugage modelling

I used all of Shakespeare's amazing sonnets as the dataset. The model was trained for 15 epochs with randomly initialised word vectors.

### Architecture and Plots

> **1. 200 dim word vectors**  
**2. 2-layer LSTM with 1024 hidden units**  
**3. Fully connected layer for prediction**  

<br/>
**Training loss V/S iterations (after gaussian smoothing)**

![loss](https://github.com/jayeshk7/Intro-to-NLP/blob/master/2.%20Language%20Models/Word%20LM/smooth%20loss.png)

### Results : 

>morning it self to my love <br/>
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

Somewhat reasonable result, given I only trained for 15 epochs. More training should hopefully result in more coherent sonnets.
