#📄 AI Tools Assignment Report
#🧠 Mastering the AI Toolkit

##✅ Part 1: Theoretical Understanding

###Q1: Explain the primary differences between TensorFlow and PyTorch. When would you choose one over the other?

TensorFlow → Best for production deployment, uses static computational graphs, integrates well with mobile/edge devices (TensorFlow Lite).

PyTorch → More intuitive and Pythonic, uses dynamic graphs, better for research and experimentation.

👉 When to choose:

Use TensorFlow for scalable production systems.

Use PyTorch for flexible prototyping & academic research.

###Q2: Describe two use cases for Jupyter Notebooks in AI development.

Interactive Prototyping → Test and visualize ML models step by step in an interactive environment.

Documentation + Code → Combine explanations, code, and visualizations in one shareable format.

Q3: How does spaCy enhance NLP tasks compared to basic Python string operations?

spaCy provides pre-trained NLP models that perform tokenization, part-of-speech tagging, and Named Entity Recognition (NER) automatically.

Basic Python string operations can only do simple text manipulation, not advanced NLP tasks.

Comparative Analysis: Scikit-learn vs TensorFlow

Feature	Scikit-learn	TensorFlow
Target Applications	Classical ML (Decision Trees, SVM, etc.)	Deep Learning (CNNs, RNNs)
Ease of Use	Very beginner-friendly	Slightly steeper learning curve
Community Support	Large, well-documented for ML	Huge support, especially for deep learning

✅ Part 2: Practical Implementation
Task 1: Iris Classification with Decision Tree
Goal: Classify iris flowers into Setosa, Versicolor, Virginica

Steps: Loaded dataset, visualized sepal/petal features, trained Decision Tree, evaluated metrics

Result: Achieved 100% Accuracy, Precision, and Recall

👉 Full code and outputs are available in the notebook.

Task 2: MNIST CNN Classification
Goal: Classify handwritten digits (0–9) using a CNN

Steps: Built CNN with Conv2D → MaxPooling → Dense layers, trained for 3 epochs, evaluated accuracy

Result: Achieved >95% Test Accuracy

👉 Full code and outputs are available in the notebook.

Task 3: NLP with spaCy
Goal: Extract product names & brands, analyze sentiment in a product review

Steps: Processed text with spaCy → Extracted entities → Used rule-based sentiment scoring

Result: Detected Apple iPhone 14 (PRODUCT) and Amazon (ORG) → Sentiment: Positive

👉 Full code and outputs are available in the notebook.

✅ Part 3: Ethical Reflection & Optimization
Bias in Data:

MNIST lacks handwriting diversity beyond simple digits.

Rule-based sentiment can misinterpret sarcasm, slang, or cultural context.

Mitigation Strategies:

Use larger, diverse datasets and data augmentation.

Apply TensorFlow Fairness Indicators for bias detection.

For NLP, use transformer models like BERT for better context understanding.

Optimization:

CNN can be improved with hyperparameter tuning & dropout layers.

Sentiment analysis can be enhanced with pre-trained sentiment models.

✅ Summary
This assignment demonstrated:
✅ Classical ML (Decision Tree) on structured data
✅ Deep Learning (CNN) for image classification
✅ NLP (spaCy) for text analysis

All code, outputs, and results are documented within the Colab notebook. Ethical considerations and optimization strategies were also discussed.

📧 Author
Kgololosego Moleba
📧 kgolomoleba@gmail.com

✅ Submission Details
Notebook: AI_Tools_Assignment.ipynb (Google Colab / Jupyter)

Report: This PDF document (summarizing theoretical answers & key findings)

README.md: Overview of project structure & tools

