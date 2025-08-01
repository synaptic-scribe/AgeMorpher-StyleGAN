# AgeMorpher-StyleGAN
This project focuses on building a deep learning pipeline to perform **age progression** using facial image data from the **MORPH dataset**. It utilizes `TensorFlow`, `ResNet50`, and image preprocessing techniques to transform and analyze how facial features change over time.

## 📁 Project Structure

- **Data Loading & Preprocessing**: Reads facial images and metadata (age, gender) from the MORPH dataset.
- **Model Architecture**: Uses pre-trained `ResNet50` for feature extraction.
- **Image Normalization**: Converts all images to RGB, resizes, and normalizes them for model input.
- **Training** *(upcoming)*: Placeholder for training a GAN or regression model for age transformation.

## 🧠 Technologies Used

- TensorFlow & Keras
- OpenCV
- Pandas
- TQDM for progress visualization
- Google Colab for experimentation

## Dataset 
- MORPH Dataset: A large facial dataset with age and gender annotations.
- Images: Stored in a directory with formats like .jpg, .png.
- Metadata: CSV file contains filename, age, and gender.
