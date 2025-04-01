# NeuralWavetables

A wavetable generator based on a simple autoencoder I developed some time ago, trained on a dataset of 15000 waveforms (each 600 samples long). The autoencoder's latent space is 8-dimensional, and since the decoder is based on a single-layer architecture, the wavetable gradually evolves as each latent parameter changes.

The generator allows you to download the generated single-cycle waveform, making it usable in synthesizers and samplers that employ this type of wave as an oscillator.

To try it out, head [here](https://valeriorlandini.github.io/neuralwavetables/), or check out the repository to use it offline.

In the folder `network` of this repository you can find the original dataset (stored as Numpy array) and a Jupyter notebook to train the network.
