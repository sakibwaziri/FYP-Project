# Detection of Conjunctivitis Disease using CNN

## Introduction

This project focuses on the development of an automated detection system for conjunctivitis using machine learning algorithms and image analysis techniques. Conjunctivitis, commonly known as "pink eye," is an inflammation of the conjunctiva that can be caused by infections, allergies, or irritants. Early and accurate detection is crucial to prevent complications and ensure timely treatment.

## Objectives

The main objectives of this project are:
- To conduct research on conjunctivitis as an epidemic disease.
- To collect data from various medical resources and create a custom dataset.
- To train machine learning models on the collected dataset for accurate classification of conjunctivitis.

## Methodology

### Dataset Creation
- Data Collection: A custom dataset was created in collaboration with ophthalmologists, consisting of high-resolution images of eyes diagnosed with conjunctivitis and healthy eyes.
- Data Augmentation: Various augmentation techniques such as rotation, shifts, shearing, zooming, and horizontal flips were applied to expand and diversify the dataset.

### Preprocessing
- Resizing: Images were resized to 300x300 pixels.
- Normalization: Pixel values were normalized to a range of 0 to 1.
- Contrast Adjustment: Contrast of images was enhanced to highlight features indicative of conjunctivitis.

### Model Development
- Custom CNN Model: A custom Convolutional Neural Network (CNN) was developed with several convolutional layers and dense layers for feature extraction and classification.
- Pre-trained Models: Well-known pre-trained models such as VGG16, ResNet50, InceptionV3, EfficientNetB0, and DenseNet121 were fine-tuned on the custom dataset.

### Training and Evaluation
- Training: The models were trained using the augmented dataset, with a batch size of 128 and 150 epochs. 
- Evaluation: Performance was evaluated using metrics like accuracy, precision, recall, F1-score, and confusion matrices.

### Deployment
- The best-performing model was deployed on a Streamlit web application, enabling real-time detection of conjunctivitis through an easy-to-use interface.

## Results
- The custom CNN model and the fine-tuned pre-trained models demonstrated high accuracy in detecting conjunctivitis, with validation accuracies surpassing 97%.
- The Streamlit application allows users to upload eye images and receive immediate predictions, making it a practical tool for both healthcare professionals and patients.

## Future Work
Future research should focus on expanding the dataset, improving model robustness, and integrating the automated detection system into clinical workflows to assist ophthalmologists in real-time diagnosis and treatment planning.

## Installation

To run the application locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/detection-of-conjunctivitis.git
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Streamlit application:
   ```bash
   streamlit run app.py
   ```

## Contributing, Find a bug?
Contributions are welcome! Please submit a pull request or open an issue to discuss improvements or bug fixes.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgements

- Special thanks to the ophthalmologists who contributed to the dataset creation, and my project mate @Aizaz Muhammad for working and contribution.
- This project was developed as part of a thesis on the automated detection of conjunctivitis.

## Like this project?
if u are feeling generous, buy me a coffee!
