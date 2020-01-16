
# Where Should We Apply Batch Normalization?

Batch Normalization is a simple but powerfull idea. By reducing covariance shift it greatly speed up our training. 

I have been taught apply batch normalization layer before activation function, but someone in https://stackoverflow.com/questions/39691902/ordering-of-batch-normalization-and-dropout has stated that recent research have shown apply batch normalization after activation function is better. 

I decided to run my own experiments. The results shows that apply batch normalization before activation is better. For details please check the jupyter book in this repo.
