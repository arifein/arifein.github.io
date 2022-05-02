---
permalink: /projects/
title: "Projects"
excerpt: "Projects"
author_profile: true
---

## Modelling vegetation uptake of atmospheric mercury
The terrestrial biosphere is a major sink of atmospheric mercury, but global estimates of this sink vary widely (1000 to 4000 tons per year). We compiled available measurements of mercury vegetation uptake from the literature and compared them to simulations in the global chemistry-transport model GEOS-Chem, in order to assess the magnitude of the mercury vegetation sink ([Feinberg et al., 2022](https://doi.org/10.1039/D2EM00032F)). I am also interested in how climate change and deforestation will affect the biosphere-atmosphere exchange of mercury in the future.
<figure>
    <img src="/images/mercury_vegetation.png"
         alt="Gold mining sites within the Amazon rainforest">
    <figcaption>In the Amazon rainforest, atmospheric sources of mercury (artisanal and small-scale gold mining) overlap spatially with a strong vegetation sink. </figcaption>
</figure>



## Biogeochemical selenium and sulfur cycles
Selenium and sulfur are both essential nutrients for humans and animals, and sulfur is additionally required by plants. Atmospheric deposition of these elements to agricultural soils is important for replenishing nutrients lost during crop harvest. However, deposition of sulfur and selenium has been decreasing in Europe and North America over recent decades due to reduced anthropogenic emissions. We ran simulations in a chemistry-climate model (SOCOL-AER) studying recent and future trends in sulfur and selenium deposition under two socioeconomic scenarios ([Feinberg et al., 2021](https://doi.org/10.1038/s43247-021-00172-0)). Across the Northern Hemisphere, deposition to agricultural soils will decline by 70–90% for sulfur and 55–80% for selenium by the end of the 21<sup>st</sup> century. These deposition changes will shift the mass balance of sulfur and selenium in the surface environment, as already evidenced by declining streamwater loads of selenium in the Northeastern US. We have also linked declining atmospheric deposition in the Baltic Sea region to recent decreases in the selenium concentration of herring tissues ([Soerensen et al., 2022](https://doi.org/10.1039/d1em00418b)). Expanded monitoring and modelling of selenium and sulfur concentrations in the environment, food, and the human population is essential to assess the extent of nutritional risks.
<figure>
    <img src="/images/img_Se_dep.png"
         alt="Map showing future decline of selenium">
    <figcaption>Projected declines in selenium deposition between the recent period (2005–2009) and the future (2095–2099) under the SSP1-2.6 scenario. Pie charts show the source contributions to selenium deposition for each continent, with biogenic sources contributing a larger proportion of deposition in the future (<a href="https://doi.org/10.1038/s43247-021-00172-0">Feinberg et al., 2021</a>).</figcaption>
</figure>


## Statistical techniques to assess and constrain model uncertainties
Atmospheric chemistry models contain many uncertain parameters, yet due to their computational complexity it has been difficult to explore their full uncertainty space. We conducted a **global sensitivity analysis** on the atmospheric selenium model (SOCOL-AER), considering the impact of 34 parameters (reaction rates, emissions, aerosol partitioning) on deposition maps and the overall atmospheric lifetime of selenium ([Feinberg et al., ACP, 2020](https://doi.org/10.5194/acp-20-1363-2020)). The sensitivity analysis was facilitated by building a **statistical emulator** (surrogate model) in the form of **polynomial chaos expansions** to represent the output of the full SOCOL-AER model. Despite wide uncertainties in the atmospheric selenium reaction rate, we calculated that the mean atmospheric selenium lifetime is likely between 3 and 6 days, establishing that long range atmospheric transport (>1000 km) can occur. We also identified that uncertainties in selenium emissions are the main driver for uncertainties in deposition maps. This finding inspired our next study to constrain the emissions of selenium from different sources using **Bayesian inference** and a compiled database of atmospheric selenium observations from more than 600 measurement stations ([Feinberg et al., EST, 2020](https://doi.org/10.1021/acs.est.0c01408)). Our new observation-constrained estimate of global selenium emissions (29–36 Gg per year) is approximately double previous estimates in the literature. The SOCOL-AER model using optimized emission estimates shows very good agreement with both the training set of particulate selenium measurements (*R*<sup>2</sup> = 0.66) and independent validation sets of particulate selenium (*R*<sup>2</sup> = 0.59) and wet deposition (*R*<sup>2</sup> = 0.57) measurements. By applying a sensitivity and uncertainty analysis framework, we could improve the accuracy of the first atmospheric selenium model, produce global estimates of selenium deposition including uncertainties, and establish priorities for future research in environmental selenium cycling. 
<figure>
    <img src="/images/combined_stats.png"
         alt="Probability distribution of selenium lifetime and model-measurement comparison">
    <figcaption> Outputted probability distribution of the mean atmospheric selenium lifetime (<a href="https://doi.org/10.5194/acp-20-1363-2020">Feinberg et al., ACP, 2020</a>) (<i>left</i>). Comparison between simulated and measured atmospheric particulate selenium (<a href="https://doi.org/10.1021/acs.est.0c01408">Feinberg et al., EST, 2020</a>) (<i>right</i>).</figcaption>
</figure>

## Modelling tropospheric and stratospheric sulfate aerosols
My PhD work used the aerosol-chemistry-climate model SOCOL-AER, first developed by [Sheng et al. (2015)](https://doi.org/10.1002/2014JD021985). I contributed substantial developments to the sulfur cycle in SOCOL-AER, such as implementing interactive deposition schemes and improving the sulfur mass conservation ([Feinberg et al., 2019](https://doi.org/10.5194/gmd-12-3863-2019)). The new model version (SOCOL-AERv2) showed improved agreement with ground-based sulfur deposition networks and satellite measurements of sulfate aerosol properties. With its more accurate representation of deposition and sulfate aerosols, SOCOL-AERv2 will serve as the basis for future scientific studies on chemistry-climate modelling (e.g., [Karagodin-Doyennel et al., 2021](https://doi.org/10.5194/gmd-14-6623-2021)) and geoengineering (e.g., [Weisenstein et al., 2021](https://doi.org/10.5194/acp-2021-569)).
<figure>
    <img src="/images/sulfur_cycle.png"
         alt="Atmospheric sulfur budget">
    <figcaption>Atmospheric sulfur budget from SOCOL-AERv2 under non-volcanic background conditions for the year 2000 (fluxes in Gg per year and burdens in Gg). Red numbers show flux estimates from observations or other models (<a href="https://doi.org/10.5194/gmd-12-3863-2019">Feinberg et al., 2019</a>).</figcaption>
</figure>


## Methane isotopic source signatures
The isotopic ratio of the stable carbon isotopes (<sup>13</sup>C and <sup>12</sup>C) in methane has been used in many studies to track the emission sources of methane. However, published isotopic source signatures are based on limited data and may not be accurate. Furthermore, past modelling studies have mostly used global mean isotopic signatures, with little consideration of regional variability in the signatures. In my MSc thesis, we produced regionally varying maps of isotopic source signatures for use in global atmospheric model simulations ([Feinberg et al., 2018](https://doi.org/10.1016/j.atmosenv.2017.11.037)). Applying these source signature maps in a chemistry-climate model simulation (SOCOLv3) improved the agreement between the modelled and observed interhemispheric difference in the methane isotopic ratio. These mapped source signatures have been used as input data for subsequent methane modelling studies (e.g., [Zhang et al., 2021](https://doi.org/10.1093/nsr/nwab200)).
<figure>
    <img src="/images/methane_signature.png"
         alt="Map of livestock methane isotopic signature">
    <figcaption>Example map of methane isotopic source signature from livestock emissions (<a href="https://doi.org/10.1016/j.atmosenv.2017.11.037">Feinberg et al., 2018</a>).</figcaption>
</figure>
