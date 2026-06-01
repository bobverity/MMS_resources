# MMS Useful Resources

This page lists a bunch of resources that I find useful across the following areas:

- Study design for MMS
- Data repositories of DR markers
- Spatial-temporal analysis methods

This is a very basic list, but I will try to update when I can.

## Study Design

### Software and web tools

- The web-based [pfhrp2/3 planner](https://shiny.dide.ic.ac.uk/DRpower-app/) is designed to help with both the *design and analysis phases* of pfhrp2/3 deletion studies. It is geared towards studies that follow the [WHO master protocol](https://www.who.int/publications/i/item/9789240099951) design. use this tool before running a study to work out a good design, and then again once you have your data to help interpret your results.
- The [DRpower](https://mrc-ide.github.io/DRpower/index.html) R package contains several functions to help with study design. This includes i) power and sample size for pfhrp2/3 studies (this is what drives the pfhrp2/3 planner tool above), ii) power to detect rare variants, iii) samples needed to achieve a given margin of error. It is particularly useful for multi-cluster prevalence studies, as most of the functions account for intra-cluster correlation.
- The web-based [OpenEpi](https://www.openepi.com/Menu/OE_Menu.htm) tool contains tabs for power and sample size calculation, including some more complex designs (e.g. trials).
- [Ausvet Epitools](https://epitools.ausvet.com.au/) is another online tool that can be used for power and sample size calculation, designed specifically for epidemiological studies.

### Training materials

- The [MMS Study Design Workshop](https://mrc-ide.github.io/MMS-SD_workshop/) was delivered in-person in 2024 and 2025, but also exists as a permanent online course. It is *specifically aimed at common MMS design questions*. It contains a series of lectures, each paired with an interactive learnR module including quizes and live code questions.
- The [Plasmo-Gen-Epi](https://www.plasmogenepi.org/) online course ["From Data to Insight"](https://www.plasmogenepi.org/OnlineCourse) is available in three languages, and gives excellent background on the objectives of MMS including high-level study design concepts.
- The book ["Power Analysis: An Introduction For the Life Sciences"](https://www.amazon.com/Power-Analysis-Nick-Colegrave/dp/0198846630) is a great introduction to power analysis. Not too thick and intimidating, it still gets into some more subtle ideas such as the "winner's curse" and other strange phenomena. I'd recommend this to anyone who wants to take their study design knowledge that little bit further.

## Data Repositories

These are some popular and public sources of data on molecular markers of antimalarial resistance:

- The [WWARN Artemisinin Molecular Surveyor](https://visualizer.iddo.org/map/k13) and the related [WWARN Partner Drug Molecular Surveyor](https://visualizer.iddo.org/map/act) are excellent resources for both browsing data via interactive maps and for downloading data.
- The [WHO Malaria Threats Map](https://tinyurl.com/3vxkmwup) is another great tool for browsing and downloading data on molecular markers of resistance, pfhrp2/3 deletion data, and more.
- The [MalariaGen Pf8](https://www.malariagen.net/data_package/open-dataset-plasmodium-falciparum-v80/) project contains data on more than 30,000 samples. As well as whole genome data, this contains a series of smaller files specifically focused on markers of resistance.

