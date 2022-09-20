# radiative_cooling_ML_dissertation
My 3rd Year Electrical and Electronic Engineering dissertation at University of Southampton. This is my first attempt at a proper **Python** project so in addition to my constant coding struggles throughout the year, I have to give a massive thank you to my supervisor and also to Professor Foley and his team who developed the WPTherml package. Check it out if you are also doing a similar radiative cooling project. 

Link to **WPTherml**: https://github.com/FoleyLab/wptherml

Link to **DEAP**: https://github.com/deap/deap

The most **concise** summary of this porject --- Combined Professor Foley's WPTherml package (which does all the Transfer Matrix calculations) with a **Genetic Algorithm** package for rapid prototyping by using DEAP (link is attached above).

N.B. This repo only contains the Python scripts (if you want to see all the dependencies, feel free to contact me). So, when you see error messages (e.g. in the 4 materials version, it is simply because I was testing an other version of the script.) 

The **full dissertation report** is attached as well: https://github.com/sanmoyo/radiative_cooling_ML_dissertation/blob/main/mms2n18_May2_Finalver_Full.pdf

**Dissertation Title:** Using Evolutionary Algorithm to optimise parameters of photonic radiator design

**Grade achieved:** 1st Class

**Problem:**
Radiative cooling technology has the potential to bring about significant impact on several industries, particularly in reducing energy consumption in buildings which makes up 40% of the total energy consumption of the world. Currently, large proportion of that energy is used for indoor thermal management via conventional HVAC systems. By utilising radiative cooling technology, a passive way of decreasing cooling energy requirements without additional power input could be realised. This technology involves a mechanism that passively obtains cooling energy by releasing heat of terrestrial-facing objects into the cold sink of outer space.
The development of photonic radiators and metamaterials has enabled significant technological advancements in innovative design and fabrication of radiators. The recent novel materials and structures of various radiators developed have created a new class of radiators – selective infrared radiators, which further highlights the advantages of diurnal radiative cooling.

**Goals:**
Despite recent advancement in design and fabrication of selective infrared radiators, challenges remain which require further research. These challenges include but are not limited to understanding what materials and what structure are best suited to incorporate into the multi-layered design of photonic radiators. Raman et al demonstrated a planar photonic radiator which comprises of seven alternating layers of hafnium dioxide and silica with varying thickness on top of 200 nm thick silver and 750µm thick silicon wafer substrate [1]. 
Currently, there is insufficient research on materials and structures which utilises machine learning techniques for advancing understanding of how to optimise parameters of photonic radiators. Hence, the primary goal of this project is to explore the potential of using evolutionary algorithms to enhance understanding of how to optimise the thickness and materials used in radiator design.

**Scope:**
Firstly, calculating a thin-film spectrum is an important starting point. This can be achieved by using the transfer matrix which is a connection between refractive index and absorptivity. After understanding the transfer matrix and the related mathematical formulas, different ideal spectrum for various conditions should be considered.
Furthermore, after performing a literature review, a pool of materials and several design structures of photonic radiators should be chosen for integrating these two types of parameters into the genetic algorithm.
Lastly, in terms of the genetic algorithm, the creation of several fitness functions and consideration of hyper-parameters are needed. These parameters include but are not limited to the number of generations, the size of the population, cross-over and mutation probabilities.


[1] Raman AP, Anoma MA, Zhu L, Rephaeli E, Fan S. Passive radiative cooling below ambient air temperature under direct sunlight. Nature 2014;515:540–4


