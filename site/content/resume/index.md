---
title: "Resume"
date: 2023-02-20T17:08:51+01:00
draft: false

showDate : false
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

## Experience

{{< timeline >}}

{{< timelineItem icon="cea.png" header="CEA / Maison de la Simulation" subheader="Permanent Research Scientist" badge="12/2023 - Current">}}
{{< figure src=cea.png alt="CEA logo" class="customEntitityLogo">}}
I'm currently working around in-situ analytics in high-performance computing (HPC) and numerical simulations, with a particular emphasis on physical applications, parallel software engineering and programming models.
{{< /timelineItem >}}

{{< timelineItem icon="lip6.png" header="LIP6" subheader="PhD Student" badge="09/2019 - 05/2023">}}
{{< figure src=lip6.png alt="LIP6 logo" class="customEntitityLogo">}}
Today, stateful serverless functions are chained together through a message-based infrastructure and store their durable state in a separate database.
This separation between storage and compute creates serious challenges that may lead to inconsistency and application crashes. A unified consistency model for message passing and shared memory is required to avoid such errors.
The model should ensure that multiple pieces of data remain mutually consistent, whether data is sent using messages or shared in a distributed memory.
Based on a well-known message-based model (actors) and a state model (transactional shared memory), we propose a unified communication and persistence model called Transactional Turn Causal Consistency (TTCC).
TTCC is asynchronous, preserves isolation, and ensures that the message and memory view are mutually causally consistent.
<br><br>Keywords: Causal Consistency, Serverless, Actor Model, Shared memory
{{< /timelineItem >}}

{{< timelineItem icon="esgi.png" header="ESGI" subheader="Teacher in Parallel Programming" badge="09/2017 - 11/2019">}}
{{< figure src=esgi.png alt="ESGI logo" class="customEntitityLogo">}}
Teacher in parallel programming for 5th year Computer Science students specialized in Software Architecture. 
During my time teaching this class, I also prepared and supervised exams and group projects. In-class lessons and projects were in C++.
{{< /timelineItem >}}

{{< timelineItem icon="inria.png" header="Inria Aramis team" subheader="R&D Engineer" badge="05/2018 - 10/2019">}}
{{< figure src=inria.svg alt="Inria logo" class="customEntitityLogo">}}
Based at the Brain and Spine Institute at the Pitié-Salpêtrière hospital in Paris, I was a member of the ARAMIS Inria team.
I participated the development of Deformetrica which was ported from C++ to Python.
I contributed by optimizing the performance of the application to help PhD students run experiments on a bigger dataset.
Also, I contributed to PyKeops which is used in Deformetrica to offload kernel operations.

I used the following technologies:
<ul>
  <li>PyTorch: tensor library with auto-differentiation used within the Deformetrica application</li>
  <li>Anaconda: library repository for Deformetrica</li>
  <li>Python/Jupyter/Matplotlib/Nibabel: to prototype plot and read MR Images</li>
  <li>C++/Cuda: Keops (kernel operations library)</li>
</ul>
{{< /timelineItem >}}

{{< timelineItem icon="tredzone.png" header="Tredzone" subheader="R&D Software Engineer" badge="07/2015 - 03/2018">}}
{{< figure src=tredzone.jpg alt="tredzone logo" class="customEntitityLogo">}}
Tredzone offers a high performance, low latency framework in C++ and Java for the capital market industry and other performance-hungry industries. I contributed to the development of the C++ and Java actor model runtime.
Additionally, we develop a library in C++11, which leverages our C++ actor framework to compose a high performance application. Our framework is used in production at Euronext to power the core of their Optiq solution.

The following technologies are used:
<ul>
  <li>C++11 : highly abstracted runtime and SDK</li>
  <li>Solarflare : sub-microsecond feedhandlers</li>
  <li>Java JNI : predictable latency Java runtime and SDK</li>
  <li>Realtime Linux : tweaking for stable and ultra-low latency</li>
</ul>
{{< /timelineItem >}}

{{< timelineItem icon="intel.png" header="Intel Corp" subheader="HPC Application Engineer" badge="07/2014 - 12/2014">}}
{{< figure src=intel.png alt="Intel logo" class="customEntitityLogo">}}
Intern at the Exascale research lab in Paris. The lab was founded by Intel, the University of Versailles Saint Quentin (UVSQ), le Commissariat à l’énergie atomique et aux énergies alternatives (CEA) and Grand Equipement National de Calcul Intensif (GENCI).
<br>
I was involved in the analysis and code optimization of the Gysela5D gyrokinetic code for Intel’s Many Integrated Core Architecture (Intel MIC/Xeon Phi) and Sandy Bridge Xeon Architecture.

<br><br>Keywords: Roofline Model, VTunes, Software Development Emulator (SDE), Intel compiler 
{{< /timelineItem >}}

{{< /timeline >}}





---

## Education

<table>
    <thead>
        <tr>
            <th>School</th>
            <th>Link</th>
            <th>Degree</th>
            <th>Date</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td><img class="customEntitityLogo" src="su.svg"/></td>
            <td><a href="https://online.hbs.edu/" target="_blank">Sorbonne Université</a></td>
            <td>PhD in Distributed Systems</td>
            <td>2023</td>
        </tr>
        <tr>
            <td><img class="customEntitityLogo" src="uqac.png"/></td>
            <td><a href="https://uqac.ca" target="_blank">Université du Québec à Chicoutimi (UQAC)</a></td>
            <td>Master</td>
            <td>2014</td>
        </tr>
        <tr>
            <td rowspan=2><img class="customEntitityLogo" src="esgi.png"/></td>
            <td rowspan=2><a href="https://esgi.fr" target="_blank">Ecole Supérieur de Génie Informatique (ESGI)</a></td>
            <td>Masters - Software Architect</td>
            <td>2014</td>
        </tr>
        <tr>
            <td>Bachelor</td>
            <td>2012</td>
        </tr>
    </tbody>
</table>


---

## Publications

- **Benoît Martin**, Laurent Prosperi and Marc Shapiro. Transactional-Turn Causal Consistency. _EURO-PAR 2023 – 29th International European Conference on Parallel and Distributed Computing_, Aug 2023, Limassol, Cyprus. [pdf](https://hal.science/hal-04117344)
- **Benoît Martin**. TTCC : Transactional-Turn Causal Consistency. PhD thesis defended in April 2023. [pdf](https://theses.hal.science/tel-04137260)
- **Benoît Martin** and Marc Shapiro. 2022. Shared memory for the actor model. In _Conférence francophone d’informatique en Parallélisme, Architecture et Système (COMPAS)_, Amiens, France. [pdf](https://hal.inria.fr/hal-04004775v1)
- **Benoît Martin**, Laurent Prosperi and Marc Shapiro. 2020. An environment for composable distributed computing. [pdf](https://hal.inria.fr/hal-03146124)
- Baptiste Couvy-Duchesne, Johann Faouzi, **Benoît Martin**, Elina Thibeau–Sutre, Adam Wild, Manon Ansart, Stanley Durrleman, Didier Dormont, Ninon Burgos and Olivier Colliot. 2020. Ensemble Learning of Convolutional Neural Network, Support Vector Machine, and Best Linear Unbiased Predictor for Brain Age Prediction: ARAMIS Contribution to the Predictive Analytics Competition 2019 Challenge. _Frontiers in Psychiatry_ 11, (2020). [pdf](https://www.frontiersin.org/articles/10.3389/fpsyt.2020.593336)
- Alexandre Bône, **Benoît Martin**, Maxime Louis, Olivier Colliot and Stanley Durrleman. 2019. Hierarchical modeling of Alzheimer’s disease progression from a large longitudinal MRI data set.  [pdf](https://hal.inria.fr/hal-02090275)
- Alexandre Bône, Maxime Louis, **Benoît Martin** and Stanley Durrleman. 2018. Deformetrica 4: An Open-Source Software for Statistical Shape Analysis. In _Shape in Medical Imaging_ (Lecture Notes in Computer Science), Springer International Publishing, Cham, 3–13. [pdf](https://doi.org/10.1007/978-3-030-04747-4_1)
- Hamid Mcheick, Louis Deladiennee, Mickael Wajnberg, **Benoît Martin** and Marc Abi-Khalil. 2014. Universal Connector Framework for Pervasive Computing Using Cloud Technologies. _Procedia Computer Science_ 34, (January 2014), 141–148. [pdf](https://doi.org/10.1016/j.procs.2014.07.072)


