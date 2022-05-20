# Kymatio Workshop 2022: Scattering1D Tutorial

[Google Colab](https://colab.research.google.com/drive/1J1nag-XlanlfbeH8hSshsqPMaelSnDkf#scrollTo=2IukvoLHcLC9)

[![Star on GitHub](https://img.shields.io/github/stars/kymatio/kymatio/hyde.svg?style=social)](https://github.com/kymatio/kymatio/subscription)

In this tutorial we will work through examples of `Scattering1D` (Time Scattering) in Kymatio.

The intention is to gain an intuition of the physical properties of modulated signals and their scattering transform.

### Part I
* understanding the scattering filterbank construction parameters (`J`, `Q`, `averaging`, `order`, `paths`)
* plotting the wavelet filterbank
* visualizing the response to modulated sounds that appear in music and speech
    - amplitude modulation (tremolo)
    - frequency modulation (vibrato)
    - attacks (note onset)
    - amplitude modulation interference 
    - musical instrument playing techniques

### Part II
* Generate a dataset of synthetic signals with varying spectral shape and interference patterns
* Unsupervised manifold embedding of the nearest neighbour graph (Isomap) of the dataset under Scattering1D

Further documentation can be found here: [Kymatio Github](https://github.com/kymatio/kymatio)
