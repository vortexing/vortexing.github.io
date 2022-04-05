---
permalink: /consulting/
title: "Consulting"
---

### Clinical/Genomics Data Management
I'm the Principal Investigator on an IRB approved data management framework that supports researcher use of cloud and on-premise data intensive resources at the Fred Hutch, specifically for human genomics research projects (the Fred Hutch Translational Genomics Repository).  As projects and technology change, the specific challenges associated with adeptly managing data use restrictions or human subject aspects along with the sometimes large data themselves do as well.  For many research labs, developing and evolving the information technology skillsets required to effectively manage all their data is not a primary focus of staff, but poses a risk of lost opportunity for the research itself to progress, or worse.

We have found that a consulting model works well to support these research labs.  By specifically engaging someone with the research information technology experience to translate needs, advise on strategy, and provide support for necessary training of staff, we can reduce the time spent wasted on fighting the underlying technology.  This allows research staff to leverage the ever-evolving set of technology resources they have available to them, while allowing them to focus on gleaning knowledge from the data via the research itself.


### Workfows, Reproducibility and Sharing  
 Once you wrangle your data, the logical next step is to develop reproducible, sharable, documented methods for analyzing said data.  To this end, I lead the testing and custom configuration of the workflow manager [Cromwell](https://github.com/broadinstitute/cromwell), for use by investigators at the Hutch, including supporting additional development required for Cromwell to use AWS Batch as a backend via scope definition and testing in collaboration with AWS and Fred Hutch IT.


#### Workflows and Computing Support  
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

#### R packages  
- Develop an R package to interact with Cromell workflows via R using [fh.wdlR](https://github.com/FredHutch/fh.wdlR).
- Recently transitioned to a new, developing R package for dataset annotation management based on the Translational Genomics Repository system at the Fred Hutch using [tgR.data](https://github.com/FredHutch/tgR.data)

#### Shiny apps  
Due to privacy concerns, most of my Shiny Apps aren't publicly visible but are in use by investigators at the Fred Hutch, but contributions are visible via my GitHub profile. 
- [Fred Hutch Cromwell app](https://cromwellapp.fredhutch.org/) here users can monitor their many workflows being run on the Fred Hutch compute cluster or in AWS from a single location.   
- Translational Genomics Repository data access app - here users can submit dataset annotations to the TGR system and view summary statistics about how much and where their data are.  


## Community Efforts
### Fred Hutch SciWiki
The [Biomedical Data Science Wiki](https://sciwiki.fredhutch.org) project aims to create a curated collection of Fred Hutch oriented documentation regarding policies, resources and tools available to our researchers supporting the generation, analysis and sharing of research data. I coordinate the project and previously supported the Wiki Writer/Editor program at the Fred Hutch. 



### Fred Hutch Bioinformatics and Computational Research Community
I administer a Slack workspace [here](https://join.slack.com/t/fhbig/shared_invite/zt-4hpsoszl-qU4hZU5H7yolOcNSzhlrxQ) that supports peer to peer support for researchers at the Hutch, UW, and local institutions working in data intensive areas.  
