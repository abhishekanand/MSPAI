## Introduction to Artificial Intelligence (AI)

### Introduction
#### Before You Start
##### Welcome
##### Pre-Course Survey

### Course Introduction
####Welcome to the Course
##### What is Artificial Intelligence?
##### Real-World AI - Workplace Safety
##### Preparing for the Labs

### Machine Learning
#### Machine Learning Fundamentals
##### What Is Machine Learning?
##### Regression
##### Classification
##### Clustering
##### Real World AI - The Yield

### Azure Machine Learning Studio
#### What is Azure Machine Learning Studio?
##### Creating an Experiment
##### Creating a Regression Model
##### Creating a Classification Model
##### Creating a Clustering Model
##### Publishing a Predictive Web Service
##### Consuming a Predictive Web Service

 
 
### Language and Communication
#### Getting Started with Text Processing

##### Introduction to Text Analytics
* Artificial intelligence needs to include the ability to communicate naturally with digital entities.
* Software needs to be able to understand text, extracting semantic meaning, and even sentiment from the language that we use as humans.
##### Word Frequency
* Descending order of frequency as a Pareto chart.
* Stop Word  example (a, the)
##### Term Frequency - Inverse Document Frequency
* Word Frequecy is good for a single document 

**Term frequency (TF)** : This is simply the relative frequency of a term within a document.

    = term instance /total terms


 **Inverse Document Frequency (IDF)** :    a measure of the relative number of documents within which the term appears.

    =log(docs/docs with term)

![Image](TFxIDF.png)
we just multiply TF by IDF to work out the overall importance of each term to the documents in which they appear. 

##### Stemming
* Stemming is a technique used to identify words with a common root and count them as the same.
* A common technique is to use something called **the Porter algorithm**, which defines a sequence of rules for breaking words down into a common stem based on the pattern of consonants, vowels, common letter combinations and word endings, and other syntactical elements.

##### Sentiment Analysis



#### Introduction to Natural Language Processing
##### Text Analytics
Speech
Translation
Real World AI - Skype Translator in the Classroom


#### Language Understanding Intelligent Service
##### What is LUIS?
Creating a LUIS App
Consuming a LUIS App
Improving a LUIS App
Real World AI - Starship Commander


### Computer Vision
#### Getting Started with Image Processing
##### Image Processing Basics
Equalization
##### Filters
* Gaussian Filter 
##### Edge Detection
* the Sobel edge detection algorithm works by convolving an operation over the image similar to Gaussian a median filters that you saw previously however this time the matrix that we apply is a two-stage masking function that is applied to the pixel intensity values in the image to calculate a gradient value based on changes in intensity

##### Corner Detection
* the harris corner detector algorithm works by testing patches of the image the patch is moved in multiple directions and the pixel intensity is compared for each position now in a featureless area of the image there's no significant difference so no corner is detected 

#### Working with Images and Video
##### Image Classification 
##### Image Analysis
##### Face Detection and Recognition
##### Video Basics
##### The Video Indexer
##### The Video Indexer API
##### Real World AI - Seeing AI


### Conversation as a Platform
#### Introduction to Bots
##### What is a Bot?
The Microsoft Bot Framework
Creating a Basic Bot
Channels
 Building Intelligent Bots
Bot Intelligence
Creating a QnA Service
Creating a QnA Bot
Cortana Skills
Real World AI - Cortana Skills
 Lab
Lab  This content is graded
Lab Instructions
Review Questions
 Learning More
 Beyond the Basics
Introduction to AI Engineering
The Data Science Virtual Machine
Deep Learning and the Microsoft Cognitive Toolkit
Real World AI - Autonomous Sailplanes
 Where Do I Go From Here?
The First Step of the Journey
Next Steps
Post-Course Survey
