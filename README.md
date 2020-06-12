# Project Title

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

In the final submission, this section will describe both the data you use for this project and any pre-existing models/neural nets. For each you should provide the name, a textual description, and a link. If there is a paper (for neural net) link that as well.
- Such and such Neural Net. The short description of this neural net. 
  - [link to code]().
  - [Title of Paper with Link](). 
- Training data: Bach's music. Piano music composed by German musician Johann Sebastian Bach (1685 - 1750). The data is in the Datasets section of the page. [https://github.com/chrisdonahue/wavegan]().

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
  1. https://arxiv.org/ftp/arxiv/papers/1804/1804.07300.pdf
  2. https://salu133445.github.io/musegan/papers

- Repositories
  1. https://github.com/salu133445/musegan
  2. https://github.com/nikhil-kotecha/Generating_Music
  3. https://github.com/Skuldur/Classical-Piano-Composer
  4. https://github.com/chrisdonahue/wavegan

- Blog posts
  1. https://towardsdatascience.com/how-to-generate-music-using-a-lstm-neural-network-in-keras-68786834d4c5
  2. https://magenta.tensorflow.org/gansynth
  3. https://chrisdonahue.com/wavegan_examples/