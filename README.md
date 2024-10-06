# Supervised Approaches to CIFAR10
Supervised machine learning is a widely used form of artificial intelligence. There are plenty of ways to approach supervised learning: some of them being Neural Networks, Convolutional Neural Networks and Residual Networks. In this repository we develop an in depth analysis of the difference between these on the CIFAR10 classification task.

<div align="center">
  <img src="https://github.com/M4mbo/Supervised_Approaches_to_CIFAR10/assets/115642529/e5f902d9-c636-4373-9431-8a50057a1218" width=500px>
  <p><em>CIFAR10 dataset. Sample of images with corresponding labels.</em></p>
</div>

## Deep Linear NN

<div align="center">
  <img src="https://github.com/m4mbo/supervised-cifar10/assets/115642529/39a2aaa6-af13-4751-87ee-d8a3582a4fd8" height=300px>
  <img src="https://github.com/m4mbo/supervised-cifar10/assets/115642529/bc32060b-7f07-412c-a6e8-a8a13f8a9b17" height=300px>
</div>

Testing Loss: 1.516
Testing Accuracy: 0.462

## Deep CNN

### No Data Augmentation

<div align="center">
  <img src="https://github.com/m4mbo/supervised-cifar10/assets/115642529/c92658cc-9af6-4e56-8329-4b9bcb5930cd" height=300px>
  <img src="https://github.com/m4mbo/supervised-cifar10/assets/115642529/4719cee4-b118-4e50-a523-34c0304367fd" height=300px>
</div>

Testing Loss: 1.109
Testing Accuracy: 0.675

### Data Augmentation

<div align="center">
  <img src="https://github.com/m4mbo/supervised-cifar10/assets/115642529/7f010f95-e31f-4fb8-bf7d-6c9240e9ce3c" height=300px>
  <img src="https://github.com/m4mbo/supervised-cifar10/assets/115642529/6020b606-9952-489b-92b5-80fad29d2d9c" height=300px>
</div>

Testing Loss: 0.876
Testing Accuracy: 0.708

## Pre-trained ResNet18

### No resizing
<div align="center">
  <img src="https://github.com/m4mbo/supervised-cifar10/assets/115642529/853ebebf-68a5-4d2f-952a-62616980d8e2" height=300px>
  <img src="https://github.com/m4mbo/supervised-cifar10/assets/115642529/90ca2dd1-7b7e-4677-aba0-2ce14ae9b56d" height=300px>
</div>

Testing Loss: 0.740
Testing Accuracy: 0.820

### Resized (224,224)px images

<div align="center">
  <img src="https://github.com/m4mbo/supervised-cifar10/assets/115642529/11d4d35a-303a-4dfc-ae15-8203dcd20922" height=300px>
  <img src="https://github.com/m4mbo/supervised-cifar10/assets/115642529/9c25b281-e898-4b75-8d48-358ae367021c" height=300px>
</div>

Testing Loss: 0.182
Testing Accuracy: 0.952

## Credits
* [m4mbo](https://github.com/m4mbo) - Code
* [LMH](https://www.lmh.ox.ac.uk/) summer program on 'AI and ML: Advanced Applications' - Theory


