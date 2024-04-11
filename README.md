# Facial-Emotion-Recognition

<!-- ABOUT THE PROJECT -->

## About The Project

A tensorflow/keras implementation of a facial emotion recognition model based on a convolutional neural network architecture and trained on the FER2013 dataset with FERPlus labels.

### Built With

- Keras
- Tensorflow
- OpenCV

<!-- GETTING STARTED -->

## Getting Started

### Prerequisites

- python >= 3.7.9
- keras >= 2.4.3
- tensorflow >= 2.3.1
- opencv >= 4.4
- sklearn >= 0.23
- numpy >= 1.18.5
- pandas >= 1.1.2
- matplotlib >= 3.3.1

<!-- USAGE EXAMPLES -->

## Usage

To train the model use the following command

```sh
 python fer.py
```

The model can make predictions on saved images by providing the image path using the following command

```sh
 python img_predict.py img_name.png
```

It can also predict on saved videos

```sh
  python vid_predict.py vid_name.mp4
```

Or by using a live camera

```sh
  python live_cam_predict.py
```

Here are some test examples:

<p align="center">
  <img src=https://user-images.githubusercontent.com/40613682/96073810-7c241980-0ea7-11eb-848d-29b56ecf4fc1.png alt="drawing" width="220" height="230"/>
  <img src=https://user-images.githubusercontent.com/40613682/96074052-fc4a7f00-0ea7-11eb-8fca-4baf225ed327.png alt="drawing" width="220" height="230"/> 
  <img src=https://user-images.githubusercontent.com/40613682/96074205-67945100-0ea8-11eb-9e43-5b9124c94275.png alt="drawing" width="220" height="230"/>
  <img src=https://user-images.githubusercontent.com/40613682/96074354-ca85e800-0ea8-11eb-86da-749d3653ddbf.png alt="drawing" width="220" height="230"/>
  <img src=https://user-images.githubusercontent.com/40613682/96076039-b9d77100-0eac-11eb-93e0-26ca0f6e678d.png alt="drawing" width="220" height="230"/>
</p>
