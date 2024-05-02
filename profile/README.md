# Welcome!

This Github organization holds the source code, documentation, walkthroughs, and issues for intelligent computational image analysis on superresolution microscopy.

This is a collaboration between the research labs of [Professor Ivan Robert Nabi](https://cps.med.ubc.ca/faculty1/nabi/) (Life Sciences Insttitute, University of British Columbia) and Professor Ghassan Hamarneh ([Medical Image Analysis Research Group](https://www.medicalimageanalysis.com/home), Simon Fraser University) 

## Table of Contents
- [Team](#team)
- [Resources](#resources)
    - Imaging
    - [Computational](#comp)
- [News](#news)
- [Software](#software)
- [Publications](#publications)
- [Documentation/walkthroughs/tutorials](#docs)
- [Contact](#contact)

<a name="team"></a>
## Team

<a name="resources"></a>
## Resources

### Imaging
Our team has access to state of the art superresolution microscopes, includng but not limited to STED, dSTORM, and many more. [todo expand]

<a name="comp"></a>
### Computational
Our team is yearly awarded cluster compute resources from the [Digital Research Alliance](https://alliancecan.ca/en/services/advanced-research-computing), has priority access to Simon Fraser University's Solar Cluster, as well as the research computing cluster at the University of British Columbia, in addition to specialized workstations for low latency prototyping.

<a name="news"></a>
## News
Coming soon

<a name="software"></a>
## Software

|  Name	        | Modality <br> datatype  	        | Language  	| Task                          | License  	        | Publication   	| Manual<br>& docs | Tests |  Contact
|---	        |---	                |---	        |---                            |---	            |---	            |---            |---    |---
| [SuperResNet](https://www.medicalimageanalysis.com/software/superresnet)   | Pointcloud<br>dStorm     | Matlab        | CL,SE,DE                      | Proprietary       | [![DOI](https://github.com/NanoscopyAI/.github/raw/main/profile/doi.gif)](http://dx.doi.org/10.1038/s41598-018-27216-4)               |    [![Github](https://github.com/NanoscopyAI/.github/blob/main/profile/docs.svg)](https://www.medicalimageanalysis.com/software/superresnet/documentation)     | TODO  |  [@](ikhater@sfu.ca)
| [SuperResNet Batch](https://github.com/NanoscopyAI/SuperResNET-Batch)   | Pointcloud<br>dStorm     | Matlab, Bash        | CL,SE,DE   | Proprietary       | TODO|    TODO     | TODO  |  [@](cdh13@sfu.ca)
| [ERGO](https://github.com/NanoscopyAI/ERGO)          | Pointcloud<br>dStorm     | Python<br>Julia  | DE,LO,<br>WSOD-L                  | GPLv3             | [![DOI](https://github.com/NanoscopyAI/.github/raw/main/profile/doi.gif)](http://dx.doi.org/10.1109/TMI.2019.2962361)   | [![Github](https://github.com/NanoscopyAI/.github/blob/main/profile/docs.svg)](https://github.com/NanoscopyAI/ERGO)     | [![CircleCI](https://dl.circleci.com/status-badge/img/gh/bencardoen/ERGO.jl/tree/main.svg?style=shield)](https://dl.circleci.com/status-badge/redirect/gh/bencardoen/ERGO.jl/tree/main)       |  [@](bcardoen@sfu.ca)
| [Smlmvis](https://github.com/NanoscopyAI/smlmvis)          | Pointcloud<br>dStorm     | Python  | VI,DF                  | AGPLv3             | [![DOI](https://github.com/NanoscopyAI/.github/raw/main/profile/doi.gif)](https://doi.org/10.5281/zenodo.7226577)              | [![Github](https://github.com/NanoscopyAI/.github/blob/main/profile/docs.svg)](https://github.com/NanoscopyAI/smlmvis)         | TODO   |  [@](bcardoen@sfu.ca)
| [SPECHT](https://github.com/NanoscopyAI/SPECHT.jl)          | 2D STED<br>voxel     | Julia  | WSOD-L<br>AD, CI, DE                  | AGPLv3             | [![DOI](https://github.com/NanoscopyAI/.github/raw/main/profile/doi.gif)](http://dx.doi.org/10.1371/journal.pone.0276726)<br> [![DOI](https://github.com/NanoscopyAI/.github/raw/main/profile/doi.gif)](https://link.springer.com/article/10.1007/s00018-022-04585-8)               | [![Github](https://github.com/NanoscopyAI/.github/blob/main/profile/docs.svg)](https://github.com/NanoscopyAI/SPECHT.jl)    | [![CircleCI](https://dl.circleci.com/status-badge/img/gh/bencardoen/SPECHT.jl/tree/main.svg?style=shield)](https://dl.circleci.com/status-badge/redirect/gh/bencardoen/SPECHT.jl/tree/main)         |  [@](bcardoen@sfu.ca)
| [DataCurator](https://github.com/NanoscopyAI/DataCurator.jl)          | 2/3D voxel<br>pointcloud<br>HDF5, CSV     | Julia  | AC, DF, ST                  | AGPLv3             | [![DOI](https://github.com/NanoscopyAI/.github/raw/main/profile/doi.gif)](https://www.techrxiv.org/articles/preprint/DataCurator_jl_Efficient_portable_and_reproducible_validation_curation_and_transformation_of_large_heterogeneous_datasets_using_human-readable_recipes_compiled_into_machine_verifiable_templates/22060118)               | [![Github](https://github.com/NanoscopyAI/.github/blob/main/profile/docs.svg)](https://github.com/NanoscopyAI/DataCurator.jl)    | [![CircleCI](https://dl.circleci.com/status-badge/img/gh/bencardoen/DataCurator.jl/tree/main.svg?style=shield)](https://dl.circleci.com/status-badge/redirect/gh/bencardoen/DataCurator.jl/tree/main)         |  [@](bcardoen@sfu.ca)
| [LogParadox](https://github.com/NanoscopyAI/LogParadox.jl)          | CSV     | Julia  | ST                  | AGPLv3             | [![DOI](https://github.com/NanoscopyAI/.github/raw/main/profile/doi.gif)](https://arxiv.org/abs/2302.04780)               | [![Github](https://github.com/NanoscopyAI/.github/blob/main/profile/docs.svg)](https://github.com/NanoscopyAI/LogParadox.jl)    | [![CircleCI](https://dl.circleci.com/status-badge/img/gh/bencardoen/LogParadox.jl/tree/main.svg?style=shield)](https://dl.circleci.com/status-badge/redirect/gh/bencardoen/LogParadox.jl/tree/main)        |  [@](bcardoen@sfu.ca)
| [SmlmTools](https://github.com/NanoscopyAI/SmlmTools.jl)          | dSTORM     | Julia  | RT, LO                  | AGPLv3             | [![DOI](https://github.com/NanoscopyAI/.github/raw/main/profile/doi.gif)](https://doi.org/10.5281/zenodo.7632321)               | [![Github](https://github.com/NanoscopyAI/.github/blob/main/profile/docs.svg)](https://github.com/NanoscopyAI/SmlmTools.jl)    | [![CircleCI](https://dl.circleci.com/status-badge/img/gh/bencardoen/SmlmTools.jl/tree/master.svg?style=shield)](https://dl.circleci.com/status-badge/redirect/gh/bencardoen/SmlmTools.jl/tree/master)        |  [@](bcardoen@sfu.ca)
| [MCS-Detect](https://github.com/NanoscopyAI/SubPrecisionContactDetection.jl)          | 3D STED     | Julia  | LO, DE, IC                   | AGPLv3             | [![DOI](https://github.com/NanoscopyAI/.github/raw/main/profile/doi.gif)](https://doi.org/10.1083/jcb.202206109)               | [![Github](https://github.com/NanoscopyAI/.github/blob/main/profile/docs.svg)](https://github.com/NanoscopyAI/SubPrecisionContactDetection.jl)    | [![CircleCI](https://dl.circleci.com/status-badge/img/gh/bencardoen/SubPrecisionContactDetection.jl/tree/main.svg?style=shield)](https://dl.circleci.com/status-badge/redirect/gh/bencardoen/SubPrecisionContactDetection.jl/tree/main)        |  [@](bcardoen@sfu.ca)
| [Colocalization](https://github.com/NanoscopyAI/Colocalization.jl)          | 2-3D Voxel     | Julia  | IC                   | AGPLv3             | [![DOI](https://github.com/NanoscopyAI/.github/raw/main/profile/doi.gif)](https://zenodo.org/record/7552357)               | [![Github](https://github.com/NanoscopyAI/.github/blob/main/profile/docs.svg)](https://github.com/NanoscopyAI/Colocalization.jl)    | [![CircleCI](https://dl.circleci.com/status-badge/img/gh/bencardoen/Colocalization.jl/tree/main.svg?style=shield)](https://dl.circleci.com/status-badge/redirect/gh/bencardoen/Colocalization.jl/tree/main)        |  [@](bcardoen@sfu.ca)
| [ER-Analysis-scripts](https://github.com/NanoscopyAI/ER-Analysis-scripts)          | 2D Confocal     | Python<br>Matlab  | IP, GP                  | todo | todo | todo | todo |  [@](asa420@sfu.ca)
| [nERdy](https://github.com/NanoscopyAI/nERdy)          | 2D Confocal     | Python<br>Matlab  | IP, GP, DL                  | AGPLv3 | todo | todo | todo |  [@](asa420@sfu.ca)

Acronym legend of functionality/features:
**Clustering (CL), Segmentation (SE), Weakly supervised object detection/localization (WSOD-L), Contrastive identification (CI), Classification (CA), Denoising (DE), Adaptive (AD), Localization (LO), Interaction/Colocalization (IC), Acceleration (AC), Visualization (VI), Data formats (DF), Statistics (ST), Registration/Tracking (RT), Image Processing (IP), Graph Processing (GP), Deep Learning (DL)**

<a name="publications"></a>
## Selected Publications
See our [bibliography](https://raw.githubusercontent.com/NanoscopyAI/.github/main/bibliography.bib) for a complete listing of publications.


<a name="contact"></a>
### Contact
For public contact, please create an [issue](https://github.com/NanoscopyAI/.github/issues/new/choose). The individual projects have contact info listed above. Each publication also has corresponding authors.
If you need private contact means, please create an issue and we will follow up with a private channel.
