# Covid Detection Using Convolution Neural Networks
This is a porject to detect the fact that a person male/female is infected with the Novel Corona Virus using the analysis of their chest X-Rays.

## Model
The Neural Network System Used to analyse the dataset

### Conv_2D
This layer creates a convolution kernel that is wind with layers input which helps produce a tensor of outputs.
### Max_Pooling
Max pooling is a sample-based discretization process. The objective is to down-sample an input representation.
### Dropout
The Dropout layer randomly sets input units to 0 with a frequency of rate at each step during training time, which helps prevent overfitting.
### Flatten
The Flatten layer is a utility layer that flattens an input of shape n * c * h * w to a simple vector output of shape n * (c*h*w) .
### Dense
Dense implements the operation: output = activation(dot(input, kernel) + bias) where activation is the element-wise activation function passed as the activation argument, kernel is a weights matrix created by the layer, and bias is a bias vector created by the layer (only applicable if use_bias is True ).

![Model Accuracy Graphs](https://github.com/kartikeya72001/CovidDetection/blob/master/Models/Model-21-98.28(-)/Model-21-98.28(-)(1).png)



## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)