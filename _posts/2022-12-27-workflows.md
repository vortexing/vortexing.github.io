---
layout: post
title:  "Computing and Analysis in Research"
info: "Cromwell, WDL and large scale computing workflow technology and training"
type: "Project Lead"
tech: "Technology"
---


I currently support multiple projects for investigators at the Fred Hutch, providing subject matter expertise on data management for genomics data, advising and technical support for various cloud resources and guidance and training for software sharing.  I often advise and train staff in the use of GitHub, Docker, WDL based workflows, and reproducible code and workflow sharing, depending on the particular expertise level and needs of individual groups. 

## Workflows, Reproducibility and Sharing  
 Once you wrangle your data, the logical next step is to develop reproducible, sharable, documented methods for analyzing said data.  To this end, I lead the testing and custom configuration of the workflow manager [Cromwell](https://github.com/broadinstitute/cromwell), for use by investigators at the Hutch, including supporting additional development required for Cromwell to use AWS Batch as a backend via scope definition and testing in collaboration with AWS and Fred Hutch IT.


## Workflows and Computing Support  
Recently, I've worked with folks to tune up code to share, Dockerize it if need be, and wrap it in modern workflow definitions such that it could be run by others, on-prem or in the cloud.  Often this work happens behind the scenes of more visible publications, but open access and sharing (when appropriate) has been a focus of mine during this work.  

I have been writing and customizing sharable workflows (in WDL) as part of collaborations that enable sharing of tasks and entire workflows across groups and across institutions leveraging Docker containers and reproducible design of workflows.

Some public, and unfortunately some still private, resources I support include:

A custom configuration for the Cromwell workflow manager at the Hutch:
- [diy-cromwell-server](https://github.com/FredHutch/diy-cromwell-server)
- Documentation on why and how to get started with Cromwell and WDL workflows: [Cromwell entry in SciWiki](https://sciwiki.fredhutch.org/compdemos/Cromwell/)

Github WDL workflows, most of which are still private while publications are in preparation:
- Consensus variant calling for paired cancer tissue exome data, including FFPE artifact awareness, QC metrics and data formatting using external tools and best practices
- Single cell genotyping suite from 10x Single Cell RNA seq with custom enrichment protocol
- Public dataset retrieval and downstream analysis, such as RNA seq analysis via STAR, for new computational users
- Custom targeted variant calling for reprocessing existing clinical genomic sequencing data for assessment of novel, research use only mutations
- Custom WDL creation and dockerization for several emerging python and R tools

### R package
- Develop an R package to interact with Cromwell workflows via R using [fh.wdlR](https://github.com/FredHutch/fh.wdlR).

### Shiny app
- [Fred Hutch Cromwell app](https://cromwellapp.fredhutch.org/) here users can monitor their many workflows being run on the Fred Hutch compute cluster or in AWS from a single location.   


## Training and Documentation
In collaboration with the Fred Hutch Data Science Lab, we've generated a guide for using Cromwell to run WDLs at [Fred Hutch](https://hutchdatascience.org/FH_WDL101_Cromwell/), and an emerging guide to [designing and testing WDL workflows](hutchdatascience.org/FH_WDL102_Workflows/).  

As a member of the [OpenWDL governance team](https://openwdl.org/), I've also contributed to [community documentation about WDL](https://wdl-docs.readthedocs.io/en/stable/) as well.  