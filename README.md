Breast Cancer Classification using PyTorch
This notebook presents a simple binary classification pipeline using the Breast Cancer dataset implemented with PyTorch. The main focus is to apply key PyTorch components and techniques rather than optimize for model accuracy.

Key steps include:

Data Preprocessing: Standardized the features using StandardScaler and converted categorical labels using LabelEncoder.

Data Batching: Converted the processed data into tensors and used TensorDataset and DataLoader to create mini-batches, enabling mini-batch stochastic gradient descent.

Model Creation: Defined a custom neural network class MySimpleNN with a single linear layer and sigmoid activation function using nn.Module.

Training: Used BCELoss as the loss function and SGD optimizer for training the model over mini-batches.

Evaluation: The goal was to demonstrate the complete pipeline, including model creation, data loading, and training—not to maximize accuracy.
