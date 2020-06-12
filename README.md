# Music Generation; GANs vs LSTMs

DSC160 Data Science and the Arts - Final Project - Generative Arts - Spring 2020

Project Team Members: 
- Adam Kreitzman, akreitzm@ucsd.edu
- Yijian Zong, name2@ucsd.edu
- Jonathan Zhang, name3@ucsd.edu
- Joseph Fallon, name4@ucsd.edu
- Ka Ming Chan, kmc026@ucsd.edu

## Abstract

(10 points) 

We aim to explore the generative prowess of both GAN and LSTM and compare their results. Moreover, we aim to try different implementations of each network and see the subtle differences within each architecture. Most importantly, such exploration enables us to investigate the rarely touched realm of the intersection between arts and technology and contemplate some metaphysical questions: What is music and can we define a qualitative measurement of it? Is there a dissonance between our perception of music and algorithms' perception? Is there a universal archetype of music composition in which we are unanimous?
  
We plan to employ different implementations of GANs and LSTMs. We intend to use Bach preludes and fugues, since Bach is the epitome of music, and his music is fairly structured which makes the training results more salient. Hopefully, the models can generate Bach-like music and capture the melody, polyphonic, and polyrhythms of his composing style. Even better, the models may be creative in utilizing Bach's composing techniques. Our result will be presented using sounds and waveplots, so the audience can see the patterns. A defined metric of musicality that we would use to compare each network would be shared. Some challenges might be the difficulty to decide a good quantative metric, and generating music that has an underlying structure rather than random sounds. This project is interesting since we are curious to see whether algorithms can capture the patterns of music and be creative to generate using the learned materials; it is like human composing using learned building blocks like scale, arpeggio, and chord progressions.

## Data and Model

(10 points) 

- Recurrent Neural Network (RNN) 
  - A neural network good at modeling sequences of data (text, music, speech/sound). Parent of LSTM.
  - https://github.com/animeshsharma97/Music-Generation/blob/master/music_generation.ipynb (Code)
  - Fundamentals of Recurrent Neural Network (RNN) and Long Short-Term Memory (LSTM) Network https://arxiv.org/abs/1808.03314 (Paper)
- Long Short-term Memory Networks (LSTM) 
  - A recurrent neural network that has multiple neural network layers. It can maintain information in memory for long periods of time. It is capable of learning long-term dependencies.
  - https://github.com/animeshsharma97/Music-Generation/blob/master/music_generation.ipynb (Code)
  - Generating Music using an LSTM Network https://arxiv.org/ftp/arxiv/papers/1804/1804.07300.pdf (Paper)
- Generative Adversarial Network (GAN) 
  - A generative model premised on game theory between two players. It involves two sub-models: the generator model which generates new plausible examples from the problem domain, and the discriminator model which is used to classify examples as real (from domain) or fake (generated)
  - https://github.com/magenta/magenta/tree/master/magenta/models/gansynth (Code)
- WaveGAN 
  - A machine learning algorithm which learns to generate raw audio waveforms.
  - https://github.com/chrisdonahue/wavegan (Code)
- SpecGAN 
  - Generates audio by applying image-generating GANs on image-like audio spectrograms. Only generates spectrograms of one second in length at 16khz.
  - https://github.com/chrisdonahue/wavegan (Code)
- Training data: Bach's music 
  - Piano music composed by German musician Johann Sebastian Bach (1685 - 1750). Data is downloadable in the Datasets section of the page labeled "Bach piano performances". 
  - https://github.com/chrisdonahue/wavegan (Link)

## Code

(20 points)

This section will link to the various code for your project (stored within this repository). Your code should be executable on datahub, should we choose to replicate your result. This includes code for: 

- code for data acquisition/scraping
- code for preprocessing
- training code (if appropriate)
- generative methods

There is no code for data acquisition/scraping as the training data consists of sound files that were downloaded directly from the given link above.

Link: https://github.com/ucsd-dsc-arts/dsc160-final-mjisthegoat/blob/master/code/Final_Project.ipynb

This link contains the code for running the main generative models of this project - WaveGAN, SpecGAN, and LSTM. The code for the preprocessing, training, as well as generating procedures are all included sequentially. 

## Results

(30 points) 

Results:
-The pred_rnn.wav file is the LSTM prediction for Bach, and if you listen to it you can pretty clearly hear both the overfitting and the lack of sound quality.

-rnn predictions.png and original wave.png compare the wave plots of the LSTM prediction and test data at one specific point.

-Rnnpred1.png and orig1.png are also a comparison of a wave from the original song versus the LSTM prediction for additional reference. 

-SpecGan.wav is the music that was generated by using SpecGan, and GenerateBach.wav is the music that was generated by using the WaveGan. You can hear that WaveGan does a much better job of replicating the style of Bach’s music, while the SpecGan is just very screechy and not great all-around.

-SpecGan.png and WaveGan.png show the wave plots of the generated music by the respective GANs.


## Discussion

(30 points, three to five paragraphs)

The first paragraph should be a short summary describing your results.

The subsequent paragraphs could address questions including:
- Why is this culturally innovative?
- How does your generative computational approach differ from traditional art/music/cultural production? 
- How do your results relate to broader social, cultural, economic political, etc., issues? 
- What are the ethical concerns for this form of generative art? 
- In what future directions could you expand this work?

## Team Roles

Provide an account of individual members and their efforts/contributions to the specific tasks you accomplished.

## Technical Notes and Dependencies

Any implementation details or notes we need to repeat your work. 
- Additional libraries you are using for this project
- Does this code require other pip packages, software, etc?
- Does this code need to run on some other (non-datahub) platform? (CoLab, etc.)

## Reference

All references to papers, techniques, previous work, repositories you used should be collected at the bottom:
- Papers
  1. https://arxiv.org/ftp/arxiv/papers/1804/1804.07300.pdf
  2. https://salu133445.github.io/musegan/papers

- Repositories
  1. https://github.com/salu133445/musegan
  2. https://github.com/nikhil-kotecha/Generating_Music
  3. https://github.com/Skuldur/Classical-Piano-Composer
  4. https://github.com/chrisdonahue/wavegan
  5. https://github.com/animeshsharma97/Music-Generation

- Blog posts
  1. https://towardsdatascience.com/how-to-generate-music-using-a-lstm-neural-network-in-keras-68786834d4c5
  2. https://magenta.tensorflow.org/gansynth
  3. https://chrisdonahue.com/wavegan_examples/
