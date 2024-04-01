# Audio-Classification

This project focuses on the classification of audio data into predefined categories using machine learning techniques. Audio classification has numerous applications including speech recognition, music genre classification, environmental sound analysis, and more. The goal of this project is to develop an accurate and robust audio classification system capable of identifying different audio classes.

Features:

    1. Extracts Mel-spectrogram features from audio data using the Librosa library.
    2. Utilizes transfer learning with pre-trained deep learning models (VGG16, ResNet50, VGG19) to extract high-level features.
    3. Implements a custom neural network architecture with dense layers and ReLU activation for classification.
    4. Supports classification of various audio classes such as speech, music, environmental sounds, etc.
    5. Provides detailed performance metrics including accuracy, precision, recall, and F1-score.

Dependencies:

    Python 3.9
    Librosa
    NumPy
    Pandas
    Scikit-learn
    TensorFlow
    Keras
Project Structure:

    UrbanSound8k/   : Classification done using LSTM, Bi-LSTM, GRU and CNN.
    UrbanSound8k_tl/: Classification done using transfer learning using pretrained VGG16, VGG19 and ResNet50 networks.
    README.md       : Overview of the project and instructions for usage.

**Contributing:**
Contributions to the project are welcome. If you encounter any bugs, issues, or have suggestions for improvements, feel free to open an issue or submit a pull request.
