# tf-neural-nets
Collection of neural netwworks made with TensorFlow and Keras.

Each network also includes the model weights in a .keras file.


## Usage Instructions

```
git clone https://github.com/avanishd-3/tf-neural-networks.git
```

Then run the notebooks

Models can also be loaded with

```
model = tf.keras.models.load_model("model_filename.keras")
```

## Model Quality

Model positions the best models (for their respective tasks) would have on the [Papers with Code](https://paperswithcode.com/) leaderboard as of April 7, 2025


| Model             | Accuracy (%) | Ranking |
| ----------------- | ------------ | ------------- |
| Fashion MNIST CNN | 91.78        | 15th          |
| MNIST ANN         | 98.44        | 53rd          |
| CIFAR-10 CNN      | 81.12        | 245th         |


## ANNs

There are 3 models here.

1. Classification model based on the Fashion MNIST dataset (~88.43% accuracy).
2. Regression model based on the Auto MPG dataset.
3. High-accuracy classification model based on the MNIST dataset (~98.44% accuracy).
4. Classification model based on the CIFAR-10 dataset (~49.20% accuracy, which is pretty high for a non-CNN model on an image-recognition dataset).

## CNNs

There are 3 models here.

1. Classification model based on the Fashion MNIST dataset (~91.78% accuracy).
2. Classification model based on the CIFAR-10 dataset (~81.12% accuracy).
3. Transfer learning (based on Xception) binary classification model trained on TensorFlow cat or dog dataset (~95.53% accuracy).
    - No weight for this one, because it exceeds the GitHub file size.
    - Training is pretty quick, though, because most of the training has already been done.
