---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
header:
  overlay_image: marbled_6.jpg
---

{% include base_path %}


# Overview
<figure>
<p style="text-align: center;">
<figcaption>Gas flows in the CGM (simulation from Lochhaas et al. 2021, left and Peeples et al. 2015, right).</figcaption>
</p>
<p float="left">
  <img src="/images/cgm/cgm_flows.jpg" style="width:50%; border:1;">
  <img src="/images/cgm/cgm_ARAA_Nature15_peeples.jpg" style="width:45%; border:1;">
</p>
</figure>

Broadly speaking, I study how galaxies form and evolve using observational tools. Understanding the physical processes that form the galaxies and set their evolution has been one of the central problems in astronomy. With the advent of advancements in computer simulations combined with powerful telescopes, we have slowly started to uncover the hidden mysteries of our vast universe. Recent large scale cosmological simulations have revealed that the galaxies are surrounded by a diffuse gaseous halo, known as the [circumgalactic medium (CGM)](https://www.annualreviews.org/doi/10.1146/annurev-astro-091916-055240). The interplay between different gas flows (outflows and inflows also knows as the cosmic baryon cycle) in this invisible medium is the key to a clear and accurate picture of the fate of galaxies. In a broader sense, I want to understand the -
  * physical processes that govern the galaxy formation and evolution.
  * the complex nature of the gas flows in the CGM and how do they depend on and impact the galaxy - - properties and its environment.
  * methods and techniques required to analyse the large datasets coming from various telescopes.

## Cosmic Baryon Cycle
In simple terms, the ["cosmic baryon cycle"](https://arxiv.org/abs/2011.01935) is very similar to how evaporation and rain work on the earth. We all know that the sun heats the water on earth which evaporates and goes up where it condenses and forms clouds which in turn shower rain on earth. This process continues, and we call it the water cycle in hydrology. Similarly, the pristine gas (mostly hydrogen and helium) is accreted (also known as the inflow) by the galactic halo (CGM), where it forms gaseous clouds (a very complex physical mechanism) which falls on the galactic disk where it is turned into stars. Finally, these stars release a lot of energy via supernovae or stellar winds, which kick gas out of the galaxy into the halo (CGM) (known as the galactic outflows). This process also makes the CGM very multiphase, where gases with different temperatures and densities compete. Will the galaxy continue getting fuel and forming new stars, or will it stop forming stars, depending on the balance between these gas flows? However, predicting or fully understanding the fate of galaxy formation is very challenging!


## Multiphase Circumgalactic Medium in Observations
As described above, the CGM plays a pivotal role in galaxy formation but it is very challenging to study it observationally. The CGM is very diffuse (having low densities, $n\sim 10^{-3} \,cm^{-3}$, for comparison air density on earth is about $10^{19} \,cm^{-3}$) and the temperature can range from $\sim 10^4\, K$ to $10^7\, K$, therefore it is excidingly hard to observe in emission as emission flux is directly proprotinal to the gas density. However, with the advent of groundbreaking space and ground based telescopes it can be studied in absorption against a bright background object.

In my PhD thesis, I explored the nature of the complex gas flows in the galaxies' circumgalactic medium (see figure at the top) using absorption lines detected in the spectra of background [Quasars](https://en.wikipedia.org/wiki/Quasar). My goal was to constrain the physical properties of these gas flows with the absorption lines that trace different phases in the CGM. [The setup is the following:](/images/cgm/my_cgm_process.png) when the light emanating from a bright background source (e.g., quasar) passes through the CGM of a foreground galaxy, it can get absorbed and cause absorption dips in the spectrum at redshifts smaller than the quasar redshift.  
  
The different absorption lines can trace [different phases](/images/cgm//absorber_phase.jpg) and physical processes in the CGM and help us understand their connection to galaxy properties and its environment. For e.g., MgII (Mg$^{+}$) and FeII (Fe$^{+}$) are tracers of the cold phase ($T \sim 10^4\, K$) of CGM, while CIV (C$^{3+}$) traces the warm-hot ($T \sim 10^5\,K$) CGM. In my project, I have explored the nature and origin of MgII absorbers in the CGM of star-forming and passive galaxies by characterizing their spatial distribution. Understanding the connection between this gas and the galactic properties and its environment does provide more insights into the physical processes governing galaxy formation and evolution.

<!-- <figure>
  <img src="/images/Multiphase_Winds_Schematic.png">
  <figcaption> Schematic overview of Multiphase Galactic Winds from Fielding & Bryan (2021). A high res pdf can be found <u><a href="http://dfielding14.github.io/images/Multiphase_Winds_Schematic.pdf">here</a>.</u>. This graphic was made in collaboration with Lucy Reading-Ikkanda.</figcaption>
</figure> 


### Circumgalactic Medium 
Galaxies grow by accreting new gas. This gas must come from the massive reservoir of material that surrounds all galaxies--the CGM. The CGM is where many competing forces meet. Gas from outside a galaxies dark matter halo feeds the CGM from without either smoothly, in filaments, or in the form of smaller galaxies. Gas from inside the galaxy is violently ejected into the CGM in the form of winds. These flows interact with the gas already present in the CGM that would otherwise cool and fuel the galaxy and can lead to the CGM being a dynamic, turbulent environemnt. 

Although the CGM plays such an important role in galaxy formation it is exceedingly hard to study. Observationally, it is nearly impossible to detect the CGM because of its low densities and high temperatures. Ground breaking recent work has begun to map out the CGM of other galaxies one pencil beam at a time using absorption by cold CGM gas in the spectra of distant bright objects like galaxies and quasars. In the (near?) future new telescopes may enable the CGM to be directly measured in emission, which would teach us much more. Theoretically, the CGM is also hard to study because of the incredible range of scales involved. On the largest scales the CGM of a single galaxy roughly the size of the Milky Way can extend to Mega-parsec scales. However, the dynamics of the whole system can be set by the processes by which cold and hot gas mix and cool, which takes place on the scale of parsecs or less. This means that there at least six orders of magnitude in scale at play in the CGM! 

In line with the nature of the CGM my work on the CGM has focused on many scales. On the largest I study how the bulk properties of the CGM are determined by winds, and cosmological accretion, and how this regulates galaxy growth. On intermediate scales I study individual patches on the CGM and how turbulence, magnetic fields, and cooling set the temperature distribution and ionization state. On the smallest scales I study how individual cold clumps mix as they move through the hot ambient medium.

<figure>
  <img src="/images/CGM_feedback_MultiPanel_n_T_2rvir_ref_9Gyr.png">
  <figcaption>Slices of density and temperature at 4 times through the CGM of halos with different masses. This is from Fielding et al. (2017).</figcaption>
</figure>



### Galactic Winds and Feedback
When a star explodes as a supernova (SN) within the interstellar medium (ISM) of a galaxy it releases prodigious amounts of energy into its surroundings. On the scale of a whole galaxy the energy released by the collective explosions of many SNe is responsible for energizing the ISM and for driving galactic winds. The stirring and ejecting of ISM gas by SNe is believed to play the dominant role in determining the relative inefficiency with which galaxies up to the mass of our own Milky Way turn gas into stars. It is therefore essential for any theory of galaxy formation to explain how energy is deposited into the ISM in the form of heat and turbulent motions (and cosmic rays), and to explain how mass and energy are sent flying out of the galaxy. 

In order to isolate these crucial processes my collaborators (Eliot Quataert, Claude-Andre Faucher-Giguere, and Davide Martizzi) and I have simulated the collective effect of numerous SNe going off in patches of the ISM and in entire galaxies. We have found that by taking into account the natural clustering of SNe due to the clustered nature of star formation the efficiency of SN feedback is greatly enhanced. The winds that result from clustered SNe can be very strong, carrying nearly as much mass out as is turned into stars and carrying nearly all of the energy ejected out into the surrounding circumgalactic medium. The implications of the large energy flux into the inner CGM has not been fully explored yet but points to a picture in which galactic winds primarily impact galaxy evolution by preventing future accretion, as opposed to ejecting gas out of the galaxy that has already accreted (although both are certianly at play).

<figure>
  <img src="/images/Clustered_SNe_mixed_strip_4panel_Sig30_Mcl45_1pc_3_3_23Myr_zoom_panel.png">
  <figcaption>Slices of temperature, density, velocity, and cooling rate at 2 times through the ISM of a galaxy with a massive cluster of SNe in the process of going off and launching a wind. This is from Fielding et al. (2018).</figcaption>
</figure> -->

## New methods of galaxy spectral fitting redshift estimation
<!-- <figure>
  <img src="/images/ISM_Plasmoid.png">
  <figcaption>Volume rendering of the temperature and magnetic fields in a patch of the turbulent, thermally unstable ISM. The magnetic fields commonly exhibit clear helical patterns, which are signs of the plasmoid instability and the associated fast magnetic reconnection. This is from Fielding et al. (2022b).</figcaption>
</figure> -->


<!-- ### Protoplanetary Disks
The Kepler mission found many Jupiter mass planets with very short orbital periods (P<10 days). How these "hot Jupiters" migrated to such close-in orbits is debated. Observations of non-zero stellar obliquity---the angle between the host star's spin axis and the hot Jupiter's orbital axis---seemed to favor orbital angular momentum loss due to tidal dissipation from the star-planet interaction during close periastron passages induced by torques from a distant third body (Fabrycky and Tremain 2007). However, using hydrodynamic and magnetohydrodynamic simulations of protostar formation, I demonstrated that a wide range of stellar obliquities may be produced as a byproduct of forming a star within a turbulent environment. I developed a simple semi-analytic model that reveals this connection between the turbulent motions and the orientation of a star and its disk. Our results are consistent with the observed obliquity distribution of hot Jupiters implying that the misaligned hot Jupiters may have instead migration due to tidal dissipation in the disk (Goldreich and Tremaine 1980). We have also applied this same concept to explain the observed misalignment of protostellar binaries outflows (Offner et al. 2016).

<figure>
  <img src="/images/threepanel_misaligned_MHD_disk.png">
  <figcaption>Three views of the density of a protostellar disk that formed around a protostar in an MHD simulation. The line shows the direction of the star's angular momentum, which is misaligned from the disk's. This is from Fielding et al. (2015).</figcaption>
</figure> -->


