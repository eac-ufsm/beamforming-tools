# beamforming-tools

This repository contains a collection list of tools for acoustic beamforming.

Contributions are welcome, get in touch. 😊

## Matlab

- [ITA-Toolbox](https://git.rwth-aachen.de/ita/toolbox): offers implementations of many beamforming algorithms and microphone array geometry generation and evaluation tools.

- [Beamap](https://github.com/eac-ufsm/beamap): offers implementations of beamforming algorithms and microphone array geometry generation and evaluation tools. This toolbox is created with focus in teaching the beamforming technique to undergraduate students from the [Acoustical Engineering Program](https://asa.scitation.org/doi/10.1121/10.0013570) at the Federal University of Santa Maria, in southern Brazil.
  - __*[Link to the article on ResearchGate.](https://www.researchgate.net/publication/362024706_Teaching_acoustical_beamforming_via_active_learning)*__

- [fia2022-fontes-sonoras](https://github.com/eac-ufsm/fia2022-fontes-sonoras): as an educational toolbox, offers tools for the generation of simulated data similar to sound source measurements, being the source is static or in movement (including the Doppler Effect). Other possibilities rely on the creation of receiver arrays using pre-defined geometries.
  - __*[Link to the article.](https://www.fia2022.com.br/arearestrita/apresentacoes/9042.pdf)*__

- [MicArrayBeamforming](https://github.com/MiguelBlancoGalindo/MicArrayBeamforming): this toolbox is focused on microphone array generation and its evaluation.
  - *[Link to the article.](https://www.aes.org/e-lib/browse.cfm?elib=20851)*

- [Spherical-Array-Processing](https://github.com/polarch/Spherical-Array-Processing): routines for acoustical array processing on spherical harmonic signals, commonly captured with a spherical microphone array.

- [Acoustic-Beamforming-Methods](https://github.com/HauLiang/Acoustic-Beamforming-Methods): provides a series of beamforming algorithms as demos.

- [Beamforming-Simulations](https://github.com/Anwar-M/Beamforming-Simulations): offers basic beamforming simulations for various circumstances and contains various examples and experiments concerning beamforming.

- [Acoustic-Beamforming](https://github.com/Anwar-M/Acoustic-Beamforming): provides various beamforming, allowing for convection, different types of steering vectors, and more.

- [Beamforming Tools](https://github.com/jorgengrythe/beamforming): set of codes with diverse options for array processing (developed by Jørgen Grythe) — alternative links [#1](https://www.mathworks.com/matlabcentral/fileexchange/53294-delay-and-sum-beamforming-for-arbitrary-array-geometry) [#2](https://www.mathworks.com/matlabcentral/fileexchange/49690-array-factor-beampattern-of-discrete-array-of-any-shape?s_tid=prof_contriblnk).

- [ACOSOLO](https://github.com/gilleschardon/acosolo): implementations of some optimization based methods for source localization (CMF, Gridless methods, and others).

## Python

- [Acoular](https://github.com/acoular/acoular): provides the possibility of using several algorithms for beamforming, as well as deconvolution methods, signal generators, and other tools.
  - *[Link to the article on ResearchGate.](https://www.researchgate.net/publication/308351201_A_Python_framework_for_microphone_array_data_processing)*

- [Augen](https://github.com/eac-ufsm/augen): is designed to create a direct integration between [Acoular](https://github.com/acoular/acoular) and [Amiet Tools](https://github.com/fchirono/amiet_tools). It also provides a few functions written in Matlab to provide support for using toolboxes like [ITA-Toolbox](https://git.rwth-aachen.de/ita/toolbox) and [Beamap](https://github.com/eac-ufsm/beamap).
  - __*[Link to the article on ResearchGate.](https://www.researchgate.net/publication/363031873_Integracao_de_multiplas_toolboxes_para_aplicacao_em_beamforming_e_aeroacustica)*__

- [SpectAcoular](https://github.com/acoular/spectacoular): is an [Acoular](https://github.com/acoular/acoular) extension built to provide the usage of the toolbox with a Graphical User Interface (GUI). Moreover, is considered as being well suited for educative and demo purposes.

- [DeconvBFNet](https://gitlab.isae-supaero.fr/daep/deconvbfnet): offers convolutional neural network used to deconvolute beamforming maps.
  - *[Link to the article.](https://www.ingentaconnect.com/content/ince/incecp/2021/00000263/00000001/art00057)*

- [Beamlib](https://gitlab.isae-supaero.fr/acoustic-beamforming/beamlib): being part of the POLA3 project, this library offers a tool for performing acoustic beamforming (a series of algorithms) from signals obtained with an array of microphones (generation and evaluations of the arrays).

- [Arlpy](https://github.com/org-arl/arlpy): has a few algorithms for beamforming.

- [AcouPipe](https://github.com/adku1173/acoupipe): extends [Acoular](https://github.com/acoular/acoular) by allowing the generation of unique acoustical source localization and characterization data sets that can be used for training of deep neural networks and machine learning.

- [ACOSOLO](https://github.com/gilleschardon/acosolo): implementations of some optimization based methods for source localization (CMF, Gridless methods, and others).

- [Beamforming-for-speech-enhancement](https://github.com/AkojimaSLP/Beamforming-for-speech-enhancement): a series of simple implementations (DSB, MVDR and CGMM-MVDR) for speech enhancement.

- [Pyroomacoustics](https://github.com/LCAV/pyroomacoustics): a toolbox includying implementations on room acoustics and beamforming like DSB and direction of arrival (DOA) finding. Reference paper: [Pyroomacoustics: A Python Package for Audio Room Simulation and Array Processing Algorithms](https://www.researchgate.net/publication/320344643_Pyroomacoustics_A_Python_Package_for_Audio_Room_Simulation_and_Array_Processing_Algorithms).

## Julia

- [AeroAcoustics.jl](https://github.com/1oly/AeroAcoustics.jl): provides methods for working with microphone array measurements. Offers as well utilities for processing beamforming and other acoustic imaging methods.
