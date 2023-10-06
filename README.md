# voice-cloning
Voice cloning is the process of creating a synthetic voice using the audio recordings of a real person. Voice cloning uses Artificial Intelligence techniques to train a Machine Learning voice model on the real recordings to extract spectrums of the voice and create a voice that sounds almost exactly like the real voice.

We use 3 stages to obtain the results, the first stage is converting an audio file to a text document in the respective language spoken in the audio itself. The next stage, is translation of the text to the required language. Final stage is converting back the translated text into an audio file.  

# Installations 

Both Windows and Linux are supported. A GPU is recommended for a faster inference.

Make sure you have a GPU system/ you can even try out the code in google colab:
change runtime type --> T4 GPU

Python 3.7 or greater is recommended.

pip install speechRecognition

pip install googletrans==3.1.0a0 {kindly use the latest version}

pip install transformers==4.19.0 einops==0.5.0 rotary_embedding_torch==0.1.5 unidecode==1

git clone https://github.com/jnordberg/tortoise-tts.git

cd tortoise-tts

python3 setup.py install


# Lets Begin to code!

After ensuring that the installations are done, lets now start with our code. 

python voice-cloning.py

# Results

The output and the inferenecs are given above for your references. 

