+++
title = "Day 3"
hascode = true
date = Date(2021, 8, 9)
+++

# Day 3: Supply side II

In the third lecture, we will talk about environmental regulation and how it affects participants in the electricity market. 

In the practical session, we will continue to learn how to use JuMP to build electricity models. We will incorporate transmission lines and environmental regulation into a model with a richer set of plants. We will also practice ways in which to save and loop over several simulations.

## Lecture

* **Slides**: [day3.pdf](/materials/day3/day3.pdf)

## Practical exercise: Supply climate policies and leakage

The exercise will be based on the paper by [Fowlie, Petersen, and Reguant (2021)](/materials/day3/pandp.20211073.pdf). Reading the paper in advance is encouraged.

A repository of the conference paper can be found [here](https://www.openicpsr.org/openicpsr/project/131024/version/V1/view). The [online appendix](https://www.aeaweb.org/content/file?id=14554) is particularly helpful, given how short the paper is.

* **Exercise file**: [day3.jl](/materials/day3/day3.jl) / [day3_julia.pdf](/materials/day3/day3_julia.pdf)

* **Data file**: [data_leakage.zip](/materials/day3/data_leakage.zip)

<!-- ## Homework -->
> :exclamation: Save the exercise Julia file and the data zip file in the same folder. You need to unzip de data\_leakage folder. It should appear as a subfolder with the same name, "data\_leakage". It contains several .csv files. Then, open the exercise Julia file from Pluto to start exploring. 
Note that the .pdf file provides a snapshot of the exercise. It does not require any installation but it will not allow interactions.

## References and readings

* Bushnell, J., Chen, Y., & Zaragoza-Watkins, M. (2014). Downstream regulation of CO2 emissions in California’s electricity sector. Energy Policy, 64, 313–323. [https://doi.org/10.1016/j.enpol.2013.08.065](https://doi.org/10.1016/j.enpol.2013.08.065)

* Bushnell, J. B., Holland, S. P., Hughes, J. E., & Knittel, C. R. (2017). Strategic policy choice in state-level regulation: The EPA’s clean power plan. American Economic Journal: Economic Policy, 9(2), 57–90. [https://doi.org/10.1257/pol.20150237](https://doi.org/10.1257/pol.20150237)

* Davis, L., & Hausman, C. (2016). Market impacts of a nuclear power plant closure. American Economic Journal: Applied Economics, 8(2), 92–122. [https://doi.org/10.1257/app.20140473](https://doi.org/10.1257/app.20140473)

* Fabra, N., & Reguant, M. (2014). Pass-through of emissions costs in electricity markets. American Economic Review, 104(9). [https://doi.org/10.1257/aer.104.9.2872](https://doi.org/10.1257/aer.104.9.2872)

* Fowlie, M., & Reguant, M. (2018). Challenges in the Measurement of Leakage Risk. AEA Papers and Proceedings, 108, 124–129. [https://doi.org/10.1257/pandp.20181087](https://doi.org/10.1257/pandp.20181087)

* Kim, H. (2021). Heterogeneous Impacts of Cost Shocks, Strategic Bidding and Pass-Through: Evidence from the New England Electricity Market. American Economic Journal: Microeconomics, 1–42. [https://doi.org/10.1257/MIC.20190367](https://doi.org/10.1257/MIC.20190367)
