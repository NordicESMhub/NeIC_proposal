**Proposal template**

- A4 with 11 point font size (Times New Roman, Arial or Calibri font types), 
- 2 cm margins and single spacing. Maximum 10 pages:

# NeIC ESM application

## Significance

- Open data requirements for Nordic research
- FAIR climate data (Nordic) as a facilitator of research collaboration

**Benefits**

- More Earth System Modeling simulations done in less time
- Homogeneous workflows to post-process ESM model outputs for evaluating the impact of climate change in the Nordics (independently of the Earth System Model used i.e. NorESM, EC-EARTH or GISS modelE)
- Common diagnostic tools/workflows for highlighting Climate impact in the Nordics
- Reduce cost (performance and energy efficiency) of ESM simulations
- Possibility to have a joint Nordic CMIP participation
- Benefit for all ESM researchers in the Nordic, even those not involved in the project and/or CMIP
- Climate data would be easier to use, even for non-specialists


## Research community

## National and international context

Large international projects (e.g. [CMIP](https://www.wcrp-climate.org/wgcm-cmip), [CORDEX](https://www.cordex.org/), [AeroCom](https://aerocom.met.no/Welcome.html), [PEEX](http://www.atm.helsinki.fi/FCoE/)) have resources to develop/exploit data management infrastructures (e.g. [ESGF](https://esgf.llnl.gov/)) whereas smaller national/Nordic projects rely more on generic 3rd party infrastructures for data management (not always well suited to the task). 
Is there scope for a collaboration project to support/develop/help Nordic research projects utilize available data infrastructures and services? Collaboration on data management and FAIR data for climate research.


## The Nordics and NeIC

## Services and tools

### Activities

- **Activity A**: Model analysis and diagnostics focused on the Nordic regions
- **Activity B**: FAIR climate data for norESM, EC-EARTH and GISS modelE
- **Activity C**: ESM workflows for efficiently running NorESM, EC-EARTH and GISS modelE on euroHPC


#### Activity A:


Remove comittment on the development of new ESMValTool diagnostic modules but put more emphasis on the usage of ESMValTool with a focus on the Nordic countries.

- Enable the development of new diagnostic modules in ESMValTool (MetNo lead)
- Tutorial or sharing expertise on these particular aspects

- Design 3 ESMValTool diagnostic modules of interest to the Nordic countries
- Development of diagnostic modules of interest to the Nordic countries
- Deployment of the diagnostic modules
- Development and publications of diagnostic workflows (for instance in the Galaxy Toolshed) to demonstrate the usability of the 3 newly developed ESMValTools for EC-EARTH, NorESM and GISS modelE 
- Development of educational material for using the 3 new ESMValTool and associated workflows

**Milestones and deliveries**

- 3 ESMValTool diagnostic modules of interest to Nordic countries (eg, polar lows, European and Greenland blocking events) with strong emphasis on (high-latitude) observations (and "observation simulators" to some extent) 
- A Common platform for common EC-EARTH, NorESM and GISS modelE analysis comparisons for Nordics to facilitate scientific collaboration
- 3 published diagnostic workflows applicable to norESM, EC-EARTH and GISS modelE
- 1 online tutorial for learning and running the new ESMValTool workflows
- 1 workshop/hackathon on how to use ESMValTool and how applicable it can be to the Nordic countries

#### Activity B: FAIR Climate data for Nordics

- ESGF related activities (to be described)
	- Involvement of ESGF admin to enable FAIR climate data
	- Strenghen existing ESGF networking activities in the Nordics (Norway, Sweden, Denmark and Finland)
	
- How can we apply current practices for simulation outside CMIP?
	- Data stewarship workshop (GO-FAIR) 
	- EOSC-Nordic & NICEST 

- Is it possible to use existing tools ESDOC, ESGF to make our data FAIR?

- Analysis on the state of the art of FAIR data in Climate and existing tool to assess
		- ESDOC analysis, can we use ESDOC for Nordic other climate simulations, does it need to be expanded? 
		- Make sure current initiatives are taken into account
		- How applicable is it outside CMIP?
- FAIR Climate data in practice
	- Implementation of the recommendations, at least in "Demo" mode to demonstrate and validate the chosen approach
	- Training

**Milestones and deliveries**

- 1  face to face training for ESGF publication and regular virtual meeting for ESGF admin
- 1  face to face training for learning how to publish on ESGF node 
- 1 hackathon with FAIR specialists and ESM specialists to understand what needs to be done for making Climate data FAIR (for norESM, EC-EARTH and GISS modelE)
- 1 deliverable on recommendation for FAIR data in Climate (based on ESDOC analysis and hackathon).
- 1 training material on how to generate FAIR climate data (and metadata) FAIR
- 1 Train the Trainer workshop on FAIR climate data using the training material developed within the project (e.g. https://indico.neic.no/event/56/).
- 1 Data Management Plan Template for Nordic Climate Data


#### Activity C: ESM workflows for efficiently running both NorESM, EC-EARTH and GISS modelE on EuroHPC

- Define requirements for efficient and useful ESM workflows
- Analysis of existing workflow tools (cylc, galaxy, snakemake, etc.) and how they fit to our requirements
- Analysis of best practices for performance optimisation and productivity of ESMs
- Development of containers for running norESM, EC-EARTH and GISS modelE
- Performance analysis of ESM containers versus ESM "native compilations"
- Analysis of EuroHPC requirements and how it can benefit our community
	
**Milestones and deliveries**

- 1 training material on workflow tools for ESM (cylc, galaxy or snakemake)
- 1 training material on performance analysis for NorESM, EC-EARTH and GISS modelE
- Best practices guides:
	- on how to run ESM 
	- on how to evaluate ESM when porting on new machine, especially for EuroHPC
- How much development would require our models (EC-EARTH, norESM) for running on the next EuroHPC
	- Analysis on what needs to be done and identify bottlenecks for all involved models
		- I/O efficiency
		- lack of GPU support
	- Understanding on what we can do and involvement with Nordic EuroHPC
(- Containerization (singularity/docker) for running NorESM, EC-EARTH and GISS modelE) <-- To clarify

**CLARIFY SUB-ACTIVITY ABOUT BENCHMARK**

- Common framework for benchmark for EuroHPC with norESM, and EC-EARTH and GISS modelE, 
	- Investigate whether using a common workflow manager (cylc, galaxy or snakemake) is helpful
	- Get in touch with Nordic EuroHPC representatives for Benchmark
- 1 face to face meeting with Nordic EuroHPC representatives to coordinate feedback on requirement for efficient use of resources specifically for the climate community
- 1 public report on the best approach for using efficiently EuroHPC for the Nordic Climate Community with guidance on performance versus energy efficiency

## Resources and viability of the anticipated e-infrastructure services


## Partners of the collaboration

Action Point: All


## Additional information
