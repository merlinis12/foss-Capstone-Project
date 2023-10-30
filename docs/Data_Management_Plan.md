# Data Management Plan

This document takes into consideration data that I use for my research.

## 0.Project Overview
**Project Title**: Identification of precision therapeutics for Alzheimer's disease prevention and treatment

**Principal Investigator**: PhD Francesca Vitali

**Data Manager**: PhD Francesca Vitali

**Collaborators**: Simona Merlini

**Project Rationale**: Alzheimer's disease (AD) is a progressive neurodegenerative disease that affects 5.8 million people in US with no effective therapeutic. Therapeutics to prevent, delay and treat AD are urgently needed.  The management and treatment of AD risk factors, such as diabetes and hypertension, might delay or prevent AD onset. To this point, an untreated risk factor generates a cascade that with time increases in complexity and ultimately results in AD. Our aim is to select risk factor profiles that are targetable with a drug class and assess if a therapeutic or a combination of therapeutics can disrupt the risk cascade modifying AD onset. 


## 1. Data Description

We use data from the [UK Biobank](https://www.ukbiobank.ac.uk) to characterize the impact of therapeutics targeting AD risk factors has on AD and cognitive impairment. UK Biobank is a large-scale biomedical database and research resource, containing in-depth genetic and health information from half a million UK participants. The database is regularly augmented with additional data and is globally accessible to **_approved researchers_**. 


## 2. Data Collection

UK Biobank is a world-leading biomedical database to enable scientific discoveries that improve human health. UK Biobank has Research Tissue Bank Approval till 2026 and through access to an unmatched amount of biological and medical data on half a million people living in the UK. Below, the main characteristics of the study:
- UK Biobank is a longitudinal study; it follows the health of 500,000 volunteer participants. 
- Participants were aged between 40-69 years when they joined UK Biobank between 2006-2010.
- Each participant attended a baseline assessment at a centre in England (89%), Scotland (7%) and Wales (4%).
- Participants provided their consent for long-term follow-up.
- Participants answered lots of questions about their health & lifestyle.
- Participants donated samples of blood, urine and saliva for long-term storage and analysis.
- Physical measurements were also taken (e.g. height, weight, spirometry, blood pressure, heel bone density).
- Many participants have undertaken MR brain & heart imaging, activity monitoring and online follow-up questionnaires.
- We have genetic data on all 500,000 participants.
- UK Biobank is not representative of the general population with evidence of a ‘healthy volunteer’ selection bias, details of which are published online.

UK Biobank is linked to the health-related records of the participants (through cancer and death registries and through hospital episode and primary care data) and in time to a range of other health-related records (further details are available on UK Biobank’s website).

## 3. Data Extraction
For the UK Biobank dataset, [Research Analysis Platform](https://www.ukbiobank.ac.uk/enable-your-research/research-analysis-platform) will be used to access and download the data.



## 4. Data Storage and Backup
There is no data-archiving as the data are 'owned' by the UK Biobank, we are only allowed to use it as long as the project runs. The original data remains at the UK Biobank and can be downloaded/obtained from them at any time when needed. Therefore, there are only costs for data access/right ('Maintenance Dataset'), and the datamanager ('Division') and data analysis tool/storage ('Other'). The data downloaded are stored in individual Box-health folder for each accepted researcher. In the event the data are deleted we can re-download these from the UK Biobank servers.


## 5.Data Protection and Security
The data downloaded from the UK Biobank website are stored in a Box-Health folder that can not be shared with noone beside the owner of the folder. The folder is password-protected.

The anonymisation of the data is irreversible in the hands of the researchers by way of the irreversible algorithm. UK Biobank retains an internal database which enables UK Biobank (and only UK Biobank) to reverse anonymise the data. They provide access to these data under their informed consent and only to people they deem certified to access these data. We obtain these data through a secure and encrypted link. The data are pseudonymised by the UK Biobank and are unique to each requested project; in other words the sampleIDs are random for each project number. For further details please refer to [UK Biobank Access Procedures](https://www.ukbiobank.ac.uk/media/llupxihh/20210309-access-procedures-v2-0-final.pdf).



## 6. Data Organization and Documentation
Data organization and documentation can be found in [UK Biobank Data Showcase](https://biobank.ndph.ox.ac.uk/showcase/). UK Biobank's Data Showcase displays on a public website all the data types and other metadata which are available within the Resource in a grouped format (i.e. a univariate distribution of the variable in appropriate categories, not at the individual participant level).

## 7. Data Preservation and Long-Term Access
As UK Biobank will retain a copy of the results data, it will not (and does not need to) proscribe a time limit to the researchers for the retention of data. 


## 8. Data Sharing and Access
As the data is privacy-sensitive, and managed by the UK Biobank we will refrain from sharing these data publicly; this should go through UK Biobank.

All R and Python code will be shared on our [lab website](https://github.com/cibs) no later than when publications are submitted. The shared files will include the main readme.md file for the project, and also instructions and parameter choices to reproduce analysis. The CIBS Github page is publicly assessable and will be hosted for at least 5 years after the grant award ends.


## 9. Data Ethics and Legal Compliance
Ethics approval has been obtained for UK Biobank.

## 10. Roles and Responsibilities
Each collaborator will be responsible for following UK Biobank data management rules.

## 11. Budget and Resources
Funding has been allocated for the Material Transfer Agreement (MTA) with a tier level 3.


