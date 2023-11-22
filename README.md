# DermatologyClassifier

This model is acts as a skin condition classifier. 

**Dataset: DermNet**
The dataset used to train the model is DermNet which can be retrieved from the following site: https://dermnet.com/

This dataset holds a collection of 23 classes of skin conditions with a total of close to 20,000 images. 

**Model: Resnet**
https://arxiv.org/abs/1512.03385
Proposed in the article above, resnet is a deep residual neural network for image recognition. The article highlights the importance of network depth to maximize training accuracy; however, in other architectures the increase in layers often degrades training accuracy. The implementation of a residual architecture solves the degredation problem when adding more layers to a model. The pytorch implementation of this model through torch vision was used.  https://pytorch.org/hub/pytorch_vision_resnet/

**Code:**
A pytorch and pytorch lightning implementation of the model on the dataset is available in the repository. 
