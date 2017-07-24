# autoencoder-omnigenic

### Omnigenic Model

* Some references:
    + http://www.plengegen.com/blog/omnigenic/
    + http://www.sciencedirect.com/science/article/pii/S0092867417306293
    + https://blog.keras.io/building-autoencoders-in-keras.html
* Architecture:
    + NN with input being genotypes and outpur layer being phenotypes
    + Autoencoder with input and output layers being the same: combination of genotypes and phenotypes
    + Find low-dimensional embedding that captures correlations between genotypes and phenotypes, within genotypes and within phenotypes
    + Visualize low-diemensional embedding by t-SNE
    + Will use Keras
