# CNN Image Recognition Project: Homer and Bart Simpson

## Project Description
This project focuses on developing a Convolutional Neural Network (CNN) to recognize and classify images of Homer and Bart Simpson from the iconic animated television show, "The Simpsons." The objective is to accurately identify characters and potentially extend this to other characters in the franchise.

## Objectives
- To build a robust CNN model that effectively identifies Homer and Bart Simpson in various image contexts.
- To explore different neural network architectures and optimization strategies to improve classification accuracy.
- To provide a user-friendly interface for inputting images for character recognition.

## Features
- Image upload for character recognition
- Visualization of predictions and probabilities
- Performance metrics reporting (accuracy, precision, recall)
- Support for various image formats (JPEG, PNG)

## Technologies Used
- Python
- TensorFlow / Keras
- OpenCV for image processing
- Flask / Django for web interface
- Git for version control
- Jupyter Notebook for experimentation

## Setup Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/DuMilo/cnn-homer-bart.git
   cd cnn-homer-bart
   ```
2. Create a virtual environment and activate it:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the application:
   - For Flask:
     ```bash
     flask run
     ```
   - For Django:
     ```bash
     python manage.py runserver
     ```

## Project Structure
```
cnn-homer-bart/
├── app/                # Main application folder
│   ├── static/        # Static files (CSS, images)
│   ├── templates/     # HTML templates
│   ├── models/        # CNN model definitions
│   ├── utils/         # Utility functions for image processing
│   ├── main.py        # Entry point of the application
├── data/              # Dataset folder
├── requirements.txt    # Python package dependencies
└── README.md          # Project documentation
```

## Team Members
- **DuMilo** - Project Lead & Developer
- [Additional team members can be added here]  

---

This README file outlines the structure and expectations of the project, ensuring clear communication and understanding among team members and contributors.