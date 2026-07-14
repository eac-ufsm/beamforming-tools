
# beamforming-tools

This repository contains a collection list of tools for acoustic beamforming.

Contributions are welcome, get in touch. 😊

# Free and open-source beamforming tools

A curated collection of free, open-source, and source-available tools for beamforming, direction-of-arrival estimation, microphone-array processing, acoustic imaging, robot audition, seismic-array analysis, and ultrasound imaging.

> **Last review:** 14 July 2026  
> **Scope note:** the list includes complete toolboxes, research libraries, educational implementations, integration layers, graphical interfaces, datasets, and benchmark cases. These categories are identified separately whenever possible.


## Contents

- [Acoustic imaging and general microphone-array processing](#acoustic-imaging-and-general-microphone-array-processing)
- [Speech enhancement and robot audition](#speech-enhancement-and-robot-audition)
- [Seismic and infrasound array processing](#seismic-and-infrasound-array-processing)
- [Ultrasound beamforming and image reconstruction](#ultrasound-beamforming-and-image-reconstruction)
- [Educational, demonstration, and hardware-oriented projects](#educational-demonstration-and-hardware-oriented-projects)
- [Datasets and benchmarking resources](#datasets-and-benchmarking-resources)
- [Surveys and general references](#surveys-and-general-references)

---

## Acoustic imaging and general microphone-array processing

### MATLAB and GNU Octave

- [Beamap](https://github.com/eac-ufsm/beamap) — Educational toolbox with beamforming algorithms, microphone-array geometry generation, array evaluation, simulations, and acoustic-map visualization.
  - **Reference:** W. D'Andrea Fonseca *et al.*, “Teaching acoustical beamforming via active learning,” *The Journal of the Acoustical Society of America*, 2022. [DOI](https://doi.org/10.1121/10.0013570).

- [ITA-Toolbox](https://git.rwth-aachen.de/ita/toolbox) — Broad acoustics framework that includes measurement, signal processing, array geometries, beamforming routines, visualization, and interfaces for laboratory hardware.
  - [Official website and documentation](https://www.ita-toolbox.org/)
  - **Reference:** M. Berzborn *et al.*, “The ITA-Toolbox: An Open Source MATLAB Toolbox for Acoustic Measurements and Signal Processing,” *DAGA*, 2017. [Paper](https://pub.dega-akustik.de/DAGA_2017/data/articles/000257.pdf).

- [ACOSOLO](https://github.com/gilleschardon/acosolo) — MATLAB and Python implementations of optimization-based acoustic source localization methods, including covariance-matrix fitting and gridless approaches.

- [Acoustic-Beamforming](https://github.com/Anwar-M/Acoustic-Beamforming) — Conventional acoustic beamforming with alternative steering-vector formulations, convection corrections, and scripts for publication-ready plots.

- [Acoustic-Beamforming-Methods](https://github.com/HauLiang/Acoustic-Beamforming-Methods) — Demonstrations of conventional and advanced beamforming methods.

- [Acoustic-Beamforming-Advanced](https://github.com/HauLiang/Acoustic-Beamforming-Advanced) — Research code associated with interpretable end-to-end real-time acoustic beamforming.

- [Beamforming by Jørgen Grythe](https://github.com/jorgengrythe/beamforming) — Delay-and-sum and array-pattern utilities for arbitrary one-, two-, and three-dimensional array geometries.
  - [Delay-and-sum File Exchange page](https://www.mathworks.com/matlabcentral/fileexchange/53294-delay-and-sum-beamforming-for-arbitrary-array-geometry)
  - [Array-factor File Exchange page](https://www.mathworks.com/matlabcentral/fileexchange/49690-array-factor-beampattern-of-discrete-array-of-any-shape)

- [MicArrayBeamforming](https://github.com/MiguelBlancoGalindo/MicArrayBeamforming) — Microphone-array design, beamformer calculation, spatial-response evaluation, and practical design examples.
  - **Reference:** M. Blanco Galindo *et al.*, “Microphone Array Beamforming Toolbox,” AES E-Library. [Publication page](https://www.aes.org/e-lib/browse.cfm?elib=20851).

- [SOFiA — Sound Field Analysis Toolbox](https://github.com/AudioGroupCologne/SOFiA) — Processing of spherical-microphone-array data, spherical-harmonic decomposition, directional impulse responses, virtual microphone signals, and sound-field visualization.
  - [Documentation](https://audiogroup.web.th-koeln.de/SOFiA_wiki/WELCOME.html)
  - **Reference:** B. Bernschütz, “SOFiA — Sound Field Analysis Toolbox,” 2011. [Paper](https://www2.users.ak.tu-berlin.de/akgroup/ak_pub/seacen/2011/Bernschuetz_2011_SOFiA_Sound_field_analysis_toolbox.pdf).

- [Spherical-Array-Processing](https://github.com/polarch/Spherical-Array-Processing) — Spherical-harmonic-domain array processing, including radial filters, beamforming weights, sound-field indicators, and localization tools.
  - [MATLAB File Exchange page](https://www.mathworks.com/matlabcentral/fileexchange/48465-acoustical-spherical-array-processing-library)

- [Fundamentals of Spherical Array Processing — companion code](https://www.mathworks.com/matlabcentral/fileexchange/68655-fundamentals-of-spherical-array-processing) — MATLAB examples supporting the theory and algorithms presented in the book *Fundamentals of Spherical Array Processing*.

### Python

- [Acoular](https://github.com/acoular/acoular) — Comprehensive framework for microphone-array data processing, acoustic source mapping, moving-source analysis, deconvolution, source simulation, and spectral characterization.
  - [Documentation](https://www.acoular.org/)
  - **Reference:** E. Sarradj and G. Herold, “A Python framework for microphone array data processing,” *Applied Acoustics*, vol. 116, pp. 50–58, 2017. [DOI](https://doi.org/10.1016/j.apacoust.2016.09.015).

- [SpectAcoular](https://github.com/acoular/spectacoular) — Browser-based graphical interface and educational front end for Acoular workflows.

- [AcouPipe](https://github.com/adku1173/acoupipe) — Acoular extension for scalable synthetic microphone-array datasets, particularly for machine-learning research.
  - **Reference:** A. Kujawski *et al.*, “A framework for generating large-scale microphone array data for machine learning,” *Multimedia Tools and Applications*, 2024. [Article](https://link.springer.com/article/10.1007/s11042-023-16947-w).

- [Augen](https://github.com/eac-ufsm/augen) — Integration layer connecting Acoular, Amiet Tools, Beamap, and ITA-Toolbox workflows.
  - **Reference:** W. D'Andrea Fonseca *et al.*, “Integração de múltiplas toolboxes para aplicação em beamforming e aeroacústica.” [ResearchGate](https://www.researchgate.net/publication/363031873_Integracao_de_multiplas_toolboxes_para_aplicacao_em_beamforming_e_aeroacustica).

- [Beamlib](https://gitlab.isae-supaero.fr/acoustic-beamforming/beamlib) — Acoustic beamforming library developed within the POLA3 project, including array geometry, signal processing, and localization routines.

- [DeconvBFNet](https://gitlab.isae-supaero.fr/daep/deconvbfnet) — Neural-network-based deconvolution of conventional beamforming maps.
  - **Reference:** [Conference paper](https://www.ingentaconnect.com/content/ince/incecp/2021/00000263/00000001/art00057).

- [ARLpy](https://github.com/org-arl/arlpy) — General array and underwater-acoustics library with time-domain delay-and-sum, broadband processing, Capon, Bartlett, and MUSIC beamformers.
  - [Beamforming documentation](https://arlpy.readthedocs.io/en/dev/bf.html)

- [doatools.py](https://github.com/morriswmz/doatools.py) — Array models, direction-of-arrival estimators, source-number estimation, and statistical performance bounds.

- [Pyroomacoustics](https://github.com/LCAV/pyroomacoustics) — Room simulation and array-processing library with delay-and-sum, MVDR, rake beamforming, MUSIC, SRP-PHAT, and room impulse-response generation.
  - **Reference:** R. Scheibler, E. Bezzam, and I. Dokmanić, “Pyroomacoustics: A Python Package for Audio Room Simulation and Array Processing Algorithms,” *ICASSP*, 2018. [DOI](https://doi.org/10.1109/ICASSP.2018.8461310).

- [Fast beamforming in Python](https://github.com/schipp/fast_beamforming) — Efficient educational notebooks for conventional and high-resolution beamforming.

- [Beamforming30](https://github.com/huangzhenyu/beamforming) — Collection of more than 30 beamforming algorithms; part of the documentation is in Chinese.

- [ACOSOLO](https://github.com/gilleschardon/acosolo) — Python components for optimization-based and gridless source localization; the repository also contains MATLAB code.

### Julia

- [AeroAcoustics.jl](https://github.com/1oly/AeroAcoustics.jl) — Microphone-array processing and aeroacoustic source-mapping methods implemented in Julia.
  - **Reference:** O. Lylloff, “AeroAcoustics.jl: A Julia package for aeroacoustics,” *Journal of Open Source Software*, vol. 9, no. 97, 6390, 2024. [DOI](https://doi.org/10.21105/joss.06390).

---

## Speech enhancement and robot audition

### Python

- [SpeechBrain](https://github.com/speechbrain/speechbrain) — General-purpose speech-processing toolkit with multichannel preprocessing, GCC-PHAT, covariance estimation, and MVDR beamforming tutorials.
  - [Multimicrophone beamforming tutorial](https://speechbrain.readthedocs.io/en/latest/tutorials/preprocessing/multi-microphone-beamforming.html)
  - **Reference:** M. Ravanelli *et al.*, “Open-Source Conversational AI with SpeechBrain 1.0,” *Journal of Machine Learning Research*, vol. 25, 2024. [Article](https://www.jmlr.org/papers/v25/24-0991.html).

- [TorchAudio beamforming functions](https://github.com/pytorch/audio) — Differentiable multichannel signal-processing components including power spectral-density estimation, Souden MVDR, RTF-based MVDR, steering-vector estimation, and beamforming-weight application.
  - [MVDR tutorial](https://pytorch.org/audio/stable/tutorials/mvdr_tutorial.html)
  - [Functional source code](https://github.com/pytorch/audio/blob/main/src/torchaudio/functional/functional.py)

- [pb_bss](https://github.com/fgnt/pb_bss) — Probabilistic blind source separation, spatial mixture models, permutation alignment, and beamforming-oriented multichannel speech processing.

- [Beamforming for speech enhancement](https://github.com/AkojimaSLP/Beamforming-for-speech-enhancement) — Compact implementations of delay-and-sum, MVDR, and CGMM-MVDR beamforming.

### C and C++

- [ODAS — Open embeddeD Audition System](https://github.com/introlab/odas) — Real-time sound-source localization, tracking, separation, and post-filtering, optimized for low-cost embedded systems.
  - **Reference:** F. Grondin *et al.*, “ODAS: Open embeddeD Audition System,” *Frontiers in Robotics and AI*, 2022. [Article](https://www.frontiersin.org/journals/robotics-and-ai/articles/10.3389/frobt.2022.854444/full).

- [BeamformIt](https://github.com/xanguera/beamformit) — Multichannel filter-and-sum beamforming for meetings and distant speech, with few assumptions about array topology or channel count.

- [HARK](https://hark.jp/) — Open-source robot-audition ecosystem with MUSIC-based localization, source tracking, GHDSS-based separation, and speech-recognition integration.
  - [Project overview](https://www.jp.honda-ri.com/en/activity/hark/)
  - **Reference:** K. Nakadai *et al.*, “Introduction to Open Source Robot Audition Software HARK.” [Paper](https://www.jsk.t.u-tokyo.ac.jp/rsj2011/_downloads/2Q2-6.pdf).

- [ManyEars](https://github.com/introlab/manyears) — Real-time localization, tracking, and separation for mobile robot audition.

- [openMHA](https://github.com/HoerTech-gGmbH/openMHA) — Open real-time hearing-aid research platform with multichannel processing and beamforming plugins.
  - **Reference:** H. Kayser *et al.*, “Open community platform for hearing aid algorithm research: open Master Hearing Aid,” 2021. [Preprint](https://arxiv.org/abs/2103.02313).

---

## Seismic and infrasound array processing

### MATLAB

- [B3AM](https://github.com/katrinloer/B3AM) — Beamforming toolbox for three-component ambient seismic-noise arrays. It estimates dispersion, propagation direction, wavefield composition, wavenumber, and polarization-dependent wave type.
  - [MATLAB File Exchange](https://www.mathworks.com/matlabcentral/fileexchange/128489-b3am)
  - **Primary reference:** K. Löer and C. Finger, “B3AM: A beamforming toolbox for three-component ambient seismic noise analysis,” *Seismica*, vol. 3, no. 2, 2024. [DOI](https://doi.org/10.26443/seismica.v3i2.1343).
  - [ResearchGate version](https://www.researchgate.net/publication/385877727_B3AM_A_beamforming_toolbox_for_three-component_ambient_seismic_noise_analysis)
  - **Related reference:** K. Löer, N. Riahi, and E. H. Saenger, “Three-component ambient noise beamforming in the Parkfield area,” *Geophysical Journal International*, vol. 213, no. 3, pp. 1478–1491, 2018. [DOI](https://doi.org/10.1093/gji/ggy058).

### Python

- [B3Ampy](https://github.com/cl-finger/B3Ampy) — Python implementation of the B3AM workflow for three-component ambient seismic-noise beamforming, including preprocessing, time-frequency analysis, frequency-wavenumber scanning, peak identification, polarization analysis, and summary plots.
  - [Archived user guide](https://fordatis.fraunhofer.de/bitstream/fordatis/364/2/README_B3AMpy.pdf)
  - **Primary reference shared with B3AM:** K. Löer and C. Finger, 2024. [DOI](https://doi.org/10.26443/seismica.v3i2.1343).
  - **Conference reference:** K. Löer, C. Finger, E. Obiri, and H. Kennedy, “A comprehensive beamforming toolbox to characterise surface and body waves in three-component ambient noise wavefields,” EGU General Assembly 2023. [DOI](https://doi.org/10.5194/egusphere-egu23-5670).

- [ObsPy](https://github.com/obspy/obspy) — Widely used seismology framework containing frequency-wavenumber and Capon-style array-processing functions.
  - [Array-analysis API](https://docs.obspy.org/packages/obspy.signal.array_analysis.html)
  - **Reference:** M. Beyreuther *et al.*, “ObsPy: A Python Toolbox for Seismology,” *Seismological Research Letters*, vol. 81, no. 3, pp. 530–533, 2010. [DOI](https://doi.org/10.1785/gssrl.81.3.530).

- [TwistPy](https://github.com/solldavid/TwistPy) — Wavefield inertial sensing, polarization analysis, filtering, and array beamforming for seismic and rotational-seismology applications.
  - [Beamforming tutorial](https://twistpy.org/examples/beamforming.html)
  - [Publications](https://twistpy.org/references.html)
  - **Reference:** D. Sollberger *et al.*, “TwistPy: An open-source Python toolbox for wavefield inertial sensing techniques,” EGU General Assembly 2023. [DOI](https://doi.org/10.5194/egusphere-egu23-7563).

- [Covseisnet](https://github.com/covseisnet/covseisnet) — Covariance-matrix methods for seismic networks, including beamforming, network-response functions, and tremor/source localization.
  - [Beamforming example](https://covseisnet.gricad-pages.univ-grenoble-alpes.fr/covseisnet/auto_examples/plot_pdf_example.html)

- [uafgeotools/array_processing](https://github.com/uafgeotools/array_processing) — Infrasound and seismic-array tools for plane-wave slowness, back-azimuth, array response, uncertainty, and spherical-wave source location.

- [doubleBeamforming](https://github.com/eileenrmartin/doubleBeamforming) — Conventional and accelerated double-beamforming workflows for ambient seismic noise.

### Julia and Fortran

- [Beamforming.jl](https://github.com/anowacki/Beamforming.jl) — Julia module for global seismic-array analysis.

- [Seismo-acoustic beamforming](https://github.com/jdassink/beamforming) — Fortran 90 routines for seismo-acoustic array processing using SAC or ASCII waveform input.

---

## Ultrasound beamforming and image reconstruction

### MATLAB

- [USTB — UltraSound ToolBox](https://github.com/unioslo/USTB) — Open toolbox for ultrasound beamforming, signal processing, image reconstruction, visualization, standardized data structures, and reproducible algorithm comparisons.
  - [Official website](https://www.ustb.no/)
  - [Examples](https://unioslo.github.io/USTB/examples/)
  - **Reference:** A. Rodriguez-Molares *et al.*, “The UltraSound ToolBox,” *IEEE International Ultrasonics Symposium*, 2017. [DOI](https://doi.org/10.1109/ULTSYM.2017.8092389).

- [QUPS](https://github.com/thorstone25/qups) — Rapid prototyping and simulation of diagnostic-ultrasound systems, with MATLAB, C, CUDA, and OpenCL support.
  - **Reference:** T. Brevett, “QUPS: A MATLAB Toolbox for Rapid Prototyping of Ultrasound Beamforming and Imaging Techniques,” *Journal of Open Source Software*, vol. 9, no. 101, 6772, 2024. [DOI](https://doi.org/10.21105/joss.06772).

- [MUST — MATLAB UltraSound Toolbox](https://www.biomecardio.com/MUST/) — Ultrasound simulation, RF/IQ processing, delay-and-sum beamforming, Doppler processing, and image reconstruction.
  - [Documentation](https://www.biomecardio.com/MUST/documentation.html)
  - **Reference:** D. Garcia, “Make the most of MUST, an open-source MATLAB UltraSound Toolbox,” *IEEE International Ultrasonics Symposium*, 2021. [DOI](https://doi.org/10.1109/IUS52206.2021.9593605).

### Python and Rust

- [PyMUST](https://github.com/creatis-ULTIM/PyMUST) — Python reimplementation of MUST for ultrasound simulation, RF/IQ processing, and image reconstruction.
  - **Reference:** G. Bernardino and D. Garcia, “PyMUST: an open-Source Python Library for the Simulation and Analysis of Ultrasound,” 2024 IEEE UFFC Joint Symposium. [DOI](https://doi.org/10.1109/UFFC-JS60046.2024.10793881).

- [vBeam](https://github.com/magnusdk/vbeam) — Fast differentiable ultrasound beamforming built on machine-learning array frameworks, supporting optimization and end-to-end differentiable workflows.

- [mach](https://github.com/Forest-Neurotech/mach) — CUDA-accelerated delay-and-sum beamformer with Python bindings for ultrafast and volumetric ultrasound imaging.
  - **Reference:** C. Guan *et al.*, “mach: ultrafast ultrasound beamforming,” 2026. [Preprint](https://arxiv.org/abs/2604.06257).

- [Ultrasound beamforming for linear arrays](https://github.com/csheaff/us-beamform-linarray) — Linear-array ultrasound beamforming implementations in Python and Rust.

### C++, CUDA, and heterogeneous computing

- [SUPRA](https://github.com/ifl-camp/supra) — Real-time, software-defined two- and three-dimensional ultrasound pipeline from beamforming to B-mode output.
  - **Reference:** R. Göbl, N. Navab, and C. Hennersperger, “SUPRA: Open Source Software Defined Ultrasound Processing for Real-Time Applications,” 2017. [Preprint](https://arxiv.org/abs/1711.06127).

- [oneAPI Ultrasound Beamforming Library](https://github.com/intel/oneAPI-Ultrasound-Beamforming-Library) — Examples of accelerated ultrasound reconstruction using Intel GPUs and FPGAs through oneAPI.

- [rtbf](https://gitlab.com/dongwoon.hyun/rtbf/-/tree/master) — GPU-based high-throughput, low-latency ultrasound beamforming.

- [ADMIRE](https://github.com/VU-BEAM-Lab/ADMIRE) — CPU and GPU implementations of the ADMIRE ultrasound reconstruction method, including real-time imaging code.

---

## Educational, demonstration, and hardware-oriented projects

### MATLAB and Python demonstrations

- [fia2022-fontes-sonoras](https://github.com/eac-ufsm/fia2022-fontes-sonoras) — Educational simulator for static and moving sound sources, Doppler effect, receiver arrays, and synthetic measurements.
  - [Associated conference presentation](https://www.fia2022.com.br/arearestrita/apresentacoes/9042.pdf)

- [Array Signal Processing Demos](https://www.mathworks.com/matlabcentral/fileexchange/55924-array-signal-processing-demos) — Reproduces numerical examples from Chapter 11 of Manolakis, Ingle, and Kogon, including spatial matched filters, optimum beamformers, sample-matrix inversion, and diagonal loading.

- [Beamforming-Simulations](https://github.com/Anwar-M/Beamforming-Simulations) — Basic beamforming experiments and simulation examples.

- [DOA Estimation via MUSIC](https://github.com/msamsami/doa-estimation-music) — Compact MATLAB MUSIC direction-of-arrival demonstration.

- [doa-tools for MATLAB](https://github.com/morriswmz/doa-tools) — MATLAB array models, direction-of-arrival estimators, and performance bounds.

- [2D Beamforming Simulator](https://github.com/Ahmed-Hajhamed/2D-Beamforming-Simulator) — Interactive real-time visualizer for phased arrays and constructive/destructive interference.

### Embedded systems and laboratory platforms

- [Acoustic source localization using MUSIC](https://github.com/VarunPwr/Hydrophone) — C implementation of MUSIC-based source localization for hydrophone arrays and autonomous underwater vehicles.

- [Acoustic array tools](https://github.com/mcbridejc/acoustic-array-tools) — Embedded STM32 and desktop experiments using PDM microphone arrays, beamforming, and source-direction estimation.

- [Acoustic Source Localization System](https://github.com/JSerwatka/Acoustic-Source-Localization-System) — LabVIEW and NI sbRIO implementation of acoustic source localization.

- [Sound visualization with an acoustic camera](https://github.com/linomp/acoustic-cam-usfq) — End-to-end educational acoustic-camera project covering array construction, acquisition, processing, and visualization.

---

## Datasets and benchmarking resources

- [Airfoil in a Kevlar-walled wind tunnel](https://github.com/MicrophoneArrayBenchmarking/airfoil-in-kevlar-walled-windtunnel) — Public microphone-array dataset and benchmark workflow used to compare Acoular and AeroAcoustics.jl.
  - **Reference:** O. A. Lylloff, G. Herold, A. Kujawski, and E. Sarradj, “State of open-source software for microphone array processing,” *10th Berlin Beamforming Conference*, 2024. [Publication record](https://orbit.dtu.dk/en/publications/state-of-open-source-software-for-microphone-array-processing/).

- [Acoular example data](https://github.com/acoular/acoular/tree/master/examples) — Example microphone geometries, time data, and processing scripts distributed with Acoular.

- [USTB datasets and examples](https://www.ustb.no/) — Standardized ultrasound data and reproducible beamforming examples.

- [PICMUS](https://www.creatis.insa-lyon.fr/Challenge/IEEE_IUS_2016/) — Plane-wave ultrasound imaging challenge datasets frequently used to compare reconstruction methods.

---

## Surveys and general references

- O. A. Lylloff, G. Herold, A. Kujawski, and E. Sarradj, “State of open-source software for microphone array processing,” *10th Berlin Beamforming Conference*, 2024. [Publication record](https://orbit.dtu.dk/en/publications/state-of-open-source-software-for-microphone-array-processing/) | [Conference literature page](https://www.bebec.eu/literature).

- E. Sarradj and G. Herold, “A Python framework for microphone array data processing,” *Applied Acoustics*, vol. 116, pp. 50–58, 2017. [DOI](https://doi.org/10.1016/j.apacoust.2016.09.015).

- W. D'Andrea Fonseca *et al.*, “Teaching acoustical beamforming via active learning,” *-   9th Berlin Beamforming Conference (BeBeC 2022)*, 2022. [Link](https://www.researchgate.net/publication/362024706_Teaching_acoustical_beamforming_via_active_learning).

- L. C. Godara, “Application of antenna arrays to mobile communications, Part II: Beam-forming and direction-of-arrival considerations,” *Proceedings of the IEEE*, vol. 85, no. 8, pp. 1195–1245, 1997. [Paper](https://www2.elo.utfsm.cl/~ipd481/Papers/godara2.pdf).

- J. Capon, “High-resolution frequency-wavenumber spectrum analysis,” *Proceedings of the IEEE*, vol. 57, no. 8, pp. 1408–1418, 1969. [DOI](https://doi.org/10.1109/PROC.1969.7278).

---

## Contribution checklist

When proposing a new entry, please include:

1. Project name and official repository or website.
2. Main programming language.
3. Application domain: acoustic imaging, speech, robotics, seismic/infrasound, ultrasound, education, or hardware.
4. Brief description of implemented beamforming or direction-of-arrival methods.
5. License, when clearly stated by the project.
6. Documentation link.
7. Peer-reviewed article, conference paper, software paper, DOI, or archived technical report, when available.
8. A note indicating whether the project is actively maintained, archived, experimental, or primarily educational.

Contributions, corrections, and reports of broken links are welcome. 😊

---
