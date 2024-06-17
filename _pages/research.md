---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

{% include base_path %}
<!--- header: --->
<!--- overlay_image: galaxy2.jpg --->

I have worked on a variety of problems, in several different biological systems, under the broad umbrella of non-linear dynamics and complex systems. Currently, I work on theoretical models of ecology and evolution of viruses. During my PhD, I worked on biomechanics of epithelial tissues, using a combination of experiments and theory. I am not actively working in this area right now but look forward to getting back into it at some point in the future. As an undergrad, I worked on collective animal movement using mathematical models.


<details>
  <summary><b>Ecology and evolution of temperate phages</b></summary>

<p>When we normally think of phages (viruses that exclusively infect bacteria), we only think of the lytic life cycle: The virus enters the host cell, hijacks the host machinery to make copies of itself, eventually kills the host and releases its virus offspring that go onto infect other hosts. This picture is true for phages that are obligately lytic. However, temperate phages, in addition to the lytic cycle, can undergo a lysogenic life cycle: they enter the host but instead of hijacking the host machinery, the viral genetic material integrates with that of the host and stays dormant until some internal or external trigger switches it back into the lytic cycle. In this case, the virus replicates when the host cell divides and replicates its own genome. While the lytic life cycle involves antagonism between the phage and its host, lysogeny is mutualistic - the reproductive success of the phage depends on the reproductive success of the host. Thus, temperate phages have a complicated relationship with their hosts which leads to interesting effects all the way from the molecular to the community level, across timescales ranging from virus-host encounter rates to evolutionary timescales. My current research focuses on the ecological and evolutionary consequences of this complicated relationship between temperate phages and their hosts. To do so, I use mathematical models that bridge scales - from cells to populations to communities.</p>



<p>The lysis-lysogeny decision is made at the level of individual host cells. It has been shown that the number of phages infecting a cell and host size affect the probability of lysogen formation (Zhang et al. 2021). I am interested in how this cell-level decision is regulated and how it affects the population dynamics of the virus-host system.</p> 


<p>At the population level, lysogen abundance is affected by host and resource availability. In polar marine environments, for example, lysogen abundance varies seasonally with higher and lower abundance in winters (low resource availability) and summers (high resource availability) respectively (Brum et al. 2016). To examine the drivers of viral strategies, I use non-linear ordinary differential equations to model the eco-evolutionary dynamics of temperate phages in fluctuating environments with phages of high and low resource availability.</p>


<p>Induction of lysogens - the process of a lysogen switching back to the lytic cycle - has two consequences: Its bad for the individual lysogen since lysis involves the death of that particular lysogen but, its good for the lysogen population in general because the newly released phage particles can go onto infect new host cells creating new lysogens. So, induction is harmful at the individual level but beneficial at the population level. I am interested in how these conflicting effects at different scales impact community ecology.</p>

</details>


<details>
  <summary><b> Biomechanics of epithelial tissues in invertebrates </b></summary>

  <p>Mechanical forces play a fundamental role in shaping biological structure and function. They set limits to length and timescales for these processes. In turn, the dynamical response of biochemical signalling pathways and genetic circuits to these mechanical forces create feedback loops that lead to interesting non-linear effects on the stress-strain relationship of biological materials. During my PhD, I studied consequences of these complex feedback loops at the population, organismal and tissue levels over timescales ranging from months to hours to minutes using <i>Hydra</i> and planarians as my model systems.</p>

  <details>
    <summary><b> Mechanics of self-bisection in planarians </b></summary>

    <img src="../images/PlanarianFission.png" alt="Schematic of planarian fission across three different species" width="500" height="500">
    
    Flatworms (planarians) reproduce asexually by ripping their body into two (or more) pieces along their length. The pieces then regenerate into fully grown adults. The survival of the offspring pieces has been shown to depend on their size. There are several interesting questions one can ask about this bisection process:
    
    <ol>
  <li>How do animals generate sufficient force to rip themselves apart?</li>
  <li>What decides when an individual should reproduces?</li>
  <li>What decides where along the body the animal should split?</li>
  <li>What sets how many pieces the animal should split into? </li>
  </ol>
    <p> We use live imaging to compare and contrast the kinematics of self bisection in three different planarian species. We show how they used body shape changes and substrate adhesion to generate the stresses necessary to overcome the ultimate tensile strength of the tissue. We also show how mechanical constraints affect resource allocation to the offspring produced by this self bisection process and develop predictive models to relate the number and size of the offspring to the size of the parent.</p>
<!---xiii
In chapter ??, we use gain-of-function and loss-of-function experiments to show how a
transition in the period and amplitude of osmotically driven shape oscillations in regenerating
Hydra tissue spheres is caused by the formation of an actively regulated mouth structure.
In chapter 2, we use a combination of experiments and mathematical modelling to study
the dynamics of mouth opening in Hydra. We show how mechanical nearest-neighbor coupling
can be sufficient to generate long range order over long timescales from underlying short range
stochastic forces. We also show how anharmonic elasticity affects can modulate the long range
order of the deformation and its timescale in non-intuitive ways.
In appendix ??, we develop the chemical linalool as a powerful, reversible anesthetic that
can be for imaging Hydra and performing surgical manipulations on them. We characterize the
activity of the linalool, tested it for its short term and long term health effects on the animals
and validated its utility in imaging and surgical applications.
Together, these studies show how non-linear effects produced by the interplay of bio-
chemical signalling, shape changes and mechanical stresses lead to a range of complex dynamical
patterns and behaviors in biological systems. --->
