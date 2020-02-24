# Quantum-Machine-Learning
Use of SVMQA(Support Vector machine quantum algorithm) for Quantum Machine learning for Breast Cancer Cell detection
Sharing a Project for Quantum Machine learning for Breast Cancer Cell detection:

The Problem focused here is to determine if cells are Cancerous or not for a specific Breast Cancer dataset. Support Vector machine quantum algorithm is used to predict the accuracy and determine how well the model works for classifying the dataset. 

How it’s done: 

Preparing the breast cancer dataset for the Quantum Circuit and importing to run on algorithm.

1.	Import dataset from sklearn or via this website.
2.	Defining the variables to include Training datasets, testing and how it’s split.
3.	Normalizing to 0 variance such that pixels from image have small range and become easy to compute.
4.	Using IBM’s qiskit library for transforming datasets into number of qubits.
5.	Set the range for SVM to -1 to +1 so classification can be done based on data point lying on the range.
6.	Set up training Dataset.
7.	Set up a plot to showcase visually the classification.

Implementing the ML algorithm. IBM has it’s library which can easily simulate by doing these:
	
1.	Declaring number of Qubits for your Quantum Circuit.
2.	Defining the classes and importing the dataset which we manipulated above.
3.	Dictating the algorithm & setting parameters for how many iteration it should do and depth of the circuit.
4.	Input the new datapoints.
5.	Check the results after the algorithm is finished running.




The results will show that quantum computers are able to produce similar results to a classical computer. The data classification is shown in the image and the different color is representing whether a data point classifies as cancerous or not.
