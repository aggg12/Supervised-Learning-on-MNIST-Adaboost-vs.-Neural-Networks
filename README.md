# Practice 2 – Computer Vision & Machine Learning

In this project for the “Intelligent Systems” course (UA, 2023/24, C2), I tackled the automatic recognition of handwritten digits (0–9) from the MNIST dataset using a variety of supervised-learning techniques:

- **From-scratch Adaboost**  
  • Implemented a binary AdaBoost classifier (Decision Stumps) in pure Python.  
  • Extended it to multi-class by combining 10 binary classifiers and ranking by confidence.  
  • Tuned parameters \(T\) (number of weak learners) and \(A\) (attempts per stump), and visualized accuracy vs. training time.

- **Scikit-learn AdaBoost**  
  • Reproduced the same multi-class task using `AdaBoostClassifier`.  
  • Compared performance, accuracy and runtime against the custom implementation.  
  • Explored alternative weak learners (e.g., full Decision Trees).

- **Keras Neural Networks**  
  • Built an MLP (multi-layer perceptron) with configurable hidden layers, activation functions and hyperparameters.  
  • Implemented a CNN (convolutional neural network) for image-specific feature extraction.  
  • Benchmarked both models on MNIST and analyzed their trade-offs.

Throughout the project I used **NumPy**, **Matplotlib** (for data visualization), **scikit-learn**, and **Keras** (TensorFlow backend). All code is modularized into functions so that each task can be run independently.
