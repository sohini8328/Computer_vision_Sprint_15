# Computer_vision_Sprint_15

Verification of Legal Age for Alcohol Purchase Using Computer Vision

Project Overview
The goal of this project is to assist the supermarket chain Good Seed in ensuring compliance with legal age restrictions for alcohol sales. By leveraging computer vision techniques, this system aims to accurately determine a customer's age from their photo, minimizing human error and automating age verification processes.

Methodology
Computer vision methods are applied to extract facial features and predict the age of individuals based on their photos. A machine learning model is built and evaluated to enhance accuracy in verifying a person’s age.

Image Analysis
During preprocessing, multiple images were analyzed. In the original images, all colors—red, blue, and green—were properly visible. However, when examining individual color channels (red, green, and blue), the respective channel showed the highest intensity while others were suppressed.

Model Training and Performance
The model was trained over 20 epochs, with noticeable improvements in loss reduction:
- Epoch 1: Loss = 95.35
- Epoch 20: Loss = 17.01
This trend indicates that increasing the number of epochs contributed to improved age predictions.

Model Evaluation
The Mean Absolute Error (MAE) of the final model is under 8, suggesting that the model provides reliable predictions—lower MAE values indicate better accuracy in age verification.

Future Improvements
Potential enhancements include:
- Fine-tuning model hyperparameters for higher precision
- Expanding the dataset to improve generalization across diverse demographics
- Implementing additional preprocessing techniques to refine image clarity.
  
Conclusion
This system presents a data-driven solution for legal age verification, helping retailers comply with regulations while minimizing manual errors. Further optimization can enhance the model’s robustness, ensuring consistent and accurate age verification in real-world applications.

Use BLANK_README.md to get started Build With: This is the list of the libraries used by me to run this project were pandas,numpy, matplotlib.pyplot, Image, ImageDataGenerator, tensorflow, ResNet50, Sequential, Adam, GlobalAveragePooling2D, Dense, Dropout and Flatten.
Getting Started: This is an example of how you may give instructions on setting up your project locally. To get a local copy up and running follow these simple steps. Prequisites: This is an example of software and how to install them. VS Code
Clone the repo:https://github.com/sohini8328/Computer_vision_Sprint_15.git


