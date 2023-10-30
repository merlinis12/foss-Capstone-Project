# Data Management Plan

This document takes into consideration data that I use for my research.

## Project Overview
**Project Title**: Identification of precision therapeutics for Alzheimer's disease prevention and treatment

**Principal Investigator**: PhD Francesca Vitali

**Data Manager**: PhD Francesca Vitali

**Collaborators**: Simona Merlini

**Project Rationale**: Alzheimer's disease (AD) is a progressive neurodegenerative disease that affects 5.8 million people in US with no effective therapeutic. Therapeutics to prevent, delay and treat AD are urgently needed.  The management and treatment of AD risk factors, such as diabetes and hypertension, might delay or prevent AD onset. To this point, an untreated risk factor generates a cascade that with time increases in complexity and ultimately results in AD. Our aim is to select risk factor profiles that are targetable with a drug class and assess if a therapeutic or a combination of therapeutics can disrupt the risk cascade modifying AD onset. 


## 1. Data Description

We use data from the [UK Biobank](https://www.ukbiobank.ac.uk) to characterize the impact of therapeutics targeting AD risk factors has on AD and cognitive impairment. UK Biobank is a large-scale biomedical database and research resource, containing in-depth genetic and health information from half a million UK participants. The database is regularly augmented with additional data and is globally accessible to **_approved researchers_**. 


## 2. Data Collection

UK Biobank is a world-leading biomedical database to enable scientific discoveries that improve human health. UK Biobank has Research Tissue Bank Approval till 2026 and through access to an unmatched amount of biological and medical data on half a million people living in the UK. Below, the main characteristics of the study:
1.UK Biobank is a longitudinal study; it follows the health of 500,000 volunteer participants. 
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
UK Biobank is periodically updated and they send update to researchers by email with news about the development of items of interest to them. Further, UK Biobank advertises the existence and content of returned datasets via the [Data Showcase](https://biobank.ndph.ox.ac.uk/showcase/) and in due course using email alerts. For the UK Biobank dataset, [Research Analysis Platform](https://www.ukbiobank.ac.uk/enable-your-research/research-analysis-platform) will be used to access and download the data.



## 4. Data Storage and Backup
There is no data-archiving as these data are 'owned' by the UK Biobank, we are only allowed to use it as long as the project runs. The original data remains at the UK Biobank and can be downloaded/obtained from them at any time when needed. Therefore, there are only costs for data access/right ('Maintenance Dataset'), and the datamanager ('Division') and data analysis tool/storage ('Other'). The data downloaded are stored in the individual Box-health folder for each accepted researcher. In the event the data are deleted we can re-download these from the UK Biobank servers.


## 5.Data Protection and Security
The data downloaded from the UK Biobank website are stored in a Box-Health folder that can not be shared with noone beside the owner of the folder. The folder is password-protected.

The anonymisation of the data is irreversible in the hands of the researchers by way of the irreversible algorithm. UK Biobank retains an internal database which enables UK Biobank (and only UK Biobank) to reverse anonymise the data. They provide access to these data under their informed consent and only to people they deem certified to access these data. We obtain these data through a secure and encrypted link. The data are pseudonymised by the UK Biobank and are unique to each requested project; in other words the sampleIDs are random for each project number. For further details please refer to [UK Biobank Access Procedures](https://www.ukbiobank.ac.uk/media/llupxihh/20210309-access-procedures-v2-0-final.pdf).



## 6. Data Organization and Documentation
Data will be organized by sample location, species, and collection year. Each dataset will have an accompanying metadata file detailing data structure, variable definitions, and data processing steps. 

(These metadata files are obtainable when downloading data through the [NOAA](https://www.ncei.noaa.gov/products/paleoclimatology/tree-ring) tree ring archive.)

## 6. Data Preservation and Long-Term Access
As UK Biobank will retain a copy of the results data, it will not (and does not need to) proscribe a time limit to the researchers for the retention of data. 



## Restrictions
There is no general restriction on the types of data that it will make available to researchers, with the exception of items (such as NHS number, name and postal address) that could be used to identify individual participants. UK Biobank may restrict the amount of data which it makes available to researchers, either on the basis that the request is excessive or that in light of the size of the data sets (eye image data for example) it may be appropriate to make this available to researchers in other forms/formats; UK Biobank might decide to restrict access to certain types of data if it had concerns about its accuracy or its provenance. In general, however, UK Biobank will not impose its own quality criteria on the data, but rather will describe the origin of the data and the methods of data collection so that the data quality can be judged (by the researcher) on the basis of the particular research question being addressed; and It may be the case – although UK Biobank is not currently aware of any specific instances - that certain of the linkage data which UK Biobank incorporates within its database may only be provided with certain restrictions attached (which the relevant third party provider requires).

Are there any reasons to make part of the data NOT publicly available or to restrict access to the data once made publicly available? Yes (please specify) As the data is privacy-sensitive, and managed by the UK Biobank we will refrain from sharing these data publicly; this should go through UK Biobank.


## Metadata content and format
UK Biobank's Data Showcase will display on a public website all the data types which are available within the Resource in a grouped format (i.e. a univariate distribution of the variable in appropriate categories, not at the individual participant level). Further, there will be certain limitations on the amount of publicly available information on certain categories of sensitive data entries (for example the category "number of sexual partners6 "). For clarification, we would add that there is a clear distinction between (1) 'metadata' (or summary data) on participant characteristics, exposures and outcomes, which are displayed in the Data Showcase to anyone who visits the website and (2) data on individual, anonymised participants which will be provided only to approved bona fide researchers who have demonstrated that the particular research use the data will be put to is in the public good (and that they fulfil all the other requirements described in the Access Procedures).

Detailed information about each data field will be made available in the Data Showcase7 and in explanatory documents, which provide the necessary background as to how the measures were taken. Researchers will be able to select the type and parameters for the data they require through UK Biobank's Application Management System ("UK Biobank's AMS"). The metadata which describe the contents of the data repository are held in a standard relational database, which is accessible to both researchers and the general public through categorised and searchable web interfaces. As above, no one standard8 for metadata has been used as the data cover a number of different categories. UK Biobank would be prepared to work with researchers to develop and produce new encodings for data, which will be treated as a data assay (see section below).


## 7. Data Sharing and Access
After a brief embargo period to allow for primary analysis, the dataset will be openly accessible through the repository under a Creative Commons Attribution (CC-BY) license, promoting data reuse with proper attribution.

All R and Python code will be shared on our [lab website](https://github.com/cibs) no later than when publications are submitted. The shared files will include the main readme.md file for the project, and also instructions and parameter choices to reproduce analysis. The CIBS Github page is publicly assessable and will be hosted for at least 5 years after the grant award ends. The R and Python codes are freely available through Github, and will be hold at least 5 years after the award ends.




## 8. Data Ethics and Legal Compliance
Ethics approval has been obtained for the study. All data collection follows ethical guidelines, and any potential impact on tree populations or ecosystems will be minimized.

## 9. Roles and Responsibilities
The lead dendrochronologist will oversee data management, ensuring accuracy and quality. Field technicians will collect core samples and measurements. The institution's data management team will facilitate repository submission.

## 10. Budget and Resources
Funding has been allocated for the Material Transfer Agreement (MTA) with a tier level 3.

This Data Management Plan ensures responsible collection, storage, and sharing of tree ring data, in adherence to dendrochronological best practices and ethical standards. It promotes the transparency, reproducibility, and accessibility of tree ring research.
