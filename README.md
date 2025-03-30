# Contents
1. [Introduction](#introduction)
2. [Citation](#citation)
3. [License](#license)

# Introduction

On this web page, I provide the Python implementation of the data augmentation method proposed in my paper titled '[Data Augmentation Using Convolutional Autoencoder for Facial Emotion Recognition](https://doi.org/10.1109/ICEIC64972.2025.10879763).' The ability to recognize the emotional state of users from their facial expressions is a useful function for various applications, such as human-computer interaction and customer service. However, the development of such a function is often hindered by the lack of facial emotion recognition (FER) data for model training. The number of samples in most publicly available FER datasets is insufficient for training deep learning models, which require large datasets. To address this problem, this study proposes the use of convolutional autoencoders (CAEs) as a form of data augmentation (DA) to generate face images with different facial expressions synthetically. To demonstrate the effectiveness of the proposed CAE-based DA method, the method was evaluated using the Japanese Female Facial Expression (JAFFE) dataset. The evaluation results showed an increase of approximately 21% in emotion recognition accuracy when the proposed method was applied. These results suggest that the training data shortage problem in FER can be addressed using the proposed method.

# Citation

Please cite the following paper in your publications if they contribute to your research.

```
@article{kwon2025data,
  title={Data Augmentation Using Convolutional Autoencoder for Facial Emotion Recognition},
  author={Kwon, Beom},
  booktitle={2025 International Conference on Electronics, Information, and Communication (ICEIC)},
  pages={1--4},
  year={2025},
  organization={IEEE},  
  doi={10.1109/ICEIC64972.2025.10879763}
}
```
Paper link: [Data Augmentation Using Convolutional Autoencoder for Facial Emotion Recognition](https://doi.org/10.1109/ICEIC64972.2025.10879763)

# License

Our codes are freely available for non-commercial use.
