---
layout: course
title: "Introduction to Computational Musicology: Music Data Mining Methods"
description: This course introduces students to methods of analyzing musical data, including music feature extraction, genre classification, emotion analysis in music, and modern Music Information Retrieval systems.
instructor: Kirill Abrosimov
year: 2023-2024
term: Spring 2023 & Spring 2024
location: ITMO University, Saint Petersburg, Russia
course_id: computational-musicology
schedule:
  - week: 1
    topic: Introduction to Computational Musicology
    description: Overview of computational musicology. Main tasks and methods of Music Information Retrieval (MIR). Introduction to digital signal processing.
    materials:
      - name: Lecture Slides
        url: /assets/musicdatamining/L1_MusicDataMining.pptx
      - name: Assignment 1
        url: /assets/musicdatamining/LR1_Music_Data_Mining_blank.ipynb

  - week: 2
    topic: Acoustic features and Monophonic Pitch Detection
    description: Fundamentals of digital sound, audio file formats, Fourier transform, spectrograms. DFT, FFT, STFT, Mel-spectrograms, MFCC. Methods for Monophonic Pitch Detection (STFT, autocorrelation). 
    materials:
      - name: Lecture Slides
        url: /assets/musicdatamining/L2_MusicDataMining.pptx
      - name: Assignment 2
        url: /assets/musicdatamining/LR2_Music_Data_Mining.ipynb

  - week: 3
    topic: Basics of Data Mining
    description: Supervised learning. K-nn, SVM, Decision Trees, Random forest. Classification metrics. 
    materials:
      - name: Lecture Slides
        url: /assets/musicdatamining/L3_MusicDataMining.pptx
      - name: Assignment 3
        url: /assets/musicdatamining/LR3_Music_Data_Mining.ipynb

  - week: 4
    topic: Music Data Mining tasks
    description: Onset Detection, Tempo Estimation, QBH and Pitch corrections, Genre Classification, Music emotion recognition, Optical Music Recognition, Automatic music arrangement, Singing Voice Synthesis.
    materials:
      - name: Lecture Slides
        url: /assets/musicdatamining/L1_MusicDataMining.pptx
      - name: Assignment 4
        url: /assets/musicdatamining/LR4_Music_Data_Mining_blank.ipynb

  - week: 5
    topic: Basics of Deep Learning I
    description: Gradient Descent, Perceptron, MLP, Loss functions, Activation functions, MiniBach Chorale Counterpoint Accompaniment Symbolic Music Generation System.
    materials:
      - name: Lecture Slides
        url: /assets/musicdatamining/L5_MusicDataMining.pptx
      - name: Assignment 5
        url: /assets/musicdatamining/LR5_Music_Data_Mining.ipynb

  - week: 6
    topic: Basics of Deep Learning II
    description: CNN, RNN, Transfer Learning, Hexahedral Polyphony Symbolic Music Generation Architecture, Chord Generation from Symbolic Melody Using BLSTM Networks, Automatic Music Transcription task, Basics of computational linguistics (tf idf, word2vec, transformers).
    materials:
      - name: Lecture Slides
        url: /assets/musicdatamining/L6_MusicDataMining.pptx
      - name: Assignment 6
        url: /assets/musicdatamining/LR6_Music_Data_Mining.ipynb

  - week: 7
    topic: Visualization of Musical Data and Music Search
    description: Dimensionality reduction (PCA, t-SNE), creativity in visualization, Music Search, LSH.
    materials:
      - name: Lecture Slides
        url: /assets/musicdatamining/L7_MusicDataMining.pptx
      - name: Assignment 7
        url: /assets/musicdatamining/LR7_Music_Data_Mining.ipynb

  - week: 8
    topic: Symbolic Music Processing
    description: Basics of music theory, introduction to mathematical linguistics, grammars and state machines, music21 lib.
    materials:
      - name: Lecture Slides
        url: /assets/musicdatamining/L8_MusicDataMining.pptx

  - week: 9
    topic: Presentation Report on Music Data Mining
    description: Presentation Report on Music Data Mining.
---

## Course Overview

The course "Introduction to Computational Musicology: Music Data Mining Methods" offers a comprehensive introduction to computational music analysis and music data mining methods. Students will become familiar with:

- Fundamentals of digital audio signal processing
- Methods for extracting and analyzing musical features
- Application of machine learning for musical tasks
- Modern approaches in Music Information Retrieval (MIR)
- Practical implementation of music analysis and processing systems

## Target Audience

This course is designed for students interested in:
- Digital signal processing
- Machine learning and data mining
- Music technology
- Interdisciplinary research at the intersection of music and computer science

## Prerequisites

- Basic programming knowledge in Python
- Understanding of machine learning fundamentals
- Basic knowledge of linear algebra and statistics
- Music education is not required, but general musical literacy is desirable

## Technologies and Tools

The course utilizes:
- **Python** - primary programming language
- **Librosa** - library for audio analysis
- **Scikit-learn** - machine learning
- **PyTorch** - deep learning
- **Jupyter Notebooks** - interactive development environment
- **Pandas/NumPy** - data processing

## Practical Projects

Students work on various MIR projects: 

1. **Genre Classifier** - building an automatic music genre classification system
2. **Synthesizer programming** - Programming a custom synthesizer for MIDI file playback
3. **Automatic Music Transcription** - development of a simple monophonic transcription system
4. **Music Search** - implementing an LSH-Based Music Search System

## Grading

- Assignments (7): 70%
- Presentation Report on Music Data Mining: 10%
- Final Exam: 20%

## Course Materials

Primary Literature:
- "Music Data Mining" by Tao Li, Mitsunori Ogihara, George Tzanetakis
- "Deep Learning Techniques for Music Generation" by Jean-Pierre Briot
- "Fundamentals of Music Processing" by Meinard Müller
- "An Introduction to Audio Content Analysis" by Alexander Lerch
- Scientific papers from ISMIR, ICASSP conferences

Additional Resources:
- Music Information Retrieval Community (https://ismir.net/)
- Librosa documentation and tutorials
- Datasets: GTZAN, Million Song Dataset, FMA
- Online courses and MIR materials

## Contact Information

**Instructor**: Kirill Abrosimov  
**University**: ITMO University, Saint Petersburg, Russia

Questions about the course can be asked during classes or through the university communication system
