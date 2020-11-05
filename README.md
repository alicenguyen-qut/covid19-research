# Research Project: Hierarchical visualization methods for a large scale network in a simulated COVID-19 transmission model 
Author: Huynh Ngoc Tram Nguyen
Supervisor: Dr. Dimitri Perrin
Science and Engineering Faculty
Queensland University of Technology

Models of the COVID-19 epidemic transmission via a social network could be useful to better understand the dynamic behavior of complex networks. Yet, numerical outputs alone may not be adequate to illustrate the simulation outputs in a way that public heath users could comprehend easily. Graph network visualizations play a crucial role in illustrating epidemiological data. Due to the complexity of graph structures and requirement of high computing resources, implementations of graph network visualizations are challenging and often absent from the majority of simulated disease transmission studies. Realizing this problem, this paper aims to present visualization methods for simulation outputs of a SEIR COVID-19 transmission model via a social network by means of line and graph drawing. The visualizations are implemented in a hierarchical way with different levels including population, individual, and community levels. To demonstrate the approach, I use Python language with Matplotlib, NetworkX library and Louvain algorithm to present graphical layouts, cluster network nodes into communities and visualize the data. It is found that while the visualization at a population level could provide information about the overall number of COVID-19 cases over time, visualizations at an individual level and community level give a clearer view on how the disease spreads via each individual/ community’s social network over time. With a high level of scalability and applicability, the findings of this research could be beneficial to other researchers who are implementing similar simulated disease transmission models. 

This project is to build visualization methods for simulation outputs of a SEIR COVID-19 transmission model by Dr. Dimitri Perrin's research team (2020).

The notebook file includes code to generate visualizations for:
 - COVID-19 tranmission at a population level
 - COVID-19 tranmission at an individual level
 - COVID-19 tranmission at a community level
 
 The repository contains:
 - A notebook file
 - An output folder
 - A data folder (containing input data).
 
 For any questions/inquiries about this research, contact me at huynhngoctram.nguyen@connect.qut.edu.au.  

