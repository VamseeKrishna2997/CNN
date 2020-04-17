# CNN
Diagnosis of Alzheimer's and Parkinson's disease By using DeepLearning




Abstract
Now a days most of the young and old people are effected by most common brain diseases are Alzheimer's and Parkinson's.Alzheimer's effects the neurons and damage the language,Memory an Intelligence of the person,where as Parkinson's effects the nerve cell in the deep part of the brain.Symptoms differ from each other.Many different type of Machine learning techniques to detect the brain  disease separately came into exsistance.Early proposed models has taken certain views of the brains like Frontal,Axial and Sagittal and differentiate with healthy brain image.The main aim of this model is to detect both the disease in a single scan technique.
Keywords:Alzheimer’s,Parkinson’s,Frontal,Axial,Sagittal,CNN

1.Introduction
Alzheimer is kind of brain disease which effect the neurons of the brain and parts of brain like Intelligent(frontallobe),Memory(temporallobe),Language(parietal lobe)[9],where as Parkinson’s is a type of which effects the nervous system in deep part of brain called Substantial Nigra.Symptoms differ from each other,For example Symptoms for Alzheimer's are difficult to remember the events,confusion,change in moods,visual problem and symptoms for Parkinson’s are unable to sleep,depression,Low blood pressure[6].However, cause of this disease is unknown,but scientist believe that it might be due to lifestyle and genetic.There is no cure for disease, but there are some training's given to the if we try to identify it in early stages[10].As,per now in health care industry different types of scan techniques came into exsistance,As Machine Learning is ruling the world by using Machine Learning technique different type of scan techniques are available in the industry to scan the diseases separately by scanning whole the brain image and trying to differentiate between healthy brain image and diseased brain image.By using PET(Positron emission tomography) scan technique to scan brain[3],by using some radioactive substance called a tracer to detect the difference between normal brain and diseased brain.The application to detect Alzheimer consists of two steps,by using segmentation of the ROI it will extract the regions like Hippocampus,Corpus Callosum and Cortex and classification is made based upon Support Vector Machine(SVM) algorithm,and classifies any components by SVM and for the final decision we used the decision tree.If the hippocampus is positive the following patient is normal and if it is negative and corpus callosum is positive the patient is MCI(Mild Cognitive Impairment) the first step of Alzheimer’s,if hippocampus is classified as negative the corpus callosum classified negative and the cortex patient is MCI(the patient is having first stage of Alzheimer).If Hippocampus is classified negative and the corpus callosum is positive the patient is suffering from Alzheimer’s[1].
They are like different steps for classification of disease,it all begins with collection of patients records which followed by preprocessing of data set includes converting the data into numeric values.Next step is evaluating the attributes by using gain ratio attribute evaluation scheme with ranker search method,and next classification.By using Relief-F for features selection and use to draw instance at random,compute their and adjust a feature weighting vector to give more weight to features that discriminate the instance from neighbours of different classes.Convolution neural networks(CNN) are specific type of Artificial Neural Network that is becoming increasingly important in Machine Learning.They are a bio-inspired variant of Multilayer Perceptrons(MLPs),in which response of a neuron is approximated by convolution operation[2].They are multiple layers in CNN like Convolution Operation,Pooling,Flattering and Full-Connection, in each layer this technique will able to classify the difference between normal and healthy brain image. We use CNN because it is a powerful in classification.[4]We use Deep Learning algorithms for
more effective accuracy.



2.METHODS AND MATERIALS:

A)Support Vector Machine(SVM):

Support vector machine algorithm,it is a kind of algorithm in which two type of different kind of data sets are separated by a hyper plane.The data-set near to the algorithm is said to be support vectors.Let us consider two kind of data sets white and blue.The data set with white falls on the left side and blue falls on the right side.The main important point we have to notice in SVM algorithm is the type of hyper-plane passing through separate two data-sets,In case of the data is randomly distributed we use kernel SVM[8].

B)Convolution Neural Networks(CNN):
Convolution Neural Network is used recognition of image,by using this we can able to classifie the images.
Computer see an input image as an array,based upon that it perform different stages such as Convolution plus RELU,pooling and second layer convolution and pooling and at end of this stage the accuracy of the images should be more that 80 and this part is called as Feature Learning.The classification is done by flatten and fully connected network and at this stage based upon the accuracy of the image it classifies into two different types of images[4].

C)DeepLearning:
DeepLearning is a part of machine learning family and its consist multilayers and covnvert the given linear input to non linear output,by using activation function.In image processing the lower layers detect the edges while higher layers detect objects such as human faces,tumors,digitsetc.The advantages of deep learning models are it output has more accuracy when compare to other models.

3.PROPOSED MODEL

The aim of this model is to to detect both Parkinson and Alzehimers under single scan technique,so by scanning the Sagittal brain image using PET scan and by using RCNN[7] extract the regions like Corpus Callosum,Cortex and Hippocampus and Substantia Nigra these are parts of the brain which are effected by Alzeheimers and Parkinson’s disease by extracting that region we compute with CNN features,it performs feature learning and classification technique and accuracy must be more than 80% it performs image classification and classifie between healthy brain and tumor brain.By using this technique it can save money and time and can detect both the brain disease using single scan even their sympotms are different
Steps of classification of model:
Step 1: Scanning brain image by using Pet scan Technique
Step 2: Add healthy brain and effected brain pics
Step 3:Now perform CNN
Step 4:Convolution and Pooling,Feature selection layer with an accuracy of 80%
Step 5:The classification step were we use to classifie healthy and normal brain images[7].

CLASSIFICATION OF PROPOSED MODEL


4.Conclusion:
Many machine learning applications are widely used in the market many applications using ML techniques came into exsistance and become and important part in scanning techniques.They are different kinds of scan techniques are their for detection of Alzehimer’s and Parkinson’s seperately,but to save time,money and data.The major aim in this proposed model is to detect the tumor part of the brain and detect both Alzheimers and Parkinson’s is a single scan setup.


5.Output:

{'MildDemented': 0, 'NonDemented': 1}

The average accuracy prediction of the model is 81% after 25 epochs and 8000steps per each
