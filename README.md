**About Algorithm:**<br/>
In the Multilayer perceptron, there can more than linear layer or neurons. If we take the simple example the three-layer first will be the input layer and last will be output layer and middle layer will be hidden layer. We feed the input data to the input layer and take the output from the output layer. We can increase the number of the hidden layer as much as we want, to make the model more complex.<br/>
Here I have used a 2,3,5 Layer Architecture giving me various outputs.I have also added drop-outs and batch Normalisation.Data trained here is MNIST data.<br/>
**Summary:**<br/>

|          Model           | Test-Score |   Test-Accuracy   | 
| ------------- | ------------- |------------- |
|       2-Layer Architecture |         0.06307864126095082          | 0.981 |  
|       3-Layer Architecture         |         0.053948233158088985           | 0.9849 |
|       5-Layer Architecture       |         0.08238632999660912          | 0.981 |
