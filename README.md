# cnvc_elc_workshop_external
* Aaron F. Wells
* aaron{dot}wells{at}aecom{dot}com
* AECOM Technical Services

## Introduction
This repository is for managing and collaboration of files for the Canadian National Vegetation Classification (CNVC) Ecological Land Classification workshop. Funding for preparing the workshop materials was provided by [NatureServe Canada](https://www.natureserve.org/canada).

The CNVC is an ecological classification of natural and semi-natural Canadian vegetation (Faber-Langendoen et al. 2014; Baldwin et al. 2019). The classification is a hierarchical taxonomy, describing vegetation conditions at different levels of generalization from global to local. This repository includes training materials that can used to host a workshop to train biologists and ecologists in the art and science of ecological classification using the CNVC system. The hands-on training focuses on developing classification skills through the analysis of sample and/or real-world ecological relevé plot data using multivariate statistical techniques and expert-based classification using manual tabulation or qualitative sorting. Participants will learn to apply CNVC criteria across various levels of the classification hierarchy. 

The primary goal of this project is to prepare training materials that equip participants with the skills necessary to produce consistent ecological classifications, review and critique existing classifications, and oversee related work conducted by contractors. The training program combines formal classroom instruction with practical, hands-on experience. Participants will have the opportunity to work with sample datasets included in this repository or they may choose to use their own data, strengthening their ability to advance ecological classification programs and contribute to the CNVC system.

The workshop includes pre-workshop data cleaning sessions, including two PowerPoint presentations and an RMarkdown file with R code used to prepare the examples shown in the presentations. There is also a recommended reading list.

The workshop itself includes a PowerPoint presentation and three practical sessions. The practical sessions are described below.

The PowerPoint files, HTML versions of the practical sessions, and PDFs of relevant literature are here: https://www.dropbox.com/scl/fo/q7rwgbgq720duudljrhho/AI68cKrhLIRCSp73ba9c-6E?rlkey=ulm26ikmylezhvwsiogtj0ab6&st=uq06yj7t&dl=0

## Practical Session 1

The purpose of the first practical session introduces a number of multivariate statistical analyses that are used in ecosystem classification, including ordination, gradient analysis, cluster analysis, and indicator species analysis. In addition, this session will introduce techniques to quantitatively compare the results of these analyses to select the best output to use to support the ecosystem classification. This session uses the Saskatchewan forest ecosystem classification data set with only the forest and woodland plots. In this session, focus on more the statistical analysis techniques that are being introduced and less on the overall data set being used.

## Practical Session 2

The first part of practical session 2 will run through an example of classifying alliances within an ecosite and aggregating those up to groups. Second, we will review the group classification using multivariate statistical analyses. The first part of this practical session will illustrate a typical analysis cycle working from the bottom up as detailed in Baldwin et al. (2019). While this is a type-based analysis, a similar workflow could be used for plot-based ecosystem classification efforts. In the second part runs through an example of assigning new communities (non-reference communities) to an existing classification (the prairie group classification) using R functions in the vegclust R library.

## Practical Session 3

The purpose of practical session 3 is to provide some examples of preparing data visualizations and data summaries for use in reporting and when preparing for a peer-review of classification results and proposed revisions to the CNVC.

## Literature Cited
Baldwin, K., K. Chapman, D. Meidinger, P. Uhlig, L. Allen, S. Basquill, D. Faber-Langendoen, N. Flynn, C. Kennedy, W. Mackenzie, M. Major, W (B.) Meades, C. Morneau, and J-P. Saucier. 2019. The Canadian National Vegetation Classification: Principles, Methods and Status. Natural Resources Canada, Canadian Forest Service Information Report GLC-X-23. Sault Ste. Marie, Ontario, CANADA. [also available in French]

Faber-Langendoen, D., T. Keeler-Wolf, D. Meidinger, D. Tart, B. Hoagland, C. Josse, G. Navarro, S. Ponomarenko, J-P Saucier, A. Weakley, and P. Comer. 2014. “EcoVeg: A New Approach to Vegetation Description and Classification.” Ecological Monographs 84(4): 533-561.

