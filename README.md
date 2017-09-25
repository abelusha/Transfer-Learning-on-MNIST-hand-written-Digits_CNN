# Transfer-Learning-on-MNIST

In this notebook, I treid to classify the digitst 5-9 by using a model that is trained on the
digits 0-4 by emplying a techinque called transfer learning.

I used two approaches.
1) save the optimized weights from the initial model (trained on the digits 0-4) and
  use them to classify the digitst 5-9 which the model had never seen.
  In this technique rather than initilize the weights randomly I used the pretrained weights
  
2) The second apprach is to freez the first layers of the model, which usually is called feature layers.
Then the model only trains, the last classification layes in classifying the digits 5-9.

**Results:**


![result_3](https://user-images.githubusercontent.com/12251952/30809512-446a758a-a202-11e7-8574-9f8ee2ae19f6.PNG)
