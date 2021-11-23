---
layout: page
title: About
permalink: /about/
---

---

### What is Debussy?
Debussy is a package of programs implementing a fast approach to the Debye Scattering Equation (DSE), for computing total scattering data from nanocrystalline and/or defective materials. It is written in Fortran90, while its GUI is in Python3. Is a free open-source software published under the terms of the [GNU General Public License Version 3] [1].

[1]: <https://www.gnu.org/licenses/gpl-3.0.txt> "gpl-3.0"


### What can Debussy do?
Debussy can be used to perform a full analysis of Small angle (SAXS) and Wide angle (WAXS) total scattering data, from modelling to fitting.

A common analysis workflow consist in two main steps:
1. Building a database of atomic clusters of variable size where the atomic coordinates and the inter-atomic distances are stored. This is performed by the **Claude** (`Crystalline LAyered User DatabasE`) module. Different clusters shapes (e.g. spheres, cubes, prisms, cylinders...) are available.

2. Calculation of the Debye function and refinement of model parameters against SAXS/WAXS data. This is performed by the **Debussy** (`DEBye USer SYstem`) module. The program offers different kind of global optimisation algorithms to refine the model against experimental total scattering data and to extract quantitative structural informations like: lattice constants, strain, site occupation factors, thermal parameters and domain size distributions.<br>

You can find how to get started with Debussy [here] [2]. If you have questions about Debussy, [contact us] [mailto]!

[2]: <https://debyeusersystem.github.io/getting-started/> "Getting Started"
[mailto]: <mailto:federica.bertolotti@uninsubria.it;antonietta.guagliardi@ic.cnr.it;ruggero.frison@protonmail.ch;antonio.cervellino@psi.ch>


### What are the features of Debussy?
Here some of the main features of Debussy:
- Analysis on single- or multiple-phase specimens;
- Fitting on one or more experimental data set simultaneously (e.g. SAXS and WAXS datasets);
- Fitting of data sets collected with synchrotron or laboratory X-ray instruments;
- All scattering amplitudes/factors of atomic species are already encoded into the program;
- Background components treated with experimental data or Chebyshev polynomials;
- Modelling of lattice expansions/contractions, site occupancy factors, Debye-Waller factors upon cluster sizes variation.


### Who made Debussy and when?
In 2006 [Antonio Cervellino] [3] and [Antonietta Guagliardi] [4] developed a [new approach for the evaluation of Fourier patterns of model structures] [5]. This made feasible the employment of a DSE-based technique to model scattering data from nanomaterials. Few years later, in 2010, the same authors released [the first version of Debussy] [6], that included a full workflow to perform data analysis, from modelling to fitting. <br>

In 2015, [Antonio Cervellino] [3], [Ruggero Frison] [7], [Federica Bertolotti] [8] and [Antonietta Guagliardi] [4] released the [Debussy 2.0] [9]. This update introduced many new features, including a Graphical User Interface (GUI), the treatment of Compton scattering and a more robust statistical treatment of fitting parameters. <br>

Debussy is still developed and maintained by the jointed efforts of [ToScaLab members] [10] (Uninsubria/IC-CNR), [Antonio Cervellino] [3] (SLS/PSI) and [Ruggero Frison] [7] (UZH).

[3]: <https://www.psi.ch/en/lsc/people/antonio-cervellino> "Antonio Cervellino - PSI"
[4]: <http://toscalab.uninsubria.it/index.php/people> "Antonella Guagliardi - CNR"
[5]: <https://doi.org/10.1002/jcc.20407> "On the efficient evaluation of Fourier patterns for nanoparticles and clusters - J Comput Chem"
[6]: <https://doi.org/10.1107/S0021889810041889> "DEBUSSY - J Appl Cryst"
[7]: <https://www.physik.uzh.ch/groups/chang/people.php> "Ruggero Frisson - UZH"
[8]: <http://toscalab.uninsubria.it/index.php/people> "Fderica Bertolotti - University of Insubria"
[9]: <https://doi.org/10.1107/S1600576715020488> "DEBUSSY 2.0: the new release - J Appl Cryst"
[10]: <http://toscalab.uninsubria.it/index.php/people> "ToScaLab crew"


### How can I find out more about Debussy?
If you want to learn how to use the software, visit the [getting started] [2] section of this website. <br>
The full documentation of the software is provided in the [manuals] [11]. <br>
For an in-depth explanation of the central concepts regarding the software and their implementations please refer to the following publications:
- [A. Cervellino, R. Frison, F. Bertolotti and  A. Guagliardi, *J. Appl. Cryst.*, **2015**, *48*, 2026-2032] [9];
- [A. Cervellino, C. Giannini and  A. Guagliardi, *J. Appl. Cryst.*, **2010**, *43*, 1543-1547] [6];
- [A. Cervellino, C. Giannini and  A. Guagliardi, *J. Comput. Chem.*, **2006**, *27*, 995-1008] [5]. <br/>

If you are interested in attending a school on how to use Debussy and total-scattering approaches, we suggest following the news of the [ToScaLab] [12] social profile on [Facebook] [12fb]. A school on the topic is generally held once a year.

[11]: <https://sourceforge.net/projects/debussy/files/2.2/MANUALS.zip/download> "MANUALS.ZIP"
[12]: <http://toscalab.uninsubria.it/> "ToScaLab website"
[12fb]: <https://www.facebook.com/toscalabCO> "facebook page"


### What has been done with Debussy?
Here some highlight studies:
- [Band Gap Narrowing in Silane-Grafted ZnO Nanocrystals. A Comprehensive Study by Wide-Angle X-ray Total Scattering Methods.] [13]
- [On the amorphous layer in bone mineral and biomimetic apatite: A combined small- and wide-angle X-ray scattering analysis.] [14]
- Structure, Morphology, and Faceting of TiO<sub>2<sub> Photocatalysts by the Debye Scattering Equation Method. The P25 and P90 Cases of [Study.] [15]
- Crystal Structure, Morphology, and Surface Termination of Cyan-Emissive, Six-Monolayers-Thick CsPbBr_3 Nanoplatelets from X-ray Total [Scattering.] [16]
- [Size-Dependent Fault-Driven Relaxation and Faceting in Zincblende CdSe Colloidal Quantum Dots.] [17]
- [When Crystals Go Nano–The Role of Advanced X‐ray Total Scattering Methods in Nanotechnology.] [18]
- [Coherent nanotwins and dynamic disorder in caesium lead halide perovskite nanocrystals.] [19]
- [Crystal symmetry breaking and vacancies in colloidal lead chalcogenide quantum dots.] [20]
- [Crystal Size, Morphology, and Growth Mechanism in Bio-Inspired Apatite Nanocrystals.] [21]
- [Magnetite–Maghemite Nanoparticles in the 5–15 nm Range: Correlating the Core–Shell Composition and the Surface Structure to the Magnetic Properties.] [22]
- [From Paracrystalline Ru(CO)_4 1D Polymer to Nanosized Ruthenium Metal.] [23]
- [Size and Shape Dependence of the Photocatalytic Activity of TiO<sub>2<sub> Nanocrystals.] [24]
- [Determination of nanoparticle structure type, size and strain distribution from X-ray data for monatomic fcc-derived non-crystallographic nanoclusters.] [25]

[13]: <https://doi.org/10.1021/acs.jpcc.0c10502>
[14]: <https://doi.org/10.1016/j.actbio.2020.04.026>
[15]: <https://doi.org/10.3390/nano10040743>
[16]: <https://doi.org/10.1021/acsnano.9b07626>
[17]: <https://doi.org/10.1021/acsnano.8b07092>
[18]: <https://doi.org/10.1002/ejic.201800534>
[19]: <https://doi.org/10.1021/acsnano.7b00017>
[20]: <https://doi.org/10.1038/nmat4661>
[21]: <https://doi.org/10.1002/adfm.201302075>
[22]: <https://doi.org/10.1021/cm403360f>
[23]: <https://doi.org/10.1021/cg3004504>
[24]: <https://doi.org/10.1021/ja110225n>
[25]: <https://doi.org/10.1107/S0021889803013542>

