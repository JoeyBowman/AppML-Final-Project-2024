# AppML-Final-Project-2024

## Plan for the project: 

### Data
- Overview: 48x48 pixel images in greyscale - seven categories.
- Goal: Recognize facial expressions/emotions
- Pre-processing algorithm: automatic crop, pixelate to right dimensions, turn to greyscale
- Extend the data set: Flip/Rotate pictures to get more data/show that it works.
- Anomali-detection on flipped/rotated pictures. Can it make a distinction between the same faces but in another direction? 

### Training and optimization
- Quick and dirty method: use pre-trained sklearn architecture to get results
- Own model: CNN with Tensorflow Keras. Train on one computer and save the model for the others to work with. 
- Comparison between pre-build architecture vs our own model
- Rapids: compare time between with/without gpu computation
- Hyperparameter optimization: kernels, "stepsize", structure of the network
- Clustering of latent space: investigation of the space. When does the network start to recognize noses (angry noses from happy noses)? 
- Final demonstration: potentially in app
- Picture on whole class with facial expression 

### Further work / improvements 
- 
