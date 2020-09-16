# Language Modelling

This is where NLP gets exciting (unless your results don't make sense). Apart from the N-gram models and stuff, I found recurrent networks to be one of the nicest ideas I've studied. There are some theoretical works on why vanilla RNNs are not the best choice (one of the first papers demonstrating this is [this](http://ai.dinfo.unifi.it/paolo//ps/tnn-94-gradient.pdf)), which led to architectural innovations like LSTM and GRU. 

### Resources 
Lectures : Stanford CS224n [Lecture 5 and 6](https://www.youtube.com/playlist?list=PLoROMvodv4rOhcuXMZkNm7j3fVwBBY42z). You can even watch Lecture 7 if you're feelin' it, it's about machine translation and attention.

These are some papers/blogs which I found useful :
1. [On the difficulty of training RNNs](https://arxiv.org/pdf/1211.5063.pdf)
2. [Understanding LSTM Networks](http://colah.github.io/posts/2015-08-Understanding-LSTMs/)
3. [The unreasonable effectiveness of RNNs](http://karpathy.github.io/2015/05/21/rnn-effectiveness/) 

I understand the first paper I mentioned can be tough for some people. And I would even suggest skipping it. I'll try to write a simple summary of the paper soon!

You can find the dataset I used for training word level language models [here](https://github.com/jayeshk7/Intro-to-NLP/blob/master/Language%20Models/Dataset/shakespeare%20sonnets.txt).
Feel free to open a PR if you find any bugs (or even improvements) in my code :)