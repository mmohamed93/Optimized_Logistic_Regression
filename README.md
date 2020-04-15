# Optimized_Logistic_Regression

An optimized version of Logistic Regression using Torch with support of CPU and GPU instances.

this version has been benchmarked against SKlearn Logistic Regression on the MNIST dataset (both running on CPU), with the same accuracy to that of SKlearn Logistic Regression and more than 100% performance enhancement.

this is an optimized version of SKLearn Logistic Regression using Pytorch, the API is similiar to that of SKlearn, where an instance of LogisticRegression_T is initialized, fit is called to fit the model to the data (the class handles the conversion of numpy arrays to torch arrays and constructing the dataloader). predict method can then be called and works the same way as SKlearn API.

N.B. Pytorch needs to be installed to use that version.
to use the GPU support(optional) CUDA has to be installed .
