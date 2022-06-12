# Machine Learning model for Speech Emotion Recognition
This machine learning model will recognize human emotions based on the tone of speech.
## Requirements
  * Python 3 (We use Google Colab)
  * Tensorflow (We use Tensorflow 2.8.2)
  * Librosa 0.8.1 (Python library for music and audio analysis)

## Dataset
  Dataset source : [Here](https://www.kaggle.com/datasets/uldisvalainis/audio-emotions)
  
  This is a dataset that contains : 
   * 16.22% of RAVDESS (The Ryerson Audio-Visual Database of Emotional Speech and Song)
   * 58.15% of CREMA-D (Crowd-sourced Emotional Multimodal Actors Dataset)
   * 3.75% of SAVEE (Surrey Audio-Visual Expressed Emotion)
   * 21.88% of TESS (Toronto Emotional Epeech Set)

## Prepare Data
  After downloading the dataset, data should be organized as follows:

   ```
   MyDrive/
     |-> Colab Notebooks/
         |-> Emotions/
         |   |-> Angry
         |   |-> Disgusted
         |   |-> Fearful
         |   |-> Happy
         |   |-> Neutral
         |   |-> Sad
         |   |-> Surprised
        
   ```
