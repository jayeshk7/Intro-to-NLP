# Character Level Language Modelling

In character language modelling our model predicts the next character instead of the next word. I used all the Pokemon names as my dataset and trained for around 80 epochs.

### Architecture

> **1. One hot character vectors**  
**2. 2-layer LSTM with 512 hidden units**  
**3. Fully connected layer for prediction**  

### Results

Some examples of generated Pokemon names. 

iciraano<br/>
qilornoe<br/>
sitorenn<br/>
xyenrai<br/>
yaoraoni<br/>
zeronaar<br/>

Overall, the results were quite underwhelming. I think the main reason could be one/all of the below :
1. The dataset is just weird. I agree Pokemon names are really cool but they don't really follow any trend and are mostly random alphabets with some vowels here and there.
2. I was too impatient and didn't train long enough 

You can also download the weights of my model and train it further. Let me know if it results in better names!