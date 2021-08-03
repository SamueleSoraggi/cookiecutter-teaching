# Software for HPC

This page contains useful links to tutorial, learning resources, benchmark and scripts for softwares usable on HPCs. Softwares are separated into broad scientific/application categories. Each tool has small numbers on its right side, indicating on which national HPC types those softwares are already installed. The symbol :snake: means that the software is available through the conda package manager for installation, for example, on the GenomeDK Type2 HPC. Remember, you can always contact an HPC front office to inquire about the installation of packages that you need for your applications.

## ML and AI
### tensorflow  :one: :snake:
`Tensorflow` is the Google's open source library used to develop, train and deploy machine learning models. Tensorflow is implemented for `python`, but now also available in `R`

??? Links
    | Link      | Description                          |
    | :---------- | :----------------------------------- |
    | [Tensorflow homepage](https://www.tensorflow.org/)       | Tensorflow home page. Contains many tutorials and howtos.  |
    | [Learning material](https://www.tensorflow.org/resources/learn-ml) | Books and courses in machine learning using tensorflow |
    | [R guide to tensorflow](https://tensorflow.rstudio.com/) | How to install and use tensorflow in `Rstudio` |
    
### pyTorch     :one: :snake:
`Pytorch` is another Machine Learning framework created mainly by Facebook.

??? Links
    | Link      | Description                          |
    | :---------- | :----------------------------------- |
    | [PyTorch homepage](https://pytorch.org/) | The official `pyTorch` homepage, contains tutorials to learn how to use the framework |
    | [PyTorch book](https://pytorch.org/assets/deep-learning/Deep-Learning-with-PyTorch.pdf) | A free book about deep learning with `pyTorch` | 
    | [PyTorch for deep learning](https://www.youtube.com/watch?v=GIsg-ZUy0MY) | A full video tutorial on `PyTorch` |

## Astrophysics and Cosmology
### COSMOMC :one: 
CosmoMC is a Fortran 2008 Markov-Chain Monte-Carlo (MCMC) engine for exploring cosmological parameter space, together with Fortran and python code for analysing Monte-Carlo samples and importance sampling (plus a suite of scripts for building grids of runs, plotting and presenting results). The code does brute force (but accurate) theoretical matter power spectrum and Cl calculations with CAMB.

??? Links
    | Link      | Description                          |
    | :---------- | :----------------------------------- |
    | [CosmoMC homepage](https://cosmologist.info/cosmomc/) | The official homepage contains the documentation of `CosmoMC`|
    | [Introduction to CAMB and CosmoMC](http://background.uchicago.edu/~whu/Courses/Ast448_18/zacharegkas.pdf) | A presentation to introduce `CosmoMC` and `CAMB`|
    | [Tutorial for CosmoMC](http://icg.port.ac.uk/~jschewts/cantata/CAMB/CosmoMC_lecture.pdf) | A lecture with usage example of `CosmoMC` |
    | [CosmoMC Paper](https://arxiv.org/abs/1808.05080 http://www.uco.es/~ajcuesta/cosmomc-ugr---day-2.pdf) | Reference paper of `CosmoMC` |

## Big data and HPDA
### KNIME :one:
A tool to easily read and transform data, model and visualize it, integrate data science practices and produce insights.

??? Links
    | Link      | Description                          |
    | :---------- | :----------------------------------- |
    | [Getting started](https://www.knime.com/getting-started-guide) | A practical example of data reading and manipulation|
    | [KNIME platform presentation](https://www.knime.com/sites/default/files/KNIME%20Analytics%20Platform%20Course%20for%20Beginners.pdf) | Slides listing the KNIME properties and tools|
    | [FORUM](https://forum.knime.com/) | Koin the community of users and ask/answer questions and problems |
    | [KNIME learning](https://www.knime.com/learning) | A wide range of learning material to use KNIME proficiently |


### TRACER :one: :snake:
Tracer is graphical tool for visualization and diagnostics of MCMC output. It can read output files from MrBayes and BEAST.

??? Links
    | Link      | Description                          |
    | :---------- | :----------------------------------- |
    | [TRACER documentation](https://www.beast2.org/tracer-2/) | Home page of `Beast2`, of which `tracer` is a tool. It contains tutorials and documentation.|

## Bioinformatics

### ANGSD :snake:
A command line tool that integrates many different tools to analyze NGS data efficiently through native C++ implementation, multithreading support and calculation of genotype likelihoods instead of genotype calling. It is easily installed by downloading it from the `GitHub` repository and compilation of the code as per the instructions in the repository readme file.

??? Links
    | Link      | Description                          |
    | :---------- | :----------------------------------- |
    | [Github repository](https://github.com/ANGSD/angsd) | Repository for download and installation|
    | [Documentation](http://www.popgen.dk/angsd/index.php/ANGSD) | Documentation for ANGSD|

### BEDtools :one: :snake:
Collectively, the bedtools utilities are a swiss-army knife of tools for a wide-range of genomics analysis tasks. The most widely-used tools enable genome arithmetic: that is, set theory on the genome. For example, bedtools allows one to intersect, merge, count, complement, and shuffle genomic intervals from multiple files in widely-used genomic file formats such as BAM, BED, GFF/GTF, VCF. While each individual tool is designed to do a relatively simple task (e.g., intersect two interval files), quite sophisticated analyses can be conducted by combining multiple bedtools operations on the UNIX command line.

??? Links
    | Link      | Description                          |
    | :---------- | :----------------------------------- |
    | [Bedtools documentation](https://bedtools.readthedocs.io/en/latest/) |The documentation page. Contains well done tutorials and examples, both for beginners and advanced users.|

### Cellranger :one:
The software pipeline used to align single cell sequencing data having Unique Molecular Identifier and coming as output from a 10X sequencing machine.

??? Links
    | Link      | Description                          |
    | :---------- | :----------------------------------- |
    | [What is cellranger](https://support.10xgenomics.com/single-cell-gene-expression/software/pipelines/latest/what-is-cell-ranger) | Description of the cellranger pipeline|
    | [Install cellranger](https://support.10xgenomics.com/single-cell-gene-expression/software/pipelines/latest/installation) | Installation guide|
    | [Use cellranger](https://support.10xgenomics.com/single-cell-gene-expression/software/pipelines/latest/using/tutorial_ov) | User guide and tutorials|

### HOMER :one: :snake:
HOMER (Hypergeometric Optimization of Motif EnRichment) is a suite of tools for Motif Discovery and next-gen sequencing analysis.  It is a collection of command line programs for UNIX-style operating systems written in Perl and C++. HOMER was primarily written as a de novo motif discovery algorithm and is well suited for finding 8-20 bp motifs in large scale genomics data.  HOMER contains many useful tools for analyzing ChIP-Seq, GRO-Seq, RNA-Seq, DNase-Seq, Hi-C and numerous other types of functional genomics sequencing data sets.

??? Links
    | Link      | Description                          |
    | :---------- | :----------------------------------- |
    | [HOMER homepage](http://homer.ucsd.edu/homer/index.html) | Software homepage|
    | [Configure HOMER](http://homer.ucsd.edu/homer/introduction/configure.html) |Setup and configuration|
    | [Tutorial](http://homer.ucsd.edu/homer/basicTutorial/index.html) | Tutorial from the official home page|

### Kallisto :one: :snake:
`Kallisto` is a program for quantifying abundances of transcripts from bulk and single-cell RNA-Seq data, or more generally of target sequences using high-throughput sequencing reads. It is based on the novel idea of pseudoalignment for rapidly determining the compatibility of reads with targets, without the need for alignment.

??? Links
    | Link      | Description                          |
    | :---------- | :----------------------------------- |
    | [Homepage](https://pachterlab.github.io/kallisto/about) | Software home page with tutorials and documentation|
    | [Kallistobus](https://www.kallistobus.tools/about) |Workflow to use kallisto to generate the expression data matrix|
    | [Reference](http://www.nature.com/nbt/journal/v34/n5/full/nbt.3519.html) |The Kallisto paper|
 
### MACS2 :one: :snake:
This tool identifies statistically significantly enriched genomic regions in ChIP- and DNase-seq data using the MACS2 algorithm (Model-Based Analysis of ChIP-Seq).

??? Links
    | Link      | Description                          |
    | :---------- | :----------------------------------- |
    | [Manual](https://chipster.csc.fi/manual/macs2.html) | MACS2 manual|
    | [Project page](https://macs3-project.github.io/MACS/) | Project page with installation and usage instructions|
    | [Tutorial](https://hbctraining.github.io/Intro-to-ChIPseq/lessons/05_peak_calling_macs.html) | A tutorial for peak calling|
    | [Reference](http://www.ncbi.nlm.nih.gov/pubmed/18798982) | Reference paper|

### Salmon :one: :snake:
Highly-accurate & wicked fast transcript-level quantification from RNA-seq reads using selective alignment. Alevin, a tool integrated in Salmon, works on 3' tagged data, such as single cell data from 10X machines.

??? Links
    | Link      | Description                          |
    | :---------- | :----------------------------------- |
    | [Salmon](https://salmon.readthedocs.io/en/latest/salmon.html) |Documentation and tutorial page for Salmon|
    | [Alevin](https://salmon.readthedocs.io/en/latest/alevin.html) |Documentation and tutorial page for Alevin-Salmon|
    | [Homepage](https://combine-lab.github.io/salmon/) |Software homepage|
    | [Reference](https://www.biorxiv.org/content/10.1101/657874v2) | Reference paper|

### SAMtools :one: :snake:
Samtools is a suite of programs for interacting with high-throughput sequencing data. It consists of three separate repositories:
- **Samtools**, Reading/writing/editing/indexing/viewing SAM/BAM/CRAM format
- **BCFtools**, Reading/writing BCF2/VCF/gVCF files and calling/filtering/summarising SNP and short indel sequence variants
- **HTSlib**, A C library for reading/writing high-throughput sequencing data

??? Links
    | Link      | Description                          |
    | :---------- | :----------------------------------- |
    | [Homepage](http://www.htslib.org/) |Documentation and tutorial page|
    | [Tutorial 1](http://quinlanlab.org/tutorials/samtools/samtools.html) |Samtools tutorial|
    | [Tutorial 2](http://davetang.org/wiki/tiki-index.php?page=SAMTools) |Blogpost on SAMtools|

### Scanpy :snake:
Scanpy is a scalable toolkit for analyzing single-cell gene expression data built jointly with anndata. It includes preprocessing, visualization, clustering, trajectory inference and differential expression testing. The Python-based implementation efficiently deals with datasets of more than one million cells.

??? Links
    | Link      | Description                          |
    | :---------- | :----------------------------------- |
    | [Homepage](https://scanpy.readthedocs.io/en/stable/) |Documentation page with tutorials, package documentation and access to example datasets ready to use|

### Seurat :snake:
Parallely to Scanpy in python, Seurat is the leading package for single cell data analysis in R.

??? Links
    | Link      | Description                          |
    | :---------- | :----------------------------------- |
    | [Homepage](https://satijalab.org/seurat/) |Documentation page with tutorials, package documentation and access to example datasets ready to use|

### Seqtk :one: :snake:
Seqtk is a fast and lightweight tool for processing sequences in the FASTA or FASTQ format. It seamlessly parses both FASTA and FASTQ files which can also be optionally compressed by gzip.

??? Links
    | Link      | Description                          |
    | :---------- | :----------------------------------- |
    | [Homepage](https://docs.csc.fi/apps/seqtk/) |Documentation page with command usage|
    | [Repository and examples](https://github.com/lh3/seqtk) |Online repository with some usage examples|

### STAR :one: :snake:
Alignment method utilizes to align sequence reads to the reference genome

??? Links
    | Link      | Description                          |
    | :---------- | :----------------------------------- |
    | [Homepage](https://github.com/alexdobin/STAR) |STAR software repository|
    | [Tutorial](hhttps://hbctraining.github.io/Intro-to-rnaseq-hpc-O2/lessons/03_alignment.html) |Online tutorial to use the STAR aligner|

## Computational fluid dynamics
### openFOAM :one:
OpenFOAM is the free, open source CFD software developed primarily by OpenCFD Ltd since 2004. It has a large user base across most areas of engineering and science, from both commercial and academic organisations. OpenFOAM has an extensive range of features to solve anything from complex fluid flows involving chemical reactions, turbulence and heat transfer, to acoustics, solid mechanics and electromagnetics.

??? Links
    | Link      | Description                          |
    | :---------- | :----------------------------------- |
    | [Homepage](https://www.openfoam.com/), [openFOAM foundation](https://openfoam.org/) |Software homepage|
    | [Forum](https://www.cfd-online.com/Forums/openfoam/) |OpenFOAM users forum|
    | [Wiki](http://openfoamwiki.net/index.php/Main_Page) |OpenFOAM (unofficial) wiki|

### ANSYS :one:


??? Links
    | Link      | Description                          |
    | :---------- | :----------------------------------- |
    | [Tutorials for Undergraduate Mechanical Engineering Courses](https://web.engr.uky.edu/~jbaker/ansystutor.html) |Exercises intended only as an educational tool to assist those who wish to learn how to use ANSYS|
    | [Basics video tutorial](https://www.youtube.com/watch?v=q-xdmKjnqS0) |Tutorial for the ANSYS basics|
    | [Introduction to static structural](https://www.youtube.com/watch?v=vnpq5zzOS48) |Video introduction to static structural with ANSYS|
    | [Simulation of 3d centrifugal pump](https://www.youtube.com/watch?v=IyjdRHwujKI) |Video guide to simulate a centrifugal pump with ANSYS|
    | [Support resources for students](https://www.ansys.com/academic/free-student-products/support-resources) |Support resources for students. Includes the possibility for a free download of the software for a tryout.|
    | [University of Alberta - ANSYS Tutorials](https://sites.ualberta.ca/~wmoussa/AnsysTutorial/) |ANSYS tutorials from the UNiversity of Alberta|

## Computational chemistry
### GROMACS :one:
GROMACS is a versatile package to perform molecular dynamics, i.e. simulate the Newtonian equations of motion for systems with hundreds to millions of particles. It is primarily designed for biochemical molecules like proteins, lipids and nucleic acids that have a lot of complicated bonded interactions, but since GROMACS is extremely fast at calculating the nonbonded interactions (that usually dominate simulations) many groups are also using it for research on non-biological systems, e.g. polymers.

??? Links
    | Link      | Description                          |
    | :---------- | :----------------------------------- |
    | [GROMACS](http://www.gromacs.org/About_Gromacs) |Official homepage|
    | [KIGAKI3 tutorial](http://www.strodel.info/index_files/lecture/html/tutorial.html) |Tutorial with KIGAKI3 peptide model|
    | [MD tutorials](http://www.mdtutorials.com/gmx/) |Six tutorials updated to one of the latest GROMACS software versions|
    | [More Tutorials](http://www.mdtutorials.com/gmx/) |Six tutorials updated to one of the latest GROMACS software versions|
    |[Complex MD tutorial](https://mmb.irbbarcelona.org/biobb/availability/tutorials/protein-complex_md_setup)| Complex and detailed MD tutorial from BioExcel. Requires the [BioExcel biobb package](https://anaconda.org/bioconda/biobb_md)|

### NWchem
The NWChem software contains computational chemistry tools that are scalable both in their ability to efficiently treat large scientific problems, and in their use of available computing resources from high-performance parallel supercomputers to conventional workstation clusters.

NWChem can handle:
- Biomolecules, nanostructures, and solid-state
- From quantum to classical, and all combinations
- Ground and excited-states
- Gaussian basis functions or plane-waves
- Scaling from one to thousands of processors
- Properties and relativistic effects

??? Links
    | Link      | Description                          |
    | :---------- | :----------------------------------- |
    | [NWCHEM](https://nwchemgit.github.io/) |Official homepage with tutorials and installation information|
    | [Argonne NL tutorial](https://wiki.alcf.anl.gov/images/b/bc/NWChem_tutorial.pdf) |Tutorial from the Argonne national lab|

### LAMMPS :one: :snake:
LAMMPS is a classical molecular dynamics code with a focus on materials modeling. It's an acronym for Large-scale Atomic/Molecular Massively Parallel Simulator.

??? Links
    | Link      | Description                          |
    | :---------- | :----------------------------------- |
    | [NWCHEM](https://nwchemgit.github.io/) |Official homepage with tutorials and installation information|
    | [Very Basic Tutorial](https://www2.ph.ed.ac.uk/~cbrackle/lammps_tutorial.html) |Basic tutorial with one or more diffusing particles|
    | [Tutorials for beginners](https://github.com/mrkllntschpp/lammps-tutorials) |Tutorials for beginners|
    | [Supramolecular structures](https://www.osti.gov/servlets/purl/1563110) |Tutorials for modeling supramolecular structure in LAMMPS from Stan Moore, Sandia NL, USA|
    | [Material from Sandia NL](https://lammps.sandia.gov/tutorials.html) |Tutorial collection from the Sandia National Lab's workshops|

### quantumESPRESSO :one: :snake:
An integrated suite of Open-Source computer codes for electronic-structure calculations and materials modeling at the nanoscale. It is based on density-functional theory, plane waves, and pseudopotentials.

??? Links
    | Link      | Description                          |
    | :---------- | :----------------------------------- |
    | [QuantumEspresso](https://www.quantum-espresso.org/) |Homepage with installation, documentation and learning resources|
    | [QE and GPUs](http://www.max-centre.eu/webinar/how-use-quantum-espresso-new-gpu-based-hpc-systems) |How to use QuantumEspresso on GPU based HPC systems|
    | [Updated tutorials](http://www.fisica.uniud.it/~giannozz/QE-Tutorial/) |Some updated tutorials from University of Udine, IT|
    | [Step by step tutorial](https://www.paradim.org/toolbox/theory/quantum_espresso/tutorials) |A detailed tutorial (based on a specific supercomputing facility)|
    | [Small tutorial](https://usc-rc.github.io/tutorials/qe) |A small QE tutorial|

### SIESTA :one: :snake:
SIESTA is both a method and its computer program implementation, to perform efficient electronic structure calculations and ab initio molecular dynamics simulations of molecules and solids. SIESTA's efficiency stems from the use of a basis set of strictly-localized atomic orbitals. A very important feature of the code is that its accuracy and cost can be tuned in a wide range, from quick exploratory calculations to highly accurate simulations matching the quality of other approaches, such as plane-wave methods.

??? Links
    | Link      | Description                          |
    | :---------- | :----------------------------------- |
    | [large tutorial collection](https://siesta.icmab.es/SIESTA_MATERIAL/Docs/Tutorials/index.html) |A large collection of tutorials for Siesta|
    | [Tel Aviv Siesta tutorial](https://departments.icmab.es/leem/SIESTA_MATERIAL/Docs/Tutorials/tlv14/index.html) |Siesta Workshop material|
    | [SIMUNE material](https://www.simuneatomistics.com/services-products/siesta-tutorials/) |A range of tutorials to guide the learning process in using Siesta. Developed by Simune Atomistics|
    | [Tutorial Repository](https://github.com/siesta-project/tutorials) |A big repository with exercises for Siesta|

## Development
### Dash :one: :snake:
Dash is a productive Python framework for building web analytic applications. Dash is ideal for building data visualization apps with highly custom user interfaces in pure Python. It's particularly suited for anyone who works with data in Python.

Through a couple of simple patterns, Dash abstracts away all of the technologies and protocols that are required to build an interactive web-based application. Dash is simple enough that you can bind a user interface around your Python code in an afternoon.

Dash apps are rendered in the web browser. You can deploy your apps to servers and then share them through URLs. Since Dash apps are viewed in the web browser, Dash is inherently cross-platform and mobile ready.

??? Links
    | Link      | Description                          |
    | :---------- | :----------------------------------- |
    | [Dash homepage](https://dash.plotly.com/) |The Dash homepage. It contains tutorial for a quick |
    | [Video introduction](https://www.youtube.com/watch?v=hSPmj7mK6ng) |A video introduction to Dash|
    | [Step by step tutorial](https://realpython.com/python-dash/) |A step by step tutorial to produce a Dash web application|

### Jupyter Lab :one: :snake:
JupyterLab is a web-based interactive development environment for Jupyter notebooks, code, and data. JupyterLab is flexible: configure and arrange the user interface to support a wide range of workflows in data science, scientific computing, and machine learning.

| Link      | Description                          |
    | :---------- | :----------------------------------- |
    | [Homepage](https://www.jupyter.org) |The Homepage of project jupyter|

### Matlab :one:
MATLAB® combines a desktop environment tuned for iterative analysis and design processes with a programming language that expresses matrix and array mathematics directly. It includes the Live Editor for creating scripts that combine code, output, and formatted text in an executable notebook.

| Link      | Description                          |
    | :---------- | :----------------------------------- |
    | [Homepage](https://www.mathworks.com/products/matlab.html) |The Homepage of Mathworks Matlab|

### Rstudio :one: :two:
An integrated development environment for R and Python, with a console, syntax-highlighting editor that supports direct code execution, and tools for plotting, history, debugging and workspace management.

| Link      | Description                          |
    | :---------- | :----------------------------------- |
    | [Homepage](https://rstudio.com/) |The Homepage of Rstudio|

### Visual Studio code :one:
Visual Studio Code is a lightweight but powerful source code editor. It comes with built-in support for JavaScript, TypeScript and Node.js and has a rich ecosystem of extensions for other languages (such as C++, C#, Java, Python, PHP, Go) and runtimes (such as .NET and Unity). Manages your Git repository and has a lot of plugins freely installable from the dedicated store.

| Link      | Description                          |
    | :---------- | :----------------------------------- |
    | [Homepage](https://code.visualstudio.com/) |The Homepage of Visual Studio Code|

### Spark :one:
Apache Spark is a lightning-fast unified analytics engine for big data and machine learning. It was originally developed at UC Berkeley in 2009.

## Natural sciences and engineering
### COMSOL :one:
COMSOL Multiphysics is a cross-platform finite element analysis, solver and multiphysics simulation software. It allows conventional physics-based user interfaces and coupled systems of partial differential equations (PDEs). COMSOL provides an IDE and unified workflow for electrical, mechanical, fluid, acoustics, and chemical applications.

| Link      | Description                          |
    | :---------- | :----------------------------------- |
    | [COMSOL models](https://www.comsol.eu/models) |A gallery of applications from the COMSOL homepage|

### FEniCS :one: :snake:
FEniCS is a popular open-source (LGPLv3) computing platform for solving partial differential equations (PDEs). FEniCS enables users to quickly translate scientific models into efficient finite element code. With the high-level Python and C++ interfaces to FEniCS, it is easy to get started, but FEniCS offers also powerful capabilities for more experienced programmers. FEniCS runs on a multitude of platforms ranging from laptops to high-performance clusters.

| Link      | Description                          |
    | :---------- | :----------------------------------- |
    | [Homepage](https://fenicsproject.org/) |Homepage of the FEniCS project|
    | [Tutorials and book](https://fenicsproject.org/tutorial/) |Free official tutorials and book|

### FreeCAD :one: :snake:
FreeCAD is a parametric 3D modeler made primarily to design real-life objects of any size.

| Link      | Description                          |
    | :---------- | :----------------------------------- |
    | [Beginners tutorial](https://www.youtube.com/watch?v=sxnij3CkkdU) |Beginners video tutorial|
    | [Free documentation](https://wiki.freecadweb.org/Tutorials) |Freecad wiki|

## Probabilistic programming
### pyMC3 :snake:
PyMC3 allows you to write down models using an intuitive syntax to describe a data generating process.

Cutting edge algorithms and model building blocks
Fit your model using gradient-based MCMC algorithms like NUTS, using ADVI for fast approximate inference — including minibatch-ADVI for scaling to large datasets — or using Gaussian processes to build Bayesian nonparametric models.

| Link      | Description                          |
    | :---------- | :----------------------------------- |
    | [Documentation](https://docs.pymc.io/) |Documentation page with tutorials, videos, examples and books|
    | [While my MCMC gently samples](https://twiecki.io/) |A blog about pyMC3 and Bayesian inference|
    | [Bayesian modeling cookbook blog](https://eigenfoo.xyz/bayesian-modelling-cookbook/) |A blog on bayesian modeling|
    | [Probabilistic Programming blog](https://colindcarroll.com/) |A blog on probabilistic programming from a pyMC3 contributor|

## Social Sciences, Humanities
### NetLogo :one:
NetLogo is a multi-agent programmable modeling environment. It is used by many hundreds of thousands of students, teachers, and researchers worldwide. It also powers HubNet participatory simulations. It is authored by Uri Wilensky and developed at the CCL.

| Link      | Description                          |
    | :---------- | :----------------------------------- |
    | [Homepage](https://ccl.northwestern.edu/netlogo/) |Netlogo homepage with tutorials, extensions, resources.|

### oTree :one:
An open-source platform for behavioral research

oTree lets you create:
- Controlled behavioral experiments in economics, market research, psychology, and related fields
- Multiplayer strategy games, like the prisoner's dilemma, public goods game, and auctions.
- Surveys and quizzes, especially those that require customized or dynamic functionality not available with conventional survey software.

| Link      | Description                          |
    | :---------- | :----------------------------------- |
    | [Homepage](https://www.otree.org/) |oTree homepage with tutorials, extensions, resources.|



