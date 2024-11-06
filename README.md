<h1>Image Classification with CNNs on CIFAR-10</h1>

<p>This project demonstrates an image classification model built using Convolutional Neural Networks (CNNs) to recognize and classify images from the CIFAR-10 dataset. CIFAR-10 is a popular dataset with 60,000 images across 10 classes (airplanes, cars, birds, cats, deer, dogs, frogs, horses, ships, and trucks).</p>

<h2>Project Overview</h2>
<ul>
  <li><strong>Data Preprocessing</strong>: Images were normalized, and data augmentation techniques (like rotation and flipping) were applied to enhance generalization.</li>
  <li><strong>CNN Architecture</strong>: The model uses multiple convolutional and pooling layers, followed by fully connected layers, with ReLU activation and softmax output for classification.</li>
  <li><strong>Training</strong>: The model was trained over multiple epochs, with evaluation on both training and validation datasets to monitor performance and avoid overfitting.</li>
  <li><strong>Evaluation</strong>: Results are visualized through accuracy and loss plots, along with a confusion matrix to analyze misclassifications.</li>
</ul>

<h2>Results</h2>
<p>Achieved an accuracy of <em>69%</em> on the test set, demonstrating robust performance across classes. Sample predictions and visualizations are included for easy reference.</p>

<h2>Usage</h2>
<p>Clone the repository and run the Jupyter notebook to explore the code, training process, and evaluation metrics. Adjust hyperparameters or add layers to experiment further.</p>
