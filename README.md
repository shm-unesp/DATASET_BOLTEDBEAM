# BERT: BoltEd stRucTure

To download the data set of vibration of a bolted joint structure from UNESP SHM Lab, please fill the form:

https://forms.gle/2PUVefGLegZbkpKt5

__________________________________________________________________________________________________
# Description

The experimental test rig is nonlinearly dependent on excitation amplitude, presenting the friction joints' well-known softening effect. The structure presents data variation related to the presence of uncertainties in the measurement process. The experimental measurements were conducted through different days, and only the tightening torque in the joint connection was controlled after each experimental realization by a torque wrench. The dataset consisted of vibration tests performed for three different tightening torques: 5, 7, and 9 Nm. The tightening torque on both bolts was always the same for each realization.

<img src="TestBench.jpg " width="35%">

The figure above presents the joint structure investigated. The test rig comprises two aluminum beams, each with dimensions of 270 mm x 25.4 mm x 6.35 mm, and assembled by a bolted-joint connection. The structure's excitation was conducted by a Modal Shop 2400E shaker located at 85 mm from the clamped end of the cantilever beam to minimize shaker/structure interaction. Due to observability purposes for modeling the structure's first vibration mode, the system output was measured at the free end of the beam, using a laser vibrometer Polytec OFV-525/5000S. The schematic top view of the experimental setup is shown below.

<img src="esquema.png " width="40%">

The data acquisition system was the LMS SCADAS. Several excitation tests were conducted on the structure:
<li> Sweeping sine tests over the frequency ranges of 0 up to 40 Hz and 70 up to 110 Hz, both with a sweep rate of 5 Hz/s, and 0 from up to 110 Hz with a sweep rate of 13.75 Hz/s; </li><br>
<li> White noise excitation over the frequency range of 0-110 Hz; </li><br>
<li> Stepped sine tests over the frequency range of 3 to 23 Hz, 23 to 3 Hz, 85 to 105 Hz and 105 to 85 Hz, with a testing time at each frequency of 32 seconds and a frequency step of 0.1 Hz; </li><br>
<li> Pure sine in steady state regime at the following frequencies: 5, 5.5, 6, 6.5, 6.75, 8, 8.5, 9, 9.5, 9.75, 16, 17, 18 and 19 Hz, with a total testing time at each frequency of 64 seconds. </li><br>

For the stepped sine test, the different levels of input amplitude 0.05 V (low), 0.10 V (medium) and 0.15 V (high), for the frequency range 3 to 23 Hz, and 0.01 V (low), 0.05 V (medium) and 0.10 V (high), for the frequency range 85 to 105 Hz, were supplied in the shaker amplifier. These signals were measured with a sampling frequency of 1600 Hz. For the other tests, the levels of input amplitude were 0.05 V, 0.10 V, 0.15 V, 0.20 V, 0.25 V and 0.30 V. These signals were measured with a sampling frequency of 1024 Hz. This experimental setup regards the shaker amplifier's voltage as the excitation signal since it is easier to keep this signal constant over a frequency range.
__________________________________________________________________________________________________
# Authors

  <li>Rafael Teloli</li>
  <li>Luccas Miguel</li>
  <li>Samuel da Silva</li>

__________________________________________________________________________________________________
# How to cite

The data are still available for non-commercial research under the following terms: (i) the SHM Lab at UNESP/Ilha Solteira should be acknowledged as the source of the data; (ii) in publications, relevant publications by members of the SHM Lab at UNESP/Ilha Solteira should be cited; (iii) this benchmark should be cited as UNESP-BERT.

This dataset was used in these papers:

  <li>Teloli, R. O. ; da Silva, Samuel ; Ritto, T. G. ; Chevalier, G. . Bayesian Model Identification of Higher-Order Frequency Response Functions for Structures Assembled by Bolted Joints. Mechanical Systems and Signal Processing, v. 151, p. 107333, 2021, https://doi.org/10.1016/j.ymssp.2020.107333 </li><br>

  <li>Miguel, L. P. ; Teloli, R. O. ; da Silva, Samuel . Some practical regards on the application of the harmonic balance method for hysteresis models. Mechanical Systems and Signal Processing, v. 143, p. 106842, 2020. https://doi.org/10.1016/j.ymssp.2020.106842</li><br>

  <li>Teloli, R. O. ; da Silva, Samuel . A new way for harmonic probing of hysteretic systems through nonlinear smooth operators. Mechanical Systems and Signal Processing, v. 121, p. 856-875, 2019. https://doi.org/10.1016/j.ymssp.2018.11.044</li><br>

If you are using a LaTeX Editor, you can cite the papers above using these BibTeX citations:

```
@article{TELOLI2021107333,
title = "Bayesian model identification of higher-order frequency response functions for structures assembled by bolted joints",
journal = "Mechanical Systems and Signal Processing",
volume = "151",
pages = "107333",
year = "2021",
issn = "0888-3270",
doi = "https://doi.org/10.1016/j.ymssp.2020.107333",
url = "http://www.sciencedirect.com/science/article/pii/S0888327020307196",
author = "Rafael de O. Teloli and Samuel {da Silva} and Thiago G. Ritto and Gaël Chevallier",
keywords = "Hysteretic systems, Higher-order frequency response function, Volterra series, Jointed structures, Bayesian identification",
}

@article{miguel2020some,
  title={Some practical regards on the application of the harmonic balance method for hysteresis models},
  author={Miguel, Luccas Pereira and de Oliveira Teloli, Rafael and da Silva, Samuel},
  journal={Mechanical Systems and Signal Processing},
  volume={143},
  pages={106842},
  year={2020},
  publisher={Elsevier},
  doi = {https://doi.org/10.1016/j.ymssp.2020.106842}
}

@article{teloli2019new,
  title={A new way for harmonic probing of hysteretic systems through nonlinear smooth operators},
  author={Teloli, Rafael de O and da Silva, Samuel},
  journal={Mechanical Systems and Signal Processing},
  volume={121},
  pages={856--875},
  year={2019},
  publisher={Elsevier},
  doi = {https://doi.org/10.1016/j.ymssp.2018.11.044}
}
```
__________________________________________________________________________________________________
# License

<img src="licenca.png" width="10%">
Creative Commons Attribution-NonCommercial-ShareAlike (CC-BY-NC-SA):

A creative commons license that bans commercial use and requires you to release any modified works under this license.

__________________________________________________________________________________________________
# Funding

São Paulo Research Foundation (<a href="http://www.fapesp.br">FAPESP</a>), grant numbers 	16/21973-5, 18/14528-0, 19/06540-3, 19/19684-3, Brazilian National Council for Scientific and Technological Development (<a href="http://www.cnpq.br/">CNPq</a>), grant number 306526/2019-0, and Brazilian Coordination for the Improvement of Higher Education Personnel (<a href="https://www.gov.br">CAPES</a>)-Finance Code 001 funded this experimental setup.

<img src="sponsors.jpg " width="50%">
