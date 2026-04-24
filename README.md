# Awesome Mathematical Neuroscience [![Awesome](https://awesome.re/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of resources at the intersection of mathematics, theoretical neuroscience, computational neuroscience, neural coding, network neuroscience, and multiscale brain modeling.

> Mathematical neuroscience uses dynamical systems, statistics, information theory, topology, graph theory, geometry, optimization, machine learning, and numerical simulation to understand nervous systems across scales.

## Contents

- [General Mathematical/Computational Neuroscience](#general-mathematicalcomputational-neuroscience)
- [Topics in Neuronal Modeling](#topics-in-neuronal-modeling)
- [Topics in Neural Coding](#topics-in-neural-coding)
- [Topics in Network Neuroscience](#topics-in-network-neuroscience)
- [Topics in Neural Information and Cognition](#topics-in-neural-information-and-cognition)
- [Topics in Multiscale Brain Modeling](#topics-in-multiscale-brain-modeling)
- [Topological, Geometric, and Algebraic Neuroscience](#topological-geometric-and-algebraic-neuroscience)
- [Statistical Neuroscience and Neural Data Analysis](#statistical-neuroscience-and-neural-data-analysis)
- [Machine Learning, NeuroAI, and Brain-Inspired Computing](#machine-learning-neuroai-and-brain-inspired-computing)
- [Software, Simulators, and Modeling Frameworks](#software-simulators-and-modeling-frameworks)
- [Data Standards, Model Repositories, and Datasets](#data-standards-model-repositories-and-datasets)
- [Journals, Conferences, Schools, and Communities](#journals-conferences-schools-and-communities)
- [Adjacent Mathematics](#adjacent-mathematics)
- [Contributing](#contributing)

---

## General Mathematical/Computational Neuroscience

### Books

- [Theoretical Neuroscience: Computational and Mathematical Modeling of Neural Systems](https://www.gatsby.ucl.ac.uk/~dayan/book/) - Peter Dayan and L. F. Abbott (MIT Press, 2001). Classic text on neural encoding, decoding, information theory, plasticity, and network models.
- [Mathematical Foundations of Neuroscience](https://link.springer.com/book/10.1007/978-0-387-87708-2) - G. Bard Ermentrout and David H. Terman (Springer, 2010). Dynamical-systems approach to neurons, synapses, rhythms, and networks.
- [Neuronal Dynamics: From Single Neurons to Networks and Models of Cognition](https://neuronaldynamics.epfl.ch/) - Wulfram Gerstner, Werner M. Kistler, Richard Naud, and Liam Paninski (Cambridge University Press, 2014). Online book with Python exercises.
- [Computational Neuroscience: A First Course](https://link.springer.com/book/10.1007/978-3-319-00861-5) - Hanspeter A. Mallot (Springer, 2013). Introductory mathematical and computational neuroscience.
- [Fundamentals of Computational Neuroscience](https://global.oup.com/academic/product/fundamentals-of-computational-neuroscience-9780199235070) - Thomas P. Trappenberg (Oxford University Press, 2010). Broad introduction to modeling neural systems.
- [Principles of Computational Modelling in Neuroscience](https://www.cambridge.org/highereducation/books/principles-of-computational-modelling-in-neuroscience/4D0C263EF0D0B6989453FD8AE6F2338F) - David Sterratt, Bruce Graham, Andrew Gillies, and David Willshaw (Cambridge University Press, 2011). Practical modeling and simulation.
- [Computational Neuroscience: A Comprehensive Approach](https://www.routledge.com/Computational-Neuroscience-A-Comprehensive-Approach/Feng/p/book/9781584883625) - Jianfeng Feng, editor (CRC Press, 2003). Collection of mathematical and computational methods.
- [An Introductory Course in Computational Neuroscience](https://mitpress.mit.edu/9780262305402/an-introductory-course-in-computational-neuroscience/) - Paul Miller (MIT Press, 2018). Accessible course-style introduction.
- [Dynamical Systems in Neuroscience: The Geometry of Excitability and Bursting](https://direct.mit.edu/books/book/2107/Dynamical-Systems-in-Neuroscience) - Eugene M. Izhikevich (MIT Press, 2007). Geometric theory of neuronal excitability.
- [Spikes: Exploring the Neural Code](https://mitpress.mit.edu/9780262681087/spikes/) - Fred Rieke, David Warland, Rob de Ruyter van Steveninck, and William Bialek (MIT Press, 1999). Foundational text on neural coding and information theory.

### Courses and Lecture Notes

- [Neuromatch Academy: Computational Neuroscience](https://compneuro.neuromatch.io/) - Open computational neuroscience course with tutorials, lectures, and Python notebooks.
- [MIT OCW 9.40: Introduction to Neural Computation](https://ocw.mit.edu/courses/9-40-introduction-to-neural-computation-spring-2018/) - Quantitative neural computation course with notes, videos, assignments, and exams.
- [EPFL Neuronal Dynamics Teaching Material](https://neuronaldynamics.epfl.ch/online/index.html) - Companion online book and exercises for Gerstner et al.
- [Methods in Computational Neuroscience Course](https://www.mbl.edu/education/advanced-research-training-courses/course-offerings/methods-computational-neuroscience) - Intensive summer school at the Marine Biological Laboratory.
- [INCF TrainingSpace](https://training.incf.org/) - Training resources for computational neuroscience, neuroinformatics, data standards, and reproducible workflows.
- [Allen Institute Tutorials and Documentation](https://brain-map.org/support) - Tutorials, documentation, and community support for Allen Brain Map data and tools.

### Reviews and Overviews

- [Computational neuroscience: a frontier of the 21st century](https://doi.org/10.1038/nn.3838) - Sejnowski, Churchland, and Movshon (Nature Neuroscience, 2014). Perspective on large-scale neuroscience data and modeling.
- [The unreasonable effectiveness of mathematics in the brain sciences](https://doi.org/10.1016/j.neuron.2015.12.001) - Abbott (Neuron, 2015). Commentary on mathematical abstraction in neuroscience.
- [Neuroscience needs behavior: correcting a reductionist bias](https://doi.org/10.1016/j.neuron.2016.05.041) - Krakauer et al. (Neuron, 2017). Important counterbalance for modelers.

---

## Topics in Neuronal Modeling

### Books

- [Spiking Neuron Models: Single Neurons, Populations, Plasticity](https://www.cambridge.org/core/books/spiking-neuron-models/76A3FC77EC2D24CDD91E29EBB23ADB0B) - Wulfram Gerstner and Werner M. Kistler (Cambridge University Press, 2002).
- [Biophysics of Computation: Information Processing in Single Neurons](https://global.oup.com/academic/product/biophysics-of-computation-9780195181999) - Christof Koch (Oxford University Press, 1999).
- [The Book of GENESIS: Exploring Realistic Neural Models with the GEneral NEural SImulation System](https://link.springer.com/book/10.1007/978-1-4612-1634-6) - James M. Bower and David Beeman (Springer, 1998).
- [Theoretical Neuroscience](https://www.gatsby.ucl.ac.uk/~dayan/book/) - Dayan and Abbott. Especially useful for integrate-and-fire neurons, population coding, and plasticity.
- [Mathematical Foundations of Neuroscience](https://link.springer.com/book/10.1007/978-0-387-87708-2) - Ermentrout and Terman. Especially useful for Hodgkin-Huxley, bifurcations, bursting, phase reduction, and neural fields.

### Foundational Articles

- [A quantitative description of membrane current and its application to conduction and excitation in nerve](https://doi.org/10.1113/jphysiol.1952.sp004764) - Hodgkin and Huxley (Journal of Physiology, 1952). Conductance-based model of the action potential.
- [Impulses and physiological states in theoretical models of nerve membrane](https://doi.org/10.1016/S0079-6107(09)62002-6) - FitzHugh (Biophysical Journal / related early excitable-system work, 1961). Reduced excitability model.
- [Voltage oscillations in the barnacle giant muscle fiber](https://doi.org/10.1016/S0006-3495(81)84782-0) - Morris and Lecar (Biophysical Journal, 1981). Two-dimensional conductance model.
- [Simple model of spiking neurons](https://doi.org/10.1109/TNN.2003.820440) - Izhikevich (IEEE Transactions on Neural Networks, 2003). Efficient spiking neuron model.
- [Reducing conductance-based neuron models](https://doi.org/10.1016/S0166-2236(97)01127-7) - Rinzel and Ermentrout-style reduction literature. Useful background for phase planes, phase reduction, and reduced neuronal models.

### Network and Population Models

- [Excitatory and inhibitory interactions in localized populations of model neurons](https://doi.org/10.1016/S0006-3495(72)86068-5) - Wilson and Cowan (Biophysical Journal, 1972). Mean-field population dynamics.
- [Neural theory of association and concept-formation](https://doi.org/10.1007/BF00337259) - Amari (Biological Cybernetics, 1977). Neural fields and pattern formation.
- [Neural networks and physical systems with emergent collective computational abilities](https://doi.org/10.1073/pnas.79.8.2554) - Hopfield (PNAS, 1982). Energy-based associative memory.
- [Dynamics of sparsely connected networks of excitatory and inhibitory spiking neurons](https://doi.org/10.1023/A:1008925309027) - Brunel (Journal of Computational Neuroscience, 2000). Balanced random networks.
- [Adaptive exponential integrate-and-fire model as an effective description of neuronal activity](https://doi.org/10.1152/jn.00686.2005) - Brette and Gerstner (Journal of Neurophysiology, 2005). AdEx model.
- [Dynamical systems and computational neuroscience](https://doi.org/10.1016/j.conb.2017.01.008) - Breakspear (Current Opinion in Neurobiology, 2017). Modern overview of dynamical systems in brain modeling.

### Plasticity and Learning Rules

- [Hebb's Organization of Behavior](https://psycnet.apa.org/record/2002-01778-000) - Donald Hebb (1949). Foundational cell-assembly theory.
- [A model of long-term potentiation](https://doi.org/10.1038/37031) - Bi and Poo (Nature, 1998). Spike-timing-dependent plasticity in experiments.
- [A model of spike-timing dependent plasticity](https://doi.org/10.1038/35062570) - Song, Miller, and Abbott (Nature Neuroscience, 2000). STDP and competition.
- [Theory for the development of neuron selectivity: orientation specificity and binocular interaction in visual cortex](https://www.jneurosci.org/content/2/1/32) - Bienenstock, Cooper, and Munro (Journal of Neuroscience, 1982). BCM theory of synaptic modification.
- [Synaptic plasticity: taming the beast](https://doi.org/10.1038/nn.2321) - Abbott and Nelson (Nature Neuroscience, 2000). Review of stability, homeostasis, and plasticity.

---

## Topics in Neural Coding

### Books

- [Spikes: Exploring the Neural Code](https://mitpress.mit.edu/9780262681087/spikes/) - Rieke, Warland, de Ruyter van Steveninck, and Bialek (MIT Press, 1999).
- [Information Theory, Inference, and Learning Algorithms](https://www.inference.org.uk/itila/book.html) - David J. C. MacKay (Cambridge University Press, 2003). Free online book; useful for entropy, coding, inference, and learning.
- [Elements of Information Theory](https://onlinelibrary.wiley.com/doi/book/10.1002/047174882X) - Thomas M. Cover and Joy A. Thomas (Wiley, 2006). Standard mathematical reference.
- [Probabilistic Models of the Brain](https://mitpress.mit.edu/9780262632683/probabilistic-models-of-the-brain/) - Rajesh P. N. Rao, Bruno A. Olshausen, and Michael S. Lewicki, editors (MIT Press, 2002).

### Articles and Reviews

- [What does the eye tell the brain?](https://doi.org/10.1073/pnas.89.19.9220) - Bialek, Rieke, de Ruyter van Steveninck, and Warland (PNAS, 1992). Efficient coding and retinal information.
- [Information theory and neural coding](https://doi.org/10.1038/14731) - Borst and Theunissen (Nature Neuroscience, 1999). Classic review.
- [Extracting information from neuronal populations: information theory and decoding approaches](https://doi.org/10.1038/nrn2578) - Quiroga and Panzeri (Nature Reviews Neuroscience, 2009). Review of decoding and information-theoretic analysis.
- [Cracking the neural code for sensory perception by combining statistics, intervention, and behavior](https://doi.org/10.1016/j.neuron.2016.11.036) - Panzeri et al. (Neuron, 2017). Review of coding, causality, and behavior.
- [Weak pairwise correlations imply strongly correlated network states in a neural population](https://doi.org/10.1038/nature04701) - Schneidman et al. (Nature, 2006). Maximum entropy models for neural populations.
- [Spatio-temporal correlations and visual signalling in a complete neuronal population](https://doi.org/10.1038/nature07140) - Pillow et al. (Nature, 2008). GLMs and population coding.
- [The structure of neural population codes](https://doi.org/10.7554/eLife.06134) - Stringer et al. (eLife, 2019). High-dimensional structure of population activity.

### Combinatorial and Algebraic Neural Codes

- [What can topology tell us about the neural code?](https://arxiv.org/abs/1605.01963) - Curto (Bulletin of the AMS, 2017). Survey of topology and combinatorial neural codes.
- [The neural ring: an algebraic tool for analyzing the intrinsic structure of neural codes](https://doi.org/10.1007/s11538-013-9823-4) - Curto, Itskov, Veliz-Cuba, and Youngs (Bulletin of Mathematical Biology, 2013).
- [Analysis of combinatorial neural codes: an algebraic approach](https://doi.org/10.1016/B978-0-12-804191-8.00007-6) - Curto et al. Chapter-style introduction to algebraic analysis of neural codes.
- [Combinatorial neural codes from a mathematical coding theory perspective](https://digitalcommons.unl.edu/mathfacpub/61/) - Curto et al. Coding-theoretic perspective.
- [Morphisms of neural codes](https://doi.org/10.1137/18M1205509) - Jeffs (SIAM Journal on Applied Algebra and Geometry, 2019). Category-theoretic structure of neural codes.
- [Oriented matroids and combinatorial neural codes](https://arxiv.org/abs/2002.03542) - Kunin, Lienkaemper, and Rosen. Connections between convex codes and oriented matroids.
- [Convex neural codes](https://doi.org/10.1137/15M1038072) - Curto et al. Convexity and receptive-field realization problems.

---

## Topics in Network Neuroscience

### Books

- [Networks of the Brain](https://mitpress.mit.edu/9780262528986/networks-of-the-brain/) - Olaf Sporns (MIT Press, 2010). Foundational book on brain networks.
- [Discovering the Human Connectome](https://direct.mit.edu/books/monograph/2168/Discovering-the-Human-Connectome) - Olaf Sporns (MIT Press, 2012). Connectomics overview.
- [Network Neuroscience](https://www.elsevier.com/books/network-neuroscience/frohlich/978-0-12-801560-5) - Flavio Fröhlich, editor (Academic Press, 2016). Multiauthor treatment of brain networks.
- [Methods in Brain Connectivity Inference through Multivariate Time Series Analysis](https://www.routledge.com/Methods-in-Brain-Connectivity-Inference-through-Multivariate-Time-Series-Analysis/Sameshima-Baccala/p/book/9781439845721) - Koichi Sameshima and Luiz A. Baccalá (CRC Press, 2014).
- [Fundamentals of Brain Network Analysis](https://www.elsevier.com/books/fundamentals-of-brain-network-analysis/fornito/978-0-12-407908-3) - Alex Fornito, Andrew Zalesky, and Edward Bullmore (Academic Press, 2016).

### Articles and Reviews

- [Brain connectivity](http://www.scholarpedia.org/article/Brain_connectivity) - Olaf Sporns (Scholarpedia). Introductory reference.
- [Complex brain networks: graph theoretical analysis of structural and functional systems](https://doi.org/10.1038/nrn2575) - Bullmore and Sporns (Nature Reviews Neuroscience, 2009). Foundational review.
- [Network neuroscience](https://doi.org/10.1038/nn.4502) - Bassett and Sporns (Nature Neuroscience, 2017). Field-defining review.
- [Complex network measures of brain connectivity: uses and interpretations](https://doi.org/10.1016/j.neuroimage.2009.10.003) - Rubinov and Sporns (NeuroImage, 2010). Measures for brain graphs.
- [Graph theory methods: applications in brain networks](https://doi.org/10.31887/DCNS.2018.20.2/osporns) - Sporns (Dialogues in Clinical Neuroscience, 2018). Methods overview.
- [A positive-negative mode of population covariation links brain connectivity, demographics and behavior](https://doi.org/10.1038/nn.4125) - Smith et al. (Nature Neuroscience, 2015). Large-scale connectome-behavior modes.
- [Controllability of structural brain networks](https://doi.org/10.1038/ncomms9414) - Gu et al. (Nature Communications, 2015). Network control theory in neuroscience.
- [The network architecture of the human brain is modular and hierarchical](https://doi.org/10.3389/fnhum.2011.00200) - Meunier, Lambiotte, and Bullmore (Frontiers in Human Neuroscience, 2010/2011). Community structure and hierarchy.
- [Partial directed coherence: a new concept in neural structure determination](https://pubmed.ncbi.nlm.nih.gov/11417058/) - Baccalá and Sameshima (Biological Cybernetics, 2001). Directional connectivity from time series.
- [The expanding horizons of network neuroscience: from description to prediction and control](https://doi.org/10.1016/j.neuroimage.2022.119019) - Srivastava et al. (NeuroImage, 2022). Modern overview.

### Tools

- [Brain Connectivity Toolbox](https://sites.google.com/site/bctnet/) - MATLAB/Python toolbox for complex-network measures in brain networks.
- [bctpy](https://github.com/aestrivex/bctpy) - Python port of the Brain Connectivity Toolbox.
- [NetworkX](https://networkx.org/) - General-purpose Python package for graph analysis.
- [graph-tool](https://graph-tool.skewed.de/) - Efficient Python module for statistical analysis of graphs.
- [Nilearn](https://nilearn.github.io/) - Python tools for statistical learning with neuroimaging data.
- [MNE-Python](https://mne.tools/stable/index.html) - MEG/EEG analysis, source localization, and connectivity workflows.
- [The Virtual Brain](https://www.thevirtualbrain.org/) - Whole-brain network simulation platform.

---

## Topics in Neural Information and Cognition

### Books

- [Bayesian Brain: Probabilistic Approaches to Neural Coding](https://mitpress.mit.edu/9780262042383/bayesian-brain/) - Kenji Doya, Shin Ishii, Alexandre Pouget, and Rajesh P. N. Rao, editors (MIT Press, 2007).
- [The Probabilistic Mind](https://global.oup.com/academic/product/the-probabilistic-mind-9780199216093) - Nick Chater and Mike Oaksford, editors (Oxford University Press, 2008).
- [Reinforcement Learning: An Introduction](http://incompleteideas.net/book/the-book-2nd.html) - Richard S. Sutton and Andrew G. Barto (MIT Press, 2018). Free online book.
- [Neural Engineering: Computation, Representation, and Dynamics in Neurobiological Systems](https://mitpress.mit.edu/9780262550604/neural-engineering/) - Chris Eliasmith and Charles H. Anderson (MIT Press, 2003). Representation and dynamics in neural systems.
- [How to Build a Brain](https://global.oup.com/academic/product/how-to-build-a-brain-9780199794546) - Chris Eliasmith (Oxford University Press, 2013). Large-scale cognitive neural modeling.
- [Surfing Uncertainty](https://global.oup.com/academic/product/surfing-uncertainty-9780190217013) - Andy Clark (Oxford University Press, 2016). Predictive processing and cognition.
- [Active Inference](https://mitpress.mit.edu/9780262045353/active-inference/) - Thomas Parr, Giovanni Pezzulo, and Karl J. Friston (MIT Press, 2022). Free-energy and active inference tutorial.

### Articles and Reviews

- [The Bayesian brain: the role of uncertainty in neural coding and computation](https://doi.org/10.1016/j.tins.2004.10.007) - Knill and Pouget (Trends in Neurosciences, 2004). Bayesian coding review.
- [Predictive coding in the visual cortex: a functional interpretation of some extra-classical receptive-field effects](https://doi.org/10.1038/4580) - Rao and Ballard (Nature Neuroscience, 1999). Predictive coding model.
- [A theory of cortical responses](https://doi.org/10.1098/rstb.2005.1622) - Friston (Philosophical Transactions B, 2005). Predictive coding/free-energy framework.
- [The free-energy principle: a unified brain theory?](https://doi.org/10.1038/nrn2787) - Friston (Nature Reviews Neuroscience, 2010). Influential synthesis.
- [Probabilistic brains: knowns and unknowns](https://doi.org/10.1038/nn.3495) - Pouget, Beck, Ma, and Latham (Nature Neuroscience, 2013). Probabilistic population codes.
- [The neural basis of the Weber–Fechner law](https://doi.org/10.1073/pnas.0908784106) - Dehaene (PNAS, 2009). Example of mathematical psychophysics and neural coding.
- [A distributional code for value in dopamine-based reinforcement learning](https://doi.org/10.1038/s41586-019-1924-6) - Dabney et al. (Nature, 2020). Distributional reinforcement learning in dopamine systems.
- [A neuronal model of a global workspace in effortful cognitive tasks](https://doi.org/10.1073/pnas.98.24.13763) - Dehaene, Kerszberg, and Changeux (PNAS, 2001). Mathematical model of global workspace dynamics.
- [Cognitive map representations in the hippocampus](https://doi.org/10.1146/annurev-neuro-062111-150314) - Moser, Kropff, and Moser (Annual Review of Neuroscience, 2008). Spatial coding and cognitive maps.

### Topics

- Bayesian inference and probabilistic population codes.
- Predictive coding and active inference.
- Reinforcement learning and dopamine.
- Decision theory, drift-diffusion models, and sequential sampling.
- Attractor networks, working memory, and cognitive maps.
- Efficient coding, sparse coding, and normative theories.
- Conscious access, global workspace, and integrated information theory.

---

## Topics in Multiscale Brain Modeling

### Books and Edited Volumes

- [Computational Neuroscience: Realistic Modeling for Experimentalists](https://www.routledge.com/Computational-Neuroscience-Realistic-Modeling-for-Experimentalists/De-Schutter/p/book/9780849310684) - Erik De Schutter, editor (CRC Press, 2001). Practical realistic modeling.
- [From Molecules to Networks: An Introduction to Cellular and Molecular Neuroscience](https://www.sciencedirect.com/book/9780123971791/from-molecules-to-networks) - John H. Byrne and Ruth Heidelberger, editors. Useful biological grounding for multiscale modelers.
- [Computational Modeling Methods for Neuroscientists](https://mitpress.mit.edu/9780262514200/computational-modeling-methods-for-neuroscientists/) - Erik De Schutter, editor (MIT Press, 2010). Methods for model construction and simulation.

### Articles and Reviews

- [Reconstruction and simulation of neocortical microcircuitry](https://doi.org/10.1016/j.cell.2015.09.029) - Markram et al. (Cell, 2015). Detailed microcircuit reconstruction and simulation.
- [Systematic integration of structural and functional data into multi-scale models of mouse primary visual cortex](https://doi.org/10.1016/j.neuron.2020.01.040) - Billeh et al. (Neuron, 2020). Data-driven multiscale cortical model.
- [The Virtual Brain: a simulator of primate brain network dynamics](https://doi.org/10.3389/fninf.2013.00010) - Sanz Leon et al. (Frontiers in Neuroinformatics, 2013). Whole-brain simulation platform paper.
- [The scientific case for brain simulations](https://doi.org/10.1016/j.neuron.2019.03.027) - Einevoll et al. (Neuron, 2019). Review and position paper on brain simulation.
- [Toward a multiscale modeling framework for understanding serotonergic function](https://doi.org/10.1177/0269881117699612) - Wong-Lin et al. (Journal of Psychopharmacology, 2017). Example multiscale neuromodulatory modeling.
- [A large-scale model of the functioning brain](https://doi.org/10.1126/science.1225266) - Eliasmith et al. (Science, 2012). SPAUN cognitive model.

### Platforms and Frameworks

- [The Virtual Brain](https://www.thevirtualbrain.org/) - Open-source platform for simulating large-scale brain network dynamics from connectomes.
- [EBRAINS](https://ebrains.eu/) - European digital research infrastructure for brain atlases, data, modeling, simulation, and computing.
- [Blue Brain Project](https://www.epfl.ch/research/domains/bluebrain/) - EPFL project focused on digital reconstruction and simulation of brain tissue.
- [Human Brain Project](https://www.humanbrainproject.eu/) - Large European brain research initiative; many tools continue through EBRAINS.
- [NetPyNE](http://netpyne.org/) - Python package for developing, simulating, and analyzing multiscale biological neuronal networks using NEURON.
- [Open Source Brain](https://www.opensourcebrain.org/) - Collaborative platform for sharing and running computational neuroscience models.
- [NeuroML](https://neuroml.org/) - Standard and software ecosystem for describing detailed neural models.
- [Arbor](https://arbor-sim.org/) - High-performance library for multicompartment neuronal network simulations.
- [CoreNEURON](https://github.com/neuronsimulator/nrn/tree/master/src/coreneuron) - Optimized compute engine for large-scale NEURON simulations.

---

## Topological, Geometric, and Algebraic Neuroscience

### Topological Data Analysis in Neuroscience

- [Clique topology reveals intrinsic geometric structure in neural correlations](https://doi.org/10.1073/pnas.1506407112) - Giusti, Pastalkova, Curto, and Itskov (PNAS, 2015). Simplicial topology of neural correlations.
- [The topology of the directed connectome of the mouse brain](https://doi.org/10.1371/journal.pcbi.1006348) - Reimann et al. (PLOS Computational Biology, 2017). Directed flag complexes in connectomics.
- [Persistent homology analysis of brain artery trees](https://doi.org/10.1214/16-AOAS886) - Bendich et al. (Annals of Applied Statistics, 2016). Example of TDA for neuroanatomy.
- [From topological analyses to functional modeling: the case of hippocampal spatial maps](https://www.frontiersin.org/articles/10.3389/fncom.2020.570934/full) - Dabaghian (Frontiers in Computational Neuroscience, 2020). Topological approaches to hippocampal maps.

### Neural Codes, Receptive Fields, and Convexity

- [What can topology tell us about the neural code?](https://arxiv.org/abs/1605.01963) - Curto. Broad survey of topological neural coding.
- [Cell groups reveal structure of stimulus space](https://doi.org/10.1371/journal.pcbi.1000205) - Curto and Itskov (PLOS Computational Biology, 2008). Topology of place-cell codes.
- [Convex neural codes](https://doi.org/10.1137/15M1038072) - Curto et al. Convexity problem for neural codes.
- [Algebraic signatures of convex and non-convex codes](https://arxiv.org/abs/1709.03527) - Lienkaemper, Shiu, and Woodstock. Algebraic constraints on convex codes.

### Geometry and Manifolds

- [Emergence of a cognitive map by learning to perform vector navigation](https://doi.org/10.1038/s41586-018-0102-6) - Banino et al. (Nature, 2018). Grid-like representations in recurrent networks.
- [Toroidal topology of population activity in grid cells](https://doi.org/10.1038/s41586-021-04268-7) - Gardner et al. (Nature, 2022). Manifold topology of grid-cell activity.
- [Geometry of abstract learned knowledge in the hippocampus](https://doi.org/10.1038/s41586-020-03001-0) - Bellmund et al. (Nature, 2020). Geometry of cognitive maps.
- [Dimensionality reduction for large-scale neural recordings](https://doi.org/10.1038/nn.3776) - Cunningham and Yu (Nature Neuroscience, 2014). Review of latent-variable and manifold methods for neural population data.

### Software

- [GUDHI](https://gudhi.inria.fr/) - Library for computational topology and persistent homology.
- [Ripser.py](https://ripser.scikit-tda.org/) - Fast persistent homology computation in Python.
- [giotto-tda](https://giotto-ai.github.io/gtda-docs/latest/) - Topological machine learning toolkit.
- [Dionysus](https://www.mrzv.org/software/dionysus2/) - Computational topology package.
- [Persim](https://persim.scikit-tda.org/) - Persistence diagram distances, bottleneck/Wasserstein metrics, and plotting.
- [KeplerMapper](https://kepler-mapper.scikit-tda.org/) - Mapper algorithm implementation in Python.

---

## Statistical Neuroscience and Neural Data Analysis

### Books

- [Analysis of Neural Data](https://link.springer.com/book/10.1007/978-1-4614-9602-1) - Robert E. Kass, Uri T. Eden, and Emery N. Brown (Springer, 2014). Statistical foundations for spike trains and neural data.
- [Bayesian Data Analysis](http://www.stat.columbia.edu/~gelman/book/) - Gelman et al. General Bayesian modeling reference.
- [Gaussian Processes for Machine Learning](https://gaussianprocess.org/gpml/) - Rasmussen and Williams. Useful for latent variable models and neural data smoothing.
- [Pattern Recognition and Machine Learning](https://www.microsoft.com/en-us/research/publication/pattern-recognition-machine-learning/) - Christopher M. Bishop. Useful for probabilistic modeling and inference.

### Methods and Articles

- [Likelihood methods for the analysis of neural spike trains](https://doi.org/10.1162/089976603321780317) - Brown, Barbieri, Ventura, Kass, and Frank (Neural Computation, 2002). Point-process GLMs.
- [Generalized linear models for neural encoding and decoding](https://doi.org/10.1152/jn.01026.2007) - Pillow et al. (Journal of Neurophysiology, 2008). GLM methods in systems neuroscience.
- [Extracting low-dimensional neural trajectories from high-dimensional neural population activity](https://doi.org/10.1162/NECO_a_00128) - Cunningham and Yu (Neural Computation, 2014). Dimensionality reduction overview.
- [Gaussian-process factor analysis for low-dimensional single-trial analysis of neural population activity](https://doi.org/10.1162/neco.2009.12-08-909) - Yu et al. (Neural Computation, 2009). GPFA.
- [LFADS: inferring single-trial neural population dynamics using sequential auto-encoders](https://doi.org/10.1038/s41592-018-0109-9) - Pandarinath et al. (Nature Methods, 2018). Deep latent dynamical systems.

### Software

- [Elephant](https://elephant.readthedocs.io/) - Electrophysiology analysis toolkit built on Neo.
- [Neo](https://neo.readthedocs.io/) - Python package for representing electrophysiology data.
- [SpikeInterface](https://spikeinterface.readthedocs.io/) - Spike sorting and extracellular electrophysiology analysis.
- [MNE-Python](https://mne.tools/) - EEG/MEG/iEEG analysis.
- [Nilearn](https://nilearn.github.io/) - Statistical learning for neuroimaging.
- [Nitime](https://nipy.org/nitime/) - Time-series analysis for neuroscience data.
- [PyMC](https://www.pymc.io/) - Probabilistic programming for Bayesian neural data analysis.
- [Stan](https://mc-stan.org/) - Probabilistic programming language for Bayesian inference.
- [scikit-learn](https://scikit-learn.org/) - General machine-learning tools widely used in neural data analysis.

---

## Machine Learning, NeuroAI, and Brain-Inspired Computing

### Books and Courses

- [Deep Learning](https://www.deeplearningbook.org/) - Ian Goodfellow, Yoshua Bengio, and Aaron Courville. Mathematical reference for deep learning.
- [Theoretical Neuroscience](https://www.gatsby.ucl.ac.uk/~dayan/book/) - Useful bridge between normative models and neural computation.
- [Neural Networks and Deep Learning](http://neuralnetworksanddeeplearning.com/) - Michael Nielsen. Accessible online introduction.
- [Neuromatch Academy: Deep Learning](https://deeplearning.neuromatch.io/) - Open course with tutorials connecting deep learning and neuroscience.

### Articles and Reviews

- [Deep learning with spiking neurons: opportunities and challenges](https://doi.org/10.3389/fnins.2018.00774) - Tavanaei et al. (Frontiers in Neuroscience, 2019). Spiking deep learning review.
- [Deep neural networks: a new framework for modeling biological vision and brain information processing](https://doi.org/10.1146/annurev-vision-082114-035447) - Yamins and DiCarlo (Annual Review of Vision Science, 2016). DNNs and vision neuroscience.
- [Task-driven deep neural networks predict neural responses in visual cortex](https://doi.org/10.1523/JNEUROSCI.2856-13.2014) - Yamins et al. (Journal of Neuroscience, 2014). DNNs as encoding models.
- [Using goal-driven deep learning models to understand sensory cortex](https://doi.org/10.1038/nn.4244) - Yamins and DiCarlo (Nature Neuroscience, 2016). Review/perspective.
- [A deep learning framework for neuroscience](https://doi.org/10.1038/s41593-019-0520-2) - Richards et al. (Nature Neuroscience, 2019). Framework linking deep learning and neuroscience.
- [Neuroscience-inspired artificial intelligence](https://doi.org/10.1016/j.neuron.2017.11.010) - Hassabis et al. (Neuron, 2017). Connections between AI and neuroscience.

### Software

- [BrainPy](https://brainpy.readthedocs.io/) - JAX-based framework for brain dynamics programming and brain-inspired computation.
- [Norse](https://github.com/norse/norse) - PyTorch-based library for deep learning with spiking neural networks.
- [snnTorch](https://snntorch.readthedocs.io/) - PyTorch package for spiking neural networks.
- [BindsNET](https://github.com/BindsNET/bindsnet) - Spiking neural networks in PyTorch.
- [Spyx](https://github.com/kmheckel/spyx) - JAX-based spiking neural network tools.
- [Lava](https://lava-nc.org/) - Intel neuromorphic computing framework.
- [Brian2GeNN](https://brian2genn.readthedocs.io/) - GPU acceleration for Brian 2 via GeNN.

---

## Software, Simulators, and Modeling Frameworks

### Biophysical and Spiking Neural Simulators

- [NEURON](https://www.neuronsimulator.org/) - Simulator for neurons and networks of neurons; supports Python, HOC, detailed morphologies, and reaction-diffusion.
- [Brian 2](https://briansimulator.org/) - Python simulator for spiking neural networks using mathematical equation definitions.
- [NEST Simulator](https://www.nest-simulator.org/) - Simulator for large networks of spiking neurons.
- [Arbor](https://arbor-sim.org/) - High-performance multicompartment neural network simulator.
- [GENESIS](http://genesis-sim.org/) - Longstanding platform for realistic neural modeling.
- [MOOSE](https://moose.ncbs.res.in/) - Multiscale Object-Oriented Simulation Environment for neuroscience and systems biology.
- [GeNN](https://genn-team.github.io/genn/) - GPU-enhanced neuronal networks framework.
- [ANNarchy](https://annarchy.github.io/) - Neural simulator for rate-coded and spiking neural networks.
- [CARLsim](https://uci-carl.github.io/CARLsim/) - GPU-accelerated spiking neural network simulator.
- [PyNN](https://neuralensemble.org/PyNN/) - Simulator-independent Python interface for neuronal network simulations.

### Multiscale and Whole-Brain Modeling

- [The Virtual Brain](https://www.thevirtualbrain.org/) - Whole-brain simulation from structural connectivity.
- [NetPyNE](http://netpyne.org/) - High-level Python interface for building and analyzing NEURON network models.
- [Open Source Brain](https://www.opensourcebrain.org/) - Collaborative sharing and simulation of computational neuroscience models.
- [NeuroML](https://neuroml.org/) - XML/LEMS-based model-description standard for neural systems.
- [LFPy](https://lfpy.readthedocs.io/) - Simulation of extracellular potentials from multicompartment neuron models.
- [NESTML](https://nestml.readthedocs.io/) - Modeling language for neuron and synapse models in NEST.

### Dynamical Systems, Symbolic, and Numerical Tools

- [SciPy](https://scipy.org/) - Scientific computing in Python.
- [NumPy](https://numpy.org/) - Numerical arrays and linear algebra.
- [JAX](https://jax.readthedocs.io/) - Differentiable numerical computing, useful for differentiable simulations and NeuroAI.
- [JuliaDynamics](https://juliadynamics.github.io/JuliaDynamics/) - Julia ecosystem for nonlinear dynamics and chaos.
- [DifferentialEquations.jl](https://docs.sciml.ai/DiffEqDocs/stable/) - Differential equation solvers in Julia.
- [AUTO-07p](https://github.com/auto-07p/auto-07p) - Continuation and bifurcation analysis.
- [PyDSTool](https://pydstool.github.io/PyDSTool/) - Dynamical systems modeling and analysis in Python.
- [XPPAUT](http://www.math.pitt.edu/~bard/xpp/xpp.html) - ODE simulation, phase-plane, and bifurcation analysis tool by Bard Ermentrout.

---

## Data Standards, Model Repositories, and Datasets

### Standards and Interoperability

- [Neurodata Without Borders (NWB)](https://nwb.org/) - Data standard and software ecosystem for neurophysiology and behavioral data.
- [Brain Imaging Data Structure (BIDS)](https://bids.neuroimaging.io/) - Standard for organizing neuroimaging and associated data.
- [NeuroML](https://neuroml.org/) - Standard for describing detailed neural models.
- [SONATA](https://github.com/AllenInstitute/sonata) - Data format for representing large-scale neuronal network models and simulations.
- [NineML](https://github.com/INCF/nineml-python) - Network Interchange for Neuroscience Modeling Language.
- [INCF Standards and Best Practices](https://www.incf.org/resources/sbps) - Portfolio of community-endorsed neuroscience standards.

### Model Repositories

- [ModelDB](https://modeldb.science/) - Repository for computational neuroscience models associated with published papers.
- [Open Source Brain](https://www.opensourcebrain.org/) - Platform for sharing, visualizing, and collaboratively developing computational neuroscience models.
- [NeuroML-DB](https://neuroml-db.org/) - Database of NeuroML and related models.
- [BioModels](https://www.ebi.ac.uk/biomodels/) - Repository for computational models of biological systems, useful for signaling and cellular models.

### Datasets and Archives

- [DANDI Archive](https://dandiarchive.org/) - BRAIN Initiative archive for neurophysiology data, including electrophysiology, optophysiology, behavior, and microscopy.
- [CRCNS](https://crcns.org/) - Collaborative Research in Computational Neuroscience data sharing site.
- [Allen Brain Map](https://brain-map.org/) - Allen Institute open datasets, atlases, cell types, connectivity, and modeling resources.
- [Human Connectome Project](https://www.humanconnectome.org/) - Public human connectome data, software, and protocols.
- [OpenNeuro](https://openneuro.org/) - Public BIDS-compatible neuroimaging datasets.
- [NeuroMorpho.Org](https://neuromorpho.org/) - Public repository of digitally reconstructed neurons.
- [NeuroElectro](https://neuroelectro.org/) - Electrophysiological properties of neuron types.
- [MICrONS Explorer](https://www.microns-explorer.org/) - Large-scale cortical connectomics and functional data.
- [International Brain Laboratory](https://www.internationalbrainlab.com/) - Standardized large-scale mouse behavior and electrophysiology datasets.
- [Brain Observatory](https://portal.brain-map.org/explore/circuits/visual-coding) - Allen Institute visual coding datasets.

### Reproducibility and Workflows

- [OpenWorm](https://openworm.org/) - Open project for whole-organism C. elegans modeling.
- [DataLad](https://www.datalad.org/) - Distributed data management for reproducible computational science.
- [ReproNim](https://www.repronim.org/) - Reproducible neuroimaging resources.
- [Boutiques](https://boutiques.github.io/) - Tool description framework for computational pipelines.
- [Nipype](https://nipype.readthedocs.io/) - Workflow engine for neuroimaging pipelines.
- [Pooch](https://www.fatiando.org/pooch/latest/) - Data download/versioning helper for Python projects.

---

## Journals, Conferences, Schools, and Communities

### Journals

- [Journal of Mathematical Neuroscience](https://mathematical-neuroscience.springeropen.com/) - Mathematical modeling and analysis in neuroscience.
- [Journal of Computational Neuroscience](https://link.springer.com/journal/10827) - Computational and theoretical neuroscience.
- [Neural Computation](https://direct.mit.edu/neco) - Computational models, learning theory, and neural information processing.
- [PLOS Computational Biology](https://journals.plos.org/ploscompbiol/) - Computational biology, including computational neuroscience.
- [Frontiers in Computational Neuroscience](https://www.frontiersin.org/journals/computational-neuroscience) - Open-access computational neuroscience journal.
- [Network Neuroscience](https://direct.mit.edu/netn) - MIT Press journal on brain networks.
- [eLife Neuroscience](https://elifesciences.org/subjects/neuroscience) - Broad neuroscience with many computational papers.
- [Nature Computational Science](https://www.nature.com/natcomputsci/) - Computational methods across science, including neuroscience.

### Conferences and Workshops

- [COSYNE](https://www.cosyne.org/) - Computational and Systems Neuroscience.
- [CNS Meeting](https://www.cnsorg.org/cns-annual-meeting) - Organization for Computational Neurosciences annual meeting.
- [NeurIPS](https://neurips.cc/) - Machine learning conference with computational neuroscience and NeuroAI work.
- [ICLR](https://iclr.cc/) - Representation learning conference with neuroscience-inspired ML work.
- [Bernstein Conference](https://bernstein-network.de/en/bernstein-conference/) - Computational neuroscience conference in Europe.
- [INCF Assembly](https://neuroinformatics.incf.org/) - Neuroinformatics and standards community meeting.
- [Society for Neuroscience](https://www.sfn.org/meetings/neuroscience-2024) - Large neuroscience conference with computational/theoretical sessions.
- [Computational and Systems Neuroscience workshops](https://www.cosyne.org/workshops) - Focused workshops after COSYNE.

### Communities and Organizations

- [Organization for Computational Neurosciences](https://www.cnsorg.org/) - International organization for computational neuroscience.
- [INCF](https://www.incf.org/) - International Neuroinformatics Coordinating Facility.
- [Neuromatch](https://neuromatch.io/) - Open education and community for computational neuroscience and machine learning.
- [NeuralEnsemble](https://neuralensemble.org/) - Community around open-source computational neuroscience software.
- [Open Source Brain](https://www.opensourcebrain.org/) - Community for open computational neuroscience models.
- [Theoretical Neuroscience Slack / communities](https://neuromatch.io/) - Neuromatch and related spaces often host theory/modeling discussions.

---

## Adjacent Mathematics

### Dynamical Systems and Bifurcation Theory

- [Nonlinear Dynamics and Chaos](https://www.routledge.com/Nonlinear-Dynamics-and-Chaos-With-Applications-to-Physics-Biology-Chemistry-and-Engineering/Strogatz/p/book/9780813349107) - Steven Strogatz. Standard introductory text.
- [Differential Equations, Dynamical Systems, and an Introduction to Chaos](https://www.sciencedirect.com/book/9780123820105/differential-equations-dynamical-systems-and-an-introduction-to-chaos) - Hirsch, Smale, and Devaney.
- [Elements of Applied Bifurcation Theory](https://link.springer.com/book/10.1007/978-1-4757-3978-7) - Yuri Kuznetsov.
- [Mathematical Physiology](https://link.springer.com/book/10.1007/978-0-387-75847-3) - James Keener and James Sneyd.

### Information Theory, Statistics, and Inference

- [Elements of Information Theory](https://onlinelibrary.wiley.com/doi/book/10.1002/047174882X) - Cover and Thomas.
- [Information Theory, Inference, and Learning Algorithms](https://www.inference.org.uk/itila/book.html) - David MacKay.
- [Pattern Recognition and Machine Learning](https://www.microsoft.com/en-us/research/publication/pattern-recognition-machine-learning/) - Christopher Bishop.
- [Probabilistic Graphical Models](https://mitpress.mit.edu/9780262013192/probabilistic-graphical-models/) - Daphne Koller and Nir Friedman.

### Graph Theory and Network Science

- [Networks: An Introduction](https://global.oup.com/academic/product/networks-9780199206650) - Mark Newman.
- [Network Science](https://networksciencebook.com/) - Albert-László Barabási. Free online book.
- [Dynamical Processes on Complex Networks](https://www.cambridge.org/core/books/dynamical-processes-on-complex-networks/9E8A48D54B34D2B8805D7D7F2062E680) - Alain Barrat, Marc Barthélemy, and Alessandro Vespignani.
- [Networks, Crowds, and Markets](https://www.cs.cornell.edu/home/kleinber/networks-book/) - David Easley and Jon Kleinberg. Free online book.

### Topology, Geometry, and Algebra

- [Computational Topology: An Introduction](https://www.maths.ed.ac.uk/~v1ranick/papers/edelcomp.pdf) - Herbert Edelsbrunner and John Harer.
- [Elementary Applied Topology](https://www.math.upenn.edu/~ghrist/notes.html) - Robert Ghrist. Free notes.
- [Topology and Data](https://www.ams.org/publications/journals/notices/200704/tx070400426p.pdf) - Gunnar Carlsson (Notices of the AMS, 2009). TDA overview.
- [Algebraic Statistics for Computational Biology](https://www.cambridge.org/core/books/algebraic-statistics-for-computational-biology/BEB0FDB5BC0E9D7D5486E8F3908DBD28) - Pachter and Sturmfels, editors. Useful for algebraic/combinatorial methods.
- [Oriented Matroids](https://www.cambridge.org/core/books/oriented-matroids/43C68AC9F92F5D2EF6F920F2C87516CA) - Björner et al. Reference for oriented matroids.

---

## Contributing

Contributions are welcome. Suggested additions should be:

- Relevant to mathematical, theoretical, computational, network, statistical, or multiscale neuroscience.
- Linked to stable official pages, DOI pages, arXiv pages, documentation, or reputable project repositories.
- Briefly described in one sentence.
- Preferably open access or accompanied by accessible documentation/tutorials when possible.

### Suggested Pull Request Format

```markdown
- [Resource Name](https://example.com/) - One-sentence description of why it is useful for mathematical neuroscience.
```



## License

[CC0-1.0](LICENSE)
