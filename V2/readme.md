# American Sign Language Translate
Translate ASL to text/speech or text to ASL

#### Libraries Used: Numpy, Tensorflow, Keras, OpenCV, gTTS, sklearn

#### How to use:
1. Install the above Libraries
2. Download the model from the link: , in case you do not wish to use the ASL.ipynb code to train your own
3. Replace the paths in the code to match your local paths
4. Run vidtoimg.ipynb to capture video from the webcam, press q to quit when you are done. Run the remaining code blocks to save the extracted frames
5. Run ASLtoText.ipynb to translate the saved frames to english with the model. It then uses NLP to create a proper sentence stored in the string text and google's
   text to speech API to store mp3 files for the speech output
6. Run TexttoASL.ipynb to read a text input from user and translate it to ASL and create a video output
