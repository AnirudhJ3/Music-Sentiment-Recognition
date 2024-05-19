# Music-Sentiment-Recognition

## Overview
This project explores the use of deep learning techniques, specifically Long Short-Term Memory (LSTM) networks and Transformers, for sentiment analysis in music tracks. By analyzing the emotional content of music, the goal is to develop models capable of predicting the sentiment conveyed by audio signals. This README provides an overview of the project structure, dependencies, and usage instructions.

## Requirements

The project requires the following dependencies:
- Python 3.11.7
- TensorFlow
- Keras
- Transformers library from Hugging Face
- NumPy
- Matplotlib
- Librosa (for audio processing)


```
pip install opendatasets
pip install pandas
pip install pydub
pip install numpy pandas matplotlib tensorflow
pip install transformers torch numpy matplotlib
```





## Project Structure
The project is organized into the following directories and files:
- `scripts/`: Includes Python notebooks for data preprocessing, model training, and evaluation.
- `README.md`: This file providing an overview of the project.


## Running the scripts

```
Running the cells in python notebooks will execute all the steps of this project
```

## Usage
1. **Data Preparation**: Ensure the dataset containing audio files and corresponding annotations is available in the `data/` directory.
2. **Preprocessing**: Run the preprocessing script to convert audio files into spectrogram features and prepare the data for model training.
3. **Model Training**: Execute the training script to train the LSTM and Transformer models on the preprocessed data.
4. **Evaluation**: Evaluate the trained models using the provided evaluation script, which includes metrics such as loss and accuracy.
5. **Inference**: Use the trained models for inference by loading them from the `models/` directory and providing input audio data.

## Notes
- The project provides basic implementations of LSTM and Transformer models for music sentiment analysis. Further customization and optimization may be required based on specific use cases and requirements.
- Due to the resource-intensive nature of training Transformer models, it's recommended to utilize powerful hardware or cloud computing resources for optimal performance.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

For any questions or inquiries, please contact [your email address].
