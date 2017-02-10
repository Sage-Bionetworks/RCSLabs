# RCSLabs

Efforts to enable transparent and reproducible research are complementary &mdash; if not essential &mdash; to the [central goals](http://sagebase.org/who-we-are/overview/) at Sage Bionetworks. By identifying and adopting best practices for disseminating algorithms, tools, and computational workflows, we can increase both the utility and impact of data shared through Sage-coordinated projects. This repository serves as a landing page for collating, discussing, and testing new and existing resources that focus on the reproducibility, portability, and scalability of code and software used for computation in biomedical research. As "infrastructure" is too general and "computing" too specific to describe the scope of this working group, we'll instead go with a name that highlights the main objective: **Reproducible Computational Science**. 

This repo will be fairly unstructured, with pieces of code and scripts from a variety of languages along with assorted documentation. We'll use the [**wiki**](https://github.com/Sage-Bionetworks/RCSLabs/wiki) to organize links, resource summaries, and other types of prose-level information. Please use the [**issues**](https://github.com/Sage-Bionetworks/RCSLabs/issues) page to propose, assign, and discuss new ideas and tasks. Some loose/suggested guidelines for starting and structuring new projects (or contributing to existing projects) to come soon.

Topics and tools to be investigated include, but are not limited to the following:

**Sharing tools, analyses, workflows**
+ packages & package repositories 
+ managing dependencies & environments
+ package managers (e.g., conda, packrat, packer)
+ containers (e.g., Docker, Singularity)

**Workflows/pipelines**
+ terminology: tools vs. workflows vs. tasks
+ workflow descriptors (e.g., CWL)
+ workflow engines/managers (e.g., rabbix, Snakemake, Ruffus, Nextflow, bcbio, etc.)
+ workflow compute platforms (e.g., Seven Bridges, CGC, Arvados)

**Scalable computing (grid & cloud)**
+ batch job execution (e.g., AWS Batch, Kubernetes, Docker Swarm)
+ cluster deployment & management (e.g., CfnCluster, StarCluster)
+ cloud services: AWS vs. Google Cloud vs. Azure

**Community standards**
+ annotations
+ schemas & APIs (e.g., GA4GH, Ensembl)

**Sage practices & infrastructure**
+ Synapse integragion
+ building tools and containers (for Sage scientists or for Synapse users)
+ writing workflow descriptors (for Sage scientists or for Synapse users)

