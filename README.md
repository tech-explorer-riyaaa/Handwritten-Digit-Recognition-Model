# Handwritten-Digit-Recognition-Model

This repository contains a machine learning model for handwritten digit recognition. The model has been trained on the MNIST dataset and achieves an accuracy of 98.7%. It was developed for the NORMID hackathon 2023, IGDTUW under the AI track.


<img width="481" alt="image" src="https://github.com/tech-explorer-riyaaa/Handwritten-Digit-Recognition-Model/assets/122520061/8051c98f-4597-4f09-927b-7998db786e19">



## Technologies Used

- **Python:** The project is coded in Python, a powerful and versatile programming language.
  
- **Libraries and Frameworks:**
  - **NumPy:** For efficient numerical computations and array operations.
  - **Matplotlib:** For data visualization and generating plots to analyze the model's performance.
  - **Keras:** A high-level neural networks API, which served as the foundation for building and training the machine learning model.
  - **OpenCV:** Used for image processing tasks, enabling efficient manipulation of images before feeding them into the model.
  - **Pygame:** Employed to create an intuitive user interface where users can draw digits for recognition.

## Usage

1. **Clone the Repository:**
   git clone https://github.com/tech-explorer-riyaaa/Handwritten-Digit-Recognition-Model.git
   
2. Ensure all required **packages/ libraries** are installed in your system.
   
3. **Run the Model:**
          - Train the model using "train_model.ipynb".
            (you can also directly use the trained model I provided in the repo, but it'll be better for you if you train it yourself.)
          - Run "digit_recognition.py" for real-time digit recognition.

   
## Folder Structure

1. **train_model.ipynb:** Jupyter Notebook containing the code for loading the MNIST dataset, building, training, and evaluating the model. This notebook serves as a comprehensive guide to understanding the model's development process.
   
2. **bestmodel.h5:** Contains the trained neural network model in a serialized format.
   
3. **digit_recognition.py:** Python script for real-time digit recognition. Users can draw digits on the Pygame window, and the model will predict and display the recognized digit.


Ensure you have the appropriate dependencies installed and configured before running the code. For any issues or inquiries, please feel free to contact [riyaaa.connects000@gmail.com].

Happy coding! 🚀
Riya Ahlawat
IGDTUW
