# Keynote Speakers

## Dr. Nadine Schneider (Novartis)
### Real-world application of ML in drug discovery 

The digital revolution finally reached the pharmaceutical industry and machine-learning models are  becoming more and more relevant for drug discovery. Often people outside the domain underestimate the  complexity related to drug discovery. The hope that novel algorithms and models can remedy the challenge  of finding new drugs more efficiently is often shaken when data science experts dive more deeply in the  domain. Nevertheless, there are many areas in drug discovery where machine learning and data science  can make a difference. A very important point is trying to better understand the data before just applying 
new models. Especially in early drug discovery, many data sets are very small and tricky given the data  distribution, data bias, data shift or incompleteness. Another critical point are the users, to make machine learning models effective and actionable they need to be accessible and integrated into the daily work of  the scientists which are most of the time not data scientists themselves. With this, an important aspect is  also education of the users to deepen their knowledge and create the right expectations on machine learning models. In this presentation, several of these aspects will be discussed in more detail using  examples and learnings we made over the past years.


## Prof. Frank Noe (FU Berlin)
### The sampling problem in statistical mechanics and Boltzmann-Generating Flows

The rare-event sampling problem is one of the fundamental problems in statistical mechanics and particularly in molecular dynamics or Monte-Carlo simulations of molecules. Here I will introduce to Boltzmann-generating flows that combine invertible neural networks and statistical-mechanics based reweighting or resampling methods in order to train a machine-learning method to generate samples from the desired equilibrium distribution of the molecule or other many-body system. In particular, two recent developments will be described: equivariant flows that take symmetries in the molecular energy function into account, and Stochastic Normalizing Flows which combine deterministic invertible neural networks with stochastic sampling steps and are trained using path likelihood maximization techniques that have emerged in nonequilibrium statistical mechanics.


## Prof. Klaus Robert Müller & Dr. Kristof Schütt (TU Berlin, BIFOLD)
### Machine Learning meets Quantum Chemistry

Machine learning is emerging as a powerful tool in quantum chemistry and materials science, combining the accuracy of electronic structure methods with computational efficiency. Going beyond the simple prediction of chemical properties, machine learning potentials can be applied to perform fast molecular dynamics simulations, model solvent effects and response properties as well as find structures with desired properties by inverse design. In this talk, we will show how this opens a clear path towards unifying machine learning and quantum chemistry.


## Dr. Rocío Mercado (AstraZeneca)
### Applying Graph Neural Networks to Molecular Design
Deep learning methods applied to chemistry can be used to accelerate the discovery of new molecules, such as promising pharmaceuticals. Notably, methods such as graph neural networks (GNNs) are interesting tools to explore for molecular design because graphs are natural data structures for describing molecules. The process of designing novel, drug-like compounds can be viewed as one of generating graphs which optimize all the features of the desirable molecules. 

In this talk, I will provide an overview of how deep learning methods can be applied to complex drug design tasks, focusing on our recently published tool, GraphINVENT. GraphINVENT uses GNNs and a tiered deep neural network architecture to probabilistically generate new molecules a single bond at a time, and learns to build new molecules resembling a training set without any explicit programming of chemical rules. GraphINVENT is one of many recent platforms which aim to streamline the drug discovery process using AI.



## Dr. Pat Walters (Relay Therapeutics)
### Challenges and Opportunities for Machine Learning in Drug Discovery

Over the last few years, we have seen a dramatic uptick in the application of Machine Learning in drug discovery.  Developments in deep learning have led to a renaissance in Quantitative Structure-Activity Relationships (QSAR) and denovo molecule generation.  While the field continues to advance, it faces several challenges.  As with any application of machine learning, the results will depend on the data, the representation, and the algorithms used to generate the machine learning models. In many cases, drug discovery data presents some unique challenges not found in data from other disciplines. Furthermore, the optimal means of representing molecules in machine learning is still an open question.  This presentation will highlight current challenges and hopefully motivate new work to move the field forward. 


## Dr. Yannick Djoumbou Feunang (Corteva Agriscience)
### In Silico Prediction and Identification of Metabolites with BioTransformer 

Increased reliance on chemicals in both industrialized and developing countries has led to a dramatic change of our exposure patterns to both natural and synthetic chemicals. This diverse plethora of xenobiotics, some of which have become nearly ubiquitous, includes among others, pesticides, pharmaceuticals, food compounds, and their largely unknown chemo-/biotransformation products. To accurately assess the various environmental health threats they may pose, it is crucial to understand how they are biologically produced, activated, detoxified, and eliminated from various biological matrices. As it turns out, understanding the biological and environmental fate of xenobiotics is a major step towards deciphering the aforementioned mechanisms. Moreover, it contributes significantly to the development of safer and more sustainable chemicals. Over the past decade several in silico tools have been developed for the prediction and identification of metabolites, most of which are only commercially available and significantly biased towards drug-like molecules. In this presentation, we will describe BioTransformer, an open source software and freely accessible server for the prediction of human CYP450-catalyzed metabolism, human gut microbial degradation, human phase-II metabolism, human promiscuous metabolism, and environmental microbial degradation. Moreover, we will present an assessment of its performance in predicting the metabolism of agrochemicals, conducted at Corteva Agriscience. Furthermore, we will illustrate a few examples of its application as demonstrated by various published scientific studies. Finally, we will share future perspectives for this open source project, and describe how it could significantly benefit the exposure science and regulatory communities.

## Dr. Benjamin Sanchez-Lengeling (Google Research) 
### Evaluating Attribution of Molecules with Graph Neural Networks

The interpretability of machine learning models for molecules is critical to scientific discovery, understanding, and debugging. Attribution is one approach to interpretability, which highlights parts of the input that are influential to a neural network’s prediction. With molecules, we can set up synthetic tasks such as the identification of subfragment logics to generate ground truth attributions and labels. This scenario serves as a testbed to quantitatively study attributions of molecular graphs with Graph Neural Networks (GNNs). We perform multiple experiments looking at the effect of GNN architectures, label noise, and spurious correlations in attributions. In the end, we make concrete recommendations for which attribution methods and models to use while also providing a framework for evaluating new attribution techniques.


## Prof. Jennifer Listgarten (UC Berkeley)
### Machine learning-based design (of proteins, small molecules and beyond)

Data-driven design is making headway into a number of application areas, including protein, small-molecule, and materials engineering. The design goal is to construct an object with desired properties, such as a protein that binds to a target more tightly than previously observed. To that end, costly experimental measurements are being replaced with calls to a high-capacity regression model trained on labeled data, which can be leveraged in an in silico search for promising design candidates. The aim then is to discover designs that are better than the best design in the observed data. This goal puts machine-learning based design in a much more difficult spot than traditional applications of predictive modelling, since successful design requires, by definition, some degree of extrapolation---a pushing of the predictive models to its unknown limits, in parts of the design space that are a priori unknown. In this talk I'll discuss our emerging approaches to tackle this problem.
