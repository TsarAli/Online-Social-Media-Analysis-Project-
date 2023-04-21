## The following is my project from when I took the Online Social Media Analysis course at IIT.

* The dataset that was used is uploaded along with the code that was used. 

### Dataset description:

- The dataset is a collection of fake news samples and the responses from users who saw that:

    - agreed: B talks about the same fake news as A.
    - disagreed: B refutes the fake news in A
    - unrelated: B is unrelated to A.

### Code Description:

- The python notebook uses Tensorflow & Keras to train 4 networks:
  
  - Simple neural network
  - A bidirectional LSTM(an RNN basically)
  - A More complex neural network that utilizes droput and more layers than the first simple neural network
  - A transformer network
 
 The code will also preprocess the data using one-hot encoding and has values that can be changed. The default vocab number is 100 but if you have the resources you can use as much as you want(I used 1000 vocab when I was testing this). The batch size and number of epohcs can also be changed. 
 
 When the preprocessing and training has been complete all models and ensembled to see the resulting confusion matrix.
