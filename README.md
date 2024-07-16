# tea-sickness
Detecting Tea Diseases through Deep Learning Techniques

This project uses a lightweight tea disease recognition model based on an improved ResNet18 to recognize tea images and thus improve the performance of the image classification model.

In our problem statement, we intend to solve the problem of tea disease detection and we propose to use a new tea disease dataset which contains five common tea diseases and hence can be used to train deep learning models. Two multi-scale depth-separable convolutions are used to replace the two 3×3 ordinary convolutions of the residual block in ResNet18, as well as the grouped attention mechanism, which combines the channel and spatial feature information to effectively improve the feature extraction ability of the model, allowing the model to pay more attention to the semantic features of the target region, and to achieve higher accuracy without increasing the number of model parameters.

Link to dataset: https://data.mendeley.com/datasets/j32xdt2ff5
