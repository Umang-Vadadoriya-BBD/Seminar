# Reference notebooks

These notebooks are **not part of this project's contribution**. They are third-party
tutorial notebooks, adapted from public sources, that were worked through while learning
the techniques used in `../CNN_With_English_Chars.ipynb`. They are kept here for
provenance and clearly separated so they are not mistaken for original work.

| Notebook | Source | What it covers |
| --- | --- | --- |
| `cnn_mnist_exercise_solution.ipynb` | codebasics deep-learning series | Side-by-side ANN vs CNN on MNIST, showing why convolution helps on image input |
| `cnn_flower_image_classification_data_augmentations.ipynb` | Adapted from the [TensorFlow image-classification tutorial](https://www.tensorflow.org/tutorials/images/classification) | Diagnosing overfitting and addressing it with data augmentation (zoom, rotation, flip) |

The augmentation notebook is the direct basis for limitation #3 in the main
[README](../README.md#limitations-honestly) — the technique was studied here but not
applied to the digits model, which is the largest single improvement still available.
