# UNESP-BERT: BoltEd stRucTure from UNESP SHM Lab/Ilha Solteira

To download the data set of vibration of a bolted joint structure from UNESP SHM Lab, please fill the form:

https://forms.gle/2PUVefGLegZbkpKt5

__________________________________________________________________________________________________
# Description

The experimental test rig is nonlinearly dependent on excitation amplitude, presenting the friction joints' well-known softening effect. The structure presents data variation related to the presence of uncertainties in the measurement process. The experimental measurements were conducted through different days, and only the tightening torque in the joint connection was controlled after each experimental realization. 

<img src="TestBench.jpg " width="35%">

The figure above presents the joint structure investigated. The test rig comprises two aluminum beams, each with dimensions of 270 mm x 25.4 mm x 6.35 mm, and assembled by a bolted-joint connection with a tightening torque of 5 Nm. The structure's excitation was conducted by a Modal Shop 2400E shaker located at 85 mm from the clamped end of the cantilever beam to minimize shaker/structure interaction. Due to observability purposes for modeling the structure's first vibration mode, the system output was measured at the free end of the beam, using a laser vibrometer Polytec OFV-525/5000S. The schematic top view of the experimental setup is shown below.

<img src="esquema.png " width="40%">

The data acquisition system was the LMS SCADAS. Several excitation tests were conducted on the structure:
<li> Sweeping sine tests over the frequency ranges of 0 up to 40 Hz and 70 up to 110 Hz, both with a sweep rate of 5 Hz/s, and 0 up to 110 Hz with a sweep rate of 13.75 Hz/s; </li><br>
<li> White noise excitation over the frequency range of 0-110 Hz; </li><br>
<li> Stepped sine tests over the frequency range of 3 up to 23 Hz, with a sweep rate of 1 Hz/min; </li><br>
<li> Pure sine in steady state regime at the following frequencies: 5, 5.5, 6, 6.5, 6.75, 8, 8.5, 9, 9.5, 9.75, 16, 17, 18 and 19 Hz, with a total testing time at each frequency of 64 seconds. </li><br>

For each excitation test, the different levels of input amplitude 0.05 V (low), 0.10 V (medium) and 0.20 V (high) were supplied in the shaker amplifier. This paper regards the voltage supplied by the shaker amplifier as the excitation signal since it is easier to keep this signal constant over a frequency range. All signals were measured with a sampling frequency of 1024 Hz.

__________________________________________________________________________________________________
# Authors

  <li>Rafael Teloli</li>
  <li>Luccas Miguel</li>
  <li>Samuel da Silva</li>

__________________________________________________________________________________________________
# How to cite

The data are still available for non-commercial research under the following terms: (i) the SHM Lab at UNESP/Ilha Solteira should be acknowledged as the source of the data; (ii) in publications, relevant publications by members of the SHM Lab at UNESP/Ilha Solteira should be cited; (iii) this benchmark should be cited as UNESP-BERT.

This dataset was used in these papers:

  <li>Teloli, R. O. ; da Silva, Samuel ; Ritto, T. G. ; Chevalier, G. . Bayesian Model Identification of Higher-Order Frequency Response Functions for Structures Assembled by Bolted Joints. Mechanical Systems and Signal Processing, 2020. </li><br>

  <li>Miguel, L. P. ; Teloli, R. O. ; da Silva, Samuel . Some practical regards on the application of the harmonic balance method for hysteresis models. Mechanical Systems and Signal Processing, v. 143, p. 106842, 2020. https://doi.org/10.1016/j.ymssp.2020.106842</li><br>

  <li>Teloli, R. O. ; da Silva, Samuel . A new way for harmonic probing of hysteretic systems through nonlinear smooth operators. Mechanical Systems and Signal Processing, v. 121, p. 856-875, 2019. https://doi.org/10.1016/j.ymssp.2018.11.044</li><br>

If you are using a LaTeX Editor, you can cite the papers above using these BibTeX citations:

```
@article{teloli2020bayesian,
  title={Bayesian Model Identification of Higher-Order Frequency Response Functions for Structures Assembled by Bolted Joints},
  author={Teloli, Rafael de O and da Silva, Samuel and Ritto, Thiago Gamboa and Chevallier, Ga{\"e}l},
  journal={Mechanical Systems and Signal Processing},
  year={2020},
  publisher={Elsevier}
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
