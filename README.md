## Dog Breed Classifier

Convolutional Neural Network (CNN) that can classify at ~85% the dog breed from any user-supplied image.

The algorithm accepts a file path to an image and first determines whether the image contains a human, dog, or neither.
Then,
- if a __dog__ is detected in the image, return the predicted breed.
- if a __human__ is detected in the image, return the resembling dog breed.
- if __neither__ is detected in the image, provide output that indicates an error.

