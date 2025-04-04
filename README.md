# Jigsaw Puzzle Solver

### Aim Of The Project

This project aims to solve a jigsaw puzzle by leveraging image processing and machine learning techniques. The process involves preprocessing the puzzle pieces, training a model to predict their arrangement, and reconstructing the puzzle from the predictions. The implementation integrates traditional image manipulation techniques with neural networks to achieve accurate results.

### Dependencies

The following libraries are required:

- TensorFlow
- Keras
- NumPy
- Pandas
- Matplotlib
- OpenCV
- PIL (Python Imaging Library)
- Scikit-learn

### Setting Up The Environment

- Open the program in Google Colab only.
- Mount your Google drive in which the datasets are present.
- Verify all dependencies are installed using the command: pip list
- Ensure the dataset and required images are available in the specified directory paths. If not you can customize the path at commented places.

### Running The Code

- The Animal image dataset has a separate section and so does the Human image dataset. Hence run the code cell by cell, carefully.
- model1 is used for training the animal dataset and model2 for training the human dataset.

### Expected Output

- Output is the score calculated as mentioned for every image.
- Then, we have calculated the score for each category of images (3x3 and 5x5) at the end by taking the average of all scores.
- The total score at the end is the weighted mean of the score of 3x3 images (Weight = 0.4) and the score of 5x5 images (Weight = 0.6).

### Miscellanous information

- All the datasets and important information are given here: https://drive.google.com/drive/folders/1waMzOqKaJIlfbdINccJVbdZavA5caoHO?usp=drive_link

### Contributors

- Om Prakash Behera (IIT Bhubaneswar)
- Suprit Naik (IIT Bhubaneswar)
