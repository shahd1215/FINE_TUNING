# Fashion-MNIST Classification using ResNet50

---

## Project Overview
This project focuses on **automatic classification of fashion items** using a **pretrained ResNet50 convolutional neural network** through **transfer learning** and **fine-tuning** on the **Fashion-MNIST** dataset.  
The model leverages **ImageNet pretrained weights**, adapts the top layers for Fashion-MNIST, and fine-tunes selected layers to improve classification performance. Epoch-wise accuracy is printed to monitor training and validation progress.

---

## Features
- Pretrained **ResNet50** backbone for feature extraction  
- **Transfer learning** for faster convergence  
- Fine-tuning top layers for **Fashion-MNIST classification**  
- Epoch-wise training and validation accuracy monitoring  
- Modular TensorFlow 2.x implementation  

---

## Dataset
- **Fashion-MNIST**: 70,000 grayscale images of size 28x28  
  - Training: 60,000 images  
  - Test: 10,000 images  
  - **10 classes**: T-shirt/top, Trouser, Pullover, Dress, Coat, Sandal, Shirt, Sneaker, Bag, Ankle boot  

---

## Results

- **Base model accuracy (before fine-tuning):** ~73%  
- **Accuracy after fine-tuning top layers:** ~88% on the test set  
- **Training vs validation accuracy** is monitored per epoch to ensure convergence and track performance improvements

---

## Contributing
Contributions are welcome:  
- Fixing bugs  
- Improving performance  
- Experimenting with dataset variations  

Please open an issue or submit a pull request.  

---

## License
This project is licensed under the **MIT License**. See LICENSE file for details.  

---

## Author
**Shahd Hamed ** – Bioinformatics  
