# Intro to NLP
 
My main motivation behind studying NLP was to mainly understand the architectural innovations of this field and apply it in Partially Observed settings in Reinforcement learning.
Although, along the way I kind of enjoyed studying this and implemented some stuff.

This repository contains PyTorch implementations of :
1. [Word Embeddings](https://github.com/jayeshk7/Intro-to-NLP/tree/master/Word%20embeddings)
2. [Character level language modelling of Pokemon names](https://github.com/jayeshk7/Intro-to-NLP/tree/master/Language%20Models/Character%20level)
3. [Word level language modelling using Shakespeare's Sonnets](https://github.com/jayeshk7/Intro-to-NLP/tree/master/Language%20Models/Word%20LM)


## Results

### 1. Word Embeddings



### 2. Language modelling on Pokemon names

Select examples of generated Pokemon names. 

acgaeria 
iciraano
oteta 
qilornoe
sitorenn
xyenrai
yaoraoni
zeronaar

Overall, the results were quite underwhelming. I think the main reason could be one/all of the below :
1. The dataset is just weird. I agree Pokemon names are really cool but they don't really follow any trend and are mostly random alphabets with some vowels here and there.
2. I was too impatient and didn't train long enough (also quite plausible)

### 3. Language modelling on Shakespeare's Sonnets

 morning it self to my love 
 you as the sun and make war 
 with me and beauty ’ s own 
 in thy love and this huge we 
 desire of thee my self thy beauty 
 of thy beauty still weep that is 
 so thou art so should look in 
 the time that thou art twice in 
 love is the day and in your 
 own hand takes from you should my 
 self thy self with his beauty and 
 in my mind that which steals a 
 little of my mind and in thy 
 sweet semblance to be a woman

 I was honestly really impressed with these results, given I trained only for 15 epochs. I think it captured some important relationships between words. 

## Resources
- Stanford CS224n : Natural language processing using deep learning([Lectures](https://www.youtube.com/playlist?list=PLoROMvodv4rOhcuXMZkNm7j3fVwBBY42z))([website](http://web.stanford.edu/class/cs224n/))