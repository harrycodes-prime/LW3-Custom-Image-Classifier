# LW3-Custom-Image-Classifier


https://drive.google.com/drive/folders/1X7r9qPx0bbonH6GolK5jxFyPpASlzI9l?usp=drive_link


# Guide Qeustions (Student Explanation & Reflection)


Student must answer:

# Visualization & Overfitting

  1. What signs indicated overfitting in your first model?
     - Overfitting was observed when the training accuracy kept increasing while the validation accuracy stopped improving or started decreasing.
       
  2. How did data augmentation affect validation accuracy?
     - Data augmentation improved the validation accuracy because it introduced more variations of the images during training.


# Model Improvement

  3. What is the purpose of dropout layers?
     - Dropout layers help prevent overfitting by randomly turning off some neurons during training.

  4. Why does data augmentation improve generalization?
     - Data augmentation improves generalization because it exposes the model to different variations of the same images.
    

# Performance Comparison

  5. Compare accuracy before and after improvements.
     - Before applying improvements such as data augmentation and dropout, the model had lower validation accuracy and showed signs of overfitting.
       After applying these techniques, the validation accuracy improved and the gap between training and validation accuracy became smaller, indicating better generalization.
       
  6. Which technique contributed most to improvement?
     - Both data augmentation and dropout helped improve the model, but data augmentation contributed the most because it increased the variety of images used during training.

# Deployment & Application

  7. Why is saving the model important?
     - Saving the model is important because it allows us to reuse the trained model without training it again.

  8. How can this model be deployed in a real-world system?
     - This model can be deployed in a mobile or web application where users can upload an image, and the system will automatically classify it.
