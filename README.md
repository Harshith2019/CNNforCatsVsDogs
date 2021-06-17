# CNNforCatsVsDogs
Recognizing cats and dogs images using convolutional neural network
<p>Building a model which can identify cats and dogs images.</p>
<p>The model is using <i>adam</i> optimizer and the metric used to track improvement is accuracy</p>
<p>Since it's a binary classification, we used sigmoid activation function for output layer which classifies the image efficiently.</p>
<p>The datasets should be placed in the same folder where this file is being running to load the dataset correctly without any errors.</p>
<p>Currently the path for training dataset is <i>"dataset/training_set"</i> and for test dataset is <i>"dataset/test_set"</i> which contains cats and dogs images (separately in folders). If you have datasets in someother directory, then change the path or place the datasets in the same directory with the folder names as said above.</p>
<p>Since we are loading data from a directory, so we used <i>flow_from_directory</i> function from <b>ImageDataGenerator</b> class from <b>keras.preprocessing.image module</b>.</p>
