## RNN
* Hidden node is feedback to itself.
* References:
  * Unrolling of RNN involves forward propogation of hidden state in a loop:
  * 1 time-step may include multiple samples: e.g. [The weather] is sunny, here [The weather] can represent single time-step:
    * https://towardsdatascience.com/from-a-lstm-cell-to-a-multilayer-lstm-network-with-pytorch-2899eb5696f3
  * Why weights are shared acrss time-steps? If not shared, computationally intensive and overfitting.
    * https://stats.stackexchange.com/questions/221513/why-are-the-weights-of-rnn-lstm-networks-shared-across-time
  * https://towardsdatascience.com/rnn-recurrent-neural-networks-how-to-successfully-model-sequential-data-in-python-5a0b9e494f92
  * https://towardsdatascience.com/step-by-step-understanding-lstm-autoencoder-layers-ffab055b6352
  * https://blog.mlreview.com/understanding-lstm-and-its-diagrams-37e2f46f1714
  * https://towardsdatascience.com/temporal-loops-intro-to-recurrent-neural-networks-for-time-series-forecasting-in-python-b0398963dc1f
  * https://cnvrg.io/pytorch-lstm/
  * https://towardsdatascience.com/whats-happening-in-my-lstm-layer-dd8110ecc52f
  * https://towardsdatascience.com/illustrated-guide-to-lstms-and-gru-s-a-step-by-step-explanation-44e9eb85bf21
  * https://medium.datadriveninvestor.com/recurrent-neural-network-rnn-52dd4f01b7e8 (open at home)
  * https://stackoverflow.com/questions/47865034/recurrent-nns-whats-the-point-of-parameter-sharing-doesnt-padding-do-the-tri
 
## To be read tommorow
* https://stackoverflow.com/questions/44381450/doubts-regarding-batch-size-and-time-steps-in-rnn
* https://keras.io/api/layers/recurrent_layers/simple_rnn/
  * **Draw the RNN in example code**
* Find better visualization of Keras models
* Backpropogation
* BPTT
