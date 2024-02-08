<h2>Project Code Overview</h2>

<p>This project leverages PyTorch to develop a sophisticated image classification system, utilizing multiple input views to enhance accuracy. Below is a breakdown of the key components and their functionalities:</p>

<ul>
  <li><strong>FeatureExtractor.py (previously classifier.py):</strong> Defines two neural network models. The <em>EmbeddingNetwork</em> extracts features from images through convolutional layers, while the <em>MultiViewNetwork</em> combines these features from multiple views for classification.</li>
  <li><strong>DataProcessor.py (previously dataloader.py):</strong> Manages data loading and preprocessing. It includes a custom <em>Dataset</em> class for handling image transformations and utilities for organizing data and splitting it into training and validation sets.</li>
  <li><strong>ModelTrainer.py (previously trainer and tester.py):</strong> Contains training and validation functions, orchestrating the model's training process, adjusting learning rates, and saving the best-performing model based on validation accuracy.</li>
</ul>

<p>This comprehensive setup aims to advance image classification tasks by considering multiple perspectives of the input data, particularly beneficial in fields requiring detailed analysis of samples, such as biomedical imaging.</p>
