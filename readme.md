## Trigger Word Detection

Here, we will construct a speech dataset and implement an algorithm for trigger word detection (sometimes also called keyword detection, or wake word detection). 

* Trigger word detection is the technology that allows devices like Amazon Alexa, Google Home, Apple Siri, and Baidu DuerOS to wake up upon hearing a certain word.  
* For this exercise, our trigger word will be "Activate." Every time it hears you say "activate," it will make a "chiming" sound. 
* This notebook talks about being able to record a clip of yourself talking, and have the algorithm trigger a chime when it detects you saying "activate." 

<img src="images/sound.png" style="width:1000px;height:150px;">

This assignment will talk about: 
- Structure a speech recognition project
- Synthesize and process audio recordings to create train/dev datasets
- Train a trigger word detection model and make predictions

## Model used:
<img src="images/model.png" style="width:1000px;height:150px;">

This notebook is derived from the MOOC course [Sequence Models](https://www.coursera.org/learn/nlp-sequence-models) by deeplearning.ai
