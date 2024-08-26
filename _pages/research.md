---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

{% include base_path %}
<!--- header: --->
<!--- overlay_image: galaxy2.jpg --->

I have worked on a variety of problems, in several different biological systems, under the broad umbrella of non-linear dynamics and complex systems. As an undergrad, I worked in a theoretical ecology lab, where I used mathematical models to study collective animal movement. I then transitioned to working on biomechanics of epithelial tissues using a combination of theory, experiments and confocal imaging during my PhD. I am not actively working in this area right now but look forward to getting back into it at some point in the future. I have since made the jump back to ecology and evolution and am <b>currently working on theoretical models of ecology and evolution of temperate phages</b>.

<p>When we think of phages (viruses that exclusively infect bacteria), we typically only think of the lytic life cycle: The virus enters the host cell, hijacks the host machinery to make copies of itself, eventually kills the host and releases its virus offspring that go onto infect other hosts. This picture is true for phages that are obligately lytic. However, temperate phages, in addition to the lytic cycle, can undergo a lysogenic life cycle: they enter the host but instead of hijacking the host machinery, the viral genetic material integrates with that of the host and stays dormant until some internal or external trigger switches it back into the lytic cycle. In this case, the virus replicates when the host cell divides and replicates its own genome. While the lytic life cycle involves antagonism between the phage and its host, lysogeny is mutualistic - the reproductive success of the phage depends on the reproductive success of the host. Thus, temperate phages have a complicated relationship with their hosts which leads to interesting effects all the way from the molecular to the community level, across timescales ranging from virus-host encounter rates to evolutionary timescales. My current research focuses on the ecological and evolutionary consequences of this complicated relationship between temperate phages and their hosts. To do so, I use mathematical models that bridge scales - from cells to populations to communities. I am trying to answer the following questions:</p>

<ol>
  <li>How do temperate phages persist and evolve in periodically changing envrionments</li>
  <p style="padding-left: 2em"> Phages encounter periodically changing environments, including diurnal and seasonal changes as well as boom-bust dynamics in the form of blooms. These changes can lead to opposing selection pressures acting over different timescales. We used a nonlinear system of ordinary differential equation to simulate periodically-forced dynamics. We showed how conflicts can arise between strategies in the near-term that may favor lysis and strategies in the long-term that may favor lysogeny. In doing so, we identified a wide range of conditions in which temperate strategies can outperform obligately lytic or lysogenic strategies. Finally, we demonstrated that temperate strategies can mitigate against the potential local extinction of viruses in stochastically fluctuating environments, providing further evidence of the eco-evolutionary benefits of being temperate. </p>
  
  <li>How does multiplicty of infection affect the lysis-lysogeny decision</li>
  <li>How does lysogeny lead to the formation of coalitions between viruses and their hosts</li>
  </ol>



<!--- <p>The lysis-lysogeny decision is made at the level of individual host cells. It has been shown that the number of phages infecting a cell and host size affect the probability of lysogen formation (Zhang et al. 2021). I am interested in how this cell-level decision is regulated and how it affects the population dynamics of the virus-host system.</p> <p>At the population level, lysogen abundance is affected by host and resource availability. In polar marine environments, for example, lysogen abundance varies seasonally with higher and lower abundance in winters (low resource availability) and summers (high resource availability) respectively (Brum et al. 2016). To examine the drivers of viral strategies, I use non-linear ordinary differential equations to model the eco-evolutionary dynamics of temperate phages in fluctuating environments with phages of high and low resource availability.</p>
<p>Induction of lysogens - the process of a lysogen switching back to the lytic cycle - has two consequences: Its bad for the individual lysogen since lysis involves the death of that particular lysogen but, its good for the lysogen population in general because the newly released phage particles can go onto infect new host cells creating new lysogens. So, induction is harmful at the individual level but beneficial at the population level. I am interested in how these conflicting effects at different scales impact community ecology.</p> --->

Click on the headers below to know more about my earlier projects.

<details>
  <summary><b> Biomechanics of epithelial tissues in invertebrates </b></summary>

  <p>Mechanical forces play a fundamental role in shaping biological structure and function. They set limits to length and timescales for biological processes. In turn, the dynamical response of biochemical signalling pathways and genetic circuits to these mechanical forces create feedback loops that lead to interesting non-linear effects on the stress-strain relationship of biological materials. During my PhD, I studied consequences of these complex feedback loops at the population, organismal and tissue levels over timescales ranging from months to hours to minutes using <i>Hydra</i> and planarians as my model systems. Overall, my research showed how non-linear effects produced by the interplay of bio-chemical signalling, shape changes and mechanical stresses lead to a range of complex patterns and behaviors in biological systems.</p>

<p style = "padding-left:1em">
  <details>
    <summary><b> Mechanics of self-bisection in planarians </b></summary>
    <a href="https://doi.org/10.1088/1478-3975/ac2f29 ">
    <figure>
      <div style="text-align: center;">
        <img src="../images/PlanarianFission.png" alt="Schematic of planarian fission across three different species" style="width:50%;">
        <figcaption>Figure: (a) Schematics and (b) brightfield images of the fission process in <i>Dugesia japonica</i> (J-planarian), <i>Girardia tigrina</i> (G-planarian) and <i>Schmidtea mediterranea</i> (S-planarian).</figcaption>
      </div>
    </figure>
    </a>
    Flatworms (planarians) reproduce asexually by ripping their body into two (or more) pieces along their length. The pieces then regenerate into fully grown adults. The survival of the offspring pieces has been shown to depend on their size. There are several interesting questions one can ask about this bisection process:
    
  <ol>
  <li>How do animals generate sufficient force to rip themselves apart?</li>
  <li>What decides when an individual should reproduces?</li>
  <li>What decides where along the body the animal should split?</li>
  <li>What sets how many pieces the animal should split into? </li>
  </ol>
    <p> We used live imaging to compare and contrast the kinematics of self bisection in three different planarian species. We showed how they used body shape changes and substrate adhesion to generate the stresses necessary to overcome the ultimate tensile strength of the tissue. We also showed how mechanical constraints affect resource allocation to the offspring produced by this self bisection process and develop predictive models to relate the number and size of the offspring to the size of the parent.
      <br>
      <a href="https://doi.org/10.1088/1478-3975/ac2f29 ">Full article here.</a>
    </p>
  </details>
  
  <details>
    <summary><b> Body axis formation in <i>Hydra</i></b></summary>
      <a href="https://www.sciencedirect.com/science/article/pii/S000634951930668X">
      <figure>
        <div style="text-align: center;">
            <video width="960" height="540" controls autoplay>
                <source src="../images/HydraRegeneration.mp4" type="video/mp4">
                Your browser does not support the video tag.
            </video>
            <figcaption>Video: Regenerating <i>Hydra</i> tissue sphere</figcaption>
        </div>
      </figure>
      </a>
    <i>Hydra</i> can regenerate from tissue spheres formed from tissue pieces excised from the body column of an adult and, from aggregates of cells. These tissue spheres undergo osmotically driven shape oscillations which are characterized by a sawtooth like timecourse of the radius of the sphere over time. Initially the tissue spheres expand isotropically, characterized by high amplitude long period oscillations. But, over time, the tissue sphere becomes more elliposidal and is characterized by low amplitude short period oscillations. This change in shape and oscillation pattern involves symmetry breaking - at some point, the tissue sphere breaks spherical symmetry and a head-tail axis emerges. This symmetry breaking arises from coupling between the Wnt signalling pathway and mechanical properties of the epithelial tissue for the formation of a chemical gradient that defines the head and tail, as well as the formation of an ellipsoidal body from the initially spherical tissue. We used gain-of-function and loss-of-function experiments to show how a transition in the period and amplitude of osmotically driven shape oscillations in regenerating tissue spheres is caused by the formation of an actively regulated mouth structure. This finding challenges the current understanding of the temporal markers of stages during regeneration in <i>Hydra</i> and necessitates a re-examination of the mechanisms driving axis formation in <i>Hydra</i>.
    <br>
    <a href="https://www.sciencedirect.com/science/article/pii/S000634951930668X">Full article here.</a>
  </details>

  <details>
    <summary><b>Mechanical control of mouth opening in <i>Hydra</i></b></summary>

     <a href="https://royalsocietypublishing.org/doi/abs/10.1098/rspb.2023.2123 ">
        <figure>
          <div style="text-align: center;">
              <video width="960" height="540" controls autoplay>
                  <source src="../images/HydraMouthOpening.mp4" type="video/mp4">
                  Your browser does not support the video tag.
              </video>
              <figcaption>Video: Chemically induced mouth opening in <i>Hydra</i></figcaption>
          </div>
        </figure>
       </a>
  
    <i>Hydra</i> lacks a permanent mouth: its head epithelium is sealed. Upon neuronal activation, a mouth opens at the apex of the head which can exceed the body column diameter in seconds, allowing Hydra to ingest prey larger than itself. While the kinematics of mouth opening are well characterized, the underlying mechanism is unknown. Using a combination of experiments and mathematical modelling, we showed that while the mouth opening is triggered by neuronal signals, nearest neighbor mechanical coupling of cells is sufficient to coordinate it. We also showed that the non-linear elasticity of epithelial tissue makes mouth opening wider and faster, contrary to what one might expect. Using the mouth opening process as a model, we showed that in the absence of long-range chemical or neuronal signals, short-range mechanical coupling is sufficient to produce long-range order in tissue deformations.
    <br>
    <a href="https://royalsocietypublishing.org/doi/abs/10.1098/rspb.2023.2123">Full article here.</a>
    
  </details>
  </p>
</details>

<details>
   <summary><b>Linalool as an anesthetic for <i>Hydra</i></b></summary>
  During the various <i>Hydra</i> related projects I worked on, we constantly came up against trying to immobilize the animals for 'surgeries' and for imaging without significantly affecting the long-term health of the animals. While various anesthetics had been used in <i>Hydra</i> studies in the past, they tended to be toxic over the course of a few hours or their long-term effects on animal health are unknown. We found that the monoterpenoid alcohol linalool is a useful anesthetic for <i>Hydra</i>. Linalool is easy to use, non-toxic, fast acting, and reversible. It has no detectable long-term effects on cell viability or cell proliferation. We demonstrated that the same animal could be immobilized in linalool multiple times at intervals of several hours for repeated imaging over 2–3 days. This uniquely allows for <i>in vivo</i> imaging of dynamic processes such as head regeneration. We directly compared linalool to currently used anesthetics and show its superior performance. Linalool can be a useful tool for tissue manipulation and imaging in <i>Hydra</i> research in both research and teaching contexts.
  <br>
<a href="https://dx.plos.org/10.1371/journal.pone.0224221 ">Full article here.</a>
</details>
   
