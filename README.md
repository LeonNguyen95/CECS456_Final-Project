# Animal Type Detection with Convolutional Neural Network

This project demonstrates the use of a Convolutional Neural Network (CNN) to classify animal images into 10 categories: **butterfly, cat, chicken, cow, dog, elephant, horse, sheep, spider, and squirrel**. 

The project includes two main files:
1. **`animal_classification_model.ipynb`**: Trains the CNN model.
2. **`animal_prediction.ipynb`**: Uses the trained model to predict the animal type in user-provided images.

---

## Files and Purpose

### 1. `animal_classification_model.ipynb`
- This Jupyter notebook is used to train the CNN model.
- It saves the trained model as `animal_classifier_model.h5` and `animal_classifier_model.keras`.
- For detailed configuration, training setup, and evaluation procedures, refer to the accompanying report: **`Convolutional Neural Network Classification in Animal Type Detection with Images.pdf`**.

---

### 2. `animal_prediction.ipynb`
- This Jupyter notebook uses the pre-trained model (`animal_classifier_model.h5` and `animal_classifier_model.keras`) to predict animal types.
- I have included both trained models (It took several hours to train).
- **How to Use**:
  1. Place the desired images for prediction in the `new-img` directory.
  2. Run the `animal_prediction.ipynb` notebook.
  3. The notebook will output:
     - Predicted animal type for each image.
     - A visualization of each image with the predicted label.