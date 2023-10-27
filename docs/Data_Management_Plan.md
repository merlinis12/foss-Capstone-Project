# Data Management Plan

This document takes into consideration data that I use for my research.

### Project Title:
Identification of precision therapeutics for Alzheimer's disease prevention and treatment

### Principal Investigator:
PhD Francesca Vitali

### Data Manager:
PhD Francesca Vitali

### Collaborators:
Simona Merlini

### Project Rationale:
Alzheimer's disease (AD) is a progressive neurodegenerative disease that affects 5.8 million people in US with no effective therapeutic. Therapeutics to prevent, delay and treat AD are urgently needed.  The management and treatment of AD risk factors, such as diabetes and hypertension, might delay or prevent AD onset. To this point, an untreated risk factor generates a cascade that with time increases in complexity and ultimately results in AD. Our aim is to select risk factor profiles that are targetable with a drug class and assess if a therapeutic or a combination of therapeutics can disrupt the risk cascade modifying AD onset. We aim to include in our analyses demographic data (age, sex, ethnicity, genotype, disease stage, socioeconomic status) to stratify efficacy of each therapeutic for AD prevention in a given population.





## 1. Data Description

We use data from the [UK Biobank](https://www.ukbiobank.ac.uk) as reference in many studies to characterize the impact of therapeutics targeting Alzheimer's disease (AD) risk factors has on AD and cognitive impairment. UK Biobank is a large-scale biomedical database and research resource, containing in-depth genetic and health information from half a million UK participants. The database is regularly augmented with additional data and is globally accessible to approved researchers undertaking vital research into the most common and life-threatening diseases. 


## 2. Data Collection

UK Biobank is a world-leading biomedical database to enable scientific discoveries that improve human health. Our goal is to inspire the imaginations of health researchers around the world to meet the challenge of greater understanding, prevention, and treatment of a range of serious illnesses. UK Biobank has Research Tissue Bank Approval till 2026 and through access to an unmatched amount of biological and medical data on half a million people living in the UK, we can enable your vision of improving human health. 
1. UK Biobank is a longitudinal study; it follows the health of 500,000 volunteer participants. 
1. Participants were aged between 40-69 years when they joined UK Biobank between 2006-2010. 
1. Each participant attended a baseline assessment at a centre in England (89%), Scotland (7%) and Wales (4%).
1. Participants provided their consent for long-term follow-up. 
1. Participants answered lots of questions about their health & lifestyle.
1. Participants donated samples of blood, urine and saliva for long-term storage and analysis. 
1. Physical measurements were also taken (e.g. height, weight, spirometry, blood pressure, heel bone density). 
1. Many participants have undertaken MR brain & heart imaging, activity monitoring and online follow-up questionnaires. 
1. We have genetic data on all 500,000 participants. 
1. UK Biobank is not representative of the general population with evidence of a ‘healthy volunteer’ selection bias, details of which are published online.

UK Biobank is linked to the health-related records of the participants (through cancer and death registries and through hospital episode and primary care data) and in time to a range of other health-related records (further details are available on UK Biobank’s website).

## 3. Data Extraction
Principally through UK Biobank's website and periodic updates, as well as through the usual public channels such as published articles. Specifically in relation to the UK Biobank website, the website will highlight changes and developments, such as the release of new data types, the establishment of data linkage and the status of enhancement proposals. It is also planned to update researchers by email with news about the development of items of interest to them. Further, UK Biobank will advertise the existence and content of returned datasets via the [Data Showcase](https://biobank.ndph.ox.ac.uk/showcase/) and in due course using email alerts.

For the UK Biobank dataset, [Research Analysis Platform](https://www.ukbiobank.ac.uk/enable-your-research/research-analysis-platform) will be used to access the data in the cloud.

## 4. Data Generation
In the course of a research project the following broad categories of data may be
generated (either by UK Biobank or by the researcher) from the UK Biobank samples
or the UK Biobank data:
- Assay Data: these are data generated from analyses of the samples. These
assays may be conducted by or on behalf of UK Biobank or by the researcher
themselves. Assay Data includes by way of example biochemical analyses
(lipids such as HDL or LDL cholesterol) and genetic sequence data;
- Analysis Data: these are data generated from analyses of other UK Biobank
materials or UK Biobank data. As above, these assays may be conducted by
or on behalf of UK Biobank or by the researchers themselves. Analysis Data
include by way of example, data generated from the analysis of eye (and
other) images, spirometry, EGCs, activity monitoring, diet questionnaires
and similar;
- Derived Data Variables: these are data generated from analyses or
functional combinations of the UK Biobank data or Assay data. An example
of a Derived Data Variable includes Body Mass Index (BMI), being a function
of height and weight;
- Researcher Analyses: these are methodologies, applications and
mathematical devices used by researchers, such as power calculations,
algorithms and statistical correlations, used by the researcher;
- Researcher Results (which includes Research Results Data): these are
respectively the qualitative conclusions of the Researcher and the
quantitative analyses which underpin those conclusions. These data will go
back into the resource and will be carefully evaluated (for example ECG
data) and its provenance highlighted



## 4. Data Storage and Backup
Tree ring data and associated metadata will be stored in a dedicated directory on our secure research server. Automated daily backups will be conducted to ensure data integrity.

There is no data-archiving as these data are 'owned' by the UK Biobank, we are only allowed to use it as long as the project runs. The original data remains at the UK Biobank and can be downloaded/obtained from them at any time when needed. Therefore, there are only costs for data access/right ('Maintenance Dataset'), and the datamanager ('Division') and data analysis tool/storage ('Other').

For purposes of analyses digital files are partly and temporarily stored on the high-performance computer cluster (HPC) facilitated by the UMC Utrecht. Data storage is only accessible to authorized personnel. Phenotype data is accessible based on an application number as given out by the UK Biobank as part of an approved application. The phenotype data should be stored per-group and only made accessible to named in the respective application. These data are not stored in the RFS associated with this DMP: in the event the data are deleted we can re-download these from the UK Biobank servers.


## 5. Data Organization and Documentation
Data will be organized by sample location, species, and collection year. Each dataset will have an accompanying metadata file detailing data structure, variable definitions, and data processing steps. 

(These metadata files are obtainable when downloading data through the [NOAA](https://www.ncei.noaa.gov/products/paleoclimatology/tree-ring) tree ring archive.)

## 6. Data Preservation and Long-Term Access
Upon project completion, the dataset will be deposited in a recognized tree ring database or repository, ensuring long-term preservation and discoverability ([NOAA](https://www.ncei.noaa.gov/products/paleoclimatology/tree-ring)). The repository will assign a Digital Object Identifier (DOI) for reliable referencing.

## 7. Data Sharing and Access
After a brief embargo period to allow for primary analysis, the dataset will be openly accessible through the repository under a Creative Commons Attribution (CC-BY) license, promoting data reuse with proper attribution.

All R and Python code will be shared on our [lab website](https://github.com/cibs) no later than when publications are submitted. The shared files will include the main readme.md file for the project, and also instructions and parameter choices to reproduce analysis. The CIBS Github page is publicly assessable and will be hosted for at least 5 years after the grant award ends. The R and Python codes are freely available through Github, and will be hold at least 5 years after the award ends.




## 8. Data Ethics and Legal Compliance
Ethics approval has been obtained for the study. All data collection follows ethical guidelines, and any potential impact on tree populations or ecosystems will be minimized.

## 9. Roles and Responsibilities
The lead dendrochronologist will oversee data management, ensuring accuracy and quality. Field technicians will collect core samples and measurements. The institution's data management team will facilitate repository submission.

## 10. Budget and Resources
Funding has been allocated for specialized dendrochronology equipment, data storage, repository fees, and data management software.

This Data Management Plan ensures responsible collection, storage, and sharing of tree ring data, in adherence to dendrochronological best practices and ethical standards. It promotes the transparency, reproducibility, and accessibility of tree ring research.
