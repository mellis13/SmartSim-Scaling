
## SmartSim Scaling

This repository holds all of the scripts and materials for testing
the scaling of SmartSim.

### Inference Tests

the inference tests run as an MPI program where a single SILC client
is initialized on every rank. Each client performs some number of
inferences with the same piece of data (an image).

Currently supported inference tests

  1) MNIST CNN
  2) Resnet50 CNN with ImageNet dataset

For more information on the scaling tests, see the directory corresponding
to the client langauge type (e.g. cpp-inference )

### Scaling data

Scaling data will also be included in the repository.