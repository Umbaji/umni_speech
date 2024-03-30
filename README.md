# umni_speech

The first version of Yodi is built on the uminispeech dataset[5], the mini speech dataset, named umni_speech dataset, which was developed and is currently being improved by the Umbaji team. It is a set of more than 800 augmented recordings from various users, in different settings speaking the same words as in the common speech dataset[6] but in Ewè.

This model was developed by applying STFT transforms to speech data to get the waveforms for training with more meaningful and embeddable data. For the audio inputs, the Ewè words vector space is:

$\alpha = \{'gome', 'djo','dusi', 'mio', 'edji', 'note', 'ao','ee'\}$

We consider the word labels (transcripts) vector space for the recognition, 

$\Omega = \{ 'down','go','left','no','right','stop','up','yes'\}$
