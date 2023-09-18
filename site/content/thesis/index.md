---
title: "PhD Thesis"
date: 2023-04-21
draft: false

showDate : true
showDateUpdated : false
showHeadingAnchors : false
showPagination : false
showReadingTime : false
showTableOfContents : true
showTaxonomies : false
showWordCount : false
showSummary : false
sharingLinks : false
showEdit: false
showViews: false
showLikes: false
layoutBackgroundHeaderSpace: false
---

I defended my PhD thesis, "TTCC: Transactional-Turn Causal Consistency", in Paris on Friday 21st April 2023 at 14:00 (Paris Time).
My PhD research was completed within the [LIP6](https://lip6.fr) with the [Delys](https://team.inria.fr/delys/) INRIA team and under the supervision of [Marc Shapiro](https://lip6.fr/Marc.Shapiro/).

The official manuscript is available [here](https://theses.hal.science/tel-04137260).

## Thesis defense live video

{{< youtube id="mRCwQgOa3JY" title="Benoît Martin's PhD defense" >}}


## Jury members
-   **Reviewer**: [Achour Mostefaoui](https://www.univ-nantes.fr/achour-mostefaoui) <br/>
    Professor, Université de Nantes  
-   **Reviewer**: [Gaël Thomas](http://www-public.imtbs-tsp.eu/~thomas_g/) <br/>
    Professor, Telecom SudParis  
-   **Examiner**: [Bernd Amann](http://www-bd.lip6.fr/wiki/site/membres/bernd/start) <br/>
    Professor, Sorbonne Université, LIP6 
-   **Examiner**: [Annette Bieniusa](https://softech.informatik.uni-kl.de/team/annettebieniusa) <br/>
    Professor, Université Technique de Kaiserslautern 
-   **Examiner**: [Carla Ferreira](http://ctp.di.fct.unl.pt/~cf/) <br/>
    Associate Professor, Université NOVA de Lisbon  
-   **Examiner**: [Peter Van Roy](https://www.info.ucl.ac.be/~pvr/cvvanroy.html) <br/>
    Professor, Université Catholique de Louvain 
-   **Supervisor**: [Marc Shapiro](https://lip6.fr/Marc.Shapiro/) <br/>
    Distinguished Research Scholar (Emeritus), Sorbonne Université, LIP6, Inria  
-   **Advisor**: [Mesaac Makpangou](https://lip6.fr/Mesaac.Makpangou) <br/>
    Researcher, Sorbonne Université, LIP6, Inria

## Abstract
Today, stateful serverless functions are chained together through a message-based infrastructure and store their durable state in a separate database. This separation between storage and compute creates serious challenges that may lead to inconsistency and application crashes. 
A unified consistency model for message passing and shared memory is required to avoid such errors. The model should ensure that multiple pieces of data remain mutually consistent, whether data is sent using messages or shared in a distributed memory.  
Based on a well-known message-based model (actors) and a state model (transactional shared memory), we propose a unified communication and persistence model called Transactional Turn Causal consistency (TTCC). TTCC is asynchronous, preserves isolation, and ensures that the message and memory view are mutually causally consistent.

