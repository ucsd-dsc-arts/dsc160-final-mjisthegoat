# Project Title

DSC160 Data Science and the Arts - Final Project - Generative Arts - Spring 2020

Project Team Members: 
- Adam Kreitzman, akreitzm@ucsd.edu
- Yijian Zong, name2@ucsd.edu
- Jonathan Zhang, name3@ucsd.edu
- Joseph Fallon, name4@ucsd.edu
- Ka Chan, name5@ucsd.edu

## Abstract

(10 points) 

For the project proposal, please write a short abstact addressing the questions below. You need to replace the entire contents of this section with one to two paragraphs addressing the following:

  We aim to explore the generative prowess of both GAN and LSTM and compare their results. Moreover, we aim to try different implementations of each network and see the subtle differences within each architecture. Most importantly, such exploration enables us to investigate the rarely touched realm of the intersection between arts and technology and contemplate some metaphysical questions: What is music and can we define a qualitative measurement of it? Is there a dissonance between our perception of music and algorithms' perception? Is there a universal archetype of music composition in which we are unanimous?
  
  We plan to employ different implementations of GANs and LSTMs. Code Base:
       1. https://urldefense.com/v3/__https://github.com/salu133445/musegan*5Cn__;JQ!!Mih3wA!TPasqpiWKI4nV2rjGWb8B4FRox7SRdg8PTmwFu2zsJn8XrcDvxswvBuYjMzenl0f$              2. https://urldefense.com/v3/__https://github.com/nikhil-kotecha/Generating_Music*5Cn__;JQ!!Mih3wA!TPasqpiWKI4nV2rjGWb8B4FRox7SRdg8PTmwFu2zsJn8XrcDvxswvBuYjCZIIxQT$              3. https://urldefense.com/v3/__https://github.com/Skuldur/Classical-Piano-Composer*5Cn__;JQ!!Mih3wA!TPasqpiWKI4nV2rjGWb8B4FRox7SRdg8PTmwFu2zsJn8XrcDvxswvBuYjO8dQCKy$   
       

We intend to use Bach preludes and fugues since Bach is the epitome of music and his music is fairly structured, which makes the training results more salient.

We hope that the models can generate Bach-like music and capture the melody, polyphonic, and polyrhythms of his composing style. Even better, we hope that models can be creative in utilizing Bach's composing techniques.

We will present our result using sounds and waveplots so the audience can see the patterns. We will also share defined metric of musicality that we would use to compare each network.

The challenges might be difficulty to decide a good quantative metric and generate music that has an underlying structure rather than random sounds.

Rather than using a single model and see the result, we go above and beyond by trying different implementations of different models and also construct a metric for comparison.

It is interesting since we are curious to see whether algorithms can capture the patterns of music and be creative to generate using the learned materials. It is like human composing using learned building blocks like scale, arpeggio, and chord progressions.

Generating Music using an LSTM Network (https://urldefense.com/v3/__https://arxiv.org/pdf/1804.07300.pdf)*5Cn__;JQ!!Mih3wA!TPasqpiWKI4nV2rjGWb8B4FRox7SRdg8PTmwFu2zsJn8XrcDvxswvBuYjL6W_UG1 2. MuseGAN (https://urldefense.com/v3/__https://salu133445.github.io/musegan/papers)*5Cn__;JQ!!Mih3wA!TPasqpiWKI4nV2rjGWb8B4FRox7SRdg8PTmwFu2zsJn8XrcDvxswvBuYjHCQSBlH  3. How to Generate Music using a LSTM Neural Network in Keras(https://urldefense.com/v3/__https://towardsdatascience.com/how-to-generate-music-using-a-lstm-neural-network-in-keras-68786834d4c5)*5Cn__;JQ!!Mih3wA!TPasqpiWKI4nV2rjGWb8B4FRox7SRdg8PTmwFu2zsJn8XrcDvxswvBuYjFY3-9OL$

## Data and Model

(10 points) 

In the final submission, this section will describe both the data you use for this project and any pre-existing models/neural nets. For each you should provide the name, a textual description, and a link. If there is a paper (for neural net) link that as well.
- Such and such Neural Net. The short description of this neural net. 
  - [link to code]().
  - [Title of Paper with Link](). 
- Training data. Short description of training data including bibliographic info. [link to data]().

## Code

(20 points)

This section will link to the various code for your project (stored within this repository). Your code should be executable on datahub, should we choose to replicate your result. This includes code for: 

- code for data acquisition/scraping
- code for preprocessing
- training code (if appropriate)
- generative methods

Link each of these items to your .ipynb or .py files within this seection, and provide a brief explanation of what the code does. Reading this section we should have a sense of how to run your code.

## Results

(30 points) 

This section should summarize your results and will embed links to documentation to significant outputs. This should document both process and show artistic results. This can include figures, sound files, videos, bitmaps, as appropriate to your generative art idea. Each result should include a brief textual description, and all should be listed below: 

- image files (`.jpg`, `.png` or whatever else is appropriate)
- audio files (`.wav`, `.mp3`)
- written text as `.pdf`

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
- Repositories
- Blog posts
