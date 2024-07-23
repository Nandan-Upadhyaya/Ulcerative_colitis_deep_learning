## Ulcerative Colitis Endoscopic Image Classification using Mayo Endoscopic Score (MES) by deep/transfer learning:

## Overview:
This project aims to classify endoscopic images of Ulcerative Colitis based on individual Mayo scores using various deep/transfer learning models. The models evaluated include MobileNet, InceptionV3, and DenseNet121. The classification involves four classes: Mayo 0, Mayo 1, Mayo 2, and Mayo 3. Additionally, InceptionV3 and MobileNet were further trained to classify Mayo 0 and Mayo 1 separately, as well as Mayo 2 and Mayo 3 separately, to enhance class prediction accuracy for any random image. A voting mechanism was employed during prediction, where the models collectively determine the final class label based on the highest probability assigned by each model, thereby improving prediction reliability.

## Dataset Used:
The HyperKvasir Dataset(https://datasets.simula.no/hyper-kvasir/) was used for model training which contained 851 images of ulcerative colitis.

## Python Libraries Used and Training Setup:

- **GPU:** Nvidia GeForce RTX 4060
- **CUDA Version:** 11.2
- **CuDNN Version:** 8.1.0
- **IDE:** Visual Studio Code
- **Python Version:** 3.9.19
- **TensorFlow Version:** 2.10.1
- **Numpy Version:** 1.23.0
- **Sklearn Version:** 1.5.1
- **Pandas Version:** 2.2.2
- **Matplotlib Version:** 3.9.1
- **Seaborn Version:** 0.13.2
- **Imbalanced Version:** 0.12.3