# Music Genre and Composer Prediction Using Deep Learning

## Project Overview
This project aims to develop a deep learning model capable of accurately predicting the composer of a musical score. By leveraging advanced neural network architectures RNN's in the form of Long Short-Term Memory (LSTM) and Convolutional Neural Networks (CNN), this model will analyze musical features extracted from MIDI files to identify patterns characteristic of specific composers.

## Objectives
- **Feature Extraction**: Extract and analyze key musical features from MIDI files, including note sequences, durations, velocities, instrument usage, and tempo changes.
- **Model Development**: Implement and optimize LSTM and CNN models to capture temporal sequences and pattern recognition in musical data.
- **Accuracy Improvement**: Enhance model performance to achieve high accuracy in predicting composers, ensuring robust generalization across various classical music styles.
- **Validation**: Conduct comprehensive testing using unseen data to validate the predictive accuracy and reliability of the model.

## Dataset Description
- **Source**: The dataset comprises 3,929 MIDI files from 175 classical composers including Bach, Beethoven, Mozart, and others.
- **Content**:
  - **Notes**: MIDI note numbers representing musical pitches.
  - **Durations**: Time length for each note's playback.
  - **Velocities**: Dynamics of notes, indicating the intensity of play.
  - **Instrumentation**: Indicated by MIDI program numbers for each track.
  - **Temporal Information**: Includes tempo and time signature changes throughout the compositions.
- **Size**:
  - **Files**: 3,929 MIDI files.
  - **Composers**: Works by 175 different composers.

## Deep Learning Techniques
- **LSTM (Long Short-Term Memory)**: Utilized to learn dependencies in musical data over long periods, crucial for capturing compositional styles and development within musical pieces.
- **CNN (Convolutional Neural Network)**: Applied to detect and recognize patterns in local structural elements of music such as motifs and phrases frequently used by specific composers.

## How to Use This Repository
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Yoha02/aai_deep_learing_music_genre_and_composer_classification.git


### Contributing
Contributions to this project are welcome! Please feel free to fork the repository, make improvements, and submit pull requests.


## License
This project is licensed under the MIT License.


