
Why Google Colab? 

To bring this project to life, we chose Google Colab as our primary playground! Think of Colab as a magical,
cloud-based interactive notebook where explanatory text, Python code, and instant results seamlessly live together. 
It eliminates the headache of complex software installations by allowing us to write and execute code right in our browser. 
This makes it an incredibly practical, flexible, and fun platform for building data-driven projects like my Information Retrieval task and the big project, PlantsVillage. 
and effortlessly share our work with anyone, anywhere!



Project Overview:

Plant Disease Detection ☘️

This project focuses on leveraging computer vision and deep learning techniques to address real-world agricultural challenges using the well-known "PlantVillage" dataset.
The primary goal is to build and train an artificial intelligence model capable of automatically detecting and classifying various plant diseases with high accuracy based on images of plant leaves.
By analyzing and processing these images, the project aims to create an effective tool that can easily distinguish between healthy leaves and those affected by specific diseases.
Ultimately, this work contributes to the advancement of "smart agriculture," helping to reduce crop losses and improve yields through early, tech-driven diagnosis.

Key Features and Technical Workflow: 

Interactive Web Application (Streamlit): The "ST" in the project indicates the integration of Streamlit. This transforms the complex machine learning model into a user-friendly web interface where users (such as farmers or agricultural researchers) can easily upload an image of a leaf and receive an instant, real-time diagnosis.

Deep Learning Architecture: At the core of the notebook is a Convolutional Neural Network (CNN) designed for image classification. The project likely utilizes custom CNN layers or Transfer Learning (using pre-trained models like ResNet, VGG, or MobileNet) to effectively extract complex visual features from the plant leaves, such as spots, discoloration, and lesions.

Data Preprocessing & Augmentation: To ensure the model is robust and performs well on real-world images, the notebook handles image resizing, pixel normalization, and data augmentation techniques (like rotating or flipping images) to expand the training dataset.

Multi-Class Classification: The PlantVillage dataset contains tens of thousands of images covering various crops (e.g., tomatoes, potatoes, bell peppers) and numerous diseases (e.g., Early Blight, Late Blight, Leaf Mold). The model is trained to accurately classify the uploaded image into one of these specific categories or to identify it as a healthy leaf.

Performance Evaluation: The notebook includes detailed visualizations of the model's performance, including training/validation accuracy and loss curves, as well as confusion matrices to verify prediction reliability.



Stop Words Analysis and Implementation 💻

for the "Information Retrieval" course at Al-Balqa Applied University. 
It explores the concept of "Stop Words" in both English and Arabic —these are frequently used words that carry little semantic meaning in text analysis.

The task consists of two main parts:

Part 1: Stop Words Analysis:
Categorizing stop words based on their grammatical functions (such as articles, prepositions, and conjunctions) in both languages,
and explaining why they are typically removed in text processing

Part 2: Python Programming: 
A Python script using the NLTK library to automatically process text. 
The program handles lowercasing, tokenizes the text, and filters out the stop words to show the text before and after processing.
