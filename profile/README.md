<!-- MarkdownTOC levels="1,2,3" autolink="true" style="ordered" -->

1. [Working](#working)
    1. [Generalized King profile \(ell, theta\)](#generalized-king-profile-ell-theta)
    1. [pyUPMASK membership](#pyupmask-membership)
1. [Participating](#participating)
    1. [32 Rain clusters](#32-rain-clusters)
    1. [Wilton project](#wilton-project)
1. [Future projects](#future-projects)
    1. [NGC2516](#ngc2516)
    1. [Blue stragglers model](#blue-stragglers-model)
    1. [Binary systems probabilities](#binary-systems-probabilities)
    1. [GAIA1](#gaia1)
    1. [Eight \(?\) new Gaia clusters](#eight--new-gaia-clusters)
    1. [Comparision between CMD distances](#comparision-between-cmd-distances)
1. [Doubtful](#doubtful)
    1. [269 Gaia clusters](#269-gaia-clusters)
    1. [AD test for catalogued clusters](#ad-test-for-catalogued-clusters)
    1. [Four NGC clusters](#four-ngc-clusters)
    1. [Five clusters](#five-clusters)
    1. [Clusters around TR24](#clusters-around-tr24)
    1. [Five embedded cluster](#five-embedded-cluster)
    1. [13 frames used in my PhD](#13-frames-used-in-my-phd)
    1. [4 GCs](#4-gcs)
1. [Done](#done)
    1. [Distant clusters \(2022\)](#distant-clusters-2022)
    1. [pyUPMASK \(2021\)](#pyupmask-2021)
    1. [Sixteen clusters \(2020\)](#sixteen-clusters-2020)

<!-- /MarkdownTOC -->


## Working

### Generalized King profile (ell, theta)

Process the clusters in the Cantat-Gaudin (2020) database, fitting a 4-parameter generalized King profile to each, using the Bayesian implementation in ASteCA.


### pyUPMASK membership

Process as many clusters as possible with pyUPMASK to generate a new database of most probable members.



## Participating

### 32 Rain clusters

Binary analysis for 32 open clusters

### Wilton project

Analysis of ~1500 clusters with Dias et al.





## Future projects

### NGC2516

Estimate the mass and binary fraction, mass ratio, etc.

### Blue stragglers model

Test the performance of ASteCA on clusters with bonafide BSS populations, after incorporating the BSS model from Xin et al. (2011)

### Binary systems probabilities

Analyze several clusters with the code that identifies binary systems and give
an estimate of the probability of binary fraction with mass, and the
distribution of q.

### GAIA1

Analysis of the GAIA1 cluster with Gaia EDR3 data.

### Eight (?) new Gaia clusters

Process the eight (include GAIA3 and GAIA8?) new clusters found in recent studies.

### Comparision between CMD distances

Compare several distribution distances to see which one better recovers the
true parameters of synthetic clusters.




## Doubtful

### 269 Gaia clusters

Process the 269 clusters studied in Bossini et al (2019) with ASteCA to compare the ages, extinction, and distances they obtained using BASE-9.

### AD test for catalogued clusters

Apply the AD test to the largest possible list of catalogued clusters. Assign
classification, and estimate a coarse parallax distance.

### Four NGC clusters

Analyze the IMF of the four clusters: NGC2571, NGC6242, NGC2660, NGC2509

### Five clusters

Analyze the five Clusters: HAF14, RUP41, RUP42, RUP44, RUP152.

### Clusters around TR24

Analysis of these four clusters located around Trumpler 24: NGC6242, Lynga13, NGC6192, Lynga14.

### Five embedded cluster

Analyze the five embedded clusters: DBS5, DBS60, DBS98, DBS116, DBS117.

### 13 frames used in my PhD

- [ ] Cross-match with Gaia DR2 (Bailer-Jones catalogue) to add parallax distances and (ra, dec) coordinates
- [ ] Add E_BV estimates with http://argonaut.skymaps.info/
- [ ] Use the [isochrones](https://isochrones.readthedocs.io/en/latest/index.html) package to assign z, log(age)
Article that applied the `isochrones` package [Bochanski et al. (2018)](https://ui.adsabs.harvard.edu/abs/2018AJ....155..149B)
- [ ] The `StarHorse`, [Queiroz et al. (2018)](https://ui.adsabs.harvard.edu/abs/2018MNRAS.476.2556Q/abstract) package estimates "*masses, ages, distances, and extinctions for field stars*".
- [ ] The method presented in [Green et al. (2020)](https://ui.adsabs.harvard.edu/abs/2020arXiv200616258G/abstract) also does what `StarHorse` does but empirically.
- [ ] [Stellar Parameter Determination from Photometry using Invertible Neural Networks](https://arxiv.org/abs/2007.08391), Ksoll et al. (2020). Might be useful
- [ ] The `brutus` package https://github.com/joshspeagle/brutus can be used to fit individual sources

### 4 GCs

Four large globular clusters with DECam data



## Done

### Distant clusters (2022)

Analysis of the distance to clusters with catalogued distances lager than 9 Kpc

### pyUPMASK (2021)

Development of a new membership probabilities method based on the UPMASK
algorithm.

### Sixteen clusters (2020)

Analysis of sixteen clusters