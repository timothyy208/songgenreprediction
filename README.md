# Lyric based song genre classification

380,000+ lyrics from MetroLyrics in the format of Lyrics, Artist, Genre, and Year

Omitted songs without lyrics and songs not in English using python library WhatTheLang

Removed/replaced problematic lyric fields (e.g null values, too few words, symbols etc.)

Removed the 5 genres with the fewest songs

Took a random sample of size n=13354 for each of the 5 remaining genres

n =  size of the smallest remaining genre 


Naïve Bayes: 
0.63050

k-NN: 
0.48506

Logistic Regression: 
0.64794

SVM: 
0.63102

LSTM RNN: 
0.67947
