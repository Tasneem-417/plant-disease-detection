# plant-disease-detection-project


⁉️ why this project?
---------------------
Make a deep learning model that can detect plant diseases (especially apple diseases) from images.
Early detection of plant diseases can help
1)farmers take timely actions, reducing crop losses and promoting sustainable agriculture.
enabling users to interactively diagnose plant diseases.

2)Agricultural Experts and Researchers: Agricultural experts and researchers can leverage this tool to identify plant diseases in experimental settings. The system can aid in analyzing disease prevalence and patterns across different plant species.

3)Educational Purposes: Students and educators can use this platform as an educational resource to understand plant diseases and learn about deep learning techniques applied in real-world applications.

4)Future Enhancements: The project's potential for growth is vast, and future enhancements could include:
Integration with additional plant-related datasets to improve the model's accuracy and generalization. Deployment on cloud platforms for scalability and increased availability. Incorporating real-time image augmentation and preprocessing techniques to handle various image qualities and formats. Building a mobile app version for on-the-go plant disease diagnosis.

🗂️ Dataset
--------------
 Source: https://www.kaggle.com/datasets/vipoooool/new-plant-diseases-dataset.
 Content:87.9k images.
 this project use only apple images (7780 image).

 🛠️ Preparing data
 ------------------
 Used transforms.ToTensor() for normalization.
 initialize DataLoader for efficient batch processing.

🏋️Training
------------------
using:- 
CNN model : for image recognition and processing.
Adam optimizer: for per-parameter adaptive learning rates.
Learning Rate: that determines the step size at each iteration while moving toward a minimum of a loss function.
loss function: CrossEntropyLoss() to measure the performance of a classification (model Calculate loss).

📊 visualization
------------------
![image](https://github.com/user-attachments/assets/24a9dac1-afec-415f-bef3-7caa45ae94a5)

🧪 Testing
-----------------
testing another images to predict diseases and get accuracy.

🏃‍♂️‍➡️ run project
------------------------
run filename.py .
Then  upload the image and make prediction.

📈 Results
---------------------
Accuracy: Achieved above 95% accuracy on the validation dataset.
Confusion Matrix: Visualized the performance of the model across classes.



