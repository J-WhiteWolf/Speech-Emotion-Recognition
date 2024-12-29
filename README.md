# Speech Emotion Recognition (SER) with TESS Dataset

This notebook demonstrates a Speech Emotion Recognition (SER) project using the TESS dataset. It includes data processing, visualization, model building, and evaluation steps. I have for you below a detailed breakdown of the notebook and instructions for usage.

---

## Table of Contents

1. [Overview](#overview)
2. [Dataset](#dataset)
3. [Dependencies](#dependencies)
4. [Structure](#structure)
5. [Usage Instructions](#usage-instructions)
6. [Results](#results)

---

## Overview

Speech Emotion Recognition (SER) is a technology used to analyze vocal signals and identify expressed emotions. This notebook:

- Processes audio data to extract features (e.g., MFCCs).
- Visualizes datasets for better understanding.
- Builds and trains a deep learning model using TensorFlow/Keras.
- Evaluate the model’s performance on emotion classification.

## Dataset

The [TESS dataset](https://tspace.library.utoronto.ca/handle/1807/24487) contains audio samples labeled with various emotions. Each audio file corresponds to a word or phrase spoken in one of the following emotional states:

- **Anger**
- **Disgust**
- **Fear**
- **Happiness**
- **Pleasant Surprise**
- **Sadness**
- **Neutrality**

The dataset is preprocessed to extract Mel-Frequency Cepstral Coefficients (MFCCs) for input into the model.

## Dependencies

To run this notebook, you will need the following libraries:

- Python 3.x
- NumPy
- pandas
- matplotlib
- seaborn
- librosa
- scikit-learn
- TensorFlow/Keras

Install the dependencies using:

```bash
pip install -r requirements.txt
```

## Structure

The notebook is organized as follows:

1. **Import Libraries**: Imports necessary libraries for data processing, visualization, and model training.
2. **Load and Explore Data**: Loads the TESS dataset and visualizes its structure.
3. **Feature Extraction**: Extracts MFCCs from audio files for model input.
4. **Data Preprocessing**: Encodes emotions and splits data into training, validation, and test sets.
5. **Model Building**: Defines and compiles a deep learning model using LSTM layers for sequence data.
6. **Training**: Trains the model with callbacks for optimization.
7. **Evaluation**: Evaluate the model on test data and visualize results.
8. **Conclusion**: Summarizes findings and suggests improvements.

## Usage Instructions

1. Clone this repository and navigate to the project directory:

   ```bash
   git clone https://github.com/J-WhiteWolf/Speech-Emotion-Recognition.git
   cd Speech-Emotion-Recognition
   ```

2. Install required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Download the TESS dataset and place it in the designated `data` directory.

4. Open the notebook:

   ```bash
   jupyter notebook SER_with_TESS_50.ipynb
   ```

5. Run each cell sequentially to execute the workflow.

## Results

- **Training Accuracy**: Achieved during training epochs.
- **Validation Accuracy**: Evaluated during model validation.
- **Test Accuracy**: Final model performance on unseen data.

Graphs and metrics for each step are included in the notebook for detailed insights.

---

## Contributing

Feel free to fork this repository and submit pull requests for improvements or bug fixes. Contributions are always welcome.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

---

Happy Coding!
