# LW3-Custom-Image-Classifier


Google Drive: https://drive.google.com/drive/folders/1X7r9qPx0bbonH6GolK5jxFyPpASlzI9l?usp=drive_link
Google Colab: https://colab.research.google.com/drive/1Ya-i1GzI-enbnAohdvfl187jPMy_P5mC?usp=sharing




# Guide Questions (Student Reflection & Explanation)
  Students must answer the following:

  # Dataset Preparation
   
   How did you organize your dataset in Google Drive?
     - I organized my dataset by creating a main folder called ImageDataset in Google Drive. Inside this folder, I created separate folders for each trees.
       Each folder contained many images of that specific trees.

  Why is folder structure important for TensorFlow image loading?
     - The folder structure is important because TensorFlow automatically uses the folder names as labels when loading the images.

  # Model Training

   What is the role of convolutional layers in image classification?
     - Convolutional layers help the model detect important features in images, such as edges, shapes, textures, and patterns.

   Why do we split data into training and validation sets?
     - We split the dataset so that the model can learn from one set (training) and be tested on another set validation.

  # Performance Analysis

   What accuracy did your model achieve?
     - The model achieved approximately 85–90% validation accuracy after training. This means the model was able to correctly classify most of the plant images in the validation dataset.

   How did the number of images affect the model’s performance?
     - The number of images had a big effect on the model’s performance. More images helped the model learn better patterns, which improved accuracy.

  # Critical Thinking

   What challenges did you encounter while using your own dataset?
     - Some challenges I encountered were collecting enough images, organizing the folders correctly, and ensuring the images were clear and properly labeled. 
       Some images also had different sizes and lighting conditions, which can affect model training.

   How can data augmentation improve your model?
     - Data augmentation improves the model by creating slightly modified versions of images, such as rotating, flipping, or zooming them.

  # Application

   Suggest a real-world application for your trained model.
     - One real-world application is a plant identification system. A user can take a photo of a plant, and the system will identify the plant species automatically.
       This can help students, gardeners, or farmers identify plants easily.

   How can this system be integrated into a mobile or web application?
     - The trained model can be integrated into a mobile or web application by connecting it to a backend server.




# Guide Questions (Student Explanation & Reflection)


Student must answer:

# Visualization & Overfitting

  1. What signs indicated overfitting in your first model?
     - Overfitting was visible when the training accuracy kept increasing while the validation accuracy stopped improving or decreased.
       
  2. How did data augmentation affect validation accuracy?
     - Data augmentation improved validation accuracy because it gave the model more varied training images.


# Model Improvement

  3. What is the purpose of dropout layers?
     - Dropout layers help reduce overfitting by randomly turning off some neurons during training.

  4. Why does data augmentation improve generalization?
     - Data augmentation improves generalization because it increases the diversity of training data.

# Performance Comparison

  5. Compare accuracy before and after improvements.
     - Before the improvements, the model had lower validation accuracy and signs of overfitting. After applying data augmentation and dropout, the validation accuracy improved and the difference between             training and validation accuracy became smaller.
       
  6. Which technique contributed most to improvement?
     - The technique that contributed most was data augmentation, because it increased the variety of training images and helped the model learn more robust features.
       
# Deployment & Application

  7. Why is saving the model important?
     - Saving the model is important so it can be reused later without retraining.
       
  8. How can this model be deployed in a real-world system?
     - The model can be deployed by integrating it into a web or mobile application. The application can send images to the trained model, and the model will return predictions.
