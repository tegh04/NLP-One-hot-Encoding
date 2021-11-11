# NLP-One-hot-Encoding

Team Members:\
-Tegh Bir Singh\
-Zeyu Li\
-Michael Cooke\
-William Godfrey

## Problem Context

Ericsson needs to establish a way to determine if a truck roll is sent to a site. 
Currently a technician needs to read trouble ticket data to determine if a remote fix should be attempted or a truck roll sent. 
To fixes this they would like to a machine learning algorithm to be developed to determine if truck roll is needed. 

## Code

This code performs one-hot encoding on text data. This was then used to preprocess the data so that ML algorithm could be used to analyse the data. 
The NLP one-hot encoding uses tokenisation-based matching from Spacy to encode the data.

## Going Forward
-Consider applying dimensionality reduction\
-Vectorise code or investigate JIT (Just-In Time) for faster speed\
-Find a way to lock file from being read to prevent file permission error
