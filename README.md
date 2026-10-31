<div align="center">
  <img src="assets/banner.svg" alt="Neural Networks. MNIST digit classification with a dense Keras network." width="100%"/>
</div>

<div align="center">
  <img src="https://img.shields.io/badge/jupyter-notebook-B45CFF?style=flat-square&labelColor=07080D&logo=jupyter&logoColor=EEF1ED" alt="jupyter notebook"/>
  <img src="https://img.shields.io/github/last-commit/Madmins07/Neural_Networks?style=flat-square&labelColor=07080D&color=6F7693&label=updated" alt="last-commit"/>
  <img src="https://img.shields.io/github/license/Madmins07/Neural_Networks?style=flat-square&labelColor=07080D&color=1C2032" alt="license"/>
</div>

## about

Handwritten digit classification on **MNIST** with a dense network in TensorFlow/Keras: load the dataset through
`tensorflow_datasets`, flatten and normalise, stack three ReLU layers (256, 128, 128) into a softmax over ten classes,
train, and evaluate on the held-out test split.

## notebooks

| notebook | what it does | open |
|:--|:--|:--|
| [`Neural_network_digitclass.ipynb`](Neural_network_digitclass.ipynb) | Data pipeline, model definition, training curves, test accuracy, and a look at the misclassified digits. | <a href="https://colab.research.google.com/github/Madmins07/Neural_Networks/blob/main/Neural_network_digitclass.ipynb"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open in Colab"/></a> |

## run

The notebook pulls MNIST itself, so it runs end to end in Colab with no setup.

---

<div align="center">
  <sub>Part of <a href="https://github.com/Madmins07">Madmins07</a> · Madhav Agarwal · IIT Kharagpur</sub>
</div>
