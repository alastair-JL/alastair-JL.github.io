---
title: "Research"
date: 2019-08-29
draft: false
---  
# Current Research

Currently, I am working with the [University of Oldenburg](https://uol.de/) and [UMCG in Groningen](https://www.umcg.nl/EN/corporate/paginas/default.aspx), studying the evolution and spread of antibiotic resistance.   


## Epidemic Spread Through 
With the recent global spread of COVID-19, there has been a dramatic upsurge in the need for epidemic forecasting, both in the year 2020, and in years and decades to come, when facing future global pandemics. One of the central questions of epidemic forecasting is the question of ``how long will an epidemic take to spread from A to B?'' - if we observe an epidemic in Stockholm, how long will it take to spread to Mumbia?
This question is tied deeply to the existence of the global flight network, and human behavior. In a [recent paper](/PastPapers/EpidemicArrival.pdf) I was able to calculate both the average epidemic arrival time, and uncertainty in this prediction.

![your_img](/Images/CurrentResearchCartoon.png#center)

## Horizontal Gene transfer and the Gossip Paradox
Unlike Eukaryotic cells (such as plants, animals and fungi), Bacterial cells contain two distinct types of DNA: Chromosomal DNA, which encodes the core genes required for a cell to survive, and Plasmid DNA, which codes accesory genes such as [antibiotic resistance](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2268074/), [virulence factors](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2786578/), or [novel biochemical pathways](https://academic.oup.com/nar/article/37/2/e16/2410275).

While Chromosomal DNA is locked tight within a cell, plasmid genes are frequently passed around between bacteria, in much the same way that humans might share books, advice, or other forms of knowledge. [Recently](https://arxiv.org/abs/2012.05071) I have been studying the evolutionary drivers behind this process, trying to puzzle out, when and why Bacteria expend such effort in sharing DNA with their competitors; cells they will inevitably need to compete with for generations to come.



# Past Research
![your_img](/Images/cuteMinCycleSmol.png#floatright)
## Pattern Formation In the Min System
Symmetry breaking and pattern formation are critical to the existence of complex life in the world around us, and have fascinated researchers for [many years](http://hopf.chem.brandeis.edu/members_content/yanglingfa/pattern/Turing/The%20Chemical%20Basis%20of%20Morphogenesis.pdf).

A particularly beautiful example of this is the Min system for cell division, in which the regulatory proteins MinD and MinE ensure cell division down the midline of the cell through a ``chase and release'' mechanism that inhibits cell division near either cell pole (depicted right).
[Recent experiments](https://www.pnas.org/content/early/2016/02/10/1600644113.abstract) by [Vecchiarelli](https://sites.lsa.umich.edu/vecchiarelli-lab/author/ave/) et al. using fluorescently marked Min Proteins were able to demonstrate a wide variety of novel spatial-temporal patterns depending on the exact concentrations used.

![your_img](/Images/BurstsAppearForWeb.png#center)

As part of my PhD thesis with [Eric Cytrnbaum](http://www.math.ubc.ca/~cytryn/index.shtml), I investigated possible mechanisms for ``Burst'' like pattern formation- using Large deviation theory to demonstrate how autocatalytic systems near a bifurcation point can quickly form circular bursts as seen in Vecchiarelli's experiments. 

![your_img](/Images/PDEBursts.png#center)


## Evolutionary Dynamics

Evolution is the driving force behind the creation of complexity in our world. Early models of evolutionary dynamics considered ``well mixed'' populations in which all individuals competed with all other individuals and geometry was ignored. Later models considered explicitly spatial populations - for example on a [network or a lattice](https://www.nature.com/articles/nature03204).

![your_img](/Images/Superstar.png#floatleft)
My Master's degree research with [Christoph Hauert](https://www.math.ubc.ca/~hauert/), sought to resolve a particularly thorny contradiction in the literature, in which one researcher had proved that a particular network structure, known as a superstar, [was able to ``amplify'' evolutionary pressure](https://www.nature.com/articles/nature03204) by an arbitrarily large amount, such that even the slightest advantage could would lead to evolutionary success - overwhelming the inherit randomness in the system. Another group of researchers, however, [provided a counterexample to this claim](https://royalsocietypublishing.org/doi/full/10.1098/rspa.2013.0193), demonstrating an analytic upper bound far below the lower bound given in the original paper, along with supporting simulation results.

During my thesis, [I was able to prove](https://www.sciencedirect.com/science/article/pii/S0022519315003082) that the superstar can provide arbitrarily strong evolutionary pressure in a suitable limit, however this approach to infinity is significantly slower than originally calculated, and thus in agreement with [the counterexample provided by Díaz et al](https://royalsocietypublishing.org/doi/full/10.1098/rspa.2013.0193).



## Collaborations outside of mathematics

Mathematics is fun, but I also do my best to find collaborations outside of mathematics whenever possible. Below are a couple of my collaborations, if you are currently working on an interesting project which could potentially use a little bit of mathematics, feel free to [get in touch](mailto:alastair.jamieson-lane@uni-oldenburg.de).


![your_img](/Images/AntMatrixB.png#floatright)
### CIB Analysis.
Cross impact Balance Analysis is an analysis technique from sociology in which we take a bunch of expert opinions on how aspects of a system effect one another (for example, how education effects economy, how economy effects politics), and combine these together in a systematic way in order to determine what possible states of the system can be considered `stable'. 

During my time at the [Complex Systems Summer School](https://www.santafe.edu/engage/learn/schools/sfi-complex-systems-summer-school)  in [Santa Fe](https://www.santafe.edu/) I was able to collaborate with [Dr. Vanessa Schweizer](https://uwaterloo.ca/knowledge-integration/faculty-schweizer) (along with many other excellent people) in extending this tool to consider stochastic effects.
You can read a blog post about that work [here](https://johncarlosbaez.wordpress.com/2014/02/24/markov-models-of-social-change-part-1/), with a follow up post by Vanessa [here](https://johncarlosbaez.wordpress.com/2014/03/05/markov-models-of-social-change-part-2/). I also constructed an [R package](https://github.com/alastair-JL/StochasticCIB) that can be used to implement this technique at home.
Like all things involved in the predicting people and societies, how far to trust such methods is a matter of debate.


![your_img](/Images/FreelistImage.png#floatleft)

### Consensus Analysis and Freelist Data.

Cultural Consensus analysis and Freelist Salience analysis are techniques from Anthropology used to combine responses from a large number of individuals in order to gain an understanding of the general opinions of the border society. While living in [Green College](https://greencollege.ubc.ca/), I had the chance collaborate with [Dr. Benjamin Purzycki](https://bgpurzycki.wordpress.com/) in building the [AnthroTools R Package](https://anthrotools.wordpress.com/about/), which can be found on GitHub [Here](https://github.com/alastair-JL/AnthroTools).
Our primary goal in constructing this package was to make CCA and Freelist methods freely available outside of proprietary software. While building this package, I was able to construct a number of data simulation tools, allowing users to predict how variable they might expect their data to be in a variety of situations.

