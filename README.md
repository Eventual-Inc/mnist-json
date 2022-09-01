# MNIST

MNIST is an image dataset of handwritten digits and their correct labels.

This repository provides the dataset in ndjson (newline-delimited JSON), where each row is one image and its label:

```
{"image": [... 784 ints], "label": 1}
...
```

# Downloading

The data is accessible at the URLs:

```
curl -LO https://github.com/Eventual-Inc/mnist-json/raw/master/mnist_handwritten_test.json.gz
curl -LO https://github.com/Eventual-Inc/mnist-json/raw/master/mnist_handwritten_train.json.gz
```

