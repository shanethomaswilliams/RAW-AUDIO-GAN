# DL_FINAL_PROJECT

Here are examples of how we can adapt some data processing for the audio data, but it is a classification CNN so the architecture itself is not that useful... https://medium.com/in-pursuit-of-artificial-intelligence/deep-learning-using-raw-audio-files-66d5e7bf4cca

Here is example to base some of the GANs off of, it uses midi data as input but it is still 1D and should be fine... https://github.com/descriptinc/melgan-neurips/blob/master/mel2wav/modules.py

There is also a point to be made here that GANs used for audio generation is very rare, expecially for music generation. If you look up GAN for raw audio or GAN for music generation you don't really see any actual music reconstruction which means that were doing something semi new which is great.

Here is a link to the dataset that we decided to use... it is 101 GB compressed and 120 GB uncompressed, however in reality only about 56 GB is actually useable .wav files that we want, but here is the link to it... https://magenta.tensorflow.org/datasets/maestro
