In this **5-day course**, we will learn about the **economics of electricity markets** and how to use code to model them. The class is taught by [Mar Reguant](https://mreguant.github.io).

The goal of the course is threefold:
* Get familiar with trends and changes in the electricity market.
* Get familiar with how to use data and models of electricity markets. 
* Get familiar with how machine learning tools can help with the above.

<!-- \tableofcontents you can use \toc as well -->

## Preliminaries

We will be using Julia and Pluto.jl to run the exercises. For this, **you will need to install Julia in your computer, and add the Pluto package to Julia.** 

You can follow this amazing guide form MIT to get started into installing this in your computer: [How to install Julia and Pluto.jl](https://computationalthinking.mit.edu/Spring21/installation/)

> Credit goes to [Florian Oswald](https://floswald.github.io) for learning about these resources. Check his website for amazing computational tools with Julia.

:exclamation: It is **highly recommended** to make sure you can use Julia and Pluto before class starts.

:information_source: You can **test the installation** by checking this small workbook plotting installed wind capacity in a few select countries. Download the [exercise file](/materials/day0/day0.jl) and [data file](/materials/day0/cumulative-installed-wind-energy-capacity-gigawatts.csv) in the same folder, and open the exercise file from Pluto to get started.

## Further optional prep

We will be using **JuMP**, a **mathematical programming library for Julia**. You do not need to actively prep for this, but if you are eager to learn about it, you can find a great JuMP tutorial [here](https://github.com/jump-dev/JuMPTutorials.jl). 

## Flow
Each day, we will cover topics in the first half of the class, and then we will do examples in the second half. You will be able to modify the exercises at home for additional practice.

In each **day page** you will find the necessary material:
* [Day 1](menu1): Introduction
* [Day 2](menu2): Supply side I
* [Day 3](menu3): Supply side II
* [Day 4](menu4): Demand side I
* [Day 5](menu5): Demand side II

## Additional Julia resources

* Quantitative Economics with Julia (macro focus) [https://julia.quantecon.org](https://julia.quantecon.org)

* MIT Introduction to Computational Thinking (with Pluto live notebooks) [https://computationalthinking.mit.edu/Spring21/](https://computationalthinking.mit.edu/Spring21/)

* PowerSystems.jl and other libraries - Julia libraries to build electricity models, developed at NREL [https://www.nrel.gov/analysis/siip.html](https://www.nrel.gov/analysis/siip.html)

* A tutorial to learn JuMP (also referenced above) - [https://github.com/jump-dev/JuMPTutorials.jl](https://github.com/jump-dev/JuMPTutorials.jl)
