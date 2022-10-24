# Lung_Cancer_Classification
<h3>Introduction</h3>
An important predictor of therapy effectiveness and prognosis in lung cancer is the tumour histology. However, current developments in deep learning for medical image processing reveal that radiologic data can be beneficial for further characterising disease features and clinical risk. Tissue collection for pathologist evaluation is still the most accurate way for histology categorization.

In this work, we present a radiomics approach for the histology of non-small cell lung cancer (NSCLC) tumours to be predicted using CT data. We built and validated convolutional neural networks with a focus on the two most prevalent histological forms, adenocarcinoma (ADC) and squamous cell carcinoma (SCC) (CNNs).

We compared the CNN model with various Algorithms like K-Nearest Neighbor (KNN), Support Vector Machine (SVM), Random Forest (RF). In diverse test sets, our best-performing CNN performed as a robust probabilistic classifier, with qualitatively interpretable visual explanations for its predictions. Deep learning-based radiomics can recognise histological traits in lung cancer.
<h3>Algorithms Used</h3>
<li>VGG16 Implementation</li>
<li>Comparison of VGG16 with ML Algorithm</li>
<h3>VGG16</h3>
It is also known as a ConvNet, which is a kind of ANN (artificial neural network). There are several hidden layers in a convolutional neural network in addition to the input and output layers. One of the top computer vision models to date is a form of CNN(Convolutional Neural Network) called VGG16. Using an architecture with very small (3x3) convolution filters, the model’s developers analyzed the networks and raised the depth, It demonstrated a substantial improvement over the state-of-the-art configurations. They increased the depth to 16–19 weight layers making it approx. — 138 trainable parameters. VGG16 is an object detection and classification method that has a 92.7 percent accuracy rate while classifying 1000 photos into 1000 different categories. It is a well-liked technique for classifying images and is simple to employ with transfer learning.
<h3>VGG16 Architecture</h3>
<img src="https://qph.fs.quoracdn.net/main-qimg-e657c195fc2696c7d5fc0b1e3682fde6">
<li>The 16 in VGG16 stands for 16 weighted layers. Thirteen convolutional layers, five Max Pooling layers, three Dense layers, and a total of 21 layers make up VGG16, but only sixteen of them are weight layers, also known as learnable parameters layers.</li>
<li>The input tensor size for VGG16 is 224, 244 and has three RGB channels.</li>
<li>The most distinctive feature of VGG16 is that it focused on convolution layers of a 3x3 filter with stride 1 rather than a large number of hyper-parameters and consistently employed the same padding and maxpool layer of a 2x2 filter with stride 2.</li>
<li>Throughout the whole architecture, the convolution and max pool layers are placed uniformly.</li>
<li>There are 64 filters in the Conv-1 Layer, 128 filters in Conv-2, 256 filters in Conv-3, and 512 filters in Conv-4 and Conv-5.</li>
<li>Three Fully-Connected (FC) layers follow a stack of convolutional layers: the first two have 4096 channels each, the third performs 1000-way ILSVRC classification and thus contains 1000 channels (one for each class). The final layer is the soft-max layer.</li>
<h2>Comparison of VGG16 with ML Algorithms</h2>
We have implemented the below models.
<li>Support Vector Machine (SVM)</li>
<li>K-Nearest Neighbors (KNN)</li>
<li>Random Forest Classifier (RFC)</li>
This project uses deep learning models (VGG16) to classify whether the patient has lung cancer or not. When compared to other methods, this method reduces storage requirements and execution time. It also highlights the recent research work in the domain and issues in the existing work. This is the best model among all the models used in the project
 
