# Water_quality_ANN_CNN

### Water Quality Classification Using ANN and CNN

Water quality is a major concern for many businesses, including agriculture, industrial, and public health. Monitoring the quality of bodies of water such as lakes, rivers, and seas is critical for identifying and addressing any pollution or contamination issues that may impact aquatic life, human health, and the environment.

Artificial Neural Networks (ANN) and Convolutional Neural Networks (CNN) are strong Deep learning methods for analysing water quality data and detecting trends or anomalies. Based on past data, ANN can be used to forecast activities such as assessing water quality characteristics. CNNs can also be used to do the water quality classification.

As a result, applying ANN and CNN approaches to water quality data can provide significant insights to water management enterprises and organisations such as environmental monitoring agencies, municipalities, and private water firms. These findings can assist decision-makers in making informed decisions about how to allocate resources, solve water quality issues, and ultimately improve the overall health of aquatic ecosystems.

Dataset: https://www.kaggle.com/datasets/mssmartypants/water-quality

### Building the ANN
The structure and function of the human brain inspired the development of Artificial Neural Networks (ANN), a form of Deep learning algorithm. ANNs are capable of learning and making predictions based on complex data patterns. Each neuron receives input signals, processes them, and sends output signals to other neurons in the network.

When applying ANN to the Water quality dataset, the input layer of the network would consist of neurons representing the various characteristics of the water samples, such as aluminium, ammonia, bacteria, virus, among others. There would be as many neurons in the input layer as there are features in the dataset.

### Building the CNN
CNNs are a type of deep learning algorithm that is often used to process images and signals, but they can also be used to analyse relational datasets like the Water quality dataset.

A CNN has a number of layers called convolutional layers, pooling layers, and fully connected layers. The convolutional layers use a set of filters to separate edges, corners, and forms from the data that comes in. By downsampling, the pooling layers lower the number of dimensions of the extracted features. This helps to avoid overfitting and makes the network run faster. Lastly, the fully linked layers take the extracted features and use a set of weights to make predictions based on the patterns they have learned.

When CNN was used on the Water quality dataset, the input layer of the network would be a two-dimensional matrix with the samples as rows and the water quality traits as columns. This matrix would be sent to the convolutional layers. The convolutional layers would then use a set of filters on the input data to find patterns and relationships between the features.

### Conclusion
In a nutshell, the decision between an ANN model and a CNN model is determined by the kind of data and the particular problem that needs to be solved. Both of these models have their own advantages and disadvantages, and it is essential to choose the proper model and optimise its hyperparameters in order to get a satisfactory level of performance.
