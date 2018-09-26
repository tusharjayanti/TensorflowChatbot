# TensorflowChatbot
A chatbot made in python using Tensorflow


Tensorflow Chat Bot
A chatbot using Tensorflow and Cornell Universities movie dialogue dataset.
This is a tutorial of one of the videos by Sirajology. 
Unlike the tutorial, I have used virtualenv to create a seperate enviroment for the program.
Note: Since this was developed as part of a class project, I did not run the program on a Cloud environment. 
Ergo, My machine was not able to handle the size of the data set. 
I broke down the dataset into sizes of 2000 conversations and runned them like a parallel system (analogically speaking).


Dependencies:

numpy

scipy

six

tensorflow, specifically tensorflow==0.12 (Newer versions will result in error)

virtualenv.


To prepare training data 
run the following
 -> cd datasets/seq2seq/cornell_movie_corpus/scripts/
 -> python prepare_data.py
 
Installation:

cd Tensorflow_Chatbot(into your directory)
virtualenv local
source local/bin/activate

USAGE:

to Train
Change mode in seq2seq.ini (i.e change value of mode to train)
mode = train
and run python execute.py

to Test
Change mode in seq2seq.ini (i.e change value of mode to train)
mode = test
and run python execute.py
