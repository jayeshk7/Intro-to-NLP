# Language Modelling

This is where NLP gets exciting (unless your results don't make sense). The basic idea behind RNN is to shared parameters so model complexity doesn't increase with inputs. There are some theoretical works on why vanilla RNNs are not the best choice (one of the first papers demonstrating this is [here](http://ai.dinfo.unifi.it/paolo//ps/tnn-94-gradient.pdf)), which led to architectural innovations like LSTM and GRU. 

### Resources 
Lectures : Stanford CS224n [Lecture 5 and 6](https://www.youtube.com/playlist?list=PLoROMvodv4rOhcuXMZkNm7j3fVwBBY42z). You can even watch Lecture 7 if you're feelin' it, it's about machine translation and attention.

These are some papers/blogs which I found useful :
1. [On the difficulty of training RNNs](https://arxiv.org/pdf/1211.5063.pdf)
2. [Understanding LSTM Networks](http://colah.github.io/posts/2015-08-Understanding-LSTMs/)
3. [The unreasonable effectiveness of RNNs](http://karpathy.github.io/2015/05/21/rnn-effectiveness/) 

I understand the first paper can be tough. And I would even suggest skipping it. I'll try to write a simple summary of the paper soon!

You can find the dataset I used for training word level language models [here](https://github.com/jayeshk7/Intro-to-NLP/blob/master/Language%20Models/Dataset/shakespeare%20sonnets.txt).