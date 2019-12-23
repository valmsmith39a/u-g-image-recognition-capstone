## Udacity Machine Learning Nanodegree - Image Recognition Capstone Project


#### Project:
This project is a dog breed classifier which integrates several components to create a simple application. The project falls under the research domain of image recognition, a field in machine learning where some of the biggest breakthroughs have been made. The application will determine if the image contains a dog (will classify image as dog/not dog). If there is a dog in the image, a convolutional neural network will take the dog image as an input and the output will be a prediction of the breed of the dog. If there is not a dog in the image, the application will detect if there is a human face in the image. If there is, a CNN will output a prediction of which kind of dog breed the human face most resembles. If there is not a human the application will display a message indicating that neither a dog nor human was found.

#### Libraries Used:
torch (nn, optim), torchvision (models, datasets, transforms), numpy, collections (OrderedDict), PIL (Image, ImageFile)

#### Files: 
* project_proposal.pdf: Initial project proposal with initial conceptions of problem definition, dataset exploration, proposed solution and methodology

* project_research.ipynb: Jupyter notebook based on notebook provided by Udacity to obtain and explore the data, experiment and implement the solution, including define, train, validate and test the model

* report.pdf: Final blog post documenting problem statement, data exploration and pre-processing, methodology, results, evaluation and reflections on project

#### Results Summary:
Convolutional neural network defined and trained from scratch achieved accuracy of 5%. Model using transfer learning to extract the features of a pre-trained convolutional network, ResNet18, and redefining final predicting layer, retrained over 25 epochs achieved an accuracy of 82%.