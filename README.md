# Summarization project
The code provided in this repository is part of a summarization project in the DTU course Deep Learning (02456).
Three Ipython notebook are provided; 
* Make_dataset.ipynb
* AttentionalDecoderModel.ipynb
* Result_plots.ipynb

The project is inspired by the work of [Abigail See et. al.](https://arxiv.org/abs/1704.04368)

## Data
The dataset used for testing the model was generated using thePython librarynum2words.  The input vector of the datatsetconsist of a sequence of string numbers and the target vec-tor consist of a sequence of numerals (word numbers).  Twodataset was generated from this approach; one with order se-quences and the target being the continuation of the sequenceand the second being random sequences and the target beingthe numeral version of the input. The length of the input andtarget sequence is similar but the lengths vary for each inputtarget  pair  up  to  a  defined  maximum  length. 

## Attentional sequence-to-sequence model
The code in AttentionalDecoderModel.ipynb hold the network of a sequence-to-sequence model with the implementation of an attentional decoder.
Part of the code can be uncomment to obtain the following:
* Testing on a dataset of continuous sequences of input string numbers and target numerals
* Testing on a dataset of random sequences of input string numbers and target numerals
* Testing on a simple seq2seq model with no attention
* Testing on the final implementation with an attentional decoder
