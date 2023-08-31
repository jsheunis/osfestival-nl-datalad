# DataLad Workshops at the NL Open Science Festival 2023

This repository contains content for the DataLad workshops at
the **NL Open Science Festival 2023** in Rotterdam, The Netherlands.

- Date: 31 August 2023
- Location: Erasmus University, Rotterdam
- Event website: https://opensciencefestival.nl/
- Presenters:
   - Stephan Heunis

## Slides

Slides: https://jsheunis.github.io/osfestival-nl-datalad

Mainly based on the presentation by Michael Hanke:

[What is DataLad and what can it do for you?](https://files.inm7.de/mih/pres/talks/whatisdatalad_2023.html#/)

## Cloud-compute environment

Code-along participation in the workshop can be done in your
browser on a cloud server with JupyterHub:
[https://jupyterhub.datalad.nl](https://jupyterhub.datalad.nl)

This server has been set up prior to the start of the workshop,
for ease of use and to minimize delays. Its has all required
software pre-installed so there is no need for participants to
prepare at all.

All you have to do is log in to the server at the start of the workshop
(selecting a provided username and your ownp assword on first signup)
and then start using it.

The server will be shut down after the session.

## Abstract

Research Data Management (RDM) is a core tenet of Open Science, and for good reason.
It encompasses the tools, practices, and ideals that allow our scientific outputs to
move from opaque descriptions to tangible digital objects that adhere to the FAIR principles.
In turn, FAIR data allow replication and verification of our work, fosters public trust in
science, promotes collaboration, and underlies scientific progress. However, the “nitty gritty”
of everyday steps necessary to conduct research data management can still be a practical challenge
for individual researchers, research groups, and institutes alike.

This hands-on and code-along workshop introduces participants to the free and open source software
tool DataLad for reproducible research data management. The workshop will focus on how to use standard
DataLad features to address everyday RDM challenges, and aims particularly at transforming an often
abstract understanding of RDM tasks into intuitive and practical experience:

- How can we version control arbitrarily large datasets?
- How do we keep track of where certain parts of our cohort data are stored, and in which format?
- How do we minimise the number of copies of a dataset to save money on storage space?
- How do we determine which version of the code was run on a particular set of input data in order to generate a given set of results?
- How can a geographically distributed set of collaborators contribute to the same dataset and analysis, interactively building on top of each others’ contributions?
- How easily can we rerun a specific analysis on a new dataset? How can we reproduce a full publication with a single command?

These are all concrete examples of everyday RDM tasks that can seem daunting at first,
but for which DataLad has specific solutions that participants will learn about.
During the workshop, the mostly interactive code-along process will be interspersed with
high-level explanations of particular DataLad features and how they solve common RDM challenges,
particularly in the modern context of big data, data privacy regulations, distributed collaboration,
and the needs for precise provenance tracking and annotated data publishing. The process will be 
tructured so as to be beneficial to a range of participants: from individual researchers with a
technical interest in using the DataLad software in their own projects/groups, to system administrators
that are curious about the benefits of DataLad for the HPC clusters they manage, to institute-level
decision makers who want to find out about the benefits of DataLad for publishing FAIR data catalogs.
This range makes the workshop widely applicable to the attendees of the Open Science Festival.