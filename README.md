# Introduction

Species distribution modeling (SDM), also known as climate envelope modeling or niche modeling, are numerical methods that combine observations of species occurrence or abundance with environmental estimates. It is used to gain ecological and evolutionary insights and to predict distributions across landscapes, and have become an important tools in the toolbox of ecologists and professionals involved in e.g, conservation planning and management, biodiversity monitoring and environmental impact assessment.

Maxent [^1] is one of the more popular algorithms for species distribution modeling. Unlike many other algorithms, it focuses specifically on presence-only data, which is typically the type of data available. Maxent is, among others, available as a stand-alone program [^2] and as R package [^3]. This tutorial focuses on the use of maxent addons for [GRASS GIS](https://grass.osgeo.org/learn/overview/). The objective is to introduce different modules in GRASS and to illustrate how they can be used to create an workflow for species distribution modeling in GRASS GIS. As example, we will use SDM to map the potential distribution of species using the example of the Almond-eyed Ringlet (*Erebia albergana*), a butterfly found in parts of Austria, Bulgaria, France, Italy, Serbia and Switzerland [^4]. 

[^1]: Phillips SJ, Anderson RP, Schapire RE (2006) Maximum entropy modeling of species geographic distributions. Ecological Modelling 190(3):231–259.
[^2]: Phillips SJ, Dudík M, Schapire R (2024) Maxent software for modeling species niches and distributions (version 3.4.4)
[^3]: Phillips S (2021) Maxnet: Fitting ’maxent’ species distribution models with ’glmnet’
[^4]: van Swaay C, Wynhoff I, Verovnik R, et al (2010) Erebia albergana. The IUCN Red List of Threatened Species 2010. IUCN Red List of Threatened Species.
[^5]: GRASS Development Team (2024) GRASS GIS
