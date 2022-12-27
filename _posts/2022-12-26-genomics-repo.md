---
layout: post
title:  "Clinical Genomics Data Management"
info: "Genomics repository and cloud-based data storage support"
type: "Project Lead"
tech: "Collaboration, Technology"
---
## Clinical/Genomics Data Management
I'm the Principal Investigator on an IRB approved data management framework that supports researcher use of cloud and on-premise data intensive resources at the Fred Hutch, specifically for human genomics research projects (the Fred Hutch Translational Genomics Repository).  As projects and technology change, the specific challenges associated with adeptly managing data use restrictions or human subject aspects along with the sometimes large data themselves do as well.  For many research labs, developing and evolving the information technology skill sets required to effectively manage all their data is not a primary focus of staff, but poses a risk of lost opportunity for the research itself to progress, or worse.

We have found that a consulting model works well to support these research labs.  By specifically engaging someone with the research information technology experience to translate needs, advise on strategy, and provide support for necessary training of staff, we can reduce the time spent wasted on fighting the underlying technology.  This allows research staff to leverage the ever-evolving set of technology resources they have available to them, while allowing them to focus on gleaning knowledge from the data via the research itself.

### Translational Genomics Repository  
As the *Principal Investigator* of the Fred Hutch Translational Genomics Repository, I have developed a collaborative data management and analysis system supporting ongoing genomics research.  The project focuses on the use of on-prem and cloud (AWS, Google, and now Azure) based data storage, harmonized collection of associated clinical and scientific metadata across groups, and the use of workflow managers (Cromwell/Nextflow) plus containerization for reproducible bioinformatic analyses using both on-prem (SLURM) and cloud (AWS Batch) based computing resources.  End users include researchers with a range of experience with bioinformatics, large data management, and computing familiarity.   

- Build R packages and R Shiny applications facilitating expert/non-expert use of compute resources via workflow manager (Cromwell) API as well as straightforward access to processed datasets for analysis.  Basic use of python for supporting infrastructure/interactions with AWS.  
- Created the data management structure that supported cloud-based (primarily AWS S3) genomic data storage (including indexing and tagging of related datasets) of 1500+ research datasets and managed the associated clinical, experimental and laboratory metadata (including ontology development and harmonization across projects) across 8 collaborative projects and across 5 investigators.
- Curate a harmonized clinical, experimental and laboratory data ontology for data from human specimens (lung, multiple types of leukemia, myelodysplastic syndrome, normal donations) as well as for datasets from 4 other species, for a range of genomic data types from single cell RNA sequencing on up to whole exome sequencing datasets.  
- Interact closely with Fred Hutch IT, Business Development, Information Security Office and Institutional Review Board to ensure that technological solutions met requirements associated with human clinical and genomic data with respect to patient consent, study approval (by IRB), de-identification, access logging and all relevant security concerns.  
- Lead the testing and custom configuration of the workflow manager [Cromwell](https://github.com/broadinstitute/cromwell), for use by investigators at the Hutch, as well as write and share my own analysis workflows using Docker and WDL workflow language.


### R packages  
- Developed an R package to interact with Cromwell workflows via R using [fh.wdlR](https://github.com/FredHutch/fh.wdlR).
- Recently transitioned to a new, developing R package for dataset annotation management based on the Translational Genomics Repository system at the Fred Hutch using [tgR.data](https://github.com/FredHutch/tgR.data)

### Shiny apps  
Due to privacy concerns, most of my Shiny Apps aren't publicly visible but are in use by investigators at the Fred Hutch, but contributions are visible via my GitHub profile. 
- [Fred Hutch Cromwell app](https://cromwellapp.fredhutch.org/) here users can monitor their many workflows being run on the Fred Hutch compute cluster or in AWS from a single location.   
- Translational Genomics Repository data access app - here users can submit dataset annotations to the TGR system and view summary statistics about how much and where their data are.  
