**Proposal template**

- A4 with 11 point font size (Times New Roman, Arial or Calibri font types), 
- 2 cm margins and single spacing. Maximum 10 pages:

# NeIC ESM application

## Significance

**Benefits**

- More Earth System Modeling simulations done in less time
- Homogeneous workflows to post-process ESM model outputs for evaluating the impact of climate change in the Nordics (independently of the Earth System Model used i.e. NorESM, EC-EARTH or GISS modelIE)
- Common diagnostic tools/workflows for highlighting Climate impact in the Nordics
- Reduce cost (performance and energy efficiency) of ESM simulations
- Possibility to have a joint Nordic CMIP participation
- Benefit for all ESM researchers in the Nordic, even those not involved in the project and/or CMIP
- Climate data would be easier to use, even for non-specialists


## Research community

The Nordic climate modeling community consists of research groups at Universities, national meteorological institutes and research institutes, and holds demonstrable world-class excellence in the field. Through international collaborations, mainly with partners within Europe and US, these Nordic groups contribute to the development of both global and regional climate models (GCMs and RCMs) and have used these highly complex and computationally demanding research tools to help understand a wide range of natural and forced phenomena within the Earth system. This research is by its very nature multi-disciplinary and multi-scale.

## National and international context

### Earth system modeling and CMIP
Changes in climate, whether anthropogenic or natural, involve a complex interplay of physical, chemical, and biological processes of the atmosphere, land surface, cryosphere and ocean. Earth System Models (ESMs) are used to address e.g. anthropogenic versus natural climate change, climate variations with time scales ranging from years to millennia. ​
An important way to get ESMs internationally recognized is the World Climate Research Program ([WCRP](https://www.wcrp-climate.org/)) sponsored Climate Model Intercomparison Projects ([CMIP](https://www.wcrp-climate.org/wgcm-cmip)) which is a unique international initiative that highlights the importance of sharing, comparing and analyzing the outcomes of global climate model simulations and to deliver high quality climate information. CMIP results have been used in a very large number of scientific studies that make them a cornerstone of IPCC assessment reports. Danish, Finnish, Norwegian and Swedish modeling groups have committed to participate in phase 6 of CMIP (CMIP6).
The regional counterpart to CMIP is the Coordinated Regional Downscaling Experiment ([CORDEX](https://www.cordex.org/)) endorsed by the WCRP that has produced a large ensemble of RCM integrations at high horizontal resolution for all continents. The CORDEX results are now being used worldwide for climate impact studies and climate change adaptation work.

### The ESMValTool
The Earth System Model eValuation Tool ([ESMValTool](https://www.esmvaltool.org/index.html)) is a community diagnostics and performance metrics tool for the evaluation of ESMs that allows for routine comparison of single or multiple models, either against predecessor versions or against observations. The ESMValTool is a community effort open to both users and developers encouraging open exchange of diagnostic source code and evaluation results from the CMIP ensemble.

### The Earth System Grid Federation
Climate models produce very large amounts of output data that needs to be post-processed and quality-checked before it can be distributed to climate researchers, those working with climate impacts and other users working with climate adaptation measures. This data handling poses a major challenge to the climate modeling community as data providers. To meet the increasing needs from the climate modeling community to archive and distribute climate data the Earth System Grid Federation ([ESGF](https://esgf.llnl.gov/)) was launched in the US in the late 1990s. CMIP and CORDEX now use the ESGF for distribution of climate data. Recently Danish, Norwegian, Finnish and Swedish ESGF nodes have been set up that now hold considerable amounts of data. Through its first phases, the ESGF grew into a Petabyte facility and it is foreseen that this will continue to increase further with the next phases of CMIP and CORDEX. It is clear that the ESGF system is the main infrastructure for archiving and distributing climate data for the foreseeable future and future developments are expected to support this system.


## The Nordics and NeIC

## Services and tools

### Activities

- **Activity A**: Model analysis and diagnostics focused on the Nordic regions
- **Activity B**: FAIR climate data for norESM, EC-EARTH and GISS modelIE
- **Activity C**: ESM workflows for efficiently running NorESM, EC-EARTH and GISS modelIE on EuroHPC


#### Activity A: Model analysis and diagnostics focused on the Nordic regions

*Partners*: **MetNo**, FMI, ???

The main objective of this activity is to develop expertise on ESMValTool within the Nordic countries and enable the development of new diagnostic modules. 

**Milestones and deliveries**

- **A-1**: 1 workshop/hackathon to discuss about how to use ESMValTool with a focus on the Nordic countries and collect user requirements for the two training materials.
- **A-2**: 1 online tutorial on how to best use ESMValTool diagnostic tools for the Nordic countries (eg, polar lows, European and Greenland blocking events) with strong emphasis on (high-latitude) observations (and "observation simulators" to some extent) 
- **A-3**: 1 online tutorial on how to develop new diagnostic modules in ESMValTool that are common to EC-EARTH, NorESM and GISS modelIE. The main objective is to facilitate analysis comparisons for Nordics for scientific collaborations.

#### Activity B: FAIR Climate data for Nordics

*Partners*: **NSC**, DMI, CSC, ????

The main objective of this activity is to define a clear roadmap to FAIR climate modeling data in the Nordics. This activity will be strongly linked to EOSC-Nordic, in particular WP4 "FAIR data" and WP5 "Open Research demonstrators". 

Two main tasks have been identified:

**Task B-1: Support for Nordic ESGF hosting of CMIP6 data**

*Lead*: ???

Danish, Finnish, Norwegian and Swedish HPC providers currently host ESGF nodes. Although there have been considerable improvements in the ESGF software, the deployment and reliable maintenance of an ESGF node requires experience and a deep technical understanding of the hardware and ESGF software. In addition, knowledge of climate model output formats, project data reference syntax and controlled vocabularies (e.g.CMIP6) is also required. This sub-activity will continue to strengthen the collaborative efforts, knowledge sharing and skills development initiated in the NICEST project regarding the deployment and administration of ESGF nodes. 

Regular (monthly) virtual meetings for the Nordic ESGF operations team will be organized and minutes will be publicly available. 


**Task B-2: FAIR climate modeling data for Nordics**

*Lead*: ???

Beyond CMIP6 and CORDEX, there are Nordic and national projects that generate valuable climate data. The management of these outputs should follow FAIR and open principles. The aim of this sub-activity is to investigate whether the tools (including ES-DOC, CF, CMOR, ESGF) and techniques for managing CMIP6 data can be reused in Nordic and national projects to ensure the valuable outputs from such projects are FAIR and open. This will be achieved by bringing together data generators (ESM modelers), data managers (ESGF) and FAIR data specialists. 

**Milestones and deliveries**

- **B-1.1**: Online minutes from all Nordic ESGF operation meetings (one per month for all the duration of the project i.e. 36) 
- **B-1.2**: 1  face to face training for Nordic ESGF operations team on the ESGF CMIP6 publication process.  
- **B-2.1**: 1 hackathon with FAIR experts and ESM specialists to understand what needs to be done for making Climate data FAIR (for norESM, EC-EARTH and GISS modelE). 
- **B-2.2**: Report on knowledge/skills gap analysis and suggested roadmap to FAIR Nordic climate modeling data
- **B-2.3**: 1 Data Management Plan Template to support FAIR Nordic Climate Data
- **B-2.4**: 1 training material on how to generate FAIR climate data (and metadata)
- **B-2.5**: 1 Data stewardship workshop for FAIR climate data


#### Activity C: ESM workflows for efficiently running both NorESM, EC-EARTH and GISS modelE on EuroHPC

*Partners*: **UiO**, ?????

The main objective of this activity is to develop expertise on how to run efficiently ESM workflows and facilitate the porting and deployment of Nordic ESMs on future HPCs, in particular the EuroHPC. Two main tasks have been identified:

**Task C-1**: Reproducible workflows for deploying and running ESM on future HPCs

*Lead*: **UiO**

As part of this task an analysis of existing workflow Management systems (cylc, galaxy, snakemake, etc.) will be done and will be the basis for the definition of Nordic ESM workflow Management Systems. Mock-ups for NorESM, EC-EARTH and GISS modelIE workflows will be made available by mid-term and will facilitate benchmarking of Nordic ESMs on new HPCs and ease the deployment of Nordic ESMs on EuroHPCs. To improve reproducibility, package management system and environment management system such as conda will be tested with NorESM, EC-EARTH and GISS modelIE and containers for running these models will be deployed. The performance achieved by the containerized models will be published and made publicly available.

Within High Energy Physics (e.g., CERN LHC), many solutions and services do already exist to tackle complex tasks like workflow management execution with data and compute. Those solutions are being used now by more and more scientific communities. One potential idea can be to identify some use cases and evaluate the services available like job management, data catalog and orchestration. A demonstrator will be set up as part of the project with at least one of the Nordic ESMs. 


**Task C-2**: Efficiency of Nordic ESMs on future euroHPC

*Lead*: ???

Having a common framework for analyzing the performance of Nordic ESMs can considerably reduce the cost (computing and energy efficiency) for running climate models and give us a competitive advantage for running on the future EuroHPC. 

This task will focus on best practices for performance and productivity of Nordic ESMs and on understanding what we need to do to be able to run on EuroHPC.

	
**Milestones and deliveries**

- **C-1.1**: 1 deliverable/report on Analysis of the Nordic ESM community needs for ESM workflow tools (cylc, galaxy, snakemake, etc.).
- **C-1.2**: 1 deliverable on the identification and classification of services to be deployed for the Nordic ESM community for orchestrating efficiently of ESM workflows
- **C-1.3**: 1 demonstrator build with a simple use case for distributing computations and managing data on at least 3 different sites (within the Nordic countries). The associated deliverable will be publicly available.
- **C-1.4**: 1 online training material for creating ESM workflows (cylc, galaxy or snakemake)
- **C-1.5**: 1 online tutorial on best practices for package management system and environment management system for Nordic ESMs.
- **C-1.6**: Publication of conda recipes and containers (docker, singularity) for norESM, EC-EARTH and GISS modelIE (github, conda-forge)
- **C-2.1**: 1 workshop (face to face meeting) with national HPC providers to discuss and characterize the nordic ESM involvement in EuroHPC
- **C-2.2**: Reports on bottlenecks that would hindrance the efficient usage of Nordic ESMs on EuroHPC and possible remediation actions (I/Os, adding GPU support, etc.) with a clear information on costs (PMs, etc.).
- **C-2.3**: Best practice guides (for research and production) on how to evaluate performance of Nordic ESMs
- **C-2.4**: Report on performance analysis of each Nordic ESM and comparisons with their containerized versions (docker and/or singularity).


## Resources and viability of the anticipated e-infrastructure services


## Partners of the collaboration

Action Point: All


## Additional information
