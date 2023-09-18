---
permalink: /software/
title: "Scientific Software"
toc: true
toc_sticky: true
---

After almost 10 years of experience in experimental structural biology, in 2016
I became a dedicated software developer in the field. I developed new
methodologies to improve protein modeling, streamlined data analysis, wrote
smaller software packages, and engineered complex software suites such as
IDPConformerGenerator and HADDOCK3, and FarSeer-NMR.  On top of that, out of my
passion, I specialized in designing modular and maintainable software and
open-source best practices, which I have lectured about.
{: .text-justify}

## Opinion and technical articles

I enjoy writing about advanced programming concepts and
implementation solutions for particular problems. You can find my posts at
[DEV.to][devto] and [PythonicThoughtsSnippets][pts]; from which I highlight the
[Rethinking Python Decorators](https://dev.to/joaomcteixeira/rethinking-python-decorators-2g53) post.

## Talks

1. "Modular code for a modular software: developing HADDOCK3".  
  [Instruct][instruct] Software Developers Exchange Webinar 5, June 10th, **2022**, *invited*.  
  [Website](https://instruct-eric.eu/content/instruct-software-developers-exchange-webinar-series) |
  [Twitter](https://twitter.com/joaomcteixeira/status/1529025387224768512) |
  [LinkedIn](https://www.linkedin.com/posts/joaomcteixeira_software-developer-exchange-5-modular-activity-6942532657725513728-hi9h/?utm_source=linkedin_share&utm_medium=member_desktop_web) |
  [Youtube](https://www.youtube.com/watch?v=5Uk1EvzCOIg) |
  [Slides](https://docs.google.com/presentation/d/1vW8CtNTLh0UDBjxsfz5f_Td8v-IEX6xY5SExv3SgpPk)  

1. "Introducing HADDOCK3: Enabling modular integrative modelling pipelines"  
  [BioExcel][bioexcel] Webminar, June 7th, **2022**, *invited*  
  [Website](https://bioexcel.eu/webinar-introducing-haddock3-enabling-modular-integrative-modelling-pipelines-2022-05-24/) |
  [Twitter](https://twitter.com/joaomcteixeira/status/1531942717726593025) |
  [LinkedIn](https://www.linkedin.com/posts/joaomcteixeira_bioexcel-webinar-67-introducing-haddock3-activity-6942780130758959104-Losw?utm_source=linkedin_share&utm_medium=member_desktop_web) |
  [Youtube](https://www.youtube.com/watch?v=V7uwFbVDKFE) |
  [Slides](https://docs.google.com/presentation/d/1C8KngBXWAF-6FJkP7DH-j6E1LKwYzqtwS2SSS_g-riM)  

1. "Effective open-science practices for organizing a scientific software repository - extended"  
  International Symposium on Grids & Clouds (ISGC), 20-25th March, **2022**, Virtual Conference.  
  [Abstract](https://docs.google.com/document/d/1dZ4XsI7UahdoSINcNuOiH8T_bZtaHDUMDc1-4qcFDQk) |
  [Slides](https://docs.google.com/presentation/d/1phdI7Q0aiK1dwh7TAcvNqlGVObWLq__WuZ-TUD5XRfM)  

1. "Effective open-science practices for organizing a scientific software repository - short"  
  OSCU Open Science Symposium - Faculty of Science, October 10th, **2021**, Utrecht University, Netherlands.  
  [Slides on OSF](https://osf.io/ghfbr/) |
  [Slides on GDrive](https://docs.google.com/presentation/d/1rD5H7Eps5LHKQAhu21KFywDxbKawOalfXWVDYVVTL0U)  

## Scientific Software

### IDPConformerGenerator

IDPConformerGenerator is a flexible software suite for sampling the
conformational space of Intrinsically Disordered Proteins which must be described
as structural ensembles. IDPCG is a flexible, highly-competitive, and modular
open-source software platform for generating large and diverse ensembles of
disordered protein states that builds conformers that obey geometric, steric,
and other physical restraints on the input sequence. IDPConformerGenerator
samples backbone phi (φ), psi (ψ), and omega (ω) torsion angles of relevant
sequence fragments from loops and secondary structure elements extracted from
folded protein structures in the RCSB Protein Data Bank and builds side chains
from robust Monte Carlo algorithms using expanded rotamer libraries.
IDPConformerGenerator is also able to model loops and terminal tails in the
presence of complexes and membrane bilayers!
<a href="https://github.com/julie-forman-kay-lab/IDPConformerGenerator"><img src="../assets/images/github-mark.svg" alt="idpcg" style="width:35px;"/></a>
<a href="https://pubs.acs.org/doi/full/10.1021/acs.jpca.2c03726"><img src="../assets/images/paper.png" alt="idpcg" style="width:38px;"/></a>
<a href="https://www.biorxiv.org/content/10.1101/2023.07.25.550520v1"><img src="../assets/images/paper.png" alt="ldrs" style="width:38px;"/></a>
{: .text-justify}

<img src="../assets/images/idpconfgen_graph_abs.png" alt="IDPCG" style="width:700px;"/>{: .align-center}

### HADDOCK3

*"HADDOCK3 is the next generation integrative modelling software in the
long-lasting HADDOCK project. It represents a complete rethinking and rewriting
of the HADDOCK2.X series, implementing a new way to interact with HADDOCK and
offering new features to users who can now define custom workflows
... [read more](https://www.bonvinlab.org/haddock3/intro.html)"*
<a href="https://github.com/haddocking/haddock3"><img src="../assets/images/github-mark.svg" alt="haddock3" style="width:35px;"/></a>
{: .text-justify}

<img src="../assets/images/haddock3_t.png" alt="haddock3" style="width:700px;"/>{: .align-center}

### pdb-tools

`pdb-tools` is *a swiss army knife for manipulating and editing PDB files*. It
is an ecosystem of more than 40 commands users can chain freely to allow maximum
versatility. `pdb-tools` is written entirely in Python standard library,
requiring no dependencies.
<a href="https://github.com/haddocking/pdb-tools"><img src="../assets/images/github-mark.svg" alt="pdbtools" style="width:35px;"/></a>
<a href="https://doi.org/10.12688/f1000research.17456.1"><img src="../assets/images/paper.png" alt="pdbtools" style="width:38px;"/></a>
{: .text-justify}

<img src="http://www.bonvinlab.org/pdb-tools/logo/pdb-tools.png" alt="pdbtools" style="width:450px;"/>{: .align-center}

### SPyCi-PDB

SPyCi-PDB is a user-friendly Python interface to back-calculate experimental
data for singular or ensembles of PDB structures. SPyCi-PDB can calculate NMR
chemical shifts, NOE, J-couplings, PRE, RDCs, SAXS, and hydrodynamic radius.
<a href="https://github.com/julie-forman-kay-lab/SPyCi-PDB"><img src="../assets/images/github-mark.svg" alt="spyci" style="width:35px;"/></a>
<a href="https://github.com/openjournals/joss-reviews/issues/4861"><img src="../assets/images/paper.png" alt="spyci" style="width:38px;"/></a>
{: .text-justify}

<img src="https://raw.githubusercontent.com/julie-forman-kay-lab/SPyCi-PDB/0e7b60d50a021d741dd7db4e2b9fbb9605fec95b/docs/spycipdb_ascii1.png" alt="spyci" style="width:450px;"/>{: .align-center}

### Python project skeleton

Python-project-skeleton is a template repository where I explain how to
configure a python package using the latest best practices in open-source
software. PPS has an efficient package structure, documentation, tests, and
continuous integration actions covering all needs for automatic deployment.
Others can use PPS as a template for their projects or navigate around it for
educational purposes because I thoroughly document all strategies I adopted.
<a href="https://github.com/joaomcteixeira/python-project-skeleton"><img src="../assets/images/github-mark.svg" alt="pps" style="width:35px;"/></a>
{: .text-justify}

<img src="../assets/images/python-project-skeleton-bt.png" alt="pdbtools" style="width:450px;"/>{: .align-center}

### taurenmd

*taurenmd* is a command-line ecosystem to analyze and manipulate Molecular
Dynamics trajectories. I wrote *taurenmd* to have a centralized platform with a
common API that leverages the potential of several software, such as MDAnalysis
and MDtraj. *taurenmd* also serves as a hub to implement standardized protocols
for MD analysis. *taurenmd* can be used as a python library but is was designed
to work mainly as command-lines.
<a href="https://github.com/joaomcteixeira/taurenmd"><img src="../assets/images/github-mark.svg" alt="taurenmd" style="width:35px;"/></a>
<a href="https://doi.org/10.21105/joss.02175"><img src="../assets/images/paper.png" alt="taurenmd" style="width:38px;"/></a>
{: .text-justify}

<img src="../assets/images/taurenmd.png" alt="taurenmd" style="width:700px;"/>{: .align-center}

### FarSeer-NMR

*FarSeer-NMR* is a software suite for automatic treatment, analysis and plotting
of large and multi-variable data sets of NMR peaklists of proteins. Users can
provide peaklists from complex titration schemes, for example, the same protein
against multiple ligands, a temperature range, **and** a pH range, and
*FarSeer-NMR* will calculate the spectral changes for every combination of
conditions.
<a href="https://github.com/Farseer-NMR/FarSeer-NMR"><img src="../assets/images/github-mark.svg" alt="farseer" style="width:35px;"/></a>
<a href="https://link.springer.com/article/10.1007/s10858-018-0182-5"><img src="../assets/images/paper.png" alt="farseer" style="width:38px;"/></a>
{: .text-justify}

<img src="../assets/images/farseer.png" alt="farseer" style="width:300px;"/>{: .align-center}

### mdacli

`mdacli` is a command-line interface for MDAnalysis. The aim is to provide
access to all MDAnalysis' operations via command-lines. Command lines are
created automatically from MDAnalysis analysis classes, avoiding the need to
manually update the codebase for new functionalities in the main MDAnalysis
project.
<a href="https://github.com/MDAnalysis/mdacli"><img src="../assets/images/github-mark.svg" alt="mdacli" style="width:35px;"/></a>
{: .text-justify}

<img src="../assets/images/mdacli-logo.png" alt="mdacli" style="height:200px;"/>{: .align-center}


[pts]: https://pythonicthoughtssnippets.github.io/ "Pythonic Thoughts Snippets"
[devto]: https://dev.to/joaomcteixeira "DEV.to JMCT"
[instruct]: https://instruct-eric.eu/ "INSTRUCT-ERIC"
[bioexcel]: https://bioexcel.eu/ "BioExcel"
