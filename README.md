Millions of songs are released every year by artists worldwide, it has become
nearly impossible to manually label each track by genre. Traditional machine
learning approaches often depend heavily on extensive feature engineering and
still struggle to capture the rich temporal and spectral patterns found in music.
In contrast, deep learning models, particularly Convolutional Neural Networks
(CNNs), can learn complex features directly from raw data representations, mak-
ing them well-suited for music classification tasks. In this project, we develop
a deep learning based solution that automatically classifies the genre of a given
audio clip. By converting audio into spectrograms and using them as inputs to
our CNN, we aim to leverage both time and frequency information embedded in
music signals. Our approach not only reduces the need for manual feature design
but also enables scalable and efficient genre classification for large audio datasets. 
We utilized a custom evolution based hyperparameter optimization algorithm which 
ended up achieving a 85% accuracy.
